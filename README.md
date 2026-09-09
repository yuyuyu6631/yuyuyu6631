<div align="center">

# 👨‍💻 秦宇 | QIN YU

<a href="https://yuyuyu6631.github.io/qinyu-resume/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=2563EB&center=true&vCenter=true&width=660&lines=%E6%B5%8B%E8%AF%95%E5%BC%80%E5%8F%91%E5%B7%A5%E7%A8%8B%E5%B8%88+(SDET)+%7C+Test+Development+Engineer;AI+%E5%BA%94%E7%94%A8%E6%B5%8B%E8%AF%95+%C2%B7+%E8%87%AA%E5%8A%A8%E5%8C%96+%C2%B7+%E5%8D%8A%E5%AF%BC%E4%BD%93+ATE+%E4%B8%8A%E4%BD%8D%E6%9C%BA%E6%B5%8B%E8%AF%95;Focusing+on+AI+Testing%2C+Automation%2C+ATE+%26+Desktop" alt="Typing SVG" />
</a>

<p align="center">
  <a href="https://yuyuyu6631.github.io/qinyu-resume/">
    <img src="https://img.shields.io/badge/⚡_个人品牌简历网站-qinyu--resume-0284c7?style=for-the-badge&logo=vercel&logoColor=white" alt="Online Resume" />
  </a>
  <a href="mailto:1642732247@qq.com">
    <img src="https://img.shields.io/badge/📧_联系邮箱-1642732247@qq.com-10b981?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/📍_期望城市-深圳%20%7C%20广州-f59e0b?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
</p>

---

</div>

## 💡 关于我 (About Me)

你好！我是**秦宇 (QIN YU)**，软件工程专业背景，专注高可靠性软件与算法评测的**测试开发工程师 (SDET)**。

- 🎯 **求职意向**：测试开发工程师 / 软件测试工程师 / AI 专项测试工程师（期望地：**深圳 / 广州**）
- 🔬 **半导体 ATE 上位机实战**：就职于**长川科技**，主导车规级功放/功耗芯片测试机（ATE）上位机测试，深入覆盖核心指令下发、测控单元参数配置与数据回传链路，搭建长时连续运行压测与 UI 自动化体系。
- 🤖 **AI 与大模型专项评测**：在**零壹视界**期间主导中金点睛等 Text-to-SQL 复杂评测项目，独创**「五维验证法」**，运用 Python (Pandas/NumPy) 攻克大模型生成非结构化数据难以量化评估与断言的痛点。
- 🚀 **自动化测试与工具研发**：深入掌握 **Python + Pytest + Playwright / Selenium + Allure**，自研小程序端到端自动化引擎与测试辅助套件，擅长结合接口返回、SQL 与日志快速根因定位。
- 🐳 **DevOps 与全栈工程能力**：从 0 到 1 落地 Jenkins CI/CD 自动构建与定时巡检流水线，独立开发 Next.js 15 单一数据源驱动的个人品牌工程。

---

## 📊 质量度量与实战证据链 (Quantified Proof & Metrics)

```
┌──────────────────┐   ┌──────────────────┐   ┌──────────────────┐   ┌──────────────────┐
│   1000+ 用例基线  │   │   50+ 接口自动巡检 │   │   72h+ 连续长时压测│   │   5 维评测闭环   │
│ 持续维护核心回归基线 │   │ 无人值守定时触发告警 │   │ 芯片ATE设备稳定性保障│   │ Text-to-SQL精度量化 │
└──────────────────┘   └──────────────────┘   └──────────────────┘   └──────────────────┘
```

- 📈 **1000+ 核心用例回归基线**：在零壹视界期间覆盖 4 条产品线（数据智能体、企业写作、低代码与智能体平台），核心路径与异常分支 100% 覆盖。
- ⚡ **50+ 核心 API 自动化巡检**：基于 MeterSphere + Jenkins 搭建核心接口无人值守定时巡检，动态参数抽取、多级断言与钉钉告警全链打通。
- 🔬 **72h+ ATE 稳定性长时连续压测**：长川科技车规级芯片测试机长时间高负载运行验证，持续监测内存占用、句柄泄漏与响应延迟。
- 🛡️ **五维验证法（Text-to-SQL 专项）**：建立 `用户问题 ──> SQL 生成 ──> 查询结果 ──> 页面展示 ──> 业务口径` 严密证据链，实现模型偏差可定位、可复现、可回归。
- 💻 **100% 单一数据源（Single Source of Truth）工程实践**：以 `resume.json` 单一数据源驱动响应式 Web 端、ATS 规范 PDF、DOCX 与 Markdown 多端资产自动化生成。

---

## 🔬 AI 应用测试工程流水线 (AI Testing Pipeline)

针对大模型应用输出不确定、工具调用偏差与业务口径脱节的行业痛点，总结出标准化的 AI 专项评测闭环流程：

```
[ 用户意图与参数输入 ]
       │
       ▼
[ 智能体工作流推理 (Agent Workflow) ] ──> 验证意图提取与多轮上下文一致性
       │
       ▼
[ 工具选择与参数调用 (Tool Calling) ] ──> 校验选择正确性与结构化入参格式
       │
       ▼
[ 复杂结构化数据生成 (Output/SQL) ]  ──> Python / Pandas 自动化数据清洗与解析
       │
       ▼
[ 五维深度核对 (Evaluation) ]        ──> 对齐真实业务数据库与口径一致性
       │
       ▼
[ Badcase 归因分析 (Root Cause) ]    ──> 区分模型幻觉 / Prompt偏差 / 业务脏数据
       │
       ▼
[ 持续回归基线 (Regression Baseline) ] ──> 纳入自动化回归用例库，防止能力劣化
```

---

