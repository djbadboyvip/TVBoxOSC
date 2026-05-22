# TVBoxOSC

![Build](https://shields.io/github/actions/workflow/status/o0HalfLife0o/TVBoxOSC/test.yml?branch=master&logo=github&label=Build)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/TVBoxOSC)
[![Download](https://img.shields.io/github/v/release/o0HalfLife0o/TVBoxOSC?color=orange&logoColor=orange&label=Download&logo=DocuSign)](https://github.com/o0HalfLife0o/TVBoxOSC/releases/latest)
[![Total](https://shields.io/github/downloads/o0HalfLife0o/TVBoxOSC/total?logo=Bookmeter&label=Counts&logoColor=yellow&color=yellow)](https://github.com/o0HalfLife0o/TVBoxOSC/releases)

## 📦 依赖项目

本仓库基于以下第三方项目：

- [CatVodTVOfficial/TVBoxOSC](https://github.com/CatVodTVOfficial/TVBoxOSC)
- [q215613905/TVBoxOS](https://github.com/q215613905/TVBoxOS) 
- [takagen99/Box](https://github.com/takagen99/Box) 

---

## 📱 版本说明

| 俗称 | 项目地址 | 主要特点 |
| :--- | :--- | :--- |
| **白盒** (q215613905版) | [q215613905/TVBoxOS](https://github.com/q215613905/TVBoxOS) | 兼容性好，更接近原生实现 |
| **灰盒** (takagen99版 / taka版) | [takagen99/Box](https://github.com/takagen99/Box) | UI美化，支持网速、分辨率显示等 |

---

## ⚙️ 核心区别：解析引擎

TVBox 本身是一个“空壳”，播放能力取决于加载的**视频源（接口/配置地址）**，这些源依靠“爬虫”程序解析视频链接。

- **`...-python.apk`**：内置 **Python 爬虫引擎**，完美支持 **Python、Java、JS** 三种语言编写的视频源。
- **`...-java.apk`**：内置 **Java 爬虫引擎**，仅支持 **Java** 源，**无法解析仅依赖 Python 环境的视频源**。

---

## 📊 对比表格

| 对比维度 | 🐍 Python 版本 | ☕ Java 版本 |
| :--- | :--- | :--- |
| **核心区别** | 内置 Python 爬虫引擎 | 内置 Java 爬虫引擎 |
| **源支持范围** | 全能（Python / Java / JS） | 受限（仅 Java） |
| **兼容性** | 主流智能电视及机顶盒 | 极佳，兼容安卓 4.x 老设备 |
| **功能丰富度** | 更丰富，可访问更多 Python 生态源 | 基本，无法使用纯 Python 源 |
| **性能与稳定性** | 对硬件要求稍高 | 资源占用低，老设备更稳定 |

---

## 💡 如何选择

### ✅ 推荐 `...-python.apk`（全能版）如果：
- 电视盒子/电视为近 5 年购买的主流型号，配置不低
- 希望体验更多视频源，不愿错过任何资源

### ✅ 推荐 `...-java.apk`（兼容版）如果：
- 使用安卓 4.x 等低版本系统、硬件性能有限的老设备
- 追求极致运行流畅度

---

## 📌 备注

- 若使用 Java 版本加载仅提供 Python 源的配置地址，可能出现“**没有可播放的源**”等提示。
- 社区共识：**标注 `py` 的版本支持全部源，想体验更多请安装 Python 版**。
