# 三思而后断：双推理专家混合模型在多模态讽刺检测中的应用研究

发布时间：2025年07月06日

`LLM应用` `社交媒体分析` `视觉语言模型`

> Think Twice Before You Judge: Mixture of Dual Reasoning Experts for Multimodal Sarcasm Detection

# 摘要

> 多模态讽刺检测近年来因社交媒体上多媒体帖子的兴起而备受关注。理解带有讽刺的图文内容通常需要借助外部背景知识，如文化参考或常识推理。然而，现有模型在捕捉讽刺的深层原因方面表现有限，主要依赖于图像描述或物体属性等浅层线索。为此，我们提出了	extbf{MiDRE}（	extbf{Mi}xture of 	extbf{D}ual 	extbf{R}easoning 	extbf{E}xperts），该模型结合了用于检测图文对内部不协调的内部推理专家，以及通过链式思考提示从大型视觉语言模型生成结构化推理的外部推理专家。自适应门控机制动态调整两个专家的权重，选择最相关的推理路径。在两个基准数据集上的实验表明，MiDRE优于现有方法。定性分析表明，外部推理至关重要，即使偶尔存在噪声，也能为模型理解讽刺提供有价值的线索。

> Multimodal sarcasm detection has attracted growing interest due to the rise of multimedia posts on social media. Understanding sarcastic image-text posts often requires external contextual knowledge, such as cultural references or commonsense reasoning. However, existing models struggle to capture the deeper rationale behind sarcasm, relying mainly on shallow cues like image captions or object-attribute pairs from images. To address this, we propose \textbf{MiDRE} (\textbf{Mi}xture of \textbf{D}ual \textbf{R}easoning \textbf{E}xperts), which integrates an internal reasoning expert for detecting incongruities within the image-text pair and an external reasoning expert that utilizes structured rationales generated via Chain-of-Thought prompting to a Large Vision-Language Model. An adaptive gating mechanism dynamically weighs the two experts, selecting the most relevant reasoning path. Experiments on two benchmark datasets show that MiDRE achieves superior performance over baselines. Various qualitative analyses highlight the crucial role of external rationales, revealing that even when they are occasionally noisy, they provide valuable cues that guide the model toward a better understanding of sarcasm.

[Arxiv](https://arxiv.org/abs/2507.04458)