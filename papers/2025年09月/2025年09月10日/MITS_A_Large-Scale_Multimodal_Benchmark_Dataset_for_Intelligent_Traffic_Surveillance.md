# MITS：面向智能交通监控的大规模多模态基准数据集

发布时间：2025年09月10日

`LLM应用` `交通运输`

> MITS: A Large-Scale Multimodal Benchmark Dataset for Intelligent Traffic Surveillance

# 摘要

> 通用领域大型多模态模型（LMMs）虽在图像-文本任务中表现突出，但在智能交通监控（ITS）领域却因缺乏专用数据集而性能受限。为此，我们推出MITS（多模态智能交通监控）——首个专为ITS打造的大规模多模态基准数据集。该数据集包含170,400张真实ITS场景图像（源自交通监控摄像头独立采集），标注了8个主类别及24个子类别的ITS专属目标与事件，覆盖多样环境条件。同时，通过系统化数据生成流程，我们构建了高质量图像描述和500万条指令跟随型视觉问答对，可支撑目标与事件识别、目标计数、目标定位、背景分析及事件推理五项关键ITS任务。为验证MITS的价值，我们在其上微调主流LMMs以开发ITS应用。实验显示，MITS显著提升了模型性能：LLaVA-1.5从0.494升至0.905（+83.2%），LLaVA-1.6从0.678升至0.921（+35.8%），Qwen2-VL从0.584升至0.926（+58.6%），Qwen2.5-VL从0.732升至0.930（+27.0%）。目前，我们已开源该数据集、代码及模型，为推动ITS与LMM研究提供高价值资源。

> General-domain large multimodal models (LMMs) have achieved significant advances in various image-text tasks. However, their performance in the Intelligent Traffic Surveillance (ITS) domain remains limited due to the absence of dedicated multimodal datasets. To address this gap, we introduce MITS (Multimodal Intelligent Traffic Surveillance), the first large-scale multimodal benchmark dataset specifically designed for ITS. MITS includes 170,400 independently collected real-world ITS images sourced from traffic surveillance cameras, annotated with eight main categories and 24 subcategories of ITS-specific objects and events under diverse environmental conditions. Additionally, through a systematic data generation pipeline, we generate high-quality image captions and 5 million instruction-following visual question-answer pairs, addressing five critical ITS tasks: object and event recognition, object counting, object localization, background analysis, and event reasoning. To demonstrate MITS's effectiveness, we fine-tune mainstream LMMs on this dataset, enabling the development of ITS-specific applications. Experimental results show that MITS significantly improves LMM performance in ITS applications, increasing LLaVA-1.5's performance from 0.494 to 0.905 (+83.2%), LLaVA-1.6's from 0.678 to 0.921 (+35.8%), Qwen2-VL's from 0.584 to 0.926 (+58.6%), and Qwen2.5-VL's from 0.732 to 0.930 (+27.0%). We release the dataset, code, and models as open-source, providing high-value resources to advance both ITS and LMM research.

[Arxiv](https://arxiv.org/abs/2509.09730)