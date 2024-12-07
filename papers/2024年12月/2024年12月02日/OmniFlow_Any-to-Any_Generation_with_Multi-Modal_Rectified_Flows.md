# OmniFlow：凭借多模态整流流实现任意到任意的生成

发布时间：2024年12月02日

`LLM应用` `多模态生成` `模型开发`

> OmniFlow: Any-to-Any Generation with Multi-Modal Rectified Flows

# 摘要

> 我们推出了 OmniFlow，这是一款专为任意到任意生成任务（像文本转图像、文本转音频以及音频转图像合成）打造的新型生成模型。OmniFlow 对文本到图像模型所用的整流流（RF）框架加以改进，用于处理多种模态的联合分布。在诸如文本到图像和文本到音频合成等众多任务中，它的表现都超越了以往的任意到任意模型。我们的工作有三大关键贡献：其一，我们把 RF 拓展到多模态场景，并引入了全新的引导机制，让用户能够灵活掌控生成输出中不同模态的对齐情况。其二，我们提出了新颖的架构，拓展了 Stable Diffusion 3 的文本到图像 MMDiT 架构，实现了音频和文本生成。扩展模块能够单独高效地预训练，并与原本的文本到图像 MMDiT 融合进行微调。最后，我们针对大规模音频和文本生成中整流流变压器的设计选择展开了全面研究，为优化不同模态的性能提供了宝贵的见解。代码可在 https://github.com/jacklishufan/OmniFlows 获取。

> We introduce OmniFlow, a novel generative model designed for any-to-any generation tasks such as text-to-image, text-to-audio, and audio-to-image synthesis. OmniFlow advances the rectified flow (RF) framework used in text-to-image models to handle the joint distribution of multiple modalities. It outperforms previous any-to-any models on a wide range of tasks, such as text-to-image and text-to-audio synthesis. Our work offers three key contributions: First, we extend RF to a multi-modal setting and introduce a novel guidance mechanism, enabling users to flexibly control the alignment between different modalities in the generated outputs. Second, we propose a novel architecture that extends the text-to-image MMDiT architecture of Stable Diffusion 3 and enables audio and text generation. The extended modules can be efficiently pretrained individually and merged with the vanilla text-to-image MMDiT for fine-tuning. Lastly, we conduct a comprehensive study on the design choices of rectified flow transformers for large-scale audio and text generation, providing valuable insights into optimizing performance across diverse modalities. The Code will be available at https://github.com/jacklishufan/OmniFlows.

[Arxiv](https://arxiv.org/abs/2412.01169)