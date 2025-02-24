# # CurricuVLM: 通过个性化安全关键课程学习与视觉语言模型实现安全自动驾驶

发布时间：2025年02月20日

`Agent

理由：这篇论文专注于自动驾驶系统的安全性，通过视觉语言模型（VLM）实现个性化课程学习，提升自动驾驶代理的行为和训练场景生成。其核心应用在智能体的行为优化和学习框架上，属于Agent领域。` `自动驾驶` `智能驾驶`

> CurricuVLM: Towards Safe Autonomous Driving via Personalized Safety-Critical Curriculum Learning with Vision-Language Models

# 摘要

> 自动驾驶系统的安全性保障仍是关键挑战，特别是在应对罕见但可能造成灾难性后果的安全关键场景时。现有研究虽已探索了为自动驾驶汽车（AV）测试生成安全关键场景的方法，但如何有效将这些场景整合到策略学习中以提升安全性仍鲜有研究。此外，开发能够适应自动驾驶汽车行为模式演变和性能瓶颈的训练课程仍是一个未被充分探索的领域。

为应对这些挑战，我们提出了CurricuVLM，一个创新框架，该框架利用视觉语言模型（VLM）实现自动驾驶代理的个性化课程学习。我们的方法独特地利用了VLM的多模态理解能力，用于分析代理行为、识别性能弱点，并动态生成定制化训练场景以实现课程适应。通过全面分析具有叙述性描述的不安全驾驶情境，CurricuVLM进行深入推理，评估自动驾驶汽车的能力并识别关键行为模式。随后，该框架合成针对这些识别限制的定制化训练场景，从而实现有效且个性化的课程学习。

在Waymo开放运动数据集上的广泛实验表明，CurricuVLM在常规和安全关键场景中均超越了现有的先进基线，在导航成功率、驾驶效率和安全指标方面表现更优。进一步分析表明，CurricuVLM作为一种通用方法，可与各种强化学习算法集成，以提升自动驾驶系统。代码和演示视频可在：https://zihaosheng.github.io/CurricuVLM/获取。

> Ensuring safety in autonomous driving systems remains a critical challenge, particularly in handling rare but potentially catastrophic safety-critical scenarios. While existing research has explored generating safety-critical scenarios for autonomous vehicle (AV) testing, there is limited work on effectively incorporating these scenarios into policy learning to enhance safety. Furthermore, developing training curricula that adapt to an AV's evolving behavioral patterns and performance bottlenecks remains largely unexplored. To address these challenges, we propose CurricuVLM, a novel framework that leverages Vision-Language Models (VLMs) to enable personalized curriculum learning for autonomous driving agents. Our approach uniquely exploits VLMs' multimodal understanding capabilities to analyze agent behavior, identify performance weaknesses, and dynamically generate tailored training scenarios for curriculum adaptation. Through comprehensive analysis of unsafe driving situations with narrative descriptions, CurricuVLM performs in-depth reasoning to evaluate the AV's capabilities and identify critical behavioral patterns. The framework then synthesizes customized training scenarios targeting these identified limitations, enabling effective and personalized curriculum learning. Extensive experiments on the Waymo Open Motion Dataset show that CurricuVLM outperforms state-of-the-art baselines across both regular and safety-critical scenarios, achieving superior performance in terms of navigation success, driving efficiency, and safety metrics. Further analysis reveals that CurricuVLM serves as a general approach that can be integrated with various RL algorithms to enhance autonomous driving systems. The code and demo video are available at: https://zihaosheng.github.io/CurricuVLM/.

[Arxiv](https://arxiv.org/abs/2502.15119)