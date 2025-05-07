# 霍姆斯：基于大型语言模型的自动事实核查系统

发布时间：2025年05月05日

`LLM应用` `信息真实性`

> Holmes: Automated Fact Check with Large Language Models

# 摘要

> 互联网连接的普及加速了虚假信息的传播，威胁到社会信任、决策和国家安全。虚假信息已从简单的文本形式发展到结合图像和文本的复杂多模态形式，这使得现有的检测方法面临挑战。传统的深度学习模型难以捕捉多模态虚假信息的复杂性。受人工智能进展的启发，本研究探索使用大型语言模型（LLMs）进行自动化的虚假信息检测。实证研究表明，（1）LLMs 无法可靠地评估声明的真实性；（2）提供相关证据显著提高了它们的性能；（3）然而，LLMs 无法自主搜索准确的证据。为了解决这一问题，我们提出了 Holmes，一个端到端的框架，其中包含一种新颖的证据检索方法，帮助 LLMs 收集高质量的证据。我们的方法利用（1）基于 LLM 的摘要功能从开放资源中提取关键信息，以及（2）一种新算法和指标来评估证据质量。Holmes 使 LLMs 能够有效地验证声明并生成理由。实验显示，Holmes 在两个开源数据集上实现了 88.3% 的准确率，并在实时验证任务中达到了 90.2%。值得注意的是，我们改进的证据检索方法使事实核查的准确率比现有方法提高了 30.8%。


> The rise of Internet connectivity has accelerated the spread of disinformation, threatening societal trust, decision-making, and national security. Disinformation has evolved from simple text to complex multimodal forms combining images and text, challenging existing detection methods. Traditional deep learning models struggle to capture the complexity of multimodal disinformation. Inspired by advances in AI, this study explores using Large Language Models (LLMs) for automated disinformation detection. The empirical study shows that (1) LLMs alone cannot reliably assess the truthfulness of claims; (2) providing relevant evidence significantly improves their performance; (3) however, LLMs cannot autonomously search for accurate evidence. To address this, we propose Holmes, an end-to-end framework featuring a novel evidence retrieval method that assists LLMs in collecting high-quality evidence. Our approach uses (1) LLM-powered summarization to extract key information from open sources and (2) a new algorithm and metrics to evaluate evidence quality. Holmes enables LLMs to verify claims and generate justifications effectively. Experiments show Holmes achieves 88.3% accuracy on two open-source datasets and 90.2% in real-time verification tasks. Notably, our improved evidence retrieval boosts fact-checking accuracy by 30.8% over existing methods

[Arxiv](https://arxiv.org/abs/2505.03135)