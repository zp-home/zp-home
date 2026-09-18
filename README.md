<h1 align="center">ZP</h1>

<p align="center">
  <b>在 DeepSeek Harness 生态的主线上写代码</b><br>
  <sub>Shipping upstream in the DeepSeek Harness (DSH) ecosystem</sub>
</p>

<p align="center">
  <a href="https://github.com/search?q=type%3Apr+author%3Azp-home+is%3Amerged&type=pullrequests">
    <img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged&label=merged%20PRs&style=flat-square&color=1a7f37&labelColor=24292f&logo=github&logoColor=white" alt="Merged PRs">
  </a>
  <a href="https://github.com/search?q=type%3Apr+author%3Azp-home&type=pullrequests">
    <img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home&label=opened&style=flat-square&color=57606a&labelColor=24292f" alt="Opened PRs">
  </a>
  <a href="https://github.com/search?q=type%3Aissue+author%3Azp-home&type=issues">
    <img src="https://img.shields.io/github/issues-search?query=type%3Aissue%20author%3Azp-home&label=issues&style=flat-square&color=57606a&labelColor=24292f" alt="Issues">
  </a>
  <a href="https://zp-home.github.io">
    <img src="https://img.shields.io/badge/site-zp--home.github.io-24292f?style=flat-square&logo=astro&logoColor=white" alt="Site">
  </a>
</p>

---

### 关于 · About

我的产出主要不在自己的仓库里，而在**上游**——DSH 桌面端、插件市场、插件精选列表这些项目的 PR 队列里。
做的事集中在三块：桌面端（Electron / Windows）的疑难缺陷、插件生态的基础设施（注册表、排行、沙箱），
以及让上面两者在版本变动时不互相踩。

<sub>Most of what I ship lands in other repositories. My work concentrates on desktop-side defects
(Electron, Windows), plugin-ecosystem infrastructure (registry, ranking, sandboxes), and keeping the two
from breaking each other across releases. Every counter on this page is queried live from the GitHub
search API on page load, and covers public repositories only.</sub>

---

### 开源贡献 · Where my PRs land

<sub>下表每个数字都是实时查询 GitHub 搜索 API 得到的，不是写死的。<br>
Every count below is queried live, never hardcoded.</sub>

