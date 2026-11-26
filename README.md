# DreamStream mirrors

Signed catalog hosts for [DreamStream](https://github.com/Prokli81/DreamStream).

The app loads `mirrors.json` at startup **only** with a valid `mirrors.json.sig`
(ECDSA P-256, `keyId` `mirrors-p256-2026-09`) and only if `version` is greater
than the APK/cache version.

## Active sources (v50)

| Key | Site | Primary |
|---|---|---|
| tizam | Tizam | https://adv.tizam.org |
| tizan2 | Tizam-2 | http://46.105.143.221:81 |

Bump `version` and `updatedAt`, sign, then push **both** `mirrors.json` and `mirrors.json.sig` (same bytes that were signed).
