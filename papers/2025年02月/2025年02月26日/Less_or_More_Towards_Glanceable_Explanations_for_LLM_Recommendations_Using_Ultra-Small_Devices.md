# 少即是多：探索LLM推荐的可视化解释——基于超小型设备的研究

发布时间：2025年02月26日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在智能手表等超小型设备上的应用，特别是如何优化解释的呈现方式以提升用户体验。研究集中在实际应用中的问题解决和用户反馈，属于LLM的应用层面。` `智能手表` `人工智能`

> Less or More: Towards Glanceable Explanations for LLM Recommendations Using Ultra-Small Devices

# 摘要

> 大型语言模型（LLMs）作为个人AI助手，在推荐日常行动方面展现出巨大潜力，而可解释性人工智能（XAI）技术则帮助用户理解推荐背后的逻辑。然而，当前AI助手多运行在智能手表等超小型设备上，受限于屏幕空间，LLM生成的冗长解释难以有效呈现。为解决这一问题，我们探索了两种方法：1）通过定义的上下文组件对LLM解释进行结构化；2）基于置信水平动态调整解释呈现方式。通过用户研究，我们发现结构化解释能显著减少用户的阅读时间和认知负担，并提升对AI推荐的接受度。然而，用户对结构化解释的满意度低于非结构化解释，主要因为细节不够丰富。此外，动态呈现结构化解释的效果不如始终显示的结构化解释。结合用户反馈，这些发现为在超小型设备上优化LLM解释的内容和时机提供了重要设计启示。

> Large Language Models (LLMs) have shown remarkable potential in recommending everyday actions as personal AI assistants, while Explainable AI (XAI) techniques are being increasingly utilized to help users understand why a recommendation is given. Personal AI assistants today are often located on ultra-small devices such as smartwatches, which have limited screen space. The verbosity of LLM-generated explanations, however, makes it challenging to deliver glanceable LLM explanations on such ultra-small devices. To address this, we explored 1) spatially structuring an LLM's explanation text using defined contextual components during prompting and 2) presenting temporally adaptive explanations to users based on confidence levels. We conducted a user study to understand how these approaches impacted user experiences when interacting with LLM recommendations and explanations on ultra-small devices. The results showed that structured explanations reduced users' time to action and cognitive load when reading an explanation. Always-on structured explanations increased users' acceptance of AI recommendations. However, users were less satisfied with structured explanations compared to unstructured ones due to their lack of sufficient, readable details. Additionally, adaptively presenting structured explanations was less effective at improving user perceptions of the AI compared to the always-on structured explanations. Together with users' interview feedback, the results led to design implications to be mindful of when personalizing the content and timing of LLM explanations that are displayed on ultra-small devices.

[Arxiv](https://arxiv.org/abs/2502.19410)