# 可控图像编辑的贝叶斯优化方法，借助大型语言模型实现

发布时间：2025年02月25日

`LLM应用

理由：这篇论文主要探讨了将大型语言模型（LLMs）应用于图像生成和编辑任务，提出了BayesGenie这一结合LLMs和贝叶斯优化的方法，属于LLM的具体应用，因此归类为LLM应用。` `图像生成` `图像编辑`

> Bayesian Optimization for Controlled Image Editing via LLMs

# 摘要

> 在快速发展的图像生成领域，实现对生成内容的精准控制并保持语义一致性仍然是主要的挑战，特别是在 grounding 技术和模型微调需求方面。为了解决这些难题，我们提出了 BayesGenie，一种结合大型语言模型 (LLMs) 和贝叶斯优化的开箱即用方法，旨在实现精确且用户友好的图像编辑。通过自然语言描述，用户可以轻松修改图像，无需手动标记区域，同时保持原始图像的语义完整性。与现有需要大量预训练或微调的技术不同，我们的方法通过其模型不可知的设计，在各种 LLMs 上展现出极强的适应性。BayesGenie 采用了一种适应性贝叶斯优化策略，自动调整推理过程的参数，从而实现高精度的图像编辑，同时最大限度地减少用户干预。通过在多种场景下的广泛实验，我们证明了我们的框架在编辑准确性和语义保存方面显著优于现有方法。这一结论通过使用不同的 LLMs（包括 Claude3 和 GPT-4）得到了验证。

> In the rapidly evolving field of image generation, achieving precise control over generated content and maintaining semantic consistency remain significant limitations, particularly concerning grounding techniques and the necessity for model fine-tuning. To address these challenges, we propose BayesGenie, an off-the-shelf approach that integrates Large Language Models (LLMs) with Bayesian Optimization to facilitate precise and user-friendly image editing. Our method enables users to modify images through natural language descriptions without manual area marking, while preserving the original image's semantic integrity. Unlike existing techniques that require extensive pre-training or fine-tuning, our approach demonstrates remarkable adaptability across various LLMs through its model-agnostic design. BayesGenie employs an adapted Bayesian optimization strategy to automatically refine the inference process parameters, achieving high-precision image editing with minimal user intervention. Through extensive experiments across diverse scenarios, we demonstrate that our framework significantly outperforms existing methods in both editing accuracy and semantic preservation, as validated using different LLMs including Claude3 and GPT-4.

[Arxiv](https://arxiv.org/abs/2502.18116)