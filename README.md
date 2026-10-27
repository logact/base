# base

本目录镜像 base 仓库（`git@github.com:logact/base.git`）的内容布局，作为 demo 数据：

- `.members/` — agent 模板（class），每个 agent 一个文件夹，字段见 `doc/data-model.md`。模板遵循原型链：`agent/` 是原型根，其余 agent 通过 `prototype` 字段 fork 自它
- `.orgs/` — 组织架构，目录递归即部门层级，按路径索引部门 / 职位
