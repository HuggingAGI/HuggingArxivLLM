# # **摘要**  
    PokéAI：一个为目标生成与战斗优化设计的《宝可梦红》多智能体系统

发布时间：2025年06月30日

`Agent` `多智能体系统`

> PokéAI: A Goal-Generating, Battle-Optimizing Multi-agent System for Pokemon Red

# 摘要

> 我们推出首个专为自主畅玩《宝可梦红》而设计的文本基础、多智能体大型语言模型（LLM）框架——PokéAI。我们的系统由三个专业代理组成：规划、执行和 critique，每个代理都拥有独立的记忆库、职责和技能集。

- 规划代理作为核心大脑，负责生成推进游戏的任务。
- 这些任务随后由执行代理在游戏环境中执行。
- 任务完成后，critique 代理会对结果进行评估，判断目标是否达成。
- 评估结束后，控制权返回规划代理，形成一个闭环决策系统。

在初步开发中，我们为执行代理打造了一个战斗模块。测试结果显示：
- AI 在 50 次野生遭遇中平均胜率达到 80.8%，与人类高手仅相差 6%。
- 模型的战斗表现与其在语言任务上的 LLM Arena 成绩高度相关，这表明语言能力和战略推理能力密切相关。
- 游戏日志分析显示，每个 LLM 都展现出独特的玩法风格，这表明不同模型会发展出各具特色的战略行为。


> We introduce PokéAI, the first text-based, multi-agent large language model (LLM) framework designed to autonomously play and progress through Pokémon Red. Our system consists of three specialized agents-Planning, Execution, and Critique-each with its own memory bank, role, and skill set. The Planning Agent functions as the central brain, generating tasks to progress through the game. These tasks are then delegated to the Execution Agent, which carries them out within the game environment. Upon task completion, the Critique Agent evaluates the outcome to determine whether the objective was successfully achieved. Once verification is complete, control returns to the Planning Agent, forming a closed-loop decision-making system.
  As a preliminary step, we developed a battle module within the Execution Agent. Our results show that the battle AI achieves an average win rate of 80.8% across 50 wild encounters, only 6% lower than the performance of an experienced human player. Furthermore, we find that a model's battle performance correlates strongly with its LLM Arena score on language-related tasks, indicating a meaningful link between linguistic ability and strategic reasoning. Finally, our analysis of gameplay logs reveals that each LLM exhibits a unique playstyle, suggesting that individual models develop distinct strategic behaviors.

[Arxiv](https://arxiv.org/abs/2506.23689)