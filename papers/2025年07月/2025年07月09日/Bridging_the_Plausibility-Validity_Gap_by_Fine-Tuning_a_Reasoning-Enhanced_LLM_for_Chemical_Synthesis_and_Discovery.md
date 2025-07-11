# 增强推理能力的大型语言模型通过微调，成功弥合了化学合成与发现中的合理性和有效性之间的差距。

发布时间：2025年07月09日

`LLM应用` `模型微调`

> Bridging the Plausibility-Validity Gap by Fine-Tuning a Reasoning-Enhanced LLM for Chemical Synthesis and Discovery

# 摘要

> 大型语言模型（LLMs）在专业领域如化学中常会出现“合理-真实性的差距”——生成看似合理却事实错误的信息。本文提出了一种系统性方法，通过开发专业化的科学助手来弥合这一差距。我们采用了具备综合推理能力的Magistral Small模型，并使用低秩适应（LoRA）对其进行微调。我们的方法的关键在于构建了一个“双域数据集”，这是一个从分子性质和化学反应等多个来源整理而成的综合语料库，并经过标准化处理以确保质量。

评估结果表明，微调后的模型在格式遵循、生成分子的化学有效性以及所提合成路线的可行性方面，均显著优于基线模型。研究结果表明存在一种分层学习模式，其中句法正确性比化学可能性和合成可行性更容易被学习。虽然与人类专家的对比分析显示在化学创造性和推理等方面具有竞争力，但也凸显了一些关键局限性，包括持续存在的立体化学错误、静态的知识截止日期以及偶尔出现的参考幻觉。

这项工作为将通用型LLMs适配为可靠的专业化工具以支持化学研究奠定了可行框架，同时也指出了未来改进的关键方向。


> Large Language Models (LLMs) often generate scientifically plausible but factually invalid information, a challenge we term the "plausibility-validity gap," particularly in specialized domains like chemistry. This paper presents a systematic methodology to bridge this gap by developing a specialized scientific assistant. We utilized the Magistral Small model, noted for its integrated reasoning capabilities, and fine-tuned it using Low-Rank Adaptation (LoRA). A key component of our approach was the creation of a "dual-domain dataset," a comprehensive corpus curated from various sources encompassing both molecular properties and chemical reactions, which was standardized to ensure quality. Our evaluation demonstrates that the fine-tuned model achieves significant improvements over the baseline model in format adherence, chemical validity of generated molecules, and the feasibility of proposed synthesis routes. The results indicate a hierarchical learning pattern, where syntactic correctness is learned more readily than chemical possibility and synthesis feasibility. While a comparative analysis with human experts revealed competitive performance in areas like chemical creativity and reasoning, it also highlighted key limitations, including persistent errors in stereochemistry, a static knowledge cutoff, and occasional reference hallucination. This work establishes a viable framework for adapting generalist LLMs into reliable, specialized tools for chemical research, while also delineating critical areas for future improvement.

[Arxiv](https://arxiv.org/abs/2507.07328)