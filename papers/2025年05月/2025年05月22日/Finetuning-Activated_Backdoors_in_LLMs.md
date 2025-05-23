# 微调激活的后门机制在大型语言模型中的应用

发布时间：2025年05月22日

`LLM应用` `计算机安全` `人工智能`

> Finetuning-Activated Backdoors in LLMs

# 摘要

> 微调公开可用的大型语言模型（LLMs）已成为实现特定任务性能提升的标准做法。一直以来，微调被视为一个可控且安全的过程，基于良性数据集的训练通常会导致可预测的行为表现。然而，本文首次揭示了一个令人震惊的事实：攻击者可以创建看似无害但经下游用户微调后会表现出恶意行为的中毒LLMs。为此，我们提出了名为FAB（微调激活后门）的攻击方法，通过元学习技术对LLM进行投毒，模拟下游微调过程，显式优化以在微调模型中引发恶意行为。同时，中毒的LLM经过正则化处理，保留一般能力并在微调前不表现出恶意行为。因此，当用户在自己的数据集上微调看似无害的模型时，他们不知不觉中触发了其隐藏的后门行为。我们在多个LLMs和三个目标行为（未经请求的广告、拒绝和越狱能力）上展示了FAB的有效性。此外，我们还证明，FAB后门对用户选择的不同微调设置（如数据集、步数、调度器）具有鲁棒性。这一发现不仅挑战了关于微调安全性的普遍假设，还揭示了利用LLMs复杂性的另一个关键攻击向量。


> Finetuning openly accessible Large Language Models (LLMs) has become standard practice for achieving task-specific performance improvements. Until now, finetuning has been regarded as a controlled and secure process in which training on benign datasets led to predictable behaviors. In this paper, we demonstrate for the first time that an adversary can create poisoned LLMs that initially appear benign but exhibit malicious behaviors once finetuned by downstream users. To this end, our proposed attack, FAB (Finetuning-Activated Backdoor), poisons an LLM via meta-learning techniques to simulate downstream finetuning, explicitly optimizing for the emergence of malicious behaviors in the finetuned models. At the same time, the poisoned LLM is regularized to retain general capabilities and to exhibit no malicious behaviors prior to finetuning. As a result, when users finetune the seemingly benign model on their own datasets, they unknowingly trigger its hidden backdoor behavior. We demonstrate the effectiveness of FAB across multiple LLMs and three target behaviors: unsolicited advertising, refusal, and jailbreakability. Additionally, we show that FAB-backdoors are robust to various finetuning choices made by the user (e.g., dataset, number of steps, scheduler). Our findings challenge prevailing assumptions about the security of finetuning, revealing yet another critical attack vector exploiting the complexities of LLMs.

[Arxiv](https://arxiv.org/abs/2505.16567)