# 基于LLMs从开发者话语自动生成半导体设备控制代码

发布时间：2025年09月16日

`LLM应用` `工业与制造`

> Automating Code Generation for Semiconductor Equipment Control from Developer Utterances with LLMs

# 摘要

> 半导体是现代电子设备的核心支柱，其制造与测试离不开高度专业化的设备和特定领域的编程语言。设备语言（如算法模式生成器（ALPG））是实现精确硬件控制的关键，但因其低级语法和陡峭的学习曲线，编程门槛较高。尽管大型语言模型（LLMs）在自然语言生成高级代码方面已展现潜力，但其在低级设备语言上的表现仍有局限。为此，我们提出渐进式知识增强（PKE）——一种新颖的多阶段提示框架，它能逐步提取并激活LLMs中的潜在知识，引导模型从简单示例过渡到复杂场景，且无需大量微调。在工业ALPG数据集上的实证评估显示，PKE在生成正确ALPG代码方面不仅显著优于标准提示，还超越了现有最先进方法——与次优技术相比，其精确匹配分数分别提升了11.1%和15.2%。对各组件的深入分析证实，基于难度的渐进式知识提取能有效提升准确性。本研究为增强LLMs在特定低级编程任务中的能力提供了实用方案，助力半导体软件开发效率的提升。

> Semiconductors form the backbone of modern electronics, with their manufacturing and testing relying on highly specialized equipment and domain-specific programming languages. Equipment languages such as the Algorithmic Pattern Generator (ALPG) are critical for precise hardware control but are challenging to program due to their low-level syntax and steep learning curve. While large language models (LLMs) have shown promise in generating high-level code from natural language, their effectiveness on low-level equipment languages remains limited. To address this, we propose Progressive Knowledge Enhancement (PKE), a novel multi-stage prompting framework that progressively extracts and activates the latent knowledge within LLMs, guiding them from simple to complex examples without extensive fine-tuning. Empirical evaluation on an industrial ALPG dataset shows that PKE significantly outperforms standard prompting and surpasses state-of-the-art methods in generating correct ALPG code, achieving 11.1\% and 15.2\% higher exact match scores compared to the second-best technique. Further analysis of individual components confirms that progressive knowledge extraction based on difficulty enhances accuracy. Our study offer a practical approach to boosting LLM capabilities for specialized low-level programming, supporting greater productivity in semiconductor software development.

[Arxiv](https://arxiv.org/abs/2509.13055)