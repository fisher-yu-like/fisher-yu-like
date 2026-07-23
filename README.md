# 👋 Hi, I'm 孙彧 (Fisher Yu)

[![GitHub followers](https://img.shields.io/github/followers/fisher-yu-like?style=social)](https://github.com/fisher-yu-like)

**中科大大二 · AI Agent 开发 / AI 产品方向**

独立构建 AI 编程 Agent 框架、多智能体协作系统、工业级 RAG 管线。关注 LLM Agent 工程落地、多框架对比选型、Context Engineering 与 Agent 安全边界。

---

## 🧠 核心项目

### 🔧 [cc_mine](https://github.com/fisher-yu-like/cc_mine) — 从零构建的 AI 编程 Agent

类 Claude Code 的 AI 编程助手，~9,000 行 Python，38 个内置工具，7 维度 59 项 benchmark 评分 **100/100**。

- 「编排者-执行者」双层 Agent 架构 + DAG 并行任务引擎
- 四层自适应上下文压缩，支持超长对话
- Plan Mode 人机协作工作流 + Markdown 双向桥接
- Gatekeeper/Observer 双角色安全 Hook 管线

`Python` `Function Calling` `MCP` `Prompt Engineering` `Multi-Agent`

---

### 📚 [Agentic RAG](https://github.com/fisher-yu-like/tech-docs-rag) — 技术文档智能问答系统

工业级 RAG，自动爬取官方文档 + 混合检索 + 反思式 Agent 管线，杜绝幻觉，封装为 MCP Server 供 AI 编码助手调用。

- LangGraph 三节点状态机 + 自动查询重写
- Qdrant 稠密 + 稀疏双索引 RRF 融合（零外部 API 成本）
- Playwright stealth 绕过 Cloudflare WAF，三层反爬兜底
- OpenAI / DeepSeek / Ollama 多后端一行切换

`Python` `LangGraph` `Qdrant` `FastAPI` `MCP` `Docker`

---

### 🎯 多智能体应用实践

**MemeClaw (梗爪)** — 10+ 平台迷因检索分析系统，先后用 **LangGraph / AutoGen / AgentScope** 三套框架实现完整闭环，对比多智能体框架设计哲学。[链接](https://github.com/fisher-yu-like/meme-claw)

**Paper Agents** — 基于 **Reflexion** 工作流的论文学术助手，arXiv + Semantic Scholar 双源检索，Gradio 全栈 GUI。[链接](https://github.com/fisher-yu-like/paperclaw)

`Python` `LangGraph` `AutoGen` `AgentScope` `Reflexion` `Streamlit` `Gradio`

### [PAVG](https://github.com/hejin001018-gif/PhysGenLoop-)



---

### 📖 论文复现

PyTorch 从零复现 **ResNet** 与 **GCN** 经典论文，覆盖 CNN 与 GNN 两大范式。

`Python` `PyTorch` `CNN` `GNN`

---

## 🛠 技术栈

| 类别 | 技术 |
|------|------|
| **语言** | Python, C/C++, MATLAB, HTML/CSS/JS |
| **Agent 框架** | LangGraph, AutoGen, AgentScope, MCP |
| **LLM 工程** | Function Calling, Prompt Engineering, ReAct, Reflexion |
| **RAG / 检索** | Qdrant, FastEmbed, TF-IDF, RRF |
| **后端 / 前端** | FastAPI, Streamlit, Gradio, MongoDB |
| **工程** | Docker, Git, Playwright, PyTorch, LaTeX |

---

## 📊 GitHub Stats

![Fisher's GitHub stats](https://github-readme-stats.vercel.app/api?username=fisher-yu-like&show_icons=true&theme=default)

---

*Building agents that build software. 中科大大二在读，持续学习中。*

📫 联系我：2055798256@qq.com
