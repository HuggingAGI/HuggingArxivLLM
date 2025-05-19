# 全局XAI方法能否检测大型语言模型中的注入偏见？SHAP与规则提取及RuleSHAP的对比分析

发布时间：2025年05月16日

`LLM应用` `可解释性AI`

> Can Global XAI Methods Reveal Injected Bias in LLMs? SHAP vs Rule Extraction vs RuleSHAP

# 摘要

> 生成式AI系统在传播信息的同时，也可能传播错误信息和偏见，这可能威胁联合国可持续发展目标（SDGs）。可解释性AI（XAI）旨在揭示AI系统的运行机制，揭露其不当行为或偏见。然而，现有的XAI工具是为结构更简单的模型设计的，难以应对大型语言模型（LLMs）的非数值特性。本文探讨了全局XAI方法（如规则提取算法和SHAP）在检测LLMs偏见方面的有效性。为此，我们提出了一种文本到序数的映射策略，将非数值输入/输出转换为数值特征，从而让这些工具能够识别（部分）LLM生成内容中与错误信息相关的偏见。接着，我们通过系统指令将不同复杂度的非线性偏见（单变量、复合型和非凸型）注入到广泛应用的LLMs（如ChatGPT和Llama）中，并利用全局XAI方法进行检测。结果发现，RuleFit在处理复合型和非凸型偏见时表现不佳，而SHAP能够近似复合型偏见，但无法将其表达为可操作的规则。因此，我们提出了RuleSHAP，这是一种结合SHAP和RuleFit的全局规则提取算法，能够检测更多非单变量偏见，与RuleFit相比，注入偏见检测的平均MRR@1指标提升了+94%。

> Generative AI systems can help spread information but also misinformation and biases, potentially undermining the UN Sustainable Development Goals (SDGs). Explainable AI (XAI) aims to reveal the inner workings of AI systems and expose misbehaviours or biases. However, current XAI tools, built for simpler models, struggle to handle the non-numerical nature of large language models (LLMs). This paper examines the effectiveness of global XAI methods, such as rule-extraction algorithms and SHAP, in detecting bias in LLMs. To do so, we first show a text-to-ordinal mapping strategy to convert non-numerical inputs/outputs into numerical features, enabling these tools to identify (some) misinformation-related biases in LLM-generated content. Then, we inject non-linear biases of varying complexity (univariate, conjunctive, and non-convex) into widespread LLMs like ChatGPT and Llama via system instructions, using global XAI methods to detect them. This way, we found that RuleFit struggles with conjunctive and non-convex biases, while SHAP can approximate conjunctive biases but cannot express them as actionable rules. Hence, we introduce RuleSHAP, a global rule extraction algorithm combining SHAP and RuleFit to detect more non-univariate biases, improving injected bias detection over RuleFit by +94% (MRR@1) on average.

[Arxiv](https://arxiv.org/abs/2505.11189)