# Kling-Avatar：锚定多模态指令的级联式长时程虚拟人动画合成

发布时间：2025年09月11日

`LLM应用` `媒体与娱乐`

> Kling-Avatar: Grounding Multimodal Instructions for Cascaded Long-Duration Avatar Animation Synthesis

# 摘要

> 音频驱动虚拟人视频生成技术的最新突破，大幅提升了视听效果的真实感。但现有方法往往将指令条件控制简化为声学或视觉线索驱动的低层次跟踪，忽略了对指令所蕴含交际意图的建模——这一缺陷导致其叙事连贯性和角色表现力大打折扣。为此，我们提出了Kling-Avatar——一种新颖的级联框架，将多模态指令理解与照片级真实感人像生成融为一体。该方法采用两阶段处理流程：第一阶段，构建多模态大型语言模型（MLLM）“导演”，根据多样化指令信号生成“蓝图视频”，进而掌控角色动作、情感等高层次语义；第二阶段，在蓝图关键帧引导下，通过首尾帧策略并行生成多个子片段。这种“全局到局部”的框架，既能忠实捕捉多模态指令背后的高层次意图，又能保留细粒度细节。此外，并行架构支持长视频的快速稳定生成，使其能胜任数字人直播、视频博客等实际场景。为全面验证方法性能，我们构建了包含375个精选样本的基准数据集，覆盖多样化指令与复杂场景。实验结果显示，Kling-Avatar可生成生动流畅的长视频（分辨率1080p、帧率48fps），并在唇形同步精度、情感动态表现力、指令可控性、身份一致性及跨域泛化能力上均表现卓越。这些成果奠定了Kling-Avatar在语义可控、高保真音频驱动虚拟人合成领域的新基准地位。

> Recent advances in audio-driven avatar video generation have significantly enhanced audio-visual realism. However, existing methods treat instruction conditioning merely as low-level tracking driven by acoustic or visual cues, without modeling the communicative purpose conveyed by the instructions. This limitation compromises their narrative coherence and character expressiveness. To bridge this gap, we introduce Kling-Avatar, a novel cascaded framework that unifies multimodal instruction understanding with photorealistic portrait generation. Our approach adopts a two-stage pipeline. In the first stage, we design a multimodal large language model (MLLM) director that produces a blueprint video conditioned on diverse instruction signals, thereby governing high-level semantics such as character motion and emotions. In the second stage, guided by blueprint keyframes, we generate multiple sub-clips in parallel using a first-last frame strategy. This global-to-local framework preserves fine-grained details while faithfully encoding the high-level intent behind multimodal instructions. Our parallel architecture also enables fast and stable generation of long-duration videos, making it suitable for real-world applications such as digital human livestreaming and vlogging. To comprehensively evaluate our method, we construct a benchmark of 375 curated samples covering diverse instructions and challenging scenarios. Extensive experiments demonstrate that Kling-Avatar is capable of generating vivid, fluent, long-duration videos at up to 1080p and 48 fps, achieving superior performance in lip synchronization accuracy, emotion and dynamic expressiveness, instruction controllability, identity preservation, and cross-domain generalization. These results establish Kling-Avatar as a new benchmark for semantically grounded, high-fidelity audio-driven avatar synthesis.

[Arxiv](https://arxiv.org/abs/2509.09595)