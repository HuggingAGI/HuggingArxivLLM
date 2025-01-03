# 从简单到专业：组合可控的图像描述生成智能体

发布时间：2024年12月14日

`Agent

理由：这篇论文描述了一个名为CapAgent的系统，它能够将用户的简单指令转化为详细的专业指令，并生成精准的图像描述。该系统利用了多模态大语言模型（MLLMs）和外部工具（如目标检测工具和搜索引擎），并且透明地控制每一步生成过程。这些特征表明CapAgent是一个自主的、能够执行复杂任务的智能体（Agent），因此将其分类为Agent是合适的。` `图像处理` `人机交互`

> From Simple to Professional: A Combinatorial Controllable Image Captioning Agent

# 摘要

> CapAgent 是一款创新的图像描述生成系统，旨在简化用户操作的同时提供专业级的输出。它能将用户的简单指令自动转化为详细的专业指令，生成精准且符合上下文的描述。借助多模态大语言模型（MLLMs）和外部工具（如目标检测工具和搜索引擎），CapAgent 确保描述符合情感、关键词、焦点和格式等要求。系统透明地控制每一步生成过程，并展示推理和工具使用细节，提升用户信任与参与感。项目代码已开源：https://github.com/xin-ran-w/CapAgent。

> The Controllable Image Captioning Agent (CapAgent) is an innovative system designed to bridge the gap between user simplicity and professional-level outputs in image captioning tasks. CapAgent automatically transforms user-provided simple instructions into detailed, professional instructions, enabling precise and context-aware caption generation. By leveraging multimodal large language models (MLLMs) and external tools such as object detection tool and search engines, the system ensures that captions adhere to specified guidelines, including sentiment, keywords, focus, and formatting. CapAgent transparently controls each step of the captioning process, and showcases its reasoning and tool usage at every step, fostering user trust and engagement. The project code is available at https://github.com/xin-ran-w/CapAgent.

[Arxiv](https://arxiv.org/abs/2412.11025)