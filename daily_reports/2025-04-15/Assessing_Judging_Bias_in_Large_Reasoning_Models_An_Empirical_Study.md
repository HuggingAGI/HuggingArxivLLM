# 大型推理模型的判断偏差评估：实证研究
发布时间：2025年04月14日


> Assessing Judging Bias in Large Reasoning Models: An Empirical Study
>
> 大型推理模型（LRMs）如 DeepSeek-R1 和 OpenAI-o1 展现出了卓越的推理能力，这引发了关于它们在作为大型语言模型（LLM）裁判时的偏见问题。我们提供了一个全面的基准测试，比较了 LLMs 和 LRMs 在主观偏好对齐数据集和客观事实数据集中的裁判偏见。通过对随大流偏见、权威偏见、位置偏见和分心偏见的调查，我们发现了四个关键发现：(1) 尽管 LRMs 具备先进的推理能力，但它们仍然容易受到上述偏见的影响；(2) 与 LLMs 相比，LRMs 在与事实相关的数据集上表现出了更好的鲁棒性；(3) LRMs 显示出显著的位置偏见，更倾向于选择较后出现的选项；(4) 我们发现了一种新型的“表面反思偏见”，其中模仿推理的短语（例如，“等等，让我想想...”）对模型的判断产生了显著影响。为了应对这些偏见，我们设计并评估了三种缓解策略：定制化系统提示，可将偏好对齐数据集中的裁判偏见降低高达 19%，并在事实相关数据集中降低 14%；在上下文学习中，偏好任务的改进高达 27%，但在事实任务中表现不一致；以及自我反思机制，在偏好数据集中可将偏见降低 10%，在事实相关数据集中降低 16%，其中自我反思对 LRMs 尤其有效。我们的研究为开发更可靠的 LLM 作为裁判框架提供了重要见解，特别是在 LRMs 日益被部署为自动裁判的情况下。
>
> https://arxiv.org/abs/2504.09946

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.09946](https://arxiv.org/abs/2504.09946)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)