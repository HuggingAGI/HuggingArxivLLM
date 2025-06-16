# VFaith：大型多模态模型是基于已见图像进行推理，还是依赖之前的记忆？

发布时间：2025年06月13日

`LLM应用` `人工智能` `计算机视觉`

> VFaith: Do Large Multimodal Models Really Reason on Seen Images Rather than Previous Memories?

# 摘要

> 近期研究表明，引入长CoT能够显著提升MLLMs解决复杂问题的能力。然而，这种范式为何有效仍是个未解之谜。难以通过量化结果分析模型在推理过程中对视觉线索的特定提取及其所谓的推理，对性能提升的贡献有多大。因此，评估MLLMs推理对视觉信息的忠实度至关重要。为了解决这一问题，我们借助GPT-Image-1，提出了一种基于线索的自动可控编辑管道。它能够根据指令实现特定视觉线索的自动精准编辑。此外，我们引入了VFaith-Bench，这是首个专注于评估MLLMs视觉推理能力，并深入分析其能力来源的基准测试，重点在于视觉忠实度。借助这一设计的管道，我们通过更改对原推理问题至关重要的图像中视觉线索，从而改变问题答案，构建了具有对比性的问答对。通过测试相似问题但图像细节不同的情况，平均准确率反映了模型的视觉推理能力，而测试集图像编辑前后准确率的变化，有效揭示了模型推理能力与视觉感知之间的关系。我们还设计了特定指标来揭示这一关系。VFaith-Bench包含755个条目，分为五个独特子集，并附带一个额外的人工标注感知任务。我们在VFaith-Bench上对现有主流旗舰模型和知名开源模型系列/推理模型进行了深入测试和分析，进一步探究了其推理能力背后的潜在因素。

> Recent extensive works have demonstrated that by introducing long CoT, the capabilities of MLLMs to solve complex problems can be effectively enhanced. However, the reasons for the effectiveness of such paradigms remain unclear. It is challenging to analysis with quantitative results how much the model's specific extraction of visual cues and its subsequent so-called reasoning during inference process contribute to the performance improvements. Therefore, evaluating the faithfulness of MLLMs' reasoning to visual information is crucial. To address this issue, we first present a cue-driven automatic and controllable editing pipeline with the help of GPT-Image-1. It enables the automatic and precise editing of specific visual cues based on the instruction. Furthermore, we introduce VFaith-Bench, the first benchmark to evaluate MLLMs' visual reasoning capabilities and analyze the source of such capabilities with an emphasis on the visual faithfulness. Using the designed pipeline, we constructed comparative question-answer pairs by altering the visual cues in images that are crucial for solving the original reasoning problem, thereby changing the question's answer. By testing similar questions with images that have different details, the average accuracy reflects the model's visual reasoning ability, while the difference in accuracy before and after editing the test set images effectively reveals the relationship between the model's reasoning ability and visual perception. We further designed specific metrics to expose this relationship. VFaith-Bench includes 755 entries divided into five distinct subsets, along with an additional human-labeled perception task. We conducted in-depth testing and analysis of existing mainstream flagship models and prominent open-source model series/reasoning models on VFaith-Bench, further investigating the underlying factors of their reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2506.11571)