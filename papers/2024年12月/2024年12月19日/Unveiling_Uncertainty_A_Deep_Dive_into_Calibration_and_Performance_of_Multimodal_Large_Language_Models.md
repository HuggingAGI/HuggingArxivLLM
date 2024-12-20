# 揭开不确定性的面纱：深度剖析多模态大型语言模型的校准与性能

发布时间：2024年12月19日

`LLM应用` `医疗保健` `自动驾驶`

> Unveiling Uncertainty: A Deep Dive into Calibration and Performance of Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）将视觉和文本数据相结合，用于图像字幕生成、视觉问答等任务。在医疗保健、自动驾驶等领域，进行恰当的不确定性校准至关重要，但也颇具挑战。本文对具有代表性的 MLLMs 展开研究，重点探讨其在多种场景下的校准情况，包括视觉微调前后、基础 LLMs 多模态训练前后。我们发现其性能存在校准偏差，同时这些场景中的校准差异并不显著。我们还指出了文本和图像之间不确定性的差异，以及它们的整合如何影响整体不确定性。为了更深入地理解 MLLMs 的校准偏差及其自我评估不确定性的能力，我们构建了 IDK（我不知道）数据集，这对于评估它们如何处理未知情况意义重大。我们的研究结果表明，MLLMs 倾向于给出答案而非承认不确定性，但通过适当的提示调整，这种自我评估能力会有所提升。最后，为校准 MLLMs 并增强模型可靠性，我们提出了温度缩放、迭代提示优化等技术。我们的成果为在多模态应用中有效且负责地部署改进后的 MLLMs 提供了深刻见解。代码和 IDK 数据集：\href{https://github.com/hfutml/Calibration-MLLM}{https://github.com/hfutml/Calibration-MLLM}。

> Multimodal large language models (MLLMs) combine visual and textual data for tasks such as image captioning and visual question answering. Proper uncertainty calibration is crucial, yet challenging, for reliable use in areas like healthcare and autonomous driving. This paper investigates representative MLLMs, focusing on their calibration across various scenarios, including before and after visual fine-tuning, as well as before and after multimodal training of the base LLMs. We observed miscalibration in their performance, and at the same time, no significant differences in calibration across these scenarios. We also highlight how uncertainty differs between text and images and how their integration affects overall uncertainty. To better understand MLLMs' miscalibration and their ability to self-assess uncertainty, we construct the IDK (I don't know) dataset, which is key to evaluating how they handle unknowns. Our findings reveal that MLLMs tend to give answers rather than admit uncertainty, but this self-assessment improves with proper prompt adjustments. Finally, to calibrate MLLMs and enhance model reliability, we propose techniques such as temperature scaling and iterative prompt optimization. Our results provide insights into improving MLLMs for effective and responsible deployment in multimodal applications. Code and IDK dataset: \href{https://github.com/hfutml/Calibration-MLLM}{https://github.com/hfutml/Calibration-MLLM}.

[Arxiv](https://arxiv.org/abs/2412.14660)