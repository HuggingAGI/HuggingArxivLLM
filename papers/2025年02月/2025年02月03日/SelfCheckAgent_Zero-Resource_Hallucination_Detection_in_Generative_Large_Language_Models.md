# SelfCheckAgent: 生成式大语言模型的零资源幻觉检测

发布时间：2025年02月03日

`Agent

理由：这篇论文介绍了一个名为SelfCheckAgent的创新框架，该框架集成了多个代理（如符号代理、专门检测代理和上下文一致性代理）来检测大型语言模型中的幻觉。由于论文的核心内容围绕多个代理的协作和功能展开，因此将其分类为Agent是合适的。` `人工智能`

> SelfCheckAgent: Zero-Resource Hallucination Detection in Generative Large Language Models

# 摘要

> 检测大型语言模型（LLMs）中的幻觉仍是其实际应用中的一大挑战。为此，我们推出了SelfCheckAgent，一个集成符号代理、专门检测代理和上下文一致性代理的创新框架。这些代理共同构建了一个多维度的幻觉检测体系。其中，上下文一致性代理结合Llama 3.1与思维链（CoT），在WikiBio数据集上表现卓越，非事实、事实和排名检测得分分别为93.64%、70.26%和78.48%。在AIME数据集上，GPT-4o与CoT在非事实检测中得分高达94.89%，但事实和排名检测得分仅为30.58%和30.68%，揭示了复杂数学领域幻觉检测的难度。框架还引入了三角测量策略，显著提升了SelfCheckAgent在实际应用中的幻觉识别能力。对比分析显示，SelfCheckAgent在多个领域均表现出色，成为可信LLMs的重要突破。这些成果彰显了一致性驱动方法在LLMs幻觉检测中的巨大潜力。

> Detecting hallucinations in Large Language Models (LLMs) remains a critical challenge for their reliable deployment in real-world applications. To address this, we introduce SelfCheckAgent, a novel framework integrating three different agents: the Symbolic Agent, the Specialized Detection Agent, and the Contextual Consistency Agent. These agents provide a robust multi-dimensional approach to hallucination detection. Notable results include the Contextual Consistency Agent leveraging Llama 3.1 with Chain-of-Thought (CoT) to achieve outstanding performance on the WikiBio dataset, with NonFactual hallucination detection scoring 93.64%, Factual 70.26%, and Ranking 78.48% respectively. On the AIME dataset, GPT-4o with CoT excels in NonFactual detection with 94.89% but reveals trade-offs in Factual with 30.58% and Ranking with 30.68%, underscoring the complexity of hallucination detection in the complex mathematical domains. The framework also incorporates a triangulation strategy, which increases the strengths of the SelfCheckAgent, yielding significant improvements in real-world hallucination identification. The comparative analysis demonstrates SelfCheckAgent's applicability across diverse domains, positioning it as a crucial advancement for trustworthy LLMs. These findings highlight the potentiality of consistency-driven methodologies in detecting hallucinations in LLMs.

[Arxiv](https://arxiv.org/abs/2502.01812)