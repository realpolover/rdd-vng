[commits]: https://github.com/realpolover/rdd-vng/commits
[badges/last-modified]: https://img.shields.io/github/last-commit/realpolover/rdd-vng?label=Last%20Modifed

> [!CAUTION]
> This is fork of https://github.com/latte-soft/rdd intended to download [Roblox-VNG](https://roblox.vnggames.com) Player version for Windows. **DO NOT USE THIS TO DOWNLOAD NORMAL ROBLOX.** MacOS and Roblox Studio are not supported.

## RDD-VNG ("Roblox Deployment Downloader-VNG")

[![Last Modified][badges/last-modified]][commits]

Locally download Roblox-VNG Player deployments (Windows) directly from your browser!


### What is this?

RDD-VNG can assemble plain resources directly from Roblox-VNG's [`setup`](https://setup.rbxcdn.com/vng) S3 storage bucket into a format the user would expect to be able to directly extract/run from. **Everything is fetched locally in your browser, without any additional required server resources!**

### How to use?

```txt
[*] How to use: 
1. Download the source code
2. Go to /src folder then open index.html on browser

    Binary Types:
    * WindowsPlayer

    Extra Notes:
    * If `channel` isn't provided, it will default to "LIVE" (the production channel)
```

### Extras

* [JSZip](https://github.com/Stuk/jszip) (Used for `WindowsPlayer` file extraction/generation)

## License

See file: [LICENSE](LICENSE)

```
MIT License

Copyright (c) 2024-2026 Latte Softworks <https://latte.to>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
