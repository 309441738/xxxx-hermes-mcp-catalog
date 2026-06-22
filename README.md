# xxxx · Hermes MCP Catalog PR 模板

xxxx —— 由 CruiseSkillBridge 一键发布的MCP。

Hermes **没有**公共 MCP catalog 写 API；收录需向官方仓库提 PR。

## 一键提 PR

1. Fork [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
2. 复制本仓库 `optional-mcps/${artifact.slug}/` 到 fork 的 `optional-mcps/`
3. 打开 PR（可参考 `PR_TEMPLATE.md`）

合并后用户可：

```bash
hermes mcp catalog
hermes mcp install xxxx
```

由 [CruiseSkillBridge](https://cruiseskillbridge.com) 生成。
