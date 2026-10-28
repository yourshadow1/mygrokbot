# 仓库规则 / Repository Rules

本文件是本仓库的治理说明。所有 bot 在改动本仓库前先读这里。

## 目的

本仓库存放整个 Grok Bot 工作区。项目说明、约定和治理规则都放在这里，由 **Bot Morgan** 统一管理。

## 一个项目 = 一个文件

每个项目只对应 `projects/` 下的**一个**文件：

- 路径：`projects/<kebab-case-name>.md`
- 文件名使用 kebab-case：小写字母、数字、连字符
- 示例：`projects/chenzhou-new-year.md`

不要把一个项目拆成多文件夹、多文件的工程树，除非负责人（owner）之后明确要求。

## 不要随意新增根目录文件或嵌套项目

- 不要在仓库根目录随意新建文件。根目录目前只保留仓库说明（如 `README.md`、`RULES.md`）和 `projects/`。
- 不要在 `projects/` 下为单个项目再建子目录或嵌套文件树。
- 若确有例外，先由 Morgan 批准。

## 变更方式

- 优先通过 Pull Request 提交变更，不要直接往默认分支堆改动。
- 提交说明写清楚：改了什么、为什么改。
- 不要在仓库里放密钥、令牌、凭证或其他秘密。
- 不要编造并不存在的项目文件。

## 谁来管

- **Morgan** 是本仓库的统一管理者。
- 其他 bot 必须遵守本规则。
- 若有人违反规则，Morgan 会点名纠正，或告知负责人。

---

## English (short)

This repository holds the whole Grok Bot workspace. **Morgan** is the unified manager.

- One project = one file under `projects/`, kebab-case, for example `projects/chenzhou-new-year.md`.
- Do not add random root files or nested project trees unless Morgan approves.
- Prefer pull requests. Keep commit messages clear. Do not commit secrets or invented projects.
- Other bots follow these rules. Morgan will call out violations or tell the owner.
