# 基于智能体AI的自然语言框架：缓解幻觉问题的利器

发布时间：2025年01月19日

`Agent

理由：这篇论文主要探讨了通过协调多个专门 AI 代理来缓解生成式 AI 模型的幻觉问题。论文中详细描述了如何设计一个管道，利用多个代理系统来审查和优化输出，并引入新的 KPI 来评估幻觉得分。研究的核心是 OVON 框架，它通过基于 NLP 的通用接口在代理间传递上下文信息。这些内容都集中在多代理系统的设计和应用上，因此将其分类为Agent。` `人工智能`

> Hallucination Mitigation using Agentic AI Natural Language-Based Frameworks

# 摘要

> # 摘要
幻觉问题仍是生成式 AI 模型的一大挑战，影响了 AI 系统的可信度。本研究探索了如何通过协调多个专门 AI 代理来缓解这一问题，重点关注基于 NLP 实现代理无缝交互的系统。我们设计了一个管道，向前端代理注入 300 多个精心设计的提示以诱发幻觉，随后由第二级和第三级代理系统审查并优化输出。这些代理采用不同的大型语言模型和定制策略，检测未经证实的声明、添加免责声明并澄清推测性内容。此外，我们引入了一套新的 KPI，专门用于评估幻觉得分。第四级 AI 代理负责评估这些 KPI，提供详细分析并量化幻觉行为的变化。研究核心是 OVON 框架，它通过基于 NLP 的通用接口在代理间传递上下文信息。每个代理通过结构化 JSON 消息传递对幻觉可能性的评估及可疑内容的原因，确保后续阶段在保留上下文的同时优化文本。结果表明，基于 NLP 框架相互协作的多个专门代理在缓解幻觉方面效果显著，有助于提升 AI 社区的可信度。

> Hallucinations remain a significant challenge in current Generative AI models, undermining trust in AI systems and their reliability. This study investigates how orchestrating multiple specialized Artificial Intelligent Agents can help mitigate such hallucinations, with a focus on systems leveraging Natural Language Processing (NLP) to facilitate seamless agent interactions. To achieve this, we design a pipeline that introduces over three hundred prompts, purposefully crafted to induce hallucinations, into a front-end agent. The outputs are then systematically reviewed and refined by second- and third-level agents, each employing distinct large language models and tailored strategies to detect unverified claims, incorporate explicit disclaimers, and clarify speculative content. Additionally, we introduce a set of novel Key Performance Indicators (KPIs) specifically designed to evaluate hallucination score levels. A dedicated fourth-level AI agent is employed to evaluate these KPIs, providing detailed assessments and ensuring accurate quantification of shifts in hallucination-related behaviors. A core component of this investigation is the use of the OVON (Open Voice Network) framework, which relies on universal NLP-based interfaces to transfer contextual information among agents. Through structured JSON messages, each agent communicates its assessment of the hallucination likelihood and the reasons underlying questionable content, thereby enabling the subsequent stage to refine the text without losing context. The results demonstrate that employing multiple specialized agents capable of interoperating with each other through NLP-based agentic frameworks can yield promising outcomes in hallucination mitigation, ultimately bolstering trust within the AI community.

[Arxiv](https://arxiv.org/abs/2501.13946)