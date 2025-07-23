# 低上下文环境下提升印地语NER性能：基于Transformer模型的检索增强对比研究

发布时间：2025年07月21日

`LLM应用` `资源有限语言`

> Enhancing Hindi NER in Low Context: A Comparative study of Transformer-based models with vs. without Retrieval Augmentation

# 摘要

> 在自然语言处理领域，命名实体识别（NER）是一项重要挑战。本研究提出了一种基于印地语预训练编码器（MuRIL 和 XLM-R）和生成模型（Llama2-7B、Llama2-70B、Llama3-70B 和 GPT3.5-turbo）的NER技术，并通过从外部上下文（如维基百科）检索数据进行增强。实验表明，结合检索增强（RA）的语言模型在大多数情况下优于传统方法。具体而言，MuRIL 和 XLM-R 的宏F1分数分别从0.69和0.495提升至0.70和0.71。微调后的 Llama2-7B 表现显著提升，而未微调的生成模型在数据增强后也表现出色。GPT3.5-turbo 对RA的适应性最佳，而 Llama2-70B 和 Llama3-70B 未能充分利用检索上下文。研究发现，RA对提升NER性能至关重要，尤其是在数据资源有限的情况下。本研究为如何有效结合数据增强和预训练模型以提升NER性能提供了重要见解，特别是在资源有限的语言环境中。

> One major challenge in natural language processing is named entity recognition (NER), which identifies and categorises named entities in textual input. In order to improve NER, this study investigates a Hindi NER technique that makes use of Hindi-specific pretrained encoders (MuRIL and XLM-R) and Generative Models ( Llama-2-7B-chat-hf (Llama2-7B), Llama-2-70B-chat-hf (Llama2-70B), Llama-3-70B-Instruct (Llama3-70B) and GPT3.5-turbo), and augments the data with retrieved data from external relevant contexts, notably from Wikipedia. We have fine-tuned MuRIL, XLM-R and Llama2-7B with and without RA. However, Llama2-70B, lama3-70B and GPT3.5-turbo are utilised for few-shot NER generation. Our investigation shows that the mentioned language models (LMs) with Retrieval Augmentation (RA) outperform baseline methods that don't incorporate RA in most cases. The macro F1 scores for MuRIL and XLM-R are 0.69 and 0.495, respectively, without RA and increase to 0.70 and 0.71, respectively, in the presence of RA. Fine-tuned Llama2-7B outperforms Llama2-7B by a significant margin. On the other hand the generative models which are not fine-tuned also perform better with augmented data. GPT3.5-turbo adopted RA well; however, Llama2-70B and llama3-70B did not adopt RA with our retrieval context. The findings show that RA significantly improves performance, especially for low-context data. This study adds significant knowledge about how best to use data augmentation methods and pretrained models to enhance NER performance, particularly in languages with limited resources.

[Arxiv](https://arxiv.org/abs/2507.16002)