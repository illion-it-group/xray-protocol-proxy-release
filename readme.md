# Flexi-Dent Xray Protocol Handler Proxy [RELEASES]

---

### This repository contains only the releases of the [xray-protocol-proxy](https://github.com/illion-it-group/xray-protocol-proxy) repository.

---

> This small program can bypass the new limitations of the Chromium engine (130+) that forbids the usage of non-valid URLs.

## Requirements
- `Windows 7 SP1` or newer
- `.NET Framework 4.7.2`
- any `32bit` or `64bit` CPU
- __Write permission__ for the registry

## Installation
- Place the executable into any accessible folder
- Run the `.exe` manually
    - If a Windows .NET framework installation dialog appears, __follow the installation steps__
- Wait for the protocol handler registration

> For manual installation:
> - Put the `ProtocolProxy.exe` file into the `C:\xray-proxy` folder
> - Run the [manual_registry.reg](manual_registry.reg) registry file.

## Usage
- Enable the `clinic_use_xray_proxy` clinic settings in the FlexiDent system
- Use the xray functionality as usual

## Changelog
Please see [CHANGELOG](changelog.md) for more information on what has changed recently.

## Credits
- [illion-it-group](https://github.com/illion-it-group)

## License
The MIT License (MIT). Please see [License File](license.md) for more information.
