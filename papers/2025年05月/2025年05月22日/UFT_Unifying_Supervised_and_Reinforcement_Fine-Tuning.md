# UFT: 统一监督式与强化微调方法

发布时间：2025年05月22日

`LLM理论` `人工智能`

> UFT: Unifying Supervised and Reinforcement Fine-Tuning

# 摘要

> 后训练对提升大型语言模型的推理能力至关重要。主要的后训练方法可分为监督微调（SFT）和强化微调（RFT）。SFT高效且适合小型模型，但可能引发过拟合，限制大型模型的推理能力。相比之下，RFT的泛化效果更佳，但其表现高度依赖于基础模型的强弱。为克服SFT和RFT的局限性，我们提出了统一微调（UFT），这是一种将SFT和RFT整合为一个统一过程的新型后训练范式。UFT使模型能够有效探索解决方案，同时整合有益的监督信号，弥合现有方法中记忆与思考之间的鸿沟。值得注意的是，无论模型规模如何，UFT在总体上均优于SFT和RFT。此外，我们从理论上证明，UFT突破了RFT内在的指数级样本复杂度瓶颈，首次证明统一训练能够在长时推理任务上实现指数级加速收敛。

> Post-training has demonstrated its importance in enhancing the reasoning capabilities of large language models (LLMs). The primary post-training methods can be categorized into supervised fine-tuning (SFT) and reinforcement fine-tuning (RFT). SFT is efficient and well-suited for small language models, but it may lead to overfitting and limit the reasoning abilities of larger models. In contrast, RFT generally yields better generalization but depends heavily on the strength of the base model. To address the limitations of SFT and RFT, we propose Unified Fine-Tuning (UFT), a novel post-training paradigm that unifies SFT and RFT into a single, integrated process. UFT enables the model to effectively explore solutions while incorporating informative supervision signals, bridging the gap between memorizing and thinking underlying existing methods. Notably, UFT outperforms both SFT and RFT in general, regardless of model sizes. Furthermore, we theoretically prove that UFT breaks RFT's inherent exponential sample complexity bottleneck, showing for the first time that unified training can exponentially accelerate convergence on long-horizon reasoning tasks.

[Arxiv](https://arxiv.org/abs/2505.16984)