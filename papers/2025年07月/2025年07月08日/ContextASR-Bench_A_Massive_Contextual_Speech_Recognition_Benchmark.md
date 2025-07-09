# ContextASR-Bench：一个大规模上下文语音识别基准测试平台

发布时间：2025年07月08日

`LLM应用` `人工智能` `语音识别`

> ContextASR-Bench: A Massive Contextual Speech Recognition Benchmark

# 摘要

> 自动语音识别（ASR）技术已得到深入研究，但传统的评估方法大多局限于无上下文的场景。这是因为传统ASR模型在上下文建模、记忆和基于世界知识的推理方面存在明显不足。随着大型语言模型（LLMs）及其对应的大型音频语言模型（LALMs）的突破性发展，通用人工智能能力受到广泛关注。因此，我们需要一个能够全面评估ASR系统通用性和智能性的基准测试。为此，我们提出了ContextASR-Bench：一个全面、大规模的基准测试，专注于评估基于上下文的语音识别能力。该基准涵盖超过10个领域，包含多达40,000个数据条目，能够全面评估模型在忽略或包含粗粒度或细粒度上下文信息场景下的性能表现。此外，与传统ASR评估不同，我们的基准还包括对模型在识别听觉输入中提到的命名实体方面的有效性分析。通过广泛评估我们发现，LALMs凭借其强大的世界知识和上下文学习能力，在性能上远超传统ASR模型。该数据集和评估代码已在https://github.com/MrSupW/ContextASR-Bench上公开发布。

> Automatic Speech Recognition (ASR) has been extensively investigated, yet prior evaluative efforts have largely been restricted to contextless paradigms. This constraint stems from the limited proficiency of conventional ASR models in context modeling and their deficiency in memory and reasoning based on world knowledge. Recent breakthroughs in the development of Large Language Models (LLMs) and corresponding Large Audio Language Models (LALMs) have markedly enhanced the visibility of general artificial intelligence capabilities. Consequently, there exists a compelling need for a benchmark that can evaluate both the generality and intelligence of ASR systems. To address this gap, we propose ContextASR-Bench: a comprehensive, large-scale benchmark designed to assess contextual speech recognition. This benchmark encompasses up to 40,000 data entries across over 10 domains, enabling a thorough evaluation of model performance in scenarios that omit or incorporate coarse-grained or fine-grained contextual information. Moreover, diverging from conventional ASR evaluations, our benchmark includes an analysis of model efficacy in recognizing named entities mentioned within the auditory input. Our extensive evaluation highlights that LALMs, with strong world knowledge and context learning capabilities, outperform conventional ASR models by a large margin. The dataset and evaluation code have been released at https://github.com/MrSupW/ContextASR-Bench.

[Arxiv](https://arxiv.org/abs/2507.05727)