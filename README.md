# story-skill — 90分精品故事剧本创作官

一个专业的 AI Agent 技能，帮助你创作具备高概念、强钩子、强人物欲望、强戏剧困境、强情绪曲线、强名场面、强传播性的精品故事剧本。

适用于短片、短剧、广告、商业视频、AI视频、美剧风格剧集等。

## 安装

### 方法一：一键安装（推荐）

```bash
git clone https://github.com/YOUR_USERNAME/story-skill.git
cd story-skill
./install.sh
```

脚本会自动检测你使用的 AI 工具并安装到正确位置。

### 方法二：手动安装

根据你使用的平台，将 `story-skill` 目录复制到对应路径：

| 平台 | 安装路径 |
|------|---------|
| Claude Code | `~/.claude/skills/story-skill` |
| Gemini CLI | `~/.gemini/skills/story-skill` |
| GitHub Copilot | `.github/skills/story-skill` |
| Cursor | `.cursor/rules/story-skill` |
| Windsurf | `.windsurf/rules/story-skill` |
| Cline | `.clinerules/story-skill` |
| Codex CLI | `~/.agents/skills/story-skill` |
| Kiro | `.kiro/skills/story-skill` |
| Trae | `.trae/rules/story-skill` |
| Goose | `~/.config/goose/skills/story-skill` |
| OpenCode | `~/.config/opencode/skills/story-skill` |
| Roo Code | `.roo/rules/story-skill` |
| Antigravity | `~/.agents/skills/story-skill` |

## 使用方法

安装后，在任何支持 SKILL.md 的 AI Agent 中输入：

```
/story 一个关于记忆交易的科幻短片
/story 写一个母亲节广告，品牌是某鲜花品牌
/story 帮我创作一个3分钟悬疑短片，主题是信任
/story 短剧剧本：职场女性逆袭
```

也可以自然语言触发：

```
帮我写一个故事剧本
创作一个短片故事
我需要一个广告创意脚本
写个爆款短剧
```

## 输出内容

技能会按以下格式输出完整剧本：

1. **故事核心判断** — 类型、高概念、人物欲望、困境、主题
2. **剧本正文** — 专业格式，含场景、动作、台词、潜台词、声音、情绪变化
3. **名场面提炼** — 1-3 个可传播的名场面
4. **自传播判断** — 共鸣点、讨论点、情绪点分析
5. **100分制自检评分** — 12 个维度评分，总分 ≥ 90 才输出

## 技能结构

```
story-skill/
├── SKILL.md                           # 主技能文件
├── references/
│   ├── scoring-rubric.md              # 100分制评分体系详解
│   ├── emotion-curves.md              # 五种情绪曲线模板
│   ├── structure-templates.md         # 1分钟/3分钟/剧集结构
│   ├── character-design.md            # 人物欲望/缺陷/弧光/潜台词
│   └── iconic-scenes.md              # 名场面设计方法论与范例
├── install.sh                         # 跨平台自动安装脚本
└── README.md                          # 本文件
```

## 许可证

MIT
