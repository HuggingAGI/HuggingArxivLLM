# LLMQuoter: 通过高效提取大上下文中的引用来增强 RAG 能力
发布时间：2025年01月09日

`RAG`
> LLMQuoter: Enhancing RAG Capabilities Through Efficient Quote Extraction From Large Contexts
>
> 我们推出了LLMQuoter，一个轻量级、基于蒸馏的模型，旨在通过提取最相关的文本证据来增强检索增强生成（RAG），助力下游推理任务。LLMQuoter基于LLaMA-3B架构，并在HotpotQA的15,000个样本子集上使用LoRA进行微调，采用“先引用后回答”策略，高效识别关键引用，再将精选片段传递给推理模型。这一流程降低了认知负担，并在小型和大型语言模型上均优于全上下文方法（如RAFT），准确率提升超过20个百分点。通过高性能教师模型的知识蒸馏，LLMQuoter在资源高效的微调设置中表现出色，无需大量重新训练即可显著提升性能。我们的研究展示了基于蒸馏的引用推理在简化复杂工作流程中的潜力，为研究者和从业者提供了一个可扩展且实用的解决方案。
>
> https://arxiv.org/abs/2501.05554

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2501.05554](https://arxiv.org/abs/2501.05554)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)