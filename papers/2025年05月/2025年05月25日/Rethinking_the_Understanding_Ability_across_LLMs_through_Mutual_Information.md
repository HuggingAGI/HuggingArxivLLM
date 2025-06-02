# 借助互信息，重新审视不同大型语言模型的理解能力

发布时间：2025年05月25日

`LLM理论

摘要中讨论了使用信息论框架评估大型语言模型的语言理解能力，提出了基于互信息的方法，并分析了模型的信息保留和恢复能力。这些内容属于理论层面的探讨，因此归类为LLM理论。` `信息论`

> Rethinking the Understanding Ability across LLMs through Mutual Information

# 摘要

> 大型语言模型（LLMs）的最新进展彻底改变了自然语言处理领域，但评估其内在的语言理解能力仍具挑战。我们提出了一种基于互信息（MI）的信息论框架，超越传统评估任务，重新定义理解。我们将理解形式化为输入句子与其潜在表示之间的互信息（句子级 MI），衡量输入信息在潜在表示中的保留效果。由于LLMs为单个令牌学习嵌入，我们将句子级 MI分解为令牌与句子嵌入之间的令牌级 MI，并建立了连接这些度量的理论界限。利用Fano不等式，我们推导出一个可计算的令牌级 MI下限，直接关联到从句子嵌入中预测原始令牌的能力（令牌级可恢复性）。通过实现这一可恢复性任务，我们比较测量了不同LLMs的MI，发现编码器-only模型始终维持更高的信息保真度，而解码器-only模型则表现出后期层数“遗忘”模式，即互信息先增强后被丢弃。此外，通过微调以最大化令牌级可恢复性，LLMs在无特定任务监督的情况下，其理解能力得到持续提升，证明互信息可作为理解与提升语言模型能力的基础。


> Recent advances in large language models (LLMs) have revolutionized natural language processing, yet evaluating their intrinsic linguistic understanding remains challenging. Moving beyond specialized evaluation tasks, we propose an information-theoretic framework grounded in mutual information (MI) to achieve this. We formalize the understanding as MI between an input sentence and its latent representation (sentence-level MI), measuring how effectively input information is preserved in latent representation. Given that LLMs learn embeddings for individual tokens, we decompose sentence-level MI into token-level MI between tokens and sentence embeddings, establishing theoretical bounds connecting these measures. Based on this foundation, we theoretically derive a computable lower bound for token-level MI using Fano's inequality, which directly relates to token-level recoverability-the ability to predict original tokens from sentence embedding. We implement this recoverability task to comparatively measure MI across different LLMs, revealing that encoder-only models consistently maintain higher information fidelity than their decoder-only counterparts, with the latter exhibiting a distinctive late-layer "forgetting" pattern where mutual information is first enhanced and then discarded. Moreover, fine-tuning to maximize token-level recoverability consistently improves understanding ability of LLMs on tasks without task-specific supervision, demonstrating that mutual information can serve as a foundation for understanding and improving language model capabilities.

[Arxiv](https://arxiv.org/abs/2505.23790)