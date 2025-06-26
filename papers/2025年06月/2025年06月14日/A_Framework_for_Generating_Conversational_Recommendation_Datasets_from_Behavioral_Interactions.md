# # 构建基于行为交互的对话推荐数据集生成框架
构建基于行为交互的对话推荐数据集生成框架

发布时间：2025年06月14日

`由于摘要无法翻译，我无法对论文进行分类。请提供正确的摘要内容以便进行分类。` `无法提供标签` `因为摘要翻译失败` `无法获取论文内容。请提供正确的摘要。`

> A Framework for Generating Conversational Recommendation Datasets from Behavioral Interactions

# 摘要

> <翻译失败>

> Modern recommendation systems typically follow two complementary paradigms: collaborative filtering, which models long-term user preferences from historical interactions, and conversational recommendation systems (CRS), which interact with users in natural language to uncover immediate needs. Each captures a different dimension of user intent. While CRS models lack collaborative signals, leading to generic or poorly personalized suggestions, traditional recommenders lack mechanisms to interactively elicit immediate needs. Unifying these paradigms promises richer personalization but remains challenging due to the lack of large-scale conversational datasets grounded in real user behavior. We present ConvRecStudio, a framework that uses large language models (LLMs) to simulate realistic, multi-turn dialogs grounded in timestamped user-item interactions and reviews. ConvRecStudio follows a three-stage pipeline: (1) Temporal Profiling, which constructs user profiles and community-level item sentiment trajectories over fine-grained aspects; (2) Semantic Dialog Planning, which generates a structured plan using a DAG of flexible super-nodes; and (3) Multi-Turn Simulation, which instantiates the plan using paired LLM agents for the user and system, constrained by executional and behavioral fidelity checks. We apply ConvRecStudio to three domains -- MobileRec, Yelp, and Amazon Electronics -- producing over 12K multi-turn dialogs per dataset. Human and automatic evaluations confirm the naturalness, coherence, and behavioral grounding of the generated conversations. To demonstrate utility, we build a cross-attention transformer model that jointly encodes user history and dialog context, achieving gains in Hit@K and NDCG@K over baselines using either signal alone or naive fusion. Notably, our model achieves a 10.9% improvement in Hit@1 on Yelp over the strongest baseline.

[Arxiv](https://arxiv.org/abs/2506.17285)