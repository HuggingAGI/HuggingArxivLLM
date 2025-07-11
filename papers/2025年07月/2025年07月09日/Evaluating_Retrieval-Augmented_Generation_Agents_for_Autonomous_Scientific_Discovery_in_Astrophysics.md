# # 评估检索增强生成智能体在天文学自主科学发现中的应用

发布时间：2025年07月09日

`RAG` `天体物理学` `问答系统`

> Evaluating Retrieval-Augmented Generation Agents for Autonomous Scientific Discovery in Astrophysics

# 摘要

> 我们评估了9种检索增强生成（RAG）代理配置，使用了专为该研究构建的105个宇宙学问答对。这些配置由一位人类专家评估，共评估了945个生成答案。结果显示，目前最佳配置是使用OpenAI的嵌入和生成模型，准确率达到91.4%。基于评估结果，我们开发了一个LLM作为裁判（LLMaaJ）系统，可作为可靠的人类评估替代方案。这些成果使我们能够为天体物理学中的多智能体系统（如配套论文中介绍的cmbagent）选择最佳RAG配置，并提供了一个可扩展的LLMaaJ系统。我们的QA数据集、评估结果、RAG管道和系统均已公开，供天体物理学界使用。

> We evaluate 9 Retrieval Augmented Generation (RAG) agent configurations on 105 Cosmology Question-Answer (QA) pairs that we built specifically for this purpose.The RAG configurations are manually evaluated by a human expert, that is, a total of 945 generated answers were assessed. We find that currently the best RAG agent configuration is with OpenAI embedding and generative model, yielding 91.4\% accuracy. Using our human evaluation results we calibrate LLM-as-a-Judge (LLMaaJ) system which can be used as a robust proxy for human evaluation. These results allow us to systematically select the best RAG agent configuration for multi-agent system for autonomous scientific discovery in astrophysics (e.g., cmbagent presented in a companion paper) and provide us with an LLMaaJ system that can be scaled to thousands of cosmology QA pairs. We make our QA dataset, human evaluation results, RAG pipelines, and LLMaaJ system publicly available for further use by the astrophysics community.

[Arxiv](https://arxiv.org/abs/2507.07155)