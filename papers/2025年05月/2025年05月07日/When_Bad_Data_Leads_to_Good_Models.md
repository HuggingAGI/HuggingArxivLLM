# 坏数据也能造就好模型？化腐朽为神奇的数据奥秘！

发布时间：2025年05月07日

`LLM理论` `人工智能`

> When Bad Data Leads to Good Models

# 摘要

> 在大型语言模型（LLM）预训练中，数据质量通常被视为决定模型质量的关键因素。本文从预训练与后训练协同设计的视角，重新审视“质量”这一概念。具体来说，我们探讨了预训练阶段引入更多有害数据是否能增强后训练阶段的控制能力，从而降低模型输出的有害性。首先，通过一个简单的实验，我们研究了数据组成对表示空间中特征几何结构的影响。随后，使用在不同比例干净数据和有害数据上训练的Olmo-1B模型进行有控制的实验，发现随着有害数据比例的增加，有害性概念在表示空间中呈现出更少纠缠的线性表示。此外，我们发现，尽管有害数据增加了基础模型生成的有害性，但它也使有害性更易于移除。在Toxigen和Real Toxicity Prompts上的评估显示，当应用推理时干预（ITI）等 detoxification 技术时，使用有害数据训练的模型在降低生成有害性的同时，能够更好地保持其一般能力。我们的研究表明，考虑到后训练过程，有害数据可能反而有助于打造更好的模型。

> In large language model (LLM) pretraining, data quality is believed to determine model quality. In this paper, we re-examine the notion of "quality" from the perspective of pre- and post-training co-design. Specifically, we explore the possibility that pre-training on more toxic data can lead to better control in post-training, ultimately decreasing a model's output toxicity. First, we use a toy experiment to study how data composition affects the geometry of features in the representation space. Next, through controlled experiments with Olmo-1B models trained on varying ratios of clean and toxic data, we find that the concept of toxicity enjoys a less entangled linear representation as the proportion of toxic data increases. Furthermore, we show that although toxic data increases the generational toxicity of the base model, it also makes the toxicity easier to remove. Evaluations on Toxigen and Real Toxicity Prompts demonstrate that models trained on toxic data achieve a better trade-off between reducing generational toxicity and preserving general capabilities when detoxifying techniques such as inference-time intervention (ITI) are applied. Our findings suggest that, with post-training taken into account, bad data may lead to good models.

[Arxiv](https://arxiv.org/abs/2505.04741)