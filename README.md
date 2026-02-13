# Fabubu

<div align="center">
  <img src="ref/Fabubu2.png" alt="Fabubu Logo" width="120" />
  <h1>Fabubu</h1>
  <p>
    <b>新一代跨平台视频自动化发布助手</b>
  </p>
  <p>
    <i>一次创作，全网发布。让内容创作更纯粹，让分发更简单。</i>
  </p>
  <p>
    <a href="https://github.com/AIKnightPanda/Fabubu/releases">
      <img src="https://img.shields.io/github/v/release/AIKnightPanda/Fabubu?style=flat-square&color=blue" alt="GitHub release (latest by date)" />
    </a>
    <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows-lightgrey?style=flat-square" alt="Platform" />
    <img src="https://img.shields.io/github/license/AIKnightPanda/Fabubu?style=flat-square" alt="License" />
  </p>
</div>

---

**Fabubu** 是一款现代化的桌面客户端，专为内容创作者打造。我们保留了强大的多平台上传内核，并为其披上了一层优雅、易用的图形界面 (GUI)。现在，您无需懂代码，无需配置 Python 环境，只需下载安装包，即可体验全自动化的视频分发流程。

## ✨ 核心特性

* **🛡️ 安全可靠**：所有操作均通过模拟浏览器进行，操作过程完全可视化，安全透明，最大程度降低封号风险。
* **👥 多账号管理**：支持多平台多账号登录，账号环境相互隔离，互不干扰，轻松管理您的媒体矩阵。
* **🔑 Cookie 智能续期**：全平台（抖音、B站、小红书、快手、视频号）Cookie 失效自动检测与重新登录，无需手动干预。
* **⏰ 定时发布 & 快捷跳转**：支持设置定时发布任务，并可一键快捷打开各平台网页端，管理效率翻倍。
* **⚡ 极致轻量 & 简单**：安装包体积优化至 60MB 以下，界面简洁直观，无需配置环境，开箱即用。
* **💻 全平台兼容**：完美支持 **macOS** (Intel & Apple Silicon) 和 **Windows** (x64) 系统，随时随地开启创作。

## ⚙️ 运行环境要求 (Requirements)

**本软件依赖 Google Chrome 浏览器来执行自动化任务。**

请确保您的电脑上已安装最新版的 Chrome。如果遇到运行问题（如点击打开按钮无反应），请尝试：

1. 更新 Chrome 到最新版本。
2. 清除浏览器历史缓存。

## 🚀 下载与安装

请查看 [安装说明](release/安装说明.md) 获取详细教程，也可以直接在下方下载安装包：

| 平台 | 最新版本文件名 | 说明 |
| :--- | :--- | :--- |
| **Windows** | [Fabubu_0.1.6_x64-setup.exe](release/Fabubu_0.1.6_x64-setup.exe) | 适用于 Windows 10/11 (x64) |
| **macOS (Intel)** | [Fabubu_0.1.6_x64.dmg](release/Fabubu_0.1.6_x64.dmg) | 适用于 Intel 芯片的 Mac |
| **macOS (M1/M2/M3)** | [Fabubu_0.1.6_aarch64.dmg](release/Fabubu_0.1.6_aarch64.dmg) | 适用于 Apple Silicon 芯片的 Mac |

### 🔧 安装故障排除 (Troubleshooting)

#### 🍎 macOS 用户必读

**问题：提示“'Fabubu' 已损坏，无法打开”**

这是 macOS 的 **Gatekeeper 安全机制**拦截了未签名的个人开发者应用，并非文件真的损坏。

**✅ 解决方法 (终端命令)：**

1. 打开 **终端 (Terminal)** (按 `Cmd + Space` 搜索 "Terminal")。
2. 复制以下命令并粘贴，然后按 **回车**：

   ```bash
   sudo xattr -r -d com.apple.quarantine /Applications/Fabubu.app
   ```

3. 输入开机密码（输入时屏幕不显示字符），按回车确认。
4. 重新打开 App 即可。

#### 🪟 Windows 用户安装

1. 双击运行安装程序。
2. 如遇 **Windows SmartScreen** 提示“已保护你的电脑”：
   * 点击 **“更多信息” (More Info)**。
   * 点击 **“仍要运行” (Run anyway)**。
   *(注：这是无数字签名应用的正常现象)*

## 📜 许可证

本项目采用 [MIT License](LICENSE) 开源许可证。

---

<div align="center">
  <sub>Made with ❤️ by AI 骑士熊猫君</sub>
</div>
