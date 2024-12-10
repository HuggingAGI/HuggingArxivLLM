# “我不懂”：通过[IDK]标记对不确定性进行明确建模

发布时间：2024年12月09日

`LLM应用` `语言模型` `下游任务`

> I Don't Know: Explicit Modeling of Uncertainty with an [IDK] Token

# 摘要

> 大型语言模型以能捕捉现实世界知识而著称，这让它们在众多下游任务中表现卓越。尽管近来有所进步，可这些模型仍易出现所谓的“幻觉”，致使其生成不需要且事实错误的文本。在本研究中，我们提出了一种全新的校准方法来应对这种“幻觉”。我们在模型的词汇表中添加了特殊的[IDK]（“我不知道”）标记，并引入了一个目标函数，将错误预测的概率质量转移到[IDK]标记上。此方法能让模型在输出中明确表达不确定性。我们在多种模型架构和实际的下游任务中对所提方法进行了评估。我们发现，用我们的方法训练的模型能够在之前会出错的地方表达不确定性，且仅损失少量编码知识。我们还对该方法的多种变体进行了广泛的消融研究，并对其精度-召回权衡进行了详细分析。

> Large Language Models are known to capture real-world knowledge, allowing them to excel in many downstream tasks. Despite recent advances, these models are still prone to what are commonly known as hallucinations, causing them to emit unwanted and factually incorrect text. In this work, we propose a novel calibration method that can be used to combat hallucinations. We add a special [IDK] ("I don't know") token to the model's vocabulary and introduce an objective function that shifts probability mass to the [IDK] token for incorrect predictions. This approach allows the model to express uncertainty in its output explicitly. We evaluate our proposed method across multiple model architectures and factual downstream tasks. We find that models trained with our method are able to express uncertainty in places where they would previously make mistakes while suffering only a small loss of encoded knowledge. We further perform extensive ablation studies of multiple variations of our approach and provide a detailed analysis of the precision-recall tradeoff of our method.

[Arxiv](https://arxiv.org/abs/2412.06676)