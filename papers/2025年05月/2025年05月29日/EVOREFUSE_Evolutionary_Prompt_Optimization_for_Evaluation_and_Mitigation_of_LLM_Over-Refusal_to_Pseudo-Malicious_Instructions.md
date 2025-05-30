# EVOREFUSE：进化提示优化，针对大语言模型对伪恶意指令过度拒绝的评估与缓解

发布时间：2025年05月29日

`LLM应用` `人工智能安全` `用户体验`

> EVOREFUSE: Evolutionary Prompt Optimization for Evaluation and Mitigation of LLM Over-Refusal to Pseudo-Malicious Instructions

# 摘要

> 大型语言模型（LLMs）在面对伪恶意指令时常常表现出过度拒绝：这些看似无害的输入查询由于保守的安全对齐机制，触发了不必要的模型拒绝，严重影响了用户体验。收集这类指令对于评估和缓解过度拒绝问题至关重要，但现有方法如手动创建或指令重写，要么难以扩展，要么无法生成足够多样且有效的触发拒绝的提示。为了解决这些问题，我们提出了一种名为EVOREFUSE的提示优化方法，能够生成多样化的伪恶意指令，这些指令可以持续触发LLMs的自信拒绝。EVOREFUSE采用进化算法，通过变异策略和重组，比现有方法更全面地探索指令空间，并迭代优化种子指令，以最大化LLM拒绝概率的证据下界。基于EVOREFUSE，我们创建了两个创新数据集：EVOREFUSE-TEST包含582条伪恶意指令，相比下一个最佳基准，在9个LLMs上平均触发拒绝率高出140.41%，词汇多样性增加34.86%，LLM回应信心评分提升40.03%；EVOREFUSE-ALIGN提供了3,000条带有回应的伪恶意指令，用于监督和基于偏好的对齐训练。在EVOREFUSE-ALIGN上进行监督微调的LLAMA3.1-8B-INSTRUCT模型，相比使用第二个最佳对齐数据集训练的模型，过度拒绝减少了14.31%，同时未影响安全性。通过使用EVOREFUSE-TEST进行分析，我们发现模型在触发过度拒绝时过于关注敏感关键词，而忽略了更广泛的上下文。

> Large language models (LLMs) frequently refuse to respond to pseudo-malicious instructions: semantically harmless input queries triggering unnecessary LLM refusals due to conservative safety alignment, significantly impairing user experience. Collecting such instructions is crucial for evaluating and mitigating over-refusals, but existing instruction curation methods, like manual creation or instruction rewriting, either lack scalability or fail to produce sufficiently diverse and effective refusal-inducing prompts. To address these limitations, we introduce EVOREFUSE, a prompt optimization approach that generates diverse pseudo-malicious instructions consistently eliciting confident refusals across LLMs. EVOREFUSE employs an evolutionary algorithm exploring the instruction space in more diverse directions than existing methods via mutation strategies and recombination, and iteratively evolves seed instructions to maximize evidence lower bound on LLM refusal probability. Using EVOREFUSE, we create two novel datasets: EVOREFUSE-TEST, a benchmark of 582 pseudo-malicious instructions that outperforms the next-best benchmark with 140.41% higher average refusal triggering rate across 9 LLMs, 34.86% greater lexical diversity, and 40.03% improved LLM response confidence scores; and EVOREFUSE-ALIGN, which provides 3,000 pseudo-malicious instructions with responses for supervised and preference-based alignment training. LLAMA3.1-8B-INSTRUCT supervisedly fine-tuned on EVOREFUSE-ALIGN achieves up to 14.31% fewer over-refusals than models trained on the second-best alignment dataset, without compromising safety. Our analysis with EVOREFUSE-TEST reveals models trigger over-refusals by overly focusing on sensitive keywords while ignoring broader context.

[Arxiv](https://arxiv.org/abs/2505.23473)