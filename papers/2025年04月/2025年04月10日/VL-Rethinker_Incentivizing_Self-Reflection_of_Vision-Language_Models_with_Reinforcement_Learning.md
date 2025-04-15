# VL-Rethinker：以强化学习推动视觉语言模型的自我反思能力

发布时间：2025年04月10日

`LLM应用` `跨学科`

> VL-Rethinker: Incentivizing Self-Reflection of Vision-Language Models with Reinforcement Learning

# 摘要

> 近期，GPT-o1和DeepSeek-R1等慢思维系统在解决复杂问题方面展现出巨大潜力，尤其在数学和科学领域大幅超越了GPT-4o等快思维模型。然而，它们的多模态推理能力仍与快思维模型持平，例如GPT-o1在MathVista、MathVerse和MathVision等基准测试中的表现与快思维模型相当。本文提出了一种基于强化学习的方法（不依赖蒸馏技术），旨在提升视觉语言模型的慢思维能力。我们首先对GRPO算法进行了改进，引入了选择性样本重放（SSR）技术来解决优势递减问题。虽然这一方法表现优异，但强化学习训练出的模型仍缺乏自我反思能力。为了解决这一问题，我们在强化学习训练中引入了强制重新思考机制，通过在初始 rollout 的末尾附加文本重新思考触发器，显式强制执行自我反思推理步骤。通过结合这两种技术，我们的模型VL-Rethinker在MathVista、MathVerse和MathVision上的最新技术水平分别提升至80.3%、61.8%和43.9%。此外，VL-Rethinker还在MMMU-Pro、EMMA和MEGA-Bench等跨学科基准测试中达到了开源领域的最新技术水平，缩小了与GPT-o1的差距。

> Recently, slow-thinking systems like GPT-o1 and DeepSeek-R1 have demonstrated great potential in solving challenging problems through explicit reflection. They significantly outperform the best fast-thinking models, such as GPT-4o, on various math and science benchmarks. However, their multimodal reasoning capabilities remain on par with fast-thinking models. For instance, GPT-o1's performance on benchmarks like MathVista, MathVerse, and MathVision is similar to fast-thinking models. In this paper, we aim to enhance the slow-thinking capabilities of vision-language models using reinforcement learning (without relying on distillation) to advance the state of the art. First, we adapt the GRPO algorithm with a novel technique called Selective Sample Replay (SSR) to address the vanishing advantages problem. While this approach yields strong performance, the resulting RL-trained models exhibit limited self-reflection or self-verification. To further encourage slow-thinking, we introduce Forced Rethinking, which appends a textual rethinking trigger to the end of initial rollouts in RL training, explicitly enforcing a self-reflection reasoning step. By combining these two techniques, our model, VL-Rethinker, advances state-of-the-art scores on MathVista, MathVerse, and MathVision to achieve 80.3%, 61.8%, and 43.9% respectively. VL-Rethinker also achieves open-source SoTA on multi-disciplinary benchmarks such as MMMU-Pro, EMMA, and MEGA-Bench, narrowing the gap with GPT-o1.

[Arxiv](https://arxiv.org/abs/2504.08837)