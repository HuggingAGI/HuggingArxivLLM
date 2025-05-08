# 揭开画布的面纱：图像生成越界测试与LLM内容安全的动态评测

发布时间：2025年05月07日

`LLM应用` `图像生成` `内容安全`

> Unmasking the Canvas: A Dynamic Benchmark for Image Generation Jailbreaking and LLM Content Safety

# 摘要

> 现有大型语言模型（LLMs）在图像生成领域取得了显著进展，但其内容安全防护仍易受基于提示的越狱攻击。通过在ChatGPT、MetaAI和Grok等平台上的初步测试发现，即使是简短自然的提示，也可能生成从伪造文件到名人形象篡改等不当内容。

我们推出"Unmasking the Canvas" (UTC基准; UTCB)——一个动态可扩展的基准数据集，用于评估LLM在图像生成中的安全漏洞。本方法结合了结构化提示工程、多语言混淆（如祖鲁语、盖尔语、Base64编码）以及基于Grok托管LLaMA-3的评估。该流水线支持零样本和回退提示策略、风险评分及自动化标签功能。所有生成内容均附带丰富元数据，并分类为青铜（未经验证）、白银（LLM辅助验证）和黄金（人工验证）三个等级。UTCB将随时间演进，纳入更多数据源、提示模板和模型行为。

警告：本文包含用于测试模型安全性的对抗性输入示例。所有输出均已做遮挡处理，确保负责任的信息披露。


> Existing large language models (LLMs) are advancing rapidly and produce outstanding results in image generation tasks, yet their content safety checks remain vulnerable to prompt-based jailbreaks. Through preliminary testing on platforms such as ChatGPT, MetaAI, and Grok, we observed that even short, natural prompts could lead to the generation of compromising images ranging from realistic depictions of forged documents to manipulated images of public figures.
  We introduce Unmasking the Canvas (UTC Benchmark; UTCB), a dynamic and scalable benchmark dataset to evaluate LLM vulnerability in image generation. Our methodology combines structured prompt engineering, multilingual obfuscation (e.g., Zulu, Gaelic, Base64), and evaluation using Groq-hosted LLaMA-3. The pipeline supports both zero-shot and fallback prompting strategies, risk scoring, and automated tagging. All generations are stored with rich metadata and curated into Bronze (non-verified), Silver (LLM-aided verification), and Gold (manually verified) tiers. UTCB is designed to evolve over time with new data sources, prompt templates, and model behaviors.
  Warning: This paper includes visual examples of adversarial inputs designed to test model safety. All outputs have been redacted to ensure responsible disclosure.

[Arxiv](https://arxiv.org/abs/2505.04146)