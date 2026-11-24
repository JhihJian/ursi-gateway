# AGENTS.md

本项目 fork 自 <https://github.com/respanai/respan-gateway/>。

## 分支维护策略

- 当前分支（main）根据自身需求独立维护 `apps/` 下的应用实现，可以自由修改。
- 不修改 `crates/` 下的包，保持与上游一致。
- 其余文件（根目录配置、docs、examples 等）跟随上游修改，不在此分支上做本地定制。

同步上游时，保留 `apps/` 的本地实现，其余文件以上游为准。
