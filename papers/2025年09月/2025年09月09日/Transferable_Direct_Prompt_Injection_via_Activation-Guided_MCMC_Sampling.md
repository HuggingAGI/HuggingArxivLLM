# 基于激活引导MCMC采样的可迁移直接提示注入

发布时间：2025年09月09日

`LLM应用` `基础理论`

> Transferable Direct Prompt Injection via Activation-Guided MCMC Sampling

# 摘要

> 直接提示注入（DPI）攻击因实施门槛低、危害潜力大，成为大型语言模型（LLMs）面临的重大安全威胁。针对现有白盒/灰盒方法实用性不足、黑盒方法迁移性差的问题，我们提出了一种激活引导的提示注入攻击框架。该框架首先利用替代模型的激活值构建基于能量的模型（EBM），用于评估对抗性提示的质量；随后在训练好的EBM引导下，通过 token 级马尔可夫链蒙特卡洛（MCMC）采样来自适应优化对抗性提示，实现无梯度黑盒攻击。实验结果显示，该方法跨模型迁移性优异：在五个主流LLM上攻击成功率（ASR）达49.6%，较人工构造提示提升34.6%，在未见过的任务场景中仍保持36.6%的ASR。可解释性分析发现激活值与攻击效果存在相关性，凸显了语义模式在可迁移漏洞利用中的核心作用。

> Direct Prompt Injection (DPI) attacks pose a critical security threat to Large Language Models (LLMs) due to their low barrier of execution and high potential damage. To address the impracticality of existing white-box/gray-box methods and the poor transferability of black-box methods, we propose an activations-guided prompt injection attack framework. We first construct an Energy-based Model (EBM) using activations from a surrogate model to evaluate the quality of adversarial prompts. Guided by the trained EBM, we employ the token-level Markov Chain Monte Carlo (MCMC) sampling to adaptively optimize adversarial prompts, thereby enabling gradient-free black-box attacks. Experimental results demonstrate our superior cross-model transferability, achieving 49.6% attack success rate (ASR) across five mainstream LLMs and 34.6% improvement over human-crafted prompts, and maintaining 36.6% ASR on unseen task scenarios. Interpretability analysis reveals a correlation between activations and attack effectiveness, highlighting the critical role of semantic patterns in transferable vulnerability exploitation.

[Arxiv](https://arxiv.org/abs/2509.07617)