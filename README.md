# jnYuyingMC.github.io/original

> ⚠️ **已弃用 / Deprecated** — 本仓库已归档，不再维护。请访问 [新版官网](https://github.com/jnYuyingMC/jnYuyingMC.github.io)。
>
> This repository is archived and no longer maintained. Visit the [new website](https://github.com/jnYuyingMC/jnYuyingMC.github.io).

大育英帝国 Minecraft 计划官网（2017 原始版）/ Original 2017 website

## 页面 / Pages

- **index.html** — 主页：项目介绍、核心成员、团队架构、时间线、B站视频（Flash）、QQ群二维码
- **photo.html** — 图片库：响应式网格布局，点击新窗口打开
- **vr.html** — VR 全景：弹窗选择源（自建/GitHub/YouTube/720yun）

## 文件结构 / File Structure

```
├── index.html          # 主页面 / Main page
├── photo.html          # 图片库 / Photo gallery
├── vr.html             # VR 全景 / VR panorama
├── vr.js               # VR 源选择逻辑 / VR source selector
├── css/
│   ├── mdui.css        # MDUI 框架 / MDUI framework
│   ├── mdui.min.css    # MDUI 压缩版 / MDUI minified
│   └── timeline.css    # 时间线样式 / Timeline styles
├── js/
│   ├── mdui.js         # MDUI 脚本 / MDUI script
│   └── mdui.min.js     # MDUI 压缩版 / MDUI minified
├── images/             # 背景、Logo、二维码等 / Background, logo, QR
├── photolib/           # 图片库资源 / Photo gallery assets
├── vrview/             # Google VR View 框架及全景资源 / VR View framework
├── fonts/              # 字体 / Fonts
├── icons/              # 图标 / Icons
└── favicon.ico
```

## 技术栈 / Tech Stack

- [MDUI v1](https://www.mdui.org) — Material Design 前端框架
- [Google VR View](https://developers.google.com/vr/concepts/vrview) — VR 全景展示
- Flash — B站视频嵌入

## 注意事项 / Notes

- 2017 年人工编写，所有依赖本地存放 / Manually written in 2017, all dependencies stored locally
- 包含 Flash 代码，现代浏览器可能不支持 / Contains Flash code, may not work in modern browsers
- VR 功能依赖 Google VR View 框架 / VR depends on Google VR View framework
