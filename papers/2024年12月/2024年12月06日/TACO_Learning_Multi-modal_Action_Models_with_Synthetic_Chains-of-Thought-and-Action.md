# TACO：借助合成的思维与行动链来学习多模态行动模型

发布时间：2024年12月06日

`LLM应用` `多模态`

> TACO: Learning Multi-modal Action Models with Synthetic Chains-of-Thought-and-Action

# 摘要

> 虽然开源的多模态语言模型在简单问答任务中表现出色，但在需要多种能力（如细粒度识别、视觉基础和推理）以及多步骤解决方案的复杂问题上却常常表现不佳。我们推出了 TACO，这一系列的多模态大动作模型旨在提升此类复杂、多步骤和多模态任务的表现。在推理时，TACO 生成思维与行动链（CoTA），通过调用诸如 OCR、深度估计和计算器等外部工具执行中间步骤，然后整合思维和行动的输出以给出连贯的回应。为训练 TACO，我们创建了一个包含超 100 万个由 GPT-4o 和 Python 程序生成的合成 CoTA 轨迹的大型数据集。接着，我们尝试了各种数据过滤和混合技术，获取了 293K 个高质量 CoTA 示例的最终子集。该数据集让 TACO 能够学习复杂的推理和行动路径，超越了仅在有直接答案的指令调整数据上训练的现有模型。我们的模型 TACO 在 8 个基准测试中优于指令调整的基线，平均提升了 3.6％，在涉及 OCR、数学推理和空间推理的 MMVet 任务中最多提升了 15％。基于高质量 CoTA 轨迹的训练为复杂的多模态推理树立了新标杆，凸显了在提升开源多模态模型能力方面对结构化、多步骤指令调整的需求。

> While open-source multi-modal language models perform well on simple question answering tasks, they often fail on complex questions that require multiple capabilities, such as fine-grained recognition, visual grounding, and reasoning, and that demand multi-step solutions. We present TACO, a family of multi-modal large action models designed to improve performance on such complex, multi-step, and multi-modal tasks. During inference, TACO produces chains-of-thought-and-action (CoTA), executes intermediate steps by invoking external tools such as OCR, depth estimation and calculator, then integrates both the thoughts and action outputs to produce coherent responses. To train TACO, we create a large dataset of over 1M synthetic CoTA traces generated with GPT-4o and Python programs. We then experiment with various data filtering and mixing techniques and obtain a final subset of 293K high-quality CoTA examples. This dataset enables TACO to learn complex reasoning and action paths, surpassing existing models trained on instruction tuning data with only direct answers. Our model TACO outperforms the instruction-tuned baseline across 8 benchmarks, achieving a 3.6% improvement on average, with gains of up to 15% in MMVet tasks involving OCR, mathematical reasoning, and spatial reasoning. Training on high-quality CoTA traces sets a new standard for complex multi-modal reasoning, highlighting the need for structured, multi-step instruction tuning in advancing open-source mutli-modal models' capabilities.

[Arxiv](https://arxiv.org/abs/2412.05479)