# Claude Code 技能指南

> AI产品全链路修炼手册的配套技能文档
> 将76+个Claude Code技能与你的4阶段成长路径精准匹配

---

## 📦 已安装资源一览

| 资源类型 | 数量 | 来源 |
|---------|------|------|
| **Skills** | 76+ | Product-Manager-Skills (46) + seo-geo-claude-skills (20) + claude-seo (19) + Deep-Research-skills (4) |
| **Commands** | 16 | `/write-prd`, `/keyword-research`, `/audit-page`, `/prioritize`, `/strategy`, `/plan-roadmap` 等 |
| **Agents** | 16 | 专业子代理，用于并行执行复杂任务 |

---

## 🗺️ 技能与成长阶段映射

### 阶段1：产品思维 (01-产品思维/)

| 技能/命令 | 用途 | 触发方式 |
|----------|------|---------|
| `/write-prd` | 编写完整PRD文档 | 输入 `/write-prd <功能描述>` |
| `discovery-process` | 全流程用户发现 | "运行发现流程验证这个假设" |
| `jobs-to-be-done` | JTBD框架分析 | "用JTBD分析用户的真实需求" |
| `problem-statement` | 问题陈述定义 | "帮我写一个问题陈述" |
| `proto-persona` | 创建用户画像 | "创建一个用户画像" |
| `customer-journey-map` | 用户旅程地图 | "绘制用户旅程地图" |
| `user-story` | 用户故事编写 | "写用户故事" |
| `user-story-splitting` | 故事拆分 | "拆分这个史诗故事" |
| `user-story-mapping` | 用户故事地图 | "创建用户故事地图" |
| `epic-hypothesis` | 史诗假设 | "将这个项目定义为可测试假设" |
| `opportunity-solution-tree` | 机会解决方案树 | "构建机会解决方案树" |
| `lean-ux-canvas` | Lean UX画布 | "用Lean UX画布梳理这个项目" |
| `problem-framing-canvas` | 问题框架画布 | "用MITRE框架重新定义问题" |
| `press-release` | 新闻稿（亚马逊风格） | "写一个亚马逊风格的新闻稿" |
| `recommendation-canvas` | AI产品评估画布 | "评估这个AI产品想法" |
| `storyboard` | 故事板 | "创建一个6格故事板" |

**使用示例：**
```
/write-prd 为客服团队设计一个智能工单分类系统，要求：
- 自动识别紧急程度
- 支持多语言
- 与现有CRM集成
```

---

### 阶段2：增长与运营 (03-增长与运营/)

| 技能/命令 | 用途 | 触发方式 |
|----------|------|---------|
| `/keyword-research` | 关键词研究 | 输入 `/keyword-research <主题>` |
| `/audit-page` | 页面SEO审计 | 输入 `/audit-page <URL>` |
| `/audit-domain` | 域名权威审计 | 输入 `/audit-domain <域名>` |
| `/write-content` | SEO/GEO内容创作 | 输入 `/write-content <主题> <关键词>` |
| `/discover` | 竞品发现流程 | 输入 `/discover <产品/功能>` |
| `acquisition-channel-advisor` | 获客渠道评估 | "评估这个获客渠道" |
| `seo` | 综合SEO分析 | "分析这个网站的SEO" |
| `seo-geo` | GEO优化 | "优化内容为AI搜索" |
| `seo-content` | 内容质量分析 | "分析这篇内容的E-E-A-T" |
| `seo-google` | Google API分析 | "用Google API分析搜索表现" |
| `seo-dataforseo` | DataForSEO数据 | "获取这个关键词的搜索数据" |
| `seo-plan` | SEO战略规划 | "制定SEO战略计划" |
| `seo-technical` | 技术SEO审计 | "技术SEO审计" |
| `seo-local` | 本地SEO | "分析本地SEO机会" |
| `seo-schema` | Schema标记 | "生成Schema标记" |

**使用示例：**
```
/keyword-research AI客服软件 目标客户是中小企业

/audit-page https://www.yuanjie.ai/pricing

/write-content "AI客服软件选型指南" 关键词："AI客服、智能客服、客服机器人"
```

---

### 阶段3：商业与战略 (05-商业与战略/)

| 技能/命令 | 用途 | 触发方式 |
|----------|------|---------|
| `/strategy` | 产品战略规划 | 输入 `/strategy <产品/业务>` |
| `/plan-roadmap` | 路线图规划 | 输入 `/plan-roadmap` |
| `/prioritize` | 优先级排序 | 输入 `/prioritize` |
| `product-strategy-session` | 产品战略会议 | "运行产品战略会议" |
| `roadmap-planning` | 路线图规划 | "规划产品路线图" |
| `positioning-statement` | 定位声明 | "创建定位声明" |
| `positioning-workshop` | 定位工作坊 | "运行定位工作坊" |
| `tam-sam-som-calculator` | 市场规模计算 | "计算TAM SAM SOM" |
| `finance-based-pricing-advisor` | 定价策略 | "评估这个定价方案" |
| `feature-investment-advisor` | 功能投资评估 | "评估这个功能投资" |
| `saas-economics-efficiency-metrics` | SaaS效率指标 | "分析SaaS单位经济学" |
| `saas-revenue-growth-metrics` | SaaS增长指标 | "计算收入增长指标" |
| `finance-metrics-quickref` | 财务指标速查 | "查询LTV公式" |
| `business-health-diagnostic` | 业务健康诊断 | "诊断业务健康状况" |
| `pestel-analysis` | PESTEL分析 | "做PESTEL分析" |
| `pol-probe` | 生存验证（Proof of Life） | "定义PoL验证" |
| `company-research` | 公司研究 | "研究这家公司" |

