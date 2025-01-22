# 循环扩散：大规模参数生成的新方法

发布时间：2025年01月20日

`其他

理由：这篇论文主要讨论的是一种名为RPG的循环扩散方法，用于大规模参数生成。虽然提到了生成神经网络参数，包括LLaMA-7B的LoRA参数，但主要内容集中在参数生成的技术和方法上，而不是直接涉及大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）。因此，将其分类为“其他”更为合适。` `机器学习` `神经网络`

> Recurrent Diffusion for Large-Scale Parameter Generation

# 摘要

> # 摘要
长期以来，参数生成难以扩展，限制了其应用范围。本研究提出了一种名为	extbf{RPG}的循环扩散方法，用于大规模参数生成。我们首先将训练参数划分为不重叠部分，随后提出循环模型学习其关系。循环模型的输出作为条件输入扩散模型，生成神经网络参数。仅用单个GPU，我们便能生成如ConvNeXt-L和LLaMA-7B的LoRA参数等流行模型。在各种架构和任务中，生成的参数表现与训练网络相当。此外，该方法还展示了生成处理未见任务模型的潜力，极大提升了参数生成的实用性。代码可在\href{https://github.com/NUS-HPC-AI-Lab/Recurrent-Parameter-Generation}{这里}获取。

> Parameter generation has struggled to scale up for a long time, significantly limiting its range of applications. In this study, we introduce \textbf{R}ecurrent diffusion for large-scale \textbf{P}arameter \textbf{G}eneration, called \textbf{RPG}. We first divide the trained parameters into non-overlapping parts, after which a recurrent model is proposed to learn their relationships. The recurrent model's outputs, as conditions, are then fed into a diffusion model to generate the neural network parameters. Using only a single GPU, recurrent diffusion enables us to generate popular vision and language models such as ConvNeXt-L and LoRA parameters of LLaMA-7B. Meanwhile, across various architectures and tasks, the generated parameters consistently perform comparable results over trained networks. Notably, our approach also shows the potential to generate models for handling unseen tasks, which largely increases the practicality of parameter generation. Our code is available \href{https://github.com/NUS-HPC-AI-Lab/Recurrent-Parameter-Generation}{here}.

[Arxiv](https://arxiv.org/abs/2501.11587)