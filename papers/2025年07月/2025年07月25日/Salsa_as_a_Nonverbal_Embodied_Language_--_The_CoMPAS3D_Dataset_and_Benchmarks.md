# 萨尔萨舞：一种非语言性具身语言 -- CoMPAS3D 数据集与基准测试

发布时间：2025年07月25日

`Agent

理由：这篇论文专注于开发能够与人类共舞的人形机器人，探讨智能体之间的互动和协作，特别是通过肢体动作和触觉信号。虽然提到了大型语言模型的应用，但主要贡献在于动作捕捉数据集和模型的开发，属于智能体（Agent）的研究领域。` `机器人` `动作捕捉`

> Salsa as a Nonverbal Embodied Language -- The CoMPAS3D Dataset and Benchmarks

# 摘要

> 设想一个能够安全且富有创意地与人类共舞的人形机器人，它能根据舞伴的水平灵活调整，并以触觉信号为主要沟通方式。虽然当前的AI系统在基于大型语言模型的文本或语音交互中表现出色，但人类的交流远不止于文字——它还包括肢体动作、时机和物理协调。两个智能体之间的耦合互动建模是一项极具挑战性的任务：这种互动是连续的、双向反应的，并受到个体差异的影响。我们推出了CoMPAS3D，这是目前规模最大、种类最丰富的即兴萨尔萨舞动作捕捉数据集，旨在作为交互式、富有表现力的人形AI的测试平台。该数据集包含18名舞者表演的3小时即兴萨尔萨舞，涵盖了初学者、中等水平和专业水平的舞者。我们首次提供了细致的萨尔萨舞专家注释，覆盖了2800多个动作片段，包括动作类型、组合、执行错误和风格元素。我们将伴侣舞的沟通与自然语言进行类比，评估CoMPAS3D在两个合成人类的基准任务上，这些任务与语音语言和对话处理中的关键问题相对应：基于熟练程度的领舞或跟舞生成（即说话者或听者合成），以及双人舞（对话）生成。朝着与人类共舞的长期目标，我们发布了数据集、注释和代码，以及一个多任务SalsaAgent模型，该模型能够执行所有基准任务，并提供了额外的基线模型，以促进社交互动型具身AI和社会创意型人形动作生成的研究。

> Imagine a humanoid that can safely and creatively dance with a human, adapting to its partner's proficiency, using haptic signaling as a primary form of communication. While today's AI systems excel at text or voice-based interaction with large language models, human communication extends far beyond text-it includes embodied movement, timing, and physical coordination. Modeling coupled interaction between two agents poses a formidable challenge: it is continuous, bidirectionally reactive, and shaped by individual variation. We present CoMPAS3D, the largest and most diverse motion capture dataset of improvised salsa dancing, designed as a challenging testbed for interactive, expressive humanoid AI. The dataset includes 3 hours of leader-follower salsa dances performed by 18 dancers spanning beginner, intermediate, and professional skill levels. For the first time, we provide fine-grained salsa expert annotations, covering over 2,800 move segments, including move types, combinations, execution errors and stylistic elements. We draw analogies between partner dance communication and natural language, evaluating CoMPAS3D on two benchmark tasks for synthetic humans that parallel key problems in spoken language and dialogue processing: leader or follower generation with proficiency levels (speaker or listener synthesis), and duet (conversation) generation. Towards a long-term goal of partner dance with humans, we release the dataset, annotations, and code, along with a multitask SalsaAgent model capable of performing all benchmark tasks, alongside additional baselines to encourage research in socially interactive embodied AI and creative, expressive humanoid motion generation.

[Arxiv](https://arxiv.org/abs/2507.19684)