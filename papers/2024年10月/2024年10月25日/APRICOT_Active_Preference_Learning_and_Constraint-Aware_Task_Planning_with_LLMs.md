# APRICOT：基于 LLMs 的主动偏好学习与约束感知任务规划

发布时间：2024年10月25日

`LLM应用` `机器人` `家庭服务`

> APRICOT: Active Preference Learning and Constraint-Aware Task Planning with LLMs

# 摘要

> 家庭机器人在执行个性化任务时，必须巧妙地平衡好用户偏好和环境可供性。我们聚焦于受限空间内的组织任务，比如把物品放进冰箱，此时放置偏好会与物理限制产生冲突。机器人得依据少量的演示来推断用户偏好，这比起让用户广泛定义所有要求要容易得多。尽管近期的工作借助大型语言模型（LLMs）从用户演示中学习偏好，但仍面临两个根本挑战。其一，解读用户行为存在固有模糊性，因为单个观察到的行为往往能由多种偏好来解释。其二，由于环境中的几何限制，并非所有用户偏好都切实可行。为应对这些挑战，我们推出了 APRICOT，这是一种将基于 LLM 的贝叶斯主动偏好学习与约束感知任务规划相融合的新颖方法。APRICOT 通过主动向用户询问来优化其生成的偏好，并动态调整计划以遵循环境约束。我们在多种组织任务的数据集上对 APRICOT 进行了评估，并在实际场景中证明了其有效性，在偏好满足和计划可行性方面均有显著提升。该项目网站为 https://portal-cornell.github.io/apricot/

> Home robots performing personalized tasks must adeptly balance user preferences with environmental affordances. We focus on organization tasks within constrained spaces, such as arranging items into a refrigerator, where preferences for placement collide with physical limitations. The robot must infer user preferences based on a small set of demonstrations, which is easier for users to provide than extensively defining all their requirements. While recent works use Large Language Models (LLMs) to learn preferences from user demonstrations, they encounter two fundamental challenges. First, there is inherent ambiguity in interpreting user actions, as multiple preferences can often explain a single observed behavior. Second, not all user preferences are practically feasible due to geometric constraints in the environment. To address these challenges, we introduce APRICOT, a novel approach that merges LLM-based Bayesian active preference learning with constraint-aware task planning. APRICOT refines its generated preferences by actively querying the user and dynamically adapts its plan to respect environmental constraints. We evaluate APRICOT on a dataset of diverse organization tasks and demonstrate its effectiveness in real-world scenarios, showing significant improvements in both preference satisfaction and plan feasibility. The project website is at https://portal-cornell.github.io/apricot/

[Arxiv](https://arxiv.org/abs/2410.19656)