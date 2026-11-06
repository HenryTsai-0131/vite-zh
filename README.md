🌏 **繁體中文** ｜ [English 原文](https://github.com/vitejs/vite)

> **非官方翻譯**：本 repo 是 [vitejs/vite](https://github.com/vitejs/vite) README 的中文翻譯，與原作者無關，亦非官方出品。
> 原專案授權：MIT（見 [LICENSE](LICENSE)）。翻譯依據原專案 commit `4835128`（2026-11-06），內容可能落後原文，請以原專案為準。
> 📚 想從零上手？[中文實戰教程](https://vocus.cc/salon/Henry)

---

<p align="center">
  <br>
  <br>
  <a href="https://vite.dev" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://vite.dev/vite-light.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://vite.dev/vite-dark.svg">
      <img alt="vite logo" src="https://vite.dev/vite-dark.svg" height="60">
    </picture>
  </a>
  <br>
  <br>
</p>
<br/>
<p align="center">
  <a href="https://npmjs.com/package/vite"><img src="https://img.shields.io/npm/v/vite.svg" alt="npm package"></a>
  <a href="https://nodejs.org/en/about/previous-releases"><img src="https://img.shields.io/node/v/vite.svg" alt="node compatibility"></a>
  <a href="https://github.com/vitejs/vite/actions/workflows/ci.yml"><img src="https://github.com/vitejs/vite/actions/workflows/ci.yml/badge.svg?branch=main" alt="build status"></a>
  <a href="https://chat.vite.dev"><img src="https://img.shields.io/badge/chat-discord-blue?style=flat&logo=discord" alt="discord chat"></a>
</p>
<br/>

# Vite ⚡

> 下一代前端工具

- 💡 即時啟動伺服器
- ⚡️ 極速的 HMR
- 🛠️ 豐富的功能
- 📦 最佳化的建置
- 🔩 通用的外掛介面
- 🔑 完整型別的 API

Vite（法文「快速」之意，發音為 [`/viːt/`](https://cdn.jsdelivr.net/gh/vitejs/vite@main/docs/public/vite.mp3)，類似 "veet"）是一個建置工具，目標是為現代網頁專案提供更快速、更精簡的開發體驗。它由兩個主要部分組成：

- 一個開發伺服器，在[原生 ES 模組（native ES modules）](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)的基礎上提供[豐富的功能增強](https://vite.dev/guide/features)，例如極其快速的[熱模組替換（Hot Module Replacement，HMR）](https://vite.dev/guide/features#hot-module-replacement)。

- 一個建置指令，使用 [Rolldown](https://rolldown.rs) 打包你的程式碼，並預先設定好，可輸出針對正式環境高度最佳化的靜態資源。

此外，Vite 可透過其 [Plugin API](https://vite.dev/guide/api-plugin.html) 與 [JavaScript API](https://vite.dev/guide/api-javascript.html) 高度擴充，並提供完整的型別支援。

[閱讀文件以了解更多](https://vite.dev)。

## 套件

| Package                                         | Version (click for changelogs)                                                                                                    |
| ----------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| [vite](https://github.com/vitejs/vite/blob/main/packages/vite)                           | [![vite version](https://img.shields.io/npm/v/vite.svg?label=%20)](packages/vite/CHANGELOG.md)                                    |
| [@vitejs/plugin-legacy](https://github.com/vitejs/vite/blob/main/packages/plugin-legacy) | [![plugin-legacy version](https://img.shields.io/npm/v/@vitejs/plugin-legacy.svg?label=%20)](packages/plugin-legacy/CHANGELOG.md) |
| [create-vite](https://github.com/vitejs/vite/blob/main/packages/create-vite)             | [![create-vite version](https://img.shields.io/npm/v/create-vite.svg?label=%20)](packages/create-vite/CHANGELOG.md)               |

## 貢獻

請參閱[貢獻指南](https://github.com/vitejs/vite/blob/main/CONTRIBUTING.md)。

## 授權條款

[MIT](https://github.com/vitejs/vite/blob/main/LICENSE)。

## 贊助者

<p align="center">
  <a target="_blank" href="https://github.com/sponsors/vitejs">
    <img alt="sponsors" src="https://sponsors.vite.dev/sponsors.svg">
  </a>
</p>
