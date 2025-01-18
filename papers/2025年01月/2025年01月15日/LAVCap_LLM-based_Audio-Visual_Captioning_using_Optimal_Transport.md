# LAVCap: 基于LLM的音频-视觉字幕生成，采用最优传输技术

发布时间：2025年01月15日

`LLM应用

理由：这篇论文提出了一个基于大型语言模型（LLM）的音频-视觉字幕生成框架LAVCap，旨在通过整合视觉信息提升字幕生成性能。该研究直接应用了LLM技术来解决音频字幕生成任务，属于LLM在实际应用中的具体使用案例，因此应归类为LLM应用。` `音频处理` `计算机视觉`

> LAVCap: LLM-based Audio-Visual Captioning using Optimal Transport

# 摘要

> 自动音频字幕生成任务旨在为音频内容生成文本描述。近期研究尝试利用视觉信息提升字幕质量，但现有方法在融合音频和视觉数据时效果欠佳，常忽略重要语义线索。为此，我们提出了LAVCap，一个基于大型语言模型（LLM）的音频-视觉字幕生成框架，通过有效整合视觉信息提升字幕生成性能。LAVCap采用最优传输对齐损失，弥合音频与视觉特征的模态差异，实现更高效的语义提取。我们还引入了最优传输注意力模块，利用最优传输分配图增强音频-视觉融合。结合最优训练策略，实验证明框架各组件均有效。LAVCap在AudioCaps数据集上表现优异，超越现有最先进方法，且无需依赖大规模数据集或后处理。代码已开源：https://github.com/NAVER-INTEL-Co-Lab/gaudi-lavcap。

> Automated audio captioning is a task that generates textual descriptions for audio content, and recent studies have explored using visual information to enhance captioning quality. However, current methods often fail to effectively fuse audio and visual data, missing important semantic cues from each modality. To address this, we introduce LAVCap, a large language model (LLM)-based audio-visual captioning framework that effectively integrates visual information with audio to improve audio captioning performance. LAVCap employs an optimal transport-based alignment loss to bridge the modality gap between audio and visual features, enabling more effective semantic extraction. Additionally, we propose an optimal transport attention module that enhances audio-visual fusion using an optimal transport assignment map. Combined with the optimal training strategy, experimental results demonstrate that each component of our framework is effective. LAVCap outperforms existing state-of-the-art methods on the AudioCaps dataset, without relying on large datasets or post-processing. Code is available at https://github.com/NAVER-INTEL-Co-Lab/gaudi-lavcap.

[Arxiv](https://arxiv.org/abs/2501.09291)