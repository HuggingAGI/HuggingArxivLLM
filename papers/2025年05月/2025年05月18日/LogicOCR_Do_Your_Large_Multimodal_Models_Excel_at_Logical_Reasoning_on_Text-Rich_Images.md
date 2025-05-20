# LogicOCR：你的大型多模态模型在文字丰富的图像上逻辑推理能力如何？

发布时间：2025年05月18日

`LLM应用` `多模态模型` `逻辑推理`

> LogicOCR: Do Your Large Multimodal Models Excel at Logical Reasoning on Text-Rich Images?

# 摘要

> # LogicOCR：评估多模态模型逻辑推理能力的新基准

大型多模态模型（LMMs）在推理和光学字符识别（OCR）方面取得了显著进展。然而，这些模型在处理复杂逻辑推理任务，特别是涉及富含文本的图像时，仍有较大的提升空间。为了解决这一问题，我们推出了LogicOCR——一个全新的基准测试平台。

**LogicOCR的核心特点：**
- **1,100道精心设计的多项选择题**：专为评估LMMs在文本丰富图像上的逻辑推理能力而设计
- **最小化领域知识依赖**：减少对特定知识（如数学）的依赖，专注于推理能力本身
- **高质量数据构建**：从中国国家公务员考试中精选优质文本语料
- **自动化生成流程**：开发了高效自动化工具链，将文本转化为多模态样本

**构建过程：**
1. **图像生成**：通过设计提示模板，引导GPT-Image-1生成多样化背景、交错文图布局和多变字体的图像，确保内容相关性和视觉真实感
2. **质量控制**：人工验证所有生成图像，剔除低质量样本

**评估方法：**
- **评估对象**：涵盖多种主流开源和专有LMMs
- **测试模式**：包括链式思维（CoT）和直接回答两种设置

**研究发现：**
- 测试时间缩放、输入模态差异和视觉-文本方向敏感性对模型表现有显著影响
- 与仅基于文本的输入相比，LMMs在多模态推理任务中仍显不足，表明视觉阅读与推理能力的结合尚不完善

**展望：**
我们期待LogicOCR能成为推动多模态推理研究的重要资源。该数据集已开源，欢迎访问https://github.com/MiliLab/LogicOCR获取更多信息。

> Recent advances in Large Multimodal Models (LMMs) have significantly improved their reasoning and Optical Character Recognition (OCR) capabilities. However, their performance on complex logical reasoning tasks involving text-rich images remains underexplored. To bridge this gap, we introduce LogicOCR, a benchmark comprising 1,100 multiple-choice questions designed to evaluate LMMs' logical reasoning abilities on text-rich images, while minimizing reliance on domain-specific knowledge (e.g., mathematics). We construct LogicOCR by curating a text corpus from the Chinese National Civil Servant Examination and develop a scalable, automated pipeline to convert it into multimodal samples. First, we design prompt templates to steer GPT-Image-1 to generate images with diverse backgrounds, interleaved text-illustration layouts, and varied fonts, ensuring contextual relevance and visual realism. Then, the generated images are manually verified, with low-quality examples discarded. We evaluate a range of representative open-source and proprietary LMMs under both Chain-of-Thought (CoT) and direct-answer settings. Our multi-dimensional analysis reveals key insights, such as the impact of test-time scaling, input modality differences, and sensitivity to visual-text orientation. Notably, LMMs still lag in multimodal reasoning compared to text-only inputs, indicating that they have not fully bridged visual reading with reasoning. We hope LogicOCR will serve as a valuable resource for advancing multimodal reasoning research. The dataset is available at https://github.com/MiliLab/LogicOCR.

[Arxiv](https://arxiv.org/abs/2505.12307)