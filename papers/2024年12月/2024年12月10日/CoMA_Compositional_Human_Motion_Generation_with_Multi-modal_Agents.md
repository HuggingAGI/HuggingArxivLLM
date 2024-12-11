# CoMA：利用多模态代理实现组合式人体运动生成

发布时间：2024年12月10日

`Agent` `人体运动` `计算机视觉`

> CoMA: Compositional Human Motion Generation with Multi-modal Agents

# 摘要

> 近年来，3D 人体运动生成取得了重大进展。尽管前沿方法显著提升了性能，但在应对训练数据中未曾出现的复杂且细致的运动时，仍面临困境，这主要归因于运动数据集的稀缺以及生成新训练样本的高昂成本。为应对这些挑战，我们推出了 CoMA，这是一种针对复杂人体运动生成、编辑与理解的基于代理的解决方案。CoMA 借助由大型语言和视觉模型驱动的多个协作代理，以及一个基于掩码变压器、具备身体部位特定编码器和码本的运动生成器，实现精细控制。我们的框架能够生成包含详细指令的长短运动序列、进行文本引导的运动编辑，并通过自我校正提升质量。在 HumanML3D 数据集上的评估显示，其性能可与前沿方法媲美。此外，我们创建了一组内容丰富、具有组合性的长文本提示，用户研究表明我们的方法显著优于现有方法。

> 3D human motion generation has seen substantial advancement in recent years. While state-of-the-art approaches have improved performance significantly, they still struggle with complex and detailed motions unseen in training data, largely due to the scarcity of motion datasets and the prohibitive cost of generating new training examples. To address these challenges, we introduce CoMA, an agent-based solution for complex human motion generation, editing, and comprehension. CoMA leverages multiple collaborative agents powered by large language and vision models, alongside a mask transformer-based motion generator featuring body part-specific encoders and codebooks for fine-grained control. Our framework enables generation of both short and long motion sequences with detailed instructions, text-guided motion editing, and self-correction for improved quality. Evaluations on the HumanML3D dataset demonstrate competitive performance against state-of-the-art methods. Additionally, we create a set of context-rich, compositional, and long text prompts, where user studies show our method significantly outperforms existing approaches.

[Arxiv](https://arxiv.org/abs/2412.07320)