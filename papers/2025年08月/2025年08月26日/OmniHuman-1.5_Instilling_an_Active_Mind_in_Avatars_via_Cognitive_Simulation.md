# OmniHuman-1.5：借由认知模拟为化身赋予主动思维

发布时间：2025年08月26日

`LLM应用` `媒体与娱乐`

> OmniHuman-1.5: Instilling an Active Mind in Avatars via Cognitive Simulation

# 摘要

> 现有视频虚拟人模型虽能生成流畅的人体动画，却难以跳出单纯的外形模仿，真正捕捉角色的内在神韵。这些模型生成的动作往往仅与音频节奏等低级信号同步，缺乏对情感、意图或语境的深层语义理解。为此，	extbf{我们提出了一个全新框架，致力于生成既符合物理规律，又语义连贯、富有表现力的角色动画。}我们的模型	extbf{OmniHuman-1.5}正是基于两项核心技术突破打造而成。其一，我们借助多模态大型语言模型合成结构化的条件文本表示，以此提供高层语义指导。这一指导机制让动作生成器不再局限于简单的节奏同步，而是能生成与语境和情感深度契合的动作。其二，为确保多模态输入的有效融合并减少模态间冲突，我们设计了一种专用的多模态DiT架构，并创新性地引入了伪最后一帧设计。这些组件的协同作用使模型能够精准解读音频、图像和文本的联合语义，进而生成与角色、场景及语言内容高度契合的动作。大量实验表明，我们的模型在唇形同步准确性、视频质量、动作自然度以及与文本提示的语义一致性等多项综合指标上均表现领先。此外，该方法在复杂场景中展现出极强的扩展性，例如多人互动及非人类角色等场景均可适用。主页：\href{https://omnihuman-lab.github.io/v1_5/}

> Existing video avatar models can produce fluid human animations, yet they struggle to move beyond mere physical likeness to capture a character's authentic essence. Their motions typically synchronize with low-level cues like audio rhythm, lacking a deeper semantic understanding of emotion, intent, or context. To bridge this gap, \textbf{we propose a framework designed to generate character animations that are not only physically plausible but also semantically coherent and expressive.} Our model, \textbf{OmniHuman-1.5}, is built upon two key technical contributions. First, we leverage Multimodal Large Language Models to synthesize a structured textual representation of conditions that provides high-level semantic guidance. This guidance steers our motion generator beyond simplistic rhythmic synchronization, enabling the production of actions that are contextually and emotionally resonant. Second, to ensure the effective fusion of these multimodal inputs and mitigate inter-modality conflicts, we introduce a specialized Multimodal DiT architecture with a novel Pseudo Last Frame design. The synergy of these components allows our model to accurately interpret the joint semantics of audio, images, and text, thereby generating motions that are deeply coherent with the character, scene, and linguistic content. Extensive experiments demonstrate that our model achieves leading performance across a comprehensive set of metrics, including lip-sync accuracy, video quality, motion naturalness and semantic consistency with textual prompts. Furthermore, our approach shows remarkable extensibility to complex scenarios, such as those involving multi-person and non-human subjects. Homepage: \href{https://omnihuman-lab.github.io/v1_5/}

[Arxiv](https://arxiv.org/abs/2508.19209)