# DocEdit-v2: 基于多模态LLM的文档结构编辑

发布时间：2024年10月21日

`LLM应用

**理由**：这篇论文主要介绍了DocEdit-v2，一个基于大型多模态模型（LMMs）的端到端文档编辑框架。该框架利用GPT-4V和Gemini等大型多模态模型来处理文档编辑任务，涉及文本、视觉和布局组件的操作。虽然论文中提到了LLM（大型语言模型）的应用，但核心内容集中在如何利用这些模型来解决文档编辑问题，因此归类为“LLM应用”更为合适。` `文档处理` `图像编辑`

> DocEdit-v2: Document Structure Editing Via Multimodal LLM Grounding

# 摘要

> # 摘要
文档结构编辑是指根据用户需求，对文档图像中的文本、视觉和布局组件进行局部操作。以往研究表明，如何在文档图像中准确定位用户需求并识别相关结构组件及其属性，仍是该任务的主要挑战。为此，我们提出了DocEdit-v2，一个基于大型多模态模型（LMMs）的端到端文档编辑框架。该框架包含三大创新模块：（1）Doc2Command，能够同时定位编辑区域（RoI）并将用户编辑请求转化为明确的编辑命令；（2）基于LLM的命令重构提示，将原本为专业软件设计的编辑命令转化为适合通用LMMs的编辑指令；（3）此外，DocEdit-v2通过GPT-4V和Gemini等大型多模态模型处理输出，解析文档布局，在定位的RoI上执行编辑，并生成编辑后的文档图像。在DocEdit数据集上的大量实验表明，DocEdit-v2在编辑命令生成（2-33%）、RoI边界框检测（12-31%）和整体文档编辑（1-12%）任务上均显著优于现有基线。

> Document structure editing involves manipulating localized textual, visual, and layout components in document images based on the user's requests. Past works have shown that multimodal grounding of user requests in the document image and identifying the accurate structural components and their associated attributes remain key challenges for this task. To address these, we introduce the DocEdit-v2, a novel framework that performs end-to-end document editing by leveraging Large Multimodal Models (LMMs). It consists of three novel components: (1) Doc2Command, which simultaneously localizes edit regions of interest (RoI) and disambiguates user edit requests into edit commands; (2) LLM-based Command Reformulation prompting to tailor edit commands originally intended for specialized software into edit instructions suitable for generalist LMMs. (3) Moreover, DocEdit-v2 processes these outputs via Large Multimodal Models like GPT-4V and Gemini, to parse the document layout, execute edits on grounded Region of Interest (RoI), and generate the edited document image. Extensive experiments on the DocEdit dataset show that DocEdit-v2 significantly outperforms strong baselines on edit command generation (2-33%), RoI bounding box detection (12-31%), and overall document editing (1-12\%) tasks.

[Arxiv](https://arxiv.org/abs/2410.16472)