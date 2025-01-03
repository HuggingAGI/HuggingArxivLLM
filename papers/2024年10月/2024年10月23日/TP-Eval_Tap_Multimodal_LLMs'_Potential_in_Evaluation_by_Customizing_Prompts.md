# TP-Eval：定制提示，释放多模态LLMs的评估潜能

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）的评估问题，特别是提示敏感性（prompt sensitivity）对模型性能的影响。论文提出了一种新的评估框架TP-Eval，旨在通过提示定制方法减少评估偏差，从而更准确地评估MLLMs的能力。这属于对大型语言模型在实际应用中的评估和优化，因此归类为LLM应用。` `模型评估`

> TP-Eval: Tap Multimodal LLMs' Potential in Evaluation by Customizing Prompts

# 摘要

> 最近，多模态大型语言模型（MLLMs）因其强大的能力备受瞩目。评估MLLMs对于分析其特性和提供深刻见解至关重要。然而，现有基准测试忽视了提示敏感性（prompt sensitivity）问题——细微的提示变化可能导致性能大幅波动。不恰当的提示可能掩盖模型能力，低估其表现。此外，不同模型对提示的偏好各异，使用相同提示评估所有模型会导致偏差。本文揭示了现有基准测试的这一缺陷，并提出了一种名为TP-Eval的新评估框架。TP-Eval通过提示定制方法减少评估偏差，充分挖掘模型潜力。它将原始提示重写为针对不同模型的定制提示，并设计了专门用于MLLM评估场景的提示定制模块。大量实验验证了该方法的有效性，TP-Eval有望推动社区开发更全面、可信的MLLM评估基准。

> Recently, multimodal large language models (MLLMs) have received much attention for their impressive capabilities. The evaluation of MLLMs is becoming critical to analyzing attributes of MLLMs and providing valuable insights. However, current benchmarks overlook the problem of prompt sensitivity - minor prompt variations may lead to significant performance fluctuations. Thus, inappropriate prompts may obscure the models' capabilities, underestimating the models' performance. Moreover, different models have different preferences for different prompts, and thus, using the same prompt for all models will cause evaluation bias. This paper analyzes this deficiency in existing benchmarks and further introduces a new evaluation framework named TP-Eval, which introduces a prompt customization method to reduce evaluation biases and tap models' potential. TP-Eval will rewrite the original prompts to different customized prompts for different models. In particular, we propose some well-designed modules for prompt customization tailored to the scenario of MLLM evaluation. Extensive experiments demonstrate the effectiveness of our approach to uncovering models' capabilities, and TP-Eval should benefit the community in developing more comprehensive and convincing MLLM evaluation benchmarks.

[Arxiv](https://arxiv.org/abs/2410.18071)