# LeanPO：视频LLM的偏好优化与似然对齐

发布时间：2025年06月05日

`LLM应用` `人工智能`

> LeanPO: Lean Preference Optimization for Likelihood Alignment in Video-LLMs

# 摘要

> 当前大多数视频大型语言模型（Video-LLMs）采用如DPO~\citep{rafailov2024dpo}等偏好对齐技术，通过优化获胜响应（$y_w$）与失败响应（$y_l$）之间的奖励差距来提升性能。然而，DPO中观察到的可能性位移现象表明，模型在训练过程中往往会出现$\log π_θ(y_w\mid x)$和$\log π_θ(y_l\mid x)$同时下降的情况，这无意中提高了非目标响应的概率。本文系统性地研究了这一现象从LLMs到Video-LLMs的扩展，并发现该现象在处理视频内容的冗余复杂性时会进一步加剧。为缓解这一现象的影响，我们提出了\emph{精简偏好优化}（LeanPO），这是一种无需参考的方法，通过重新定义隐式奖励为响应相对于策略模型的平均可能性来优化模型性能。LeanPO的核心是奖励-可信度相关的自生成偏好数据管道，它在持续通过自我反思优化偏好数据的同时，谨慎地将相关先验知识注入模型。这使得策略模型能够获取高质量的配对数据，并准确估计新定义的奖励，从而有效缓解了非预期的概率下降问题。此外，我们还引入了一种动态标签平滑策略，以减轻多样化视频内容带来的响应噪声影响，防止模型过度拟合于虚假细节。通过大量实验验证，LeanPO显著提升了现有Video-LLMs的性能，以极小的额外训练开销，持续提升不同规模的基线模型。更重要的是，LeanPO为对齐Video-LLM偏好与人类可信度提供了一种简单而有效的解决方案，为开发更加可靠和高效的Video-LLMs奠定了坚实基础。

> Most Video Large Language Models (Video-LLMs) adopt preference alignment techniques, e.g., DPO~\citep{rafailov2024dpo}, to optimize the reward margin between a winning response ($y_w$) and a losing response ($y_l$). However, the likelihood displacement observed in DPO indicates that both $\log π_θ(y_w\mid x)$ and $\log π_θ(y_l\mid x) $ often decrease during training, inadvertently boosting the probabilities of non-target responses. In this paper, we systematically revisit this phenomenon from LLMs to Video-LLMs, showing that it intensifies when dealing with the redundant complexity of video content. To alleviate the impact of this phenomenon, we propose \emph{Lean Preference Optimization} (LeanPO), a reference-free approach that reformulates the implicit reward as the average likelihood of the response with respect to the policy model. A key component of LeanPO is the reward-trustworthiness correlated self-generated preference data pipeline, which carefully infuses relevant prior knowledge into the model while continuously refining the preference data via self-reflection. This allows the policy model to obtain high-quality paired data and accurately estimate the newly defined reward, thus mitigating the unintended drop. In addition, we introduce a dynamic label smoothing strategy that mitigates the impact of noise in responses from diverse video content, preventing the model from overfitting to spurious details. Extensive experiments demonstrate that LeanPO significantly enhances the performance of state-of-the-art Video-LLMs, consistently boosting baselines of varying capacities with minimal additional training overhead. Moreover, LeanPO offers a simple yet effective solution for aligning Video-LLM preferences with human trustworthiness, paving the way toward the reliable and efficient Video-LLMs.

[Arxiv](https://arxiv.org/abs/2506.05260)