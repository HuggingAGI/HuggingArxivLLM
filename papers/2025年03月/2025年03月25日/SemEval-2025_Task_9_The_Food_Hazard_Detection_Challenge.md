# SemEval-2025 的任务 9：食品风险检测挑战

发布时间：2025年03月25日

`LLM应用` `食品安全` `食品危害预测`

> SemEval-2025 Task 9: The Food Hazard Detection Challenge

# 摘要

> 在这个挑战中，我们探索了基于文本的食品危害预测，涉及长尾分布的类别。任务分为两个子任务：(1) 判断网络文本是否暗示十种食品危害类别中的一种，并识别相关食品类别；(2) 通过为危害和产品分配特定标签，实现更细粒度的分类。我们发现，大型语言模型生成的合成数据对处理长尾分布非常有效。此外，微调后的编码器-only、编码器-解码器和解码器-only系统在两个子任务中均表现出色。在此挑战期间，我们逐步发布了6,644份全新的手动标注食品事件报告，这些数据在CC BY-NC-SA 4.0许可下开放。

> In this challenge, we explored text-based food hazard prediction with long tail distributed classes. The task was divided into two subtasks: (1) predicting whether a web text implies one of ten food-hazard categories and identifying the associated food category, and (2) providing a more fine-grained classification by assigning a specific label to both the hazard and the product. Our findings highlight that large language model-generated synthetic data can be highly effective for oversampling long-tail distributions. Furthermore, we find that fine-tuned encoder-only, encoder-decoder, and decoder-only systems achieve comparable maximum performance across both subtasks. During this challenge, we gradually released (under CC BY-NC-SA 4.0) a novel set of 6,644 manually labeled food-incident reports.

[Arxiv](https://arxiv.org/abs/2503.19800)