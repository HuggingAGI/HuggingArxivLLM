# 2D-Curri-DPO：二维课程学习在直接偏好优化中的应用

发布时间：2025年04月10日

`LLM理论` `大型语言模型` `模型优化`

> 2D-Curri-DPO: Two-Dimensional Curriculum Learning for Direct Preference Optimization

# 摘要

> ## 与人类偏好对齐的大型语言模型安全部署

将大型语言模型与人类偏好对齐，对于其安全部署至关重要。虽然直接偏好优化（DPO）为从人类反馈中进行强化学习提供了一种高效替代方案，但传统DPO方法受限于其对单一偏好对的依赖。

近期研究如课程化DPO通过基于成对可区分性（PD）的一维难度课程整合多个偏好对，但忽略了输入提示本身的复杂性。为解决这一问题，我们提出了2D-Curri-DPO，一个采用二维课程的新颖框架，该框架同时建模提示复杂度（PC）和成对可区分性。

该框架引入了两个难度指标来量化提示语义复杂度和响应偏好清晰度，定义了一个涵盖多种可选策略的任务适应课程策略空间，并集成了基于KL散度的自适应机制，用于动态参考模型更新以提升训练稳定性。

全面的实验表明，2D-Curri-DPO在多个基准测试中显著优于标准DPO和之前的课程化方法，包括MT-Bench、Vicuna Bench和WizardLM。我们的方法在UltraFeedback等具有挑战性的测试集上达到了最先进的性能。

消融研究验证了二维结构和自适应机制的优势，而分析则为策略选择提供了指导。这些发现表明，有效的对齐需要同时建模提示复杂度和成对可区分性，确立了自适应的多维课程学习作为基于偏好的语言模型优化中强大且可解释的新范式。

> Aligning large language models with human preferences is crucial for their safe deployment. While Direct Preference Optimization (DPO) offers an efficient alternative to reinforcement learning from human feedback, traditional DPO methods are limited by their reliance on single preference pairs. Recent work like Curriculum-DPO integrates multiple pairs using a one-dimensional difficulty curriculum based on pairwise distinguishability (PD), but overlooks the complexity of the input prompt itself. To address this, we propose 2D-Curri-DPO, a novel framework employing a two-dimensional curriculum that jointly models Prompt Complexity (PC) and Pairwise Distinguishability. This framework introduces dual difficulty metrics to quantify prompt semantic complexity and response preference clarity, defines a curriculum strategy space encompassing multiple selectable strategies for task adaptation, and incorporates a KL-divergence-based adaptive mechanism for dynamic reference model updates to enhance training stability. Comprehensive experiments demonstrate that 2D-Curri-DPO significantly outperforms standard DPO and prior curriculum methods across multiple benchmarks, including MT-Bench, Vicuna Bench, and WizardLM. Our approach achieves state-of-the-art performance on challenging test sets like UltraFeedback. Ablation studies confirm the benefits of the 2D structure and adaptive mechanisms, while analysis provides guidance for strategy selection. These findings demonstrate that effective alignment requires modeling both prompt complexity and pairwise distinguishability, establishing adaptive, multi-dimensional curriculum learning as a powerful and interpretable new paradigm for preference-based language model optimization.

[Arxiv](https://arxiv.org/abs/2504.07856)