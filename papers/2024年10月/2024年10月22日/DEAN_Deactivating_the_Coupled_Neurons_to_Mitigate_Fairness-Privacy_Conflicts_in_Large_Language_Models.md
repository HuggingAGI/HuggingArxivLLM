# DEAN：解耦神经元，缓解LLM中的公平性与隐私冲突

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在公平性和隐私意识之间的权衡问题，并提出了一种无需训练的方法（DEAN）来解决这一问题。论文的核心内容涉及LLM的理论改进和优化，特别是通过信息论的方法来减少公平性和隐私意识之间的互信息。因此，这篇论文更适合归类为“LLM理论”。` `人工智能`

> DEAN: Deactivating the Coupled Neurons to Mitigate Fairness-Privacy Conflicts in Large Language Models

# 摘要

> 确保大型语言模型（LLMs）对公平性和隐私的意识至关重要。有趣的是，我们发现了一个反直觉的权衡现象：通过监督微调（SFT）方法增强LLM的隐私意识会显著降低其公平性意识，尤其是在数千个样本的情况下。为了解决这个问题，受信息论的启发，我们提出了一种无需训练的方法——**DEA**ctivate公平性和隐私耦合的**N**eurons（**DEAN**），该方法在理论和实验上都减少了公平性和隐私意识之间的互信息。大量实验表明，DEAN消除了这种权衡现象，并显著同时提升了LLMs的公平性和隐私意识，例如将Qwen-2-7B-Instruct的公平性意识提高了12.2%，隐私意识提高了14.0%。更重要的是，DEAN在标注数据有限或仅提供恶意微调数据的情况下依然稳健有效，而SFT方法在这些情况下可能失效。我们希望这项研究为同时解决LLMs中的公平性和隐私问题提供了有价值的见解，并可以集成到综合框架中以开发更道德和负责任的AI系统。我们的代码可在url{https://github.com/ChnQ/DEAN}获取。

> Ensuring awareness of fairness and privacy in Large Language Models (LLMs) is critical. Interestingly, we discover a counter-intuitive trade-off phenomenon that enhancing an LLM's privacy awareness through Supervised Fine-Tuning (SFT) methods significantly decreases its fairness awareness with thousands of samples. To address this issue, inspired by the information theory, we introduce a training-free method to \textbf{DEA}ctivate the fairness and privacy coupled \textbf{N}eurons (\textbf{DEAN}), which theoretically and empirically decrease the mutual information between fairness and privacy awareness. Extensive experimental results demonstrate that DEAN eliminates the trade-off phenomenon and significantly improves LLMs' fairness and privacy awareness simultaneously, \eg improving Qwen-2-7B-Instruct's fairness awareness by 12.2\% and privacy awareness by 14.0\%. More crucially, DEAN remains robust and effective with limited annotated data or even when only malicious fine-tuning data is available, whereas SFT methods may fail to perform properly in such scenarios. We hope this study provides valuable insights into concurrently addressing fairness and privacy concerns in LLMs and can be integrated into comprehensive frameworks to develop more ethical and responsible AI systems. Our code is available at url{https://github.com/ChnQ/DEAN}.

[Arxiv](https://arxiv.org/abs/2410.16672)