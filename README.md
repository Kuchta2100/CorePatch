# CorePatch
An xposed module for Vector (formerly LSPosed) that disables signature verification in Android.

![GitHub Release (latest by date)](https://img.shields.io/github/v/release/coderstory/CorePatch)
![CRAN/METACRAN](https://img.shields.io/cran/l/devtools)
### Supported Android Versions

This version is only for **Android 9-16.**
<br>![](https://img.shields.io/badge/INFO-Użyaj%20najczesna%20wsji%20aplikacji%20Vector-blue)

## Features

CorePatch offers several key features that allow you to bypass standard Android installation checks.

 **Allow Downgrade**:
<br>Allows you to install an older version of the app, eliminating the error:
<br>![](https://img.shields.io/badge/INFO-INSTALL__FAILED__VERSION__DOWNGRADE-green)

**Disable Hash Verification**:
<br>Allows you to install the app after modifying the APK
<br>![](https://img.shields.io/badge/INFO-ignores%20badge%20hash%20error-green)

**Disable Signature Comparison**:
<br>Allows you to reinstall apps with different signatures

**Disable Exact Signature Match**:
<br>Disables exact signature matching between APKs, allowing installations where each APK fragment has a different signature.
<br>![](https://img.shields.io/badge/WARNING!-Enable%20only%20w%20razie%20needs!-red)

**Use installed signatures**:
<br>Always uses the signatures of already installed apps during installation.
<br>![](https://img.shields.io/badge/WARNING!-It's%20extremely%20safe-red)
<br>![](https://img.shields.io/badge/WARNING!-It's%20absolutely%20necessary-red)

**Bypass**:
<br>Bypasses the list of blocked installations on some devices, e.g., the Nothing Phone.

 **Skip shared user verification**:
<br>Allows installation of apps with a signature different from the shared user.
<br>![](https://img.shields.io/badge/INFO-Wyłącz%20porównanie%20podpisów-blue)
<br>![](https://img.shields.io/badge/musi%20być%20rownież%20włączone-blue)

**Disable package verification agent**:
<br>e.g., Google Play Protect