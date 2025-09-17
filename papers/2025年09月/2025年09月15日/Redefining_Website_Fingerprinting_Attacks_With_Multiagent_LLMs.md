# 利用多智能体LLMs重新定义网站指纹攻击

发布时间：2025年09月15日

`Agent` `基础理论`

> Redefining Website Fingerprinting Attacks With Multiagent LLMs

# 摘要

> 网站指纹识别（WFP）借助深度学习模型对加密网络流量分类，从而推断用户访问过的网站。尽管这类方法在过去效果显著，却难以适用于现代网络环境。单页应用程序（SPAs）打破了网站由离散页面构成的传统范式，导致基于页面的分类方法失效；同时，脚本化浏览器生成的流量也缺乏真实用户会话中的行为丰富度。我们的研究发现，即使用户访问同一网站，行为也千差万别，由此产生的流量模式因人而异，差异显著。这种行为熵让WFP的难度远超以往认知，也凸显了构建更大规模、更多样化且更具代表性的数据集对实现稳健性能的必要性。为此，我们提出全新范式：不再受限于会话边界，而是采用连续流量段，并借助大型语言模型（LLM）智能体构建了可扩展的数据生成管道。这些多智能体系统通过协调决策与浏览器交互，模拟出符合角色设定的真实浏览行为，且成本仅为人工收集的1/3至1/5。我们基于30名真实用户浏览20个现代网站的流量，对九个最先进的WFP模型进行了评估，并对比了其在人工、脚本生成及LLM生成数据集上的训练效果。所有模型若基于脚本流量训练、再用人工数据测试，准确率均不足10%；相比之下，使用LLM生成流量训练的模型准确率可达80%左右，展现出对真实世界流量轨迹的优异泛化能力。研究结果表明，在现代WFP中，模型性能的瓶颈正逐渐转向数据质量；而可扩展、语义贴合的合成流量是捕捉真实用户行为复杂性的关键。

> Website Fingerprinting (WFP) uses deep learning models to classify encrypted network traffic to infer visited websites. While historically effective, prior methods fail to generalize to modern web environments. Single-page applications (SPAs) eliminate the paradigm of websites as sets of discrete pages, undermining page-based classification, and traffic from scripted browsers lacks the behavioral richness seen in real user sessions. Our study reveals that users exhibit highly diverse behaviors even on the same website, producing traffic patterns that vary significantly across individuals. This behavioral entropy makes WFP a harder problem than previously assumed and highlights the need for larger, more diverse, and representative datasets to achieve robust performance. To address this, we propose a new paradigm: we drop session-boundaries in favor of contiguous traffic segments and develop a scalable data generation pipeline using large language models (LLM) agents. These multi-agent systems coordinate decision-making and browser interaction to simulate realistic, persona-driven browsing behavior at 3--5x lower cost than human collection. We evaluate nine state-of-the-art WFP models on traffic from 20 modern websites browsed by 30 real users, and compare training performance across human, scripted, and LLM-generated datasets. All models achieve under 10\% accuracy when trained on scripted traffic and tested on human data. In contrast, LLM-generated traffic boosts accuracy into the 80\% range, demonstrating strong generalization to real-world traces. Our findings indicate that for modern WFP, model performance is increasingly bottlenecked by data quality, and that scalable, semantically grounded synthetic traffic is essential for capturing the complexity of real user behavior.

[Arxiv](https://arxiv.org/abs/2509.12462)