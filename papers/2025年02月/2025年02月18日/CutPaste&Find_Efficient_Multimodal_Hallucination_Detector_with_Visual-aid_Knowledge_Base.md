# 剪切粘贴找：基于视觉辅助知识库的高效多模态幻觉检测器

发布时间：2025年02月18日

`LLM应用` `人工智能` `计算机视觉`

> CutPaste&Find: Efficient Multimodal Hallucination Detector with Visual-aid Knowledge Base

# 摘要

> 大型视觉-语言模型（LVLMs）展现了强大的多模态推理能力，但容易在生成描述中虚构不存在的对象或错误属性。现有检测方法虽表现强劲，但因依赖昂贵的API调用和迭代式验证，难以应用于大规模或离线场景。为此，我们提出了CutPaste&Find——一个轻量级、无需训练的框架，用于检测LVLM生成输出中的幻觉。

我们的方法利用现成的视觉和语言模块，高效地进行多步验证，无需LVLM推理。框架核心是一个视觉辅助知识库，编码丰富的实体-属性关系及其图像表示。我们引入缩放因子优化相似度得分，即使对于真实图像-文本对，也能有效缓解对齐值次优的问题。

在POPE和R-Bench等基准数据集上的评估显示，CutPaste&Find不仅幻觉检测性能优异，且比现有方法更高效、更具成本效益。

> Large Vision-Language Models (LVLMs) have demonstrated impressive multimodal reasoning capabilities, but they remain susceptible to hallucination, particularly object hallucination where non-existent objects or incorrect attributes are fabricated in generated descriptions. Existing detection methods achieve strong performance but rely heavily on expensive API calls and iterative LVLM-based validation, making them impractical for large-scale or offline use. To address these limitations, we propose CutPaste\&Find, a lightweight and training-free framework for detecting hallucinations in LVLM-generated outputs. Our approach leverages off-the-shelf visual and linguistic modules to perform multi-step verification efficiently without requiring LVLM inference. At the core of our framework is a Visual-aid Knowledge Base that encodes rich entity-attribute relationships and associated image representations. We introduce a scaling factor to refine similarity scores, mitigating the issue of suboptimal alignment values even for ground-truth image-text pairs. Comprehensive evaluations on benchmark datasets, including POPE and R-Bench, demonstrate that CutPaste\&Find achieves competitive hallucination detection performance while being significantly more efficient and cost-effective than previous methods.

[Arxiv](https://arxiv.org/abs/2502.12591)