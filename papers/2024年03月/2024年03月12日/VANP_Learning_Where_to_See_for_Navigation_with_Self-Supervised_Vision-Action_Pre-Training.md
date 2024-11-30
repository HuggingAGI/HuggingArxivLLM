# VANP 方法利用自我监督的视觉-动作预训练技术，教导模型在进行导航时学会自主发现关键观察点，从而提升导航能力。

发布时间：2024年03月12日

`Agent` `机器人` `计算机视觉`

> VANP: Learning Where to See for Navigation with Self-Supervised Vision-Action Pre-Training

# 摘要

> 人类在穿越人群时能凭借对导航关键视觉区域的关注而避免碰撞，表现出色。然而，当前多数机器人视觉导航技术主要依赖于预训练的深度学习模型，这类模型虽重视显著物体识别，却未必与实际导航需求紧密关联，有时甚至会引入误导。有别于此，另一种途径是耗费大量计算资源从头训练专精于导航的模型。尽管自我监督学习已在计算机视觉和自然语言处理中引发革命，但在如何为机器人导航设计有效自我监督信号方面尚存在难题，故该领域的探索仍未深入。基于以上思考，我们创新性地提出了视觉导航预训练的自监督视觉-动作模型——VANP。它并不追求识别有助于分类或检测任务的显著物体，而是专注于挖掘与导航任务密切相关的特定视觉区域。为此，VANP 利用历史视觉观测序列、未来动作计划以及目标图像构建自我监督信号，并借助两个小巧的Transformer编码器进行嵌入表示。进一步地，VANP 通过运用互信息最大化的目标函数强化嵌入间的联系。实验显示，VANP 提取的特征大多契合人类直观的导航认知。而且，VANP 能在减少一半训练时间的前提下，取得与端到端训练模型相媲美的效果；更加惊人的是，仅利用0.08%的ImageNet全监督数据集规模数据，VANP 的表现就可与完全基于该数据集训练出的模型不分伯仲。

> Humans excel at efficiently navigating through crowds without collision by focusing on specific visual regions relevant to navigation. However, most robotic visual navigation methods rely on deep learning models pre-trained on vision tasks, which prioritize salient objects -- not necessarily relevant to navigation and potentially misleading. Alternative approaches train specialized navigation models from scratch, requiring significant computation. On the other hand, self-supervised learning has revolutionized computer vision and natural language processing, but its application to robotic navigation remains underexplored due to the difficulty of defining effective self-supervision signals. Motivated by these observations, in this work, we propose a Self-Supervised Vision-Action Model for Visual Navigation Pre-Training (VANP). Instead of detecting salient objects that are beneficial for tasks such as classification or detection, VANP learns to focus only on specific visual regions that are relevant to the navigation task. To achieve this, VANP uses a history of visual observations, future actions, and a goal image for self-supervision, and embeds them using two small Transformer Encoders. Then, VANP maximizes the information between the embeddings by using a mutual information maximization objective function. We demonstrate that most VANP-extracted features match with human navigation intuition. VANP achieves comparable performance as models learned end-to-end with half the training time and models trained on a large-scale, fully supervised dataset, i.e., ImageNet, with only 0.08% data.

[Arxiv](https://arxiv.org/abs/2403.08109)