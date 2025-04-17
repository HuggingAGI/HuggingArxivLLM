# LANGTRAJ：语言引导的轨迹扩散模型与数据集

发布时间：2025年04月15日

`Agent` `自动驾驶`

> LANGTRAJ: Diffusion Model and Dataset for Language-Conditioned Trajectory Simulation

# 摘要

> 通过可控性评估自动驾驶汽车，我们能够在反事实或结构化场景中实现高效且安全的可扩展测试。我们推出了LangTraj，一种基于语言条件的场景扩散模型，专门用于模拟交通场景中所有代理的联合行为。通过自然语言输入进行条件设置，LangTraj不仅实现了对交互行为的灵活控制，还能生成细腻且现实的场景。与依赖领域特定指导函数的传统方法不同，LangTraj在训练过程中集成了语言条件设置，让交通模拟控制更加直观。我们还提出了一种专为扩散模型设计的新型闭环训练策略，旨在提升闭环模拟中的稳定性和现实性。为了支持基于语言条件的模拟，我们开发了Inter-Drive，一个包含多样化交互标签的大规模数据集，用于训练基于语言条件的扩散模型。我们的数据集建立在标注代理间交互和单个代理行为的可扩展管道之上，确保了丰富且多样的监督。在Waymo Motion数据集上的验证表明，LangTraj在现实性、语言可控性和基于语言的安全关键模拟方面表现优异，为灵活且可扩展的自动驾驶测试确立了新的范式。

> Evaluating autonomous vehicles with controllability enables scalable testing in counterfactual or structured settings, enhancing both efficiency and safety. We introduce LangTraj, a language-conditioned scene-diffusion model that simulates the joint behavior of all agents in traffic scenarios. By conditioning on natural language inputs, LangTraj provides flexible and intuitive control over interactive behaviors, generating nuanced and realistic scenarios. Unlike prior approaches that depend on domain-specific guidance functions, LangTraj incorporates language conditioning during training, facilitating more intuitive traffic simulation control. We propose a novel closed-loop training strategy for diffusion models, explicitly tailored to enhance stability and realism during closed-loop simulation. To support language-conditioned simulation, we develop Inter-Drive, a large-scale dataset with diverse and interactive labels for training language-conditioned diffusion models. Our dataset is built upon a scalable pipeline for annotating agent-agent interactions and single-agent behaviors, ensuring rich and varied supervision. Validated on the Waymo Motion Dataset, LangTraj demonstrates strong performance in realism, language controllability, and language-conditioned safety-critical simulation, establishing a new paradigm for flexible and scalable autonomous vehicle testing.

[Arxiv](https://arxiv.org/abs/2504.11521)