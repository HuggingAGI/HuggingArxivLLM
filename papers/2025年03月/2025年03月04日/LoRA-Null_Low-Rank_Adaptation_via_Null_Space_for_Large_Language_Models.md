# LoRA-Null：基于零空间的低秩适配方法用于大型语言模型

发布时间：2025年03月04日

`LLM理论` `人工智能`

> LoRA-Null: Low-Rank Adaptation via Null Space for Large Language Models

# 摘要

> 低秩适配（LoRA）是大型语言模型（LLMs）中领先的参数高效微调方法。然而，这种微调方法会导致模型出现灾难性遗忘，丢失预训练的世界知识。为了解决这一问题，我们受到零空间理论的启发，提出了一种名为LoRA-Null（通过零空间进行低秩适配）的方法。该方法利用预训练知识激活的零空间来初始化适配器。

具体来说，我们随机收集少量数据样本，并捕获它们通过LLM层后的激活状态。接着，我们对输入激活执行奇异值分解以获得其零空间。然后，我们将预训练权重在零空间上的投影作为适配器的初始化值。实验结果表明，这种初始化方法能够在微调过程中有效保留LLMs的原始预训练世界知识。此外，如果我们冻结下投影矩阵的值进行微调，可以实现对预训练世界知识的更好保留。

通过在LLaMA系列（包括LLaMA2、LLaMA3、LLaMA3.1和LLaMA3.2）上的广泛实验，LoRA-Null在代码、数学和指令遵循任务中不仅有效保留了预训练世界知识，还保持了强大的微调性能。我们还提供了LoRA-Null保留预训练知识能力的理论保证。代码已开源，地址为https://github.com/HungerPWAY/LoRA-Null。


> Low-Rank Adaptation (LoRA) is the leading parameter-efficient fine-tuning method for Large Language Models (LLMs). However, the fine-tuned LLMs encounter the issue of catastrophic forgetting of the pre-trained world knowledge. To address this issue, inspired by theoretical insights of null space, we propose LoRA-Null, i.e., Low-Rank Adaptation via null space, which builds adapters initialized from the null space of the pre-trained knowledge activation. Concretely, we randomly collect a few data samples and capture their activations after passing through the LLM layer. We perform Singular Value Decomposition on the input activations to obtain their null space. We use the projection of the pre-trained weights onto the null space as the initialization for adapters. Experimental results demonstrate that this initialization approach can effectively preserve the original pre-trained world knowledge of the LLMs during fine-tuning. Additionally, if we freeze the values of the down-projection matrices during fine-tuning, it achieves even better preservation of the pre-trained world knowledge. LoRA-Null effectively preserves pre-trained world knowledge while maintaining strong fine-tuning performance, as validated by extensive experiments on LLaMA series (LLaMA2, LLaMA3, LLaMA3.1, and LLaMA3.2) across Code, Math, and Instruction Following tasks. We also provide a theoretical guarantee for the capacity of LoRA-Null to retain pre-trained knowledge. Code is in https://github.com/HungerPWAY/LoRA-Null.

[Arxiv](https://arxiv.org/abs/2503.02659)