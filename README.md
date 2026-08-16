<p align="center">
  <img src="https://img.itch.zone/aW1nLzI2MDkzMjAwLnBuZw==/original/aZRdNz.png" alt="NullA Browser">
</p>

---

Extension store index for [NullA Browser](https://github.com/EPLS-collective/NullA-Browser). Opened from the browser's **Extensions** button.

This repo hosts [`extensions.json`](extensions.json), the list the store page reads, and the `.zip` file for each extension.

## Adding an extension

1. Zip your extension folder (`manifest.json` + its `.js` files).
2. Add the zip to this repo.
3. Add an entry to `extensions.json` with a `download_url` pointing to it.
4. Open a pull request.

**Note:** only `manifest.json`'s `content_scripts` are supported for now, other manifest fields (background scripts, permissions, icons) are ignored.

Questions? Open an issue.
