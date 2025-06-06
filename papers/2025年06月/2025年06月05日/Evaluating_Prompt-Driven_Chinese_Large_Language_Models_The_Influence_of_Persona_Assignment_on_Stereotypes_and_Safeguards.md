# 评估提示驱动的中文大型语言模型：角色分配对刻板印象和防护措施的影响

发布时间：2025年06月05日

`LLM应用

论文摘要：最近的研究表明，赋予大型语言模型（LLMs）特定人设会显著增加有害内容的生成。然而，对于非西方背景下的基于人设的毒性问题，尤其是中文大型语言模型，相关研究仍然有限。本文以广泛使用的中文语言模型Qwen为例，进行了大规模、系统性的分析，研究人设分配如何影响拒绝行为和毒性回应。通过微调后的BERT分类器和回归分析，我们发现拒绝率中存在显著的性别偏见，并且某些负面人设会将针对中国社会群体的毒性提升至默认模型的60倍。为了解决这一问题，我们提出了一种创新的多模型反馈策略，通过Qwen与外部评估器之间的迭代交互，无需昂贵的模型重新训练即可有效减少有毒输出。我们的研究强调了对LLMs安全进行文化特定分析的重要性，并为评估和提升LLM生成内容的伦理一致性提供了实用框架。

LLM应用` `模型安全` `模型治理`

> Evaluating Prompt-Driven Chinese Large Language Models: The Influence of Persona Assignment on Stereotypes and Safeguards

# 摘要

> 最近的研究表明，赋予大型语言模型（LLMs）特定人设会显著增加有害内容的生成。然而，对于非西方背景下的基于人设的毒性问题，尤其是中文大型语言模型，相关研究仍然有限。本文以广泛使用的中文语言模型Qwen为例，进行了大规模、系统性的分析，研究人设分配如何影响拒绝行为和毒性回应。通过微调后的BERT分类器和回归分析，我们发现拒绝率中存在显著的性别偏见，并且某些负面人设会将针对中国社会群体的毒性提升至默认模型的60倍。为了解决这一问题，我们提出了一种创新的多模型反馈策略，通过Qwen与外部评估器之间的迭代交互，无需昂贵的模型重新训练即可有效减少有毒输出。我们的研究强调了对LLMs安全进行文化特定分析的重要性，并为评估和提升LLM生成内容的伦理一致性提供了实用框架。

> Recent research has highlighted that assigning specific personas to large language models (LLMs) can significantly increase harmful content generation. Yet, limited attention has been given to persona-driven toxicity in non-Western contexts, particularly in Chinese-based LLMs. In this paper, we perform a large-scale, systematic analysis of how persona assignment influences refusal behavior and response toxicity in Qwen, a widely-used Chinese language model. Utilizing fine-tuned BERT classifiers and regression analysis, our study reveals significant gender biases in refusal rates and demonstrates that certain negative personas can amplify toxicity toward Chinese social groups by up to 60-fold compared to the default model. To mitigate this toxicity, we propose an innovative multi-model feedback strategy, employing iterative interactions between Qwen and an external evaluator, which effectively reduces toxic outputs without costly model retraining. Our findings emphasize the necessity of culturally specific analyses for LLMs safety and offer a practical framework for evaluating and enhancing ethical alignment in LLM-generated content.

[Arxiv](https://arxiv.org/abs/2506.04975)