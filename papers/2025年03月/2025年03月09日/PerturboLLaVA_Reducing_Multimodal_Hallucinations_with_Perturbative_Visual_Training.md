# # PerturboLLaVA：利用扰动视觉训练降低多模态幻觉

发布时间：2025年03月09日

`LLM应用` `计算机视觉`

> PerturboLLaVA: Reducing Multimodal Hallucinations with Perturbative Visual Training

# 摘要

> 本文聚焦于多模态大语言模型（MLLMs）在密集图像字幕任务中的幻觉问题。我们发现现有评估指标在概念层面难以精细衡量字幕质量，因此提出HalFscore这一新指标。HalFscore基于语言图构建，旨在从细粒度层面全面评估密集字幕的准确性和完整性。针对幻觉现象，我们深入分析发现其根本原因在于模型对语言先验的过度依赖。为解决这一问题，我们提出PerturboLLaVA方法。该方法通过在训练过程中引入对抗扰动文本，有效降低模型对语言先验的依赖，使模型更加专注于视觉输入。这不仅显著减少了幻觉现象，还能生成准确且基于图像的描述，且无需额外计算开销。实验结果表明，PerturboLLaVA在提升字幕保真度方面表现优异，超越现有方法，尤其在处理多模态幻觉问题时展现出显著优势，并在通用多模态基准测试中取得更好的性能表现。

> This paper aims to address the challenge of hallucinations in Multimodal Large Language Models (MLLMs) particularly for dense image captioning tasks. To tackle the challenge, we identify the current lack of a metric that finely measures the caption quality in concept level. We hereby introduce HalFscore, a novel metric built upon the language graph and is designed to evaluate both the accuracy and completeness of dense captions at a granular level. Additionally, we identify the root cause of hallucination as the model's over-reliance on its language prior. To address this, we propose PerturboLLaVA, which reduces the model's reliance on the language prior by incorporating adversarially perturbed text during training. This method enhances the model's focus on visual inputs, effectively reducing hallucinations and producing accurate, image-grounded descriptions without incurring additional computational overhead. PerturboLLaVA significantly improves the fidelity of generated captions, outperforming existing approaches in handling multimodal hallucinations and achieving improved performance across general multimodal benchmarks.

[Arxiv](https://arxiv.org/abs/2503.06486)