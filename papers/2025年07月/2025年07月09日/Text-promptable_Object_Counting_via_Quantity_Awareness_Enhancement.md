# # 支持文本提示的目标计数：通过增强数量感知能力实现

发布时间：2025年07月09日

`LLM应用` `计算机视觉` `目标计数`

> Text-promptable Object Counting via Quantity Awareness Enhancement

# 摘要

> 大型视觉语言模型（VLMs）的最新进展显著推动了可文本提示的目标计数问题的解决。现有方法通常通过在图像中添加目标类别信息来指定文本提示，但这种方法难以训练模型在计数任务中准确区分目标数量。为解决这一问题，我们提出了QUANet，通过引入新型基于数量的文本提示，并结合视觉-文本数量对齐损失，显著增强了模型的数量感知能力。此外，我们设计了一种创新的双流自适应计数解码器，包含Transformer流、CNN流以及多个Transformer-to-CNN增强适配器（T2C适配器），用于密度图预测。这些T2C适配器有效促进了Transformer流和CNN流之间的知识交流与聚合。最终，我们提出了一种跨流数量排序损失，进一步优化了两个流的预测排序。在FSC-147、CARPK、PUCPR+和上海科技等标准基准上的大量实验证明了我们模型在零样本类别无关计数任务中强大的泛化能力。代码可在GitHub仓库https://github.com/viscom-tongji/QUANet获取。

> Recent advances in large vision-language models (VLMs) have shown remarkable progress in solving the text-promptable object counting problem. Representative methods typically specify text prompts with object category information in images. This however is insufficient for training the model to accurately distinguish the number of objects in the counting task. To this end, we propose QUANet, which introduces novel quantity-oriented text prompts with a vision-text quantity alignment loss to enhance the model's quantity awareness. Moreover, we propose a dual-stream adaptive counting decoder consisting of a Transformer stream, a CNN stream, and a number of Transformer-to-CNN enhancement adapters (T2C-adapters) for density map prediction. The T2C-adapters facilitate the effective knowledge communication and aggregation between the Transformer and CNN streams. A cross-stream quantity ranking loss is proposed in the end to optimize the ranking orders of predictions from the two streams. Extensive experiments on standard benchmarks such as FSC-147, CARPK, PUCPR+, and ShanghaiTech demonstrate our model's strong generalizability for zero-shot class-agnostic counting. Code is available at https://github.com/viscom-tongji/QUANet

[Arxiv](https://arxiv.org/abs/2507.06679)