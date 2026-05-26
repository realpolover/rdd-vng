[commits]: https://github.com/latte-soft/rdd/commits
[badges/last-modified]: https://img.shields.io/github/last-commit/latte-soft/rdd?label=Last%20Modifed

> [!CAUTION]
> This is fork of https://github.com/latte-soft/rdd intended to download [Roblox-VNG](https://roblox.vnggames.com) version for Windows/Mac. DO NOT USE THIS TO DOWNLOAD NORMAL ROBLOX.

## RDD-VNG ("Roblox Deployment Downloader-VNG")

[![Last Modified][badges/last-modified]][commits]

Locally download Roblox-VNG deployments (Windows/Mac) directly from your browser!

Hosted officially @ <will be added>

### What is this?

RDD-VNG can assemble plain resources directly from Roblox-VNG's [`setup`](https://setup.rbxcdn.com/vng) S3 storage bucket into a format the user would expect to be able to directly extract/run from. **Everything is fetched locally in your browser, without any additional required server resources!**

### Usage

```txt
[*] USAGE: https://rdd.latte.to/?channel=<CHANNEL_NAME>&binaryType=<BINARY_TYPE>&arch=<ARCH>&version=<VERSION_HASH>

    Binary Types:
    * WindowsPlayer
    * WindowsStudio64
    * MacPlayer
    * MacStudio

    Extra Notes:
    * If `channel` isn't provided, it will default to "LIVE" (the production channel)
```

### Extras

* [JSZip](https://github.com/Stuk/jszip) (Used for `WindowsPlayer`/`WindowsStudio` file extraction/generation)

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
