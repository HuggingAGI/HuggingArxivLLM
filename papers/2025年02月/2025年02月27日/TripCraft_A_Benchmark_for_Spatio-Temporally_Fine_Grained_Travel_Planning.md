# 旅行匠：时空精细旅行规划基准测试

发布时间：2025年02月27日

`LLM应用`

> TripCraft: A Benchmark for Spatio-Temporally Fine Grained Travel Planning

# 摘要

> 近期，探查大型语言模型（LLMs）的研究揭示了其作为个性化旅行规划助手的潜在能力，然而现有基准在现实世界中的适用性仍然有限。现有的数据集，如TravelPlanner和TravelPlanner+，存在对半合成数据的依赖、空间一致性问题以及缺乏关键旅行约束，使其难以胜任实际行程规划任务。为填补这些空白，我们引入了TripCraft，这是一个时空一致的旅行规划数据集，整合了现实世界的约束条件，包括公共交通时刻表、活动可用性、多样化的景点类别以及用户角色，以实现更个性化的体验。为了超越现有的二元验证方法评估LLM生成的计划，我们提出了五个连续评估指标：时间餐饮得分、时间景点得分、空间得分、顺序得分和角色得分，这些指标从多个维度评估行程质量。在7天场景下，我们的参数化设置显著提升了餐饮安排，使时间餐饮得分从61%提升至80%。TripCraft为LLM驱动的个性化旅行规划设立了新基准，提供了更现实、更具约束感知能力的行程生成框架。数据集和代码库将在接受后公开发布。

> Recent advancements in probing Large Language Models (LLMs) have explored their latent potential as personalized travel planning agents, yet existing benchmarks remain limited in real world applicability. Existing datasets, such as TravelPlanner and TravelPlanner+, suffer from semi synthetic data reliance, spatial inconsistencies, and a lack of key travel constraints, making them inadequate for practical itinerary generation. To address these gaps, we introduce TripCraft, a spatiotemporally coherent travel planning dataset that integrates real world constraints, including public transit schedules, event availability, diverse attraction categories, and user personas for enhanced personalization. To evaluate LLM generated plans beyond existing binary validation methods, we propose five continuous evaluation metrics, namely Temporal Meal Score, Temporal Attraction Score, Spatial Score, Ordering Score, and Persona Score which assess itinerary quality across multiple dimensions. Our parameter informed setting significantly enhances meal scheduling, improving the Temporal Meal Score from 61% to 80% in a 7 day scenario. TripCraft establishes a new benchmark for LLM driven personalized travel planning, offering a more realistic, constraint aware framework for itinerary generation. Dataset and Codebase will be made publicly available upon acceptance.

[Arxiv](https://arxiv.org/abs/2502.20508)