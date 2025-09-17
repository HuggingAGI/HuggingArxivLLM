# 参数化技能赋能大型语言模型（LLMs）：对抗性长程规划

发布时间：2025年09月16日

`Agent` `媒体与娱乐`

> Empowering LLMs with Parameterized Skills for Adversarial Long-Horizon Planning

# 摘要

> 大型语言模型（LLMs）的最新进展催生了基于LLM的AI智能体。其中的关键挑战在于：如何让智能体在复杂、对抗性的长程环境中有效落地。现有方法主要分为两类：（1）将LLMs用作策略，通过生成低层级可行动作与环境交互；（2）利用LLMs生成高层级任务或语言指导，以驱动动作生成。但前者难以生成可靠动作，后者则严重依赖专家经验将高层级任务转化为具体动作序列。为应对这些挑战，我们提出了“语言规划-参数行动”（PLAP）规划框架，助力基于LLM的智能体在长程环境中有效落地。PLAP方法包含三个核心组件：（1）技能库，内含环境特定的参数化技能；（2）由LLMs驱动的技能规划器；（3）技能执行器，将参数化技能转化为可执行动作序列。我们在MicroRTS中部署了PLAP——这是一款长程实时战略游戏，为LLMs提供了陌生且极具挑战性的环境。实验结果验证了PLAP的有效性：在零样本设置下，GPT-4o驱动的PLAP性能优于80%的基线智能体；而借助精心设计的少量样本示例，Qwen2-72B驱动的PLAP甚至超越了顶级脚本智能体CoacAI。此外，我们设计了全面的评估指标，在PLAP框架内测试了6个闭源和2个开源LLM，并最终发布了长程技能规划能力的LLM排行榜。我们的代码已开源，地址为https://github.com/AI-Research-TeamX/PLAP。

> Recent advancements in Large Language Models(LLMs) have led to the development of LLM-based AI agents. A key challenge is the creation of agents that can effectively ground themselves in complex, adversarial long-horizon environments. Existing methods mainly focus on (1) using LLMs as policies to interact with the environment through generating low-level feasible actions, and (2) utilizing LLMs to generate high-level tasks or language guides to stimulate action generation. However, the former struggles to generate reliable actions, while the latter relies heavily on expert experience to translate high-level tasks into specific action sequences. To address these challenges, we introduce the Plan with Language, Act with Parameter (PLAP) planning framework that facilitates the grounding of LLM-based agents in long-horizon environments. The PLAP method comprises three key components: (1) a skill library containing environment-specific parameterized skills, (2) a skill planner powered by LLMs, and (3) a skill executor converting the parameterized skills into executable action sequences. We implement PLAP in MicroRTS, a long-horizon real-time strategy game that provides an unfamiliar and challenging environment for LLMs. The experimental results demonstrate the effectiveness of PLAP. In particular, GPT-4o-driven PLAP in a zero-shot setting outperforms 80% of baseline agents, and Qwen2-72B-driven PLAP, with carefully crafted few-shot examples, surpasses the top-tier scripted agent, CoacAI. Additionally, we design comprehensive evaluation metrics and test 6 closed-source and 2 open-source LLMs within the PLAP framework, ultimately releasing an LLM leaderboard ranking long-horizon skill planning ability. Our code is available at https://github.com/AI-Research-TeamX/PLAP.

[Arxiv](https://arxiv.org/abs/2509.13127)