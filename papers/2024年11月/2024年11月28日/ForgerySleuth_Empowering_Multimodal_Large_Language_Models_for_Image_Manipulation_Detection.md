# ForgerySleuth：助力多模态大型语言模型进行图像篡改检测

发布时间：2024年11月28日

`LLM应用` `图像操纵检测` `多模态任务`

> ForgerySleuth: Empowering Multimodal Large Language Models for Image Manipulation Detection

# 摘要

> 多模态大型语言模型为各类多模态任务带来了新机遇。然而，其在图像操纵检测领域的潜力尚未得到挖掘。当直接用于 IMD 任务时，M-LLMs 常常生成存在幻觉和过度思考的推理文本。为此，在本研究中，我们提出了 ForgerySleuth，它借助 M-LLMs 进行全面的线索融合，并生成能指出被篡改特定区域的分割输出。另外，我们通过线索链提示构建了 ForgeryAnalysis 数据集，其中涵盖分析和推理文本，以优化图像操纵检测任务。同时还引入了一个数据引擎，为预训练阶段构建更大规模的数据集。我们大量的实验证实了 ForgeryAnalysis 的有效性，且表明 ForgerySleuth 在泛化、鲁棒和可解释方面显著优于现有方法。

> Multimodal large language models have unlocked new possibilities for various multimodal tasks. However, their potential in image manipulation detection remains unexplored. When directly applied to the IMD task, M-LLMs often produce reasoning texts that suffer from hallucinations and overthinking. To address this, in this work, we propose ForgerySleuth, which leverages M-LLMs to perform comprehensive clue fusion and generate segmentation outputs indicating specific regions that are tampered with. Moreover, we construct the ForgeryAnalysis dataset through the Chain-of-Clues prompt, which includes analysis and reasoning text to upgrade the image manipulation detection task. A data engine is also introduced to build a larger-scale dataset for the pre-training phase. Our extensive experiments demonstrate the effectiveness of ForgeryAnalysis and show that ForgerySleuth significantly outperforms existing methods in generalization, robustness, and explainability.

[Arxiv](https://arxiv.org/abs/2411.19466)