# ReVanced Magisk Module

[![CI](https://github.com/chaosoffire-org/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/chaosoffire-org/revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder

Get the [latest CI release](https://github.com/chaosoffire-org/revanced-magisk-module/releases).

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules.

<details><summary><big>Features</big></summary>
<ul>
 <li> Supports all present and future ReVanced apps (including projects implementing the same API)</li>
 <li> Can build Magisk modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimizes APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk app</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>
</details>

also see here [`CONFIG.md`](./CONFIG.md)

## If you are having trouble with the classic mount method of the modules

such as,

- **"Reflash needed"** error after reboots
- **"Suspicious mount detected"** warnings from root detector apps

You can consider using [rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount)

## Building Locally

### On Termux

```console
bash <(curl -sSf https://raw.githubusercontent.com/chaosoffire-org/revanced-magisk-module/main/build-termux.sh)
```

### On Linux

```console
$ git clone https://github.com/chaosoffire-org/revanced-magisk-module --depth 1
$ cd revanced-magisk-module
$ ./build.sh
```

---

## Credits

This project is a fork of [j-hc/revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module) by **j-hc**. Thank you for creating and maintaining the original project!
