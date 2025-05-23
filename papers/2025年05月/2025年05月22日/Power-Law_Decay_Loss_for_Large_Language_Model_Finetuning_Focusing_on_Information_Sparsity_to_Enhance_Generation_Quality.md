# 幂律衰减损失助力大型语言模型微调：针对信息稀疏性提升生成质量

发布时间：2025年05月22日

`LLM理论` `信息处理`

> Power-Law Decay Loss for Large Language Model Finetuning: Focusing on Information Sparsity to Enhance Generation Quality

# 摘要

> 在文本生成任务的微调过程中，标准交叉熵损失对所有token一视同仁，这可能使模型过度关注高频低信息的token，忽视了对生成内容的特异性和信息量至关重要的低频token。本文提出了一种名为幂律衰减损失（PDL）的新颖损失函数，旨在优化文本生成任务的微调过程。PDL的设计灵感源自信息论和语言学的观察：token的信息量通常与其出现频率呈反比。PDL通过训练语料库中token的频率，采用幂律衰减的方式重新调整标准交叉熵损失中每个token的权重。具体而言，高频token的权重被降低，而低频且信息丰富的token则被赋予更高的权重。这种机制引导模型在微调过程中更加关注学习和生成那些传递特定和独特信息的token，从而显著提升生成文本的质量、多样性和信息量。本文从理论上详细阐述了PDL的设计动机和构建方法，并探讨了其在摘要生成、对话系统和风格迁移等文本生成微调任务中的潜在应用和优势。

> During the finetuning stage of text generation tasks, standard cross-entropy loss treats all tokens equally. This can lead models to overemphasize high-frequency, low-information tokens, neglecting lower-frequency tokens crucial for specificity and informativeness in generated content. This paper introduces a novel loss function, Power-Law Decay Loss (PDL), specifically designed to optimize the finetuning process for text generation. The core motivation for PDL stems from observations in information theory and linguistics: the informativeness of a token is often inversely proportional to its frequency of occurrence. PDL re-weights the contribution of each token in the standard cross-entropy loss based on its frequency in the training corpus, following a power-law decay. Specifically, the weights for high-frequency tokens are reduced, while low-frequency, information-dense tokens are assigned higher weights. This mechanism guides the model during finetuning to focus more on learning and generating tokens that convey specific and unique information, thereby enhancing the quality, diversity, and informativeness of the generated text. We theoretically elaborate on the motivation and construction of PDL and discuss its potential applications and advantages across various text generation finetuning tasks, such as abstractive summarization, dialogue systems, and style transfer.

[Arxiv](https://arxiv.org/abs/2505.16900)