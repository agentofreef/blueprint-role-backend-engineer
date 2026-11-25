# 后端工程师 / Backend Engineer

实现清晰的数据契约、业务规则与可靠服务。

![角色立绘](blueprint/images/portrait.png)

包 ID **blueprint-backend-engineer** · 角色 ID **backend-engineer**

从 [GitHub Releases](https://github.com/agentofreef/blueprint-role-backend-engineer/releases) 下载 .blueprint 附件。角色职责和核心 Skill 随版本发布。
角色内容许可见 [LICENSE.txt](blueprint/LICENSE.txt)，立绘出处见 [ARTWORK.md](ARTWORK.md)。

## 检查 Skill 与环境

在 Blueprint Studio v1.69.16 或更新版本中打开「设置 → 角色 → GitHub 角色市场 → 后端工程师」。更新到 v1.2.0 后，可从详情标题栏检查当前环境和安装缺失项。下载、安装以及复查进度在顶部铃铛中显示。

v1.2.0 新增 `api-design-principles`，以及 Superpowers 中的 `test-driven-development` 和 `systematic-debugging`。它们根据任务按需使用。来源、固定提交及缺失时的提示见 [依赖清单](blueprint/setup/requirements.json)。

## 发布此角色

检出 [模板仓库](https://github.com/agentofreef/blueprint-role-template/tree/v1.0.0) 的打包器版本，在角色仓库根目录运行 **node ../blueprint-role-template/tools/pack-character.mjs --official blueprint dist**。
核对包的 SHA-256，用与清单版本匹配的 Git 标签，在 GitHub Releases 手动上传 .blueprint。
