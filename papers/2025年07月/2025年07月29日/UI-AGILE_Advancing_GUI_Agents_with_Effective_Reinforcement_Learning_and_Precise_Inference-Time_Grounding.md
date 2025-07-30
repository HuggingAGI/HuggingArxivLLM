# UI-AGILE: 助力 GUI 代理发展，结合有效强化学习与精准推理时刻接地

发布时间：2025年07月29日

`Agent` `人机交互` `图形用户界面`

> UI-AGILE: Advancing GUI Agents with Effective Reinforcement Learning and Precise Inference-Time Grounding

# 摘要

> 多模态大型语言模型（MLLMs）的崛起显著提升了图形用户界面（GUI）代理的能力。然而，现有的训练和推理方法仍面临推理设计、奖励机制不力及视觉噪声的多重挑战。为解决这些问题，我们推出UI-AGILE框架，全面优化GUI代理的训练与推理过程。在训练方面，我们对监督微调（SFT）进行了三项关键改进：1）引入连续奖励函数，激励高精度接地；2）设计“简单思考”奖励机制，平衡规划速度与接地准确性；3）采用基于裁剪的重采样策略，缓解稀疏奖励问题并提升复杂任务的学习效果。在推理方面，我们创新性地提出“带选择的分解接地”方法，通过将图像分割为更小、更易处理的部分，显著提升了高分辨率显示下的接地准确性。实验结果表明，UI-AGILE在ScreenSpot-Pro和ScreenSpot-v2两个基准测试中均达到当前最佳性能。例如，在ScreenSpot-Pro上，结合我们的训练和推理增强方法，与最佳基线相比，接地准确性提升了23%。

> The emergence of Multimodal Large Language Models (MLLMs) has driven significant advances in Graphical User Interface (GUI) agent capabilities. Nevertheless, existing GUI agent training and inference techniques still suffer from a dilemma for reasoning designs, ineffective reward, and visual noise. To address these issues, we introduce UI-AGILE, a comprehensive framework enhancing GUI agents at both the training and inference stages. For training, we propose a suite of improvements to the Supervised Fine-Tuning (SFT) process: 1) a Continuous Reward function to incentivize high-precision grounding; 2) a "Simple Thinking" reward to balance planning with speed and grounding accuracy; and 3) a Cropping-based Resampling strategy to mitigate the sparse reward problem and improve learning on complex tasks. For inference, we present Decomposed Grounding with Selection, a novel method that dramatically improves grounding accuracy on high-resolution displays by breaking the image into smaller, manageable parts. Experiments show that UI-AGILE achieves the state-of-the-art performance on two benchmarks ScreenSpot-Pro and ScreenSpot-v2. For instance, using both our proposed training and inference enhancement methods brings 23% grounding accuracy improvement over the best baseline on ScreenSpot-Pro.

[Arxiv](https://arxiv.org/abs/2507.22025)