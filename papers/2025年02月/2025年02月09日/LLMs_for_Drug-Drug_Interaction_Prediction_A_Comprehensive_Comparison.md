# 大型语言模型在药物相互作用预测中的全面比较

发布时间：2025年02月09日

`LLM应用

理由：这篇论文探讨了大型语言模型在药物-药物相互作用预测中的应用，属于将LLMs应用于特定领域的问题解决，符合LLM应用的分类。` `药物研发` `药物相互作用`

> LLMs for Drug-Drug Interaction Prediction: A Comprehensive Comparison

# 摘要

> 现代治疗方案中日益增多的药物组合需要可靠的方法来预测药物-药物相互作用 (DDIs)。尽管大型语言模型 (LLMs) 在多个领域带来了革命性的变化，但它们在药物研发，特别是DDI预测方面的潜力尚未得到充分挖掘。本研究通过将分子结构 (SMILES)、目标生物体和基因相互作用数据作为原始文本输入，从最新的DrugBank数据集中独特地处理这些信息，全面探索了LLMs在DDI预测中的能力。

我们评估了18种不同的LLMs，包括专有模型 (GPT-4, Claude, Gemini) 和开源变体 (从1.5B到72B参数)，首先评估了它们在DDI预测中的零样本能力。随后，我们对选定的模型 (GPT-4, Phi-3.5 2.7B, Qwen-2.5 3B, Gemma-2 9B 和 Deepseek R1 distilled Qwen 1.5B) 进行了微调，以优化其性能。我们的评估框架涵盖了13个外部DDI数据集的验证，并与传统方法（如l2-正则化逻辑回归）进行了对比。微调后的LLMs表现出了更优的性能，其中Phi-3.5 2.7B在DDI预测中的灵敏度达到0.978，平衡数据集（50%阳性，50%阴性案例）上的准确率为0.919。这一结果优于零样本预测和用于DDI预测的现有最先进的机器学习方法。

我们的分析表明，LLMs能够有效捕捉复杂的分子相互作用模式以及药物对共同靶点基因的情况，使其成为药物研发和临床应用中极具价值的工具。


> The increasing volume of drug combinations in modern therapeutic regimens needs reliable methods for predicting drug-drug interactions (DDIs). While Large Language Models (LLMs) have revolutionized various domains, their potential in pharmaceutical research, particularly in DDI prediction, remains largely unexplored. This study thoroughly investigates LLMs' capabilities in predicting DDIs by uniquely processing molecular structures (SMILES), target organisms, and gene interaction data as raw text input from the latest DrugBank dataset. We evaluated 18 different LLMs, including proprietary models (GPT-4, Claude, Gemini) and open-source variants (from 1.5B to 72B parameters), first assessing their zero-shot capabilities in DDI prediction. We then fine-tuned selected models (GPT-4, Phi-3.5 2.7B, Qwen-2.5 3B, Gemma-2 9B, and Deepseek R1 distilled Qwen 1.5B) to optimize their performance. Our comprehensive evaluation framework included validation across 13 external DDI datasets, comparing against traditional approaches such as l2-regularized logistic regression. Fine-tuned LLMs demonstrated superior performance, with Phi-3.5 2.7B achieving a sensitivity of 0.978 in DDI prediction, with an accuracy of 0.919 on balanced datasets (50% positive, 50% negative cases). This result represents an improvement over both zero-shot predictions and state-of-the-art machine-learning methods used for DDI prediction. Our analysis reveals that LLMs can effectively capture complex molecular interaction patterns and cases where drug pairs target common genes, making them valuable tools for practical applications in pharmaceutical research and clinical settings.

[Arxiv](https://arxiv.org/abs/2502.06890)