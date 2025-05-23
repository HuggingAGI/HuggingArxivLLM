# 从通用共情到个性化情感支持：一个用于用户偏好对齐的自我进化框架

发布时间：2025年05月22日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于情感支持任务，并提出了一种自我进化框架来改进模型的回应，使其更好地满足用户需求。这属于LLM的应用层面，而非理论或架构层面的改进。` `情感计算` `对话系统`

> From Generic Empathy to Personalized Emotional Support: A Self-Evolution Framework for User Preference Alignment

# 摘要

> 有效的情感支持需要理解用户的情绪和需求，从而在多轮对话中提供实质性的慰藉。大型语言模型（LLMs）在表达同理心方面潜力巨大，但常常因提供千篇一律的回应而无法满足用户的特定需求。针对这一问题，我们提出了一种自我进化框架，旨在帮助LLMs改进回应，使其更好地与用户关于个性、情绪状态和具体情境的隐含偏好相匹配。我们的框架分为两个阶段：	extit{(1)} 	extit{情感支持经验获取}，LLMs通过微调有限的情感支持对话数据提供基础支持；	extit{(2)} 	extit{个性化情感支持的自我改进}，LLMs借助自我反思与完善生成个性化回应。通过迭代优化预优化和后优化的回应，我们的模型能更好地理解用户的隐含偏好。实验结果表明，该方法显著提升了模型在情感支持方面的能力，减少了无益回应，并缩小了用户偏好与模型输出的差距。

> Effective emotional support hinges on understanding users' emotions and needs to provide meaningful comfort during multi-turn interactions. Large Language Models (LLMs) show great potential for expressing empathy; however, they often deliver generic and one-size-fits-all responses that fail to address users' specific needs. To tackle this issue, we propose a self-evolution framework designed to help LLMs improve their responses to better align with users' implicit preferences concerning user profiles (personalities), emotional states, and specific situations. Our framework consists of two distinct phases: \textit{(1)} \textit{Emotional Support Experience Acquisition}, where LLMs are fine-tuned on limited emotional support conversation data to provide basic support, and \textit{(2)} \textit{Self-Improvement for Personalized Emotional Support}, where LLMs leverage self-reflection and self-refinement to generate personalized responses. Through iterative direct preference optimization between the pre- and post-refined responses, our model generates responses that reflect a better understanding of the user's implicit preferences. Extensive experiments and evaluations demonstrate that our method significantly enhances the model's performance in emotional support, reducing unhelpful responses and minimizing discrepancies between user preferences and model outputs.

[Arxiv](https://arxiv.org/abs/2505.16610)