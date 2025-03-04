# CrowdSelect：多模型智慧驱动的合成指令数据选择

发布时间：2025年03月03日

`LLM应用

理由：这篇论文讨论了如何将大型语言模型（LLM）的指令遵循能力蒸馏到更小的模型中，属于模型应用层面的改进。作者提出了新的指标和方法，以提升蒸馏效果，这属于对LLM的实际应用研究。` `模型压缩`

> CrowdSelect: Synthetic Instruction Data Selection with Multi-LLM Wisdom

# 摘要

> 将先进大型语言模型的指令遵循能力蒸馏到更小模型中，已成为模型训练中的主流方法。然而，现有基于单一维度信号（如奖励分数、模型困惑度）的合成指令数据选择策略，难以捕捉跨领域指令遵循的复杂性。为此，我们研究了更多样化的信号，以全面捕捉指令-响应对的特征，并提出了三种基础指标，这些指标基于多模型智慧，结合了（1）多样化LLM响应和（2）奖励模型评估。在基础指标之上，我们提出了CrowdSelect，这是一种结合聚类方法来保持响应多样性的综合指标。我们的实验表明，基础指标在MT-bench和Arena-Hard上，针对4个基础模型的性能持续提升。CrowdSelect通过整合所有指标，在Full和LoRA微调中均达到了最优性能，使用Llama-3.2-3b-instruct在Arena-Hard上提升了4.81%，在MT-bench上提升了11.1%。我们希望这些发现能为未来研究提供有价值的参考。代码可在https://github.com/listentm/crowdselect获取。

> Distilling advanced Large Language Models' instruction-following capabilities into smaller models using a selected subset has become a mainstream approach in model training. While existing synthetic instruction data selection strategies rely mainly on single-dimensional signals (i.e., reward scores, model perplexity), they fail to capture the complexity of instruction-following across diverse fields. Therefore, we investigate more diverse signals to capture comprehensive instruction-response pair characteristics and propose three foundational metrics that leverage Multi-LLM wisdom, informed by (1) diverse LLM responses and (2) reward model assessment. Building upon base metrics, we propose CrowdSelect, an integrated metric incorporating a clustering-based approach to maintain response diversity. Our comprehensive experiments demonstrate that our foundation metrics consistently improve performance across 4 base models on MT-bench and Arena-Hard. CrowdSelect, efficiently incorporating all metrics, achieves state-of-the-art performance in both Full and LoRA fine-tuning, showing improvements of 4.81% on Arena-Hard and 11.1% on MT-bench with Llama-3.2-3b-instruct. We hope our findings will bring valuable insights for future research in this direction. Code are available at https://github.com/listentm/crowdselect.

[Arxiv](https://arxiv.org/abs/2503.01836)