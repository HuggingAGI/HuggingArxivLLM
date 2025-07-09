# # LLMs 是内敛的

发布时间：2025年07月07日

`LLM应用` `社交媒体` `人工智能`

> LLMs are Introvert

# 摘要

> 社交媒体和生成式AI的指数级增长彻底改变了信息传播的方式，虽然增强了人与人之间的连接，但也加速了错误信息的扩散。理解信息传播的动态并开发有效的控制策略，对于减少有害内容的传播至关重要。传统的SIR模型虽然提供了基本的见解，但难以捕捉到复杂的在线交互。先进的注意力机制和图神经网络虽然提高了准确性，却忽视了用户心理和行为动态。大型语言模型（LLMs）凭借其类人推理能力，为模拟信息传播的心理层面提供了新思路。我们开发了一个基于LLMs的仿真环境，能够捕捉到代理不断变化的态度、情感和反应。然而，初步实验显示，LLM生成的行为与真实人类动态之间存在显著差距，尤其是在立场检测和心理现实感方面。通过基于社会信息处理理论的详细评估，我们发现目标设定和反馈评估方面存在重大差异，这些差异源于标准LLM训练中缺乏情感处理。为了解决这些问题，我们提出了基于社会信息处理的思考链（SIP-CoT）机制，并通过情感引导的记忆进行了增强。该方法显著提升了对社会线索的解释能力、个性化目标设定以及反馈评估。实验结果证实，增强后的SIP-CoT LLM代理更高效地处理了社会信息，展现出的行为、态度和情感更接近真实的人类互动。总之，这项研究揭示了当前基于LLM的传播模拟的关键局限性，并展示了通过整合SIP-CoT和情感记忆，显著提升了LLM代理的社会智能和现实感。

> The exponential growth of social media and generative AI has transformed information dissemination, fostering connectivity but also accelerating the spread of misinformation. Understanding information propagation dynamics and developing effective control strategies is essential to mitigate harmful content. Traditional models, such as SIR, provide basic insights but inadequately capture the complexities of online interactions. Advanced methods, including attention mechanisms and graph neural networks, enhance accuracy but typically overlook user psychology and behavioral dynamics. Large language models (LLMs), with their human-like reasoning, offer new potential for simulating psychological aspects of information spread. We introduce an LLM-based simulation environment capturing agents' evolving attitudes, emotions, and responses. Initial experiments, however, revealed significant gaps between LLM-generated behaviors and authentic human dynamics, especially in stance detection and psychological realism. A detailed evaluation through Social Information Processing Theory identified major discrepancies in goal-setting and feedback evaluation, stemming from the lack of emotional processing in standard LLM training. To address these issues, we propose the Social Information Processing-based Chain of Thought (SIP-CoT) mechanism enhanced by emotion-guided memory. This method improves the interpretation of social cues, personalization of goals, and evaluation of feedback. Experimental results confirm that SIP-CoT-enhanced LLM agents more effectively process social information, demonstrating behaviors, attitudes, and emotions closer to real human interactions. In summary, this research highlights critical limitations in current LLM-based propagation simulations and demonstrates how integrating SIP-CoT and emotional memory significantly enhances the social intelligence and realism of LLM agents.

[Arxiv](https://arxiv.org/abs/2507.05638)