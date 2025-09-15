# 结合人口普查与土地利用数据，利用大型语言模型生成个人旅行日记

发布时间：2025年09月07日

`LLM应用` `交通运输`

> Generating Individual Travel Diaries Using Large Language Models Informed by Census and Land-Use Data

# 摘要

> 本研究提出了一种基于大型语言模型（LLM）的方案，用于在基于智能体的交通模型中生成个人旅行日记。传统方法通常依赖大量专有家庭旅行调查，而本研究提出的方法则从开源的美国社区调查（ACS）和智能位置数据库（SLD）数据中随机生成角色，再通过直接提示合成日记。研究的一大创新点是提出了“个体-群体真实性评分”：这是一项由四个指标（行程数量评分、时间间隔评分、目的评分和交通方式评分）构成的综合评分，已通过康涅狄格州全州交通研究（CSTS）日记验证，并在人口统计变量上实现匹配。验证过程采用詹森-香农散度来衡量生成日记与真实日记的分布相似性。与在验证集上校准的经典方法（行程生成用负二项分布，交通方式/目的用多项Logit模型）相比，LLM生成的日记整体真实性相当（LLM均值：0.485 vs. 经典方法：0.455）。其中，LLM在行程目的判断上表现突出，且一致性更高（真实性评分分布更集中）；经典模型则在行程数量和活动持续时间的数值估计上更胜一筹。聚合验证进一步证实了LLM的统计代表性（LLM均值：0.612 vs. 经典方法：0.435），不仅证明了LLM的零样本可行性，还为未来的合成日记评估系统奠定了可量化的日记真实性指标。

> This study introduces a Large Language Model (LLM) scheme for generating individual travel diaries in agent-based transportation models. While traditional approaches rely on large quantities of proprietary household travel surveys, the method presented in this study generates personas stochastically from open-source American Community Survey (ACS) and Smart Location Database (SLD) data, then synthesizes diaries through direct prompting. This study features a novel one-to-cohort realism score: a composite of four metrics (Trip Count Score, Interval Score, Purpose Score, and Mode Score) validated against the Connecticut Statewide Transportation Study (CSTS) diaries, matched across demographic variables. The validation utilizes Jensen-Shannon Divergence to measure distributional similarities between generated and real diaries. When compared to diaries generated with classical methods (Negative Binomial for trip generation; Multinomial Logit for mode/purpose) calibrated on the validation set, LLM-generated diaries achieve comparable overall realism (LLM mean: 0.485 vs. 0.455). The LLM excels in determining trip purpose and demonstrates greater consistency (narrower realism score distribution), while classical models lead in numerical estimates of trip count and activity duration. Aggregate validation confirms the LLM's statistical representativeness (LLM mean: 0.612 vs. 0.435), demonstrating LLM's zero-shot viability and establishing a quantifiable metric of diary realism for future synthetic diary evaluation systems.

[Arxiv](https://arxiv.org/abs/2509.09710)