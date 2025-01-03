# Xmodel-2 技术报告

发布时间：2024年12月27日

`LLM理论

理由：这篇论文主要介绍了Xmodel-2这一大型语言模型的架构设计、训练策略和性能表现，特别是其在推理任务中的表现。论文内容集中在模型的设计和训练方法上，属于对大型语言模型的理论研究和优化，因此应归类为LLM理论。` `人工智能`

> Xmodel-2 Technical Report

# 摘要

> Xmodel-2 是一款专为推理任务打造的 12 亿参数大型语言模型。其独特架构支持不同规模的模型共享统一超参数，便于在小模型上广泛实验，并将最优配置无缝迁移至大模型。为提升训练效率和稳定性，Xmodel-2 采用了 MiniCPM 的 WSD 学习率调度器。通过在 1.5 万亿个多样化 token 上进行预训练，Xmodel-2 在复杂推理和智能体任务中表现卓越，同时训练成本低廉。这些成果彰显了高效模型设计与训练策略在推动推理能力进步中的巨大潜力。模型检查点和代码已开源，详见 GitHub：https://github.com/XiaoduoAILab/Xmodel-2

> Xmodel-2 is a 1.2-billion-parameter large language model designed specifically for reasoning tasks. Its architecture enables different model scales to share a unified set of hyperparameters, allowing for extensive experimentation on smaller models and seamless transfer of optimal configurations to larger models. To maximize training efficiency and stability, Xmodel-2 employs the WSD learning rate scheduler from MiniCPM. Pretrained on 1.5 trillion tokens from diverse sources, Xmodel-2 achieves state-of-the-art performance in complex reasoning and agent-based tasks, while maintaining low training costs. These results highlight the potential of efficient model design and training strategies in advancing reasoning capabilities. Model checkpoints and code are publicly available on GitHub at https://github.com/XiaoduoAILab/Xmodel-2

[Arxiv](https://arxiv.org/abs/2412.19638)