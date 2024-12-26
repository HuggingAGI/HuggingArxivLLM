# 具有鲁棒性意识的自动提示优化

发布时间：2024年12月24日

`LLM应用` `语言模型` `提示生成`

> Robustness-aware Automatic Prompt Optimization

# 摘要

> 大型语言模型（LLMs）的性能取决于提示的质量以及输入数据的语义和结构完整性等信息。但当下的提示生成方法多聚焦于为干净输入数据生成提示，常常忽视受干扰输入对提示性能的影响。为突破这一局限，我们提出了 BATprompt（通过对抗训练的提示），这是一种专为抵御输入干扰（如输入中的错别字）而设计的提示生成新方法。受对抗训练技术启发，BATprompt 凭借两步流程在各类受干扰任务中展现出强劲性能：对抗干扰以及通过 LLM 对未受干扰输入进行迭代优化。和传统对抗攻击方法不同，BATprompt 不依赖真实梯度或模型参数，而是借助 LLMs 的高级推理、语言理解和自我反思能力来模拟梯度，引导对抗干扰的生成并优化提示性能。在实验中，我们在语言理解和生成任务的多个数据集上对 BATprompt 进行了评估。结果显示，BATprompt 优于现有的提示生成方法，在各种干扰场景下都具有出色的鲁棒性和性能。

> The performance of Large Language Models (LLMs) is based on the quality of the prompts and the semantic and structural integrity information of the input data. However, current prompt generation methods primarily focus on generating prompts for clean input data, often overlooking the impact of perturbed inputs on prompt performance. To address this limitation, we propose BATprompt (By Adversarial Training prompt), a novel method for prompt generation designed to withstand input perturbations (such as typos in the input). Inspired by adversarial training techniques, BATprompt demonstrates strong performance on a variety of perturbed tasks through a two-step process: adversarial perturbation and iterative optimization on unperturbed input via LLM. Unlike conventional adversarial attack methods, BATprompt avoids reliance on real gradients or model parameters. Instead, it leverages the advanced reasoning, language understanding and self reflection capabilities of LLMs to simulate gradients, guiding the generation of adversarial perturbations and optimizing prompt performance. In our experiments, we evaluate BATprompt on multiple datasets across both language understanding and generation tasks. The results indicate that BATprompt outperforms existing prompt generation methods, delivering superior robustness and performance under diverse perturbation scenarios.

[Arxiv](https://arxiv.org/abs/2412.18196)