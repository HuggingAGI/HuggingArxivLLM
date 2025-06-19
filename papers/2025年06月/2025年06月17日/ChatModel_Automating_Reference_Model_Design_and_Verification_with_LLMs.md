# # ChatModel  
ChatModel：基于 LLM 实现参考模型设计与验证的自动化

发布时间：2025年06月17日

`LLM应用` `集成电路` `功能验证`

> ChatModel: Automating Reference Model Design and Verification with LLMs

# 摘要

> 集成电路设计复杂性日益增加，使得功能验证面临更大挑战。参考模型对于加速验证至关重要，但其开发难度和耗时也在不断增加。尽管大型语言模型（LLMs）在代码编程领域展现出巨大潜力，但生成复杂参考模型仍是难题。为此，我们推出ChatModel——首个基于LLM的敏捷参考模型生成与验证平台。通过整合设计标准化和分层敏捷建模，ChatModel简化了从设计规范到完整功能参考模型的转换过程。采用积木式生成策略，它不仅提升了LLMs在参考模型设计方面的能力，还显著提高了验证效率。我们在300个不同复杂度的设计上对ChatModel进行了评估，结果表明其在参考模型生成效率和质量方面均有显著提升。与传统方法相比，ChatModel的峰值性能提升了55.02%，生成稳定性也得到了显著增强，其生成参考模型设计的能力提升了9.18倍。此外，与传统方法相比，它还加速了参考模型设计和验证的迭代过程，平均加速倍数为5.90倍。这些结果凸显了ChatModel在推动参考模型生成与验证自动化方面的巨大潜力。

> As the complexity of integrated circuit designs continues to escalate, the functional verification becomes increasingly challenging. Reference models, critical for accelerating the verification process, are themselves becoming more intricate and time-consuming to develop. Despite the promise shown by large language models (LLMs) in code programming, effectively generating complex reference models remains a significant hurdle. To address these challenges, we introduce ChatModel, the first LLM-aided agile reference model generation and verification platform. ChatModel streamlines the transition from design specifications to fully functional reference models by integrating design standardization and hierarchical agile modeling. Employing a building-block generation strategy, it not only enhances the design capabilities of LLMs for reference models but also significantly boosts verification efficiency. We evaluated ChatModel on 300 designs of varying complexity, demonstrating substantial improvements in both efficiency and quality of reference model generation. ChatModel achieved a peak performance improvement of 55.02% compared to alternative methods, with notable enhancements in generation stability, and delivered a 9.18x increase in its capacity to produce reference model designs. Furthermore, it accelerated the iterative process of reference model design and validation by an average of 5.90x compared to traditional approaches. These results highlight the potential of ChatModel to significantly advance the automation of reference model generation and validation.

[Arxiv](https://arxiv.org/abs/2506.15066)