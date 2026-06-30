# 我的锻造应用

> 由 [FORGE // 网页锻造工坊](https://forge.example) 生成 · GitHub Action 多端打包

- **入口 URL**: https://example.com
- **Bundle ID**: com.forge.myapp
- **版本**: 1.0.0
- **构建目标**: ios · android · windows · macos · linux
- **壳引擎**: capacitor

## 触发构建

向 `main` 分支推送任意提交（含对 `forge.config.json` 的修改）即会触发 `forge.yml`，
在矩阵 runner 上并行锻造各端产物，产物上传为 artifact，打 tag 时发布到 Release。

## 配置

编辑 `forge.config.json` 调整应用名称、URL、目标端等，提交后自动重新构建。

---
_本仓库由 FORGE 通过 GitHub Personal Access Token 自动创建。_
