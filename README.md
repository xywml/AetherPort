<a name="中文"></a>
# AetherPort | 云之彼端串口助手

<div align="center">

  [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/xywml/AetherPort/blob/main/LICENSE)
  [![Vue.js](https://img.shields.io/badge/Vue.js-3.x-brightgreen.svg)](https://vuejs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue.svg)](https://www.typescriptlang.org/)
  [![WebSerial](https://img.shields.io/badge/Web%20Serial%20API-Supported-lightgrey.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Serial_API)
</div>

## 📋 概述

`AetherPort` (云之彼端串口助手) 是一款高性能、全功能的在线串口调试工具。它利用现代 Web 技术 (Vue 3, TypeScript, Web Serial API) 提供了卓越的用户体验和强大的功能集，包括实时数据可视化、YMODEM 固件升级、高级指令管理、智能日志监控等。无需安装，开箱即用。

## 🚀 主要特性

### 核心功能
- ✅ **Web Serial API 支持**：直接在浏览器中进行串口通信，无需任何插件或额外驱动。
- ✅ **高性能数据可视化**：
  - ⚡ **实时波形渲染**：支持多达 10 个通道的小端浮点数据实时绘制，帧率高达 60FPS。
  - 🔬 **高级图表控制**：支持图表缩放、平移、时间/数值测量，以及四元数姿态三维可视化。
- ✅ **YMODEM 固件升级**：在线进行设备固件升级，支持文件 CRC16 校验和预复位指令发送。
- ✅ **智能指令管理**：
  - 📝 **自定义指令**：保存、编辑、删除常用指令，支持 JSON/TOML 格式导入导出。
  - 🔄 **循环与定时发送**：支持单次、循环发送，包括高级递增发送模式（针对 HEX 数据）。
  - 🔢 **顺序发送**：可将多个指令组合成序列进行自动发送。

### 数据处理与辅助
- 💡 **数据转换工具**：内置进制转换 (DEC, BIN, OCT, HEX) 和 IEEE 754 浮点数 (32/64位) 格式解析器。
- ⚙️ **智能 HEX 输入**：实时格式化和验证十六进制输入，提供友好的用户体验。
- 📦 **可配置数据分包**：支持固定长度、结束符、超时三种模式，确保数据包完整性。
- 🏷️ **智能日志监控**：自动检测接收数据的日志级别 (DEBUG, INFO, WARN, ERROR) 并进行颜色高亮显示。
- 🌐 **全局背景设置**：自定义背景图片、透明度和模糊度，打造个性化工作界面。

### 性能与体验
- ⚡ **性能监控**：实时显示消息处理速率、字节流速、缓存命中率，提供多种性能预设。
- 🚀 **响应式设计**：界面自适应，完美兼容各种屏幕尺寸，提供一致的用户体验。

## 🐛 问题反馈

如果您在使用过程中遇到任何问题或有改进建议，请通过以下方式联系：

- **GitHub Issues**：[提交新问题](https://github.com/xywml/AetherPort/issues/new)
- **Email**：`xywml@outlook.com`

## 📄 许可证信息

本项目采用 [MIT 许可证](LICENSE)。

**版权所有 © 2025 xywml.com**

---

<div align="center">
  <p><strong>✨ `AetherPort` 旨在提供最先进、最便捷的在线串口调试体验，助力开发者高效工作。</strong></p>
  <p><em>⭐ 如果这个项目对您有帮助，请给个 Star！</em></p>
</div>
