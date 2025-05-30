# ToMAP: 基于心智理论训练具备对手意识的LLM说服者

发布时间：2025年05月28日

`Agent

理由：这篇论文专注于构建一个增强心智理论的劝说智能体（ToMAP），通过强化学习框架和模块化设计来提升劝说能力，属于智能体设计与应用领域。` `对话系统`

> ToMAP: Training Opponent-Aware LLM Persuaders with Theory of Mind

# 摘要

> 大型语言模型（LLMs）在劝说领域展现出巨大潜力，但目前针对LLM劝说者的训练研究仍处于初步阶段。尽管人类擅长主动建模对手的思想和观点，现有的LLMs在“心智理论”（ToM）推理方面仍存在不足，导致劝说内容的多样性和对对手意识的把握能力有限。为解决这一问题，我们提出了“心智理论增强型劝说器”（ToMAP），这是一种通过整合两个增强心智理论模块来构建更灵活劝说代理的新方法。具体而言，我们首先引导劝说者考虑针对目标核心主张的可能反对意见，然后利用文本编码器结合训练好的MLP分类器来预测对手对这些反驳主张的立场。通过精心设计的强化学习框架，劝说者能够学习分析对手相关信息并生成更具说服力的论点。实验结果显示，尽管ToMAP劝说者仅包含30亿个参数，但它在多个被说服者模型和多样化语料库上均显著超越了更大规模的基线模型（如GPT-4o），相对提升了39.4%。ToMAP在训练过程中展现了复杂的推理链条和减少了重复，生成了更具多样性和说服力的论点。此外，ToMAP对对手的感知能力使其适用于长对话，并能够采用更逻辑性和对手意识更强的策略。这些结果不仅证明了我们方法的有效性，也为开发更具说服力的语言代理奠定了基础。代码可在以下链接获取：https://github.com/ulab-uiuc/ToMAP。

> Large language models (LLMs) have shown promising potential in persuasion, but existing works on training LLM persuaders are still preliminary. Notably, while humans are skilled in modeling their opponent's thoughts and opinions proactively and dynamically, current LLMs struggle with such Theory of Mind (ToM) reasoning, resulting in limited diversity and opponent awareness. To address this limitation, we introduce Theory of Mind Augmented Persuader (ToMAP), a novel approach for building more flexible persuader agents by incorporating two theory of mind modules that enhance the persuader's awareness and analysis of the opponent's mental state. Specifically, we begin by prompting the persuader to consider possible objections to the target central claim, and then use a text encoder paired with a trained MLP classifier to predict the opponent's current stance on these counterclaims. Our carefully designed reinforcement learning schema enables the persuader learns how to analyze opponent-related information and utilize it to generate more effective arguments. Experiments show that the ToMAP persuader, while containing only 3B parameters, outperforms much larger baselines, like GPT-4o, with a relative gain of 39.4% across multiple persuadee models and diverse corpora. Notably, ToMAP exhibits complex reasoning chains and reduced repetition during training, which leads to more diverse and effective arguments. The opponent-aware feature of ToMAP also makes it suitable for long conversations and enables it to employ more logical and opponent-aware strategies. These results underscore our method's effectiveness and highlight its potential for developing more persuasive language agents. Code is available at: https://github.com/ulab-uiuc/ToMAP.

[Arxiv](https://arxiv.org/abs/2505.22961)