# 从 CLIP 中提取自由的密集不对齐情况

发布时间：2024年12月24日

`LLM应用` `计算机视觉`

> Extract Free Dense Misalignment from CLIP

# 摘要

> 近期的视觉语言基础模型常常输出与输入不匹配的结果，比如字幕中的对象幻觉以及文本到图像生成模型中的提示不匹配。近期研究探索了识别不匹配元素的方法，旨在既提高可解释性，又提升模型性能。然而，当下的方法主要以零样本形式依赖大型基础模型，或者依靠有人工标注的微调模型，因巨大的计算成本而限制了可扩展性。此项工作提出了一种名为 CLIP4DM 的新方法，用于从预训练的 CLIP 中检测密集的不匹配情况，尤其专注于找出图像与文本之间不匹配的单词。我们精心改进了基于梯度的归因计算方法，使单个文本标记的负梯度能够指示不匹配。我们还提出了 F-CLIPScore，它用全局对齐分数来聚合不匹配的归因。我们在各类密集不匹配检测基准上评估了我们的方法，涵盖了各种图像和文本领域以及不匹配类型。我们的方法在零样本模型中展现出了顶尖性能，与微调模型相比也具备竞争力，同时保持了出色的效率。我们的定性示例显示，我们的方法在检测实体级对象、无形对象和属性方面具有独特优势，而这些对于现有工作而言难以检测。我们进行了消融研究和分析，以凸显我们方法的优点和局限性。我们的代码在 https://github.com/naver-ai/CLIP4DM 上公开可用。

> Recent vision-language foundation models still frequently produce outputs misaligned with their inputs, evidenced by object hallucination in captioning and prompt misalignment in the text-to-image generation model. Recent studies have explored methods for identifying misaligned elements, aiming not only to enhance interpretability but also to improve model performance. However, current approaches primarily rely on large foundation models in a zero-shot manner or fine-tuned models with human annotations, which limits scalability due to significant computational costs. This work proposes a novel approach, dubbed CLIP4DM, for detecting dense misalignments from pre-trained CLIP, specifically focusing on pinpointing misaligned words between image and text. We carefully revamp the gradient-based attribution computation method, enabling negative gradient of individual text tokens to indicate misalignment. We also propose F-CLIPScore, which aggregates misaligned attributions with a global alignment score. We evaluate our method on various dense misalignment detection benchmarks, covering various image and text domains and misalignment types. Our method demonstrates state-of-the-art performance among zero-shot models and competitive performance with fine-tuned models while maintaining superior efficiency. Our qualitative examples show that our method has a unique strength to detect entity-level objects, intangible objects, and attributes that can not be easily detected for existing works. We conduct ablation studies and analyses to highlight the strengths and limitations of our approach. Our code is publicly available at https://github.com/naver-ai/CLIP4DM.

[Arxiv](https://arxiv.org/abs/2412.18404)