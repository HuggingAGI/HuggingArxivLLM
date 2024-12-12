# StreamChat：与流媒体视频畅聊

发布时间：2024年12月11日

`LLM应用` `流媒体` `视频交互`

> StreamChat: Chatting with Streaming Video

# 摘要

> 本文推出了 StreamChat 这一创新方法，它能够提升大型多模态模型（LMMs）与流媒体视频内容的交互水平。在流媒体交互场景下，现有的方法仅仅依靠提问时的视觉信息，致使模型无法知晓流媒体视频的后续变化，从而产生明显的延迟。StreamChat 巧妙地在每个解码步骤更新视觉上下文，以此解决这一局限，保证模型在整个解码流程中都能运用最新的视频内容。另外，我们引入了灵活高效的基于交叉注意力的架构来处理动态的流媒体输入，同时维持流媒体交互的推理效率。再者，我们构建了新的密集指令数据集来助力流媒体交互模型的训练，还搭配了并行 3D-RoPE 机制，用于对视觉和文本标记的相对时间信息进行编码。实验结果显示，StreamChat 在既定的图像和视频基准测试中表现出色，在流媒体交互场景中相较于最先进的视频 LMM 具备更卓越的能力。

> This paper presents StreamChat, a novel approach that enhances the interaction capabilities of Large Multimodal Models (LMMs) with streaming video content. In streaming interaction scenarios, existing methods rely solely on visual information available at the moment a question is posed, resulting in significant delays as the model remains unaware of subsequent changes in the streaming video. StreamChat addresses this limitation by innovatively updating the visual context at each decoding step, ensuring that the model utilizes up-to-date video content throughout the decoding process. Additionally, we introduce a flexible and efficient crossattention-based architecture to process dynamic streaming inputs while maintaining inference efficiency for streaming interactions. Furthermore, we construct a new dense instruction dataset to facilitate the training of streaming interaction models, complemented by a parallel 3D-RoPE mechanism that encodes the relative temporal information of visual and text tokens. Experimental results demonstrate that StreamChat achieves competitive performance on established image and video benchmarks and exhibits superior capabilities in streaming interaction scenarios compared to state-of-the-art video LMM.

[Arxiv](https://arxiv.org/abs/2412.08646)