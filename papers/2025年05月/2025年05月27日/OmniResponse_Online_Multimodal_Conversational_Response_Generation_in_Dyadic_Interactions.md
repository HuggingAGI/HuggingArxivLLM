# OmniResponse：双向互动中的在线多模态对话响应生成

发布时间：2025年05月27日

`LLM应用` `人机交互` `智能对话系统`

> OmniResponse: Online Multimodal Conversational Response Generation in Dyadic Interactions

# 摘要

> 本文提出了一项激动人心的新任务——在线多模态对话响应生成（OMCRG），致力于基于说话人的多模态输入，在线生成同步的言语与非言语反馈。这一任务不仅体现了自然的双向互动特性，更在音频与面部反应的同步生成上提出了全新挑战。为突破这些难题，我们开创性地引入文本作为连接音频与面部反应的中间模态。在此基础上，我们提出了OmniResponse——一款多模态大型语言模型（MLLM），能够自回归生成高质量的多模态听者反馈。OmniResponse基于增强型预训练LLM，配备了两大创新组件：Chrono-Text通过时间锚点优化文本生成，而TempoVoice则是一个可控的在线TTS模块，可实现语音与面部反应的精准同步。为了推动OMCRG领域的进一步研究，我们推出了ResponseNet数据集，其中包含696个高质量双向互动案例，每个案例均配有同步的分屏视频、多声道音频、文本转录和面部行为注释。通过在ResponseNet上的全面评估，OmniResponse在语义语音内容、视听同步性及生成质量方面均显著超越现有基线模型。

> In this paper, we introduce Online Multimodal Conversational Response Generation (OMCRG), a novel task that aims to online generate synchronized verbal and non-verbal listener feedback, conditioned on the speaker's multimodal input. OMCRG reflects natural dyadic interactions and poses new challenges in achieving synchronization between the generated audio and facial responses of the listener. To address these challenges, we innovatively introduce text as an intermediate modality to bridge the audio and facial responses. We hence propose OmniResponse, a Multimodal Large Language Model (MLLM) that autoregressively generates high-quality multi-modal listener responses. OmniResponse leverages a pretrained LLM enhanced with two novel components: Chrono-Text, which temporally anchors generated text tokens, and TempoVoice, a controllable online TTS module that produces speech synchronized with facial reactions. To support further OMCRG research, we present ResponseNet, a new dataset comprising 696 high-quality dyadic interactions featuring synchronized split-screen videos, multichannel audio, transcripts, and facial behavior annotations. Comprehensive evaluations conducted on ResponseNet demonstrate that OmniResponse significantly outperforms baseline models in terms of semantic speech content, audio-visual synchronization, and generation quality.

[Arxiv](https://arxiv.org/abs/2505.21724)