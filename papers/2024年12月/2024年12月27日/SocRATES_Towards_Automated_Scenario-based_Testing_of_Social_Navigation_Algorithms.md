# SocRATES：致力于实现社交导航算法基于场景的自动化测试

发布时间：2024年12月27日

`LLM应用` `机器人` `社会导航`

> SocRATES: Towards Automated Scenario-based Testing of Social Navigation Algorithms

# 摘要

> 当前的社会导航方法和基准重点多在空间关系与任务效率上。虽说这些因素很关键，但像对机器人社交能力的看法这类定性方面，对于成功被采用并融入人类环境也同等重要。我们建议通过基于场景的测试来更全面地评估社会导航，特定的人机交互场景能揭示关键的机器人行为。然而，创建此类场景往往费力又复杂。在这项工作中，我们引入了一个管道来应对此挑战，它能自动生成契合上下文和位置的社会导航场景，以供模拟。我们的管道能把简单的场景元数据转化为详细的文本场景，推断行人和机器人的轨迹，并模拟行人行为，从而实现更可控的评估。我们借助大型语言模型（LLMs）的社会推理和代码生成能力来简化场景生成与转换。我们的实验表明，我们的管道生成的场景逼真，在场景转换方面显著优于简单的 LLM 提示。另外，我们还给出了来自社会导航专家可用性研究的初步反馈，以及一个展示对三种导航算法进行基于场景评估的案例研究。

> Current social navigation methods and benchmarks primarily focus on proxemics and task efficiency. While these factors are important, qualitative aspects such as perceptions of a robot's social competence are equally crucial for successful adoption and integration into human environments. We propose a more comprehensive evaluation of social navigation through scenario-based testing, where specific human-robot interaction scenarios can reveal key robot behaviors. However, creating such scenarios is often labor-intensive and complex. In this work, we address this challenge by introducing a pipeline that automates the generation of context-, and location-appropriate social navigation scenarios, ready for simulation. Our pipeline transforms simple scenario metadata into detailed textual scenarios, infers pedestrian and robot trajectories, and simulates pedestrian behaviors, which enables more controlled evaluation. We leverage the social reasoning and code-generation capabilities of Large Language Models (LLMs) to streamline scenario generation and translation. Our experiments show that our pipeline produces realistic scenarios and significantly improves scenario translation over naive LLM prompting. Additionally, we present initial feedback from a usability study with social navigation experts and a case-study demonstrating a scenario-based evaluation of three navigation algorithms.

[Arxiv](https://arxiv.org/abs/2412.19595)