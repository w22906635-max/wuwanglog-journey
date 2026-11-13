# 来源与致谢

这个博客不是从零写的：骨架来自一个开源模板，其余能力由一堆开源项目和服务拼起来。下面逐项标明来源与许可。

> 说明：本仓库只保存**文字复盘**，不包含下列任何项目的源码或素材文件。

## 一、起点模板（最重要的一个）

| 项目 | 作者 | 来源 | 许可 | 在本站的作用 |
|---|---|---|---|---|
| **XHBlogs / XinghuisamaBlogs** | heiehiehi（XingHuiSama） | <https://github.com/heiehiehi/XinghuisamaBlogs> | **CC BY-NC 4.0（署名—非商业性使用）** | 博客的前端骨架、页面结构、本地控制台的原型 |

**本站对模板的使用方式**：

- 基于它改造而来，**未用于任何商业用途**（站点无广告、无付费内容）
- 已替换掉原作者的站名、作者名、简介、导航、友链、项目等全部个人化内容
- 后续的公告页、每日拾光、RSS、换域名等都是在此之上的二次改动

如果模板作者认为使用方式不妥，请联系我，我会调整或下线。

## 二、框架与依赖

| 项目 | 来源 | 许可 | 用途 |
|---|---|---|---|
| Next.js | <https://nextjs.org> | MIT | 应用框架（App Router） |
| React | <https://react.dev> | MIT | UI 运行时 |
| Tailwind CSS | <https://tailwindcss.com> | MIT | 样式 |
| gray-matter / remark / rehype / KaTeX | 各自仓库 | MIT | Markdown 解析、公式渲染 |
| lucide-react | <https://lucide.dev> | ISC | 图标 |
| framer-motion | <https://www.framer.com/motion/> | MIT | 动画 |

## 三、服务与平台

| 服务 | 来源 | 说明 |
|---|---|---|
| Vercel | <https://vercel.com> | 托管与自动部署（免费额度） |
| Cloudflare | <https://cloudflare.com> | DNS 托管；域名 `wuwanglog.com` 在 Cloudflare Registrar 注册 |
| GitHub | <https://github.com> | 源码仓库、Actions 定时任务 |
| Giscus | <https://giscus.app> | 基于 GitHub Discussions 的评论系统 |
| Europe PMC | <https://europepmc.org> | 「每日拾光」的文献数据来源（REST API） |
| DeepSeek API | <https://platform.deepseek.com> | 文献摘要的中文改写 |
| 网易云音乐 | <https://music.163.com> | 首页歌单数据（个人歌单） |
| Google Fonts（Geist / Noto Serif SC） | <https://fonts.google.com> | 字体，OFL 许可 |

## 四、内容与素材

| 内容 | 说明 |
|---|---|
| 文章、杂谈、说说、公告 | 站主本人原创 |
| 背景图、照片墙、头像、封面 | 站主自备或 AI 生成 |
| 「令」猫猫助理 | 形象与台词为本站二次创作；角色出自游戏《明日方舟》，版权归**上海鹰角网络**所有，此处仅作个人非商业性同人使用 |
| 友链头像 | 各友站所有，版权归原站 |
| 字体渲染 | Noto Serif SC / Geist，均按 OFL 使用 |

## 五、特别说明

- 本仓库**公开可读**，内容是文字复盘与运维手册，不含站点源码。
- 仓库里的运维文档已做脱敏：本机路径、用户名、密钥路径都替换成了占位符。
- 如果你是基于这份记录搭自己的站，模板请去原作者仓库取，并按 CC BY-NC 4.0 遵守「署名 + 非商业」两条。
