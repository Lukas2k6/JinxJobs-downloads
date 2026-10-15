# JinxJobs downloads

Public distribution files for the JinxJobs Windows desktop preview. Development source is maintained separately in a private repository. This repository contains release notes, packaged downloads, notices and checksums.

[Download v0.1.0-preview.1](https://github.com/Lukas2k6/JinxJobs-downloads/releases/tag/v0.1.0-preview.1) · [JinxJobs website and simulated browser demo](https://jinxjobs.com)

The first download is an **unsigned Windows x64 portable ZIP**. Download the ZIP and its `.sha256` file, extract the complete archive, and open `JinxJobs/JinxJobs.exe`.
Keep its adjacent runtime files and license notices.
Node and npm are not needed to run it. 
There is no installer or automatic update service at this time. (This may change in the future)

Chat/inference is simulated until backend is complete and I get enough money somehow to buy the GPUs to host this locally.

To check the download locally:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\JinxJobs-0.1.0-preview.1-windows-x64-portable.zip'
```

Compare that result to the published `.zip.sha256` value.
Windows may show publisher/reputation warnings for this unsigned preview. 
Do not disable Windows protections unless ur a roadrunner and risktaker. 

No license to third-party artwork is inferred from dependency notices.
