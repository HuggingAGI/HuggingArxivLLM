# AI 聊天机器人：专业服务代理的身份构建

发布时间：2025年01月23日

`Agent

理由：这篇论文主要讨论了基于大型语言模型（LLM）的专业服务代理，特别是针对医疗领域的问答服务。论文提出了一个名为LAPI的框架，旨在确保与特定专业身份的一致性，并通过任务规划和熵方法来生成专业且符合伦理的响应。这些内容涉及到代理的设计和应用，因此将其分类为Agent。` `聊天机器人`

> AI Chatbots as Professional Service Agents: Developing a Professional Identity

# 摘要

> 随着大型语言模型（LLM）应用的迅猛发展，基于LLM的AI聊天机器人正从通用查询工具转型为专业服务代理。然而，现有研究常忽略一个关键点：专业服务代理的沟通方式应与其专业身份相符。这在医疗领域尤为重要，因为与患者的有效沟通是实现专业目标的关键，例如通过鼓励健康行为来提升患者福祉。为填补这一空白，我们提出了LAPI（基于LLM的专业身份代理），这是一个专为医疗问答（Q&A）服务设计的框架，确保与特定专业身份的一致性。我们的方法包括理论指导的任务规划，将复杂任务分解为与专业目标一致的可管理子任务，以及实用的熵方法，旨在生成低不确定性的专业且符合伦理的响应。实验表明，该方法在流畅性、自然性、同理心、以患者为中心和ROUGE-L分数等关键指标上优于少样本提示和思维链提示等基线方法。消融研究进一步验证了各组件对方法整体有效性的贡献。

> With the rapid expansion of large language model (LLM) applications, there is an emerging shift in the role of LLM-based AI chatbots from serving merely as general inquiry tools to acting as professional service agents. However, current studies often overlook a critical aspect of professional service agents: the act of communicating in a manner consistent with their professional identities. This is of particular importance in the healthcare sector, where effective communication with patients is essential for achieving professional goals, such as promoting patient well-being by encouraging healthy behaviors. To bridge this gap, we propose LAPI (LLM-based Agent with a Professional Identity), a novel framework for designing professional service agent tailored for medical question-and-answer (Q\&A) services, ensuring alignment with a specific professional identity. Our method includes a theory-guided task planning process that decomposes complex professional tasks into manageable subtasks aligned with professional objectives and a pragmatic entropy method designed to generate professional and ethical responses with low uncertainty. Experiments on various LLMs show that the proposed approach outperforms baseline methods, including few-shot prompting, chain-of-thought prompting, across key metrics such as fluency, naturalness, empathy, patient-centricity, and ROUGE-L scores. Additionally, the ablation study underscores the contribution of each component to the overall effectiveness of the approach.

[Arxiv](https://arxiv.org/abs/2501.14179)