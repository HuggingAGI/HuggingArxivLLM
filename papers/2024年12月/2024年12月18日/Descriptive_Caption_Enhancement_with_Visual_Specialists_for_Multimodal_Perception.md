# 利用视觉专家增强描述性字幕以实现多模态感知

发布时间：2024年12月18日

`LLM应用` `视觉理解`

> Descriptive Caption Enhancement with Visual Specialists for Multimodal Perception

# 摘要

> 训练大型多模态模型（LMMs）离不开连接图像与语言的描述性图像标题。现有的方法，要么从 LMM 模型中提炼标题，要么从互联网图像获取或由人工构建。我们建议借助现成的视觉专家，他们最初是基于有标注的图像训练的，并非用于生成图像标题，来强化图像标题。
  我们的方法名为 DCE，探索对象的低层级和细粒度属性（如深度、情感和细粒度类别）以及对象关系（如相对位置和人-对象交互（HOI）），并将这些属性融入描述性标题。实验表明，这类视觉专家能够提升视觉理解任务的表现，以及得益于更精准视觉理解的推理能力。我们会发布源代码和流程，以便其他视觉专家能轻松融入流程。DCE 流程和数据集的完整源代码将在 url{https://github.com/syp2ysy/DCE} 提供。

> Training Large Multimodality Models (LMMs) relies on descriptive image caption that connects image and language. Existing methods either distill the caption from the LMM models or construct the captions from the internet images or by human. We propose to leverage off-the-shelf visual specialists, which were trained from annotated images initially not for image captioning, for enhancing the image caption.
  Our approach, named DCE, explores object low-level and fine-grained attributes (e.g., depth, emotion and fine-grained categories) and object relations (e.g., relative location and human-object-interaction (HOI)), and combine the attributes into the descriptive caption. Experiments demonstrate that such visual specialists are able to improve the performance for visual understanding tasks as well as reasoning that benefits from more accurate visual understanding. We will release the source code and the pipeline so that other visual specialists are easily combined into the pipeline. The complete source code of DCE pipeline and datasets will be available at url{https://github.com/syp2ysy/DCE}.

[Arxiv](https://arxiv.org/abs/2412.14233)