# 自我奖励与自我改进

发布时间：2025年05月12日

`LLM理论` `教育技术`

> Self Rewarding Self Improving

# 摘要

> 我们发现，大型语言模型无需参考答案，仅凭生成与验证的不对称性，就能通过自我评估实现自我提升。实验结果显示，模型在倒计时谜题和麻省理工积分竞赛中无需真实答案即可提供可靠奖励信号，使强化学习在以前无法实现的领域成为可能。通过自我评估机制，我们不仅实现了性能的显著提升，还保持了与正式验证的一致性。结合合成问题生成技术，我们构建了一个完整的自我改进循环：模型自动生成练习题、解答问题并自我评估——与基线相比，Qwen 2.5 7B实现了8%的性能提升，甚至在积分任务上超越了GPT-4o的表现。这一发现表明，LLM评估器可以为模型训练提供有效的奖励信号，从而突破了创建程序化奖励的限制，解锁更多强化学习环境。这可能标志着AI系统从依赖人类引导训练转向通过自我导向学习持续改进的范式转变，尤其在训练数据稀缺或评估要求复杂的领域，有望加速技术进步。

> We demonstrate that large language models can effectively self-improve through self-judging without requiring reference solutions, leveraging the inherent asymmetry between generating and verifying solutions. Our experiments on Countdown puzzles and MIT Integration Bee problems show that models can provide reliable reward signals without ground truth answers, enabling reinforcement learning in domains previously not possible. By implementing self-judging, we achieve significant performance gains maintaining alignment with formal verification. When combined with synthetic question generation, we establish a complete self-improvement loop where models generate practice problems, solve them, and evaluate their own performance-achieving an 8% improvement with Qwen 2.5 7B over baseline and surpassing GPT-4o performance on integration tasks. Our findings demonstrate that LLM judges can provide effective reward signals for training models, unlocking many reinforcement learning environments previously limited by the difficulty of creating programmatic rewards. This suggests a potential paradigm shift toward AI systems that continuously improve through self-directed learning rather than human-guided training, potentially accelerating progress in domains with scarce training data or complex evaluation requirements.

[Arxiv](https://arxiv.org/abs/2505.08827)