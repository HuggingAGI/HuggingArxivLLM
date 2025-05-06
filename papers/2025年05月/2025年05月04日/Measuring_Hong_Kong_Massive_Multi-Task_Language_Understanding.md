# 测评香港大规模多任务语言理解能力

发布时间：2025年05月04日

`LLM应用

摘要：这篇论文专注于评估大型语言模型（LLMs）在香港独特语言环境中的多语言理解能力。通过开发HKMMLU基准，研究者测试了多个模型的表现，并分析了影响模型性能的因素，推动了LLMs在跨文化环境中的应用。` `多语言`

> Measuring Hong Kong Massive Multi-Task Language Understanding

# 摘要

> # 摘要  
多语言理解对大型语言模型 (LLMs) 在跨文化环境中的适用性至关重要。然而，针对香港独特语言环境（结合繁体中文书写系统、粤语口语形式及其文化背景）设计的评估基准仍然不完善。为了解决这一差距，我们引入了HKMMLU，一个多任务语言理解基准，用于评估香港的语言能力和社会文化知识。  
HKMMLU包含涵盖66个科目的26,698个多选题，分为四类：科学、技术、工程和数学 (STEM)，社会科学，人文学科，以及其他。为了评估LLMs的多语言理解能力，还额外包含了90,550个普通话-粤语翻译任务。  
我们在GPT-4o、Claude 3.7 Sonnet和18个不同规模的开源LLMs上对HKMMLU进行了全面实验。结果显示，表现最佳的模型DeepSeek-V3的准确率难以达到75%，远低于MMLU和CMMLU的水平。这一性能差距凸显了提升LLMs在香港特定语言和知识领域的能力的必要性。  
此外，我们还研究了问题语言、模型规模、提示策略以及问题和推理令牌长度对模型性能的影响。我们希望HKMMLU将极大地推动LLMs在多语言和跨文化环境中的发展，从而实现更广泛和更有影响力的落地应用。

> Multilingual understanding is crucial for the cross-cultural applicability of Large Language Models (LLMs). However, evaluation benchmarks designed for Hong Kong's unique linguistic landscape, which combines Traditional Chinese script with Cantonese as the spoken form and its cultural context, remain underdeveloped. To address this gap, we introduce HKMMLU, a multi-task language understanding benchmark that evaluates Hong Kong's linguistic competence and socio-cultural knowledge. The HKMMLU includes 26,698 multi-choice questions across 66 subjects, organized into four categories: Science, Technology, Engineering, and Mathematics (STEM), Social Sciences, Humanities, and Other. To evaluate the multilingual understanding ability of LLMs, 90,550 Mandarin-Cantonese translation tasks were additionally included. We conduct comprehensive experiments on GPT-4o, Claude 3.7 Sonnet, and 18 open-source LLMs of varying sizes on HKMMLU. The results show that the best-performing model, DeepSeek-V3, struggles to achieve an accuracy of 75\%, significantly lower than that of MMLU and CMMLU. This performance gap highlights the need to improve LLMs' capabilities in Hong Kong-specific language and knowledge domains. Furthermore, we investigate how question language, model size, prompting strategies, and question and reasoning token lengths affect model performance. We anticipate that HKMMLU will significantly advance the development of LLMs in multilingual and cross-cultural contexts, thereby enabling broader and more impactful applications.

[Arxiv](https://arxiv.org/abs/2505.02177)