# 多模态图对比学习与提示在图表问答中的应用

发布时间：2025年01月08日

`LLM应用

理由：这篇论文主要讨论了如何通过构建多模态场景图和引入多模态图对比学习来提升图表问答（ChartQA）的性能。虽然涉及到了多模态大语言模型（MLLMs）的使用，但重点在于如何应用这些技术来解决具体的图表问答问题，而不是对LLM本身的理论研究或Agent、RAG的应用。因此，将其归类为LLM应用更为合适。` `图表分析` `多模态学习`

> Multimodal Graph Constrastive Learning and Prompt for ChartQA

# 摘要

> ChartQA 因图表元素的复杂分布和底层数据中的隐含模式而面临巨大挑战。本章中，我们构建了一个联合多模态场景图，清晰呈现了图表元素及其相关模式之间的关系。
    我们的多模态场景图包含视觉图和文本图两部分，分别捕捉图表的结构和语义信息。为统一不同模态的表示，我们引入了多模态图对比学习，通过最大化跨模态图中相同对象节点的相似性来学习统一表示。学习到的图表示可无缝融入 transformer 解码器作为软提示。
    此外，针对零-shot 场景中对多模态大语言模型（MLLMs）的需求，我们设计了思维链（CoT）提示以减少幻觉。我们在 ChartQA、OpenCQA 和 ChartX 等公开基准上测试了这些方法，验证了其有效性和性能提升。

> ChartQA presents significant challenges due to the complex distribution of chart elements and the implicit patterns embedded within the underlying data. In this chapter, we have developed a joint multimodal scene graph for charts, explicitly representing the relationships between chart elements and their associated patterns.
  Our proposed multimodal scene graph consists of two components: a visual graph and a textual graph, each designed to capture the structural and semantic information within the chart. To unify representations across these different modalities, we introduce a multimodal graph contrastive learning approach that learns unified representations by maximizing similarity between nodes representing the same object across multimodal graphs. The learned graph representations can be seamlessly incorporated into a transformer decoder as a soft prompt.
  Additionally, given the growing need for Multimodal Large Language Models (MLLMs) in zero-shot scenarios, we have designed Chain-of-Thought (CoT) prompts for MLLMs to reduce hallucinations. We tested both methods on public benchmarks such as ChartQA, OpenCQA, and ChartX, demonstrating improved performance and validating the effectiveness of our proposed methods.

[Arxiv](https://arxiv.org/abs/2501.04303)