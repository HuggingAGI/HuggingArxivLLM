# FarExStance：针对波斯语的可解释立场检测

发布时间：2024年12月18日

`LLM应用` `波斯语研究`

> FarExStance: Explainable Stance Detection for Farsi

# 摘要

> 我们推出了 FarExStance，这是用于波斯语可解释立场检测的全新数据集。该数据集中的每个实例都涵盖一个主张、一篇文章或社交媒体帖子针对该主张的立场，还有一个能为立场标签提供证据的抽取式解释。我们在新数据集上，于零样本、少样本和参数高效微调的设定中，对微调的多语言 RoBERTa 模型和几个大型语言模型的性能进行了比较。就立场检测而言，最精准的模型是微调后的 RoBERTa 模型、通过参数高效微调的 LLM Aya-23-8B 以及少样本的 Claude-3.5-Sonnet。在解释的质量方面，我们的自动评估指标显示，少样本的 GPT-4o 生成的解释最为连贯，而我们的人工评估表明，最佳的总体解释得分（OES）归属于少样本的 Claude-3.5-Sonnet。微调的 Aya-32-8B 模型所生成的解释与参考解释最为契合。

> We introduce FarExStance, a new dataset for explainable stance detection in Farsi. Each instance in this dataset contains a claim, the stance of an article or social media post towards that claim, and an extractive explanation which provides evidence for the stance label. We compare the performance of a fine-tuned multilingual RoBERTa model to several large language models in zero-shot, few-shot, and parameter-efficient fine-tuned settings on our new dataset. On stance detection, the most accurate models are the fine-tuned RoBERTa model, the LLM Aya-23-8B which has been fine-tuned using parameter-efficient fine-tuning, and few-shot Claude-3.5-Sonnet. Regarding the quality of the explanations, our automatic evaluation metrics indicate that few-shot GPT-4o generates the most coherent explanations, while our human evaluation reveals that the best Overall Explanation Score (OES) belongs to few-shot Claude-3.5-Sonnet. The fine-tuned Aya-32-8B model produced explanations most closely aligned with the reference explanations.

[Arxiv](https://arxiv.org/abs/2412.14008)