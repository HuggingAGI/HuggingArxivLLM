# A-MESS：基于锚点的多模态嵌入与语义同步方法，用于多模态意图识别

发布时间：2025年03月25日

`LLM应用` `多模态` `人机交互`

> A-MESS: Anchor based Multimodal Embedding with Semantic Synchronization for Multimodal Intent Recognition

# 摘要

> 在多模态意图识别（MIR）领域，我们的目标是通过整合语言文本、肢体动作和语气等多种模态，精准识别人类意图。然而，现有方法在捕捉模态间的内在联系和意图的语义表示方面存在不足。为了解决这些问题，我们提出了基于锚点的多模态嵌入语义同步（A-MESS）框架。首先，我们设计了一个基于锚点的多模态嵌入（A-ME）模块，该模块采用创新的嵌入融合机制，高效整合多模态输入。此外，我们开发了一种语义同步（SS）策略，并结合三元对比学习流水线，通过与大型语言模型生成的标签描述同步多模态表示，优化了整个过程。经过全面实验验证，我们的A-MESS不仅达到了当前最先进的水平，更为多模态表示和下游任务提供了深刻的见解和重要的研究方向。

> In the domain of multimodal intent recognition (MIR), the objective is to recognize human intent by integrating a variety of modalities, such as language text, body gestures, and tones. However, existing approaches face difficulties adequately capturing the intrinsic connections between the modalities and overlooking the corresponding semantic representations of intent. To address these limitations, we present the Anchor-based Mul- timodal Embedding with Semantic Synchronization (A-MESS) framework. We first design an Anchor-based Multimodal Embed- ding (A-ME) module that employs an anchor-based embedding fusion mechanism to integrate multimodal inputs. Furthermore, we develop a Semantic Synchronization (SS) strategy with the Triplet Contrastive Learning pipeline, which optimizes the pro- cess by synchronizing multimodal representation with label de- scriptions produced by the large language model. Comprehensive experiments indicate that our A-MESS achieves state-of-the-art and provides substantial insight into multimodal representation and downstream tasks.

[Arxiv](https://arxiv.org/abs/2503.19474)