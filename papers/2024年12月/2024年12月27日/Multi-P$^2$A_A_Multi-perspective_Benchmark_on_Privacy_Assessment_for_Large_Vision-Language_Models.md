# Multi-P$^2$A：针对大型视觉语言模型隐私评估的多视角基准

发布时间：2024年12月27日

`LLM应用` `隐私保护` `视觉语言模型`

> Multi-P$^2$A: A Multi-perspective Benchmark on Privacy Assessment for Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）在各类任务中潜力非凡，但也面临着严重的隐私风险，从而限制了其实际应用。当下对于 LVLMs 隐私评估的研究颇为有限，在评估维度和隐私类别上均存在缺口。为填补这一空缺，我们提出了 Multi-P$^2$A，这是一个从隐私意识和泄漏角度评估 LVLMs 隐私保护能力的综合基准。隐私意识用于衡量模型识别输入数据隐私敏感度的能力，隐私泄漏则评估模型在输出中无意泄露隐私信息的风险。我们设计了一系列子任务，以全面评估 LVLMs 提供的隐私保护。Multi-P$^2$A 涵盖 26 类个人隐私、15 类商业机密和 18 类国家机密，总计 31962 个样本。基于 Multi-P$^2$A，我们对 21 个开源和 2 个闭源的 LVLMs 进行了隐私保护能力评估。我们的结果显示，当前的 LVLMs 通常存在较高的隐私泄露风险，在个人隐私、商业机密和国家机密方面的漏洞各有不同。

> Large Vision-Language Models (LVLMs) exhibit impressive potential across various tasks but also face significant privacy risks, limiting their practical applications. Current researches on privacy assessment for LVLMs is limited in scope, with gaps in both assessment dimensions and privacy categories. To bridge this gap, we propose Multi-P$^2$A, a comprehensive benchmark for evaluating the privacy preservation capabilities of LVLMs in terms of privacy awareness and leakage. Privacy awareness measures the model's ability to recognize the privacy sensitivity of input data, while privacy leakage assesses the risk of the model unintentionally disclosing privacy information in its output. We design a range of sub-tasks to thoroughly evaluate the model's privacy protection offered by LVLMs. Multi-P$^2$A covers 26 categories of personal privacy, 15 categories of trade secrets, and 18 categories of state secrets, totaling 31,962 samples. Based on Multi-P$^2$A, we evaluate the privacy preservation capabilities of 21 open-source and 2 closed-source LVLMs. Our results reveal that current LVLMs generally pose a high risk of facilitating privacy breaches, with vulnerabilities varying across personal privacy, trade secret, and state secret.

[Arxiv](https://arxiv.org/abs/2412.19496)