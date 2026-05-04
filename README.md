# 毛选方法论 Skills 合集

> "我们的同志在困难的时候，要看到成绩，要看到光明，要提高我们的勇气。"

从教员思想中提炼的方法论集合，武装 AI 的大脑。不是口号，不是鸡汤，而是可操作的方法论。

## 项目简介

本项目将毛泽东选集中的核心方法论提炼为 AI Agent Skills，使其能够系统性地应用于现代问题分析、决策制定和工作方法指导。

所有 Skills 均基于公开出版物《毛泽东选集》（第一至五卷），仅作为方法论研究与应用，不涉及政治立场。

## Skills 列表

### 核心 Skill

| Skill | 描述 | 触发词 |
|-------|------|--------|
| [qiushi](skills/qiushi/SKILL.md) | 求是总原则 + 九大思想武器 | 实事求是、从实际出发、客观分析 |

### 九大思想武器

| 序号 | 方法 | 核心要义 | 原著出处 |
|------|------|----------|----------|
| 1 | [矛盾分析法](skills/qiushi/SKILL.md) | 识别矛盾、抓住主要矛盾 | 《矛盾论》 |
| 2 | [实践认识论](skills/qiushi/SKILL.md) | 实践→认识→再实践，螺旋上升 | 《实践论》 |
| 3 | [调查研究](skills/qiushi/SKILL.md) | 没有调查就没有发言权 | 《反对本本主义》 |
| 4 | [群众路线](skills/qiushi/SKILL.md) | 从群众中来，到群众中去 | 《关于领导方法的若干问题》 |
| 5 | [批评与自我批评](skills/qiushi/SKILL.md) | 惩前毖后，治病救人 | 《论联合政府》 |
| 6 | [持久战略](skills/qiushi/SKILL.md) | 战略上藐视，战术上重视 | 《论持久战》 |
| 7 | [集中兵力](skills/qiushi/SKILL.md) | 伤其十指不如断其一指 | 《中国革命战争的战略问题》 |
| 8 | [星火燎原](skills/qiushi/SKILL.md) | 建立根据地，不做流寇 | 《星星之火，可以燎原》 |
| 9 | [统筹兼顾](skills/qiushi/SKILL.md) | 调动一切积极因素 | 《论十大关系》 |

### 扩展方法论

| Skill | 描述 | 触发词 |
|-------|------|--------|
| [united-front](skills/united-front/SKILL.md) | 统一战线：团结一切可以团结的力量 | 统一战线、团结、合作、联盟 |
| [independent-self-reliance](skills/independent-self-reliance/SKILL.md) | 独立自主：自力更生，艰苦奋斗 | 独立自主、自力更生、自主可控 |
| [strategic-thinking](skills/strategic-thinking/SKILL.md) | 战略思维：全局观和长远眼光 | 战略思维、全局观、长远眼光 |
| [class-analysis](skills/class-analysis/SKILL.md) | 阶级分析：谁是我们的敌人，谁是我们的朋友 | 阶级分析、敌友分析、利益相关者 |
| [piano-method](skills/piano-method/SKILL.md) | 弹钢琴工作法：统筹全局，抓住重点 | 弹钢琴、统筹兼顾、多任务 |
| [feng-ge-perspective](skills/feng-ge-perspective/SKILL.md) | 峰哥视角：街头社会学家看透社会 | 峰哥、峰哥亡命天涯、用峰哥的方式 |

## 目录结构

```
mao-skills-collection/
├── README.md                    # 项目说明
├── LICENSE                      # MIT 开源许可证
└── skills/                      # Skills 目录
    ├── qiushi/                  # 求是总原则
    │   ├── SKILL.md             # 主 Skill 文件
    │   ├── README.md            # 详细说明
    │   └── original-texts/      # 原著知识库
    │       ├── README.md
    │       ├── vol1/            # 第一卷（1925-1937）
    │       ├── vol2/            # 第二卷（1938-1940）
    │       ├── vol3/            # 第三卷（1941-1945）
    │       ├── vol4/            # 第四卷（1945-1949）
    │       └── vol5/            # 第五卷（1949-1957）
    ├── united-front/            # 统一战线
    ├── independent-self-reliance/ # 独立自主
    ├── strategic-thinking/      # 战略思维
    ├── class-analysis/          # 阶级分析
    ├── piano-method/            # 弹钢琴工作法
    └── feng-ge-perspective/     # 峰哥视角（街头社会学家）
```

## 使用方法

### 在 Trae 中使用

将 `skills/` 目录复制到你的 Trae 项目的 `.trae/skills/` 目录下：

```bash
cp -r skills/ /your-project/.trae/skills/
```

### 在其他 AI Agent 中使用

每个 Skill 都是独立的 Markdown 文件，可以直接导入到支持 SKILL.md 格式的 AI Agent 系统中。

### 触发方式

当用户的问题包含对应 Skill 的触发词时，AI 会自动加载相应的方法论进行分析。

## 方法论结构

```
精神底色：精益求精 · 坚持到底
    ↓
总原则：实事求是
    ↓
第一层·哲学基座：矛盾分析法 · 实践认识论
    ↓
第二层·工作方法：调查研究 · 群众路线 · 批评与自我批评
    ↓
第三层·战略战术：持久战略 · 集中兵力 · 星火燎原 · 统筹兼顾
```

## 原著知识库

本项目包含完整的毛选原著知识库，位于 `skills/qiushi/original-texts/` 目录下，按卷次组织，包含核心语录和方法论索引。

## 示例用法

### 新产品开发

**问题**：我要做一个新产品，但不知道从哪里开始

**分析流程**：
1. **实事求是**：分析资源、能力、市场环境
2. **矛盾分析**：找出当前主要矛盾（产品？市场？资金？）
3. **调查研究**：深入了解目标用户和竞争对手
4. **星火燎原**：从小处着手，先做 MVP
5. **集中兵力**：把有限资源投入到最关键的功能上
6. **实践认识**：快速上线，收集反馈，迭代优化

### 团队管理

**问题**：团队效率不高，怎么办？

**分析流程**：
1. **调查研究**：先了解团队现状
2. **矛盾分析**：找出影响效率的主要矛盾
3. **群众路线**：收集团队成员的意见
4. **弹钢琴**：统筹安排各项工作
5. **批评与自我批评**：定期复盘，持续改进

## 贡献指南

欢迎提交 Issue 和 Pull Request：

- 发现方法论描述不准确的地方
- 补充更多原著引用
- 添加新的应用场景
- 改进触发词和示例

## 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

## 免责声明

本项目仅为方法论研究与应用，所有引用均出自公开出版物《毛泽东选集》，不涉及政治立场表达。

## 参考资料

- 《毛泽东选集》第一至五卷，人民出版社
- 36氪专访：《对话峰哥亡命天涯：不是所有视频都要有意义》
- 腾讯新闻：《从程序员到百万粉丝网红，峰哥回应成名之路》

**项目来源**：[mao-skills-collection](https://github.com/your-username/mao-skills-collection)
