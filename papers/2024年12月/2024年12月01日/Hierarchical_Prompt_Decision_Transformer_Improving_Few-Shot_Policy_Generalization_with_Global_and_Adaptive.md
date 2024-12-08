# 分层提示决策转换器：借助全局和自适应手段提升少样本策略的泛化能力

发布时间：2024年12月01日

`Agent` `决策转换`

> Hierarchical Prompt Decision Transformer: Improving Few-Shot Policy Generalization with Global and Adaptive

# 摘要

> 决策转换器把强化学习重塑为有条件的序列生成问题，为传统的基于价值或策略的方法提供了简便且有效的替代选择。该领域近期的关键进展在于将提示融入决策转换器，以推动少样本策略的泛化。然而，当下的方法主要采用静态提示段来引导展开，这限制了其提供特定情境指导的能力。针对此，我们引入了一种借助检索增强实现的分层提示方法。我们的方法学习两层软标记作为引导提示：（1）包含轨迹任务级信息的全局标记；（2）提供聚焦的、特定时间步长指令的自适应标记。自适应标记从一组精心挑选的演示段中动态获取，确保了情境感知引导。在 MuJoCo 和 MetaWorld 环境中的七个基准任务实验表明，所提方法始终优于所有基线方法，这意味着决策转换器的分层提示是实现少样本策略泛化的有效策略。

> Decision transformers recast reinforcement learning as a conditional sequence generation problem, offering a simple but effective alternative to traditional value or policy-based methods. A recent key development in this area is the integration of prompting in decision transformers to facilitate few-shot policy generalization. However, current methods mainly use static prompt segments to guide rollouts, limiting their ability to provide context-specific guidance. Addressing this, we introduce a hierarchical prompting approach enabled by retrieval augmentation. Our method learns two layers of soft tokens as guiding prompts: (1) global tokens encapsulating task-level information about trajectories, and (2) adaptive tokens that deliver focused, timestep-specific instructions. The adaptive tokens are dynamically retrieved from a curated set of demonstration segments, ensuring context-aware guidance. Experiments across seven benchmark tasks in the MuJoCo and MetaWorld environments demonstrate the proposed approach consistently outperforms all baseline methods, suggesting that hierarchical prompting for decision transformers is an effective strategy to enable few-shot policy generalization.

[Arxiv](https://arxiv.org/abs/2412.00979)