# MultiMind：结合多模态推理与心智理论，提升狼人智能体的能力

发布时间：2025年04月24日

`LLM应用` `社交推理` `多模态`

> MultiMind: Enhancing Werewolf Agents with Multimodal Reasoning and Theory of Mind

# 摘要

> 大型语言模型（LLM）代理在狼人杀等需要战略推理和社会欺骗的社交推理游戏中展现了出色能力。然而，现有方法仅局限于文本信息，忽视了面部表情和语调等人类自然交流中至关重要的多模态线索。此外，现有社交推理游戏代理主要关注推断其他玩家身份，而未建模他人对自己或队友的看法。为解决这些局限，我们以《终极狼人杀》为试验平台，提出MultiMind——首个将多模态信息整合到社交推理游戏代理中的框架。MultiMind不仅处理面部表情和语调，还结合言语内容，并采用心智理论（ToM）模型来表示每个玩家对其他人的怀疑程度。通过将ToM模型与蒙特卡洛树搜索（MCTS）相结合，我们的代理能够识别出将怀疑最小化指向自身的沟通策略。通过在代理对战模拟和与真人玩家的研究中进行的全面评估，我们展示了MultiMind在游戏玩法中的优越表现。我们的工作朝着创建具备跨多模态领域类人社交推理能力的LLM代理迈出了重要一步。

> Large Language Model (LLM) agents have demonstrated impressive capabilities in social deduction games (SDGs) like Werewolf, where strategic reasoning and social deception are essential. However, current approaches remain limited to textual information, ignoring crucial multimodal cues such as facial expressions and tone of voice that humans naturally use to communicate. Moreover, existing SDG agents primarily focus on inferring other players' identities without modeling how others perceive themselves or fellow players. To address these limitations, we use One Night Ultimate Werewolf (ONUW) as a testbed and present MultiMind, the first framework integrating multimodal information into SDG agents. MultiMind processes facial expressions and vocal tones alongside verbal content, while employing a Theory of Mind (ToM) model to represent each player's suspicion levels toward others. By combining this ToM model with Monte Carlo Tree Search (MCTS), our agent identifies communication strategies that minimize suspicion directed at itself. Through comprehensive evaluation in both agent-versus-agent simulations and studies with human players, we demonstrate MultiMind's superior performance in gameplay. Our work presents a significant advancement toward LLM agents capable of human-like social reasoning across multimodal domains.

[Arxiv](https://arxiv.org/abs/2504.18039)