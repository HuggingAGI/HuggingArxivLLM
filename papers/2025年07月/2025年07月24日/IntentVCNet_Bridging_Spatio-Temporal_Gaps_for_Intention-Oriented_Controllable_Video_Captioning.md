# 意图视频描述网络：跨越时空鸿沟，实现意图导向的可控视频描述生成

发布时间：2025年07月24日

`LLM应用` `计算机视觉` `语言模型`

> IntentVCNet: Bridging Spatio-Temporal Gaps for Intention-Oriented Controllable Video Captioning

# 摘要

> 意图导向的视频描述生成旨在根据用户自定义意图，为视频中的特定目标生成有针对性的描述。当前大型视觉语言模型（LVLMs）在遵循指令和视觉理解方面表现出强大的能力。尽管LVLMs在空间和时间理解方面分别表现出色，但它们在直接响应指令时，无法实现对时空序列中空间细节的精细控制。这种显著的时空差距使得实现视频中的细粒度意图导向控制变得复杂。为此，我们提出了一种新型的 IntentVCNet，旨在整合LVLMs内在的时间和空间理解知识，从提示和模型两个角度弥合时空差距。具体而言，我们首先提出了一种提示组合策略，旨在使语言模型能够建模表征用户意图的提示与视频序列之间的隐含关系。然后，我们提出了一种参数高效的边界框适配器，用于增强全局视觉上下文中的对象语义信息，使得视觉令牌能够预先了解用户意图。最终实验表明，这两种策略的结合可以进一步提升LVLMs对视频序列中空间细节的建模能力，并帮助LVLMs准确生成受控的意图导向描述。我们的方法在多个开源LVLMs上实现了最先进的结果，并在IntentVC挑战赛中获得亚军。我们的代码可在 https://github.com/thqiu0419/IntentVCNet 获取。

> Intent-oriented controlled video captioning aims to generate targeted descriptions for specific targets in a video based on customized user intent. Current Large Visual Language Models (LVLMs) have gained strong instruction following and visual comprehension capabilities. Although the LVLMs demonstrated proficiency in spatial and temporal understanding respectively, it was not able to perform fine-grained spatial control in time sequences in direct response to instructions. This substantial spatio-temporal gap complicates efforts to achieve fine-grained intention-oriented control in video. Towards this end, we propose a novel IntentVCNet that unifies the temporal and spatial understanding knowledge inherent in LVLMs to bridge the spatio-temporal gap from both prompting and model perspectives. Specifically, we first propose a prompt combination strategy designed to enable LLM to model the implicit relationship between prompts that characterize user intent and video sequences. We then propose a parameter efficient box adapter that augments the object semantic information in the global visual context so that the visual token has a priori information about the user intent. The final experiment proves that the combination of the two strategies can further enhance the LVLM's ability to model spatial details in video sequences, and facilitate the LVLMs to accurately generate controlled intent-oriented captions. Our proposed method achieved state-of-the-art results in several open source LVLMs and was the runner-up in the IntentVC challenge. Our code is available on https://github.com/thqiu0419/IntentVCNet.

[Arxiv](https://arxiv.org/abs/2507.18531)