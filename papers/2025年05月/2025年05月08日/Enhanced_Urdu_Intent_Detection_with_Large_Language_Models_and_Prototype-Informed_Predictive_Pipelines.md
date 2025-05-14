# 结合大型语言模型和基于原型的预测流水线的增强乌尔都语意图识别

发布时间：2025年05月08日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在乌尔都语意图检测任务中的应用。研究者提出了一种新的对比学习方法，并结合预训练的LLMs和基于原型的注意力机制，构建了一个端到端的意图检测流水线。实验结果展示了该方法在实际数据集上的显著性能提升，属于LLM应用的范畴。` `意图检测`

> Enhanced Urdu Intent Detection with Large Language Models and Prototype-Informed Predictive Pipelines

# 摘要

> 尽管针对英语、中文和法语等语言开发了多种意图检测预测器，但作为全球十大语言之一的乌尔都语在这一领域的发展仍显滞后。在知名语言领域，意图检测预测器通常采用少样本学习策略，基于已知类别的训练来预测未知类别。然而，乌尔都语至今尚未发展出基于少样本策略的意图检测预测器，现有传统预测器仅专注于预测模型在训练集中见过的相同类别。为了弥补这一空白，本研究提出了一种独特的对比学习方法，通过利用未标注的乌尔都语数据重新训练预训练语言模型，从而提升LLMs在下游意图检测任务中的表示学习能力。最终，该方法结合预训练LLMs与基于原型的注意力机制，构建了一个全面的端到端LLMPIA意图检测流水线。在该框架下，我们探索了6种不同语言模型和13种相似度计算方法的潜力。实验结果表明，在包含5836个样本的ATIS数据集和包含8519个样本的Web Queries数据集上，LLMPIA分别在4-way 1-shot和4-way 5-shot设置中取得了83.28%和98.25%的F1分数，以及76.23%和84.42%的F1分数。特别地，在Web Queries数据集的同一类别训练和测试集设置下，LLMPIA相较于现有最优预测器，F1分数提升了53.55%，展现了显著优势。

> Multifarious intent detection predictors are developed for different languages, including English, Chinese and French, however, the field remains underdeveloped for Urdu, the 10th most spoken language. In the realm of well-known languages, intent detection predictors utilize the strategy of few-shot learning and prediction of unseen classes based on the model training on seen classes. However, Urdu language lacks few-shot strategy based intent detection predictors and traditional predictors are focused on prediction of the same classes which models have seen in the train set. To empower Urdu language specific intent detection, this introduces a unique contrastive learning approach that leverages unlabeled Urdu data to re-train pre-trained language models. This re-training empowers LLMs representation learning for the downstream intent detection task. Finally, it reaps the combined potential of pre-trained LLMs and the prototype-informed attention mechanism to create a comprehensive end-to-end LLMPIA intent detection pipeline. Under the paradigm of proposed predictive pipeline, it explores the potential of 6 distinct language models and 13 distinct similarity computation methods. The proposed framework is evaluated on 2 public benchmark datasets, namely ATIS encompassing 5836 samples and Web Queries having 8519 samples. Across ATIS dataset under 4-way 1 shot and 4-way 5 shot experimental settings LLMPIA achieved 83.28% and 98.25% F1-Score and on Web Queries dataset produced 76.23% and 84.42% F1-Score, respectively. In an additional case study on the Web Queries dataset under same classes train and test set settings, LLMPIA outperformed state-of-the-art predictor by 53.55% F1-Score.

[Arxiv](https://arxiv.org/abs/2505.07857)