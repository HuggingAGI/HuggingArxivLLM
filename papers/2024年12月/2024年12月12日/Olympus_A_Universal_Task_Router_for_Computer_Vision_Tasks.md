# Olympus：计算机视觉任务的通用任务路由工具

发布时间：2024年12月12日

`LLM应用` `计算机视觉` `多模态语言模型`

> Olympus: A Universal Task Router for Computer Vision Tasks

# 摘要

> 我们推出了 Olympus 这一新方法，它能将多模态大型语言模型（MLLMs）转化为一个统一的框架，从而能够处理众多计算机视觉任务。借助控制器 MLLM，Olympus 把图像、视频和 3D 对象相关的 20 多个专项任务分配给了专门的模块。这种基于指令的路由方式，无需训练繁重的生成模型，就能通过链式操作实现复杂的工作流程。Olympus 能轻松与现有的 MLLMs 集成，在性能相当的情况下拓展了它们的能力。实验结果显示，Olympus 在 20 个任务中的平均路由准确率达 94.75%，在链式操作场景中的精度为 91.82%，充分证明了其作为能解决各类计算机视觉任务的通用任务路由器的有效性。项目页面: https://github.com/yuanze-lin/Olympus_page

> We introduce Olympus, a new approach that transforms Multimodal Large Language Models (MLLMs) into a unified framework capable of handling a wide array of computer vision tasks. Utilizing a controller MLLM, Olympus delegates over 20 specialized tasks across images, videos, and 3D objects to dedicated modules. This instruction-based routing enables complex workflows through chained actions without the need for training heavy generative models. Olympus easily integrates with existing MLLMs, expanding their capabilities with comparable performance. Experimental results demonstrate that Olympus achieves an average routing accuracy of 94.75% across 20 tasks and precision of 91.82% in chained action scenarios, showcasing its effectiveness as a universal task router that can solve a diverse range of computer vision tasks. Project page: https://github.com/yuanze-lin/Olympus_page

[Arxiv](https://arxiv.org/abs/2412.09612)