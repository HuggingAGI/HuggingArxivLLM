# ManeuverGPT：智能控制技术实现安全自主特技操作

发布时间：2025年03月11日

`Agent` `自动驾驶` `主动安全`

> ManeuverGPT Agentic Control for Safe Autonomous Stunt Maneuvers

# 摘要

> 自动驾驶汽车的下一代主动安全技术，应当像职业特技车手一样，能够在车辆操控极限内安全执行高敏捷性紧急避险动作。本文提出了一种名为ManeuverGPT的创新框架，通过基于大型语言模型（LLM）的代理作为控制器，在自动驾驶车辆中生成和执行高动态特技动作。我们以CARLA模拟环境中的J-turn等激进动作为研究目标，展示了一种基于迭代提示的优化方法，从零开始优化车辆控制参数，无需重新训练模型权重。

我们设计了一种由三个专门代理组成的智能体架构：
1. 查询丰富剂（Query Enricher Agent），负责为用户命令提供上下文；
2. 驾驶员剂（Driver Agent），负责生成动作参数；
3. 参数验证剂（Parameter Validator Agent），负责施加基于物理和安全的约束条件。

实验结果表明，通过适应不同车辆动态的文本提示，成功在多个车辆模型上实现了J-turn动作的执行。我们采用既定的成功标准评估了性能表现，并讨论了数值精度和场景复杂度方面的限制。研究发现不仅凸显了LLM驱动控制在实现灵活高动态动作方面的潜力，还强调了结合基于语言的推理与算法验证的混合方法的重要性。

> The next generation of active safety features in autonomous vehicles should be capable of safely executing evasive hazard-avoidance maneuvers akin to those performed by professional stunt drivers to achieve high-agility motion at the limits of vehicle handling. This paper presents a novel framework, ManeuverGPT, for generating and executing high-dynamic stunt maneuvers in autonomous vehicles using large language model (LLM)-based agents as controllers. We target aggressive maneuvers, such as J-turns, within the CARLA simulation environment and demonstrate an iterative, prompt-based approach to refine vehicle control parameters, starting tabula rasa without retraining model weights. We propose an agentic architecture comprised of three specialized agents (1) a Query Enricher Agent for contextualizing user commands, (2) a Driver Agent for generating maneuver parameters, and (3) a Parameter Validator Agent that enforces physics-based and safety constraints. Experimental results demonstrate successful J-turn execution across multiple vehicle models through textual prompts that adapt to differing vehicle dynamics. We evaluate performance via established success criteria and discuss limitations regarding numeric precision and scenario complexity. Our findings underscore the potential of LLM-driven control for flexible, high-dynamic maneuvers, while highlighting the importance of hybrid approaches that combine language-based reasoning with algorithmic validation.

[Arxiv](https://arxiv.org/abs/2503.09035)