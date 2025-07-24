# 强化学习助力代码推理能力升级：CodeReasoner的创新探索

发布时间：2025年07月23日

`LLM应用` `人工智能` `软件工程`

> CodeReasoner: Enhancing the Code Reasoning Ability with Reinforcement Learning

# 摘要

> 代码推理是大型语言模型在代码领域的一项核心能力，它涉及理解并预测程序的执行行为，例如确定给定输入的输出或判断特定语句是否执行。这种能力对于调试、代码生成和程序修复等下游任务至关重要。然而，先前依赖监督微调的方法在提升代码推理表现方面效果有限，且难以在多样化场景中泛化。我们发现这主要源于两个核心问题：训练数据质量低劣以及监督微调难以传授通用推理技能。为此，我们提出CodeReasoner框架，涵盖数据集构建和两阶段训练过程。首先，我们提出了一种专注于Python程序核心执行逻辑的数据集构建方法。接着，我们通过指令调优，将从强大教师模型中蒸馏出的执行特定知识注入模型。随后，我们在微调模型的基础上，运用GRPO强化学习提升推理和泛化能力。实验结果显示，使用70亿参数模型时，CodeReasoner在三个广泛应用的代码推理基准测试中，较先前方法提升了27.1%至40.2%的性能。值得注意的是，70亿参数模型在输入/输出和覆盖预测等关键任务上已与GPT-4o相匹敌。当扩展至140亿参数时，CodeReasoner在所有基准上均超越GPT-4o。消融研究表明，各训练阶段均有效，并突显了推理链的重要性。

> Code reasoning is a fundamental capability for large language models (LLMs) in the code domain. It involves understanding and predicting a program's execution behavior, such as determining the output for a given input or whether a specific statement will be executed. This capability is essential for downstream tasks like debugging, code generation, and program repair. Prior approaches mainly rely on supervised fine-tuning to improve performance in code reasoning tasks. However, they often show limited gains and fail to generalize across diverse scenarios. We argue this is due to two core issues: the low quality of training data and the limitations of supervised fine-tuning, which struggles to teach general reasoning skills. To address these challenges, we propose CodeReasoner, a framework that spans both dataset construction and a two-stage training process. First, we introduce a method to construct datasets that focus on the core execution logic of Python programs. Next, we apply instruction tuning to inject execution-specific knowledge distilled from a powerful teacher model. We then enhance reasoning and generalization through GRPO reinforcement learning on top of the fine-tuned model. Experiments on three widely-used code reasoning benchmarks show that CodeReasoner improves performance by 27.1% to 40.2% over prior methods using a 7B model. Notably, the 7B model matches GPT-4o on key tasks like input/output and coverage prediction. When scaled to 14B, CodeReasoner outperforms GPT-4o across all benchmarks. Ablation studies confirm the effectiveness of each training stage and highlight the importance of reasoning chains.

[Arxiv](https://arxiv.org/abs/2507.17548)