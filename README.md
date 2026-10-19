# wefewe/trae2api-hub

> Trae 国际/国内双区多账号 OpenAI 兼容网关。
> 上游源：`shuishuipingan/trae2api-hub` (MIT)。
> 本仓库包含多架构 GHCR 自动化构建与自动同步工作流。

## 特性
- 镜像发布于 `ghcr.io/wefewe/trae2api-hub:latest`；
- 支持 `linux/amd64` 与 `linux/arm64`；
- 前置本地预发布冒烟测试门禁 (Pre-flight smoke test)，健康后才允许推送；
- 每 2 小时定时同步上游源码；
- 默认端口：`8791`。
