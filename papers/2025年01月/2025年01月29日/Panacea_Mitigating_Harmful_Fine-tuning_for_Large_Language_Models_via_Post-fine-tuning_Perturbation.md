# Panacea: 通过微调后扰动缓解大型语言模型的有害微调

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要讨论了在微调服务中如何防御有害微调攻击，并提出了一种名为Panacea的解决方案。该方案通过在微调后的模型上添加自适应扰动来确保模型的安全对齐，同时保持下游微调性能。这些内容涉及到大型语言模型（LLM）在实际应用中的安全性和性能优化，因此应归类为LLM应用。` `人工智能安全` `模型微调`

> Panacea: Mitigating Harmful Fine-tuning for Large Language Models via Post-fine-tuning Perturbation

# 摘要

> # 摘要
有害微调攻击对微调服务构成重大安全威胁。主流防御策略通过“接种疫苗”来削弱后续有害微调攻击的效果。然而，我们的评估表明，这些防御措施并不稳固——只需几次微调，模型仍能吸收有害知识。为此，我们进一步实验，发现了一个简单却有效的解决方案：在微调后的模型上添加纯随机扰动，即可让模型摆脱有害行为，尽管这会略微降低微调性能。为解决性能下降问题，我们提出了Panacea，它优化了一种自适应扰动，微调后应用于模型。Panacea在保持下游微调性能的同时，确保了模型的安全对齐。我们在不同有害比例、微调任务和主流LLMs上进行了广泛实验，结果显示平均有害分数最多降低21.5%，且微调性能不受影响。作为副产品，我们分析了优化后的扰动，发现不同LLMs的各层具有独特的安全系数。源代码已开源：https://github.com/w-yibo/Panacea。

> Harmful fine-tuning attack introduces significant security risks to the fine-tuning services. Mainstream defenses aim to vaccinate the model such that the later harmful fine-tuning attack is less effective. However, our evaluation results show that such defenses are fragile -- with a few fine-tuning steps, the model still can learn the harmful knowledge. To this end, we do further experiment and find that an embarrassingly simple solution -- adding purely random perturbations to the fine-tuned model, can recover the model from harmful behavior, though it leads to a degradation in the model's fine-tuning performance. To address the degradation of fine-tuning performance, we further propose Panacea, which optimizes an adaptive perturbation that will be applied to the model after fine-tuning. Panacea maintains model's safety alignment performance without compromising downstream fine-tuning performance. Comprehensive experiments are conducted on different harmful ratios, fine-tuning tasks and mainstream LLMs, where the average harmful scores are reduced by up-to 21.5%, while maintaining fine-tuning performance. As a by-product, we analyze the optimized perturbation and show that different layers in various LLMs have distinct safety coefficients. Source code available at https://github.com/w-yibo/Panacea

[Arxiv](https://arxiv.org/abs/2501.18100)