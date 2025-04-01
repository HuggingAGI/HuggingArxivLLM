# # RARE: 检索增强推理建模

发布时间：2025年03月30日

`LLM应用`

> RARE: Retrieval-Augmented Reasoning Modeling

# 摘要

> 领域智能需要专业知识和复杂推理来解决问题，这对大型语言模型（LLMs）来说是一个重大挑战，因为它们在有限的参数预算下难以应对知识幻觉和推理能力不足的问题。受教育理论中的布卢姆 taxonomy 启发，我们提出了检索增强推理建模（RARE），这是一种将知识存储与推理优化分离的新范式。RARE 将领域知识外化为可检索的来源，并在训练过程中内化特定领域的推理模式。具体来说，通过将检索到的知识注入训练提示中，RARE 将学习目标从死记硬背转变为情境化推理应用。它使模型能够绕过参数密集型记忆，优先发展高级认知过程。我们的实验表明，轻量级的 RARE 训练模型（例如，Llama-3.1-8B）能够达到最先进的性能，超越检索增强的 GPT-4 和 Deepseek-R1 蒸馏版本。RARE 建立了一种范式转变，其中可维护的外部知识库与紧凑的、推理优化的模型协同工作，共同推动更可扩展的领域智能。Repo: https://github.com/Open-DataFlow/RARE

> Domain-specific intelligence demands specialized knowledge and sophisticated reasoning for problem-solving, posing significant challenges for large language models (LLMs) that struggle with knowledge hallucination and inadequate reasoning capabilities under constrained parameter budgets. Inspired by Bloom's Taxonomy in educational theory, we propose Retrieval-Augmented Reasoning Modeling (RARE), a novel paradigm that decouples knowledge storage from reasoning optimization. RARE externalizes domain knowledge to retrievable sources and internalizes domain-specific reasoning patterns during training. Specifically, by injecting retrieved knowledge into training prompts, RARE transforms learning objectives from rote memorization to contextualized reasoning application. It enables models to bypass parameter-intensive memorization and prioritize the development of higher-order cognitive processes. Our experiments demonstrate that lightweight RARE-trained models (e.g., Llama-3.1-8B) could achieve state-of-the-art performance, surpassing retrieval-augmented GPT-4 and Deepseek-R1 distilled counterparts. RARE establishes a paradigm shift where maintainable external knowledge bases synergize with compact, reasoning-optimized models, collectively driving more scalable domain-specific intelligence. Repo: https://github.com/Open-DataFlow/RARE

[Arxiv](https://arxiv.org/abs/2503.23513)