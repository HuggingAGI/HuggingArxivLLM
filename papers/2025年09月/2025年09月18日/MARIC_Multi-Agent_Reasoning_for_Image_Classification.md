# MARIC：面向图像分类的多智能体推理

发布时间：2025年09月18日

`Agent` `基础理论`

> MARIC: Multi-Agent Reasoning for Image Classification

# 摘要

> 传统图像分类通常依赖参数密集型模型训练，需大规模标注数据集与大量微调方可实现优异性能。尽管近年的视觉语言模型（VLMs）缓解了部分限制，但其依赖单遍表示的特性仍使其难以捕捉视觉内容的互补信息。为此，本文提出基于多智能体的图像分类推理框架（MARIC），将图像分类重构为协作推理过程。MARIC首先通过轮廓智能体（Outliner Agent）分析图像全局主题并生成目标提示，随后三个方面智能体（Aspect Agents）基于提示从不同视觉维度提取细粒度描述，最后由推理智能体（Reasoning Agent）通过整合反思步骤合成互补输出，生成统一的分类表示。通过明确将任务分解为多视角分析并促进反思合成，MARIC有效缓解了参数密集型训练与单一VLM推理的固有缺陷。在4个不同图像分类基准数据集上的实验表明，MARIC性能显著优于基线模型，充分证明了多智能体视觉推理在实现鲁棒且可解释的图像分类任务中的有效性。

> Image classification has traditionally relied on parameter-intensive model training, requiring large-scale annotated datasets and extensive fine tuning to achieve competitive performance. While recent vision language models (VLMs) alleviate some of these constraints, they remain limited by their reliance on single pass representations, often failing to capture complementary aspects of visual content. In this paper, we introduce Multi Agent based Reasoning for Image Classification (MARIC), a multi agent framework that reformulates image classification as a collaborative reasoning process. MARIC first utilizes an Outliner Agent to analyze the global theme of the image and generate targeted prompts. Based on these prompts, three Aspect Agents extract fine grained descriptions along distinct visual dimensions. Finally, a Reasoning Agent synthesizes these complementary outputs through integrated reflection step, producing a unified representation for classification. By explicitly decomposing the task into multiple perspectives and encouraging reflective synthesis, MARIC mitigates the shortcomings of both parameter-heavy training and monolithic VLM reasoning. Experiments on 4 diverse image classification benchmark datasets demonstrate that MARIC significantly outperforms baselines, highlighting the effectiveness of multi-agent visual reasoning for robust and interpretable image classification.

[Arxiv](https://arxiv.org/abs/2509.14860)