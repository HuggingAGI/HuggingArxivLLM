# 你看见我了吗？：多模态大语言模型视觉感知能力的多维度评估基准

发布时间：2025年05月28日

`LLM应用` `人工智能` `计算机视觉`

> Do You See Me : A Multidimensional Benchmark for Evaluating Visual Perception in Multimodal LLMs

# 摘要

> 多模态大型语言模型 (MLLMs) 虽然在推理方面展现出潜力，但其视觉感知能力却是一个主要瓶颈。令人惊讶的是，MLLMs 即使在误解关键视觉元素的情况下，仍能生成正确答案，从而掩盖了潜在的失败。我们对一个联合感知推理数据集的初步研究发现，对于一个领先的 MLLM，其推理问题的正确答案中仍有 29% 存在视觉感知错误。

为了系统地解决这一问题，我们推出了“Do You See Me”——一个包含 1,758 张图像和 2,612 个问题的可扩展基准测试。它涵盖了 2D 和 3D 中的七个受人类心理学启发的子任务，具有可控的复杂性，能够严格评估 MLLM 的视觉技能。

我们对 3 个领先的闭源模型和 5 个主要开源模型的研究发现了一个显著的差距：人类的准确率达到了 96.49%，而顶级 MLLMs 的平均准确率却低于 50%。随着任务复杂性的增加，这一性能差距迅速扩大（例如，在视觉形态恒常性子任务中，差距从 12% 增加到 45%）。进一步的分析揭示了根本原因：失败源于诸如视觉注意力分配不当以及对精细细节（特别是在或低于编码器补丁分辨率时）的内部表示不稳定等挑战。

这突显了对具有真正 robust 视觉感知能力的 MLLMs 的迫切需求。基准数据集、源代码和评估脚本可在 https://github.com/microsoft/Do-You-See-Me 获取。


> Multimodal Large Language Models (MLLMs) show reasoning promise, yet their visual perception is a critical bottleneck. Strikingly, MLLMs can produce correct answers even while misinterpreting crucial visual elements, masking these underlying failures. Our preliminary study on a joint perception-reasoning dataset revealed that for one leading MLLM, 29% of its correct answers to reasoning questions still exhibited visual perception errors. To systematically address this, we introduce "Do You See Me", a scalable benchmark with 1,758 images and 2,612 questions. It spans seven human-psychology inspired subtasks in 2D and 3D, featuring controllable complexity to rigorously evaluate MLLM visual skills. Our findings on 3 leading closed-source and 5 major open-source models reveal a stark deficit: humans achieve 96.49% accuracy, while top MLLMs average below 50%. This performance gap widens rapidly with increased task complexity (e.g., from 12% to 45% in the visual form constancy subtask). Further analysis into the root causes suggests that failures stem from challenges like misallocated visual attention and the instability of internal representations for fine-grained details, especially at or below encoder patch resolution. This underscores an urgent need for MLLMs with truly robust visual perception. The benchmark dataset, source code and evaluation scripts are available at https://github.com/microsoft/Do-You-See-Me.

[Arxiv](https://arxiv.org/abs/2506.02022)