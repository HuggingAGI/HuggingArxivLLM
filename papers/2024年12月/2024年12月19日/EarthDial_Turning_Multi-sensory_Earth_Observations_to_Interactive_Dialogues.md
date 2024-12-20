# EarthDial：把多感官地球观测转化为互动式对话

发布时间：2024年12月19日

`LLM应用` `地球观测` `环境监测`

> EarthDial: Turning Multi-sensory Earth Observations to Interactive Dialogues

# 摘要

> 通过交互式视觉语言模型（VLMs）对海量地球观测数据进行自动分析，能够为环境监测、灾害应对和资源管理创造新机遇。现有的通用VLMs在遥感数据方面表现欠佳，而近期的地理空间VLMs仍受限于固定分辨率和少数传感器模式。在本文中，我们推出了EarthDial，这是专为地球观测（EO）数据打造的对话助手，将复杂、多感官的地球观测转化为互动式自然语言对话。EarthDial支持多光谱、多时相和多分辨率影像，可完成众多遥感任务，如分类、检测、字幕生成、问答、视觉推理和视觉基础。为此，我们引入了一个庞大的指令调整数据集，其中包含超过1111万对涵盖RGB、合成孔径雷达（SAR）以及近红外（NIR）和红外等多光谱模式的指令对。另外，EarthDial能够处理双时相和多时相序列分析，适用于变化检测等应用。我们在37个下游应用中的大量实验结果显示，EarthDial优于现有的通用和特定领域模型，在各类EO任务中展现出更出色的泛化能力。

> Automated analysis of vast Earth observation data via interactive Vision-Language Models (VLMs) can unlock new opportunities for environmental monitoring, disaster response, and resource management. Existing generic VLMs do not perform well on Remote Sensing data, while the recent Geo-spatial VLMs remain restricted to a fixed resolution and few sensor modalities. In this paper, we introduce EarthDial, a conversational assistant specifically designed for Earth Observation (EO) data, transforming complex, multi-sensory Earth observations into interactive, natural language dialogues. EarthDial supports multi-spectral, multi-temporal, and multi-resolution imagery, enabling a wide range of remote sensing tasks, including classification, detection, captioning, question answering, visual reasoning, and visual grounding. To achieve this, we introduce an extensive instruction tuning dataset comprising over 11.11M instruction pairs covering RGB, Synthetic Aperture Radar (SAR), and multispectral modalities such as Near-Infrared (NIR) and infrared. Furthermore, EarthDial handles bi-temporal and multi-temporal sequence analysis for applications like change detection. Our extensive experimental results on 37 downstream applications demonstrate that EarthDial outperforms existing generic and domain-specific models, achieving better generalization across various EO tasks.

[Arxiv](https://arxiv.org/abs/2412.15190)