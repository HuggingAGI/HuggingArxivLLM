# 解锁小时级视频训练，提升长视频语言理解能力

发布时间：2025年06月05日

`LLM应用` `问答系统`

> Unleashing Hour-Scale Video Training for Long Video-Language Understanding

# 摘要

> 长格式视频语言理解基准测试推动了视频大型多模态模型（Video-LMMs）的发展。然而，由于高质量长视频标注的稀缺性，对长达数小时的Video-LLMs训练研究仍然不足。为此，我们推出了VideoMarathon，一个大规模的小时级视频指令遵循数据集。该数据集包含来自多个领域的约9,700小时长视频，每段视频时长在3到60分钟之间。具体来说，它包含了330万个高质量问答对，涵盖时间性、空间性、物体、动作、场景和事件六大主题。与现有视频指令数据集相比，VideoMarathon将训练视频时长延长至1小时，并支持22种多样化的任务，这些任务需要同时具备短期和长期的视频理解能力。基于VideoMarathon，我们提出了Hour-LLaVA，一个强大且高效的Video-LMM，用于小时级视频语言建模。该模型通过引入内存增强模块，以1-FPS的采样率实现小时级的视频训练和推理，该模块能自适应地整合用户问题相关和时空信息丰富的语义，来自缓存的完整视频上下文。实验结果显示，Hour-LLaVA在多个长视频语言基准测试中表现最佳，这不仅证明了VideoMarathon数据集的高质量，也凸显了Hour-LLaVA模型的优越性。

> Recent long-form video-language understanding benchmarks have driven progress in video large multimodal models (Video-LMMs). However, the scarcity of well-annotated long videos has left the training of hour-long Video-LLMs underexplored. To close this gap, we present VideoMarathon, a large-scale hour-long video instruction-following dataset. This dataset includes around 9,700 hours of long videos sourced from diverse domains, ranging from 3 to 60 minutes per video. Specifically, it contains 3.3M high-quality QA pairs, spanning six fundamental topics: temporality, spatiality, object, action, scene, and event. Compared to existing video instruction datasets, VideoMarathon significantly extends training video durations up to 1 hour, and supports 22 diverse tasks requiring both short- and long-term video comprehension. Building on VideoMarathon, we propose Hour-LLaVA, a powerful and efficient Video-LMM for hour-scale video-language modeling. It enables hour-long video training and inference at 1-FPS sampling by leveraging a memory augmentation module, which adaptively integrates user question-relevant and spatiotemporal-informative semantics from a cached full video context. In our experiments, Hour-LLaVA achieves the best performance on multiple long video-language benchmarks, demonstrating the high quality of the VideoMarathon dataset and the superiority of the Hour-LLaVA model.

[Arxiv](https://arxiv.org/abs/2506.05332)