# 基于物体的视频问答：结合视觉定位与指代

发布时间：2025年07月25日

`LLM应用` `视频分析` `图像处理`

> Object-centric Video Question Answering with Visual Grounding and Referring

# 摘要

> 视频大型语言模型（VideoLLMs）在通用视频理解领域取得了显著进展。然而，现有模型主要关注高级理解能力，并且仅限于文本形式的输出，这限制了以对象为中心、多轮交互的灵活性。本文做出了三项重要贡献：首先，我们引入了一种新型视频大型语言模型，能够在视频推理任务中同时支持输入对象引用和输出定位，使用户能够通过文本和视觉提示与视频进行交互；其次，我们提出了STOM（时空叠加模块），这是一种创新方法，能够将任意视觉提示从视频中的某一时间戳传播到剩余帧；最后，我们推出了VideoInfer，一个手动整理的对象为中心的视频指令数据集，包含需要推理的问题-答案对。我们在VideoInfer和其他现有基准数据集上进行了全面的视频问答和引用对象分割实验。实验结果表明，在6项任务的12个基准测试中，我们的模型在视频问答和分割方面始终优于基线模型，充分展示了其在多模态、对象为中心的视频和图像理解方面的稳健性。项目页面：https://qirui-chen.github.io/RGA3-release/。

> Video Large Language Models (VideoLLMs) have recently demonstrated remarkable progress in general video understanding. However, existing models primarily focus on high-level comprehension and are limited to text-only responses, restricting the flexibility for object-centric, multiround interactions. In this paper, we make three contributions: (i) we address these limitations by introducing a VideoLLM model, capable of performing both object referring for input and grounding for output in video reasoning tasks, i.e., allowing users to interact with videos using both textual and visual prompts; (ii) we propose STOM (Spatial-Temporal Overlay Module), a novel approach that propagates arbitrary visual prompts input at any single timestamp to the remaining frames within a video; (iii) we present VideoInfer, a manually curated object-centric video instruction dataset featuring questionanswering pairs that require reasoning. We conduct comprehensive experiments on VideoInfer and other existing benchmarks across video question answering and referring object segmentation. The results on 12 benchmarks of 6 tasks show that our proposed model consistently outperforms baselines in both video question answering and segmentation, underscoring its robustness in multimodal, object-centric video and image understanding. Project page: https://qirui-chen.github.io/RGA3-release/.

[Arxiv](https://arxiv.org/abs/2507.19599)