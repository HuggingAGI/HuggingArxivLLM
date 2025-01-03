# Adsorb-Agent: 利用大型语言模型代理自主识别稳定吸附配置

发布时间：2024年10月21日

`Agent

理由：这篇论文提出了一个名为 Adsorb-Agent 的基于大型语言模型（LLM）的代理，旨在高效推导系统特定的稳定吸附构型。Adsorb-Agent 利用 LLM 的内置知识和推理能力，减少初始构型数量并提高预测准确性。这表明该论文主要关注的是开发一个智能代理（Agent）来解决特定领域的问题，因此应归类为Agent。` `催化剂`

> Adsorb-Agent: Autonomous Identification of Stable Adsorption Configurations via Large Language Model Agent

# 摘要

> 吸附能是催化反应中的关键指标，能够高效筛选潜在催化剂。然而，确定吸附能需要比较多个吸附物-催化剂构型的能量，由于可能的构型数量庞大，计算量巨大。现有算法通常枚举吸附位点和构型，缺乏理论指导。本文提出 Adsorb-Agent，一个基于大型语言模型（LLM）的代理，旨在以最少人工干预高效推导系统特定的稳定吸附构型。Adsorb-Agent 利用内置知识和推理能力，显著减少初始构型数量，同时提高预测最小吸附能的准确性。我们通过 NNH-CuPd3 (111) 和 NNH-Mo3Pd (111) 两个系统展示了其在氮还原反应（NRR）中的性能，NRR 是哈伯-博世工艺的可持续替代方案。Adsorb-Agent 通过识别更低能量构型，减少初始设置，降低计算成本，同时提高准确性，优于传统“启发式”和“随机”算法，展现了其在加速催化剂发现中的潜力。

> Adsorption energy is a key reactivity descriptor in catalysis, enabling the efficient screening of potential catalysts. However, determining adsorption energy involves comparing the energies of multiple adsorbate-catalyst configurations, which is computationally demanding due to a large number of possible configurations. Current algorithmic approaches typically enumerate adsorption sites and configurations without leveraging theoretical insights to guide the initial setup. In this work, we present Adsorb-Agent, a Large Language Model (LLM) agent designed to efficiently derive system-specific stable adsorption configurations with minimal human intervention. Adsorb-Agent leverages built-in knowledge and emergent reasoning capabilities, significantly reducing the number of initial configurations required while improving accuracy in predicting the minimum adsorption energy. We demonstrate its performance using two example systems, NNH-CuPd3 (111) and NNH-Mo3Pd (111), for the Nitrogen Reduction Reaction (NRR), a sustainable alternative to the Haber-Bosch process. Adsorb-Agent outperforms conventional "heuristic" and "random" algorithms by identifying lower-energy configurations with fewer initial setups, reducing computational costs while enhancing accuracy. This highlights its potential to accelerate catalyst discovery.

[Arxiv](https://arxiv.org/abs/2410.16658)