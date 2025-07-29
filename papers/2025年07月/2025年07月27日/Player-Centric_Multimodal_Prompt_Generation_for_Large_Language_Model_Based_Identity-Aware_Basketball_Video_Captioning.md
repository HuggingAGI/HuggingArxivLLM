# # 基于大型语言模型的以球员为中心多模态提示生成篮球视频身份感知字幕生成

发布时间：2025年07月27日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLM）在体育视频字幕生成中的应用，特别是在识别球员身份方面的创新。论文提出了一种多模态提示生成网络，结合视觉和语义信息，以提高生成描述的准确性。虽然涉及模型结构和模块设计，但核心是LLM的应用场景和改进，因此归类为LLM应用。` `体育视频` `视频分析`

> Player-Centric Multimodal Prompt Generation for Large Language Model Based Identity-Aware Basketball Video Captioning

# 摘要

> 现有体育视频字幕生成方法多关注动作，却忽视了球员身份，限制了其应用范围。尽管有方法整合额外信息生成身份意识描述，但因信息独立，身份常有误。本文提出LLM-IAVC，一种以球员为中心的多模态提示生成网络，专注于从视觉角度识别球员身份。设计了身份相关信息提取模块（IRIEM），提取球员相关的多模态嵌入。IRIEM包含球员识别网络（PIN），提取视觉特征和名字，及双向语义交互模块（BSIM），增强球员特征与视频内容的关联。此外，视觉上下文学习模块（VCLM）捕捉关键视频信息。通过整合模块输出作为LLM提示，生成带球员身份的描述。我们构建了NBA-Identity数据集，含9,726个视频，涵盖9种事件类型。实验结果表明，LLM-IAVC性能优越。代码和数据集已公开。

> Existing sports video captioning methods often focus on the action yet overlook player identities, limiting their applicability. Although some methods integrate extra information to generate identity-aware descriptions, the player identities are sometimes incorrect because the extra information is independent of the video content. This paper proposes a player-centric multimodal prompt generation network for identity-aware sports video captioning (LLM-IAVC), which focuses on recognizing player identities from a visual perspective. Specifically, an identity-related information extraction module (IRIEM) is designed to extract player-related multimodal embeddings. IRIEM includes a player identification network (PIN) for extracting visual features and player names, and a bidirectional semantic interaction module (BSIM) to link player features with video content for mutual enhancement. Additionally, a visual context learning module (VCLM) is designed to capture the key video context information. Finally, by integrating the outputs of the above modules as the multimodal prompt for the large language model (LLM), it facilitates the generation of descriptions with player identities. To support this work, we construct a new benchmark called NBA-Identity, a large identity-aware basketball video captioning dataset with 9,726 videos covering 9 major event types. The experimental results on NBA-Identity and VC-NBA-2022 demonstrate that our proposed model achieves advanced performance. Code and dataset are publicly available at https://github.com/Zeyu1226-mt/LLM-IAVC.

[Arxiv](https://arxiv.org/abs/2507.20163)