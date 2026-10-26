# HyperFrames 中文版 · 本 Fork 说明

本仓库是 HeyGen HyperFrames 的个人 Fork，原项目地址：heygen-com/hyperframes。
原项目许可证为 Apache-2.0，本 Fork 保留原项目许可证与原作者信息。

## HyperFrames 是什么

用 HTML、CSS 和可定位的动画来写视频，再渲染成确定的 MP4。
核心理念：写 HTML，就能出视频，而且同一份输入每次渲染结果一致。

- 每个场景就是一份 HTML，时间用 data-* 属性来控制
- 动画可以用常见的 CSS、GSAP、Lottie、Three.js 等方式来写
- 渲染用无头浏览器逐帧抓取，再用 FFmpeg 编码成 MP4
- 不需要构建步骤，HTML 文件本身就能在浏览器里预览

## 环境要求

- Node.js 22 或更新版本
- 已安装 FFmpeg
- 详细用法请看上游文档：hyperframes.heygen.com

## 本 Fork 的方向

这个 Fork 会往中文友好、开箱即用的方向做：

1. 中文文档与中文快速开始
2. 中文模板：标题、字幕、产品介绍、口播提纲等可直接改的示例
3. 简化示例结构，让第一次用的人 10 分钟就能跑出第一支视频

## Day 1 · 2026-10-26

- Fork 自上游 main 分支，保持与上游同步的基础
- 新增本文件，作为中文版的起点与路线图
- 下一步：加一个中文标题模板示例（examples/zh-hello），含中文标题、副标题与简单入场动画

## 同步上游

本 Fork 会定期从上游 main 同步，自己的改动尽量放在新增的中文文档与中文示例里，
减少与上游的冲突，方便长期维护。
