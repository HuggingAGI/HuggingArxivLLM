# 针对数字广告战役中的影响者选择问题，我们采用 LLM 驱动的智能代理方案。这种方案利用 LLM 的强大能力，在影响者筛选过程中提供精准而高效的决策支持。

发布时间：2024年03月22日

`Agent` `社交网络`

> LLM-Driven Agents for Influencer Selection in Digital Advertising Campaigns

# 摘要

> 在数字化世界里，网红作为引领潮流的意见领袖，深刻影响着粉丝的看法与抉择。现今，广告行业常借助这一现象，依据深入的市场调研，让营销人员挑选适宜的网红为其产品背书。以往关于网红选取的研究大多采用简化社交动态复杂性的数值化方法，仅关注个体意见和互动的量化表示。随着大型语言模型（LLMs）技术的进步，我们有机会深入探究社交网络中的信息传播细节。为此，我们在本研究中创新推出“网红影响力模拟器”（IDS），利用LLM模拟技术助力推广者筛选并确定最合适的网红推广其产品。具体而言，我们先设计了一个基于网红与其粉丝互动度的预筛选模块，初步筛选出有潜力的网红候选人。接下来，针对这些候选人及其粉丝构建仿真环境，其中每位用户以基于LLM的智能体形式呈现，通过挖掘其互动历史描绘出个性特征及兴趣偏好。粉丝智能体会模拟其对网红广告可能产生的反应行为。最后，我们研发了一套基于粉丝反馈来精确预测哪些网红最能带动产品销售的排名指标。为了验证这套框架的有效性，我们采集了一个涵盖社交关系、发帖与评论内容以及用户行为的真实广告网络数据集，涉及六大类别的六款产品及其各自的推广网红。实验证明，IDS能够从众多候选网红中精准识别出合适人选，并通过具体的评论和态度分析，提供极具价值的洞见参考。

> In the digital world, influencers are pivotal as opinion leaders, shaping the views and choices of their influencees. Modern advertising often follows this trend, where marketers choose appropriate influencers for product endorsements, based on thorough market analysis. Previous studies on influencer selection have typically relied on numerical representations of individual opinions and interactions, a method that simplifies the intricacies of social dynamics. With the development of large language models (LLMs), we now have the opportunity to capture the nuanced exchanges of information within social networks. Hence, in this work, we first introduce an Influencer Dynamics Simulator (IDS), helping promoters identify and select the right influencers to market their products, based on LLM simulation. Concretely, we first propose an influencer-influencee engagement-based pre-selection module to screen potential influencer candidates. Subsequently, a simulation is constructed for these candidates and their influencees. Each user is represented as an LLM-based agent, drawing from their interaction history to deduce their profile and interests. The influencee agents will predict their behavior in response to influencer advertising. Finally, we develop a ranking metric designed to pinpoint influencers who are most likely to drive product purchases based on feedback from their influencees. To evaluate our framework, we collect a real-world advertising network dataset, including social relations, post and comment content, and user behaviors. Our dataset covers six products in diverse categories with their promoter influencers. Experiments show that IDS accurately identifies influencers from hundreds of candidates and provides valuable insights through detailed comments and specific attitudes.

[Arxiv](https://arxiv.org/abs/2403.15105)