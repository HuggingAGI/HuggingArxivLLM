# # 基于大型语言模型的双向动作序列学习实现长期动作预测

发布时间：2025年08月01日

`LLM应用` `自动驾驶` `机器人`

> Bidirectional Action Sequence Learning for Long-term Action Anticipation with Large Language Models

# 摘要

> 基于视频的长期动作预测在自动驾驶和机器人领域的早期风险检测中发挥着关键作用。传统方法通过编码器提取过去动作的特征，并利用解码器预测未来事件，但受限于单向性，其性能表现有限，且难以捕捉场景中语义不同的子动作。而我们提出的BiAnt方法巧妙地结合了前向预测与后向预测，并借助大型语言模型克服了这一限制。实验结果表明，在Ego4D数据集上，与基线方法相比，BiAnt在编辑距离方面取得了更好的性能表现。

> Video-based long-term action anticipation is crucial for early risk detection in areas such as automated driving and robotics. Conventional approaches extract features from past actions using encoders and predict future events with decoders, which limits performance due to their unidirectional nature. These methods struggle to capture semantically distinct sub-actions within a scene. The proposed method, BiAnt, addresses this limitation by combining forward prediction with backward prediction using a large language model. Experimental results on Ego4D demonstrate that BiAnt improves performance in terms of edit distance compared to baseline methods.

[Arxiv](https://arxiv.org/abs/2508.00374)