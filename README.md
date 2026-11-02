# CheatBreaker3 Cosmetics

`cosmetics.json` says who wears what. CheatBreaker3 reads it every 5 minutes, so edits show up without a client update.

```json
{
  "Notch": { "cape": "cb_black", "wings": "galaxy" },
  "jeb_": { "cape": "prplz" }
}
```

- Usernames match in any capitalization.
- `cape` and `wings` are optional. Each one names a file in `capes/` or `wings/`, without `.png`.
- To add a cosmetic, add a PNG to one of the folders. Capes use the normal cape layout at any multiple of 64x32, wings use the layout of the ender dragon's texture at any multiple of 256x256.
