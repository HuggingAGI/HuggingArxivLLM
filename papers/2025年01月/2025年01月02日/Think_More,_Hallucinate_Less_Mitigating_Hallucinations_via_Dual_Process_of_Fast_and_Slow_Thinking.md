# 多思少幻：通过快慢思维双管齐下，减少幻觉

发布时间：2025年01月02日

`LLM应用

理由：这篇论文提出了一个名为HaluSearch的框架，旨在通过引入基于树搜索的算法（如MCTS）来缓解大型语言模型（LLMs）在推理中的幻觉问题。该框架通过显式的慢思考生成过程和自评估奖励模型来引导生成路径，从而提高文本生成的可靠性和准确性。这种方法直接应用于LLMs的文本生成过程，属于LLM应用的范畴。` `认知科学`

> Think More, Hallucinate Less: Mitigating Hallucinations via Dual Process of Fast and Slow Thinking

# 摘要

> 大型语言模型（LLMs）虽然能力卓越，但幻觉问题依然存在。传统文本生成方法依赖自回归生成，缺乏深度推理，常导致不可靠且事实错误的输出。本文提出HaluSearch框架，通过引入基于树搜索的算法（如MCTS），实现显式的慢思考生成过程，有效缓解LLMs在推理中的幻觉问题。HaluSearch将文本生成视为逐步推理，利用自评估奖励模型为每一步生成评分，引导树搜索走向最可靠的生成路径，充分挖掘LLMs的内部知识。为平衡效率与质量，我们借鉴认知科学的双过程理论，设计分层思维系统切换机制，在实例和步骤层面动态切换快慢思维模式，灵活应对问题复杂性和推理状态。我们在中英文数据集上的实验表明，该方法显著优于基线模型。

> Large language models (LLMs) demonstrate exceptional capabilities, yet still face the hallucination issue. Typical text generation approaches adopt an auto-regressive generation without deliberate reasoning, which often results in untrustworthy and factually inaccurate responses. In this paper, we propose HaluSearch, a novel framework that incorporates tree search-based algorithms (e.g. MCTS) to enable an explicit slow thinking generation process for mitigating hallucinations of LLMs during inference. Specifically, HaluSearch frames text generation as a step-by-step reasoning process, using a self-evaluation reward model to score each generation step and guide the tree search towards the most reliable generation pathway for fully exploiting the internal knowledge of LLMs. To balance efficiency and quality, we introduce a hierarchical thinking system switch mechanism inspired by the dual process theory in cognitive science, which dynamically alternates between fast and slow thinking modes at both the instance and step levels, adapting to the complexity of questions and reasoning states. We conduct extensive experiments on both English and Chinese datasets and the results show that our approach significantly outperforms baseline approaches.

[Arxiv](https://arxiv.org/abs/2501.01306)