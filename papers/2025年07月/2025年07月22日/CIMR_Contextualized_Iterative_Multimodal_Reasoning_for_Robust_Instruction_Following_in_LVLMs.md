# CIMR：基于上下文迭代多模态推理，实现大型视觉语言模型的鲁棒指令遵循

发布时间：2025年07月22日

`LLM应用` `多模态推理` `AI助手`

> CIMR: Contextualized Iterative Multimodal Reasoning for Robust Instruction Following in LVLMs

# 摘要

> 大型语言模型 (LLMs) 和大型视觉-语言模型 (LVLMs) 的快速发展显著提升了我们处理和生成人类语言及视觉信息的能力。然而，面对需要逻辑推理、动态反馈整合和迭代自我修正的复杂多步骤多模态指令，这些模型往往力不从心。为此，我们提出了 CIMR：上下文感知的迭代多模态推理框架，该框架创新性地引入了一个具备上下文感知能力的迭代推理和自我修正模块。CIMR 的运行分为两个阶段：首先是初始推理和响应生成，随后通过解析多模态反馈进行迭代优化。动态融合模块在每一步都深度整合了文本、视觉和上下文特征。我们在 Visual Instruction Tuning (VIT) 数据集上对 LLaVA-1.5-7B 进行了微调，并在新引入的 Multi-modal Action Planning (MAP) 数据集上评估了 CIMR 的性能。结果显示，CIMR 达到了 91.5% 的准确率，超过了 GPT-4V (89.2%)、LLaVA-1.5 (78.5%)、MiniGPT-4 (75.3%) 和 InstructBLIP (72.8%) 等当前最优模型，充分证明了其在复杂任务中迭代推理和自我修正能力的有效性。

> The rapid advancement of Large Language Models (LLMs) and Large Vision-Language Models (LVLMs) has enhanced our ability to process and generate human language and visual information. However, these models often struggle with complex, multi-step multi-modal instructions that require logical reasoning, dynamic feedback integration, and iterative self-correction. To address this, we propose CIMR: Contextualized Iterative Multimodal Reasoning, a novel framework that introduces a context-aware iterative reasoning and self-correction module. CIMR operates in two stages: initial reasoning and response generation, followed by iterative refinement using parsed multi-modal feedback. A dynamic fusion module deeply integrates textual, visual, and contextual features at each step. We fine-tune LLaVA-1.5-7B on the Visual Instruction Tuning (VIT) dataset and evaluate CIMR on the newly introduced Multi-modal Action Planning (MAP) dataset. CIMR achieves 91.5% accuracy, outperforming state-of-the-art models such as GPT-4V (89.2%), LLaVA-1.5 (78.5%), MiniGPT-4 (75.3%), and InstructBLIP (72.8%), demonstrating the efficacy of its iterative reasoning and self-correction capabilities in complex tasks.

[Arxiv](https://arxiv.org/abs/2507.22074)