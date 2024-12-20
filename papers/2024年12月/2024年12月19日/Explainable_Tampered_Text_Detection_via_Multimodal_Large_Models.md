# 借助多模态大模型实现可解释的篡改文本检测

发布时间：2024年12月19日

`LLM应用` `信息安全` `文本检测`

> Explainable Tampered Text Detection via Multimodal Large Models

# 摘要

> 近来，篡改文本检测因其在信息安全中的重要作用而备受关注。尽管现有方法能检测出篡改的文本区域，但其检测的解释尚不清晰，导致预测不可靠。为解决这一黑箱问题，我们提议借助大型多模态模型，用自然语言阐释篡改文本检测的依据。为填补此项任务的数据空缺，我们提出了一个大规模、综合性的数据集 ETTD，其中包含指示篡改文本区域的像素级标注以及描述篡改文本异常的自然语言标注。运用了多种方法来提升所提数据的质量。比如，提出了一种融合掩码提示，以减少查询 GPT4o 生成异常描述时的混淆。通过用掩码标注对输入图像加权，能够清晰地指明篡改区域，同时保留篡改区域及其周边的内容。我们还提议让 GPT4o 识别篡改文本，并过滤掉 OCR 准确率低的响应，这能有效自动提高标注质量。为进一步优化可解释的篡改文本检测，我们提出了一个简单却有效的模型 TTD，其通过关注带有辅助参考接地查询的可疑区域，实现了更精细的感知。在 ETTD 数据集和公共数据集上的大量实验均证实了所提方法的有效性。同时还提供了深入分析，以启发进一步的研究。数据集和代码将会公开。

> Recently, tampered text detection has attracted increasing attention due to its essential role in information security. Although existing methods can detect the tampered text region, the interpretation of such detection remains unclear, making the prediction unreliable. To address this black-box problem, we propose to explain the basis of tampered text detection with natural language via large multimodal models. To fill the data gap for this task, we propose a large-scale, comprehensive dataset, ETTD, which contains both pixel-level annotations indicating the tampered text region and natural language annotations describing the anomaly of the tampered text. Multiple methods are employed to improve the quality of the proposed data. For example, a fused mask prompt is proposed to reduce confusion when querying GPT4o to generate anomaly descriptions. By weighting the input image with the mask annotation, the tampered region can be clearly indicated and the content in and around the tampered region can also be preserved. We also propose prompting GPT4o to recognize tampered texts and filtering out the responses with low OCR accuracy, which can effectively improve annotation quality in an automatic manner. To further improve explainable tampered text detection, we propose a simple yet effective model called TTD, which benefits from improved fine-grained perception by paying attention to the suspected region with auxiliary reference grounding query. Extensive experiments on both the ETTD dataset and the public dataset have verified the effectiveness of the proposed methods. In-depth analysis is also provided to inspire further research. The dataset and code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2412.14816)