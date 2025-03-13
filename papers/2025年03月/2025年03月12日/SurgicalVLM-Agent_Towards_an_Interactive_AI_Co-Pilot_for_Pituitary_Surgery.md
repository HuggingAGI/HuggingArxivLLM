# SurgicalVLM-Agent：打造垂体手术的交互式AI协 pilot

发布时间：2025年03月12日

`Agent` `医疗成像`

> SurgicalVLM-Agent: Towards an Interactive AI Co-Pilot for Pituitary Surgery

# 摘要

> 医学图像引导手术需要实时、自适应的决策支持，但传统静态AI模型在结构化任务规划和交互式指导方面表现有限。大型视觉语言模型（VLMs）通过实现动态任务规划和预测性决策支持，为这一领域带来了突破性解决方案。我们推出SurgicalVLM-Agent，一个专注于图像引导垂体手术的AI助手，它具备对话、规划和任务执行三大核心能力。该系统能够实时处理外科医生的查询，并动态规划包括MRI肿瘤分割、内窥镜解剖分割、术前成像与术中视图叠加、器械追踪以及手术视觉问答（VQA）在内的多种任务。为实现高效的任务规划，我们开发了全新的PitAgent数据集，这是一个全面覆盖手术场景的数据集，包含分割、叠加、器械定位、工具追踪、工具-组织交互、阶段识别和手术活动识别等多维度信息。此外，我们创新性地提出FFT-GaLore，一种基于快速傅里叶变换（FFT）的梯度投影技术，用于高效低秩适配，显著优化了LLaMA 3.2模型在手术环境中的微调效果。通过在PitAgent数据集上评估任务规划和提示生成能力，并利用公共垂体数据集进行零样本VQA测试，我们验证了SurgicalVLM-Agent的卓越性能。实验结果表明，该系统在任务规划和查询解释方面达到了当前最高水平，并能生成高度语义化的VQA响应，为AI驱动的手术辅助技术树立了新标杆。

> Image-guided surgery demands adaptive, real-time decision support, yet static AI models struggle with structured task planning and providing interactive guidance. Large vision-language models (VLMs) offer a promising solution by enabling dynamic task planning and predictive decision support. We introduce SurgicalVLM-Agent, an AI co-pilot for image-guided pituitary surgery, capable of conversation, planning, and task execution. The agent dynamically processes surgeon queries and plans the tasks such as MRI tumor segmentation, endoscope anatomy segmentation, overlaying preoperative imaging with intraoperative views, instrument tracking, and surgical visual question answering (VQA). To enable structured task planning, we develop the PitAgent dataset, a surgical context-aware dataset covering segmentation, overlaying, instrument localization, tool tracking, tool-tissue interactions, phase identification, and surgical activity recognition. Additionally, we propose FFT-GaLore, a fast Fourier transform (FFT)-based gradient projection technique for efficient low-rank adaptation, optimizing fine-tuning for LLaMA 3.2 in surgical environments. We validate SurgicalVLM-Agent by assessing task planning and prompt generation on our PitAgent dataset and evaluating zero-shot VQA using a public pituitary dataset. Results demonstrate state-of-the-art performance in task planning and query interpretation, with highly semantically meaningful VQA responses, advancing AI-driven surgical assistance.

[Arxiv](https://arxiv.org/abs/2503.09474)