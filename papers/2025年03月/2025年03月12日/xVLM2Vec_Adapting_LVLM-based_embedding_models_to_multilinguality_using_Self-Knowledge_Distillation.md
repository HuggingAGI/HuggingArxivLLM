# xVLM2Vec：通过自知识蒸馏将基于大视觉-语言模型的嵌入模型适配为多语言模型

发布时间：2025年03月12日

`LLM应用` `多语言` `多模态`

> xVLM2Vec: Adapting LVLM-based embedding models to multilinguality using Self-Knowledge Distillation

# 摘要

> 目前，大多数嵌入模型采用编码器架构的Transformer模型，用于从文本、图像等输入中提取密集且有意义的表示。随着大型语言模型的引入，语言建模领域取得了显著进展，从这些大型且经过广泛训练的模型中提取嵌入的可能性也得到了探索。然而，当前研究主要集中在英文文本嵌入上，这也是这些模型主要的训练语言。此外，能够处理多模态和多语言输入的模型非常少。为此，我们提出了一种针对基于英文数据训练的大型视觉语言模型的适应方法，以提升其在多语言和多模态嵌入提取方面的性能。最后，我们设计并引入了一个基准测试，用于评估多语言和多模态嵌入模型的有效性。

> In the current literature, most embedding models are based on the encoder-only transformer architecture to extract a dense and meaningful representation of the given input, which can be a text, an image, and more. With the recent advances in language modeling thanks to the introduction of Large Language Models, the possibility of extracting embeddings from these large and extensively trained models has been explored. However, current studies focus on textual embeddings in English, which is also the main language on which these models have been trained. Furthermore, there are very few models that consider multimodal and multilingual input. In light of this, we propose an adaptation methodology for Large Vision-Language Models trained on English language data to improve their performance in extracting multilingual and multimodal embeddings. Finally, we design and introduce a benchmark to evaluate the effectiveness of multilingual and multimodal embedding models.

[Arxiv](https://arxiv.org/abs/2503.09313)