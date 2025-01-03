# 通过相似度计算提升多模态大型语言模型的复杂推理能力

发布时间：2024年12月12日

`LLM应用

**理由**：该论文主要探讨了多模态大型语言模型（LVLMs）在复杂推理任务中的应用，特别是通过提出一种新的图像标记精简方法来提升模型的推理能力。虽然涉及模型内部机制的研究，但其核心关注点在于如何改进和优化LLM在实际任务中的表现，因此归类为“LLM应用”。` `人工智能`

> Enhancing Multimodal Large Language Models Complex Reason via Similarity Computation

# 摘要

> 多模态大型语言模型（LVLMs）发展迅速，涌现出众多模型。然而，LVLMs的可解释性仍是一个待探索的领域，尤其是在面对链式思维推理等复杂任务时，其内部机制仍如黑箱般难以理解。通过研究图像与文本的交互和信息流，我们发现，在LLaVA1.5等模型中，与文本语义相关的图像标记更易在LLM解码层实现信息汇聚，并获得更高的注意力分数；而无关的图像标记则难以汇聚信息，且注意力分数极低。为此，我们提出了一种新的图像标记精简方法Simignore，通过计算图像与文本嵌入的相似性，忽略无关且不重要的图像标记，从而提升LVLMs的复杂推理能力。大量实验验证了该方法在复杂推理任务中的有效性。论文源代码详见url{https://github.com/FanshuoZeng/Simignore}。

> Multimodal large language models have experienced rapid growth, and numerous different models have emerged. The interpretability of LVLMs remains an under-explored area. Especially when faced with more complex tasks such as chain-of-thought reasoning, its internal mechanisms still resemble a black box that is difficult to decipher. By studying the interaction and information flow between images and text, we noticed that in models such as LLaVA1.5, image tokens that are semantically related to text are more likely to have information flow convergence in the LLM decoding layer, and these image tokens receive higher attention scores. However, those image tokens that are less relevant to the text do not have information flow convergence, and they only get very small attention scores. To efficiently utilize the image information, we propose a new image token reduction method, Simignore, which aims to improve the complex reasoning ability of LVLMs by computing the similarity between image and text embeddings and ignoring image tokens that are irrelevant and unimportant to the text. Through extensive experiments, we demonstrate the effectiveness of our method for complex reasoning tasks. The paper's source code can be accessed from url{https://github.com/FanshuoZeng/Simignore}.

[Arxiv](https://arxiv.org/abs/2412.09817)