| 项目 | Stars | 已合并 PR | 主要工作 |
|---|---|---|---|
| **[anywhere-labs/dsh-desktop](https://github.com/anywhere-labs/dsh-desktop)** | ![](https://img.shields.io/github/stars/anywhere-labs/dsh-desktop?style=flat-square&label=&color=24292f) | [![](https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Aanywhere-labs%2Fdsh-desktop&label=&style=flat-square&color=1a7f37)](https://github.com/anywhere-labs/dsh-desktop/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged) | Windows 渲染进程重绘与强杀恢复、控制台代码页下的运行时 shim 解码、beta 通道内核隔离、侧边栏布局<br><sub>Windows repaint & force-kill recovery, runtime-shim decoding across console code pages, beta-channel kernel isolation</sub> |
| **[awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin)** | ![](https://img.shields.io/github/stars/awesome-dsh-plugin/awesome-dsh-plugin?style=flat-square&label=&color=24292f) | [![](https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Aawesome-dsh-plugin%2Fawesome-dsh-plugin&label=&style=flat-square&color=1a7f37)](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged) | 插件精选列表收录<br><sub>Curated-list entries</sub> |
| **[dsh-market](https://github.com/dsh-market/dsh-market)** | ![](https://img.shields.io/github/stars/dsh-market/dsh-market?style=flat-square&label=&color=24292f) | [![](https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Adsh-market%2Fdsh-market&label=&style=flat-square&color=1a7f37)](https://github.com/dsh-market/dsh-market/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged) | 可视化插件市场<br><sub>In-app visual plugin market</sub> |
| **[0xsline/awesome-deepseek-harness](https://github.com/0xsline/awesome-deepseek-harness)** | ![](https://img.shields.io/github/stars/0xsline/awesome-deepseek-harness?style=flat-square&label=&color=24292f) | [![](https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3A0xsline%2Fawesome-deepseek-harness&label=&style=flat-square&color=1a7f37)](https://github.com/0xsline/awesome-deepseek-harness/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged) | 生态工具与基础设施收录<br><sub>Ecosystem tooling entries</sub> |
| **[oh-my-dsh/dsh-plugin-upgrade-skill](https://github.com/oh-my-dsh/dsh-plugin-upgrade-skill)** | ![](https://img.shields.io/github/stars/oh-my-dsh/dsh-plugin-upgrade-skill?style=flat-square&label=&color=24292f) | [![](https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Aoh-my-dsh%2Fdsh-plugin-upgrade-skill&label=&style=flat-square&color=1a7f37)](https://github.com/oh-my-dsh/dsh-plugin-upgrade-skill/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged) | 让插件跟随 DSH 版本自动升级的 skill<br><sub>Auto-upgrading plugins across DSH releases</sub> |
| **[xyingsoft/dsh-chat](https://github.com/xyingsoft/dsh-chat)** | ![](https://img.shields.io/github/stars/xyingsoft/dsh-chat?style=flat-square&label=&color=24292f) | [![](https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Axyingsoft%2Fdsh-chat&label=&style=flat-square&color=1a7f37)](https://github.com/xyingsoft/dsh-chat/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged) | 面向团队与企业组织的 DSH Web 协作平台<br><sub>Team / enterprise DSH collaboration platform</sub> |
| **[zp-home/deepseek-harness-desktop](https://github.com/zp-home/deepseek-harness-desktop)** | ![](https://img.shields.io/github/stars/zp-home/deepseek-harness-desktop?style=flat-square&label=&color=24292f) | [![](https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Azp-home%2Fdeepseek-harness-desktop&label=&style=flat-square&color=57606a)](https://github.com/zp-home/deepseek-harness-desktop/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged) | 自维护的 rc8 分支，Issue 与 PR 由 Opus 5 与 GPT-5.6 协同审核<br><sub>My own rc8 maintenance fork</sub> |

---

### 我维护的项目 · What I maintain

| 项目 | | 做什么 |
|---|---|---|
| **[dsh-recommend](https://github.com/zp-home/dsh-recommend)** | ![](https://img.shields.io/github/stars/zp-home/dsh-recommend?style=flat-square&label=&color=24292f) | 插件透明排行：每日自动抓取 `dsh-plugin` 话题，公开评分模型<br><sub>Daily-crawled, openly-scored plugin leaderboard</sub> |
| **[dsh-weixin-clawbot](https://github.com/zp-home/dsh-weixin-clawbot)** | ![](https://img.shields.io/github/stars/zp-home/dsh-weixin-clawbot?style=flat-square&label=&color=24292f) | 用微信远程操控 DSH，走腾讯官方 ClawBot / iLink 通道<br><sub>Phone-to-DSH control over the official Weixin bot channel</sub> |
| **[dsh-dev-sandbox](https://github.com/zp-home/dsh-dev-sandbox)** | ![](https://img.shields.io/github/stars/zp-home/dsh-dev-sandbox?style=flat-square&label=&color=24292f) | 隔离的 DSH 实例（独立 `DSH_HOME`／端口／profile）挂载在开发的插件<br><sub>Isolated DSH instances for plugin development</sub> |
| **[dsh-plugin-registry](https://github.com/zp-home/dsh-plugin-registry)** | ![](https://img.shields.io/github/stars/zp-home/dsh-plugin-registry?style=flat-square&label=&color=24292f) | GitHub 原生的插件注册表与冲突预警<br><sub>GitHub-native registry with advisory conflict checks</sub> |
| **[dsh-skill-adapter](https://github.com/zp-home/dsh-skill-adapter)** | ![](https://img.shields.io/github/stars/zp-home/dsh-skill-adapter?style=flat-square&label=&color=24292f) | 把 Claude Code / Codex 的 `SKILL.md` 导入或运行时挂载进 DSH<br><sub>Bring Claude Code / Codex skills into DSH</sub> |
| **[kb-graph](https://github.com/zp-home/kb-graph)** | ![](https://img.shields.io/github/stars/zp-home/kb-graph?style=flat-square&label=&color=24292f) | markdown 知识库渲染成 3D 关系图。单 HTML，无后端，数据不出浏览器<br><sub>A knowledge base as a 3D graph — one HTML file, no backend</sub> |
| **[orbit-token-widget](https://github.com/zp-home/orbit-token-widget)** | ![](https://img.shields.io/github/stars/zp-home/orbit-token-widget?style=flat-square&label=&color=24292f) | 桌面常驻 token 用量气泡，火势由实时消耗速率驱动。PowerShell + WinForms<br><sub>Desktop token-usage bubble whose flames scale with burn rate</sub> |

---

### 技术栈 · Stack

![TypeScript](https://img.shields.io/badge/TypeScript-24292f?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-24292f?style=flat-square&logo=javascript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-24292f?style=flat-square&logo=nodedotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-24292f?style=flat-square&logo=electron&logoColor=white)
![Python](https://img.shields.io/badge/Python-24292f?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-24292f?style=flat-square&logo=powershell&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-24292f?style=flat-square&logo=vuedotjs&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-24292f?style=flat-square&logo=astro&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-24292f?style=flat-square&logo=githubactions&logoColor=white)

---

<p align="center"><sub>热爱开发 · 欢迎来 <a href="https://github.com/topics/dsh-plugin">dsh-plugin</a> 话题下逛逛</sub></p>
