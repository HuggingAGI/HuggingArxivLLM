# # 关于应用控制设计的标准性能准则：PID、MPC还是机器学习控制器？

发布时间：2025年03月18日

`其他` `控制理论` `自动化`

> On the Standard Performance Criteria for Applied Control Design: PID, MPC or Machine Learning Controller?

# 摘要

> 传统控制理论在基础与复杂系统中的应用已高度成熟，涵盖空中、海洋、地面车辆，以及日常生活中广泛应用的机器人、化工、交通和电气系统。新兴的数据驱动方法、大型语言模型（LLMs）和基于AI的控制器时代，并非表明传统控制理论存在缺陷，而是旨在减少对模型和不确定性的依赖，应对日益复杂的系统，并可能实现接近人类水平的决策能力。这场革命融合了计算机科学、机器学习、生物学和经典控制的知识，产生了具有前景的算法，但尚未在现实世界中得到广泛应用。尽管控制理论已相当成熟且存在多种性能标准，仍缺乏标准化的测试、评估、验证和确认（$V\&V$）算法的指标。这一差距可能导致某些算法在某些方面虽达到最优，却无法满足实际应用需求，引发文献中的讨论。一个控制器要在实际应用中成功，必须满足三个关键类别的性能指标：跟踪质量、控制努力（能源消耗）和鲁棒性。本文从应用角度出发，提出并整合了用于测试和分析控制系统的标准性能标准，旨在为研究人员和学生提供参考。所提出的框架确保了黑箱算法在设计后具备实际应用性，并与现代数据分析和$V\&V$视角保持一致，以防止资源分配到影响有限或声明不精确的系统中。

> The traditional control theory and its application to basic and complex systems have reached an advanced level of maturity. This includes aerial, marine, and ground vehicles, as well as robotics, chemical, transportation, and electrical systems widely used in our daily lives. The emerging era of data-driven methods, Large Language Models (LLMs), and AI-based controllers does not indicate a weakness in well-established control theory. Instead, it aims to reduce dependence on models and uncertainties, address increasingly complex systems, and potentially achieve decision-making capabilities comparable to human-level performance. This revolution integrates knowledge from computer science, machine learning, biology, and classical control, producing promising algorithms that are yet to demonstrate widespread real-world applicability. Despite the maturity of control theory and the presence of various performance criteria, there is still a lack of standardised metrics for testing, evaluation, Verification and Validation ($V\&V$) of algorithms. This gap can lead to algorithms that, while optimal in certain aspects, may fall short of practical implementation, sparking debates within the literature. For a controller to succeed in real-world applications, it must satisfy three key categories of performance metrics: tracking quality, control effort (energy consumption), and robustness. This paper rather takes an applied perspective, proposing and consolidating standard performance criteria for testing and analysing control systems, intended for researchers and students. The proposed framework ensures the post-design applicability of a black-box algorithm, aligning with modern data analysis and $V\&V$ perspectives to prevent resource allocation to systems with limited impact or imprecise claims.

[Arxiv](https://arxiv.org/abs/2503.14379)