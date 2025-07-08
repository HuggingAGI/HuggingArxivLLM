# 双模态感知门控提示微调方法在少样本多模态讽刺检测中的应用

发布时间：2025年07月06日

`LLM应用` `社交媒体` `多模态分析`

> Dual Modality-Aware Gated Prompt Tuning for Few-Shot Multimodal Sarcasm Detection

# 摘要

> 社交媒体上多模态内容的广泛应用凸显了有效反讽检测的重要性，这对于提升观点挖掘具有重要意义。然而，现有模型严重依赖大型标注数据集，在现实场景中标签数据稀缺的情况下，这些模型的适用性较低。这促使我们探索在小样本学习场景下的反讽检测问题。为此，我们引入了DMDP（深度模态解耦提示微调），一个专为小样本多模态反讽检测设计的全新框架。

与以往方法使用跨模态通用浅层提示不同，DMDP采用了针对文本和视觉编码器的门控、模态专用深度提示。这些提示被注入到多个网络层中，从而实现层次化特征学习，更好地捕捉多样化的反讽类型。为了增强模态内学习，我们在各层引入了提示共享机制，使模型能够聚合低级和高级语义线索。此外，跨模态提示对齐模块促进了图像和文本表示之间的精细交互，提升了模型识别微妙反讽意图的能力。

在两个公共数据集上的实验表明，DMDP在小样本和极低资源场景下均表现出色。进一步的跨数据集评估显示，DMDP在不同领域中具有良好的泛化能力，始终超越基线方法。

> The widespread use of multimodal content on social media has heightened the need for effective sarcasm detection to improve opinion mining. However, existing models rely heavily on large annotated datasets, making them less suitable for real-world scenarios where labeled data is scarce. This motivates the need to explore the problem in a few-shot setting. To this end, we introduce DMDP (Deep Modality-Disentangled Prompt Tuning), a novel framework for few-shot multimodal sarcasm detection. Unlike prior methods that use shallow, unified prompts across modalities, DMDP employs gated, modality-specific deep prompts for text and visual encoders. These prompts are injected across multiple layers to enable hierarchical feature learning and better capture diverse sarcasm types. To enhance intra-modal learning, we incorporate a prompt-sharing mechanism across layers, allowing the model to aggregate both low-level and high-level semantic cues. Additionally, a cross-modal prompt alignment module enables nuanced interactions between image and text representations, improving the model's ability to detect subtle sarcastic intent. Experiments on two public datasets demonstrate DMDP's superior performance in both few-shot and extremely low-resource settings. Further cross-dataset evaluations show that DMDP generalizes well across domains, consistently outperforming baseline methods.

[Arxiv](https://arxiv.org/abs/2507.04468)