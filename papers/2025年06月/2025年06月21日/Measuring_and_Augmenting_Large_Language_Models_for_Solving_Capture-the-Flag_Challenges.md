# 衡量与增强大型语言模型，解决夺旗挑战

发布时间：2025年06月21日

`LLM应用` `网络安全` `人工智能`

> Measuring and Augmenting Large Language Models for Solving Capture-the-Flag Challenges

# 摘要

> # 摘要  
夺旗赛（CTF）竞赛对于网络安全教育和培训至关重要。随着大型语言模型（LLMs）的发展，人们越来越关注它们在自动化解决CTF挑战方面的能力。例如，DARPA自2023年起组织了AIxCC竞赛，旨在推动AI驱动的自动化攻防技术。然而，这需要结合多种能力，从知识到推理，再到行动。

在本文中，我们强调了技术知识在解决CTF问题中的重要性，并特意构建了一个专注于此的基准测试集CTFKnow，包含3992道问题，以衡量LLMs在这一核心方面的表现。我们的研究为评估LLMs理解CTF知识并将其应用于解决CTF挑战的能力提供了一种专注且创新的测量方法。我们的关键发现表明，尽管LLMs拥有丰富的技术知识，但在准确应用这些知识到具体场景以及根据CTF环境的反馈调整策略方面表现欠佳。

基于这项测量研究的洞察，我们提出了CTFAgent，这是一个全新的LLM驱动框架，旨在提升CTF问题解决能力。CTFAgent引入了两个新模块：两阶段增强检索生成（RAG）和交互式环境增强，分别提升了LLMs在CTF中的技术知识和漏洞利用能力。我们的实验结果显示，在两个流行的CTF数据集上，CTFAgent实现了超过80%的性能提升。此外，在最近由CMU主办的picoCTF2024竞赛中，CTFAgent在近7000支参赛队伍中名列前23.6%。这反映了我们的测量研究的价值以及我们的框架在提升LLMs解决CTF问题能力方面的潜力。

> Capture-the-Flag (CTF) competitions are crucial for cybersecurity education and training. As large language models (LLMs) evolve, there is increasing interest in their ability to automate CTF challenge solving. For example, DARPA has organized the AIxCC competition since 2023 to advance AI-powered automated offense and defense. However, this demands a combination of multiple abilities, from knowledge to reasoning and further to actions. In this paper, we highlight the importance of technical knowledge in solving CTF problems and deliberately construct a focused benchmark, CTFKnow, with 3,992 questions to measure LLMs' performance in this core aspect. Our study offers a focused and innovative measurement of LLMs' capability in understanding CTF knowledge and applying it to solve CTF challenges. Our key findings reveal that while LLMs possess substantial technical knowledge, they falter in accurately applying this knowledge to specific scenarios and adapting their strategies based on feedback from the CTF environment.
  Based on insights derived from this measurement study, we propose CTFAgent, a novel LLM-driven framework for advancing CTF problem-solving. CTFAgent introduces two new modules: two-stage Retrieval Augmented Generation (RAG) and interactive Environmental Augmentation, which enhance LLMs' technical knowledge and vulnerability exploitation on CTF, respectively. Our experimental results show that, on two popular CTF datasets, CTFAgent both achieves over 80% performance improvement. Moreover, in the recent picoCTF2024 hosted by CMU, CTFAgent ranked in the top 23.6% of nearly 7,000 participating teams. This reflects the benefit of our measurement study and the potential of our framework in advancing LLMs' capabilities in CTF problem-solving.

[Arxiv](https://arxiv.org/abs/2506.17644)