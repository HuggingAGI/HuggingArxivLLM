# ReuseDroid：一个由VLM驱动的Android UI测试迁移工具，通过主动反馈增强性能。

发布时间：2025年04月03日

`LLM应用` `软件工程` `移动应用开发`

> ReuseDroid: A VLM-empowered Android UI Test Migrator Boosted by Active Feedback

# 摘要

> # GUI测试迁移的创新框架：REUSEDROID

在移动应用开发中，GUI测试是确保产品质量的关键环节。然而，创建和维护GUI测试不仅耗时费力，而且成本高昂。针对这一挑战，研究者提出了多种技术，旨在将一个应用的GUI测试迁移到另一个功能相似的应用中。例如，基于映射的方法通过将源应用测试遍历的GUI元素与目标应用中的相应元素对齐来实现迁移。此外，还有研究提出利用大型语言模型（LLMs），通过对源测试中的GUI任务进行调整来实现迁移。然而，这些方法在处理源应用与目标应用之间不同的操作逻辑时效果不佳。由于缺乏对这些流程的分析，GUI元素的语义可能无法被正确推断。

为了解决这一问题，我们提出了REUSEDROID——一个基于大型视觉-语言模型（VLMs）的创新多智能体框架，专为GUI测试迁移设计。REUSEDROID由多个基于VLM的智能体组成，每个智能体负责处理测试迁移过程中的一个阶段，并利用GUI页面中嵌入的视觉和文本信息。REUSEDROID的核心理念是，仅基于相似应用之间共享的核心逻辑进行测试迁移，而它们的整体操作逻辑可能有所不同。

为了验证REUSEDROID的效果，我们在LinPro数据集上进行了实验。该数据集包含4个类别下39个热门应用的578个迁移任务。实验结果表明，REUSEDROID成功完成了90.3%的迁移任务，分别比最佳的基于映射和基于LLM的基线方法高出318.1%和109.1%。这一结果充分展示了REUSEDROID在GUI测试迁移领域的卓越性能。


> GUI testing is an essential quality assurance process in mobile app development. However, the creation and maintenance of GUI tests for mobile apps are resource-intensive and costly. Recognizing that many apps share similar functionalities, researchers have proposed various techniques to migrate GUI tests from one app to another with similar features. For example, some techniques employ mapping-based approaches to align the GUI elements traversed by the tests of a source app to those present in the target app. Other test migration techniques have also been proposed to leverage large language models (LLMs) by adapting the GUI tasks in source tests. However, these techniques are ineffective in dealing with different operational logic between the source and target apps. The semantics of GUI elements may not be correctly inferred due to the missing analysis of these flows. In this work, we propose REUSEDROID, a novel multiagent framework for GUI test migration empowered by Large Vision-Language Models (VLMs). REUSEDROID is powered by multiple VLM-based agents, each tackling a stage of the test migration process by leveraging the relevant visual and textual information embedded in GUI pages. An insight of REUSEDROID is to migrate tests based only on the core logic shared across similar apps, while their entire operational logic could differ. We evaluate REUSEDROID on LinPro, a new test migration dataset that consists of 578 migration tasks for 39 popular apps across 4 categories. The experimental result shows that REUSEDROID can successfully migrate 90.3% of the migration tasks, outperforming the best mapping-based and LLM-based baselines by 318.1% and 109.1%, respectively.

[Arxiv](https://arxiv.org/abs/2504.02357)