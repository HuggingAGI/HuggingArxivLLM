# EditIQ: 基于对话解析与显著性提示的静态广角视频自动电影化剪辑

发布时间：2025年02月04日

`LLM应用

理由：这篇论文介绍了EditIQ框架，该框架利用LLM（大型语言模型）进行对话理解，并结合视觉显著性预测来实现电影化视频编辑。虽然论文的主要焦点是视频编辑，但其核心部分依赖于LLM的应用，因此将其归类为“LLM应用”。` `影视制作` `自动化编辑`

> EditIQ: Automated Cinematic Editing of Static Wide-Angle Videos via Dialogue Interpretation and Saliency Cues

# 摘要

> 我们推出了EditIQ，一个全自动框架，用于对固定、广角、高分辨率摄像机捕捉的场景进行电影化编辑。EditIQ从静态画面中生成多个虚拟画面，模拟一组摄像师的工作。这些虚拟镜头（称为“毛片”）随后通过自动编辑算法组装，旨在为观众呈现最生动的场景内容。我们采用双管齐下的方法：（1）基于LLM的对话理解模块分析对话流程，（2）视觉显著性预测识别关键场景元素和镜头。我们将电影化视频编辑公式化为镜头选择的能量最小化问题，电影化约束决定镜头选择、过渡和连续性。EditIQ合成了美学和视觉上引人入胜的叙事表现，同时保持电影化的连贯性和流畅的观看体验。通过在BBC Old School数据集和十一部剧院表演视频上的心理物理学研究，我们展示了EditIQ相对于竞争基线的有效性。EditIQ的视频样本可在https://editiq-ave.github.io/查看。

> We present EditIQ, a completely automated framework for cinematically editing scenes captured via a stationary, large field-of-view and high-resolution camera. From the static camera feed, EditIQ initially generates multiple virtual feeds, emulating a team of cameramen. These virtual camera shots termed rushes are subsequently assembled using an automated editing algorithm, whose objective is to present the viewer with the most vivid scene content. To understand key scene elements and guide the editing process, we employ a two-pronged approach: (1) a large language model (LLM)-based dialogue understanding module to analyze conversational flow, coupled with (2) visual saliency prediction to identify meaningful scene elements and camera shots therefrom. We then formulate cinematic video editing as an energy minimization problem over shot selection, where cinematic constraints determine shot choices, transitions, and continuity. EditIQ synthesizes an aesthetically and visually compelling representation of the original narrative while maintaining cinematic coherence and a smooth viewing experience. Efficacy of EditIQ against competing baselines is demonstrated via a psychophysical study involving twenty participants on the BBC Old School dataset plus eleven theatre performance videos. Video samples from EditIQ can be found at https://editiq-ave.github.io/.

[Arxiv](https://arxiv.org/abs/2502.02172)