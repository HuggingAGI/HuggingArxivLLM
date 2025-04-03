# # Comment Staytime Prediction with LLM-enhanced Comment Understanding
# 基于LLM的评论理解增强的评论停留时长预测

发布时间：2025年04月02日

`LLM应用` `社交媒体` `推荐系统`

> Comment Staytime Prediction with LLM-enhanced Comment Understanding

# 摘要

> 在现代在线流媒体平台中，评论区对提升用户体验起着关键作用。理解用户在评论区的行为对于全面建模用户兴趣至关重要。用户参与度的一个关键指标是停留时长，即用户浏览和发布评论所花费的时间。现有的观看时长预测方法难以适应停留时长预测，忽视了用户与单条评论的互动及其相互关系。

在本文中，我们提出一个包含视频评论的微视频推荐数据集（命名为KuaiComt），该数据集从快手平台收集。相应地，我们提出一个基于大语言模型的评论理解（LCU）的评论停留时长预测框架。我们的框架利用大型语言模型（LLMs）强大的文本理解能力来理解评论的文本信息，同时还将细粒度的评论排序信号作为辅助任务。

该框架分为两个阶段：第一阶段，使用特定领域的任务对LLM进行微调，以连接视频和评论；第二阶段，我们将LLM的输出集成到预测模型中，并设计了两个评论排序辅助任务，以更好地理解用户偏好。广泛的离线实验验证了我们框架的有效性，在评论停留时长预测任务上取得了显著改进。此外，在线A/B测试进一步验证了在工业场景中的实际收益。我们的数据集KuaiComt（https://github.com/lyingCS/KuaiComt.github.io）和LCU代码（https://github.com/lyingCS/LCU）已全部公开发布。

> In modern online streaming platforms, the comments section plays a critical role in enhancing the overall user experience. Understanding user behavior within the comments section is essential for comprehensive user interest modeling. A key factor of user engagement is staytime, which refers to the amount of time that users browse and post comments. Existing watchtime prediction methods struggle to adapt to staytime prediction, overlooking interactions with individual comments and their interrelation. In this paper, we present a micro-video recommendation dataset with video comments (named as KuaiComt) which is collected from Kuaishou platform. correspondingly, we propose a practical framework for comment staytime prediction with LLM-enhanced Comment Understanding (LCU). Our framework leverages the strong text comprehension capabilities of large language models (LLMs) to understand textual information of comments, while also incorporating fine-grained comment ranking signals as auxiliary tasks. The framework is two-staged: first, the LLM is fine-tuned using domain-specific tasks to bridge the video and the comments; second, we incorporate the LLM outputs into the prediction model and design two comment ranking auxiliary tasks to better understand user preference. Extensive offline experiments demonstrate the effectiveness of our framework, showing significant improvements on the task of comment staytime prediction. Additionally, online A/B testing further validates the practical benefits on industrial scenario. Our dataset KuaiComt (https://github.com/lyingCS/KuaiComt.github.io) and code for LCU (https://github.com/lyingCS/LCU) are fully released.

[Arxiv](https://arxiv.org/abs/2504.01602)