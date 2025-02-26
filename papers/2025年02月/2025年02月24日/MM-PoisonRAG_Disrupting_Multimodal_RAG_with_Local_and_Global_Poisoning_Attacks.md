# MM-PoisonRAG：用局部和全局投毒攻击颠覆多模态RAG

发布时间：2025年02月24日

`RAG` `人工智能`

> MM-PoisonRAG: Disrupting Multimodal RAG with Local and Global Poisoning Attacks

# 摘要

> # 摘要  
    配备检索增强生成（RAG）的多模态大型语言模型（MLLMs）利用其丰富的参数知识和动态的外部知识，在问答等任务中表现出色。然而，RAG通过将模型的回答基于与查询相关的外部知识来增强MLLMs，这种依赖性带来了一个重要但未充分探索的安全风险：知识中毒攻击，即故意向外部知识库中注入错误信息或不相关知识，以操纵模型输出，使其产生错误甚至有害的结果。  
    为了揭示多模态RAG中的这些漏洞，我们提出了MM-PoisonRAG，一个新颖的知识中毒攻击框架，包含两种攻击策略：局部中毒攻击（LPA），在文本和图像中注入特定于查询的错误信息以进行有针对性的操纵；以及全局中毒攻击（GPA），在MLLM生成过程中提供虚假指导，以引发所有查询的无意义回答。  
    我们在多个任务、模型和访问设置下评估了我们的攻击方法，结果表明，LPA成功地控制了MLLM的回答，准确率高达56%。此外，GPA只需注入一条无关知识即可完全破坏模型生成，准确率降至0%。  
    我们的研究结果凸显了针对知识中毒攻击构建强大防御机制的迫切需求，以保护多模态RAG框架的安全性。

> Multimodal large language models (MLLMs) equipped with Retrieval Augmented Generation (RAG) leverage both their rich parametric knowledge and the dynamic, external knowledge to excel in tasks such as Question Answering. While RAG enhances MLLMs by grounding responses in query-relevant external knowledge, this reliance poses a critical yet underexplored safety risk: knowledge poisoning attacks, where misinformation or irrelevant knowledge is intentionally injected into external knowledge bases to manipulate model outputs to be incorrect and even harmful. To expose such vulnerabilities in multimodal RAG, we propose MM-PoisonRAG, a novel knowledge poisoning attack framework with two attack strategies: Localized Poisoning Attack (LPA), which injects query-specific misinformation in both text and images for targeted manipulation, and Globalized Poisoning Attack (GPA) to provide false guidance during MLLM generation to elicit nonsensical responses across all queries. We evaluate our attacks across multiple tasks, models, and access settings, demonstrating that LPA successfully manipulates the MLLM to generate attacker-controlled answers, with a success rate of up to 56% on MultiModalQA. Moreover, GPA completely disrupts model generation to 0% accuracy with just a single irrelevant knowledge injection. Our results highlight the urgent need for robust defenses against knowledge poisoning to safeguard multimodal RAG frameworks.

[Arxiv](https://arxiv.org/abs/2502.17832)