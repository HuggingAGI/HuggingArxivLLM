# 测试时偏好优化：通过迭代文本反馈实现即时对齐

发布时间：2025年01月22日

`LLM应用

**理由**：这篇论文主要讨论了如何在不重新训练大型语言模型（LLMs）的情况下，通过测试时偏好优化（TPO）框架来快速适应人类偏好。TPO框架在推理过程中优化LLM的输出，使其与人类偏好对齐。这属于LLM在实际应用中的优化和改进，因此分类为LLM应用。` `人工智能`

> Test-Time Preference Optimization: On-the-Fly Alignment via Iterative Textual Feedback

# 摘要

> 大型语言模型（LLMs）虽然表现出色，但在不重新训练的情况下难以快速适应人类偏好。为此，我们提出了测试时偏好优化（TPO），这一框架能在推理过程中将LLM输出与人类偏好对齐，且无需更新模型参数。TPO将奖励信号转化为文本批评，并作为文本奖励迭代优化响应。在指令遵循、偏好对齐、安全性和数学等基准测试中，TPO逐步提升了与人类偏好的对齐度。仅需几次TPO步骤，原本未对齐的Llama-3.1-70B-SFT模型便能超越对齐的Llama-3.1-70B-Instruct模型。此外，TPO在推理过程中随搜索宽度和深度的增加而高效扩展。通过案例研究，我们展示了TPO如何利用LLM的固有能力解释并响应奖励信号。研究表明，TPO是一种实用、轻量级的测试时偏好优化方案，能够即时实现对齐。代码已开源：https://github.com/yafuly/TPO。

> Large language models (LLMs) demonstrate impressive performance but lack the flexibility to adapt to human preferences quickly without retraining. In this work, we introduce Test-time Preference Optimization (TPO), a framework that aligns LLM outputs with human preferences during inference, removing the need to update model parameters. Rather than relying on purely numerical rewards, TPO translates reward signals into textual critiques and uses them as textual rewards to iteratively refine its response. Evaluations on benchmarks covering instruction following, preference alignment, safety, and mathematics reveal that TPO progressively improves alignment with human preferences. Notably, after only a few TPO steps, the initially unaligned Llama-3.1-70B-SFT model can surpass the aligned counterpart, Llama-3.1-70B-Instruct. Furthermore, TPO scales efficiently with both the search width and depth during inference. Through case studies, we illustrate how TPO exploits the innate capacity of LLM to interpret and act upon reward signals. Our findings establish TPO as a practical, lightweight alternative for test-time preference optimization, achieving alignment on the fly. Our code is publicly available at https://github.com/yafuly/TPO.

[Arxiv](https://arxiv.org/abs/2501.12895)