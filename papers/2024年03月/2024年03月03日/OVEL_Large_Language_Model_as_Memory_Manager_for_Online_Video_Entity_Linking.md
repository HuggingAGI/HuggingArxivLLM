# OVEL 利用大型语言模型充当在线视频实体链接的记忆管家，提升链接效能。

发布时间：2024年03月03日

`LLM应用`

> OVEL: Large Language Model as Memory Manager for Online Video Entity Linking

# 摘要

> 近年来，因在各类多模态应用中发挥关键作用，多模态实体链接（MEL）研究愈发受到学术界的重视。视频作为信息传递的重要载体，已深深渗透到人们的日常生活中。不过，现有主流的 MEL 方法更多地专注于将文本、视觉以及离线视频中的实体提及与多模态知识库中的实体关联起来，而对在线视频内容内实体提及的链接则研究较少。为此，本文提出了“在线视频实体链接”（OVEL）这一新任务，旨在高效精准地连接在线视频中的实体提及与知识库。为了促进 OVEL 领域的研究进展，我们特以直播场景为切入点，精心构建了 LIVE 数据集。同时，我们创新性地设计了一套综合考量时效性、稳定性及精确度的评估标准。此外，我们借助大型语言模型管理的记忆模块，从知识库中检索实体候选信息以提升 LLM 在内存管理方面的表现。实验验证了我们所提方法在效果和效率上的优越性。

> In recent years, multi-modal entity linking (MEL) has garnered increasing attention in the research community due to its significance in numerous multi-modal applications. Video, as a popular means of information transmission, has become prevalent in people's daily lives. However, most existing MEL methods primarily focus on linking textual and visual mentions or offline videos's mentions to entities in multi-modal knowledge bases, with limited efforts devoted to linking mentions within online video content. In this paper, we propose a task called Online Video Entity Linking OVEL, aiming to establish connections between mentions in online videos and a knowledge base with high accuracy and timeliness. To facilitate the research works of OVEL, we specifically concentrate on live delivery scenarios and construct a live delivery entity linking dataset called LIVE. Besides, we propose an evaluation metric that considers timelessness, robustness, and accuracy. Furthermore, to effectively handle OVEL task, we leverage a memory block managed by a Large Language Model and retrieve entity candidates from the knowledge base to augment LLM performance on memory management. The experimental results prove the effectiveness and efficiency of our method.

[Arxiv](https://arxiv.org/abs/2403.01411)