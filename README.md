# Zadi Athan Sounds

Downloadable athan (call-to-prayer) sound pack for the [Zadi](https://github.com/samaneng2002/nurani) Quran app.

Served to the app via jsDelivr:

```
https://cdn.jsdelivr.net/gh/samaneng2002/zadi-athan-sounds@main/manifest.json
https://cdn.jsdelivr.net/gh/samaneng2002/zadi-athan-sounds@main/sounds/<id>.mp3
```

`manifest.json` lists every available sound: its `id`, relative `file` path, size in bytes, and a `displayName` localized for the app's supported languages (`en`, `ar`, `fr`, `bn`, `in`, `ur`).

To add a new athan sound: drop the file in `sounds/`, add an entry to `manifest.json`, commit, and push. jsDelivr's CDN cache may take a few minutes to pick up changes to `main`.
