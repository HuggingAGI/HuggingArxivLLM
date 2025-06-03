# 评估医疗大语言模型中提示工程技巧对准确性和置信度提取的效果

发布时间：2025年05月29日

`LLM应用` `人工智能`

> Evaluating Prompt Engineering Techniques for Accuracy and Confidence Elicitation in Medical LLMs

# 摘要

> 本文探讨了提示工程方法对大型语言模型（LLMs）在医疗场景中的准确性和置信度提取的影响。我们采用涵盖多个医学专业的波斯语医学考试试题作为分层数据集，评估了GPT-4o、o3-mini、Llama-3.3-70b、Llama-3.1-8b和DeepSeek-v3五款LLMs，测试了156种不同配置。这些配置在温度设置（0.3、0.7、1.0）、提示风格（链式思维、少量示例、情感化、专家模拟）和置信度量表（1-10、1-100）上各有不同。通过AUC-ROC、Brier Score和预期校准误差（ECE）评估了置信度与实际表现的匹配度。研究发现，链式思维提示虽然提升了准确性，但也导致了过度自信，凸显了校准的必要性。情感化提示进一步夸大了置信度，增加了错误决策的风险。小型模型如Llama-3.1-8b在所有指标上表现不佳，而 proprietary models尽管准确率更高，但依然缺乏校准的置信度。这些结果表明，提示工程要想在高风险的医疗任务中有效应用，必须同时兼顾准确性和不确定性。

> This paper investigates how prompt engineering techniques impact both accuracy and confidence elicitation in Large Language Models (LLMs) applied to medical contexts. Using a stratified dataset of Persian board exam questions across multiple specialties, we evaluated five LLMs - GPT-4o, o3-mini, Llama-3.3-70b, Llama-3.1-8b, and DeepSeek-v3 - across 156 configurations. These configurations varied in temperature settings (0.3, 0.7, 1.0), prompt styles (Chain-of-Thought, Few-Shot, Emotional, Expert Mimicry), and confidence scales (1-10, 1-100). We used AUC-ROC, Brier Score, and Expected Calibration Error (ECE) to evaluate alignment between confidence and actual performance. Chain-of-Thought prompts improved accuracy but also led to overconfidence, highlighting the need for calibration. Emotional prompting further inflated confidence, risking poor decisions. Smaller models like Llama-3.1-8b underperformed across all metrics, while proprietary models showed higher accuracy but still lacked calibrated confidence. These results suggest prompt engineering must address both accuracy and uncertainty to be effective in high-stakes medical tasks.

[Arxiv](https://arxiv.org/abs/2506.00072)