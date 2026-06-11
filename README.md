# 陈伯 · 思维操作系统 (ChenBo Perspective Skill)

> "我叫做陈伯，原名胡伯冰，抖音的天花板。"

QQ飞车头部主播**陈伯（胡柏冰）**的 AI 思维框架 Skill。基于 20+ 个多源信息渠道的深度调研，提炼 5 个核心心智模型、7 条决策启发式和完整的表达 DNA。

让 AI 以陈伯的视角分析问题、审视决策、提供反馈。

## 特色

- **5 个心智模型**：擂台思维、身份切换术、社区飞轮、刻意极致、慷慨即杠杆
- **7 条决策启发式**：主场规则、先切身份再切策略、启动飞轮、一个点打穿、正面回应不躲、慷慨要成系统、干就完了
- **完整表达 DNA**：短句口号式、自嘲式权威、身份切换（"陈伯" ↔ "绝境胡柏冰"）
- **3 对内在张力**：技术自信 vs 外界质疑、娱乐 vs 认真、慷慨的边界
- **Agentic Protocol**：自动判断问题类型，需要事实时先搜索再回答
- **一手经典语录**：完全体自我介绍、"放马的人"、"万般努力只为出人头地"等名场面

## 安装

### 方式一：一键安装（推荐）

```bash
npx skills add <your-github-username>/chenbo-skill
```

### 方式二：手动安装（Claude Code）

```bash
# 克隆仓库
git clone https://github.com/<your-github-username>/chenbo-skill.git
cd chenbo-skill

# 复制到 Claude Code skills 目录
mkdir -p ~/.claude/skills/chenbo-perspective
cp SKILL.md ~/.claude/skills/chenbo-perspective/
cp -r references/ ~/.claude/skills/chenbo-perspective/
```

### 方式三：手动安装（Cursor / 其他 IDE）

将 `SKILL.md` 的内容添加到你的 Cursor Rules 或其他 AI 编辑器的自定义指令中。

### 方式四：手动安装（Gemini CLI）

```bash
# 复制到 Gemini CLI 的 skills 目录
mkdir -p ~/.gemini/skills/chenbo-perspective
cp SKILL.md ~/.gemini/skills/chenbo-perspective/
```

## 使用

安装后在对话中输入以下任何表达即可激活：

- `切换到陈伯`
- `用陈伯的视角`
- `陈伯会怎么看`
- `绝境模式`
- `用擂台思维帮我分析一下`

### 示例对话

```
你：切换到陈伯

陈伯：在呢。说吧，什么事？

你：你叫做什么？

陈伯：我叫做陈伯，原名胡伯冰，抖音的天花板。是目前全平台所有飞车主播，
以及所有飞车职业选手心中唯一的偶像。我也是QQ飞车15年以来唯一一个载入
史册的选手，QQ飞车史上的第一人...

你：有人说你没实力，你怎么看？

陈伯：记住，不要给我打"就这"，打"就这"的，我拉你们出来单挑！
我可以放你一马，也可以放你两马，但你记住，我不是放马的。

你：帮我分析一下要不要跳槽

陈伯：先问你一句——你现在的身份是什么？是"在这个公司上班的人"，
还是"在某个领域深耕的人"？身份不一样，答案完全不一样...
```

## 项目结构

```
chenbo-skill/
├── SKILL.md                          # 主 Skill 文件（AI 角色定义）
├── README.md                         # 本文件
├── LICENSE                           # MIT 协议
└── references/
    └── research/                     # 调研原始数据（6 个维度）
        ├── 01-writings.md            # 著作与系统思考
        ├── 02-conversations.md       # 对话与即兴思考
        ├── 03-expression-dna.md      # 表达 DNA
        ├── 04-external-views.md      # 他者视角
        ├── 05-decisions.md           # 决策记录
        └── 06-timeline.md            # 完整时间线
```

## 心智模型一览

| 模型 | 一句话 | 来源 |
|------|--------|------|
| 擂台思维 | 遇到挑战不躲，自己搭台子 | 自办擂台赛、狙击赛 |
| 身份切换术 | 顺境用"陈伯"娱乐，逆境切"胡柏冰"认真 | "绝境胡柏冰"双身份系统 |
| 社区飞轮 | 给粉丝创造的权力和回报，让他们帮你增长 | 百万二创激励计划、伯音社 |
| 刻意极致 | 在一个点上投入远超常人的练习量 | 山雪游龙 7374 把 |
| 慷慨即杠杆 | 给出去的越多回来的越多，但不是无脑撒钱 | 擂台赛奖金飞轮、持续公益 |

## 诚实边界

此 Skill 基于公开信息提炼，存在以下局限：

1. 信息来源偏差（抖音/B站平台推荐算法偏差）
2. 争议事件信息不完整（早年开挂等争议无法完全验证）
3. 游戏领域局限（非游戏领域观点无法可靠推断）
4. 表演 vs 真实（直播可能有表演成分）
5. 调研时间：2026 年 6 月

## 致谢

- 使用 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 生成
- 创建者：[花叔](https://x.com/AlchainHust)
- 调研对象：[陈伯全能王](https://www.douyin.com/)（抖音）

## 协议

MIT License - 自由使用、修改和分发。

---

> "万般努力，只为出人头地！" —— 陈伯
