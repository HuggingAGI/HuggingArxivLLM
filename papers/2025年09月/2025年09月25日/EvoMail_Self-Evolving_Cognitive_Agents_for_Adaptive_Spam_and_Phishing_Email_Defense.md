# EvoMail：自进化认知智能体——自适应垃圾邮件与钓鱼邮件防御系统

发布时间：2025年09月25日

`Agent` `金融科技`

> EvoMail: Self-Evolving Cognitive Agents for Adaptive Spam and Phishing Email Defense

# 摘要

> 如今的电子邮件垃圾邮件和网络钓鱼攻击早已不是关键词黑名单或简单启发式方法能应付的了。攻击者如今打造多模态攻击活动，将自然语言文本与混淆URL、伪造邮件头及恶意附件相结合，并在几天内调整策略以绕过过滤系统。传统垃圾邮件检测系统依赖静态规则或单模态模型，难以整合异构信号或持续适应新威胁，性能因此迅速下滑。
  为此，我们提出EvoMail——一个用于稳健检测垃圾邮件和网络钓鱼的自进化认知智能体框架。EvoMail首先构建统一的异构电子邮件图，融合文本内容、元数据（邮件头、发件人、域名）及嵌入资源（URL、附件）。随后，由大型语言模型（LLM）增强的认知图神经网络对这些来源进行上下文感知推理，识别协同垃圾邮件攻击活动。最关键的是，EvoMail具备对抗性自进化循环：“红队”智能体生成新型规避手段（如字符混淆或AI生成钓鱼文本），而“蓝队”检测器则从失败中学习，将经验压缩到记忆模块，并用于未来推理。
  在真实世界数据集（Enron-Spam、Ling-Spam、SpamAssassin、TREC）及合成对抗变体上的大量实验表明，EvoMail在检测准确率、对垃圾邮件策略演变的适应性及推理轨迹可解释性方面均持续优于现有最佳基线。这些结果彰显了EvoMail作为抵御下一代垃圾邮件和网络钓鱼威胁的弹性可解释防御框架的潜力。

> Modern email spam and phishing attacks have evolved far beyond keyword blacklists or simple heuristics. Adversaries now craft multi-modal campaigns that combine natural-language text with obfuscated URLs, forged headers, and malicious attachments, adapting their strategies within days to bypass filters. Traditional spam detection systems, which rely on static rules or single-modality models, struggle to integrate heterogeneous signals or to continuously adapt, leading to rapid performance degradation.
  We propose EvoMail, a self-evolving cognitive agent framework for robust detection of spam and phishing. EvoMail first constructs a unified heterogeneous email graph that fuses textual content, metadata (headers, senders, domains), and embedded resources (URLs, attachments). A Cognitive Graph Neural Network enhanced by a Large Language Model (LLM) performs context-aware reasoning across these sources to identify coordinated spam campaigns. Most critically, EvoMail engages in an adversarial self-evolution loop: a ''red-team'' agent generates novel evasion tactics -- such as character obfuscation or AI-generated phishing text -- while the ''blue-team'' detector learns from failures, compresses experiences into a memory module, and reuses them for future reasoning.
  Extensive experiments on real-world datasets (Enron-Spam, Ling-Spam, SpamAssassin, and TREC) and synthetic adversarial variants demonstrate that EvoMail consistently outperforms state-of-the-art baselines in detection accuracy, adaptability to evolving spam tactics, and interpretability of reasoning traces. These results highlight EvoMail's potential as a resilient and explainable defense framework against next-generation spam and phishing threats.

[Arxiv](https://arxiv.org/abs/2509.21129)