# 视频中的面部动态：指令微调助力面部表情感知与上下文意识提升

发布时间：2025年01月14日

`LLM应用

**理由**：这篇论文主要讨论了视频多模态大语言模型（MLLMs）在面部表情描述任务中的应用，提出了一个新的数据集和模型（FaceTrack-MM），并引入了新的评估指标和基准测试（FEC-Bench）。这些内容都属于大语言模型在实际应用中的改进和优化，因此分类为LLM应用。` `面部识别` `视频分析`

> Facial Dynamics in Video: Instruction Tuning for Improved Facial Expression Perception and Contextual Awareness

# 摘要

> 面部表情描述在多个领域广泛应用。近期，视频多模态大语言模型（MLLMs）在通用视频理解任务中展现出潜力。然而，视频中的面部表情描述对这些模型提出了两大挑战：一是缺乏足够的数据集和基准测试，二是视频MLLMs的视觉标记容量有限。为此，本文推出了一款专为动态面部表情描述设计的指令跟随数据集，包含5,033个高质量视频片段，手动标注，标记数超过700,000个，旨在提升视频MLLMs识别细微面部表情的能力。此外，我们提出了FaceTrack-MM模型，它通过有限的标记数量编码主角的面部，即使在复杂的多人场景中，也能出色地跟踪面部并聚焦主角的表情。我们还引入了一种新的评估指标，结合事件提取、关系分类和最长公共子序列（LCS）算法，用于评估生成文本的内容一致性和时间序列一致性。同时，我们推出了FEC-Bench基准测试，用于评估现有视频MLLMs在这一特定任务中的表现。所有数据和源代码将公开提供。

> Facial expression captioning has found widespread application across various domains. Recently, the emergence of video Multimodal Large Language Models (MLLMs) has shown promise in general video understanding tasks. However, describing facial expressions within videos poses two major challenges for these models: (1) the lack of adequate datasets and benchmarks, and (2) the limited visual token capacity of video MLLMs. To address these issues, this paper introduces a new instruction-following dataset tailored for dynamic facial expression caption. The dataset comprises 5,033 high-quality video clips annotated manually, containing over 700,000 tokens. Its purpose is to improve the capability of video MLLMs to discern subtle facial nuances. Furthermore, we propose FaceTrack-MM, which leverages a limited number of tokens to encode the main character's face. This model demonstrates superior performance in tracking faces and focusing on the facial expressions of the main characters, even in intricate multi-person scenarios. Additionally, we introduce a novel evaluation metric combining event extraction, relation classification, and the longest common subsequence (LCS) algorithm to assess the content consistency and temporal sequence consistency of generated text. Moreover, we present FEC-Bench, a benchmark designed to assess the performance of existing video MLLMs in this specific task. All data and source code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2501.07978)