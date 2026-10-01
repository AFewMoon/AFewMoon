# AFewMoon

把规则繁杂的现实问题拆成能复算的代码，现在主要写原生 JavaScript 的静态网页应用，也会用 Python 整理资料。

UTC+08:00 · [afewmoon.cnblogs.com](https://afewmoon.cnblogs.com)

---

## 关于我

- 偏好无构建、无依赖的前端：原生 HTML + ES Modules + 一份样式表，打开浏览器就能跑，也方便别人直接读源码。
- 对“把公开的计算方法落成可验证代码”有兴趣。做法是先照着文档把每条规则对到公式上，再用案例跑回归，差多少就记多少。
- 界面和文档同步维护。改了控件名称或行为，说明页跟着改，不留下对不上的描述。
- 业余时间做项目，欢迎在 Issues 里指出算错的地方。

## 技术栈

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

## 精选项目

| 项目 | 语言 | 许可 | 最后更新 |
| --- | --- | --- | --- |
| [railway-fare-calculation](https://github.com/AFewMoon/railway-fare-calculation) | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ![GPL-3.0](https://img.shields.io/github/license/AFewMoon/railway-fare-calculation?style=flat-square) | ![updated](https://img.shields.io/github/last-commit/AFewMoon/railway-fare-calculation?label=updated&style=flat-square) |
| [the-New-World-of-Teyvat](https://github.com/AFewMoon/the-New-World-of-Teyvat) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | ![Other](https://img.shields.io/badge/license-Other-lightgrey?style=flat-square) | ![updated](https://img.shields.io/github/last-commit/AFewMoon/the-New-World-of-Teyvat?label=updated&style=flat-square) |
| [RandomPassword](https://github.com/AFewMoon/RandomPassword) | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ![MIT](https://img.shields.io/github/license/AFewMoon/RandomPassword?style=flat-square) | ![updated](https://img.shields.io/github/last-commit/AFewMoon/RandomPassword?label=updated&style=flat-square) |
| [train-ticket-maker](https://github.com/AFewMoon/train-ticket-maker) | ![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vue.js&logoColor=white) | ![MIT](https://img.shields.io/github/license/AFewMoon/train-ticket-maker?style=flat-square) | ![updated](https://img.shields.io/github/last-commit/AFewMoon/train-ticket-maker?label=updated&style=flat-square) |

### railway-fare-calculation

依据[黄河铁路网](https://jprailfan.com)《铁路标准票价计算方法》《铁路非标准票价计算方法》实现的中国铁路票价模拟计算网页。

- 纯静态站点，无构建、无依赖，原生 HTML + 原生 ES Modules + 单一样式表。
- 引擎是纯函数：`calculate(params)` 只依赖入参，返回总价、分项、明细 `trace` 与警告，不碰 DOM，界面只管渲染。
- 每一步换算、累加、舍入、上浮都展示计算式与中间值，支持单步复制。
- 案例回归 `npm test` 的结果是 通过 10 / 失败 0 / 参考偏差 8。偏差项来自历史票价表的查表基准，属于已知现象，不做强行对齐。
- 在线演示：<https://afewmoon.github.io/railway-fare-calculation/>

### the-New-World-of-Teyvat

《提瓦特新世界》是基于《原神》世界观进行的二次创作与深度世界构建项目。涵盖蒙德、璃月、稻妻、枫丹、须弥、纳塔、至冬七大区域的政治体制、经济体系、历史沿革、地理区划与产业发展等内容，尝试以写实笔触构筑一个逻辑自洽、细节丰满的提瓦特世界。

- 以文字资料为主体，Python 用于内容整理与一致性校验。
- 非官方二次创作，与原权利方无隶属关系。

### RandomPassword

一个纯前端、零依赖、零构建的随机密码生成器。

- 践行无构建、无依赖的前端理念，打开浏览器即可运行。
- 适合需要快速生成安全密码的场景。

### train-ticket-maker

火车票 DIY 生成器（根据提供信息生成火车票用于纪念，本项目不含隐私信息纪念内容，非联网项目）。

- 用于生成纪念版火车票。
- 非联网项目，保障隐私安全。

## 近况

2026 年 10 月，除了持续维护票价计算与提瓦特世界构建项目外，近期整理并上线了一些零依赖的纯前端小工具和趣味项目。2021 年的几个小工具仍保留，未归档。

## 概览

<!-- 统计卡片依赖第三方图片服务（github-readme-stats），加载不出时页面会留空，属正常现象。 -->
<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=AFewMoon&show_icons=true&hide_border=true" alt="GitHub 统计" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AFewMoon&layout=compact&hide_border=true" alt="常用语言" />
</p>

## 联系

- 博客：[afewmoon.cnblogs.com](https://afewmoon.cnblogs.com)
- 有问题或发现算错的地方，直接在对应仓库开 Issue。
