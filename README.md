# bridgeall-plugin-assets

BridgeAll 各插件装插件时下载的大文件，按“插件/程序-版本”分目录放，并打同名标签。插件清单里写了每个文件的大小和 sha256，本体下载后逐个核对。

## netdisk/syncthing-v2.1.7
- syncthing.exe：Syncthing v2.1.7 Windows amd64，从官方发布 https://github.com/syncthing/syncthing/releases/tag/v2.1.7 的 syncthing-windows-amd64-v2.1.7.zip 解出，未改动。
  - zip SHA-256：3ce7da770f546a8d02b65b2e7ee31f2a3b8b7c3f990ede045590cca4172ecfe1（与官方 sha256sum 清单一致）
  - exe SHA-256：cd9aea20afda2b9bdba5aff2e6ac964ed5c2e741ed4ceb48ad9e1be096ca7891，34,802,944 字节
- 许可证：Mozilla Public License 2.0（LICENSE.txt），作者名单 AUTHORS.txt。源码：https://github.com/syncthing/syncthing/tree/v2.1.7

## remote-desktop/sharp-0.33.5
- 远程桌面插件 Windows x64 截图编码用的 sharp 0.33.5 及其运行依赖，共 64 个文件、20,113,614 字节，按 node_modules 目录结构放，原样取自 npm 包，只删去运行用不到的说明、类型声明和构建源码，没有改动文件内容。
- 包和许可证：sharp 0.33.5（Apache-2.0）；@img/sharp-win32-x64 0.33.5（Apache-2.0 AND LGPL-3.0-or-later，内含 libvips，第三方库许可见包内 README）；color 4.2.3、color-convert 2.0.1、color-name 1.1.4、color-string 1.9.1、is-arrayish 0.3.4、simple-swizzle 0.2.4（MIT）；detect-libc 2.1.2（Apache-2.0）；semver 7.8.6（ISC）。各包 LICENSE 随文件保留。
- 原始来源：https://registry.npmjs.org/ 上的同名同版本包。
