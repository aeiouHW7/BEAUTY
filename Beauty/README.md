# 美容院运营 Agent 系统 (AI Beauty Ops)

这是一个基于专业营销技能库（Skills）和品牌底层协议构建的智能运营系统。Agent 将严格遵循调度协议，串联多种专业技能为你的美容院提供线上运营支持。

## 📁 核心项目结构

```
.
├── .agents/
│   ├── steering/                   # 核心指令与调度中心
│   │   ├── agent_orchestrator.md   # [核心] Agent 调度 SOP (启动必读)
│   │   ├── brand_tone.md           # 品牌底层协议与视觉符号
│   │   ├── shop_products.md        # 团购产品、价格与销量数据
│   │   ├── customer_persona_report.# 目标客群画像与痛点地图
│   │   └── marketing-calendar.md   # 年度/周度营销日历
│   └── skills/                     # 专业技能库 (23年经验集成)
│       ├── daily-content-topic-generator # 每日选题生成
│       ├── copywriting              # 转化文案写作
│       ├── social-content           # 社交媒体策略
│       ├── visual-prompt-master     # AI 视觉提示词 (NanoBanana/Kling)
│       └── ... (其他营销技能)
└── README.md
```

## 🛠️ Agent 启动协议 (Execution Protocol)

当你在对话中下达任务时，Agent 会自动执行以下流程：

1.  **Context Sync**: 自动扫描 `.agents/steering/` 目录下的品牌与产品数据。
2.  **Orchestration**: 根据 `agent_orchestrator.md` 决定技能调用链。
3.  **Strategy**: 调用 `customer-research` 和 `marketing-psychology` 确定营销钩子。
4.  **Generation**: 生成包含文案、脚本及 AI 图片/视频提示词的内容方案。

## 🚀 快速开始

### 1. 推广特定项目
> "帮我策划一篇小红书文案，主推咱们那个销冠项目【在逃公主洗清洁】。"

### 2. 生成每日选题
> "根据现在的换季节点和我的营销日历，生成 3 个今日选题建议。"

### 3. AI 视觉生成
> "为这篇文案生成配套的 NanoBanana 海报提示词和一段 Kling 视频脚本。"

## 💡 核心原则
- **专业度**: 坚持 23 年行业沉淀，主理人视角。
- **美学**: 统一暖木色调，光影氛围。
- **转化**: 每一篇文案必须包含心理学钩子和明确到店指令。
