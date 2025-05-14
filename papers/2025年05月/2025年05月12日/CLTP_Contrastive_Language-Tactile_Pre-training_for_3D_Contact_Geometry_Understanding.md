# CLTP：对比语言-触觉预训练助力三维接触几何理解

发布时间：2025年05月12日

`LLM应用` `触觉感知` `机器人`

> CLTP: Contrastive Language-Tactile Pre-training for 3D Contact Geometry Understanding

# 摘要

> 触觉感知与视觉-语言模型（VLMs）的结合近期展现出机器人多模态感知的非凡潜力。然而，现有触觉描述仍局限于纹理等浅层属性，忽视了机器人操作中至关重要的接触状态。为填补这一空白，我们提出了CLTP，一个直观且有效的语言触觉预训练框架。该框架能够在多种接触场景下将触觉3D点云与自然语言对齐，从而实现面向接触密集型操作任务的接触状态感知触觉语言理解。我们首先构建了一个包含5万多对触觉3D点云-语言的新型数据集，其中描述明确捕捉了多维接触状态（如接触位置、形状和力）从触觉传感器的独特视角。CLTP通过预对齐且冻结的视觉-语言特征空间，实现了整体的文本和触觉模态的连接。实验结果表明，CLTP在零样本3D分类、接触状态分类以及触觉3D大语言模型（LLM）交互三项任务中均表现出色。据我们所知，这是首个从接触状态视角对齐触觉和语言表示以支持操作任务的研究，为触觉-语言-动作模型学习提供了巨大潜力。代码和数据集已开源，地址为https://sites.google.com/view/cltp/。

> Recent advancements in integrating tactile sensing with vision-language models (VLMs) have demonstrated remarkable potential for robotic multimodal perception. However, existing tactile descriptions remain limited to superficial attributes like texture, neglecting critical contact states essential for robotic manipulation. To bridge this gap, we propose CLTP, an intuitive and effective language tactile pretraining framework that aligns tactile 3D point clouds with natural language in various contact scenarios, thus enabling contact-state-aware tactile language understanding for contact-rich manipulation tasks. We first collect a novel dataset of 50k+ tactile 3D point cloud-language pairs, where descriptions explicitly capture multidimensional contact states (e.g., contact location, shape, and force) from the tactile sensor's perspective. CLTP leverages a pre-aligned and frozen vision-language feature space to bridge holistic textual and tactile modalities. Experiments validate its superiority in three downstream tasks: zero-shot 3D classification, contact state classification, and tactile 3D large language model (LLM) interaction. To the best of our knowledge, this is the first study to align tactile and language representations from the contact state perspective for manipulation tasks, providing great potential for tactile-language-action model learning. Code and datasets are open-sourced at https://sites.google.com/view/cltp/.

[Arxiv](https://arxiv.org/abs/2505.08194)