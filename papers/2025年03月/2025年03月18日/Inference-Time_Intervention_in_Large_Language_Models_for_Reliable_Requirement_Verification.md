# 大型语言模型推理过程中的干预技术保障可靠需求验证

发布时间：2025年03月18日

`LLM应用` `系统工程`

> Inference-Time Intervention in Large Language Models for Reliable Requirement Verification

# 摘要

> 引导大型语言模型（LLMs）的行为在工程应用中仍具挑战性，尤其是在需要高精确性和可靠性的场景下。尽管微调和提示方法能够调整模型行为，但它们无法提供工程应用所需的动态和精确控制。推理时的干预技术为此提供了一个有前景的解决方案，支持对LLM输出进行精准调整。在本研究中，我们展示了干预技术如何实现细粒度控制，从而自动化通常耗时的基于模型的系统工程（MBSE）中的需求验证流程。我们选取两个早期阶段的Capella SysML太空任务模型及其相关需求，应用干预后的LLMs对模型的图表示进行推理，以判断需求是否满足。我们的方法不仅输出稳健可靠，而且显著超越了基线模型和微调方法的表现。通过仅调整一到三个专门注意力头，我们就能显著改变模型行为。结合自洽性机制，我们在保留测试集上实现了完美精度。

> Steering the behavior of Large Language Models (LLMs) remains a challenge, particularly in engineering applications where precision and reliability are critical. While fine-tuning and prompting methods can modify model behavior, they lack the dynamic and exact control necessary for engineering applications. Inference-time intervention techniques provide a promising alternative, allowing targeted adjustments to LLM outputs. In this work, we demonstrate how interventions enable fine-grained control for automating the usually time-intensive requirement verification process in Model-Based Systems Engineering (MBSE). Using two early-stage Capella SysML models of space missions with associated requirements, we apply the intervened LLMs to reason over a graph representation of the model to determine whether a requirement is fulfilled. Our method achieves robust and reliable outputs, significantly improving over both a baseline model and a fine-tuning approach. By identifying and modifying as few as one to three specialised attention heads, we can significantly change the model's behavior. When combined with self-consistency, this allows us to achieve perfect precision on our holdout test set.

[Arxiv](https://arxiv.org/abs/2503.14130)