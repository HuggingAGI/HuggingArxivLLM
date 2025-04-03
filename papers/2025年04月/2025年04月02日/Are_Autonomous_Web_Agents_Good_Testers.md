# 自主网络代理能否胜任测试者的角色？

发布时间：2025年04月02日

`LLM应用` `软件测试` `软件工程`

> Are Autonomous Web Agents Good Testers?

# 摘要

> 尽管自动化测试技术不断进步，手动测试依然占据主导地位，原因在于测试脚本的脆弱性导致高昂的维护成本——即使应用程序结构稍有变动，脚本也常会失效。大型语言模型（LLMs）的最新进展为开发能够自主与应用程序交互的自主网络代理（AWAs）提供了潜在的替代方案。这些代理可作为自主测试代理（ATAs），通过利用与人类测试人员相似的自然语言指令，可能减少对维护密集型自动化脚本的依赖。本文探讨了将AWAs应用于自然语言测试用例执行的可行性及其评估方法。我们的贡献包括：（1）一个包含三个离线Web应用的基准测试，以及一套分为通过和失败情况的113个手动测试用例，用于评估和比较ATAs的性能；（2）SeeAct-ATA和pinATA，两个开源的ATA实现，能够执行测试步骤、验证断言并给出结论；（3）基于我们基准测试的比较实验，量化了ATAs的有效性。最后，我们进行了定性评估，以识别我们表现最佳的实现PinATA的局限性。研究发现，与更先进的PinATA相比，我们的简单实现SeeAct-ATA在执行测试用例时表现不佳（性能提升50%）。然而，尽管PinATA实现了约60%的正确结论率和高达94%的令人鼓舞的特异性，我们仍识别出需要解决的几个局限性，以开发出更坚韧和可靠的ATAs，从而为稳健且低维护的测试自动化铺平道路。CCS主题：$ullet$ 软件及其工程 $ightarrow$ 软件测试与调试。

> Despite advances in automated testing, manual testing remains prevalent due to the high maintenance demands associated with test script fragility-scripts often break with minor changes in application structure. Recent developments in Large Language Models (LLMs) offer a potential alternative by powering Autonomous Web Agents (AWAs) that can autonomously interact with applications. These agents may serve as Autonomous Test Agents (ATAs), potentially reducing the need for maintenance-heavy automated scripts by utilising natural language instructions similar to those used by human testers. This paper investigates the feasibility of adapting AWAs for natural language test case execution and how to evaluate them.  We contribute with (1) a benchmark of three offline web applications, and a suite of 113 manual test cases, split between passing and failing cases, to evaluate and compare ATAs performance, (2) SeeAct-ATA and pinATA, two open-source ATA implementations capable of executing test steps, verifying assertions and giving verdicts, and (3) comparative experiments using our benchmark that quantifies our ATAs effectiveness. Finally we also proceed to a qualitative evaluation to identify the limitations of PinATA, our best performing implementation.  Our findings reveal that our simple implementation, SeeAct-ATA, does not perform well compared to our more advanced PinATA implementation when executing test cases (50% performance improvement). However, while PinATA obtains around 60% of correct verdict and up to a promising 94% specificity, we identify several limitations that need to be addressed to develop more resilient and reliable ATAs, paving the way for robust, low maintenance test automation.  CCS Concepts: $\bullet$ Software and its engineering $\rightarrow$ Software testing and debugging.

[Arxiv](https://arxiv.org/abs/2504.01495)