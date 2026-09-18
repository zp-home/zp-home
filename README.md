<!-- ═══════════════════ 顶部横幅 ═══════════════════ -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=ZP&fontSize=76&fontAlignY=34&fontColor=ffffff&desc=%E4%B8%8A%E6%B8%B8%E6%89%8D%E6%98%AF%E6%88%98%E5%9C%BA%20%C2%B7%20Shipping%20upstream%20in%20the%20DSH%20ecosystem&descAlignY=54&descSize=15&animation=fadeIn" alt="banner">
</p>

<!-- ═══════════════════ 打字机 ═══════════════════ -->
<p align="center">
  <a href="https://github.com/search?q=type%3Apr+author%3Azp-home+is%3Amerged&type=pullrequests">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=2600&pause=900&color=58A6FF&center=true&vCenter=true&width=720&height=45&lines=%E6%88%91%E7%9A%84%E4%BB%A3%E7%A0%81%E5%A4%A7%E9%83%A8%E5%88%86%E8%B7%91%E5%9C%A8%E5%88%AB%E4%BA%BA%E7%9A%84%E4%BB%93%E5%BA%93%E9%87%8C;Most+of+what+I+ship+lands+upstream;Electron+%2F+Windows+%E7%96%91%E9%9A%BE%E6%9D%82%E7%97%87%E4%B8%93%E6%B2%BB;Plugin+infra%3A+registry%2C+ranking%2C+sandboxes;%E6%89%80%E6%9C%89%E6%95%B0%E5%AD%97%E9%83%BD%E6%98%AF%E5%AE%9E%E6%97%B6%E6%9F%A5%E7%9A%84%2C%E4%B8%8D%E6%98%AF%E5%86%99%E6%AD%BB%E7%9A%84" alt="typing">
  </a>
</p>

<!-- ═══════════════════ 实时计数 ═══════════════════ -->
<p align="center">
  <a href="https://github.com/search?q=type%3Apr+author%3Azp-home+is%3Amerged&type=pullrequests">
    <img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged&label=MERGED%20PRs&style=for-the-badge&color=2ea043&labelColor=0d1117&logo=git&logoColor=white" alt="Merged PRs">
  </a>
  <a href="https://github.com/search?q=type%3Apr+author%3Azp-home&type=pullrequests">
    <img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home&label=OPENED&style=for-the-badge&color=1f6feb&labelColor=0d1117&logo=github&logoColor=white" alt="Opened">
  </a>
  <a href="https://github.com/search?q=type%3Aissue+author%3Azp-home&type=issues">
    <img src="https://img.shields.io/github/issues-search?query=type%3Aissue%20author%3Azp-home&label=ISSUES&style=for-the-badge&color=8957e5&labelColor=0d1117&logo=gitbook&logoColor=white" alt="Issues">
  </a>
  <a href="https://zp-home.github.io">
    <img src="https://img.shields.io/badge/SITE-zp--home.github.io-f78166?style=for-the-badge&labelColor=0d1117&logo=astro&logoColor=white" alt="Site">
  </a>
</p>

<!-- ═══════════════════ 奖杯墙 ═══════════════════ -->
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=zp-home&theme=algolia&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="trophies">
</p>

---

## 🛠 我在干什么 · What I do

我的产出主要不在自己的仓库里，而在**上游**——DSH 桌面端、插件市场、插件精选列表的 PR 队列里。
三条主线：**桌面端疑难杂症**（Electron / Windows 那些「只在某台机器上复现」的）、
**插件生态基础设施**（注册表、排行、沙箱）、以及**让前两者在版本变动时不互相踩**。

<sub>Most of what I ship lands in other people's repositories: hard-to-reproduce desktop defects
(Electron, Windows), plugin-ecosystem infrastructure (registry, ranking, sandboxes), and keeping
the two from breaking each other across releases.</sub>

---

## ⚔️ 上游战绩 · Where my PRs land

> 下面每个数字都是**页面加载时实时查 GitHub 搜索 API** 得到的，不是写死的。
> 点任意数字直接跳到该仓库下我的 PR 列表。
> <sub>Every number is queried live on page load — never hardcoded. Click any of them.</sub>

<table>
<tr><th align="left">项目</th><th>Stars</th><th>已合并</th><th align="left">主要工作</th></tr>

