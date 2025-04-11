# # 更优决策：选择合适的因果世界模型
选择合适的因果世界模型，助力更优决策。

发布时间：2025年04月09日

`Agent` `因果推理`

> Better Decisions through the Right Causal World Model

# 摘要

> 强化学习（RL）代理在各种环境中展现出卓越的能力，能够直接从感官输入中发现有效策略。然而，这些代理常常过度依赖训练数据中的虚假相关性，导致行为缺乏稳健性，难以推广到新环境或稍作修改的环境。为解决这一问题，我们提出了一种新型算法——因果对象中心模型提取工具（COMET），它专注于学习精确且可解释的因果世界模型（CWMs）。COMET通过从观察中提取对象中心的状态描述，并识别与对象属性相关的环境内部状态。借助符号回归技术，COMET建模对象中心的转换过程，揭示控制对象动态的因果关系。此外，COMET还集成了大型语言模型（LLMs）进行语义推理，对因果变量进行注释以提升可解释性。通过这些功能，COMET构建的CWMs与环境的真实因果结构高度一致，使代理能够专注于任务相关的核心特征。这种CWMs的应用有效避免了捷径依赖，使RL系统能够在动态场景中实现更优的规划与决策。我们的实验结果在Pong和Freeway等Atari环境中得到了验证，充分展示了COMET的准确性和鲁棒性，彰显了其在强化学习领域中连接对象中心推理与因果推理的潜力。

> Reinforcement learning (RL) agents have shown remarkable performances in various environments, where they can discover effective policies directly from sensory inputs. However, these agents often exploit spurious correlations in the training data, resulting in brittle behaviours that fail to generalize to new or slightly modified environments. To address this, we introduce the Causal Object-centric Model Extraction Tool (COMET), a novel algorithm designed to learn the exact interpretable causal world models (CWMs). COMET first extracts object-centric state descriptions from observations and identifies the environment's internal states related to the depicted objects' properties. Using symbolic regression, it models object-centric transitions and derives causal relationships governing object dynamics. COMET further incorporates large language models (LLMs) for semantic inference, annotating causal variables to enhance interpretability.
  By leveraging these capabilities, COMET constructs CWMs that align with the true causal structure of the environment, enabling agents to focus on task-relevant features. The extracted CWMs mitigate the danger of shortcuts, permitting the development of RL systems capable of better planning and decision-making across dynamic scenarios. Our results, validated in Atari environments such as Pong and Freeway, demonstrate the accuracy and robustness of COMET, highlighting its potential to bridge the gap between object-centric reasoning and causal inference in reinforcement learning.

[Arxiv](https://arxiv.org/abs/2504.07257)