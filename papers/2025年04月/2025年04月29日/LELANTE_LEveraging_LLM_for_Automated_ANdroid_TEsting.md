# LELANTE：借助 LLM 实现安卓自动化测试

发布时间：2025年04月29日

`LLM应用` `移动应用`

> LELANTE: LEveraging LLM for Automated ANdroid TEsting

# 摘要

> 针对 Android 应用的自然语言测试用例描述，现有的测试方法需要开发人员手动编写脚本，这一过程耗时费力，且随着 UI 界面的演变，维护成本显著增加。本文提出了一种开创性的框架 LELANTE，它利用大型语言模型（LLMs）无需预先编写脚本即可实现测试用例的自动化执行。LELANTE 通过解析自然语言描述，迭代生成行动计划，并直接在 Android 屏幕上执行操作。它采用屏幕细化技术提升 LLM 的可解释性，构建结构化提示，并基于链式推理实现动作生成。为了优化计算成本和扩展性，LELANTE 还采用了模型蒸馏技术。在 10 个流行 Android 应用的 390 个测试用例中，LELANTE 实现了 73% 的成功执行率。这表明 LLMs 能够有效连接自然语言描述与自动化执行，显著提升了移动测试的扩展性和适应性。

> Given natural language test case description for an Android application, existing testing approaches require developers to manually write scripts using tools such as Appium and Espresso to execute the corresponding test case. This process is labor-intensive and demands significant effort to maintain as UI interfaces evolve throughout development. In this work, we introduce LELANTE, a novel framework that utilizes large language models (LLMs) to automate test case execution without requiring pre-written scripts. LELANTE interprets natural language test case descriptions, iteratively generate action plans, and perform the actions directly on the Android screen using its GUI. LELANTE employs a screen refinement process to enhance LLM interpretability, constructs a structured prompt for LLMs, and implements an action generation mechanism based on chain-of-thought reasoning of LLMs. To further reduce computational cost and enhance scalability, LELANTE utilizes model distillation using a foundational LLM. In experiments across 390 test cases spanning 10 popular Android applications, LELANTE achieved a 73% test execution success rate. Our results demonstrate that LLMs can effectively bridge the gap between natural language test case description and automated execution, making mobile testing more scalable and adaptable.

[Arxiv](https://arxiv.org/abs/2504.20896)