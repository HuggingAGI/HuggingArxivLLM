# 构建高质量的数据集并进行可靠的评估，助力交错图像文本生成任务

发布时间：2025年06月11日

`其他` `人工智能` `多模态系统`

> A High-Quality Dataset and Reliable Evaluation for Interleaved Image-Text Generation

# 摘要

> 大型多模态模型（LMMs）的最新进展显著提升了多模态理解和生成能力。然而，这些模型在生成紧密交织的图像-文本输出方面仍面临挑战，这主要归因于当前训练数据集在规模、质量和指令丰富性方面的局限。为解决这一问题，我们引入了InterSyn——一个通过自研的自我评估与迭代优化（SEIR）方法构建的大型多模态数据集。InterSyn以其多轮、指令驱动的对话和紧密交织的图像-文本响应为特色，同时提供丰富的对象多样性以及严格的自动化质量优化，使其成为训练下一代遵循指令的LMMs的理想选择。此外，为应对缺乏可靠评估工具来评估交织式多模态输出的现状，我们推出了SynJudge——一个自动评估模型，旨在从文本内容、图像内容、图像质量及图像-文本协同作用四个维度对多模态输出进行定量评估。实验结果表明，SEIR方法相较于无优化的同类流程，显著提升了数据集质量。此外，基于InterSyn训练的LMMs在所有评估指标上均实现了性能提升，证实了InterSyn在推动多模态系统发展方面的实用价值。


> Recent advancements in Large Multimodal Models (LMMs) have significantly improved multimodal understanding and generation. However, these models still struggle to generate tightly interleaved image-text outputs, primarily due to the limited scale, quality and instructional richness of current training datasets. To address this, we introduce InterSyn, a large-scale multimodal dataset constructed using our Self-Evaluation with Iterative Refinement (SEIR) method. InterSyn features multi-turn, instruction-driven dialogues with tightly interleaved imagetext responses, providing rich object diversity and rigorous automated quality refinement, making it well-suited for training next-generation instruction-following LMMs. Furthermore, to address the lack of reliable evaluation tools capable of assessing interleaved multimodal outputs, we introduce SynJudge, an automatic evaluation model designed to quantitatively assess multimodal outputs along four dimensions: text content, image content, image quality, and image-text synergy.
  Experimental studies show that the SEIR method leads to substantially higher dataset quality compared to an otherwise identical process without refinement.
  Moreover, LMMs trained on InterSyn achieve uniform performance gains across all evaluation metrics, confirming InterSyn's utility for advancing multimodal systems.

[Arxiv](https://arxiv.org/abs/2506.09427)