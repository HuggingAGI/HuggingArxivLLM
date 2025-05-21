# DecIF：利用元分解优化指令遵循效果

发布时间：2025年05月20日

`LLM应用` `人工智能`

> DecIF: Improving Instruction-Following through Meta-Decomposition

# 摘要

> 遵循指令已成为大型语言模型 (LLMs) 的关键能力。然而，现有方法通常依赖于预先存在的文档或外部资源来合成遵循指令的数据，这大大限制了其灵活性和泛化能力。本文介绍 DecIF，一种完全自主的、基于元分解引导的框架，仅利用 LLMs 生成多样且高质量的遵循指令数据。DecIF 基于分解原则。在指令生成方面，我们引导 LLMs 迭代生成多种类型的元信息，然后将其与响应约束相结合，形成结构良好且语义丰富的指令。我们进一步利用 LLMs 检测并解决生成指令中的潜在不一致。关于响应生成，我们将每个指令分解为原子级的评估标准，从而实现严格的验证并消除不准确的指令-响应对。在广泛的不同场景和设置下的大量实验表明，DecIF 在遵循指令任务中表现出色。进一步分析强调了其在自动合成高质量指令数据方面的强大灵活性、可扩展性和泛化能力。

> Instruction-following has emerged as a crucial capability for large language models (LLMs). However, existing approaches often rely on pre-existing documents or external resources to synthesize instruction-following data, which limits their flexibility and generalizability. In this paper, we introduce DecIF, a fully autonomous, meta-decomposition guided framework that generates diverse and high-quality instruction-following data using only LLMs. DecIF is grounded in the principle of decomposition. For instruction generation, we guide LLMs to iteratively produce various types of meta-information, which are then combined with response constraints to form well-structured and semantically rich instructions. We further utilize LLMs to detect and resolve potential inconsistencies within the generated instructions. Regarding response generation, we decompose each instruction into atomic-level evaluation criteria, enabling rigorous validation and the elimination of inaccurate instruction-response pairs. Extensive experiments across a wide range of scenarios and settings demonstrate DecIF's superior performance on instruction-following tasks. Further analysis highlights its strong flexibility, scalability, and generalizability in automatically synthesizing high-quality instruction data.

[Arxiv](https://arxiv.org/abs/2505.13990)