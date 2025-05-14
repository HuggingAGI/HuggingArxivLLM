# PosterO: 基于布局树结构构建，赋能语言模型实现通用内容感知布局生成

发布时间：2025年05月06日

`LLM应用` `图形设计`

> PosterO: Structuring Layout Trees to Enable Language Models in Generalized Content-Aware Layout Generation

# 摘要

> 海报设计中，内容感知布局生成对于自动排列视觉-文本元素至关重要。然而，现有研究虽专注于以图像为中心的增强，却忽视了布局多样性，难以应对形状多变的元素和多样化设计意图。为此，我们提出了以布局为中心的PosterO方法，利用大型语言模型（LLMs）中的隐含布局知识，实现多种用途的海报设计。具体而言， PosterO通过通用形状、设计意图向量化及分层节点表示，将布局数据集转化为SVG语言中的树结构。在推理过程中，PosterO结合上下文学习与意图对齐的示例选择，利用LLMs预测新的布局树。生成布局树后，我们可与LLMs对话编辑，轻松实现海报设计。实验结果表明，PosterO能为图像生成视觉吸引人的布局，在各项基准测试中达到最先进水平。为探索PosterO在通用场景下的潜力，我们构建了PStylish7，这是首个包含多用途海报和多样形状元素的数据集，为研究提供了具有挑战性的测试环境。

> In poster design, content-aware layout generation is crucial for automatically arranging visual-textual elements on the given image. With limited training data, existing work focused on image-centric enhancement. However, this neglects the diversity of layouts and fails to cope with shape-variant elements or diverse design intents in generalized settings. To this end, we proposed a layout-centric approach that leverages layout knowledge implicit in large language models (LLMs) to create posters for omnifarious purposes, hence the name PosterO. Specifically, it structures layouts from datasets as trees in SVG language by universal shape, design intent vectorization, and hierarchical node representation. Then, it applies LLMs during inference to predict new layout trees by in-context learning with intent-aligned example selection. After layout trees are generated, we can seamlessly realize them into poster designs by editing the chat with LLMs. Extensive experimental results have demonstrated that PosterO can generate visually appealing layouts for given images, achieving new state-of-the-art performance across various benchmarks. To further explore PosterO's abilities under the generalized settings, we built PStylish7, the first dataset with multi-purpose posters and various-shaped elements, further offering a challenging test for advanced research.

[Arxiv](https://arxiv.org/abs/2505.07843)