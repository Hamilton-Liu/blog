---
title: "\u535a\u5ba2\u642d\u5efa\u8bb0\u5f55"
description: "\u8fd9\u7bc7\u6587\u7ae0\u8bb0\u5f55\u8fd9\u4e2a\u9759\u6001\u535a\u5ba2\u7684\u67b6\u6784\u548c\u66f4\u65b0\u65b9\u5f0f\u3002"
pubDate: 2026-05-15
heroImage: ../../assets/blog-placeholder-1.jpg
---

这个博客使用 Astro 生成静态页面，并通过 GitHub Pages 托管。

日常更新流程很简单：

1. 在 `src/content/blog/` 里新增 Markdown 或 MDX 文件。
2. 写好 frontmatter，包括 `title`、`description` 和 `pubDate`。
3. 本地运行 `npm.cmd run dev` 预览。
4. commit 并 push 到 GitHub，Actions 会自动构建和发布。

静态站点的优点是部署成本低、访问速度快、维护面小。对于个人博客来说，这通常比长期维护一台服务器更合适。
