# <翻译失败>

发布时间：2025年08月31日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。`

> Prompt the Unseen: Evaluating Visual-Language Alignment Beyond Supervision

# 摘要

> <翻译失败>

> Vision-Language Models (VLMs) combine a vision encoder and a large language model (LLM) through alignment training, showing strong performance on multimodal tasks. A central component in this architecture is the projection layer, which maps visual features into the LLM's embedding space. Despite its importance, its ability to generalize to unseen visual concepts has not been systematically evaluated. To address this, we propose a benchmark for evaluating projection-layer generalization. We adapt object detection datasets (rich in fine-grained annotations) into a prompting format and design train/test splits with disjoint label sets, enabling precise control over seen and unseen concept separation. Experimental results show that the projection layer retains about 79 to 88 percent of the performance on unseen classes compared to seen ones across various settings, suggesting a non-trivial level of generalization even without explicit alignment supervision on those concepts. We further analyze this behavior through a mechanistic interpretability lens. Our findings indicate that the feed-forward network in the projection layer functions like a key-value memory, processing seen and unseen tokens in similar ways. This study introduces a new evaluation framework for alignment generalization and highlights the potential for efficient VLM training with limited aligned data.

[Arxiv](https://arxiv.org/abs/2509.00700)