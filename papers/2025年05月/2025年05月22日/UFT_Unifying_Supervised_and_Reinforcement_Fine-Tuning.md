# UFT: 融合监督式与强化式微调

发布时间：2025年05月22日

`LLM理论` `人工智能`

> UFT: Unifying Supervised and Reinforcement Fine-Tuning

# 摘要

> 后训练在提升大型语言模型（LLMs）的推理能力方面发挥了关键作用。主要的后训练方法包括监督微调（SFT）和强化微调（RFT）。SFT虽然高效且适合小型模型，但可能引发过拟合并限制大型模型的推理能力。相比之下，RFT通常表现更佳，但其效果取决于基础模型的强弱。为克服SFT与RFT的局限性，我们提出了一种全新的后训练范式——统一微调（UFT），它将SFT与RFT整合为一个统一的过程。UFT不仅使模型能够有效探索解决方案，还通过融入监督信号，弥合了现有方法中记忆与思考之间的鸿沟。值得注意的是，无论模型规模如何，UFT普遍优于SFT与RFT。此外，我们从理论上证明，UFT突破了RFT的指数级样本复杂度瓶颈，首次证实统一训练可使长时推理任务的收敛速度呈指数级加速。

> Post-training has demonstrated its importance in enhancing the reasoning capabilities of large language models (LLMs). The primary post-training methods can be categorized into supervised fine-tuning (SFT) and reinforcement fine-tuning (RFT). SFT is efficient and well-suited for small language models, but it may lead to overfitting and limit the reasoning abilities of larger models. In contrast, RFT generally yields better generalization but depends heavily on the strength of the base model. To address the limitations of SFT and RFT, we propose Unified Fine-Tuning (UFT), a novel post-training paradigm that unifies SFT and RFT into a single, integrated process. UFT enables the model to effectively explore solutions while incorporating informative supervision signals, bridging the gap between memorizing and thinking underlying existing methods. Notably, UFT outperforms both SFT and RFT in general, regardless of model sizes. Furthermore, we theoretically prove that UFT breaks RFT's inherent exponential sample complexity bottleneck, showing for the first time that unified training can exponentially accelerate convergence on long-horizon reasoning tasks.

[Arxiv](https://arxiv.org/abs/2505.16984)