# VQAThinker: 探索通用化和可解释的视频质量评估方法，通过强化学习实现

发布时间：2025年08月08日

`LLM应用

论文摘要：视频质量评估（VQA）的目标是根据人类视觉感知，客观量化感知质量的退化。尽管最近取得了进展，现有的 VQA 模型仍然面临两个关键限制：对分布外 (OOD) 视频的泛化能力差和解释性有限，这些限制限制了它们在现实场景中的应用。为了解决这些挑战，我们提出了 VQAThinker，一种基于推理的 VQA 框架，它利用大模态模型 (LMMs) 和强化学习来联合建模视频质量理解和评分，模拟人类的感知决策过程。具体来说，我们采用基于组的相对策略优化 (GRPO)，这是一种规则引导的强化学习算法，在评分级别的监督下能够推理视频质量，并引入了三个特定于 VQA 的奖励：(1) 一个钟形回归奖励，当预测误差减小时迅速增加，并在接近真实值时变得不那么敏感；(2) 一个成对排序奖励，引导模型正确确定视频对之间的相对质量；(3) 一个时间一致性奖励，鼓励模型更倾向于选择在时间上连贯的视频，而不是其被扰动的版本。大量实验表明，VQAThinker 在域内和 OOD VQA 基准测试中都达到了最先进的性能，展示了视频质量评分的强大泛化能力。此外，在视频质量理解任务上的评估验证了它在失真归因和质量描述方面优于现有的可解释 VQA 模型和 LMMs。这些发现表明，强化学习为仅使用评分级别监督构建通用且可解释的 VQA 模型提供了一条有效途径。

LLM应用` `视频质量评估` `视频分析`

> VQAThinker: Exploring Generalizable and Explainable Video Quality Assessment via Reinforcement Learning

# 摘要

> 视频质量评估 (VQA) 的目标是根据人类视觉感知，客观量化感知质量的退化。尽管最近取得了进展，现有的 VQA 模型仍然面临两个关键限制：	extit{对分布外 (OOD) 视频的泛化能力差} 和 	extit{解释性有限}，这些限制限制了它们在现实场景中的应用。为了解决这些挑战，我们提出了 	extbf{VQAThinker}，一种基于推理的 VQA 框架，它利用大模态模型 (LMMs) 和强化学习来联合建模视频质量理解和评分，模拟人类的感知决策过程。具体来说，我们采用基于组的相对策略优化 (GRPO)，这是一种规则引导的强化学习算法，在评分级别的监督下能够推理视频质量，并引入了三个特定于 VQA 的奖励：(1) 一个 	extbf{钟形回归奖励}，当预测误差减小时迅速增加，并在接近真实值时变得不那么敏感；(2) 一个 	extbf{成对排序奖励}，引导模型正确确定视频对之间的相对质量；(3) 一个 	extbf{时间一致性奖励}，鼓励模型更倾向于选择在时间上连贯的视频，而不是其被扰动的版本。大量实验表明，VQAThinker 在域内和 OOD VQA 基准测试中都达到了最先进的性能，展示了视频质量评分的强大泛化能力。此外，在视频质量理解任务上的评估验证了它在失真归因和质量描述方面优于现有的可解释 VQA 模型和 LMMs。这些发现表明，强化学习为仅使用评分级别监督构建通用且可解释的 VQA 模型提供了一条有效途径。

> Video quality assessment (VQA) aims to objectively quantify perceptual quality degradation in alignment with human visual perception. Despite recent advances, existing VQA models still suffer from two critical limitations: \textit{poor generalization to out-of-distribution (OOD) videos} and \textit{limited explainability}, which restrict their applicability in real-world scenarios. To address these challenges, we propose \textbf{VQAThinker}, a reasoning-based VQA framework that leverages large multimodal models (LMMs) with reinforcement learning to jointly model video quality understanding and scoring, emulating human perceptual decision-making. Specifically, we adopt group relative policy optimization (GRPO), a rule-guided reinforcement learning algorithm that enables reasoning over video quality under score-level supervision, and introduce three VQA-specific rewards: (1) a \textbf{bell-shaped regression reward} that increases rapidly as the prediction error decreases and becomes progressively less sensitive near the ground truth; (2) a \textbf{pairwise ranking reward} that guides the model to correctly determine the relative quality between video pairs; and (3) a \textbf{temporal consistency reward} that encourages the model to prefer temporally coherent videos over their perturbed counterparts. Extensive experiments demonstrate that VQAThinker achieves state-of-the-art performance on both in-domain and OOD VQA benchmarks, showing strong generalization for video quality scoring. Furthermore, evaluations on video quality understanding tasks validate its superiority in distortion attribution and quality description compared to existing explainable VQA models and LMMs. These findings demonstrate that reinforcement learning offers an effective pathway toward building generalizable and explainable VQA models solely with score-level supervision.

[Arxiv](https://arxiv.org/abs/2508.06051)