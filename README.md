# 站点产物仓库（GitHub Pages）

> 这里是 **https://crui.is-a.dev** 的编译产物：Hexo 生成的静态 HTML、CSS、JS 与图片。
> 由部署脚本自动推送，**请勿手工修改** —— 下一次部署会整体覆盖。

| | |
|---|---|
| 线上站点 | **https://crui.is-a.dev** |
| 源码仓库 | https://github.com/hccc044-bit/blog-source |
| 托管 | GitHub Pages（`main` 分支）+ 自定义域名 `crui.is-a.dev` |

## 这个博客是什么

一个边学边记的运维技术博客，内容围绕 **Linux、RHCSA / RHCE（EX294）、CKA** 展开：

- **学习日志** —— 每天做了什么、卡在哪、怎么解决的，按月归档（[`/study-log/`](https://crui.is-a.dev/study-log/)）
- **学习地图** —— 按能力域组织的知识树：知识点、命令释义、可折叠练习题（[`/maps/rhcsa.html`](https://crui.is-a.dev/maps/rhcsa.html)）
- **实操手册** —— 分区 / LVM / swap / 挂载、软件包与仓库等完整操作流程（[`/maps/labs.html`](https://crui.is-a.dev/maps/labs.html)）

技术栈：Hexo 8.1.1 + Butterfly 5.5.3 + GitHub Pages。

## 想改内容

改**源码仓库**，而不是这里：

```bash
git clone git@github.com:hccc044-bit/blog-source.git
cd blog-source && npm install && npx hexo server   # 本地预览 http://localhost:4000
```

写完之后 `hexo generate` 出静态文件，再推送到本仓库的 `main` 分支，GitHub Pages 会自动更新。

---

<sub>本文件的源在源码仓库的 `source/README.md`，经 `skip_render` 原样复制到这里。要改说明请改那一份。</sub>
