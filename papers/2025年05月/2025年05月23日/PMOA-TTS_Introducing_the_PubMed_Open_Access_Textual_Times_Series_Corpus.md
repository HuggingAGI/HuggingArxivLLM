# PMOA-TTS：推出PubMed开放获取文本时间序列语料库

发布时间：2025年05月23日

`LLM应用` `时间序列`

> PMOA-TTS: Introducing the PubMed Open Access Textual Times Series Corpus

# 摘要

> 临床叙述中的时间动态分析对建模患者轨迹至关重要，但大规模时间标注资源仍显稀缺。我们推出PMOA-TTS，这是首个公开可用的数据集，包含124,699份PubMed开放获取（PMOA）病例报告，每份报告经由可扩展的基于LLM的管道转换为结构化的（事件，时间）时间线。我们的方法巧妙结合启发式过滤与Llama 3.3识别单个患者的病例报告，并借助Llama 3.3和DeepSeek R1进行基于提示的提取，最终生成超过560万个带有时间戳的临床事件。通过与临床医生整理的参考集对比，采用事件级别匹配（余弦相似度阈值为0.1时匹配率80%）、时间一致性（c-index > 0.90）和基于时间戳对齐的对数时间累积分布下的面积（AULTC）三大指标评估时间线质量。语料库级别的分析表明，该数据集涵盖了广泛的诊断和人口统计信息。在下游生存预测任务中，提取时间线生成的嵌入达到了高达0.82 ± 0.01的时间依赖性一致性指数，充分证明了时间结构化叙述的预测价值。PMOA-TTS为生物医学NLP领域的时间线提取、时间推理和纵向建模提供了强大的可扩展基础。该数据集现已开放获取，访问链接为：https://huggingface.co/datasets/snoroozi/pmoa-tts。


> Understanding temporal dynamics in clinical narratives is essential for modeling patient trajectories, yet large-scale temporally annotated resources remain limited. We present PMOA-TTS, the first openly available dataset of 124,699 PubMed Open Access (PMOA) case reports, each converted into structured (event, time) timelines via a scalable LLM-based pipeline. Our approach combines heuristic filtering with Llama 3.3 to identify single-patient case reports, followed by prompt-driven extraction using Llama 3.3 and DeepSeek R1, resulting in over 5.6 million timestamped clinical events. To assess timeline quality, we evaluate against a clinician-curated reference set using three metrics: (i) event-level matching (80% match at a cosine similarity threshold of 0.1), (ii) temporal concordance (c-index > 0.90), and (iii) Area Under the Log-Time CDF (AULTC) for timestamp alignment. Corpus-level analysis shows wide diagnostic and demographic coverage. In a downstream survival prediction task, embeddings from extracted timelines achieve time-dependent concordance indices up to 0.82 $\pm$ 0.01, demonstrating the predictive value of temporally structured narratives. PMOA-TTS provides a scalable foundation for timeline extraction, temporal reasoning, and longitudinal modeling in biomedical NLP. The dataset is available at: https://huggingface.co/datasets/snoroozi/pmoa-tts .

[Arxiv](https://arxiv.org/abs/2505.20323)