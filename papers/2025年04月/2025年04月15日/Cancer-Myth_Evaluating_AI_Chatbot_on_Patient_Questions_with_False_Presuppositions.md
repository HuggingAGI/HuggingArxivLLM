# # 癌症误区：评估AI聊天机器人在处理带有错误预设的患者问题时的表现

发布时间：2025年04月15日

`LLM应用

摘要中讨论了大型语言模型（LLMs）在医疗信息获取中的应用，特别是评估这些模型处理复杂个性化医疗问题的能力。研究重点在于模型在真实患者问题中的表现，以及它们在识别和处理错误假设方面的局限性。这属于对LLMs在特定领域（医疗）的应用评估和分析，因此归类为LLM应用。` `健康科技`

> Cancer-Myth: Evaluating AI Chatbot on Patient Questions with False Presuppositions

# 摘要

> 越来越多的癌症患者将大型语言模型（LLMs）作为获取医疗信息的新途径，这使得评估这些模型处理复杂个性化医疗问题的能力变得尤为重要。然而，现有的医学评估标准主要集中在医学考试或消费者搜索问题上，未能对真实患者提出的、包含详细临床背景的问题进行全面评估。在本研究中，我们首次对来自真实患者的癌症相关问题进行了评估，这些问题经过了三位血液肿瘤科医生的专业审核。尽管模型的回答总体上是准确的，GPT-4-Turbo的表现尤为突出，得分为4.13分（满分5分），但它们常常未能识别或处理问题中隐含的错误假设，这可能对医疗决策的安全性构成潜在风险。为系统研究这一局限性，我们推出了Cancer-Myth，一个包含585个带有错误假设的癌症相关问题的专家验证对抗性数据集。在这一基准测试中，包括GPT-4、Gemini-1.Pro和Claude-3.5-Sonnet在内的前沿LLMs，仅有不到30%的时间能够纠正这些错误假设。即使采用先进的医疗智能体方法，也无法避免LLMs忽略错误假设的问题。这些发现揭示了LLMs在临床可靠性方面的重大差距，凸显了在医疗AI系统中建立更强大保障措施的迫切需求。

> Cancer patients are increasingly turning to large language models (LLMs) as a new form of internet search for medical information, making it critical to assess how well these models handle complex, personalized questions. However, current medical benchmarks focus on medical exams or consumer-searched questions and do not evaluate LLMs on real patient questions with detailed clinical contexts. In this paper, we first evaluate LLMs on cancer-related questions drawn from real patients, reviewed by three hematology oncology physicians. While responses are generally accurate, with GPT-4-Turbo scoring 4.13 out of 5, the models frequently fail to recognize or address false presuppositions in the questions-posing risks to safe medical decision-making. To study this limitation systematically, we introduce Cancer-Myth, an expert-verified adversarial dataset of 585 cancer-related questions with false presuppositions. On this benchmark, no frontier LLM -- including GPT-4o, Gemini-1.Pro, and Claude-3.5-Sonnet -- corrects these false presuppositions more than 30% of the time. Even advanced medical agentic methods do not prevent LLMs from ignoring false presuppositions. These findings expose a critical gap in the clinical reliability of LLMs and underscore the need for more robust safeguards in medical AI systems.

[Arxiv](https://arxiv.org/abs/2504.11373)