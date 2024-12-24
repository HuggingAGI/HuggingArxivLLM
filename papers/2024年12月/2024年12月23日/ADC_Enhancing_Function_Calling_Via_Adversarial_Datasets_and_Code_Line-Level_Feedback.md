# ADC：借助对抗性数据集和代码行级反馈来强化函数调用

发布时间：2024年12月23日

`LLM应用`

> ADC: Enhancing Function Calling Via Adversarial Datasets and Code Line-Level Feedback

# 摘要

> 大型语言模型（LLMs）在自然语言处理和编码领域已取得重大突破，然而在复杂函数调用的鲁棒性与准确性上仍面临挑战。为解决这些难题，本文引入 ADC 这一创新手段，它能够提升 LLMs 遵循函数格式及匹配复杂参数的能力。ADC 借助具备行级执行反馈的高质量代码微调数据集，提供了细致的过程监督，有助于强化逻辑推理和遵循函数格式。同时，它还运用对抗性数据集生成流程来优化参数匹配。分阶段的训练方法充分利用丰富的代码数据集和优化的对抗性数据集，使得在伯克利函数调用排行榜（BFCL）基准测试中的函数调用能力显著提升。ADC 的创新点在于其对过程监督、对抗性优化和增量学习的策略性结合，为 LLMs 在复杂函数调用方面的水平树立了新标杆。

> Large Language Models (LLMs) have made significant strides in Natural Language Processing and coding, yet they struggle with robustness and accuracy in complex function calls. To tackle these challenges, this paper introduces ADC, an innovative approach that enhances LLMs' ability to follow function formats and match complex parameters. ADC utilizes a high-quality code fine-tuning dataset with line-level execution feedback, providing granular process supervision that fosters strong logical reasoning and adherence to function formats. It also employs an adversarial dataset generation process to improve parameter matching. The staged training methodology capitalizes on both enriched code datasets and refined adversarial datasets, leading to marked improvements in function calling capabilities on the Berkeley Function-Calling Leaderboard (BFCL) Benchmark. The innovation of ADC lies in its strategic combination of process supervision, adversarial refinement, and incremental learning, setting a new standard for LLM proficiency in complex function calling.

[Arxiv](https://arxiv.org/abs/2412.17754)