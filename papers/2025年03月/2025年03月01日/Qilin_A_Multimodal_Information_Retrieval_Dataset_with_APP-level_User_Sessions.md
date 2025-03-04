# # 摘要
麒麟数据集是一个多模态数据集，包含来自多个APP的真实用户会话，可用于研究跨APP的信息检索。

发布时间：2025年03月01日

`RAG` `社交网络` `搜索与推荐`

> Qilin: A Multimodal Information Retrieval Dataset with APP-level User Sessions

# 摘要

> 用户生成内容（UGC）社区，尤其是多模态内容社区，通过整合视觉与文本信息提升用户体验。近年来，如何在复杂系统中优化搜索与推荐（S&R）服务的用户体验成为学术界与工业界关注的焦点。然而，高质量数据集的匮乏阻碍了多模态搜索与推荐研究的进展。为应对这一挑战，我们推出全新多模态信息检索数据集——Qilin。该数据集源自小红书，一个拥有3亿月活用户、搜索渗透率超70%的社交平台。相较于现有数据集，	extsf{Qilin} 包含了异构结果的完整用户会话，如图文笔记、视频笔记、商业笔记和直接答案，助力多模态神经检索模型的跨任务开发。为深入理解用户满意度并分析异构行为，我们还收集了丰富的应用级上下文信号和真实用户反馈。特别地，Qilin 包含了用户 favor 的答案及其引用结果，针对触发深度查询解答（DQA）模块的搜索请求。这不仅支持检索增强生成（RAG）流水线的训练与评估，还揭示了此类模块对用户搜索行为的影响。通过深入分析与实验，我们为优化搜索与推荐系统提供了宝贵见解。我们期待，	extsf{Qilin} 将在未来助力多模态内容平台的搜索与推荐服务发展。


> User-generated content (UGC) communities, especially those featuring multimodal content, improve user experiences by integrating visual and textual information into results (or items). The challenge of improving user experiences in complex systems with search and recommendation (S\&R) services has drawn significant attention from both academia and industry these years. However, the lack of high-quality datasets has limited the research progress on multimodal S\&R. To address the growing need for developing better S\&R services, we present a novel multimodal information retrieval dataset in this paper, namely Qilin. The dataset is collected from Xiaohongshu, a popular social platform with over 300 million monthly active users and an average search penetration rate of over 70\%. In contrast to existing datasets, \textsf{Qilin} offers a comprehensive collection of user sessions with heterogeneous results like image-text notes, video notes, commercial notes, and direct answers, facilitating the development of advanced multimodal neural retrieval models across diverse task settings. To better model user satisfaction and support the analysis of heterogeneous user behaviors, we also collect extensive APP-level contextual signals and genuine user feedback. Notably, Qilin contains user-favored answers and their referred results for search requests triggering the Deep Query Answering (DQA) module. This allows not only the training \& evaluation of a Retrieval-augmented Generation (RAG) pipeline, but also the exploration of how such a module would affect users' search behavior. Through comprehensive analysis and experiments, we provide interesting findings and insights for further improving S\&R systems. We hope that \textsf{Qilin} will significantly contribute to the advancement of multimodal content platforms with S\&R services in the future.

[Arxiv](https://arxiv.org/abs/2503.00501)