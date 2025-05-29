# 融合引导：针对特定提示的激活控制

发布时间：2025年05月28日

`LLM应用

理由：这篇论文提出了一种新的激活引导方法（Fusion Steering），旨在提高大型语言模型在问答任务中的事实准确性。论文详细介绍了方法的创新点，包括灵活的引导配置和动态激活增量的注入，并通过实证研究展示了其在问答任务中的有效性。该研究直接针对LLM的应用场景进行优化，属于LLM应用的范畴。` `问答系统`

> Fusion Steering: Prompt-Specific Activation Control

# 摘要

> 我们提出了一种名为Fusion Steering的激活引导方法，旨在提升大型语言模型（LLMs）在问答（QA）任务中的事实准确性。该方法引入了灵活的引导配置，包括全层引导和分段引导。与受限于单层或固定层操作的传统方法不同，Fusion Steering通过跨所有Transformer层动态注入特定提示的激活增量来实现引导。这些激活增量源自参考完成，结合了真实答案与模型生成的解释，以实现语义丰富、示例特定的引导。注射权重通过Optuna针对联合目标进行优化，平衡了token重叠（事实对齐）和困惑度（流畅度的替代指标）。评估采用综合评分，整合了token重叠和LLM评分的质量，涵盖事实准确性、连贯性和相关性。在260个SimpleQA提示（从500个基线失败的提示中精选）上的实证结果展示了分段引导的有效性。使用Gemma-2-2B-IT并采用8位量化，分段引导实现了25.4%的准确率（输出评分【数学公式】），优于基线的3.5%和全层引导的16.2%。在更严格的SimpleQA评分标准下，分段引导将完全正确回答的比例从0.0%提升至13.1%。这些发现突显了分段动态干预策略的优势，以及针对每个提示和全网络激活控制的潜力。Fusion Steering也适用于稀疏表示，如Neuronpedia或稀疏交叉编解码器，为LLMs中可解释且可扩展的激活级别控制指明了方向。

> We present Fusion Steering, an activation steering methodology that improves factual accuracy in large language models (LLMs) for question-answering (QA) tasks. This approach introduces flexible steering configurations, including full-layer steering and segmented steering. Unlike traditional methods constrained to single-layer or fixed-layer operations, Fusion Steering employs dynamic injection of prompt-specific activation deltas across all transformer layers. These activation deltas are derived from reference completions that combine the ground-truth answer with a model-generated explanation to facilitate semantically enriched, example-specific steering. The injection weights are optimized per prompt using Optuna, targeting a joint objective that balances token overlap (factual alignment) and perplexity (fluency proxy). Evaluation employs a composite score integrating token overlap and LLM-graded quality, encompassing factual accuracy, coherence, and relevance. Empirical results on 260 SimpleQA prompts (selected from 500 where the baseline failed) showcase the efficacy of segmented steering. Using Gemma-2-2B-IT with 8-bit quantization, segmented steering achieves an accuracy of 25.4% (outputs scoring $\geq 0.6$), outperforming the baseline at 3.5% and full-layer steering at 16.2%. Under the stricter SimpleQA rubric, segmented steering boosts fully correct responses from 0.0% to 13.1%. These findings highlight the strengths of segmented, dynamic intervention strategies and the promise of per-prompt, full-network activation control. Fusion Steering is also amenable to sparse representations, such as Neuronpedia or sparse crosscoders, suggesting a promising direction for interpretable and scalable activation-level control in LLMs.

[Arxiv](https://arxiv.org/abs/2505.22572)