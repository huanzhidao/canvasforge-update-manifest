# CanvasForge Update Manifest

This repository only stores the public update manifest read by CanvasForge.

## File

- `version.json`: the update manifest fetched by the app.

## How To Use

1. Upload the latest CanvasForge installer package to your web disk.
2. Edit `version.json`.
3. Set `version` to the new app version, for example `1.6.3`.
4. Set `downloadUrl` to the web disk share URL.
5. Commit and push this repository.
6. Use the raw URL of `version.json` as `CANVASFORGE_MANUAL_UPDATE_URL` when packaging CanvasForge.

GitHub raw URL example:

```text
https://raw.githubusercontent.com/<your-name>/canvasforge-update-manifest/main/version.json
```

Gitee raw URL example:

```text
Use the Raw button on the version.json page and copy the address.
```
