# Photos folder

The gallery is built from the `galleryPhotos` array in `home.html`
(search for `GALLERY WITH PLACEHOLDER FALLBACK`). Each entry looks like:

```js
{ file: "1.jpg", caption: "Our First Selfie Together 🤳💖" }
```

To add, remove, or reorder photos: add/remove files here in `photos/`
and add/remove matching entries in that array. File extension can be
`.jpg` or `.png` — just make sure it matches what's in the array.

If a listed file is missing, that gallery slot shows a placeholder
instead of a broken image, so it's safe to add entries before the file
itself is uploaded.
