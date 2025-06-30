# DeepTalk：实现无缝智能语音交互，基于自适应模态特定的MoE

发布时间：2025年06月26日

`LLM理论` `语音交互` `多模态模型`

> DeepTalk: Towards Seamless and Smart Speech Interaction with Adaptive Modality-Specific MoE

# 摘要

> 原生多模态大型语言模型（MLLMs）将单一的大型语言模型（LLM）重构为能够同时生成语音和文本的语音语言模型（SLM）。相比模块化且对齐的MLLMs，原生MLLMs保留了更丰富的情感和韵律等副语言特征，并在主干LLM内部直接生成语音响应，无需依赖独立的语音解码器，从而实现更低的响应延迟和更流畅的交互体验。然而，由于MLLMs预训练所需的配对语音-文本数据量远不及文本LLMs所需的海量文本数据，原生MLLMs面临着灾难性遗忘和性能下降的挑战。为解决这一问题，我们提出了DeepTalk——一个基于专家混合（MoE）架构的自适应模态专家学习框架。DeepTalk首先根据模态负载在LLM内部自适应地区分不同的模态专家。每个模态专家随后接受专门的单模态训练，最后进行联合多模态协作训练。结果显示，DeepTalk仅导致5.5%的性能下降，远低于原生MLLMs（如GLM-4-Voice）通常超过20%的平均性能下降，与模块化MLLMs持平。同时，端到端对话延迟保持在0.5秒以内，确保了无缝且智能的语音交互体验。代码和模型已发布在https://github.com/talkking/DeepTalk。


> Native multimodal large language models (MLLMs) restructure a single large language model (LLM) into a spoken language model (SLM) capable of both speech and text generation. Compared to modular and aligned MLLMs, native MLLMs preserve richer paralinguistic features such as emotion and prosody, and generate speech responses directly within the backbone LLM rather than using a separate speech decoder. This integration also results in lower response latency and smoother interaction. However, native MLLMs suffer from catastrophic forgetting and performance degradation because the available paired speech-text data is insufficient to support the pretraining of MLLMs compared to the vast amount of text data required to pretrain text LLMs. To address this issue, we propose DeepTalk, a framework for adaptive modality expert learning based on a Mixture of Experts (MoE) architecture. DeepTalk first adaptively distinguishes modality experts according to their modality load within the LLM. Each modality expert then undergoes specialized single-modality training, followed by joint multimodal collaborative training. As a result, DeepTalk incurs only a 5.5% performance drop compared to the original LLM, which is significantly lower than the average performance drop of over 20% typically seen in native MLLMs (such as GLM-4-Voice), and is on par with modular MLLMs. Meanwhile, the end-to-end dialogue latency remains within 0.5 seconds, ensuring a seamless and intelligent speech interaction experience. Code and models are released at https://github.com/talkking/DeepTalk.

[Arxiv](https://arxiv.org/abs/2506.21864)