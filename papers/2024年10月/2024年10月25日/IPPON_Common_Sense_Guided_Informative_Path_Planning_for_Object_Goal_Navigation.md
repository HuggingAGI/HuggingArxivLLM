# IPPON：针对对象目标导航的常识引导式有效路径规划

发布时间：2024年10月25日

`LLM应用` `机器人`

> IPPON: Common Sense Guided Informative Path Planning for Object Goal Navigation

# 摘要

> 在未探索的环境中，高效导航至物体是通用智能机器人的关键技能。对于物体目标导航问题，近来的方法采用了模块化策略，将经典的探索算法（尤其是前沿探索）与学习到的语义映射/探索模块相融合。本文引入了一种新颖的信息路径规划和 3D 物体概率映射方法。映射模块通过语义分割和贝叶斯滤波器来计算感兴趣物体的概率。此外，它还存储常见物体的概率，依据大型语言模型中的常识先验在语义上引导探索。当当前视点捕获到足够多被高置信度认定为感兴趣物体的体素时，规划器停止。虽然我们的规划器采用零样本方法，但在 2023 年 Habitat ObjectNav 挑战赛中，以路径长度加权成功（SPL）和软 SPL 来衡量，其性能达到了最先进水平，比其他成果高出 20%以上。而且，我们在真实机器人上验证了其有效性。项目网页：https://ippon-paper.github.io/

> Navigating efficiently to an object in an unexplored environment is a critical skill for general-purpose intelligent robots. Recent approaches to this object goal navigation problem have embraced a modular strategy, integrating classical exploration algorithms-notably frontier exploration-with a learned semantic mapping/exploration module. This paper introduces a novel informative path planning and 3D object probability mapping approach. The mapping module computes the probability of the object of interest through semantic segmentation and a Bayes filter. Additionally, it stores probabilities for common objects, which semantically guides the exploration based on common sense priors from a large language model. The planner terminates when the current viewpoint captures enough voxels identified with high confidence as the object of interest. Although our planner follows a zero-shot approach, it achieves state-of-the-art performance as measured by the Success weighted by Path Length (SPL) and Soft SPL in the Habitat ObjectNav Challenge 2023, outperforming other works by more than 20%. Furthermore, we validate its effectiveness on real robots. Project webpage: https://ippon-paper.github.io/

[Arxiv](https://arxiv.org/abs/2410.19697)