# 通过少量示例学习具身智能体的多模态基础规划与高效重新规划

发布时间：2024年12月23日

`Agent` `机器人` `人工智能`

> Multi-Modal Grounded Planning and Efficient Replanning For Learning Embodied Agents with A Few Examples

# 摘要

> 学习用于机器人助手的感知与推理模块，使其能依据自然语言指令规划执行复杂任务的步骤，这往往需要大量自由形式的语言注释，短高级指令尤甚。为降低注释成本，大型语言模型（LLMs）被当作数据量少的规划器使用。但在细化步骤时，即便是使用LLMs的顶尖规划器，也多依赖语言常识，常忽视接收指令时的环境状态，致使规划不当。为生成基于环境的规划，我们提出了FLARE（具有环境自适应重新规划的少样本语言具身智能体），它通过语言指令和环境感知来优化任务规划。鉴于语言指令常含歧义或错误表述，我们还提议借助智能体的视觉线索来纠错。所提方案借助视觉线索，让我们能用少量语言对，且表现优于前沿方法。我们的代码可在https://github.com/snumprlab/flare获取。

> Learning a perception and reasoning module for robotic assistants to plan steps to perform complex tasks based on natural language instructions often requires large free-form language annotations, especially for short high-level instructions. To reduce the cost of annotation, large language models (LLMs) are used as a planner with few data. However, when elaborating the steps, even the state-of-the-art planner that uses LLMs mostly relies on linguistic common sense, often neglecting the status of the environment at command reception, resulting in inappropriate plans. To generate plans grounded in the environment, we propose FLARE (Few-shot Language with environmental Adaptive Replanning Embodied agent), which improves task planning using both language command and environmental perception. As language instructions often contain ambiguities or incorrect expressions, we additionally propose to correct the mistakes using visual cues from the agent. The proposed scheme allows us to use a few language pairs thanks to the visual cues and outperforms state-of-the-art approaches. Our code is available at https://github.com/snumprlab/flare.

[Arxiv](https://arxiv.org/abs/2412.17288)