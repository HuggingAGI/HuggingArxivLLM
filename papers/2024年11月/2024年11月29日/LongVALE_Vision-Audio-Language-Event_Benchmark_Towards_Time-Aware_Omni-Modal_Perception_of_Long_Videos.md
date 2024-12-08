# LongVALE：致力于长视频时间感知全模态感知的视觉-音频-语言-事件基准

发布时间：2024年11月29日

`LLM应用` `多模态`

> LongVALE: Vision-Audio-Language-Event Benchmark Towards Time-Aware Omni-Modal Perception of Long Videos

# 摘要

> 尽管视频理解领域已取得显著进步，但多数工作仍局限于粗粒度或纯视觉的视频任务。然而，现实中的视频涵盖了全模态信息（视觉、音频和语音），一系列事件构成连贯的故事情节。缺乏带有细粒度事件标注的多模态视频数据以及手动标注的高昂成本，是实现全面全模态视频感知的主要阻碍。为弥补这一差距，我们提出了一个自动流程，包含高质量多模态视频筛选、语义连贯的全模态事件边界检测以及跨模态关联感知的事件字幕生成。由此，我们推出了 LongVALE，这是首个视觉 - 音频 - 语言事件理解基准，涵盖 10.5 万个全模态事件，在 8400 个高质量长视频中具备精确的时间边界和详细的关系感知字幕。此外，我们构建了一个基线，首次借助 LongVALE 让视频大型语言模型（LLMs）能够进行全模态细粒度时间视频理解。大量实验表明，LongVALE 在推动全面多模态视频理解方面成效显著，潜力巨大。

> Despite impressive advancements in video understanding, most efforts remain limited to coarse-grained or visual-only video tasks. However, real-world videos encompass omni-modal information (vision, audio, and speech) with a series of events forming a cohesive storyline. The lack of multi-modal video data with fine-grained event annotations and the high cost of manual labeling are major obstacles to comprehensive omni-modality video perception. To address this gap, we propose an automatic pipeline consisting of high-quality multi-modal video filtering, semantically coherent omni-modal event boundary detection, and cross-modal correlation-aware event captioning. In this way, we present LongVALE, the first-ever Vision-Audio-Language Event understanding benchmark comprising 105K omni-modal events with precise temporal boundaries and detailed relation-aware captions within 8.4K high-quality long videos. Further, we build a baseline that leverages LongVALE to enable video large language models (LLMs) for omni-modality fine-grained temporal video understanding for the first time. Extensive experiments demonstrate the effectiveness and great potential of LongVALE in advancing comprehensive multi-modal video understanding.

[Arxiv](https://arxiv.org/abs/2411.19772)