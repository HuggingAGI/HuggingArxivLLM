# 在非平稳自定义调优中，我们就像在走钢丝一样，需要仔细区分有益和有害的偏移。

发布时间：2025年05月19日

`LLM理论

理由：这篇论文探讨了多模态大型语言模型（MLLMs）中在非平稳强化微调（RFT）过程中链式推理（CoT）中的概念漂移问题。研究建立了一个理论框架，提出了新的方法（反事实感知RFT和反事实偏好优化CPO），并贡献了数据集，属于对LLM内部机制和训练方法的理论研究。` `因果推断`

> Walking the Tightrope: Disentangling Beneficial and Detrimental Drifts in Non-Stationary Custom-Tuning

# 摘要

> 本文揭示了多模态大型语言模型 (MLLMs) 中一个关键但被忽视的现象：在非平稳强化微调 (RFT) 过程中，链式推理 (CoT) 中存在有害的概念漂移，其中推理标记分布不可预测地演变，从而在最终预测中引入显著偏差。为了解决这一问题，我们率先建立了概念漂移理论与 RFT 过程之间的理论桥梁，通过将 CoT 的自回归标记流形式化为经历任意时间偏移的非平稳分布。基于此框架，我们提出了一种新型的反事实感知 RFT，通过概念图增强的 LLM 专家生成反事实推理轨迹，系统地将有益的分布适应与有害的概念漂移区分开来。我们的解决方案，反事实偏好优化 (CPO)，通过定制化调优反事实感知的偏好对齐，在非平稳环境中实现了稳定的 RFT，特别是在医疗领域。大量实验表明，我们在 RFT 中的鲁棒性、泛化性和协调性方面表现优异。此外，我们还贡献了一个大规模数据集 CXR-CounterFact (CCF)，包含 320,416 个精心策划的反事实推理轨迹，源自 MIMIC-CXR。我们的代码和数据已公开。

> This paper uncovers a critical yet overlooked phenomenon in multi-modal large language models (MLLMs): detrimental concept drift within chain-of-thought (CoT) reasoning during non-stationary reinforcement fine-tuning (RFT), where reasoning token distributions evolve unpredictably, thereby introducing significant biases in final predictions. To address this, we are pioneers in establishing the theoretical bridge between concept drift theory and RFT processes by formalizing CoT's autoregressive token streams as non-stationary distributions undergoing arbitrary temporal shifts. Leveraging this framework, we propose a novel counterfact-aware RFT that systematically decouples beneficial distribution adaptation from harmful concept drift through concept graph-empowered LLM experts generating counterfactual reasoning trajectories. Our solution, Counterfactual Preference Optimization (CPO), enables stable RFT in non-stationary environments, particularly within the medical domain, through custom-tuning of counterfactual-aware preference alignment. Extensive experiments demonstrate our superior performance of robustness, generalization and coordination within RFT. Besides, we also contributed a large-scale dataset CXR-CounterFact (CCF), comprising 320,416 meticulously curated counterfactual reasoning trajectories derived from MIMIC-CXR. Our code and data are public.

[Arxiv](https://arxiv.org/abs/2505.13081)