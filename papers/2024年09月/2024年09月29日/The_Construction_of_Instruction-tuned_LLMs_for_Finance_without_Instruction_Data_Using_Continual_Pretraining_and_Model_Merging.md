# 利用持续预训练和模型合并技术，构建无需指令数据的金融领域指令调优大型语言模型

发布时间：2024年09月29日

`LLM应用

理由：这篇论文主要讨论了一种构建金融领域指令调优大型语言模型（LLMs）的方法，属于将LLM应用于特定领域（金融）的实际应用场景。论文提出的方法通过结合特定领域的持续预训练与模型合并，减少了传统方法所需的资源和计算能力，展示了LLM在实际应用中的创新和优化。因此，将其归类为“LLM应用”是合适的。`

> The Construction of Instruction-tuned LLMs for Finance without Instruction Data Using Continual Pretraining and Model Merging

# 摘要

> 本文提出了一种无需指令数据即可构建金融领域指令调优大型语言模型（LLMs）的创新方法。传统上，开发此类特定领域的LLMs需要大量资源和计算能力，用于持续预训练和指令调优。我们提出了一种更简洁的方法，结合特定领域的持续预训练与模型合并。由于通用预训练LLMs及其指令调优版本通常公开可用，我们可以利用它们获取指令任务向量，并将其与特定领域的预训练向量合并，从而无需额外指令数据即可创建金融领域指令调优LLMs。我们的方法分为两步：首先对金融数据进行持续预训练，然后将指令调优向量与特定领域的预训练向量合并。实验证明，该方法成功构建了金融领域指令调优LLMs。我们方法的一大优势是指令调优和特定领域的预训练向量几乎独立，这使得方法非常高效。我们在本研究中开发的日本金融指令调优LLMs可在https://huggingface.co/pfnet/nekomata-14b-pfn-qfin-inst-merge获取。

> This paper proposes a novel method for constructing instruction-tuned large language models (LLMs) for finance without instruction data. Traditionally, developing such domain-specific LLMs has been resource-intensive, requiring a large dataset and significant computational power for continual pretraining and instruction tuning. Our study proposes a simpler approach that combines domain-specific continual pretraining with model merging. Given that general-purpose pretrained LLMs and their instruction-tuned LLMs are often publicly available, they can be leveraged to obtain the necessary instruction task vector. By merging this with a domain-specific pretrained vector, we can effectively create instruction-tuned LLMs for finance without additional instruction data. Our process involves two steps: first, we perform continual pretraining on financial data; second, we merge the instruction-tuned vector with the domain-specific pretrained vector. Our experiments demonstrate the successful construction of instruction-tuned LLMs for finance. One major advantage of our method is that the instruction-tuned and domain-specific pretrained vectors are nearly independent. This independence makes our approach highly effective. The Japanese financial instruction-tuned LLMs we developed in this study are available at https://huggingface.co/pfnet/nekomata-14b-pfn-qfin-inst-merge.

[Arxiv](https://arxiv.org/abs/2409.19854)