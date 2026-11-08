# App standards

The shared rulebook for the owner's Windows desktop apps.

| File | What it covers |
| --- | --- |
| [STANDARDS.md](STANDARDS.md) | How an app behaves: files and the Recycle Bin, where data lives, building and releasing, progress, the queue, logs, crashes, GPU, settings, keyboard, words, docs |
| [DESIGN.md](DESIGN.md) | How an app looks: colours, type, sizes, layout, components, the Appearance screen and theme files |

## How to use them

- **New app:** copy both files into the new app's repo, then follow them. Anything specific to that app is changed in its own copies. The app's README.md and PRODUCT.md don't link back here.
- **Existing apps** (Waifu2x Batch, Image Seek, Ginkgo, Nirvash, Media Toolbox, Collection Sorter, Tweet Browser, Lens Library) keep their own design and behaviour. Only bring one in line when the owner asks for that app.
- **Priority:** each topic lives in only one of the two files. If they ever seem to disagree, **STANDARDS.md wins**.
- **Changing a rule:** edit it here (on github.com or in a chat that has this repo), raise the version line at the top of the file, and say what changed in the commit message. Apps already made keep their copies until the owner updates them.

## For Claude in any chat

To work on a new app, or to check one against these rules, attach the repository `Sezekai/app-standards` and read both files first. They're written to be followed literally. Where a rule says "When relevant" or "App chooses", decide with the owner and record the choice in the new app's PRODUCT.md.
