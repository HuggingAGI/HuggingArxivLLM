# 基于双层扩散策略优化的修辞文本到图像生成

发布时间：2025年05月28日

`LLM应用` `图像生成` `计算机视觉`

> Rhetorical Text-to-Image Generation via Two-layer Diffusion Policy Optimization

# 摘要

> 从修辞语言生成图像仍是文本到图像模型的重大挑战。尽管人类能轻松将修辞内容转化为视觉，但即使是当前最先进的多模态大语言模型（MLLM），也无法准确捕捉其中的隐含意义生成图像。现有模型过分关注对象级别的词嵌入对齐，导致比喻性表达生成的图像趋向于字面视觉，忽略了实际语义。为此，我们提出Rhet2Pix框架，将修辞文本生成图像建模为多步骤策略优化问题，创新性地引入双层马尔可夫决策过程（MDP）扩散模块。在外层，Rhet2Pix逐步细化输入提示，生成更丰富的视觉效果；在内层，通过优化扩散轨迹上的动作对，缓解奖励稀疏问题。实验结果表明，Rhet2Pix显著优于GPT-4o、Grok-3等先进模型，在定性和定量评估中均表现最佳。我们的代码和数据集已公开。

> Generating images from rhetorical languages remains a critical challenge for text-to-image models. Even state-of-the-art (SOTA) multimodal large language models (MLLM) fail to generate images based on the hidden meaning inherent in rhetorical language--despite such content being readily mappable to visual representations by humans. A key limitation is that current models emphasize object-level word embedding alignment, causing metaphorical expressions to steer image generation towards their literal visuals and overlook the intended semantic meaning. To address this, we propose Rhet2Pix, a framework that formulates rhetorical text-to-image generation as a multi-step policy optimization problem, incorporating a two-layer MDP diffusion module. In the outer layer, Rhet2Pix converts the input prompt into incrementally elaborated sub-sentences and executes corresponding image-generation actions, constructing semantically richer visuals. In the inner layer, Rhet2Pix mitigates reward sparsity during image generation by discounting the final reward and optimizing every adjacent action pair along the diffusion denoising trajectory. Extensive experiments demonstrate the effectiveness of Rhet2Pix in rhetorical text-to-image generation. Our model outperforms SOTA MLLMs such as GPT-4o, Grok-3 and leading academic baselines across both qualitative and quantitative evaluations. The code and dataset used in this work are publicly available.

[Arxiv](https://arxiv.org/abs/2505.22792)