<tr><td><b><a href="https://github.com/anywhere-labs/dsh-desktop">anywhere-labs/dsh-desktop</a></b><br><sub>DSH 桌面端主线</sub></td>
<td align="center"><img src="https://img.shields.io/github/stars/anywhere-labs/dsh-desktop?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341"></td>
<td align="center"><a href="https://github.com/anywhere-labs/dsh-desktop/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged"><img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Aanywhere-labs%2Fdsh-desktop&label=&style=flat-square&color=2ea043"></a></td>
<td>Windows 渲染进程重绘与强杀恢复 · 控制台代码页下的运行时 shim 解码 · beta 通道内核隔离 · 侧边栏布局<br><sub>Repaint & force-kill recovery, shim decoding across code pages, beta-channel isolation</sub></td></tr>

<tr><td><b><a href="https://github.com/awesome-dsh-plugin/awesome-dsh-plugin">awesome-dsh-plugin</a></b><br><sub>插件精选列表</sub></td>
<td align="center"><img src="https://img.shields.io/github/stars/awesome-dsh-plugin/awesome-dsh-plugin?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341"></td>
<td align="center"><a href="https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged"><img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Aawesome-dsh-plugin%2Fawesome-dsh-plugin&label=&style=flat-square&color=2ea043"></a></td>
<td>插件收录<br><sub>Curated-list entries</sub></td></tr>

<tr><td><b><a href="https://github.com/dsh-market/dsh-market">dsh-market</a></b><br><sub>可视化插件市场</sub></td>
<td align="center"><img src="https://img.shields.io/github/stars/dsh-market/dsh-market?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341"></td>
<td align="center"><a href="https://github.com/dsh-market/dsh-market/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged"><img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Adsh-market%2Fdsh-market&label=&style=flat-square&color=2ea043"></a></td>
<td>DSH 内置的一键安装插件市场<br><sub>In-app visual plugin market</sub></td></tr>

<tr><td><b><a href="https://github.com/0xsline/awesome-deepseek-harness">awesome-deepseek-harness</a></b><br><sub>生态索引</sub></td>
<td align="center"><img src="https://img.shields.io/github/stars/0xsline/awesome-deepseek-harness?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341"></td>
<td align="center"><a href="https://github.com/0xsline/awesome-deepseek-harness/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged"><img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3A0xsline%2Fawesome-deepseek-harness&label=&style=flat-square&color=2ea043"></a></td>
<td>生态工具与基础设施收录<br><sub>Ecosystem tooling entries</sub></td></tr>

<tr><td><b><a href="https://github.com/oh-my-dsh/dsh-plugin-upgrade-skill">dsh-plugin-upgrade-skill</a></b><br><sub>插件自动升级</sub></td>
<td align="center"><img src="https://img.shields.io/github/stars/oh-my-dsh/dsh-plugin-upgrade-skill?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341"></td>
<td align="center"><a href="https://github.com/oh-my-dsh/dsh-plugin-upgrade-skill/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged"><img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Aoh-my-dsh%2Fdsh-plugin-upgrade-skill&label=&style=flat-square&color=2ea043"></a></td>
<td>让插件跟随 DSH 版本自动升级<br><sub>Auto-upgrading plugins across releases</sub></td></tr>

<tr><td><b><a href="https://github.com/xyingsoft/dsh-chat">xyingsoft/dsh-chat</a></b><br><sub>团队协作平台</sub></td>
<td align="center"><img src="https://img.shields.io/github/stars/xyingsoft/dsh-chat?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341"></td>
<td align="center"><a href="https://github.com/xyingsoft/dsh-chat/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged"><img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Axyingsoft%2Fdsh-chat&label=&style=flat-square&color=2ea043"></a></td>
<td>面向团队与企业组织的 DSH Web 协作平台<br><sub>Team / enterprise collaboration platform</sub></td></tr>

<tr><td><b><a href="https://github.com/zp-home/deepseek-harness-desktop">deepseek-harness-desktop</a></b><br><sub>自维护 rc8 分支</sub></td>
<td align="center"><img src="https://img.shields.io/github/stars/zp-home/deepseek-harness-desktop?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341"></td>
<td align="center"><a href="https://github.com/zp-home/deepseek-harness-desktop/pulls?q=is%3Apr+author%3Azp-home+is%3Amerged"><img src="https://img.shields.io/github/issues-search?query=type%3Apr%20author%3Azp-home%20is%3Amerged%20repo%3Azp-home%2Fdeepseek-harness-desktop&label=&style=flat-square&color=8b949e"></a></td>
<td>Issue 与 PR 由 Opus 5 与 GPT-5.6 协同审核<br><sub>My own maintenance fork</sub></td></tr>
</table>

---

## 🧪 我维护的东西 · What I maintain

<table>
<tr>
<td width="50%" valign="top">

