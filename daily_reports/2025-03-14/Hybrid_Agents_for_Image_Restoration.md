# # 图像修复的混合智能体方案
发布时间：2025年03月13日

`Agent应用`
> Hybrid Agents for Image Restoration
>
> 现有图像修复 (IR) 研究通常分别专注于特定任务或通用模式，依赖用户的模式选择，缺乏多种特定任务/通用修复模式之间的协作。这导致了对非专业用户的交互不足，限制了他们在复杂现实应用中的修复能力。在本研究中，我们提出了HybridAgent，旨在将多种修复模式整合到一个统一的图像修复模型中，并通过我们的混合智能体实现智能高效的用户交互。具体来说，我们提出了快速、慢速和反馈修复智能体的混合规则。其中，慢速修复智能体通过我们的指令微调数据集优化了强大的多模态大型语言模型 (MLLM)，以识别具有模糊用户提示的图像中的退化，并相应地调用合适的修复工具。快速修复智能体基于轻量级大型语言模型 (LLM) 通过上下文学习设计，能够理解具有简单清晰要求的用户提示，从而避免了MLLM不必要的时间和资源消耗。此外，我们为HybridAgents引入了混合失真去除模式，这是之前基于智能体的工作中未关注但至关重要的内容。它可以有效防止分步图像修复中的错误传播，并大幅提高智能体系统的效率。我们通过合成和真实世界的图像修复任务验证了HybridAgent的有效性。
>
> https://arxiv.org/abs/2503.10120

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.10120](https://arxiv.org/abs/2503.10120)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)