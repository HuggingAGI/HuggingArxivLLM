# $IF-GUIDE$: 基于影响函数的大型语言模型净化方法

发布时间：2025年06月02日

`LLM理论` `人工智能` `数据安全`

> $IF-GUIDE$: Influence Function-Guided Detoxification of LLMs

# 摘要

> 我们研究了训练数据如何导致大型语言模型中产生有害行为。大多数先前减少模型毒性的工作采用$reactive$方法，例如微调预训练（且可能有毒性）的模型，以使其与人类价值观对齐。相比之下，我们提出了一种$proactive$方法$-$IF-Guide$-$它利用影响函数来识别训练数据中的有害标记，并在训练过程中抑制它们的影响。为此，我们首先表明标准影响函数无法有效发现有害的训练记录。然后，我们提出了一种新的适应方法，用于衡量训练数据到模型毒性的标记级归属，并介绍了选择有毒训练文档的技术以及一种可以集成到预训练和微调中的学习目标。此外，IF-Guide 不依赖于通常需要的现有对齐方法的人类偏好数据。在评估中，我们展示了 IF-Guide 显著减少了显性和隐性毒性$-$与未经审查的模型相比最多减少 10 倍，与基线对齐方法（如 DPO 和 RAD）相比最多减少 3 倍$-$在预训练和微调场景中均如此。IF-Guide 在计算上是高效的：不需要十亿参数规模的模型来计算影响分数；一个百万参数规模的模型$-$参数数量减少 7.5 倍$-$可以有效地作为代理来识别有害数据。

> We study how training data contributes to the emergence of toxic behaviors in large-language models. Most prior work on reducing model toxicity adopts $reactive$ approaches, such as fine-tuning pre-trained (and potentially toxic) models to align them with human values. In contrast, we propose a $proactive$ approach$-$IF-Guide$-$which leverages influence functions to identify harmful tokens within any training data and suppress their impact during training. To this end, we first show that standard influence functions are ineffective at discovering harmful training records. We then present a novel adaptation that measures token-level attributions from training data to model toxicity, along with techniques for selecting toxic training documents and a learning objective that can be integrated into both pre-training and fine-tuning. Moreover, IF-Guide does not rely on human-preference data, which is typically required by existing alignment methods. In evaluation, we demonstrate that IF-Guide substantially reduces both explicit and implicit toxicity$-$by up to 10$\times$ compared to uncensored models, and up to 3$\times$ compared to baseline alignment methods, e.g., DPO and RAD$-$across both pre-training and fine-tuning scenarios. IF-Guide is computationally efficient: a billion-parameter model is $not$ $necessary$ for computing influence scores; a million-parameter model$-$with 7.5$\times$ fewer parameters$-$can effectively serve as a proxy for identifying harmful data.

[Arxiv](https://arxiv.org/abs/2506.01790)