# 基于视觉语言反馈的人类网格恢复适应

发布时间：2025年02月06日

`LLM应用

理由：该论文摘要提到利用大型视觉语言模型（VLMs）生成交互式身体描述，并将其应用于单目人体网格恢复任务。这表明该研究是将大型语言模型（LLM）应用于具体的视觉任务中，属于LLM在实际应用中的使用，因此分类为LLM应用。` `计算机视觉` `人体建模`

> Adapting Human Mesh Recovery with Vision-Language Feedback

# 摘要

> # 摘要
人体网格恢复可通过回归或优化方法实现。回归模型姿态精度高，但缺乏2D-3D对应关系，难以精确对齐模型与图像。优化方法虽能对齐3D模型与2D观测，却易陷入局部最小值和深度模糊。本研究利用大型视觉语言模型（VLMs）生成交互式身体描述，作为隐式约束增强3D感知并限制优化空间。我们将单目人体网格恢复任务定义为分布适应任务，结合2D观测与语言描述。为弥合文本与3D姿态的差距，先训练文本编码器与姿态VQ-VAE，通过对比学习将文本与姿态对齐到共享潜在空间。随后，采用基于扩散的框架，利用2D观测和文本描述的梯度优化初始参数。最终，模型生成具有准确3D感知和图像一致性的姿态。多基准实验结果验证了其有效性，代码将公开。

> Human mesh recovery can be approached using either regression-based or optimization-based methods. Regression models achieve high pose accuracy but struggle with model-to-image alignment due to the lack of explicit 2D-3D correspondences. In contrast, optimization-based methods align 3D models to 2D observations but are prone to local minima and depth ambiguity. In this work, we leverage large vision-language models (VLMs) to generate interactive body part descriptions, which serve as implicit constraints to enhance 3D perception and limit the optimization space. Specifically, we formulate monocular human mesh recovery as a distribution adaptation task by integrating both 2D observations and language descriptions. To bridge the gap between text and 3D pose signals, we first train a text encoder and a pose VQ-VAE, aligning texts to body poses in a shared latent space using contrastive learning. Subsequently, we employ a diffusion-based framework to refine the initial parameters guided by gradients derived from both 2D observations and text descriptions. Finally, the model can produce poses with accurate 3D perception and image consistency. Experimental results on multiple benchmarks validate its effectiveness. The code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2502.03836)