# 驾驶问答：通过驾驶知识考试

发布时间：2025年08月29日

`LLM应用` `交通运输`

> DriveQA: Passing the Driving Knowledge Test

# 摘要

> 要是现在让大型语言模型（LLM）去考驾照理论考试，它能及格吗？除了现有自动驾驶基准测试中的标准空间与视觉问答（QA）任务外，驾照理论考试还需全面掌握所有交通规则、标志和路权规则。要通过考试，人类驾驶员必须能识别现实数据里罕见的各种边缘情况。为此，我们构建了DriveQA——一个开源文本-视觉综合基准测试，系统覆盖了各类交通法规与场景。通过DriveQA实验，我们发现：（1）顶尖的LLM和多模态LLM（MLLM）虽在基础交通规则上表现不俗，但在数值推理、复杂路权场景、交通标志变体及空间布局理解上短板明显；（2）基于DriveQA微调后，多类任务准确率均有提升，尤其在指示标志识别和交叉口决策上效果显著；（3）DriveQA-V的可控变量设计揭示了模型对环境因素（如光照、视角、距离、天气）的敏感程度；（4）在DriveQA上预训练能提升下游驾驶任务表现，在nuScenes、BDD等真实数据集上效果更优；同时还证明，模型可将文本及合成交通知识内化为自身能力，进而在下游QA任务中实现高效泛化。

> If a Large Language Model (LLM) were to take a driving knowledge test today, would it pass? Beyond standard spatial and visual question-answering (QA) tasks on current autonomous driving benchmarks, driving knowledge tests require a complete understanding of all traffic rules, signage, and right-of-way principles. To pass this test, human drivers must discern various edge cases that rarely appear in real-world datasets. In this work, we present DriveQA, an extensive open-source text and vision-based benchmark that exhaustively covers traffic regulations and scenarios. Through our experiments using DriveQA, we show that (1) state-of-the-art LLMs and Multimodal LLMs (MLLMs) perform well on basic traffic rules but exhibit significant weaknesses in numerical reasoning and complex right-of-way scenarios, traffic sign variations, and spatial layouts, (2) fine-tuning on DriveQA improves accuracy across multiple categories, particularly in regulatory sign recognition and intersection decision-making, (3) controlled variations in DriveQA-V provide insights into model sensitivity to environmental factors such as lighting, perspective, distance, and weather conditions, and (4) pretraining on DriveQA enhances downstream driving task performance, leading to improved results on real-world datasets such as nuScenes and BDD, while also demonstrating that models can internalize text and synthetic traffic knowledge to generalize effectively across downstream QA tasks.

[Arxiv](https://arxiv.org/abs/2508.21824)