# 为语义安全生成机器人宪章与基准测试

发布时间：2025年03月11日

`Agent` `机器人安全` `人工智能`

> Generating Robot Constitutions & Benchmarks for Semantic Safety

# 摘要

> 机器人安全研究曾长期聚焦于机器人周边环境中的避障与风险降低。大型视觉语言模型（VLMs）的出现，赋予了机器人更高级的语义场景理解能力以及与人类的自然语言交互能力。尽管VLMs存在已知漏洞（如幻觉或越狱风险），但它们正在被赋予控制能够与现实世界进行物理接触的机器人的能力。这种做法可能引发危险行为，使机器人语义安全成为亟待关注的问题。本文贡献分为两部分：首先，为应对这些新兴风险，我们发布了ASIMOV基准测试，这是一个大规模、全面的机器人基础模型语义安全评估与改进数据集集合。我们的数据生成方法具有高度可扩展性：通过文本和图像生成技术，我们从现实世界视觉场景和医院的人体伤害报告中生成不良情况。其次，我们开发了一个框架，能够从现实世界数据中自动生成机器人宪法，利用宪法AI机制引导机器人的行为。我们提出了一种新型的自动修正流程，能够在行为规则中引入细微差别，从而增强与人类对行为可接受性和安全性的偏好一致。我们探索了在不同长度的多样化宪法之间的一般性和特定性之间的权衡，并证明机器人能够有效拒绝违宪行为。在ASIMOV基准测试中，使用生成的宪法，我们达到了84.3%的最高对齐率，超过了无宪法基线和人工编写的宪法。数据可在asimov-benchmark.github.io获取

> Until recently, robotics safety research was predominantly about collision avoidance and hazard reduction in the immediate vicinity of a robot. Since the advent of large vision and language models (VLMs), robots are now also capable of higher-level semantic scene understanding and natural language interactions with humans. Despite their known vulnerabilities (e.g. hallucinations or jail-breaking), VLMs are being handed control of robots capable of physical contact with the real world. This can lead to dangerous behaviors, making semantic safety for robots a matter of immediate concern. Our contributions in this paper are two fold: first, to address these emerging risks, we release the ASIMOV Benchmark, a large-scale and comprehensive collection of datasets for evaluating and improving semantic safety of foundation models serving as robot brains. Our data generation recipe is highly scalable: by leveraging text and image generation techniques, we generate undesirable situations from real-world visual scenes and human injury reports from hospitals. Secondly, we develop a framework to automatically generate robot constitutions from real-world data to steer a robot's behavior using Constitutional AI mechanisms. We propose a novel auto-amending process that is able to introduce nuances in written rules of behavior; this can lead to increased alignment with human preferences on behavior desirability and safety. We explore trade-offs between generality and specificity across a diverse set of constitutions of different lengths, and demonstrate that a robot is able to effectively reject unconstitutional actions. We measure a top alignment rate of 84.3% on the ASIMOV Benchmark using generated constitutions, outperforming no-constitution baselines and human-written constitutions. Data is available at asimov-benchmark.github.io

[Arxiv](https://arxiv.org/abs/2503.08663)