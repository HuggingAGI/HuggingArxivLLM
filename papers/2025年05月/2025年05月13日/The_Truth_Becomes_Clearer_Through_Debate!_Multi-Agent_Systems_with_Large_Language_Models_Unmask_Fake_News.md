# 辩论让真相更清晰！多智能体系统与大型语言模型携手，精准识别虚假新闻。

发布时间：2025年05月13日

`Agent` `信息传播`

> The Truth Becomes Clearer Through Debate! Multi-Agent Systems with Large Language Models Unmask Fake News

# 摘要

> 在当今数字时代，假新闻通过社交网络的快速传播给社会带来了巨大挑战。现有检测方法主要分为两类：一类是采用传统分类模型，但这类模型存在解释性差、泛化能力有限的问题；另一类则为大型语言模型（LLMs）设计特定提示，直接生成解释和结果，但未能充分发挥LLMs的推理能力。受“真理越辩越明”启发，我们提出了一种基于LLMs的多智能体系统TruEDebate（TED），旨在提升假新闻检测的可解释性和有效性。TED采用了受正式辩论环境启发的严格辩论流程。我们的方法核心在于两个创新组件：DebateFlow Agents和InsightFlow Agents。DebateFlow Agents将智能体分为正反两方，分别支持和质疑新闻的真实性。这些智能体通过开场陈述、交叉询问、反驳和总结等环节，模拟了一个严格的辩论过程，类似于人类的 discourse analysis，从而对新闻内容进行全面评估。同时，InsightFlow Agents由两个专门子智能体组成：Synthesis Agent和Analysis Agent。Synthesis Agent对辩论内容进行总结，提供全局视角，确保评估的一致性和全面性。Analysis Agent包含一个角色感知编码器和一个辩论图，通过整合角色嵌入，并使用注意力机制建模辩论角色与论点之间的交互，从而提供最终的判断结果。

> In today's digital environment, the rapid propagation of fake news via social networks poses significant social challenges. Most existing detection methods either employ traditional classification models, which suffer from low interpretability and limited generalization capabilities, or craft specific prompts for large language models (LLMs) to produce explanations and results directly, failing to leverage LLMs' reasoning abilities fully. Inspired by the saying that "truth becomes clearer through debate," our study introduces a novel multi-agent system with LLMs named TruEDebate (TED) to enhance the interpretability and effectiveness of fake news detection. TED employs a rigorous debate process inspired by formal debate settings. Central to our approach are two innovative components: the DebateFlow Agents and the InsightFlow Agents. The DebateFlow Agents organize agents into two teams, where one supports and the other challenges the truth of the news. These agents engage in opening statements, cross-examination, rebuttal, and closing statements, simulating a rigorous debate process akin to human discourse analysis, allowing for a thorough evaluation of news content. Concurrently, the InsightFlow Agents consist of two specialized sub-agents: the Synthesis Agent and the Analysis Agent. The Synthesis Agent summarizes the debates and provides an overarching viewpoint, ensuring a coherent and comprehensive evaluation. The Analysis Agent, which includes a role-aware encoder and a debate graph, integrates role embeddings and models the interactions between debate roles and arguments using an attention mechanism, providing the final judgment.

[Arxiv](https://arxiv.org/abs/2505.08532)