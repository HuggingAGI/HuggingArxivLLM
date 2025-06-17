# # 低资源语言LLM数据生成策略的严谨评估

发布时间：2025年06月13日

`LLM应用

摘要中讨论了大型语言模型（LLMs）在生成合成文本数据方面的应用，特别是针对低资源语言环境中的生成策略比较。研究评估了多种生成策略及其组合在不同语言中的性能，并探讨了这些策略在实际任务中的有效性。因此，这篇论文属于LLM应用类别。` `合成数据生成`

> A Rigorous Evaluation of LLM Data Generation Strategies for Low-Resource Languages

# 摘要

> 大型语言模型（LLMs）正被越来越多地用于生成合成文本数据，以训练更小的专用模型。然而，针对低资源语言环境的各种生成策略的比较研究尚不充分。尽管已经提出了多种提示策略，例如演示、基于标签的摘要和自我修订，但它们在低资源语言中的相对有效性仍不清楚。本文系统地评估了这些生成策略及其组合在11种类型多样语言中的性能，其中包括几种极度低资源的语言。我们使用三个NLP任务和四个开源的LLMs，评估生成数据与标准数据在下游模型上的表现。我们的结果显示，生成方法的策略性组合，特别是目标语言的演示结合基于LLM的修订，能够取得优异性能，使与真实数据的差距在某些情况下缩小到仅5%。此外，我们发现智能提示技术可以减少大型LLMs的优势，突出了在低资源场景中使用较小模型进行合成数据生成的有效策略。

> Large Language Models (LLMs) are increasingly used to generate synthetic textual data for training smaller specialized models. However, a comparison of various generation strategies for low-resource language settings is lacking. While various prompting strategies have been proposed, such as demonstrations, label-based summaries, and self-revision, their comparative effectiveness remains unclear, especially for low-resource languages. In this paper, we systematically evaluate the performance of these generation strategies and their combinations across 11 typologically diverse languages, including several extremely low-resource ones. Using three NLP tasks and four open-source LLMs, we assess downstream model performance on generated versus gold-standard data. Our results show that strategic combinations of generation methods, particularly target-language demonstrations with LLM-based revisions, yield strong performance, narrowing the gap with real data to as little as 5% in some settings. We also find that smart prompting techniques can reduce the advantage of larger LLMs, highlighting efficient generation strategies for synthetic data generation in low-resource scenarios with smaller models.

[Arxiv](https://arxiv.org/abs/2506.12158)