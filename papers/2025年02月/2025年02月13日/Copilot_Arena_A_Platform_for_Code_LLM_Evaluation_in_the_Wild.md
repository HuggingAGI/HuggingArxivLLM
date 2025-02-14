# Copilot Arena：一个用于在真实环境中评估代码LLM的平台

发布时间：2025年02月13日

`LLM应用` `软件开发`

> Copilot Arena: A Platform for Code LLM Evaluation in the Wild

# 摘要

> 评估大型语言模型（LLMs）在真实环境中的编码能力是一项充满挑战的任务，目前尚无明确的解决方案。我们推出Copilot Arena平台，通过与开发者的日常工作环境无缝集成，收集用户对代码生成的偏好。Copilot Arena包含三个核心组件：用于比较模型输出对的新型界面、优化以减少延迟的采样策略，以及支持代码补全功能的提示方案。该平台已为10个模型提供了超过450万条建议，并收集了11,000多个成对的判断结果。我们的研究结果突显了在集成环境中进行模型评估的重要性。通过Copilot Arena，我们发现模型的排名与现有评估结果存在显著差异，这主要归因于Copilot Arena中包含的更贴近真实场景的数据和任务分布。此外，我们还发现了人类对代码的一些新见解，例如用户偏好在不同编程语言间保持一致性，但因任务类别不同而产生显著差异。为了推动以人类为中心的评估并增进对编码助手的理解，我们开源了Copilot Arena，并发布了相关数据。

> Evaluating in-the-wild coding capabilities of large language models (LLMs) is a challenging endeavor with no clear solution. We introduce Copilot Arena, a platform to collect user preferences for code generation through native integration into a developer's working environment. Copilot Arena comprises a novel interface for comparing pairs of model outputs, a sampling strategy optimized to reduce latency, and a prompting scheme to enable code completion functionality. Copilot Arena has served over 4.5 million suggestions from 10 models and collected over 11k pairwise judgements. Our results highlight the importance of model evaluations in integrated settings. We find that model rankings from Copilot Arena differ from those of existing evaluations, which we attribute to the more realistic distribution of data and tasks contained in Copilot Arena. We also identify novel insights into human preferences on code such as an observed consistency in user preference across programming languages yet significant variation in preference due to task category. We open-source Copilot Arena and release data to enable human-centric evaluations and improve understanding of coding assistants.

[Arxiv](https://arxiv.org/abs/2502.09328)