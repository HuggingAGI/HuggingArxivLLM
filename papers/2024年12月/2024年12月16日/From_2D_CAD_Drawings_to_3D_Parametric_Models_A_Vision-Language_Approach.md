# 从 2D CAD 图纸迈向 3D 参数化模型：一种视觉语言途径

发布时间：2024年12月16日

`LLM应用` `计算机辅助设计` `制造业`

> From 2D CAD Drawings to 3D Parametric Models: A Vision-Language Approach

# 摘要

> 在本文中，我们推出了 CAD2Program，这是一种由 2D CAD 图纸重构 3D 参数模型的新办法。我们的方法受视觉语言模型（VLMs）近期成果的启发，有别于依赖特定任务数据表征和/或算法的传统手段。具体而言，在输入端，不管原始格式怎样，我们都把 2D CAD 图纸视作光栅图像，并用标准的 ViT 模型对其编码。我们发现，这种编码方案相比基于矢量图形输入的现有方法，性能颇具竞争力，而且对 2D 图纸的限制大幅减少。在输出端，我们的方法以自回归形式预测用文本描述 3D 参数模型的通用语言。相较于其他用于 CAD 且使用具有固定大小插槽的特定领域序列表示的序列建模方法，我们基于文本的表示更具灵活性，能够轻松拓展到任意几何实体以及语义或功能属性。在大规模橱柜模型数据集上的实验结果表明了我们方法的有效性。

> In this paper, we present CAD2Program, a new method for reconstructing 3D parametric models from 2D CAD drawings. Our proposed method is inspired by recent successes in vision-language models (VLMs), and departs from traditional methods which rely on task-specific data representations and/or algorithms. Specifically, on the input side, we simply treat the 2D CAD drawing as a raster image, regardless of its original format, and encode the image with a standard ViT model. We show that such an encoding scheme achieves competitive performance against existing methods that operate on vector-graphics inputs, while imposing substantially fewer restrictions on the 2D drawings. On the output side, our method auto-regressively predicts a general-purpose language describing 3D parametric models in text form. Compared to other sequence modeling methods for CAD which use domain-specific sequence representations with fixed-size slots, our text-based representation is more flexible, and can be easily extended to arbitrary geometric entities and semantic or functional properties. Experimental results on a large-scale dataset of cabinet models demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2412.11892)