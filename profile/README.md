## Medianex

A powerful video player, supports various protocols and cloud disks, automatic generation of beautiful poster walls.

> Medianex is not open source,this orgs only store plugins and other depend repo

<details>
<summary>Screenshot</summary>

![](../screenshot/01.png)
![](../screenshot/02.png)
![](../screenshot/03.png)
![](../screenshot/04.png)
![](../screenshot/05.png)
![](../screenshot/06.png)

</details>

## Support Platform And Downloads

[![Static Badge](https://img.shields.io/badge/Macos_arm64_dmg-v0.0.3_beta-blue?style=flat)](https://file.medianex.app/macos/medianex-0.0.3-beta-macos-arm64.dmg)

[![Static Badge](https://img.shields.io/badge/Macos_x86_64_dmg-v0.0.3_beta-blue?style=flat)](https://file.medianex.app/macos/medianex-0.0.3-beta-macos-x86_64.dmg)

[![Static Badge](https://img.shields.io/badge/Windows_x86_64_exe-v0.0.3_beta-blue?style=flat)](https://file.medianex.app/windows/medianex-0.0.3-beta-windows-setup.exe)

[![Static Badge](https://img.shields.io/badge/Linux_x86_64_deb-v0.0.3_beta-blue?style=flat)](https://file.medianex.app/linux/medianex-0.0.3-beta-linux.deb)

![Static Badge](https://img.shields.io/badge/IOS-Coming_Soon-green?style=flat)

![Static Badge](https://img.shields.io/badge/Apple_TV-Coming_Soon-green?style=flat)

![Static Badge](https://img.shields.io/badge/Android-Coming_Soon-green?style=flat)

![Static Badge](https://img.shields.io/badge/Android_TV-Coming_Soon-green?style=flat)

## Future Request OR Report Bug

[Future Request](https://github.com/orgs/medianexapp/discussions/new?category=future-request)

[Report Bug](https://github.com/orgs/medianexapp/discussions/new?category=bug-report)

## Support Plugins

Support various protocols and cloud disk access through plug-in design, plugins base on webassembly

[Plugins](https://github.com/medianexapp/plugins)

## How to devlop a plugin

> Need install [tinygo](https://github.com/tinygo-org/tinygo)  
> Note: tinygo's runtime file must replace this [PR](https://github.com/tinygo-org/tinygo/pull/4875/files)'s files src/runtime/\*.go, or wait next release

1. Install [plugin_api](https://github.com/medianexapp/plugin_api)  
   `go install github.com/medianexapp/plugin_api/cmd/plugin_api@main`
2. Init Plugin Project  
   `plugin_api init example`  
   `cd example`
3. Impl Plugin Method in file `plugin_impl.go`
4. Create your plugin's icon file and change plugin toml config file
5. Build Plugin  
   `make`
6. Install Plugin From Local

## Follow Author

![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/labulakalia)  
![GitHub followers](https://img.shields.io/github/followers/labulakalia)
