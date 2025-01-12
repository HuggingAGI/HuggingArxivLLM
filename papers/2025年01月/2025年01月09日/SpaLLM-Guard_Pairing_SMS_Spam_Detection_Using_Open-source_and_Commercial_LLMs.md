# SpaLLM-Guard: 利用开源与商业LLMs实现短信垃圾检测配对

发布时间：2025年01月09日

`LLM应用

**理由**: 这篇论文主要探讨了大型语言模型（LLMs）在短信垃圾邮件检测中的应用，包括零-shot、少-shot、微调和思维链提示等方法。研究重点在于如何利用LLMs来解决实际问题（即垃圾邮件检测），并评估了不同方法的效果。因此，这篇论文属于LLM应用类别。` `网络安全` `垃圾邮件检测`

> SpaLLM-Guard: Pairing SMS Spam Detection Using Open-source and Commercial LLMs

# 摘要

> 随着对抗性技术和概念漂移的不断演进，短信垃圾邮件的威胁日益严峻，亟需更强大且适应性更强的检测方法。本文评估了开源和商业大型语言模型（LLMs）在短信垃圾邮件检测中的潜力，对比了它们在零-shot、少-shot、微调和思维链提示方法中的表现。基于一个全面的短信数据集，我们测试了GPT-4、DeepSeek、LLAMA-2和Mixtral等知名LLMs的垃圾邮件检测能力。研究发现，零-shot学习虽然便捷，但在垃圾邮件检测中并不可靠；少-shot学习通过精心挑选示例提升了检测效果，但不同模型间存在差异。微调策略表现最佳，Mixtral的准确率高达98.6%，假阳性和假阴性率均低于2%，达到了稳健检测的标准。此外，微调显著增强了模型对可见和不可见对抗攻击的鲁棒性。最后，研究表明，微调LLMs结合少-shot学习能够有效缓解概念漂移的影响，即使在动态变化的垃圾邮件数据集上也能保持高性能。本研究凸显了微调和定制学习策略在LLMs实际部署中的重要性。

> The increasing threat of SMS spam, driven by evolving adversarial techniques and concept drift, calls for more robust and adaptive detection methods. In this paper, we evaluate the potential of large language models (LLMs), both open-source and commercial, for SMS spam detection, comparing their performance across zero-shot, few-shot, fine-tuning, and chain-of-thought prompting approaches. Using a comprehensive dataset of SMS messages, we assess the spam detection capabilities of prominent LLMs such as GPT-4, DeepSeek, LLAMA-2, and Mixtral. Our findings reveal that while zero-shot learning provides convenience, it is unreliable for effective spam detection. Few-shot learning, particularly with carefully selected examples, improves detection but exhibits variability across models. Fine-tuning emerges as the most effective strategy, with Mixtral achieving 98.6% accuracy and a balanced false positive and false negative rate below 2%, meeting the criteria for robust spam detection. Furthermore, we explore the resilience of these models to adversarial attacks, finding that fine-tuning significantly enhances robustness against both perceptible and imperceptible manipulations. Lastly, we investigate the impact of concept drift and demonstrate that fine-tuned LLMs, especially when combined with few-shot learning, can mitigate its effects, maintaining high performance even on evolving spam datasets. This study highlights the importance of fine-tuning and tailored learning strategies to deploy LLMs effectively for real-world SMS spam detection

[Arxiv](https://arxiv.org/abs/2501.04985)