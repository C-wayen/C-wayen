<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=2F81F7&center=true&vCenter=true&random=false&width=1000&height=120&lines=Hi,+I'm+Wayen+;AI+Application+Developer;Software+Engineer;Building+reliable+AI+systems+with+veteran+discipline&v=1" alt="Typing SVG" />
</a>

<!-- 社交/联系徽章 -->
<p>
  <a href="mailto:wayenoro@gmail.com"><img src="https://img.shields.io/badge/Email-wayenoro%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/C-wayen"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://komarev.com/ghpvc/?username=C-wayen&style=for-the-badge&color=2F81F7" alt="Visitor Count" />
</p>

</div>

---

### 👋 关于我 (About Me)

我是 **Wayen**，一名专注于 **AI 应用开发与全栈工程**的软件工程师。

- 🎓 **教育背景**：广东海洋大学 - 计算机科学与技术（本科，成绩前 11%，二等奖学金）
- 🎖️ **职业经历**：2022-2024 服役。军旅生涯赋予了我极强的抗压能力、纪律性以及解决复杂问题的执行力。
- 💼 **求职意向**：AI 应用开发 / 软件开发工程师（Base：广州）
- 🌱 **技术聚焦**：深耕 RAG 架构设计与 LLM Agent 工作流开发，热衷于把复杂的大模型能力封装为可靠的工程化产品。

---

### 🛠️ 技术栈 (Tech Stack)

<div align="center">

**🧠 AI & 大模型生态**
<br><br>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-FF5722?style=for-the-badge&logo=graphql&logoColor=white" />
<img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Milvus-00A1EA?style=for-the-badge&logo=milvus&logoColor=white" />

<br><br>

**💻 后端 & 数据库 & 工具**
<br><br>
<img src="https://skillicons.dev/icons?i=nodejs,express,java,mysql,postgres,sqlite,docker,git&theme=dark&perline=8" />

<br><br>

**🎨 前端**
<br><br>
<img src="https://skillicons.dev/icons?i=vue,react,js,html,css&theme=dark&perline=5" />

</div>

---

### 🚀 核心项目 (Featured Projects)

<details>
<summary><b>🔍 基于大语言模型的课程知识智能问答系统 (RAG)</b></summary>
<br>

*围绕课程讲义与教材构建可检索知识库，实现带溯源的智能问答。*

- **核心架构**：基于 `FastAPI` + `LangChain` 独立设计开发，结合 `pgvector` 向量数据库。
- **检索优化**：实现 **混合检索**（向量+关键词）与 **Rerank 精排**，通过调优 TOPK 与相似度阈值，大幅提升长尾问题命中率。
- **可信生成**：设计 `文档 ➔ 知识库 ➔ 检索 ➔ 生成` 分层解耦架构，结合 Prompt 工程实现带引用溯源的回答，有效缓解大模型幻觉。
- **模型微调**：规划使用 `LLaMA-Factory` 进行 `QLoRA` 微调，并搭建评测集量化对比 SFT/DPO 前后的生成效果。
</details>

<details>
<summary><b>🤖 自媒体内容运营 Agent (LangGraph 多智能体)</b></summary>
<br>

*面向电商场景的自动化内容生成工作流，显著降低 Token 与时间成本。*

- **工作流编排**：基于 `LangGraph` 构建多阶段生成流，利用 SubGraph 拆解任务，结合 `PostgreSQL Checkpointer` 实现节点级状态回滚与增量重试。
- **极速流式体验**：深度集成 `SSE` 与 `astream_events`，捕获 Token 级实时流，将首字生成时间（TTTF）**降低 60%**。
- **成本优化**：实现多模型动态路由（轻量任务走 Flash / 复杂任务走旗舰模型），结合 Pydantic 强约束，将推理成本**降低 40%**。
- **全链路可观测**：使用 `asyncio` 异步并行与指数退避重试（耗时缩减 70%），接入 `LangSmith` + `structlog` 实现全链路追踪。
</details>

<details>
<summary><b>🌐 GEO 智能内容生成与研究系统 (全栈独立开发)</b></summary>
<br>

*帮助品牌内容在生成式搜索引擎中获得更好引用的全流程工具。*

- **多模型网关**：封装 OpenAI-compatible 标准网关，统一接入通义、DeepSeek、豆包等厂商，实现业务层无感切换。
- **业务闭环**：完成 `任务录入 ➔ 批量生成 ➔ 来源归类 ➔ 二次回测` 的完整链路，前端使用 `ECharts` 可视化。
- **高可用设计**：实现任务容错机制（部分失败不拖垮整批）、僵尸任务自动回收；基于 `Vue3 + Node.js + SQLite` 架构，预留 PostgreSQL 切换接口。
</details>

---

### 📊 GitHub 数据

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=C-wayen&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top Languages" />
</div>

---

<div align="center">
  <i>"Stay disciplined, keep building."</i>
</div>
