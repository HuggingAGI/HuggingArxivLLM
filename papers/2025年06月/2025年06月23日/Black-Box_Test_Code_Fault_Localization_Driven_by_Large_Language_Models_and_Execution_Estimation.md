# 基于大型语言模型与执行评估的黑盒测试代码故障定位驱动型方法研究

发布时间：2025年06月23日

`LLM应用` `软件工程` `测试自动化`

> Black-Box Test Code Fault Localization Driven by Large Language Models and Execution Estimation

# 摘要

> 故障定位（FL）是调试中的关键步骤，通常需要通过多次执行来定位故障代码区域。然而，在面对非确定性故障或高执行成本时，多次执行可能并不实际。尽管近期研究利用大型语言模型（LLMs）实现了无执行的故障定位，但这些研究主要关注被测系统（SUT）中的故障，而往往忽略了复杂系统测试代码中的故障。然而，测试代码的故障同样重要，因为许多实际故障是由有缺陷的测试代码引发的。为了解决这些挑战，我们提出了一种完全静态的、基于LLM的系统测试代码故障定位（TCFL）方法，无需执行测试用例。我们的方法利用单一故障执行日志，通过三种新型算法估计测试的执行轨迹，仅识别可能与故障相关的代码语句。结合错误信息，这一精简后的轨迹被用于提示LLM对潜在故障位置进行排序。我们的黑盒、系统级方法无需访问SUT源代码，适用于评估整个系统行为的大规模测试脚本。我们使用一个工业级的、未在LLM预训练中使用的故障测试用例数据集，在函数、代码块和代码行三个层次上评估了我们的技术。结果显示，我们最佳的估计轨迹与实际轨迹非常接近，F1分数约为90%。此外，精简复杂的系统测试代码可将LLM推理时间减少高达34%，而不会影响故障定位性能。我们的结果进一步表明，代码块级别的TCFL在缩小搜索空间的同时保留了有用的上下文，实现了实际的平衡，在前3名命中率（Hit@3）上达到了81%。

> Fault localization (FL) is a critical step in debugging which typically relies on repeated executions to pinpoint faulty code regions. However, repeated executions can be impractical in the presence of non-deterministic failures or high execution costs. While recent efforts have leveraged Large Language Models (LLMs) to aid execution-free FL, these have primarily focused on identifying faults in the system under test (SUT) rather than in the often complex system test code. However, the latter is also important as, in practice, many failures are triggered by faulty test code. To overcome these challenges, we introduce a fully static, LLM-driven approach for system test code fault localization (TCFL) that does not require executing the test case. Our method uses a single failure execution log to estimate the test's execution trace through three novel algorithms that identify only code statements likely involved in the failure. This pruned trace, combined with the error message, is used to prompt the LLM to rank potential faulty locations. Our black-box, system-level approach requires no access to the SUT source code and is applicable to large test scripts that assess full system behavior. We evaluate our technique at function, block, and line levels using an industrial dataset of faulty test cases not previously used in pre-training LLMs. Results show that our best estimated trace closely match actual traces, with an F1 score of around 90%. Additionally, pruning the complex system test code reduces the LLM's inference time by up to 34% without any loss in FL performance. Our results further suggest that block-level TCFL offers a practical balance, narrowing the search space while preserving useful context, achieving an 81% hit rate at top-3 (Hit@3).

[Arxiv](https://arxiv.org/abs/2506.19045)