# 针对低资源语言任务，本研究探讨如何运用商业大型语言模型进行成本与性能的优化，以期在保证任务完成质量的同时，有效控制处理此类任务的成本。

发布时间：2024年03月08日

`LLM应用`

> Cost-Performance Optimization for Processing Low-Resource Language Tasks Using Commercial LLMs

# 摘要

> LLMs 对于高资源语言的表现卓越，在零样本/少量样本情况下仍能实现高质量的推理与生成。尽管少数 LLM 经过针对低资源语言的训练，并取得了一定效果，但因训练成本问题，它们普遍作为计费型网络服务存在，费用按输入和输出令牌数计算。而令牌数量的多少受制于语言、脚本及LLM子词词汇等因素，不幸的是，LRLs在此机制下处于价格劣势，因为当前主流的LLMs处理LRLs时产生的令牌更多，原因在于这些LLMs主要针对HRLs的词汇表进行了优化。我们的目标是平衡这一局面，在保证预测和生成品质的前提下，降低当代LLMs处理LRLs的成本。为此，我们探讨了通过混码、翻译及转写等方式将LRLs转换为HRLs来缩减LLM处理的令牌数量。利用包含15种印度语言数据的IndicXTREME数据集，结合迄今最昂贵的商用LLM服务之一GPT-4进行深入研究，我们揭示并剖析了跨越多种语言和任务的令牌数、成本与质量之间的有趣关联。研究表明，通过精心设计与LLM交互的最佳策略，可以在保持甚至提升性能的同时，将成本最高削减90%，远胜于直接采用原始LRL与LLM交流的方式。

> Large Language Models (LLMs) exhibit impressive zero/few-shot inference and generation quality for high-resource languages(HRLs). A few of them have been trained in low-resource languages (LRLs) and give decent performance. Owing to the prohibitive costs of training LLMs, they are usually used as a network service, with the client charged by the count of input and output tokens. The number of tokens strongly depends on the script and language, as well as the LLM's sub-word vocabulary. We show that LRLs are at a pricing disadvantage, because the well-known LLMs produce more tokens for LRLs than HRLs. This is because most currently popular LLMs are optimized for HRL vocabularies. Our objective is to level the playing field: reduce the cost of processing LRLs in contemporary LLMs while ensuring that predictive and generative qualities are not compromised. As means to reduce the number of tokens processed by the LLM, we consider code-mixing, translation, and transliteration of LRLs to HRLs. We perform an extensive study using the IndicXTREME dataset, covering 15 Indian languages, while using GPT-4 (one of the costliest LLM services released so far) as a commercial LLM. We observe and analyze interesting patterns involving token count, cost,and quality across a multitude of languages and tasks. We show that choosing the best policy to interact with the LLM can reduce cost by 90% while giving better or comparable performance, compared to communicating with the LLM in the original LRL.

[Arxiv](https://arxiv.org/abs/2403.05434)