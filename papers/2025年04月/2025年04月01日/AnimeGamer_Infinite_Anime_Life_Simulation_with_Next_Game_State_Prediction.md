# AnimeGamer：无限动漫人生模拟世界，结合游戏下一状态预测技术。

发布时间：2025年04月01日

`LLM应用` `视频生成`

> AnimeGamer: Infinite Anime Life Simulation with Next Game State Prediction

# 摘要

> 图像和视频合成的最新进展为生成类游戏开辟了新的可能性。其中最引人入胜的应用之一是将动漫电影中的角色转变为可交互、可玩的游戏实体。玩家可以通过语言指令，以自己钟爱的角色身份沉浸在动态的动漫世界中，体验生活模拟的乐趣。这类游戏被称为无限游戏，因其打破了预设的边界和固定规则，让玩家通过开放式的语言与游戏世界互动，感受不断演变的故事线和环境。最近，一种开创性的无限动漫生活模拟方法采用了大型语言模型（LLMs），将多轮文本对话转化为图像生成的语言指令。然而，该方法忽视了历史视觉上下文，导致游戏体验不连贯。此外，它仅生成静态图像，未能融入吸引人的游戏动态元素。为此，我们提出了AnimeGamer，该框架基于多模态大型语言模型（MLLMs），能够生成包含动态动画镜头（展示角色动作和状态更新）的游戏状态，如图1所示。我们引入了动作感知的多模态表示来描述动画镜头，这些表示可以通过视频扩散模型转化为高质量的视频片段。通过将历史动画镜头表示作为上下文，并预测后续表示，AnimeGamer能够生成上下文一致且动态丰富的游戏体验。通过自动化指标和人工评估的全面测试，AnimeGamer在游戏体验的多个方面均优于现有方法。代码和检查点可在https://github.com/TencentARC/AnimeGamer获取。

> Recent advancements in image and video synthesis have opened up new promise in generative games. One particularly intriguing application is transforming characters from anime films into interactive, playable entities. This allows players to immerse themselves in the dynamic anime world as their favorite characters for life simulation through language instructions. Such games are defined as infinite game since they eliminate predetermined boundaries and fixed gameplay rules, where players can interact with the game world through open-ended language and experience ever-evolving storylines and environments. Recently, a pioneering approach for infinite anime life simulation employs large language models (LLMs) to translate multi-turn text dialogues into language instructions for image generation. However, it neglects historical visual context, leading to inconsistent gameplay. Furthermore, it only generates static images, failing to incorporate the dynamics necessary for an engaging gaming experience. In this work, we propose AnimeGamer, which is built upon Multimodal Large Language Models (MLLMs) to generate each game state, including dynamic animation shots that depict character movements and updates to character states, as illustrated in Figure 1. We introduce novel action-aware multimodal representations to represent animation shots, which can be decoded into high-quality video clips using a video diffusion model. By taking historical animation shot representations as context and predicting subsequent representations, AnimeGamer can generate games with contextual consistency and satisfactory dynamics. Extensive evaluations using both automated metrics and human evaluations demonstrate that AnimeGamer outperforms existing methods in various aspects of the gaming experience. Codes and checkpoints are available at https://github.com/TencentARC/AnimeGamer.

[Arxiv](https://arxiv.org/abs/2504.01014)