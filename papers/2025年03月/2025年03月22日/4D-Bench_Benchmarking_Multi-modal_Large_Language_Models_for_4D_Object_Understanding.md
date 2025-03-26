# 4D-Bench：多模态大语言模型在4D物体理解中的基准评测

发布时间：2025年03月22日

`LLM应用` `计算机视觉` `基准测试`

> 4D-Bench: Benchmarking Multi-modal Large Language Models for 4D Object Understanding

# 摘要

> 多模态大型语言模型（MLLMs）在2D图像/视频理解方面表现优异，但目前尚无公开标准来评估其在4D对象（随时间演化的3D对象）理解上的能力。本文推出首个专注于4D对象理解的基准测试——4D-Bench，涵盖4D对象问答（4D QA）与描述生成任务。相比传统2D基准，4D-Bench提供多类别4D对象、高质量标注，并特别考察多视图时空理解能力。

通过对开源与闭源MLLMs的全面评估，我们发现MLLMs在时间理解方面的能力普遍弱于外观理解，尤其在时间理解任务中，开源模型与闭源模型的性能差距更为明显。更令人意外的是，在简单的单对象视频测试中，MLLMs的表现不尽如人意，即使是最先进的GPT-4o也仅达到63%的准确率，远低于人类的91%水平。这些结果凸显了MLLMs在4D对象理解上的显著短板，同时也为未来研究指明了方向。

> Multimodal Large Language Models (MLLMs) have demonstrated impressive 2D image/video understanding capabilities. However, there are no publicly standardized benchmarks to assess the abilities of MLLMs in understanding the 4D objects (3D objects with temporal evolution over time). In this paper, we introduce 4D-Bench, the first benchmark to evaluate the capabilities of MLLMs in 4D object understanding, featuring tasks in 4D object Question Answering (4D object QA) and 4D object captioning. 4D-Bench provides 4D objects with diverse categories, high-quality annotations, and tasks necessitating multi-view spatial-temporal understanding, different from existing 2D image/video-based benchmarks. With 4D-Bench, we evaluate a wide range of open-source and closed-source MLLMs. The results from the 4D object captioning experiment indicate that MLLMs generally exhibit weaker temporal understanding compared to their appearance understanding, notably, while open-source models approach closed-source performance in appearance understanding, they show larger performance gaps in temporal understanding. 4D object QA yields surprising findings: even with simple single-object videos, MLLMs perform poorly, with state-of-the-art GPT-4o achieving only 63\% accuracy compared to the human baseline of 91\%. These findings highlight a substantial gap in 4D object understanding and the need for further advancements in MLLMs.

[Arxiv](https://arxiv.org/abs/2503.17827)