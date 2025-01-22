# VARGPT: 视觉自回归多模态大语言模型中的统一理解与生成

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文介绍了VARGPT，一个多模态大型语言模型（MLLM），它结合了视觉理解和生成功能。VARGPT通过自回归框架实现了视觉理解和生成，并在LLaVA架构的基础上进行了扩展。论文详细描述了VARGPT的训练过程和性能表现，特别是在视觉问答和推理任务中的优异表现。这些内容表明VARGPT是一个具体的LLM应用，旨在解决多模态理解和生成问题，因此分类为LLM应用。` `计算机视觉`

> VARGPT: Unified Understanding and Generation in a Visual Autoregressive Multimodal Large Language Model

# 摘要

> 我们推出了VARGPT，这是一款创新的多模态大型语言模型（MLLM），它将视觉理解与生成整合在一个自回归框架中。VARGPT通过下一个标记预测实现视觉理解，并通过下一个尺度预测进行视觉自回归生成。VARGPT在LLaVA架构的基础上进行了创新扩展，不仅实现了MLLMs中的高效尺度自回归视觉生成，还能在一个模型框架内无缝处理混合模态的输入与输出。VARGPT经过三阶段的统一训练，包括预训练和两个混合视觉指令调优阶段，旨在对齐视觉与文本特征，提升理解和生成的指令跟随能力，并优化视觉生成质量。尽管VARGPT基于LLaVA进行多模态理解，但在视觉问答和推理等视觉中心任务中，其表现远超LLaVA-1.5。特别值得一提的是，VARGPT还支持自回归视觉生成和指令到图像合成，展现了其在视觉理解与生成任务中的强大灵活性。项目详情请访问：url{https://vargpt-1.github.io/}

> We present VARGPT, a novel multimodal large language model (MLLM) that unifies visual understanding and generation within a single autoregressive framework. VARGPT employs a next-token prediction paradigm for visual understanding and a next-scale prediction paradigm for visual autoregressive generation. VARGPT innovatively extends the LLaVA architecture, achieving efficient scale-wise autoregressive visual generation within MLLMs while seamlessly accommodating mixed-modal input and output within a single model framework. Our VARGPT undergoes a three-stage unified training process on specially curated datasets, comprising a pre-training phase and two mixed visual instruction-tuning phases. The unified training strategy are designed to achieve alignment between visual and textual features, enhance instruction following for both understanding and generation, and improve visual generation quality, respectively. Despite its LLAVA-based architecture for multimodel understanding, VARGPT significantly outperforms LLaVA-1.5 across various vision-centric benchmarks, such as visual question-answering and reasoning tasks. Notably, VARGPT naturally supports capabilities in autoregressive visual generation and instruction-to-image synthesis, showcasing its versatility in both visual understanding and generation tasks. Project page is at: url{https://vargpt-1.github.io/}

[Arxiv](https://arxiv.org/abs/2501.12327)