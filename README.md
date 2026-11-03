# 闪记 LumaJot

轻量的便签与待办工具，支持分区管理、多种配色和桌面小组件。

Mac 安装包通过本仓库的 [Releases](https://github.com/miloraJade/LumaJot/releases) 提供。请以各版本说明中的系统要求和测试状态为准。

## 下载 Mac 测试版

**[下载闪记 0.9.5 · macOS DMG（约 6.2 MB）](https://github.com/miloraJade/LumaJot/releases/download/v0.9.5-test/LumaJot-0.9.5-macOS-universal-test.dmg)**

[版本说明与全部附件](https://github.com/miloraJade/LumaJot/releases/tag/v0.9.5-test) · [SHA-256 校验文件](https://github.com/miloraJade/LumaJot/releases/download/v0.9.5-test/SHA256SUMS.txt)

支持 macOS 14.0 及以上，兼容 Apple Silicon 和 Intel Mac。DMG 仅适用于 Mac。

> 当前为测试版，使用 Apple Development 开发签名，尚未完成 Developer ID 分发签名和 Apple 公证，当前 Gatekeeper 评估未通过。其他 Mac 的安装和小组件共享行为仍需验证，安装时可能被系统拦截。请先阅读版本说明。

## 界面预览

以下展示 0.9.5（build 26）的界面，全部使用虚构示例内容。

### iPhone 与 iPad

<table>
  <tr>
    <th>iPhone · 分区总览</th>
    <th>iPhone · 便签详情</th>
    <th>iPad · 四色便签</th>
  </tr>
  <tr>
    <td><img src="docs/screenshots/01-iphone-overview.png" alt="iPhone 分区总览，包含分区卡片、筛选和搜索" width="240"></td>
    <td><img src="docs/screenshots/02-iphone-notes.png" alt="iPhone 便签详情，展示待办、日期和难度信息" width="240"></td>
    <td><img src="docs/screenshots/03-ipad-notes.png" alt="iPad 竖屏双栏，展示绿蓝黄粉四种便签配色" width="320"></td>
  </tr>
</table>

以上三张为模拟器直接截图。

### 小组件

<table>
  <tr>
    <th>分区 · 多张便签</th>
    <th>单张便签</th>
  </tr>
  <tr>
    <td><img src="docs/screenshots/04-widget-board.png" alt="分区小组件示例，多张便签自动分栏和堆叠" width="620"></td>
    <td><img src="docs/screenshots/05-widget-single-note.png" alt="单张便签的小组件样式示例" width="300"></td>
  </tr>
</table>

这两张为当前版本的原生 SwiftUI 小组件渲染预览，非系统桌面截图。

[查看全部高清截图](docs/screenshots)