# scoop-bitdm

[![Tests](https://github.com/Henner4746/scoop-bitdm/actions/workflows/ci.yml/badge.svg)](https://github.com/Henner4746/scoop-bitdm/actions/workflows/ci.yml) [![Excavator](https://github.com/Henner4746/scoop-bitdm/actions/workflows/excavator.yml/badge.svg)](https://github.com/Henner4746/scoop-bitdm/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for [BitDM](https://bitdm.net), an end-to-end
encrypted messenger without phone number, e-mail or account.

## Install

```pwsh
scoop bucket add bitdm https://github.com/Henner4746/scoop-bitdm
scoop install bitdm/bitdm
```

`scoop update bitdm` fetches new releases. The Excavator workflow picks them up
from [GitHub releases](https://github.com/Henner4746/BitDM/releases) and checks
each download against the published `.sha256` file.

Your keys live in `%APPDATA%\com.bitdm\bitdm`, outside the Scoop app folder.
Updating or uninstalling BitDM keeps them.

## Other ways to install

Windows installer, Android APK, Linux build and the web app:
[bitdm.net/#download](https://bitdm.net/#download).