#### 🏆 [dsh-recommend](https://github.com/zp-home/dsh-recommend)
![](https://img.shields.io/github/stars/zp-home/dsh-recommend?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341)
![](https://img.shields.io/badge/JavaScript-f1e05a?style=flat-square&labelColor=0d1117)

插件透明排行。每日自动抓 `dsh-plugin` 话题，**评分模型公开**——不想再有一个说不清怎么排的榜。
<sub>Daily-crawled leaderboard with an openly published scoring model.</sub>

</td>
<td width="50%" valign="top">

#### 📱 [dsh-weixin-clawbot](https://github.com/zp-home/dsh-weixin-clawbot)
![](https://img.shields.io/github/stars/zp-home/dsh-weixin-clawbot?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341)
![](https://img.shields.io/badge/WeChat-07C160?style=flat-square&logo=wechat&logoColor=white&labelColor=0d1117)

躺床上用微信指挥电脑上的 DSH 干活。走腾讯官方 ClawBot / iLink 通道，不是逆向。
<sub>Drive DSH from your phone over the official Weixin bot channel.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📦 [dsh-dev-sandbox](https://github.com/zp-home/dsh-dev-sandbox)
![](https://img.shields.io/github/stars/zp-home/dsh-dev-sandbox?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341)
![](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white&labelColor=0d1117)

开发插件时拉起完全隔离的 DSH 实例（独立 `DSH_HOME` / 端口 / profile），炸了也不影响主环境。
<sub>Isolated DSH instances so a broken plugin can't take your main setup down.</sub>

</td>
<td width="50%" valign="top">

#### 🕸 [kb-graph](https://github.com/zp-home/kb-graph)
![](https://img.shields.io/github/stars/zp-home/kb-graph?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341)
![](https://img.shields.io/badge/single%20HTML-e34c26?style=flat-square&logo=html5&logoColor=white&labelColor=0d1117)

把 markdown 知识库变成可转动的 3D 关系图。**单个 HTML，无后端，数据一个字节都不出浏览器。**
<sub>Your knowledge base as a 3D graph. One file, no backend, nothing leaves the browser.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔥 [orbit-token-widget](https://github.com/zp-home/orbit-token-widget)
![](https://img.shields.io/github/stars/zp-home/orbit-token-widget?style=flat-square&label=&color=e3b341&logo=star&logoColor=e3b341)
![](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white&labelColor=0d1117)

桌面常驻的 token 用量气泡，数字底下烧着一排火焰——**烧得越旺说明你这个月账单越狠**。纯 PowerShell + WinForms。
<sub>A desktop token bubble whose flames scale with your live burn rate.</sub>

</td>
<td width="50%" valign="top">

#### 🔌 [dsh-plugin-registry](https://github.com/zp-home/dsh-plugin-registry) · [dsh-skill-adapter](https://github.com/zp-home/dsh-skill-adapter)
![](https://img.shields.io/github/stars/zp-home/dsh-plugin-registry?style=flat-square&label=registry&color=e3b341)
![](https://img.shields.io/github/stars/zp-home/dsh-skill-adapter?style=flat-square&label=adapter&color=e3b341)

插件名冲突预警的 GitHub 原生注册表；把 Claude Code / Codex 的 `SKILL.md` 直接搬进 DSH。
<sub>A registry with conflict checks, and a bridge for Claude Code / Codex skills.</sub>

</td>
</tr>
</table>

---

## 🧰 家伙事儿 · Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,electron,vue,astro,python,powershell,git,github,githubactions,vscode&theme=dark&perline=12" alt="stack">
</p>

---

## 📈 数据 · Numbers

<p align="center">
  <img height="170" src="https://streak-stats.demolab.com?user=zp-home&theme=tokyonight&hide_border=true&border_radius=8&date_format=Y.n.j" alt="streak">
</p>

<!-- 贪吃蛇由 .github/workflows/snake.yml 生成后存进本仓库 output 分支，不依赖任何第三方图床 -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zp-home/zp-home/output/snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/zp-home/zp-home/output/snake.svg">
    <img alt="贪吃蛇吞噬我的贡献格" src="https://raw.githubusercontent.com/zp-home/zp-home/output/snake.svg">
  </picture>
</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=110&section=footer&text=%E7%83%AD%E7%88%B1%E5%BC%80%E5%8F%91&fontSize=22&fontColor=ffffff&fontAlignY=72&desc=%E6%AC%A2%E8%BF%8E%E6%9D%A5%20dsh-plugin%20%E8%AF%9D%E9%A2%98%E4%B8%8B%E9%80%9B%E9%80%9B&descAlignY=88&descSize=12" alt="footer">
</p>
