# # GEM: 赋能多模态语言模型实现基于体征的ECG理解，融合时间序列与图像信息

发布时间：2025年03月08日

`LLM应用` `心电图解读`

> GEM: Empowering MLLM for Grounded ECG Understanding with Time Series and Images

# 摘要

> 尽管近期的多模态大型语言模型（MLLMs）在自动化心电图解读方面取得了进展，但它们仍面临两大关键限制：（1）时间序列信号与视觉心电图表示之间的多模态协同作用不足；（2）在将诊断结果与精细的波形证据关联时，解释性有限。我们引入了GEM，这是首个统一心电图时间序列、12导联心电图图像和文本的MLLM，旨在实现基于证据且与临床医生思路一致的心电图解读。通过三个核心创新，GEM实现了基于特征的分析、基于证据的推理以及类似临床医生的诊断流程：一种双编码器框架，用于提取互补的时间序列和图像特征；跨模态对齐，以实现有效的多模态理解；以及知识引导的指令生成，用于创建高粒度的接地数据（ECG-Grounding），将诊断结果与可测量参数（例如，QRS/PR间期）关联。此外，我们提出了“基于证据的心电图理解”任务，这是一个以临床应用为导向的基准测试，旨在全面评估MLLM在基于证据的心电图理解方面的能力。在现有基准和我们提出的基准上的实验结果表明，GEM在预测性能（CSN提升7.4%）、解释性（提升22.7%）和接地能力（提升24.8%）方面均有显著提升，使其更适用于实际临床应用。GitHub仓库地址：https://github.com/lanxiang1017/GEM.git

> While recent multimodal large language models (MLLMs) have advanced automated ECG interpretation, they still face two key limitations: (1) insufficient multimodal synergy between time series signals and visual ECG representations, and (2) limited explainability in linking diagnoses to granular waveform evidence. We introduce GEM, the first MLLM unifying ECG time series, 12-lead ECG images and text for grounded and clinician-aligned ECG interpretation. GEM enables feature-grounded analysis, evidence-driven reasoning, and a clinician-like diagnostic process through three core innovations: a dual-encoder framework extracting complementary time series and image features, cross-modal alignment for effective multimodal understanding, and knowledge-guided instruction generation for generating high-granularity grounding data (ECG-Grounding) linking diagnoses to measurable parameters ($e.g.$, QRS/PR Intervals). Additionally, we propose the Grounded ECG Understanding task, a clinically motivated benchmark designed to comprehensively assess the MLLM's capability in grounded ECG understanding. Experimental results on both existing and our proposed benchmarks show GEM significantly improves predictive performance (CSN $7.4\% \uparrow$), explainability ($22.7\% \uparrow$), and grounding ($24.8\% \uparrow$), making it more suitable for real-world clinical applications. GitHub repository: https://github.com/lanxiang1017/GEM.git

[Arxiv](https://arxiv.org/abs/2503.06073)