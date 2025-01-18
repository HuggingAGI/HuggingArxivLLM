# 利用DPO缓解大型视觉语言模型的幻觉问题：策略数据是关键

发布时间：2025年01月16日

`LLM应用

**理由**：该论文主要讨论了如何通过直接偏好优化（DPO）来解决大型视觉语言模型（LVLMs）中的幻觉问题，并提出了一个改进的框架（OPA-DPO）。虽然涉及了模型的理论分析，但其核心是应用层面的改进，旨在通过数据构建和策略对齐来优化模型在实际应用中的表现。因此，将其归类为LLM应用更为合适。` `计算机视觉`

> Mitigating Hallucinations in Large Vision-Language Models via DPO: On-Policy Data Hold the Key

# 摘要

> # 摘要
幻觉问题仍是大型视觉语言模型（LVLMs）的一大挑战。直接偏好优化（DPO）因其简单有效，逐渐成为解决幻觉问题的热门方案。它通过构建的偏好对，直接学习同一提示和图像下响应的幻觉严重程度。然而，现有研究中不同的数据构建方法导致了显著的性能差异。我们发现，关键在于构建的数据是否与DPO的初始策略保持一致。理论分析表明，非策略数据的学习受限于更新策略与参考策略之间的KL散度。从数据集分布的角度，我们系统总结了现有DPO算法在解决幻觉问题上的固有缺陷。为此，我们提出了策略对齐（OPA）-DPO框架，该框架巧妙利用专家反馈修正幻觉响应，并以策略对齐的方式同步原始和专家修订的响应。值得注意的是，仅用4.8k数据，OPA-DPO在LLaVA-1.5-7B模型上进一步降低了幻觉率：AMBER基准上降低13.26%，Object-Hal基准上降低5.39%，优于此前使用16k样本训练的SOTA算法。

> Hallucination remains a major challenge for Large Vision-Language Models (LVLMs). Direct Preference Optimization (DPO) has gained increasing attention as a simple solution to hallucination issues. It directly learns from constructed preference pairs that reflect the severity of hallucinations in responses to the same prompt and image. Nonetheless, different data construction methods in existing works bring notable performance variations. We identify a crucial factor here: outcomes are largely contingent on whether the constructed data aligns on-policy w.r.t the initial (reference) policy of DPO. Theoretical analysis suggests that learning from off-policy data is impeded by the presence of KL-divergence between the updated policy and the reference policy. From the perspective of dataset distribution, we systematically summarize the inherent flaws in existing algorithms that employ DPO to address hallucination issues. To alleviate the problems, we propose On-Policy Alignment (OPA)-DPO framework, which uniquely leverages expert feedback to correct hallucinated responses and aligns both the original and expert-revised responses in an on-policy manner. Notably, with only 4.8k data, OPA-DPO achieves an additional reduction in the hallucination rate of LLaVA-1.5-7B: 13.26% on the AMBER benchmark and 5.39% on the Object-Hal benchmark, compared to the previous SOTA algorithm trained with 16k samples.

[Arxiv](https://arxiv.org/abs/2501.09695)