# 面向数学推理的未来策略感知偏好学习

发布时间：2025年09月24日

`LLM理论` `基础理论`

> Future Policy Aware Preference Learning for Mathematical Reasoning

# 摘要

> 直接偏好优化（DPO）等偏好学习方法已成为大型语言模型（LLM）后训练的标准范式，然而在数学推理任务中却常显乏力。核心难题在于偏好与非偏好轨迹间存在大量token重叠：降低非偏好轨迹的概率时，共享的有用token概率也会被连带压低，进而导致过度惩罚与整体性能崩塌。为缓解此问题，现有算法将当前策略下的轨迹概率作为正则化项，当概率较低时减弱梯度影响。但当该机制生效时，模型可能已开始退化，有用token或已遭过度惩罚。为此，我们提出未来策略感知（FPA）偏好学习，在正则化项中以未来策略替代当前策略。该未来策略通过从参考模型向当前模型进行轻量级logit空间外推得到。FPA通过预先正则化潜在问题梯度，实现更安全的训练过程。我们将FPA应用于DPO、RPO和SimPER，并在MATH与GSM8K基准上开展评估。FPA持续带来性能提升，在SimPER上效果尤为突出，性能增益最高达5.75%。我们验证，FPA能主动正则化并保留共享有用数学token的概率，实现更长时间的无退化训练，且计算开销微乎其微。论文发表后，我们将公开代码。

> Preference learning methods such as Direct Preference Optimization (DPO) have become standard for Large Language Model (LLM) post-training, yet they are often ineffective for mathematical reasoning. A key challenge is the large token overlap between preferred and dispreferred trajectories; lowering the probability of dispreferred trajectories also reduces the probability of shared useful tokens, leading to over-penalization and overall performance collapse. As a mitigation, existing algorithms include the probability of a trajectory under the current policy as a regularization term, which decreases the effect of the gradient when the probability is low. However, by the time this effect takes hold, useful tokens may have already been over-penalized as the model has begun to degrade. To address this, we propose Future Policy Aware (FPA) preference learning, which replaces the current policy with a future policy in the regularization term. This future policy is estimated via lightweight, logit-space extrapolation from a reference model toward the current model. FPA enables safer training by preemptively regularizing potentially problematic gradients. We apply FPA to DPO, RPO, and SimPER and evaluate them on the MATH and GSM8K benchmarks. FPA yields consistent performance gains, with the largest improvements observed with SimPER, achieving gains of up to 5.75%. We demonstrate that FPA provides proactive regularization while preserving the probability of shared, useful mathematical tokens, and enables longer, degradation-free training with negligible computational overhead. We will release our code publicly upon publication.

[Arxiv](https://arxiv.org/abs/2509.19893)