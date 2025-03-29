# RALLRec+: 集成推理能力的检索增强型大型语言模型推荐系统
发布时间：2025年03月26日

`推荐系统`
> RALLRec+: Retrieval Augmented Large Language Model Recommendation with Reasoning
>
> 大型语言模型（LLMs）正在被广泛应用于推荐系统中，以提升对用户行为的理解。检索增强生成（RAG）技术进一步被引入，用于提高内容的相关性和系统性能。然而，现有RAG方法存在两大关键问题：	extit{(i)} 在	extit{检索阶段}，它们过度依赖文本语义，常常忽略最相关的内容，导致系统效果受限；	extit{(ii)} 在	extit{生成阶段}，缺乏明确的链式推理能力，进一步制约了其潜力。

    本文提出了一种创新的基于表示学习和推理增强的检索-增强大型语言模型推荐方法（RALLRec+）。具体而言，在检索阶段，我们通过提示LLMs生成详细的内容描述，并结合从LLM和推荐模型中提取的文本和协作信号进行联合表示学习。为了应对用户兴趣随时间变化的特性，我们设计了一种简单而有效的重排序方法，以捕捉用户偏好的动态变化。在生成阶段，我们首先评估推理型LLMs在推荐任务中的表现，揭示了其潜在的优势和挑战。随后，我们引入知识注入提示和基于一致性的融合方法，将推理型LLMs与通用型LLMs相结合，从而显著提升了整体推荐效果。通过在三个真实世界数据集上的广泛实验，我们验证了该方法的有效性和优越性。
>
> https://arxiv.org/abs/2503.20430

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.20430](https://arxiv.org/abs/2503.20430)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)