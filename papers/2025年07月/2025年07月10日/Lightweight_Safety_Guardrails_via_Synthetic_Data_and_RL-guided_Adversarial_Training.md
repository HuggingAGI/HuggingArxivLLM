# 轻量级安全防护：利用合成数据与强化学习引导的对抗训练

发布时间：2025年07月10日

`LLM应用` `互联网安全` `内容审核`

> Lightweight Safety Guardrails via Synthetic Data and RL-guided Adversarial Training

# 摘要

> 我们推出了一款轻量级且高效的语言模型安全护栏框架，证明小型语言模型在内容审核任务中不仅能够匹敌，甚至超越大型模型的表现。这一突破得益于高保真合成数据生成与对抗训练的结合。我们的合成数据生成始于人工精选的种子数据，通过查询增强和改写生成多样且语境丰富的示例。这些数据经过多轮精炼，确保高保真度和相关性。借鉴生成对抗网络（GAN）架构的最新进展，我们的对抗训练采用强化学习引导生成器，生产具有挑战性的合成示例。这些示例用于微调安全分类器，显著提升了其检测和缓解有害内容的能力。此外，我们融合了近期关于高效LLM训练的研究策略，利用小型模型的优势来优化大型生成模型的表现。通过迭代的对抗训练和生成多样、高质量的合成数据，我们的框架使小型语言模型（SLMs）能够充当坚固的安全护栏。这一创新不仅降低了计算成本，还增强了抵御对抗攻击的能力，为AI系统的内容审核提供了一个高效且可扩展的解决方案。

> We introduce a lightweight yet highly effective safety guardrail framework for language models, demonstrating that small-scale language models can achieve, and even surpass, the performance of larger counterparts in content moderation tasks. This is accomplished through high-fidelity synthetic data generation and adversarial training. The synthetic data generation process begins with human-curated seed data, which undergoes query augmentation and paraphrasing to create diverse and contextually rich examples. This augmented data is then subjected to multiple rounds of curation, ensuring high fidelity and relevance. Inspired by recent advances in the Generative Adversarial Network (GAN) architecture, our adversarial training employs reinforcement learning to guide a generator that produces challenging synthetic examples. These examples are used to fine-tune the safety classifier, enhancing its ability to detect and mitigate harmful content. Additionally, we incorporate strategies from recent research on efficient LLM training, leveraging the capabilities of smaller models to improve the performance of larger generative models. With iterative adversarial training and the generation of diverse, high-quality synthetic data, our framework enables small language models (SLMs) to serve as robust safety guardrails. This approach not only reduces computational overhead but also enhances resilience against adversarial attacks, offering a scalable and efficient solution for content moderation in AI systems.

[Arxiv](https://arxiv.org/abs/2507.08284)