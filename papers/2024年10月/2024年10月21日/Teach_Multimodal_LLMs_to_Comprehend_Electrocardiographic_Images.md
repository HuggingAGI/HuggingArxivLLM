# 让多模态大语言模型学会解读心电图图像

发布时间：2024年10月21日

`LLM应用` `心电图`

> Teach Multimodal LLMs to Comprehend Electrocardiographic Images

# 摘要

> 心电图（ECG）是评估心脏状况的重要非侵入性诊断工具。然而，现有的自动解释方法泛化能力有限，主要集中在少数心脏状况上，且依赖原始生理信号，这在资源有限的环境中难以获取，通常只能获得打印或数字ECG图像。最近，多模态大型语言模型（MLLMs）的进展为解决这些挑战带来了希望。但由于缺乏指令调优数据集和成熟的ECG图像基准，MLLMs在ECG图像解释中的应用仍面临挑战。为此，我们推出了ECGInstruct，一个包含超过一百万样本的全面ECG图像指令调优数据集，涵盖多种ECG相关任务。基于ECGInstruct，我们开发了PULSE，一个专为ECG图像理解设计的MLLM。此外，我们还构建了ECGBench，一个涵盖九个数据集中四个关键ECG图像解释任务的评估基准。实验表明，PULSE在准确率上比通用MLLMs平均提升了15%到30%，达到了新的技术高度。这项工作展示了PULSE在临床实践中提升ECG解释的潜力。

> The electrocardiogram (ECG) is an essential non-invasive diagnostic tool for assessing cardiac conditions. Existing automatic interpretation methods suffer from limited generalizability, focusing on a narrow range of cardiac conditions, and typically depend on raw physiological signals, which may not be readily available in resource-limited settings where only printed or digital ECG images are accessible. Recent advancements in multimodal large language models (MLLMs) present promising opportunities for addressing these challenges. However, the application of MLLMs to ECG image interpretation remains challenging due to the lack of instruction tuning datasets and well-established ECG image benchmarks for quantitative evaluation. To address these challenges, we introduce ECGInstruct, a comprehensive ECG image instruction tuning dataset of over one million samples, covering a wide range of ECG-related tasks from diverse data sources. Using ECGInstruct, we develop PULSE, an MLLM tailored for ECG image comprehension. In addition, we curate ECGBench, a new evaluation benchmark covering four key ECG image interpretation tasks across nine different datasets. Our experiments show that PULSE sets a new state-of-the-art, outperforming general MLLMs with an average accuracy improvement of 15% to 30%. This work highlights the potential of PULSE to enhance ECG interpretation in clinical practice.

[Arxiv](https://arxiv.org/abs/2410.19008)