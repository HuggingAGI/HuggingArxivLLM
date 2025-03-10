# 引文前置：提升电商对话LLM代理的上下文-响应关联性

发布时间：2025年03月05日

`LLM应用` `电子商务` `对话式AI`

> Cite Before You Speak: Enhancing Context-Response Grounding in E-commerce Conversational LLM-Agents

# 摘要

> 对话式大型语言模型（LLMs）的进步催生了多种基于LLM的对话式购物代理（CSA），它们在电子商务领域帮助客户解答问题，提升购物体验。然而，构建一个值得信赖的CSA面临两大挑战：LLMs可能产生幻觉或无支持声明，导致信息不准确，损害客户信任；CSA的回答缺乏知识来源归属，使客户难以验证信息。为解决这些问题，我们提出了一种易于部署的解决方案，利用In-context Learning (ICL) 和 Multi-UX-Inference (MUI) 来生成带引文的回答，将原始来源归属到回答中，同时不影响其他用户体验功能。通过适当的用户体验设计，这些引文标记可链接到相关产品信息，向客户展示来源。我们还构建了自动度量和可扩展的基准测试，全面评估LLM的 grounding 和归属能力。实验表明，引入这种引文生成范式使LLM回答的 grounding 提升了13.83%。因此，我们的解决方案不仅解决了LLM grounding 的问题，还为对话式AI增加了透明度。

> With the advancement of conversational large language models (LLMs), several LLM-based Conversational Shopping Agents (CSA) have been developed to help customers answer questions and smooth their shopping journey in e-commerce domain. The primary objective in building a trustworthy CSA is to ensure the agent's responses are accurate and factually grounded, which is essential for building customer trust and encouraging continuous engagement. However, two challenges remain. First, LLMs produce hallucinated or unsupported claims. Such inaccuracies risk spreading misinformation and diminishing customer trust. Second, without providing knowledge source attribution in CSA response, customers struggle to verify LLM-generated information. To address these challenges, we present an easily productionized solution that enables a "citation experience" utilizing In-context Learning (ICL) and Multi-UX-Inference (MUI) to generate responses with citations to attribute its original sources without interfering other existing UX features. With proper UX design, these citation marks can be linked to the related product information and display the source to our customers. In this work, we also build auto-metrics and scalable benchmarks to holistically evaluate LLM's grounding and attribution capabilities. Our experiments demonstrate that incorporating this citation generation paradigm can substantially enhance the grounding of LLM responses by 13.83% on the real-world data. As such, our solution not only addresses the immediate challenges of LLM grounding issues but also adds transparency to conversational AI.

[Arxiv](https://arxiv.org/abs/2503.04830)