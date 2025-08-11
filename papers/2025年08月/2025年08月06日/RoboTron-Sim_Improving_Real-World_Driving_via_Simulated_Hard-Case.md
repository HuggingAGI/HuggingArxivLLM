# RoboTron-Sim：借助模拟极端场景提升真实驾驶能力

发布时间：2025年08月06日

`LLM应用` `自动驾驶` `数据科学`

> RoboTron-Sim: Improving Real-World Driving via Simulated Hard-Case

# 摘要

> 在自动驾驶领域，收集罕见高风险场景、长尾驾驶事件及复杂交互的现实数据仍然充满挑战，这也导致现有系统在关键情境下表现欠佳。为解决这一问题，我们提出了RoboTron-Sim，通过模拟困难案例来提升关键场景下的驾驶性能。具体而言，我们开发了包含13类高风险边缘案例的HASS数据集，覆盖昼夜、晴雨等多种平衡环境条件。同时，我们提出了场景感知提示工程（SPE）和图像到 ego 编码器（I2E 编码器），帮助多模态大模型从HASS中学习现实中的复杂驾驶技能，并适应真实与模拟场景间的环境与硬件差异。实验结果表明，RoboTron-Sim在挑战性场景中将驾驶性能提升了约50%，在现实世界的开环规划任务中达到顶尖水准。定性分析进一步证实了其在处理罕见高风险驾驶场景中的有效性。项目详情请访问：https://stars79689.github.io/RoboTron-Sim/

> Collecting real-world data for rare high-risk scenarios, long-tailed driving events, and complex interactions remains challenging, leading to poor performance of existing autonomous driving systems in these critical situations. In this paper, we propose RoboTron-Sim that improves real-world driving in critical situations by utilizing simulated hard cases. First, we develop a simulated dataset called Hard-case Augmented Synthetic Scenarios (HASS), which covers 13 high-risk edge-case categories, as well as balanced environmental conditions such as day/night and sunny/rainy. Second, we introduce Scenario-aware Prompt Engineering (SPE) and an Image-to-Ego Encoder (I2E Encoder) to enable multimodal large language models to effectively learn real-world challenging driving skills from HASS, via adapting to environmental deviations and hardware differences between real-world and simulated scenarios. Extensive experiments on nuScenes show that RoboTron-Sim improves driving performance in challenging scenarios by around 50%, achieving state-of-the-art results in real-world open-loop planning. Qualitative results further demonstrate the effectiveness of RoboTron-Sim in better managing rare high-risk driving scenarios. Project page: https://stars79689.github.io/RoboTron-Sim/

[Arxiv](https://arxiv.org/abs/2508.04642)