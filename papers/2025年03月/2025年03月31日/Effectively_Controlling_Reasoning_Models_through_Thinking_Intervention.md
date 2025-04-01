# # 通过思维干预有效控制推理模型
利用思维干预实现推理模型的有效控制

发布时间：2025年03月31日

`LLM理论` `人工智能`

> Effectively Controlling Reasoning Models through Thinking Intervention

# 摘要

> 增强推理的大型语言模型（LLMs）通过在生成最终答案前显式生成中间推理步骤，展现了在复杂问题解决中的卓越能力。本文提出了一种新兴的生成框架，为更精细地控制模型行为提供了独特机会。我们创新性地提出Thinking Intervention范式，通过战略性地插入或修改特定思考令牌，显式引导LLMs的内部推理过程。我们对多个任务进行了全面评估，包括IFEval上的指令遵循、SEP上的指令层次结构，以及XSTest和SORRY-Bench上的安全对齐。实验结果表明，Thinking Intervention显著超越基线提示方法，使用开源DeepSeek R1模型，在指令遵循场景中准确率提升高达6.7%，推理指令层次结构提升15.4%，对不安全提示的拒绝率更是激增40.0%。总体而言，我们的研究为控制推理型LLMs开辟了富有潜力的新方向。

> Reasoning-enhanced large language models (LLMs) explicitly generate intermediate reasoning steps prior to generating final answers, helping the model excel in complex problem-solving. In this paper, we demonstrate that this emerging generation framework offers a unique opportunity for more fine-grained control over model behavior. We propose Thinking Intervention, a novel paradigm designed to explicitly guide the internal reasoning processes of LLMs by strategically inserting or revising specific thinking tokens. We conduct comprehensive evaluations across multiple tasks, including instruction following on IFEval, instruction hierarchy on SEP, and safety alignment on XSTest and SORRY-Bench. Our results demonstrate that Thinking Intervention significantly outperforms baseline prompting approaches, achieving up to 6.7% accuracy gains in instruction-following scenarios, 15.4% improvements in reasoning about instruction hierarchies, and a 40.0% increase in refusal rates for unsafe prompts using open-source DeepSeek R1 models. Overall, our work opens a promising new research avenue for controlling reasoning LLMs.

[Arxiv](https://arxiv.org/abs/2503.24370)