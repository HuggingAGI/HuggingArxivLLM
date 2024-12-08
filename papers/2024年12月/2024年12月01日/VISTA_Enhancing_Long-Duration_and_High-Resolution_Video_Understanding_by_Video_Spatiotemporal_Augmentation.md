# VISTA：借由视频时空增强提升长时程和高分辨率视频的理解能力

发布时间：2024年12月01日

`LLM应用` `数据集`

> VISTA: Enhancing Long-Duration and High-Resolution Video Understanding by Video Spatiotemporal Augmentation

# 摘要

> 当前的大型多模态模型（LMMs）在处理和理解长时长、高分辨率视频时遭遇重大挑战，主因是缺乏优质数据集。为从数据为核心的视角攻克此难题，我们推出 VISTA，一个简易且高效的视频时空增强框架，能从现存视频字幕数据集中合成长时长、高分辨率的视频指令跟随对。VISTA 对视频进行时空组合，创造出时长延长、分辨率提升的新合成视频，接着生成与这些新合成视频相关的问答对。基于此模式，我们开发了七种视频增强方法，整理出 VISTA-400K，这是一个旨在提升长时长和高分辨率视频理解能力的视频指令跟随数据集。在我们的数据上对各类视频 LMMs 进行微调，在四个长视频理解的挑战性基准测试中平均提升 3.3％。此外，我们引入首个全面的高分辨率视频理解基准 HRVideoBench，在该基准上我们微调的模型实现 6.5％的性能增益。这些成果彰显了我们框架的有效性。

> Current large multimodal models (LMMs) face significant challenges in processing and comprehending long-duration or high-resolution videos, which is mainly due to the lack of high-quality datasets. To address this issue from a data-centric perspective, we propose VISTA, a simple yet effective Video Spatiotemporal Augmentation framework that synthesizes long-duration and high-resolution video instruction-following pairs from existing video-caption datasets. VISTA spatially and temporally combines videos to create new synthetic videos with extended durations and enhanced resolutions, and subsequently produces question-answer pairs pertaining to these newly synthesized videos. Based on this paradigm, we develop seven video augmentation methods and curate VISTA-400K, a video instruction-following dataset aimed at enhancing long-duration and high-resolution video understanding. Finetuning various video LMMs on our data resulted in an average improvement of 3.3% across four challenging benchmarks for long-video understanding. Furthermore, we introduce the first comprehensive high-resolution video understanding benchmark HRVideoBench, on which our finetuned models achieve a 6.5% performance gain. These results highlight the effectiveness of our framework.

[Arxiv](https://arxiv.org/abs/2412.00927)