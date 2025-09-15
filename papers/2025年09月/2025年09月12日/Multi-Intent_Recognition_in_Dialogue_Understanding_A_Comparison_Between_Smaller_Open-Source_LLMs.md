# # 对话理解中的多意图识别：小型开源LLM的对比研究

发布时间：2025年09月12日

`LLM应用` `基础理论`

> Multi-Intent Recognition in Dialogue Understanding: A Comparison Between Smaller Open-Source LLMs

# 摘要

> 本文针对可在消费级硬件运行的开源公开大型语言模型（LLMs），展开了多标签意图分类的全面分析。我们以对话系统领域的基准数据集MultiWOZ 2.1为实验对象，测试了LLama2-7B-hf、Mistral-7B-v0.1和Yi-6B这三款主流开源预训练LLM的性能表现。实验采用少样本学习模式，在提示词中加入20个示例及相关指令来完成分类任务。我们通过多维度性能指标，系统评估了这些模型在多标签意图分类任务中的表现差异。此外，我们还将基于指令的微调方法与监督学习（以小型Transformer模型BertForSequenceClassification为基线）的效果进行了对比。评估指标包括准确率、精确率、召回率，以及微平均、宏平均和加权F1分数，同时记录了模型的推理时间、显存（VRAM）占用等关键指标。结果显示，Mistral-7B-v0.1在14个意图类别中的11个上F分数均高于另外两款生成式模型，加权平均F分数达0.50；同时，该模型的汉明损失（Hamming Loss）更低、杰卡德相似度（Jaccard Similarity）更高，因此成为少样本场景下的最优模型。研究还发现，基于BERT的监督分类器性能优于表现最佳的少样本生成式LLM。本研究为小型开源LLM在复杂多意图对话检测中的应用提供了参考框架，有助于提升任务导向型聊天机器人的自然语言理解水平。

> In this paper, we provide an extensive analysis of multi-label intent classification using Large Language Models (LLMs) that are open-source, publicly available, and can be run in consumer hardware. We use the MultiWOZ 2.1 dataset, a benchmark in the dialogue system domain, to investigate the efficacy of three popular open-source pre-trained LLMs, namely LLama2-7B-hf, Mistral-7B-v0.1, and Yi-6B. We perform the classification task in a few-shot setup, giving 20 examples in the prompt with some instructions. Our approach focuses on the differences in performance of these models across several performance metrics by methodically assessing these models on multi-label intent classification tasks. Additionally, we compare the performance of the instruction-based fine-tuning approach with supervised learning using the smaller transformer model BertForSequenceClassification as a baseline. To evaluate the performance of the models, we use evaluation metrics like accuracy, precision, and recall as well as micro, macro, and weighted F1 score. We also report the inference time, VRAM requirements, etc. The Mistral-7B-v0.1 outperforms two other generative models on 11 intent classes out of 14 in terms of F-Score, with a weighted average of 0.50. It also has relatively lower Humming Loss and higher Jaccard Similarity, making it the winning model in the few-shot setting. We find BERT based supervised classifier having superior performance compared to the best performing few-shot generative LLM. The study provides a framework for small open-source LLMs in detecting complex multi-intent dialogues, enhancing the Natural Language Understanding aspect of task-oriented chatbots.

[Arxiv](https://arxiv.org/abs/2509.10010)