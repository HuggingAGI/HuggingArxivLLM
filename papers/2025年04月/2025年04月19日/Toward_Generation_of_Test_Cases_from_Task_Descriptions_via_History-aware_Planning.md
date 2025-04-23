# 面向测试用例生成：基于任务描述的规划方法

发布时间：2025年04月19日

`Agent` `软件工程` `网络测试`

> Toward Generation of Test Cases from Task Descriptions via History-aware Planning

# 摘要

> 在自动化网络测试中，从自然语言任务描述生成测试脚本是提升测试生成流程的关键。这一过程需要创建正确的动作序列，以生成用于未来测试的脚本。然而，现有的先进方法在生成动作序列时面临两大挑战：要么需要大量人工演示，要么无法利用历史网络内容和动作来决定下一步。为了解决这些问题，我们提出了HxAgent——一种基于大型语言模型的迭代代理规划方法。HxAgent通过以下三方面决定下一步动作：1) 当前内容和可行动作的观察，2) 短期记忆中的历史状态和动作，3) 长期积累的正确与错误动作序列经验。该代理生成的一系列动作即为自动化的测试用例，用于验证任务的正确性。我们通过两个数据集对HxAgent进行了全面评估。在MiniWoB++数据集上，我们的方法实现了97%的精确匹配准确率，与最佳基线方法持平，且无需人工演示。对于涉及多个动作和屏幕导航的复杂任务，HxAgent的平均精确匹配率达到82%。在包含350个任务实例的第二个数据集上（涵盖YouTube、LinkedIn、Facebook和Google等七个流行网站），HxAgent表现优异，87%的动作序列与地面真实值完全匹配，前缀匹配率更是达到93%，比基线方法高出59%。

> In automated web testing, generating test scripts from natural language task descriptions is crucial for enhancing the test generation process. This activity involves creating the correct sequences of actions to form test scripts for future testing activities. Current state-of-the-art approaches are limited in generating these action sequences, as they either demand substantial manual effort for human demonstrations or fail to consider the history of previous web content and actions to decide the next action. In this paper, we introduce HxAgent, an iterative large language model agent planning approach that determines the next action based on: 1) observations of the current contents and feasible actions, 2) short-term memory of previous web states and actions, and 3) long-term experience with (in)correct action sequences. The agent generates a sequence of actions to perform a given task, which is effectively an automated test case to verify the task. We conducted an extensive empirical evaluation of HxAgent using two datasets. On the MiniWoB++ dataset, our approach achieves 97% exact-match accuracy that is comparable to the best baselines while eliminating the need for human demonstrations required by those methods. For complex tasks requiring navigation through multiple actions and screens, HxAgent achieves an average 82% exact-match. On the second dataset, comprising 350 task instances across seven popular websites, including YouTube, LinkedIn, Facebook, and Google, HxAgent achieves high performance, with 87% of the action sequences exactly matching the ground truth and a prefix-match of 93%, outperforming the baseline by 59%.

[Arxiv](https://arxiv.org/abs/2504.14336)