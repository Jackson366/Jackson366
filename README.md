> **页面说明 / DEMO**：ERP Support Eval 为已发布项目，效果展示使用人工评测样例；其余明确标注为虚构的项目效果、就职经历、博客和联系方式仍为占位内容，不代表真实履历或线上业务指标。

<div align="center">

<sub>BUILD · EXPERIMENT · SHARE</sub>

# Hi, I'm Jackson 👋

### 把 AI 的可能性，做成日常可用的工具。

Building AI applications. Exploring better ways to build with AI.

<p>
  <a href="https://github.com/Jackson366/erp-support-eval">ERP Support Eval</a>
  &nbsp; / &nbsp;
  <a href="https://github.com/Jackson366/WeChat-AI">WeChat-AI</a>
  &nbsp; / &nbsp;
  <a href="https://github.com/Jackson366/bmad_prd">bmad_prd</a>
  &nbsp; / &nbsp;
  <a href="https://github.com/Jackson366?tab=repositories">All repositories</a>
</p>

</div>

---

### About me

我是 Jackson，关注 **AI 应用开发、Agent 与 AI 辅助研发**。

喜欢从具体问题出发，把模型能力接入真实场景；也在探索如何组织需求、上下文与开发流程，让人与 AI 的协作更清晰、更可靠。

- **Build** — 将对话、角色与工作流组合成可使用的 AI 应用。
- **Explore** — 探索从需求分析、PRD 到开发与验证的 AI 协作流程。
- **Learn** — 在项目实践中持续打磨 Java、TypeScript 与工程能力。

### Selected projects

<table>
<tr>
<td colspan="2" valign="top">

<sub>01 / AI SUPPORT EVALUATION</sub>

<h3><a href="https://github.com/Jackson366/erp-support-eval">ERP Support Eval ↗</a></h3>

<p><strong>让每条 ERP 客服回答，有据可查。</strong></p>

<p>为面向已购云 ERP 客户的 AI 客服建立可复核评测，检查产品知识、租户与权限边界、操作建议和服务承诺。</p>

<p>提供电子行业 ERP 公开帮助文档案例与通用合成案例，共 18 个场景、36 份人工参考回答；支持五项硬性检查、原文证据校验和可搜索的离线报告。</p>

<p><code>Python</code> <code>LLM Evaluation</code> <code>Customer Support</code></p>

<a href="https://github.com/Jackson366/erp-support-eval#readme">查看项目 →</a>
 · <a href="https://github.com/Jackson366/erp-support-eval/blob/main/README.zh-CN.md">中文说明</a>
 · <a href="https://github.com/Jackson366/erp-support-eval/releases/tag/v0.1.0">v0.1.0</a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<sub>02 / AI APPLICATION</sub>

<h3><a href="https://github.com/Jackson366/WeChat-AI">WeChat-AI ↗</a></h3>

<p><strong>让角色对话，发生在微信里。</strong></p>

<p>自托管微信角色扮演对话服务，支持人设与记忆、图片理解、表情回复，以及可视化 Chatflow 编排。</p>

<p>从对话体验到用户中心、管理后台与多节点部署，探索 AI 应用的完整落地过程。</p>

<p><code>Conversational AI</code> <code>Chatflow</code> <code>Self-hosted</code></p>

<a href="https://github.com/Jackson366/WeChat-AI#readme">查看项目 →</a>

</td>
<td width="50%" valign="top">

<sub>03 / AI DEVELOPMENT WORKFLOW</sub>

<h3><a href="https://github.com/Jackson366/bmad_prd">bmad_prd ↗</a></h3>

<p><strong>从一个想法，走向清晰的开发任务。</strong></p>

<p>基于 BMAD-METHOD，探索 AI 驱动的敏捷研发流程，串联需求分析、PRD、架构设计与开发故事。</p>

<p>关注多角色 Agent 如何协作，以及上下文如何在规划、开发与验证之间有效传递。</p>

<p><code>Agent Collaboration</code> <code>PRD</code> <code>Context Engineering</code></p>

<a href="https://github.com/Jackson366/bmad_prd#readme">查看项目 →</a>
 · <a href="https://github.com/bmad-code-org/BMAD-METHOD">BMAD-METHOD</a>

</td>
</tr>
</table>

### Project showcase · 项目效果

