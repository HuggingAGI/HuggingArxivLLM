# SMooGPT：利用大型语言模型生成风格化运动

发布时间：2025年09月04日

`LLM应用` `媒体与娱乐`

> SMooGPT: Stylized Motion Generation using Large Language Models

# 摘要

> 风格化运动生成是计算机图形学领域的研究热点，尤其得益于扩散模型的飞速发展。其目标是生成兼具运动内容与期望风格的全新运动，例如“像猴子一样循环行走”。现有研究多通过运动风格迁移或条件运动生成来应对这一挑战，通常将运动风格嵌入潜在空间并在其中进行隐式引导。尽管已取得进展，这些方法仍存在可解释性与控制能力不足、对新风格泛化受限等问题，且受公共风格化数据集中强烈偏见的影响，难以生成“行走”之外的运动。本文基于三项关键观察，提出从“推理-组合-生成”的全新视角解决风格化运动生成问题：i) 人类运动可通过以身体部位为中心的自然语言得到有效描述；ii) 大型语言模型（LLMs）具备强大的人类运动理解与推理能力；iii) 人类运动具有内在组合性，通过有效重组即可生成新的运动内容或风格。为此，我们提出将身体部位文本空间作为中间表示，并构建 SMooGPT——一个微调的大型语言模型（LLM），在生成目标风格化运动时同时扮演推理器、组合器与生成器的角色。该方法在身体部位文本空间中运行，可解释性显著提升，不仅支持细粒度运动控制、有效化解运动内容与风格间的潜在冲突，还借助 LLM 的开放词汇能力，对新风格展现出优异的泛化性能。大量实验、评估及用户感知研究均验证了该方法的有效性，尤其在纯文本驱动的风格化运动生成任务中表现突出。

> Stylized motion generation is actively studied in computer graphics, especially benefiting from the rapid advances in diffusion models. The goal of this task is to produce a novel motion respecting both the motion content and the desired motion style, e.g., ``walking in a loop like a Monkey''. Existing research attempts to address this problem via motion style transfer or conditional motion generation. They typically embed the motion style into a latent space and guide the motion implicitly in a latent space as well. Despite the progress, their methods suffer from low interpretability and control, limited generalization to new styles, and fail to produce motions other than ``walking'' due to the strong bias in the public stylization dataset. In this paper, we propose to solve the stylized motion generation problem from a new perspective of reasoning-composition-generation, based on our observations: i) human motion can often be effectively described using natural language in a body-part centric manner, ii) LLMs exhibit a strong ability to understand and reason about human motion, and iii) human motion has an inherently compositional nature, facilitating the new motion content or style generation via effective recomposing. We thus propose utilizing body-part text space as an intermediate representation, and present SMooGPT, a fine-tuned LLM, acting as a reasoner, composer, and generator when generating the desired stylized motion. Our method executes in the body-part text space with much higher interpretability, enabling fine-grained motion control, effectively resolving potential conflicts between motion content and style, and generalizes well to new styles thanks to the open-vocabulary ability of LLMs. Comprehensive experiments and evaluations, and a user perceptual study, demonstrate the effectiveness of our approach, especially under the pure text-driven stylized motion generation.

[Arxiv](https://arxiv.org/abs/2509.04058)