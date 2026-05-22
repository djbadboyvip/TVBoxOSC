# TVBoxOSC

![Build](https://shields.io/github/actions/workflow/status/o0HalfLife0o/TVBoxOSC/test.yml?branch=master&logo=github&label=Build)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/TVBoxOSC)
[![Download](https://img.shields.io/github/v/release/o0HalfLife0o/TVBoxOSC?color=orange&logoColor=orange&label=Download&logo=DocuSign)](https://github.com/o0HalfLife0o/TVBoxOSC/releases/latest) 
[![Total](https://shields.io/github/downloads/o0HalfLife0o/TVBoxOSC/total?logo=Bookmeter&label=Counts&logoColor=yellow&color=yellow)](https://github.com/o0HalfLife0o/TVBoxOSC/releases)

## Credits
This repo relies on the following third-party projects:
- [CatVodTVOfficial/TVBoxOSC](https://github.com/CatVodTVOfficial/TVBoxOSC)
- [q215613905/TVBoxOS](https://github.com/q215613905/TVBoxOS) (Updated: 704cd2658fbcaf38551228cb90bd9f766a0c9e72)
- [takagen99/Box](https://github.com/takagen99/Box) (Updated: 258a5fef61578869ae905ca230bdde9e99fc19a8)
---
项目名称	社区俗称	主要特点
q215613905/TVBoxOS	白盒 / q215613905版	兼容性较好，被认为是更原生的版本。
takagen99/Box	灰盒 / takagen99版 / taka版	UI界面经过了美化，并增加了网速显示、分辨率显示等实用功能。
---
1.⚙️ 核心区别：解析引擎不同
TVBox这类软件本身是一个“空壳”，其播放能力取决于加载的视频源（接口/配置地址），这些源依靠“爬虫”程序解析视频链接。

TVBox...-python.apk：内置了 Python 爬虫引擎。这使得它能完美支持所有使用 Python、Java 和 JS 三种语言编写的视频源。

TVBox...-java.apk：内置的 Java 爬虫引擎。它能支持所有 Java 源，但无法解析仅依赖 Python 环境的视频源。

2.📊 对比表格：快速一览
对比维度	🐍 Python 版本	☕ Java 版本
核心区别	内置 Python 爬虫引擎	内置 Java 爬虫引擎
源支持范围	全能，支持 Python、Java、JS 源	受限，仅支持 Java 源
兼容性	更佳，广泛兼容智能电视及机顶盒。	极佳，甚至能兼容安卓4.x的低版本盒子。
功能丰富度	更丰富，可访问更多依赖Python生态的源	基本，无法使用仅支持Python的源
性能与稳定性	对设备硬件要求稍高	资源占用低，运行更轻量，老设备上更稳定
💡 如何选择？
结合你的情况，可以这样决定：

3.选择 ...-python.apk（全能版），如果你：

使用的电视盒子或电视设备是近5年购买的主流型号，配置不低。

想要体验更多的视频源，不愿意错过任何资源。

选择 ...-java.apk（兼容版），如果你：

使用的是安卓4.x等系统版本较低、硬件性能有限的老款电视盒子或电视。

追求极致的运行流畅度。
