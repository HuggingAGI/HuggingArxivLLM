# # 先思考，再扩散：LLM引导的物理感知视频生成

发布时间：2025年05月27日

`LLM应用` `视频生成` `物理模拟`

> Think Before You Diffuse: LLMs-Guided Physics-Aware Video Generation

# 摘要

> 视频扩散模型在生成视觉效果上已表现出卓越能力，但在视频中准确呈现物理效果仍具挑战。现实世界中动作、互动和动力学的复杂性使得从数据中学习物理规律变得困难。我们提出了一种名为DiffPhy的通用框架，通过微调预训练视频扩散模型，实现物理正确且照片真实的视频生成。我们的方法利用大型语言模型（LLMs）从文本提示中推理出全面的物理上下文，并将其用于生成指导。为了将物理上下文融入扩散模型，我们采用多模态大语言模型（MLLM）作为监督信号，并引入了一组新的训练目标，确保生成视频的物理正确性和与输入文本的一致性。我们还建立了一个高质量的物理视频数据集，包含多样化的物理动作和事件，以促进有效微调。在公共基准上的广泛实验表明，DiffPhy在各种与物理相关的场景中均能达到顶尖水平。我们的项目页面可访问：https://bwgzk-keke.github.io/DiffPhy/

> Recent video diffusion models have demonstrated their great capability in generating visually-pleasing results, while synthesizing the correct physical effects in generated videos remains challenging. The complexity of real-world motions, interactions, and dynamics introduce great difficulties when learning physics from data. In this work, we propose DiffPhy, a generic framework that enables physically-correct and photo-realistic video generation by fine-tuning a pre-trained video diffusion model. Our method leverages large language models (LLMs) to explicitly reason a comprehensive physical context from the text prompt and use it to guide the generation. To incorporate physical context into the diffusion model, we leverage a Multimodal large language model (MLLM) as a supervisory signal and introduce a set of novel training objectives that jointly enforce physical correctness and semantic consistency with the input text. We also establish a high-quality physical video dataset containing diverse phyiscal actions and events to facilitate effective finetuning. Extensive experiments on public benchmarks demonstrate that DiffPhy is able to produce state-of-the-art results across diverse physics-related scenarios. Our project page is available at https://bwgzk-keke.github.io/DiffPhy/

[Arxiv](https://arxiv.org/abs/2505.21653)