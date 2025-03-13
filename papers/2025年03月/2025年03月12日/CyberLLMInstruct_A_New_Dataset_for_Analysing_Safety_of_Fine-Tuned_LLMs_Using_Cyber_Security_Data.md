# # 摘要
CyberLLMInstruct：首个基于网络安全数据评估微调LLMs安全性的数据集

发布时间：2025年03月12日

`LLM应用` `网络安全` `数据安全`

> CyberLLMInstruct: A New Dataset for Analysing Safety of Fine-Tuned LLMs Using Cyber Security Data

# 摘要

> 将大型语言模型（LLMs）应用于网络安全，既带来了提升威胁分析与恶意软件检测等显著机遇，也伴随着个人数据泄露与新型恶意软件生成等关键风险。为应对这些挑战，我们开发了CyberLLMInstruct数据集，包含54,928个指令-响应对，涵盖恶意软件分析、钓鱼演练及零日漏洞等任务。该数据集通过多阶段构建，包括数据获取、筛选整理与场景对齐，确保其实际应用价值。我们选取了七种开源LLMs进行测试，包括Phi 3 Mini 3.8B、Mistral 7B、Qwen 2.5 7B、Llama 3 8B、Llama 3.1 8B、Gemma 2 9B和Llama 2 70B。通过OWASP top 10框架评估发现，微调显著降低了模型的安全韧性（例如，Llama 3.1 8B在提示注入攻击中的安全评分从0.95降至0.15）。同时，这些微调模型在CyberMetric基准测试中达到了92.50%的准确率。这表明性能与安全间的权衡，强调了对抗性测试的重要性，并推动了在提升性能同时降低安全风险的微调方法研究。所有用于重现结果的脚本、示例及资源，将在论文发表后公开。

> The integration of large language models (LLMs) into cyber security applications presents significant opportunities, such as enhancing threat analysis and malware detection, but can also introduce critical risks and safety concerns, including personal data leakage and automated generation of new malware. To address these challenges, we developed CyberLLMInstruct, a dataset of 54,928 instruction-response pairs spanning cyber security tasks such as malware analysis, phishing simulations, and zero-day vulnerabilities. The dataset was constructed through a multi-stage process. This involved sourcing data from multiple resources, filtering and structuring it into instruction-response pairs, and aligning it with real-world scenarios to enhance its applicability. Seven open-source LLMs were chosen to test the usefulness of CyberLLMInstruct: Phi 3 Mini 3.8B, Mistral 7B, Qwen 2.5 7B, Llama 3 8B, Llama 3.1 8B, Gemma 2 9B, and Llama 2 70B. In our primary example, we rigorously assess the safety of fine-tuned models using the OWASP top 10 framework, finding that fine-tuning reduces safety resilience across all tested LLMs and every adversarial attack (e.g., the security score of Llama 3.1 8B against prompt injection drops from 0.95 to 0.15). In our second example, we show that these same fine-tuned models can also achieve up to 92.50 percent accuracy on the CyberMetric benchmark. These findings highlight a trade-off between performance and safety, showing the importance of adversarial testing and further research into fine-tuning methodologies that can mitigate safety risks while still improving performance across diverse datasets and domains. All scripts required to reproduce the dataset, along with examples and relevant resources for replicating our results, will be made available upon the paper's acceptance.

[Arxiv](https://arxiv.org/abs/2503.09334)