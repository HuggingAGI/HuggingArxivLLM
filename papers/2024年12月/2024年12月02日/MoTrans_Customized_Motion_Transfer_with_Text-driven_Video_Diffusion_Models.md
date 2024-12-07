# MoTrans：基于文本驱动视频扩散模型的定制化运动转移

发布时间：2024年12月02日

`LLM应用` `视频生成` `动作建模`

> MoTrans: Customized Motion Transfer with Text-driven Video Diffusion Models

# 摘要

> 现有的预训练文本转视频（T2V）模型在生成有基本动作或摄像机移动的逼真视频时，展现出了非凡的能力。然而，在生成复杂的、以人为核心的动作时，这些模型存在明显局限。当下的努力主要集中于对一小部分含特定动作的视频进行模型微调。它们常常难以在有限的参考视频中有效分离动作与外观，进而削弱了动作模式的建模能力。为此，我们提出了 MoTrans，这是一种定制的动作迁移方法，能在新情境中生成相似动作的视频。具体而言，我们引入了基于多模态大型语言模型（MLLM）的重新描述器，将初始提示拓展得更侧重于外观，还引入了外观注入模块，把视频帧中的外观先验适配到动作建模过程。这些来自重新描述的提示和视频帧的互补多模态表示，促进了外观建模，也有利于外观与动作的解耦。另外，我们设计了特定于动作的嵌入，进一步强化特定动作的建模。实验结果表明，我们的方法能有效地从单个或多个参考视频中学习特定动作模式，在定制视频生成方面比现有方法表现更优。

> Existing pretrained text-to-video (T2V) models have demonstrated impressive abilities in generating realistic videos with basic motion or camera movement. However, these models exhibit significant limitations when generating intricate, human-centric motions. Current efforts primarily focus on fine-tuning models on a small set of videos containing a specific motion. They often fail to effectively decouple motion and the appearance in the limited reference videos, thereby weakening the modeling capability of motion patterns. To this end, we propose MoTrans, a customized motion transfer method enabling video generation of similar motion in new context. Specifically, we introduce a multimodal large language model (MLLM)-based recaptioner to expand the initial prompt to focus more on appearance and an appearance injection module to adapt appearance prior from video frames to the motion modeling process. These complementary multimodal representations from recaptioned prompt and video frames promote the modeling of appearance and facilitate the decoupling of appearance and motion. In addition, we devise a motion-specific embedding for further enhancing the modeling of the specific motion. Experimental results demonstrate that our method effectively learns specific motion pattern from singular or multiple reference videos, performing favorably against existing methods in customized video generation.

[Arxiv](https://arxiv.org/abs/2412.01343)