## 🛠️ 专业技能与实战证据映射 (Capabilities & Evidence)

| 专业技能域 | 掌握水平 | 核心工具链与方法 | 真实项目落地证据 |
| :--- | :---: | :--- | :--- |
| **测试开发 (SDET)** | **主力** | Pytest, 数据驱动设计, 边界/场景法, XMind, Jira/禅道 | 独立搭建自动化测试体系，全流程负责从用例设计到缺陷闭环 |
| **UI / 接口自动化** | **主力** | Python, Playwright, Selenium, Requests, WebSocket | 50+ 核心 API 自动巡检，数字分身小程序端到端自动化巡检 |
| **AI 应用专项评测** | **专项实践** | Text-to-SQL, Agent Workflow, Prompt 分析, Badcase 归因 | 中金点睛项目（五维验证法）、星点评 AI 工具平台测试 |
| **桌面与 ATE 测试** | **当前方向** | Windows 上位机, ATE 设备通信, 指令下发回传, 长时压测 | 长川科技车规级芯片测试机（ATE）上位机软件质量保障 |
| **DevOps 与持续集成** | **熟练** | Docker, Jenkins CI/CD, Linux / Shell, Webhook 钉钉告警 | 搭建定时自动巡检流水线，构建缺陷自动报告与告警闭环 |
| **全栈研发与工具** | **熟练** | TypeScript, Next.js 15, TailwindCSS, Vue.js, MySQL | 自研个人品牌网站、数璇接口测试平台与 AI 辅助工具台 |

---

## 🏆 核心实战项目与工程代表作 (Featured Projects)

| 🎯 项目名称 | 🏷️ 核心技术栈 | 📖 方案解决与工程亮点 |
| :--- | :--- | :--- |
| **车规级芯片测试机 (ATE) 上位机软件** | `Windows Desktop` `ATE` `长时压测` `UI 自动化` | **半导体测试机核心上位机质量保障 (长川科技 · 2026.07 - 至今)**<br>覆盖功放/功耗芯片测试的核心控制链路（指令下发、参数配置、数据采集、状态回传）；组织 72h+ 长时运行压测监测资源泄漏，搭建 UI 自动化保障版本快速闭环。 |
| **[qinyu-resume](https://github.com/yuyuyu6631/qinyu-resume)**<br>👉 [在线访问](https://yuyuyu6631.github.io/qinyu-resume/) | `Next.js 15` `TypeScript` `Tailwind` `Motion` | **高密度证据链个人品牌简历与作品集**<br>以 Apple / Vercel 极客设计语言打造，单一数据源（resume.json）同时驱动响应式网站、ATS 规范 PDF/DOCX 与 Markdown 衍生资产。 |
| **[sql-eval](https://github.com/yuyuyu6631/sql-eval)**<br>& **[sql-api-test-framework](https://github.com/yuyuyu6631/sql-api-test-framework)** | `Python` `Text-to-SQL` `MeterSphere` `Postman` | **中金点睛 AI 大模型评测体系 (Text-to-SQL · 零壹视界)**<br>建立 **「五维验证法」**（问题 → SQL生成 → 查询结果 → 页面展示 → 业务口径），实现模型输出偏差可定位、可复现、可自动化回归。 |
| **[ai-tool](https://github.com/yuyuyu6631/ai-tool)**<br>& **[AI-Tool-Demo](https://github.com/yuyuyu6631/AI-Tool-Demo)** | `Playwright` `Pytest` `LLM 辅助用例` `MySQL` | **星点评 AI 工具平台自动化测试方案 (零壹视界)**<br>拆解多状态登录态与数据一致性风险，运用 Playwright 覆盖主流程，结合 LLM 辅助生成边界测试用例与异常数据，大幅提高场景覆盖深度。 |
| **数字分身小程序自动化** | `Python` `Pytest` `微信小程序` `自动报告` | **小程序端到端自动化测试框架 (零壹视界)**<br>接入微信开发者工具自动化端口，设计端口重试机制与参数执行解耦，实现注册激活、Tab 导航与核心业务全自动巡检与多格式报告输出。 |
| **[PytestAutoApi](https://github.com/yuyuyu6631/PytestAutoApi)** | `Pytest` `Allure` `Jenkins` `DingTalk` | **企业级高可用接口自动化测试工程**<br>基于 Yaml 数据驱动，集成 Allure 可视化测试报告、Jenkins 自动构建流水线与钉钉群缺陷实时告警。 |

---

## 📊 GitHub 动态数据与活跃看板 (GitHub Activity)

<div align="center">

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yuyuyu6631&show_icons=true&theme=radical&locale=cn&hide_border=true" width="48.5%" alt="yuyuyu6631's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yuyuyu6631&layout=compact&theme=radical&locale=cn&hide_border=true" width="48.5%" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yuyuyu6631&theme=radical&hide_border=true" width="98%" alt="yuyuyu6631's GitHub Streak" />
</p>

</div>

---

## 📫 联系与交流 (Get in Touch)

如果您正在寻找具备**半导体 ATE 经验、AI 评测方法论与扎实自动化工具链研发能力**的测试开发工程师，随时欢迎沟通交流！

- 🌐 **个人品牌简历网站 (Portfolio)**：👉 **[https://yuyuyu6631.github.io/qinyu-resume/](https://yuyuyu6631.github.io/qinyu-resume/)**
- 💬 **微信 / 电话**：`18662732817`
- 📮 **联系邮箱 (Email)**：[1642732247@qq.com](mailto:1642732247@qq.com)
- 🏢 **意向城市**：深圳 / 广州 / 远程

<div align="center">
  <sub>⭐️ 持续深耕质量工程与效能工具研发！ Built with passion by Qinyu.</sub>
</div>
