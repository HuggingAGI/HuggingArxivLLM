# # MrM：针对多模态 RAG 系统的黑盒成员推断攻击

发布时间：2025年06月08日

`RAG` `隐私保护` `计算机视觉`

> MrM: Black-Box Membership Inference Attacks against Multimodal RAG Systems

# 摘要

> 多模态检索增强生成（RAG）系统通过整合跨模态知识显著提升了大型视觉语言模型的能力，使其在现实世界的多模态任务中得到广泛应用。然而，这些系统中的知识数据库可能包含敏感信息，需要隐私保护。由于多模态RAG系统允许外部用户间接访问这些数据，它们容易受到隐私攻击，特别是成员推断攻击（MIAs）。目前，针对RAG系统的成员推断攻击方法主要集中在文本模态，而视觉模态的研究相对较少。为了解决这一问题，我们提出了MrM，首个针对多模态RAG系统的黑盒成员推断攻击框架。MrM采用受反事实攻击约束的多对象数据扰动框架，能够同时诱导RAG系统检索目标数据并生成泄露成员信息的内容。首先，我们的方法使用对象感知的数据扰动技术，将扰动限制在关键语义上，确保检索成功。在此基础上，我们设计了基于反事实的掩码选择策略，优先选择最具信息量的掩码区域，以消除模型自身知识的干扰并增强攻击效果。最后，我们通过建模查询尝试进行统计成员推断，提取反映从响应模式中重建掩码语义的特征。在两个视觉数据集和八个主流商业视觉语言模型（如GPT-4o、Gemini-2）上的实验结果表明，MrM在样本级和集合级评估中均表现优异，并且在自适应防御下仍保持 robust.

> Multimodal retrieval-augmented generation (RAG) systems enhance large vision-language models by integrating cross-modal knowledge, enabling their increasing adoption across real-world multimodal tasks. These knowledge databases may contain sensitive information that requires privacy protection. However, multimodal RAG systems inherently grant external users indirect access to such data, making them potentially vulnerable to privacy attacks, particularly membership inference attacks (MIAs). % Existing MIA methods targeting RAG systems predominantly focus on the textual modality, while the visual modality remains relatively underexplored. To bridge this gap, we propose MrM, the first black-box MIA framework targeted at multimodal RAG systems. It utilizes a multi-object data perturbation framework constrained by counterfactual attacks, which can concurrently induce the RAG systems to retrieve the target data and generate information that leaks the membership information. Our method first employs an object-aware data perturbation method to constrain the perturbation to key semantics and ensure successful retrieval. Building on this, we design a counterfact-informed mask selection strategy to prioritize the most informative masked regions, aiming to eliminate the interference of model self-knowledge and amplify attack efficacy. Finally, we perform statistical membership inference by modeling query trials to extract features that reflect the reconstruction of masked semantics from response patterns. Experiments on two visual datasets and eight mainstream commercial visual-language models (e.g., GPT-4o, Gemini-2) demonstrate that MrM achieves consistently strong performance across both sample-level and set-level evaluations, and remains robust under adaptive defenses.

[Arxiv](https://arxiv.org/abs/2506.07399)