**使用示例：**
```
/strategy 元境AI客服产品的未来12个月战略

/plan-roadmap

/prioritize 目前有：智能分类、情绪分析、知识库集成、多语言支持
```

---

### 阶段4：团队与领导力 (06-团队与领导力/)

| 技能/命令 | 用途 | 触发方式 |
|----------|------|---------|
| `/leadership-transition` | 领导力过渡指导 | 输入 `/leadership-transition` |
| `director-readiness-advisor` | 总监准备度评估 | "评估我是否准备好成为总监" |
| `vp-cpo-readiness-advisor` | VP/CPO准备度评估 | "评估我是否准备好成为VP" |
| `altitude-horizon-framework` | 高度-视野框架 | "分析我的高度和视野" |
| `executive-onboarding-playbook` | 高管入职指南 | "创建90天入职计划" |
| `workshop-facilitation` | 工作坊主持 | "主持一个工作坊" |
| `prioritization-advisor` | 优先级框架选择 | "选择正确的优先级框架" |

**使用示例：**
```
/leadership-transition 从产品经理到产品总监
```

---

### 跨阶段：深度研究

| 技能/命令 | 用途 | 触发方式 |
|----------|------|---------|
| `research` | 初步研究大纲 | "研究这个话题" |
| `research-deep` | 深度研究 | "深度研究这些对象" |
| `research-report` | 生成研究报告 | "生成研究报告" |
| `company-research` | 公司研究 | "研究这家公司" |
| `ai-shaped-readiness-advisor` | AI准备度评估 | "评估AI准备度" |
| `context-engineering-advisor` | 上下文工程 | "优化AI上下文工程" |

**使用示例：**
```
research: AI客服市场格局

research-deep: 研究这三家竞品：Zendesk、Intercom、Freshdesk
```

---

## 🚀 Commands 快速参考

### 产品开发
| Command | 描述 |
|---------|------|
| `/write-prd <描述>` | 创建PRD文档 |
| `/plan-roadmap` | 规划产品路线图 |
| `/prioritize` | 优先级排序 |

### SEO与内容
| Command | 描述 |
|---------|------|
| `/keyword-research <主题>` | 关键词研究 |
| `/audit-page <URL>` | 单页审计 |
| `/audit-domain <域名>` | 域名审计 |
| `/write-content <主题> <关键词>` | SEO内容创作 |
| `/discover <产品>` | 竞品发现 |
| `/optimize-meta <URL>` | 优化Meta标签 |
| `/generate-schema <页面类型>` | 生成Schema标记 |
| `/report` | 生成SEO报告 |
| `/check-technical <URL>` | 技术SEO检查 |
| `/setup-alert` | 设置SEO监控 |

### 战略与增长
| Command | 描述 |
|---------|------|
| `/strategy <产品>` | 产品战略 |
| `/leadership-transition` | 领导力过渡 |

---

## 🔄 技能组合配方

### 配方1：新产品启动
```
1. /strategy 新产品方向
2. research-deep 竞品分析
3. jobs-to-be-done 用户需求
4. /write-prd 产品需求文档
5. /plan-roadmap 发布路线图
```

### 配方2：SEO增长优化
```
1. /keyword-research 目标市场
2. /audit-domain 当前网站
3. /write-content 核心关键词
4. seo-geo 优化AI搜索可见性
5. /setup-alert 监控排名
```

### 配方3：业务健康诊断
```
1. business-health-diagnostic 业务健康
2. saas-economics-efficiency-metrics 单位经济
3. finance-metrics-quickref 关键指标
4. /prioritize 改进优先级
```

### 配方4：晋升准备
```
1. director-readiness-advisor 评估当前水平
2. altitude-horizon-framework 理解高度差异
3. /leadership-transition 制定过渡计划
4. executive-onboarding-playbook 准备入职
```

---

## 🛠️ 已配置MCP服务器

除了Skills，你还有以下MCP工具可用：

| MCP | 用途 | 典型场景 |
|-----|------|---------|
| **firecrawl** | 网页抓取、爬虫 | 抓取竞品页面、提取内容 |
| **exa** | AI搜索引擎 | 研究AI相关信息 |
| **context7** | 技术文档查询 | 查询API文档 |
| **playwright** | 浏览器自动化 | 截图、测试页面 |

**组合使用示例：**
```
"用firecrawl抓取竞品的定价页面，然后用/prd-development生成我们的产品定价PRD"

"用exa搜索最新的AI客服趋势，然后用research-deep深度研究前三名"
```

---

## 📝 最佳实践

### 1. 自然语言触发
不需要记住精确的技能名称，用自然语言描述需求：
- ✅ "帮我做一个JTBD分析"
- ✅ "我想了解用户旅程"
- ✅ "这个需要深度研究"

### 2. 分阶段使用
- **早期**：多用发现类技能（discovery, jtbd, persona）
- **中期**：多用规划类技能（prd, roadmap, story）
- **后期**：多用战略类技能（strategy, positioning, metrics）

### 3. 命令 vs Skills
- **Commands** (`/`)：直接执行，快速产出
- **Skills**：对话式，需要多轮交互
- **Agents**：后台执行，适合复杂任务

### 4. 复杂任务分解
大任务分解为小任务串行或并行执行：
```
"先做竞品研究，然后做用户画像，最后写PRD"
```

---

## 🔗 快速链接

- [产品思维阶段 → 01-产品思维/](/01-产品思维/)
- [增长运营阶段 → 03-增长与运营/](/03-增长与运营/)
- [商业战略阶段 → 05-商业与战略/](/05-商业与战略/)
- [团队领导力阶段 → 06-团队与领导力/](/06-团队与领导力/)
- [完整技能列表](https://github.com/kevinten10/Product-Manager-Skills)

---

*最后更新：2026-04-06*
*技能版本：v1.0*
