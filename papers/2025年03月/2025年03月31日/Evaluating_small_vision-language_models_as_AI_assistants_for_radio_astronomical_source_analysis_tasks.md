# 评估小型视觉-语言模型在射电天文源分析任务中的AI助手作用

发布时间：2025年03月31日

`LLM应用` `天文学`

> Evaluating small vision-language models as AI assistants for radio astronomical source analysis tasks

# 摘要

> 下一代射电望远镜即将彻底改变射电天文学，其产生的海量数据对传统处理方法提出了巨大挑战。深度学习技术在射电分析任务自动化方面潜力巨大，但受限于大型标注数据集的匮乏。近期自监督学习的进展催生了基础射电视觉模型，但适应新任务通常需要编程专业知识，限制了其在天文学界的广泛应用。基于文本的AI界面通过支持特定任务查询和示例驱动学习，提供了一个有前途的替代方案。在此背景下，大型语言模型（LLMs）凭借其卓越的零样本学习能力，在科学领域得到了越来越多的应用。然而，部署大规模模型需要大量资源，天文学分析中对能够处理视觉和文本数据的AI系统需求日益增长。

本研究探索了小型规模的视觉-语言模型（VLMs）作为射电天文学的AI助手，结合了LLM的能力与视觉变压器。我们对LLaVA VLM进行了微调，使用了来自多个调查的59,000张射电图像的数据集，并通过文献中添加了38,000个图像-标题对。微调后的模型在射电特定任务上明显优于基础模型，在扩展源检测方面实现了约30%的F1分数提升，但在通用多模态任务上表现不佳，比纯视觉模型低约20%。加入标题数据和LoRA微调增强了模型的指令遵循能力，并在标准基准测试中帮助恢复了约10%的准确率。

这项工作为未来射电VLM的发展奠定了基础，突显了它们的潜力和局限性，例如需要更好的多模态对齐、更高质量的数据集以及缓解灾难性遗忘的需求。

> The advent of next-generation radio telescopes is set to transform radio astronomy by producing massive data volumes that challenge traditional processing methods. Deep learning techniques have shown strong potential in automating radio analysis tasks, yet are often constrained by the limited availability of large annotated datasets. Recent progress in self-supervised learning has led to foundational radio vision models, but adapting them for new tasks typically requires coding expertise, limiting their accessibility to a broader astronomical community. Text-based AI interfaces offer a promising alternative by enabling task-specific queries and example-driven learning. In this context, Large Language Models (LLMs), with their remarkable zero-shot capabilities, are increasingly used in scientific domains. However, deploying large-scale models remains resource-intensive, and there is a growing demand for AI systems that can reason over both visual and textual data in astronomical analysis. This study explores small-scale Vision-Language Models (VLMs) as AI assistants for radio astronomy, combining LLM capabilities with vision transformers. We fine-tuned the LLaVA VLM on a dataset of 59k radio images from multiple surveys, enriched with 38k image-caption pairs from the literature. The fine-tuned models show clear improvements over base models in radio-specific tasks, achieving ~30% F1-score gains in extended source detection, but they underperform pure vision models and exhibit ~20% drop on general multimodal tasks. Inclusion of caption data and LoRA fine-tuning enhances instruction-following and helps recover ~10% accuracy on standard benchmarks. This work lays the foundation for future advancements in radio VLMs, highlighting their potential and limitations, such as the need for better multimodal alignment, higher-quality datasets, and mitigation of catastrophic forgetting.

[Arxiv](https://arxiv.org/abs/2503.23859)