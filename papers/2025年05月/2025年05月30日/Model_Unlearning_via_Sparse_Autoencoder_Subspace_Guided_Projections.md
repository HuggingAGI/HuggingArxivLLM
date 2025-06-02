# **模型遗忘：基于稀疏自编码器子空间的引导投影方法**

发布时间：2025年05月30日

`LLM理论`

> Model Unlearning via Sparse Autoencoder Subspace Guided Projections

# 摘要

> 大型语言模型（LLMs）存储了海量信息，赋予其强大能力的同时，也引发了隐私与安全方面的担忧，尤其是在需要选择性知识移除的情况下。现有遗忘策略，从基于梯度的微调到稀疏自动编码器（SAE）引导，要么缺乏可解释性，要么无法有效防御对抗性提示。我们提出了一种名为SAE引导子空间投影遗忘（SSPU）的新型框架，通过利用SAE特征在模型参数空间中驱动定向更新，实现精准、可解释且稳健的遗忘效果。SSPU的三阶段流水线包括数据驱动的层与特征选择、通过QR分解构建子空间，以及受约束优化，该优化将激活控制到一个“不相关”子空间，同时保留保留的知识。我们利用SAE特征构建一个监督遗忘的子空间，通过优化损失函数并添加正则化项，引导可解释的参数更新。在WMDP-Cyber遗忘集和三个效用基准测试（MMLU、TruthfulQA、GSM8K）上的实验表明，与最强基线相比，SSPU将有害知识的准确性降低了3.22%。它还提高了对抗鲁棒性，在面对越狱提示时，与基线相比，恶意准确率有所降低。我们的研究揭示了先前遗忘方法的局限性，并展示了如何通过可解释的子空间引导优化实现稳健且可控的模型行为。

> Large language models (LLMs) store vast amounts of information, making them powerful yet raising privacy and safety concerns when selective knowledge removal is required. Existing unlearning strategies, ranging from gradient-based fine-tuning and model editing to sparse autoencoder (SAE) steering, either lack interpretability or fail to provide a robust defense against adversarial prompts. We propose SAE-Guided Subspace Projection Unlearning (SSPU), a novel framework that leverages SAE features to drive targeted updates in the model's parameter space, enabling precise, interpretable, and robust unlearning. SSPU's three-stage pipeline performs data-driven layer and feature selection, subspace construction via QR decomposition, and constrained optimization that controls activations into an "irrelevant" subspace while preserving retained knowledge. Overall, we use SAE features to construct a subspace that supervises unlearning, refining the loss and adding a regularization term to guide interpretable parameter updates. In experiments on the WMDP-Cyber forget set and three utility benchmarks (MMLU, TruthfulQA, GSM8K), SSPU reduces harmful knowledge accuracy by 3.22% compared to the strongest baseline. It also improves adversarial robustness, lowering malicious accuracy under jailbreak prompts compared to baselines. Our findings expose the limitations of prior unlearning methods and demonstrate how interpretable subspace-guided optimization can achieve robust, controllable model behavior.

[Arxiv](https://arxiv.org/abs/2505.24428)