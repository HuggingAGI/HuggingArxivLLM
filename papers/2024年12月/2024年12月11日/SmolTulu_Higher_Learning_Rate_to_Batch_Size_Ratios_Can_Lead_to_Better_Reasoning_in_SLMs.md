# SmolTulu：在 SLMs 里，学习率与批量大小的比率越高，可能越有助于实现更好的推理。

发布时间：2024年12月11日

`LLM应用` `语言模型` `模型开发`

> SmolTulu: Higher Learning Rate to Batch Size Ratios Can Lead to Better Reasoning in SLMs

# 摘要

> 我们推出了 SmolTulu-1.7b-Instruct，在本报告中称为 SmolTulu-DPO-1130，这是一个经指令调整的语言模型，它对 AllenAI 的 Tulu 3 后训练管道加以调整，以增强 Huggingface 的 SmolLM2-1.7B 基础模型。通过运用 1.35 亿参数模型展开全面的实证分析，我们表明学习率与批量大小的关系会以任务依赖的方式显著影响模型性能。我们的发现呈现出明显的差异：诸如 ARC 和 GSM8K 这类推理任务得益于较高的学习率与批量大小比率，而像 HellaSwag 和 IFEval 这样的模式识别任务在较低比率时表现最优。这些见解助力了 SmolTulu 的开发，它在 20 亿以下参数模型的指令遵循方面达到了领先水平，在 IFEval 上得分 67.7%（$Δ$11%），在 GSM8K 上数学推理得分 51.6%（$Δ$3.4%），另一个版本在 ARC 上得分 57.1%（$\Delta5.4%$）。我们发布了模型、训练配方和消融研究，以推动高效模型对齐方面的进一步研究，表明对优化动态的精心调整能够助力缩小小型和大型语言模型之间的能力差距。

> We present SmolTulu-1.7b-Instruct, referenced in this report as SmolTulu-DPO-1130, an instruction-tuned language model that adapts AllenAI's Tulu 3 post-training pipeline to enhance Huggingface's SmolLM2-1.7B base model. Through comprehensive empirical analysis using a 135M parameter model, we demonstrate that the relationship between learning rate and batch size significantly impacts model performance in a task-dependent manner. Our findings reveal a clear split: reasoning tasks like ARC and GSM8K benefit from higher learning rate to batch size ratios, while pattern recognition tasks such as HellaSwag and IFEval show optimal performance with lower ratios. These insights informed the development of SmolTulu, which achieves state-of-the-art performance among sub-2B parameter models on instruction following, scoring 67.7% on IFEval ($Δ$11%), and mathematical reasoning with 51.6% on GSM8K ($Δ$3.4%), with an alternate version achieving scoring 57.1% on ARC ($\Delta5.4%$). We release our model, training recipes, and ablation studies to facilitate further research in efficient model alignment, demonstrating that careful adaptation of optimization dynamics can help bridge the capability gap between small and large language models.

[Arxiv](https://arxiv.org/abs/2412.08347)