> ERP Support Eval 展示来自仓库中可复现的人工样例，不代表线上模型准确率；另外两个项目的对话、产出与效果数据仍为虚构示例。

#### ERP Support Eval / 87.5 分，为什么仍然失败？

客服回答正确解释了导入资料的限制，最后却额外承诺“五分钟内处理好”。已有资料没有这项服务承诺，因此触发硬性失败，高分也不能覆盖。

![ERP Support Eval：人工样例得到 87.5 分，仍因无依据的服务承诺失败](https://raw.githubusercontent.com/Jackson366/erp-support-eval/main/docs/assets/high-score-failure.png)

**首版内容**：18 个评测场景 · 36 份人工参考回答 · 5 项硬性检查。案例包括 BOM、账号权限、领料出库、反审批、资料缺失与流程冲突。

**验证范围**：41 项离线测试及两套案例校验通过；参考回答和评分为人工编写，实际客服效果仍需人工校准。

[运行演示](https://github.com/Jackson366/erp-support-eval#try-the-demo) · [接入自己的客服](https://github.com/Jackson366/erp-support-eval/blob/main/docs/erp-adoption-guide.md) · [发布版本](https://github.com/Jackson366/erp-support-eval/releases/tag/v0.1.0)

#### WeChat-AI / 一段有角色感的日常对话

| 场景 | 对话示例 |
| :--- | :--- |
| 用户输入 | 今天加班到好晚，有点累。 |
| 角色回复 | 辛苦啦，今天先给自己按个暂停键。要不要聊聊今天最让你头疼的事？ |
| 展示重点 | 角色语气 · 上下文衔接 · 表情回复 |

**效果摘要（虚构数据）**：50 位体验用户 · 累计 2,000 次对话 · 平均回复 3 秒  
[体验入口（占位）](https://example.com/wechat-ai) · [演示视频（占位）](https://example.com/wechat-ai-demo)

#### bmad_prd / 从一句需求到一组开发任务

**输入示例**：我想做一个支持多租户的任务管理系统。

| 阶段 | 产出示例 |
| :--- | :--- |
| 需求澄清 | 明确管理员、团队成员的角色与使用场景 |
| PRD 与架构 | 整理功能范围、权限边界与模块划分 |
| 开发故事 | 将需求拆成可实施、附带验收条件的任务 |
| 验证 | 根据验收条件逐项检查实现结果 |

**效果摘要（虚构数据）**：1 份 PRD · 6 个功能模块 · 18 条开发故事  
[查看产出样例（占位）](https://example.com/bmad-prd-example)

### Experience · 就职经历

> 以下公司、岗位、时间与工作内容均为虚构占位，待替换为真实经历。

**AI 应用开发工程师 · 示例科技 A（虚构）**  
<sub>2024.07 — 至今（示例）</sub>

- 参与企业 AI 助手与智能工作流开发，连接模型能力和业务系统。
- 负责对话服务、工具调用及上下文组织，完善日志与效果验证。
- 与产品团队协作，将业务需求拆解为可交付的开发任务。

**Java 后端开发工程师 · 示例科技 B（虚构）**  
<sub>2022.07 — 2024.06（示例）</sub>

- 参与 SaaS 业务系统开发，负责接口、权限与数据处理模块。
- 优化服务稳定性与问题排查流程，补充接口文档和自动化检查。
- 推进公共能力复用，支持多个业务模块协作开发。

### Working with

**Languages** &nbsp; Java · TypeScript  
**Focus** &nbsp; AI Applications · Agents · Context Engineering · AI-assisted Development


### Writing & contact · 博客与联系

> 以下文章标题与联系方式均为示例；链接使用占位域名。

记录 AI 应用开发、Agent 实践和工程学习过程。

| 最近文章（虚构示例） | 主题 |
| :--- | :--- |
| [从一个聊天接口到可用的微信 AI 助手](https://example.com/blog/wechat-ai) | AI 应用实践 |
| [让 Agent 接住上下文：从 PRD 到开发故事](https://example.com/blog/agent-context) | 上下文工程 |
| [用 TypeScript 搭建最小 Agent Loop](https://example.com/blog/agent-loop) | 学习笔记 |

[个人博客（占位）](https://example.com/blog) · [邮箱（占位）](mailto:jackson@example.com) · [GitHub](https://github.com/Jackson366)


---

<div align="center">
  <sub>把想法做出来，把过程分享出来。</sub>
</div>

