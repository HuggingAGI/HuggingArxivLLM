# BleedOrigin: 基于两阶段检测与追踪的内镜下黏膜下剥离术动态出血源定位系统

发布时间：2025年07月20日

`其他` `计算机视觉`

> BleedOrigin: Dynamic Bleeding Source Localization in Endoscopic Submucosal Dissection via Dual-Stage Detection and Tracking

# 摘要

> 在内镜下黏膜剥离术（ESD）中，术中出血具有显著风险，需要对出血源进行精准的实时定位和持续监测，以实现有效的止血干预。特别地，内镜医师需要反复冲洗以清除血液，仅在数毫秒内识别出血源，这种低效过程延长了手术时间并增加了患者风险。然而，当前的人工智能（AI）方法主要集中在出血区域分割，忽视了在具有频繁视觉遮挡和动态场景变化的ESD环境中，对出血源的准确检测和时间追踪这一关键需求。此外，缺乏专用数据集进一步加剧了这一差距，阻碍了鲁棒AI辅助指导系统的开发。为了解决这些挑战，我们引入了BleedOrigin-Bench，首个全面的ESD出血源数据集，包含来自44项手术的106,222帧中的1,771个专家标注的出血源，以及39,755个伪标签帧。该基准涵盖了8个解剖部位和6种具有挑战性的临床场景。我们还提出了BleedOrigin-Net，一种用于ESD手术中出血源定位的创新两阶段检测-追踪框架，从出血起始检测到持续空间追踪，完整覆盖了整个工作流程。我们将其与广泛使用的对象检测模型（YOLOv11/v12）、多模态大型语言模型以及点追踪方法进行了比较。通过广泛的评估，BleedOrigin-Net展示了最先进的性能，实现了出血起始检测的96.85%帧级准确率（【数学公式】），初始源检测的70.24%像素级准确率（【数学公式】）以及点追踪的96.11%像素级准确率（【数学公式】）。

> Intraoperative bleeding during Endoscopic Submucosal Dissection (ESD) poses significant risks, demanding precise, real-time localization and continuous monitoring of the bleeding source for effective hemostatic intervention. In particular, endoscopists have to repeatedly flush to clear blood, allowing only milliseconds to identify bleeding sources, an inefficient process that prolongs operations and elevates patient risks. However, current Artificial Intelligence (AI) methods primarily focus on bleeding region segmentation, overlooking the critical need for accurate bleeding source detection and temporal tracking in the challenging ESD environment, which is marked by frequent visual obstructions and dynamic scene changes. This gap is widened by the lack of specialized datasets, hindering the development of robust AI-assisted guidance systems. To address these challenges, we introduce BleedOrigin-Bench, the first comprehensive ESD bleeding source dataset, featuring 1,771 expert-annotated bleeding sources across 106,222 frames from 44 procedures, supplemented with 39,755 pseudo-labeled frames. This benchmark covers 8 anatomical sites and 6 challenging clinical scenarios. We also present BleedOrigin-Net, a novel dual-stage detection-tracking framework for the bleeding source localization in ESD procedures, addressing the complete workflow from bleeding onset detection to continuous spatial tracking. We compare with widely-used object detection models (YOLOv11/v12), multimodal large language models, and point tracking methods. Extensive evaluation demonstrates state-of-the-art performance, achieving 96.85% frame-level accuracy ($\pm\leq8$ frames) for bleeding onset detection, 70.24% pixel-level accuracy ($\leq100$ px) for initial source detection, and 96.11% pixel-level accuracy ($\leq100$ px) for point tracking.

[Arxiv](https://arxiv.org/abs/2507.15094)