# CySecBench：用于对大型语言模型进行基准测试的、基于生成式人工智能且聚焦网络安全的提示数据集

发布时间：2025年01月02日

`LLM应用` `网络安全` `语言模型`

> CySecBench: Generative AI-based CyberSecurity-focused Prompt Dataset for Benchmarking Large Language Models

# 摘要

> 众多研究对破解大型语言模型（LLMs）以生成有害内容的方法展开了探究。通常，这些方法会借助旨在绕开LLM提供商所设安全策略的恶意提示数据集来进行评估。然而，现有数据集普遍范围宽泛且开放性强，这可能导致破解效果的评估变得复杂，在特定领域（尤其是网络安全领域）更是如此。为应对此问题，我们推出并公开发布了CySecBench，这是一个综合性数据集，包含12662个专为评估网络安全领域破解技术而设计的提示。该数据集被划分为10个不同的攻击类型类别，采用封闭式提示，以便更一致、更准确地评估破解尝试。此外，我们详述了用于数据集生成和筛选的方法，此方法可用于在其他领域创建类似数据集。为展现CySecBench的实用性，我们提出并评估了一种基于提示混淆的破解方法。实验结果显示，该方法能成功从商业黑盒LLM中引出有害内容，ChatGPT的成功率为65%，Gemini为88%；相比之下，Claude的抵抗力更强，破解成功率为17%。与现有的基准方法相比，我们的方法性能更优，凸显了特定领域评估数据集在评估LLM安全措施方面的价值。此外，使用来自广泛使用的数据集（即AdvBench）的提示进行评估时，成功率达78.5%，高于前沿方法。

> Numerous studies have investigated methods for jailbreaking Large Language Models (LLMs) to generate harmful content. Typically, these methods are evaluated using datasets of malicious prompts designed to bypass security policies established by LLM providers. However, the generally broad scope and open-ended nature of existing datasets can complicate the assessment of jailbreaking effectiveness, particularly in specific domains, notably cybersecurity. To address this issue, we present and publicly release CySecBench, a comprehensive dataset containing 12662 prompts specifically designed to evaluate jailbreaking techniques in the cybersecurity domain. The dataset is organized into 10 distinct attack-type categories, featuring close-ended prompts to enable a more consistent and accurate assessment of jailbreaking attempts. Furthermore, we detail our methodology for dataset generation and filtration, which can be adapted to create similar datasets in other domains. To demonstrate the utility of CySecBench, we propose and evaluate a jailbreaking approach based on prompt obfuscation. Our experimental results show that this method successfully elicits harmful content from commercial black-box LLMs, achieving Success Rates (SRs) of 65% with ChatGPT and 88% with Gemini; in contrast, Claude demonstrated greater resilience with a jailbreaking SR of 17%. Compared to existing benchmark approaches, our method shows superior performance, highlighting the value of domain-specific evaluation datasets for assessing LLM security measures. Moreover, when evaluated using prompts from a widely used dataset (i.e., AdvBench), it achieved an SR of 78.5%, higher than the state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2501.01335)