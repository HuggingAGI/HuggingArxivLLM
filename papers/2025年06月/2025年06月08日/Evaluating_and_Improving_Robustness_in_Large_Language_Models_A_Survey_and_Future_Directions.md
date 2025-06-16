# 大型语言模型稳健性研究：提升与评估的综述与未来展望

发布时间：2025年06月08日

`LLM理论` `鲁棒性`

> Evaluating and Improving Robustness in Large Language Models: A Survey and Future Directions

# 摘要

> 大型语言模型（LLMs）凭借其强大的理解和生成自然语言的能力，近年来备受关注。随着其在智能体、具身智能等领域的快速发展和广泛应用，LLMs的鲁棒性问题也日益受到重视。作为众多AI应用的核心引擎，LLMs的鲁棒性不仅要求模型能够生成一致的内容，还要求其在面对有毒提示、有限噪声域数据、领域外（OOD）应用等意外场景时，确保生成内容的正确性和稳定性。在这篇综述论文中，我们对LLMs的鲁棒性进行了全面梳理，旨在为该领域提供系统化的概念框架和方法论，并助力相关研究的发展。具体而言，我们首先给出了LLMs鲁棒性的正式定义，并介绍了本综述的收集和整理方法。随后，基于扰动输入的类型，我们从以下几个维度展开探讨：1) 对抗鲁棒性：针对提示被故意篡改的问题，如噪声提示、长上下文、数据攻击等；2) OOD鲁棒性：应对真实世界中的意外应用场景，如OOD检测、零样本迁移、幻觉等；3) 鲁棒性评估：汇总用于验证LLMs鲁棒性的新数据集、指标和工具。在对各维度的代表性工作进行回顾后，我们进一步探讨了该领域的未来研究方向和潜在机遇。此外，我们还整理了相关研究，并创建了一个便于查阅的项目（https://github.com/zhangkunzk/Awesome-LLM-Robustness-papers），以支持社区的研究工作。

> Large Language Models (LLMs) have gained enormous attention in recent years due to their capability of understanding and generating natural languages. With the rapid development and wild-range applications (e.g., Agents, Embodied Intelligence), the robustness of LLMs has received increased attention. As the core brain of many AI applications, the robustness of LLMs requires that models should not only generate consistent contents, but also ensure the correctness and stability of generated content when dealing with unexpeted application scenarios (e.g., toxic prompts, limited noise domain data, outof-distribution (OOD) applications, etc). In this survey paper, we conduct a thorough review of the robustness of LLMs, aiming to provide a comprehensive terminology of concepts and methods around this field and facilitate the community. Specifically, we first give a formal definition of LLM robustness and present the collection protocol of this survey paper. Then, based on the types of perturbated inputs, we organize this survey from the following perspectives: 1) Adversarial Robustness: tackling the problem that prompts are manipulated intentionally, such as noise prompts, long context, data attack, etc; 2) OOD Robustness: dealing with the unexpected real-world application scenarios, such as OOD detection, zero-shot transferring, hallucinations, etc; 3) Evaluation of Robustness: summarizing the new evaluation datasets, metrics, and tools for verifying the robustness of LLMs. After reviewing the representative work from each perspective, we discuss and highlight future opportunities and research directions in this field. Meanwhile, we also organize related works and provide an easy-to-search project (https://github.com/zhangkunzk/Awesome-LLM-Robustness-papers) to support the community.

[Arxiv](https://arxiv.org/abs/2506.11111)