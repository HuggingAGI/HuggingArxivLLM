# 身份至关重要：借助LLM增强的逻辑推荐连接主题与社会角色

发布时间：2025年05月16日

`LLM应用` `推荐系统` `用户行为分析`

> Who You Are Matters: Bridging Topics and Social Roles via LLM-Enhanced Logical Recommendation

# 摘要

> 推荐系统通过分析用户特征和历史行为，帮助筛选出对用户有价值的内容或项目。主流方法采用学习排序范式，专注于发现和建模项目主题（如类别），并基于历史交互捕捉用户在这些主题上的偏好。然而，这一范式往往忽略了对用户特征及其社会角色的建模，而这些是影响相关兴趣和用户偏好转变的逻辑混杂因素。为此，我们引入了用户角色识别任务和行为逻辑建模任务，旨在显式建模用户角色，并学习项目主题与用户社会角色之间的逻辑关系。我们表明，通过一个高效的大规模语言模型（LLM）与推荐系统集成框架，我们可以显式地解决这些任务，为此我们提出了TagCF。一方面，利用LLM的世界知识和逻辑推理能力生成虚拟逻辑图，揭示用户动态和丰富的知识，从而增强推荐性能。另一方面，用户角色将用户行为逻辑与观察到的用户反馈对齐，深化我们对用户行为的理解。此外，我们还表明，提取的用户-项目逻辑图在经验上是一种通用知识，可以广泛受益于各种推荐任务，并在工业和多个公共数据集上进行实验以验证这一点。


> Recommender systems filter contents/items valuable to users by inferring preferences from user features and historical behaviors. Mainstream approaches follow the learning-to-rank paradigm, which focus on discovering and modeling item topics (e.g., categories), and capturing user preferences on these topics based on historical interactions. However, this paradigm often neglects the modeling of user characteristics and their social roles, which are logical confounders influencing the correlated interest and user preference transition. To bridge this gap, we introduce the user role identification task and the behavioral logic modeling task that aim to explicitly model user roles and learn the logical relations between item topics and user social roles. We show that it is possible to explicitly solve these tasks through an efficient integration framework of Large Language Model (LLM) and recommendation systems, for which we propose TagCF. On the one hand, the exploitation of the LLM's world knowledge and logic inference ability produces a virtual logic graph that reveals dynamic and expressive knowledge of users, augmenting the recommendation performance. On the other hand, the user role aligns the user behavioral logic with the observed user feedback, refining our understanding of user behaviors. Additionally, we also show that the extracted user-item logic graph is empirically a general knowledge that can benefit a wide range of recommendation tasks, and conduct experiments on industrial and several public datasets as verification.

[Arxiv](https://arxiv.org/abs/2505.10940)