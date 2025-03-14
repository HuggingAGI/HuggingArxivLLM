# StepMathAgent：一种通过错误树逐步评估数学过程的智能体

发布时间：2025年03月13日

`Agent`

> StepMathAgent: A Step-Wise Agent for Evaluating Mathematical Processes through Tree-of-Error

# 摘要

> 评估数学能力是衡量大型语言模型整体性能的关键环节。然而，现有评估方法往往仅关注最终答案，导致评估结果存在高度不准确和不可解释的问题，同时也无法对证明过程或开放性问题进行评估。为了解决这些问题，我们提出了一种基于错误树的新型数学过程评估代理——StepMathAgent。该代理集成了四个核心内部操作：逻辑步骤分割、步骤评分、分数聚合和错误树生成，以及四个外部扩展模块：难度校准、简洁性评估、完整性和格式评估。此外，我们还引入了StepMathBench，这是一个包含1,000个分步评估实例的基准测试集，这些实例源自200个高质量数学问题，按问题类型、学科领域和难度级别进行分类。在StepMathBench上的实验表明，我们的StepMathAgent在所有现有最先进的方法中表现最佳，展示了与人类一致的评估偏好，并且在各种场景中具有广泛适用性。我们的数据和代码可在https://github.com/SHU-XUN/StepMathAgent获取。

> Evaluating mathematical capabilities is critical for assessing the overall performance of large language models (LLMs). However, existing evaluation methods often focus solely on final answers, resulting in highly inaccurate and uninterpretable evaluation outcomes, as well as their failure to assess proof or open-ended problems. To address these issues, we propose a novel mathematical process evaluation agent based on Tree-of-Error, called StepMathAgent. This agent incorporates four internal core operations: logical step segmentation, step scoring, score aggregation and error tree generation, along with four external extension modules: difficulty calibration, simplicity evaluation, completeness validation and format assessment. Furthermore, we introduce StepMathBench, a benchmark comprising 1,000 step-divided process evaluation instances, derived from 200 high-quality math problems grouped by problem type, subject category and difficulty level. Experiments on StepMathBench show that our proposed StepMathAgent outperforms all state-of-the-art methods, demonstrating human-aligned evaluation preferences and broad applicability to various scenarios. Our data and code are available at https://github.com/SHU-XUN/StepMathAgent.

[Arxiv](https://arxiv.org/abs/2503.10105)