# balamod-registry

`balamod-registry` 是 balamod 的受控中心注册表，用于定义哪些 Balatro 模组可以被 `balamod-cli` 推荐与安装。

## 文件说明

- `mods.json`: 模组元数据列表
- `packs.json`: 模组包（组合）定义
- `categories.json`: 可用分类列表
- `tags.json`: 可用标签列表
- `schemas/mods.schema.json`: `mods.json` 的 JSON Schema
- `schemas/packs.schema.json`: `packs.json` 的 JSON Schema
- `policies/trusted-owners.json`: 受信任仓库所有者名单
- `policies/install-rules.md`: 安装策略说明

## 约束

- 仅允许受控 GitHub owner（当前为 `yuyue1015`）
- 仅存储元数据，不包含模组源码
