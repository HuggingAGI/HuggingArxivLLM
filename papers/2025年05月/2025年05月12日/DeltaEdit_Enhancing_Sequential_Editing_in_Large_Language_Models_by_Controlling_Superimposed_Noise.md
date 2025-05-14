# DeltaEdit：借助对叠加噪声的精准控制，显著提升大型语言模型的序列编辑能力

发布时间：2025年05月12日

`LLM理论` `机器学习`

> DeltaEdit: Enhancing Sequential Editing in Large Language Models by Controlling Superimposed Noise

# 摘要

> 序列知识编辑技术以低成本持续更新大型语言模型，防止生成过时或错误信息。然而，现有方法在长期编辑后，成功率显著下降。我们发现，随着编辑次数增加，模型输出偏离预期目标，导致成功率下降，这一问题被称为叠加噪声积累问题。为解决此问题，我们识别了导致偏离的因素，并提出DeltaEdit方法。该方法通过动态正交约束策略优化更新参数，有效减少编辑间干扰，缓解偏离问题。实验表明，DeltaEdit在编辑成功率和保持泛化能力方面显著优于现有方法，即使在大量编辑下，也能确保模型性能稳定可靠。

> Sequential knowledge editing techniques aim to continuously update the knowledge in large language models at a low cost, preventing the models from generating outdated or incorrect information. However, existing sequential editing methods suffer from a significant decline in editing success rates after long-term editing. Through theoretical analysis and experiments, we identify that as the number of edits increases, the model's output increasingly deviates from the desired target, leading to a drop in editing success rates. We refer to this issue as the accumulation of superimposed noise problem. To address this, we identify the factors contributing to this deviation and propose DeltaEdit, a novel method that optimizes update parameters through a dynamic orthogonal constraints strategy, effectively reducing interference between edits to mitigate deviation. Experimental results demonstrate that DeltaEdit significantly outperforms existing methods in edit success rates and the retention of generalization capabilities, ensuring stable and reliable model performance even under extensive sequential editing.

[Arxiv](https://arxiv.org/abs/2505.07899)