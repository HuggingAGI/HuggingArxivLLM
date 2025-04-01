# Any2Caption：将任意条件转化为视频字幕，从而实现对视频生成过程的精准控制

发布时间：2025年03月31日

`LLM应用` `视频生成` `计算机视觉`

> Any2Caption:Interpreting Any Condition to Caption for Controllable Video Generation

# 摘要

> 针对当前视频生成领域中用户意图准确解释的瓶颈，我们提出了 Any2Caption——一个在任意条件下实现可控视频生成的创新框架。其核心理念在于将条件解释与视频合成过程解耦。借助现代多模态大语言模型（MLLMs），Any2Caption能够将文本、图像、视频以及区域、运动和相机姿态等多样化输入转化为密集、结构化的描述，从而为视频生成器提供更精准的指导。同时，我们推出了 Any2CapIns 数据集，包含 337K 实例和 407K 条件，专为任意条件到描述的指令微调设计。全面的实验结果表明，与现有视频生成模型相比，我们的系统在可控性和视频质量方面均有显著提升。项目页面：https://sqwu.top/Any2Cap/

> To address the bottleneck of accurate user intent interpretation within the current video generation community, we present Any2Caption, a novel framework for controllable video generation under any condition. The key idea is to decouple various condition interpretation steps from the video synthesis step. By leveraging modern multimodal large language models (MLLMs), Any2Caption interprets diverse inputs--text, images, videos, and specialized cues such as region, motion, and camera poses--into dense, structured captions that offer backbone video generators with better guidance. We also introduce Any2CapIns, a large-scale dataset with 337K instances and 407K conditions for any-condition-to-caption instruction tuning. Comprehensive evaluations demonstrate significant improvements of our system in controllability and video quality across various aspects of existing video generation models. Project Page: https://sqwu.top/Any2Cap/

[Arxiv](https://arxiv.org/abs/2503.24379)