# JinxJobs downloads

Public distribution files for the JinxJobs Windows desktop preview. Development source is maintained separately in a private repository. This repository contains release notes, packaged downloads, notices and checksums.

[Download v0.1.0-preview.1](https://github.com/Lukas2k6/JinxJobs-downloads/releases/tag/v0.1.0-preview.1) · [JinxJobs website and simulated browser demo](https://jinxjobs.com)

The first download is an **unsigned Windows x64 portable ZIP**. Download the ZIP and its `.sha256` file, extract the complete archive, and open `JinxJobs/JinxJobs.exe`. Keep its adjacent runtime files and license notices. Node and npm are not needed to run it. There is no installer or automatic update service.

Chat/inference is simulated. The desktop app can browse a user-selected local project, edit supported text files, attach explicit context and review simulated changes before explicit Save/Apply. Recovery stores unencrypted source code and chat in the current Windows account's application-data JinxJobs directory; deleting the portable folder does not clear that recovery or project backups.

To check the download locally:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\JinxJobs-0.1.0-preview.1-windows-x64-portable.zip'
```

Compare that result to the published `.zip.sha256` value. A checksum detects a mismatch; it is not a code-signing identity. Windows may show publisher/reputation warnings for this unsigned preview. Do not disable Windows protections.

Read the version's release notes for actual verification, known limitations and the source commit identifier. Electron/Chromium and frontend dependency notices are included with each ZIP. No license to third-party artwork is inferred from dependency notices.
