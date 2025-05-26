# 各向同性在什么情况下能助力 LLM 的下一步词预测适应数值领域？

发布时间：2025年05月22日

`LLM理论` `数值分析` `预测模型`

> When can isotropy help adapt LLMs' next word prediction to numerical domains?

# 摘要

> 近期研究表明，预训练大型语言模型（LLMs）学习到的上下文嵌入向量表示在数值领域的各种下游任务中表现优异。然而，尽管LLMs在数值领域具有显著优势，但其容易出现幻觉的特性可能在能源、自然、金融、医疗、零售和交通等应用中带来严重后果。为了保证数值领域预测的可靠性和准确性，我们需要打开黑箱并通过解释提供性能保障。然而，目前对预训练语言模型何时有助于解决数值下游任务缺乏理论理解。本文旨在通过基于上下文嵌入空间中各向同性概念的新型分析，探讨LLMs的下一个词预测能力如何能够适应数值领域，从而填补这一研究空白。具体而言，我们考虑了一种基于LLMs的对数线性模型，其中数值数据可以通过LLMs输出层的softmax网络（即自注意力中的语言模型头）从其上下文中进行预测。我们证明，为了在数值领域实现最先进的性能，LLMs嵌入的隐藏表示必须具备一种结构，以解释softmax函数的平移不变性。通过构建预训练模型中自注意力的梯度结构，我们展示了LLMs嵌入在上下文嵌入空间中的各向同性特性如何保留表示的潜在结构，从而解决平移不变性问题并提供性能保障。实验表明，数值数据的不同特性和模型架构可能对各向同性产生不同影响。

> Recent studies have shown that vector representations of contextual embeddings learned by pre-trained large language models (LLMs) are effective in various downstream tasks in numerical domains. Despite their significant benefits, the tendency of LLMs to hallucinate in such domains can have severe consequences in applications such as energy, nature, finance, healthcare, retail and transportation, among others. To guarantee prediction reliability and accuracy in numerical domains, it is necessary to open the black-box and provide performance guarantees through explanation. However, there is little theoretical understanding of when pre-trained language models help solve numeric downstream tasks. This paper seeks to bridge this gap by understanding when the next-word prediction capability of LLMs can be adapted to numerical domains through a novel analysis based on the concept of isotropy in the contextual embedding space. Specifically, we consider a log-linear model for LLMs in which numeric data can be predicted from its context through a network with softmax in the output layer of LLMs (i.e., language model head in self-attention). We demonstrate that, in order to achieve state-of-the-art performance in numerical domains, the hidden representations of the LLM embeddings must possess a structure that accounts for the shift-invariance of the softmax function. By formulating a gradient structure of self-attention in pre-trained models, we show how the isotropic property of LLM embeddings in contextual embedding space preserves the underlying structure of representations, thereby resolving the shift-invariance problem and providing a performance guarantee. Experiments show that different characteristics of numeric data and model architecture could have different impacts on isotropy.

[Arxiv](https://arxiv.org/abs/2505.17135)