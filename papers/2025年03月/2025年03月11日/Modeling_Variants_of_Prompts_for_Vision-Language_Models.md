# 视觉语言模型的提示变体建模：探索与实践

发布时间：2025年03月11日

`LLM理论

理由：这篇论文探讨了大型视觉语言模型（VLMs）的鲁棒性问题，特别是对提示模板的敏感性。作者提出了新的基准测试和方法，以提升模型的鲁棒性，属于模型理论和改进的研究范畴。`

> Modeling Variants of Prompts for Vision-Language Models

# 摘要

> 大型预训练视觉语言模型（VLMs）为下游任务的提升提供了一种有前景的方法。然而，以CLIP为代表的VLMs存在显著局限：其性能对提示模板的设计高度敏感。尽管提示学习方法通过将自然语言提示替换为可学习的提示来解决这一敏感性问题，但这些方法难以被人类理解。确保模型在不同提示模板上表现一致，可以使其无缝适应多种表达方式，从而增强处理下游任务的能力，而无需进行繁琐的提示工程。在本研究中，我们提出了RobustPrompt基准，这是一个系统化的基准测试，用于评估VLMs对不同提示模板的鲁棒性。该基准包含一个包含数百个精心设计的提示模板的数据集，分为六种类型，涵盖了广泛使用的模板。除了基准测试，我们还提出了提示变体建模（MVP），这是一种简单而有效的方法，通过建模提示结构的变体来缓解敏感性问题。MVP的创新之处在于将提示分解为模板和类别名称，并利用变分自编码器（VAE）来建模多样化提示结构的分布。在11个数据集上的实验表明，MVP可以在不降低性能的情况下显著提升模型对输入提示变化的鲁棒性。代码可在https://github.com/xiaoyaoxinyi/MVP获取。

> Large pre-trained vision-language models (VLMs) offer a promising approach to leveraging human language for enhancing downstream tasks. However, VLMs such as CLIP face significant limitation: its performance is highly sensitive to prompt template design. Although prompt learning methods can address the sensitivity issue by replacing natural language prompts with learnable ones, they are incomprehensible to humans. Ensuring consistent performance across various prompt templates enables models to adapt seamlessly to diverse phrasings, enhancing their ability to handle downstream tasks without requiring extensive prompt engineering. In this work, we introduce the RobustPrompt Benchmark, a systematic benchmark to evaluate robustness to different prompt templates for VLMs. It includes a dataset with hundreds of carefully designed prompt templates, divided into six types, covering a wide variety of commonly used templates. Beside the benchmark, we propose Modeling Variants of Prompts (MVP), a simple yet effective method that mitigates sensitivity by modeling variants of prompt structures. The innovation of MVP lies in decoupling prompts into templates and class names, and using Variational Autoencoders (VAE) to model the distribution of diverse prompt structures. Experiments across 11 datasets demonstrate that MVP can greatly enhance model robustness to variations in input prompts without a drop in performance. The code is available at https://github.com/xiaoyaoxinyi/MVP.

[Arxiv](https://arxiv.org/abs/2503.08229)