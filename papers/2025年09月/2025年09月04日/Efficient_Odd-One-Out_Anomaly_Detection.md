# 高效的离群点异常检测

发布时间：2025年09月04日

`其他` `基础理论`

> Efficient Odd-One-Out Anomaly Detection

# 摘要

> 最近新提出的“格格不入”异常检测任务，旨在识别多物体场景中外观异常的实例。这一问题给现代深度学习模型带来了多重挑战，要求模型具备跨多视角的空间推理能力和关系推理能力，以理解上下文并在不同物体类别与布局间实现泛化。我们认为，解决这些挑战时必须兼顾效率。为此，我们提出了一种基于DINO的模型，与当前最先进的模型相比，该模型参数数量减少三分之一，训练时间缩短至原来的三分之一，同时性能仍具竞争力。我们的实验评估还引入了多模态大型语言模型作为基线，揭示了其在结构化视觉推理任务中目前存在的局限性。项目页面详见https://silviochito.github.io/EfficientOddOneOut/。

> The recently introduced odd-one-out anomaly detection task involves identifying the odd-looking instances within a multi-object scene. This problem presents several challenges for modern deep learning models, demanding spatial reasoning across multiple views and relational reasoning to understand context and generalize across varying object categories and layouts. We argue that these challenges must be addressed with efficiency in mind. To this end, we propose a DINO-based model that reduces the number of parameters by one third and shortens training time by a factor of three compared to the current state-of-the-art, while maintaining competitive performance. Our experimental evaluation also introduces a Multimodal Large Language Model baseline, providing insights into its current limitations in structured visual reasoning tasks. The project page can be found at https://silviochito.github.io/EfficientOddOneOut/

[Arxiv](https://arxiv.org/abs/2509.04326)