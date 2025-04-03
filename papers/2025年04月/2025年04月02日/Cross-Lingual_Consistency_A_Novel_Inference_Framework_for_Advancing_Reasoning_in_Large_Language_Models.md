# 跨语言一致性：助力大型语言模型推理能力的新框架

发布时间：2025年04月02日

`LLM理论`

> Cross-Lingual Consistency: A Novel Inference Framework for Advancing Reasoning in Large Language Models

# 摘要

> 思维链（CoT）已成为提升大型语言模型（LLMs）推理能力的关键机制，而自我一致性在提高性能方面展现出显著潜力。然而，多语言训练语料库中固有的语言偏见常常引发语义漂移和逻辑不一致，尤其是在处理复杂推理任务的100亿参数以下的LLMs中。为克服这些限制，我们提出了跨语言一致性（CLC）框架——一种创新的推理范式，通过多数投票整合多语言推理路径，从而提升LLMs的推理能力。在CMATH数据集上的实证评估显示，与传统的自我一致性方法相比，CLC表现出色，分别为DeepSeek-Math-7B-Instruct、Qwen2.5-Math-7B-Instruct和Gemma2-9B-Instruct带来9.5%、6.5%和6.0%的绝对准确率提升。将CLC的语言范围扩展至11种多样化语言，带来了两大协同优势：1）通过多语言集成投票中和多语言训练语料库中的语言偏见；2）通过探索更广阔的多语言解决方案空间，摆脱单语推理陷阱。这两大优势使CLC在推理路径上相较于单语自我一致性基线更具全局最优性，这一点在Gemma2-9B-Instruct于MGSM数据集上实现4.1%-18.5%的准确率提升中得到印证。

> Chain-of-thought (CoT) has emerged as a critical mechanism for enhancing reasoning capabilities in large language models (LLMs), with self-consistency demonstrating notable promise in boosting performance. However, inherent linguistic biases in multilingual training corpora frequently cause semantic drift and logical inconsistencies, especially in sub-10B parameter LLMs handling complex inference tasks. To overcome these constraints, we propose the Cross-Lingual Consistency (CLC) framework, an innovative inference paradigm that integrates multilingual reasoning paths through majority voting to elevate LLMs' reasoning capabilities. Empirical evaluations on the CMATH dataset reveal CLC's superiority over the conventional self-consistency method, delivering 9.5%, 6.5%, and 6.0% absolute accuracy gains for DeepSeek-Math-7B-Instruct, Qwen2.5-Math-7B-Instruct, and Gemma2-9B-Instruct respectively. Expanding CLC's linguistic scope to 11 diverse languages implies two synergistic benefits: 1) neutralizing linguistic biases in multilingual training corpora through multilingual ensemble voting, 2) escaping monolingual reasoning traps by exploring the broader multilingual solution space. This dual benefits empirically enables more globally optimal reasoning paths compared to monolingual self-consistency baselines, as evidenced by the 4.1%-18.5% accuracy gains using Gemma2-9B-Instruct on the MGSM dataset.

[Arxiv](https://arxiv.org/abs/2504.01857)