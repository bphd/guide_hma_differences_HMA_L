# Hide My Applist Guide

This is just a quick guide to hopefully make it a little easier for people new to Hide My Applist.<br>
<i>Often referred to as <b>HMA</b> and will be referenced as such in the majority of this guide.</i>

## Description

In the simplest terms it aims to stop one app detecting a list of other installed apps. Most notably it can often help stop your banking app(s) from detecting if you have any of the apps it considers harmful (ie. is on their apps internal blacklist) - example: the magisk App, or Teamviewer (a bank flagged this as riskware on my device.)

In Android 13 Google has added extra protections to prevent Applist detection abuse by apps but its early days and apps have various ways to bypass Android/Google protections...

## Requirement(s)
- Magisk
  - <i>Preferably a Magisk installation (setup) that passes Play Integrity.</i>
- LSPosed
  - <i>Systemless Xposed framework.</i>

## Download Links
- [LSPosed framework](https://github.com/LSPosed/LSPosed/releases)
- [Hide My Applist (HMA)](https://github.com/Dr-TSNG/Hide-My-Applist/releases)

## Pages (How to)
- [Install LSPosed](Install-LSPosed.md)
- [Install HMA](Install.md)
- [Compare HMA Blacklist vs Whitelist Methods](BlacklistvsWhitelist.md)
- [Configure HMA using the blacklist method](BlackList.md)
- [Configure HMA using the whitelist method](WhiteList.md)
- [Testing HMA](TestHMA.md)
- [Backup and Restore HMA settings](BackupAndRestore.md)

## Notes
<b>This guide is for Hide My Applist v3.x</b>
>1. It is now <b>safe</b> to use the downloader in <i>LSPosed Manager</i> to download/update HMA.<br>
<i>(When this guide was originally posted LSPosed was only serving v2.x builds as v3.x were still in beta)</i><br>

>2. HMA v2.x required a companion magisk module that <b>must be uninstall</b> when updating to HMA v3.x.<br>
<b><i>It's use with v3.x will cause bootloops.</i></b><br>
<i>HMA v3.x <b>does not</b> require a magisk module to achieve its purpose!</i><br>

<b>LSPosed for systemless XPosed framework</b>
>Either Zygisk or Riru version depending on your fork of Magisk.<br>
For most people on the official Magisk builds, this will be the Zygisk build.

>For people on the Magisk Delta build by **huskydg** my current understanding is:
>- if you have **enabled Zygisk** in your Magisk Manager, you should install the **Zygisk** build
>- if you have **disabled Zygisk** in your Magisk Manager, you should install the **Riru** build

<b>Magisk</b>
>Configuration of Magisk is outside the scope of this guide.<br>
<i>A minimal set of instructions have been written for completeness.<br>
See [Magisk Pages](MagiskTOC.md) for Magisk setup and passing Play Integrity.</i><br>

## Known Issue(s)
- [HMA is still detected by x app](KnownIssues.md#hma-is-still-detected-by-x-detection-app)


---

### Reporting Issues Or Providing Feedback On The Guide
Please report any issues you may find with the guide above via the [Issues](https://github.com/mModule/guide_hma/issues) tab.
