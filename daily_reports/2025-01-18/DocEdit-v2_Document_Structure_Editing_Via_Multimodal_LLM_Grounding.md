# DocEdit-v2: 基于多模态LLM的文档结构编辑
发布时间：2024年10月21日


> DocEdit-v2: Document Structure Editing Via Multimodal LLM Grounding
>
> # 摘要
文档结构编辑是指根据用户需求，对文档图像中的文本、视觉和布局组件进行局部操作。以往研究表明，如何在文档图像中准确定位用户需求并识别相关结构组件及其属性，仍是该任务的主要挑战。为此，我们提出了DocEdit-v2，一个基于大型多模态模型（LMMs）的端到端文档编辑框架。该框架包含三大创新模块：（1）Doc2Command，能够同时定位编辑区域（RoI）并将用户编辑请求转化为明确的编辑命令；（2）基于LLM的命令重构提示，将原本为专业软件设计的编辑命令转化为适合通用LMMs的编辑指令；（3）此外，DocEdit-v2通过GPT-4V和Gemini等大型多模态模型处理输出，解析文档布局，在定位的RoI上执行编辑，并生成编辑后的文档图像。在DocEdit数据集上的大量实验表明，DocEdit-v2在编辑命令生成（2-33%）、RoI边界框检测（12-31%）和整体文档编辑（1-12%）任务上均显著优于现有基线。
>
> https://arxiv.org/abs/2410.16472

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.16472](https://arxiv.org/abs/2410.16472)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)