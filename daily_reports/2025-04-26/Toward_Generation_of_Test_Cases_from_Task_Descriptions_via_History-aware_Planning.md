# 面向测试用例生成：基于任务描述的规划方法
发布时间：2025年04月19日


> Toward Generation of Test Cases from Task Descriptions via History-aware Planning
>
> 在自动化网络测试中，从自然语言任务描述生成测试脚本是提升测试生成流程的关键。这一过程需要创建正确的动作序列，以生成用于未来测试的脚本。然而，现有的先进方法在生成动作序列时面临两大挑战：要么需要大量人工演示，要么无法利用历史网络内容和动作来决定下一步。为了解决这些问题，我们提出了HxAgent——一种基于大型语言模型的迭代代理规划方法。HxAgent通过以下三方面决定下一步动作：1) 当前内容和可行动作的观察，2) 短期记忆中的历史状态和动作，3) 长期积累的正确与错误动作序列经验。该代理生成的一系列动作即为自动化的测试用例，用于验证任务的正确性。我们通过两个数据集对HxAgent进行了全面评估。在MiniWoB++数据集上，我们的方法实现了97%的精确匹配准确率，与最佳基线方法持平，且无需人工演示。对于涉及多个动作和屏幕导航的复杂任务，HxAgent的平均精确匹配率达到82%。在包含350个任务实例的第二个数据集上（涵盖YouTube、LinkedIn、Facebook和Google等七个流行网站），HxAgent表现优异，87%的动作序列与地面真实值完全匹配，前缀匹配率更是达到93%，比基线方法高出59%。
>
> https://arxiv.org/abs/2504.14336

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.14336](https://arxiv.org/abs/2504.14336)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)