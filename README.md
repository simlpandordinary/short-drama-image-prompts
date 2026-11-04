# Drama Skills · short-drama-image-prompts

> **[short-drama-image-prompts](https://github.com/simlpandordinary/short-drama-image-prompts)** —— 飞书《WorkBuddy 视频系列 · 全技能与提示词总目录》里推荐的开源技能，已拆分为独立仓库分发（一个技能一个仓库）。

| 项 | 内容 |
| - | - |
| 上游仓库 | <https://github.com/zenstory-ai/drama-skills> |
| 上游路径 | `skills/short-drama-image-prompts` |
| 上游协议 | MIT |
| 上游 Star | 3.7k+ |
| 拆分方式 | 仅抽取该技能自身文件，独立可用 |

## 技能说明

为短剧人物、造型、地点、道具和状态编写或修改可直接复制的图片提示词 Markdown。用户提到角色设定图、三视图、参考图、场景板、道具图、风格帧、Look Development、状态变体或局部编辑提示词时使用；不生成图片，也不调用供应商。

## 目录结构

```
├── LICENSE
├── README.upstream.md
├── SKILL.md
├── references/
├── character-and-look.md
├── common-recipe.md
├── edit-and-revision.md
├── location-plate.md
├── look-and-state-variant.md
├── lookdev-frame.md
├── production-sheet-recipes.md
├── prop-plate.md
├── review-and-fixtures.md
└── stage-contract.md
└── agents/
└── openai.yaml
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原件。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/short-drama-image-prompts/`：

```bash
git clone https://github.com/simlpandordinary/short-drama-image-prompts.git ~/.workbuddy/skills/short-drama-image-prompts
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/short-drama-image-prompts> 装成 Skill」。

安装后用自然语言触发，例如「Drama Skills · short-drama-image-prompts」「用 short-drama-image-prompts 帮我处理这个任务」。

## 版权

原始作者与版权归上游仓库 `zenstory-ai/drama-skills` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
