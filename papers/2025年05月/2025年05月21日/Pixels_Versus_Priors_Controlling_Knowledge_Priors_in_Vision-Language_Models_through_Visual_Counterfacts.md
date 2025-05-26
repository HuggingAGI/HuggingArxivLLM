# 像素与先验：通过视觉反事实方法控制视觉-语言模型中的知识先验

发布时间：2025年05月21日

`LLM理论

理由：这篇论文探讨了多模态大型语言模型在推理过程中依赖世界知识还是视觉输入的问题，深入分析了模型的工作机制，并提出了一种新的调控方法。这些内容属于对LLM内部工作原理的理论研究，因此归类为LLM理论。` `视觉信息处理` `多模态模型`

> Pixels Versus Priors: Controlling Knowledge Priors in Vision-Language Models through Visual Counterfacts

# 摘要

> 多模态大型语言模型（MLLMs）在视觉问答等任务中表现优异，但它们的推理能力究竟是依赖记忆中的世界知识，还是依赖输入图像的视觉信息，这一问题仍有待解答。为探究此问题，我们推出了Visual CounterFact——一个视觉上生动形象的反事实数据集，它巧妙地将世界知识的先验（如红色草莓）与视觉输入（如蓝色草莓）置于直接冲突之中。

通过Visual CounterFact，我们发现模型的预测过程呈现出有趣的变化：初始预测更多依赖记忆中的先验知识，但随着模型深度的增加，预测逐渐转向视觉证据。这一动态揭示了两种信息源之间的竞争关系，最终视觉输入在推理过程中占据了主导地位。

为了更好地控制这一行为，我们提出了Pixels Versus Priors（PvP）引导向量——一种通过激活级别干预机制，来调控模型输出偏向世界知识或视觉输入的创新方法。实验结果表明，PvP成功地将92.5%的颜色和74.6%的大小预测从先验知识引导至反事实场景。这些发现不仅深化了我们对多模态模型工作原理的理解，更为调控其推理行为提供了有力工具。


> Multimodal Large Language Models (MLLMs) perform well on tasks such as visual question answering, but it remains unclear whether their reasoning relies more on memorized world knowledge or on the visual information present in the input image. To investigate this, we introduce Visual CounterFact, a new dataset of visually-realistic counterfactuals that put world knowledge priors (e.g, red strawberry) into direct conflict with visual input (e.g, blue strawberry). Using Visual CounterFact, we show that model predictions initially reflect memorized priors, but shift toward visual evidence in mid-to-late layers. This dynamic reveals a competition between the two modalities, with visual input ultimately overriding priors during evaluation. To control this behavior, we propose Pixels Versus Priors (PvP) steering vectors, a mechanism for controlling model outputs toward either world knowledge or visual input through activation-level interventions. On average, PvP successfully shifts 92.5% of color and 74.6% of size predictions from priors to counterfactuals. Together, these findings offer new tools for interpreting and controlling factual behavior in multimodal models.

[Arxiv](https://arxiv.org/abs/2505.17127)