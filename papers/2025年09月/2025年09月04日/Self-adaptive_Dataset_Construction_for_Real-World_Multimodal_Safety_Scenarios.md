# 面向真实世界多模态安全场景的自适应数据集构建

发布时间：2025年09月04日

`LLM应用` `基础理论`

> Self-adaptive Dataset Construction for Real-World Multimodal Safety Scenarios

# 摘要

> 多模态大型语言模型（MLLMs）发展迅猛，随之而来的是日益复杂的安全挑战。然而，当前以风险为核心的数据集构建方法难以覆盖现实世界多模态安全场景（RMS）不断增加的复杂性；此外，由于缺乏统一的评估指标，其整体有效性尚未得到验证。为此，本文提出了一种面向RMS的新型图像导向自适应数据集构建方法：该方法以图像为起点，最终生成成对的文本及指导性响应。利用该图像导向方法，我们自动构建了包含35k图像-文本对及指导性响应的RMS数据集。同时，我们还提出了一种标准化的安全数据集评估指标——通过微调安全判断模型并在其他安全数据集上评估其性能实现。在多种任务上的大量实验验证了所提图像导向流程的有效性，结果表明该图像导向方法具备良好的可扩展性和实用性，为现实世界多模态安全数据集的构建提供了新思路。

> Multimodal large language models (MLLMs) are rapidly evolving, presenting increasingly complex safety challenges. However, current dataset construction methods, which are risk-oriented, fail to cover the growing complexity of real-world multimodal safety scenarios (RMS). And due to the lack of a unified evaluation metric, their overall effectiveness remains unproven. This paper introduces a novel image-oriented self-adaptive dataset construction method for RMS, which starts with images and end constructing paired text and guidance responses. Using the image-oriented method, we automatically generate an RMS dataset comprising 35k image-text pairs with guidance responses. Additionally, we introduce a standardized safety dataset evaluation metric: fine-tuning a safety judge model and evaluating its capabilities on other safety datasets.Extensive experiments on various tasks demonstrate the effectiveness of the proposed image-oriented pipeline. The results confirm the scalability and effectiveness of the image-oriented approach, offering a new perspective for the construction of real-world multimodal safety datasets.

[Arxiv](https://arxiv.org/abs/2509.04403)