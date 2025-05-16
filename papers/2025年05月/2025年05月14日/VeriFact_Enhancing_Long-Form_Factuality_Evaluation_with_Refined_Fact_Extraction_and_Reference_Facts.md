# VeriFact: 结合优化的事实提取与参考事实，增强长文本事实性评估

发布时间：2025年05月14日

`LLM应用` `事实验证`

> VeriFact: Enhancing Long-Form Factuality Evaluation with Refined Fact Extraction and Reference Facts

# 摘要

> 大型语言模型（LLMs）擅长生成长篇回应，但在评估其事实性时，依然面临挑战，原因在于生成事实中复杂的句间依赖关系。现有解决方案大多遵循分解-去上下文-验证的流水线，但常遗漏关键上下文和关系事实。本文介绍VeriFact，一个专注于提升事实提取能力的事实性评估框架，通过识别和解决不完整及缺失事实，支持更精准的验证结果。此外，我们还引入了事实基准测试（FactRBench），一个评估长篇回应模型准确率和召回率的基准，而以往工作主要侧重于准确率。FactRBench提供了来自先进LLMs和人工撰写答案的参考事实集，支持召回评估。实证评估表明，VeriFact显著提升了事实完整性，保留了包含关键关系信息的复杂事实，从而实现了更准确的事实性评估。在FactRBench上对各种开源及闭源LLMs进行基准测试发现，同一家族中的更大模型可提升准确率和召回率，但高准确率并不总是与高召回率相关，突显了全面事实性评估的重要性。

> Large language models (LLMs) excel at generating long-form responses, but evaluating their factuality remains challenging due to complex inter-sentence dependencies within the generated facts. Prior solutions predominantly follow a decompose-decontextualize-verify pipeline but often fail to capture essential context and miss key relational facts. In this paper, we introduce VeriFact, a factuality evaluation framework designed to enhance fact extraction by identifying and resolving incomplete and missing facts to support more accurate verification results. Moreover, we introduce FactRBench , a benchmark that evaluates both precision and recall in long-form model responses, whereas prior work primarily focuses on precision. FactRBench provides reference fact sets from advanced LLMs and human-written answers, enabling recall assessment. Empirical evaluations show that VeriFact significantly enhances fact completeness and preserves complex facts with critical relational information, resulting in more accurate factuality evaluation. Benchmarking various open- and close-weight LLMs on FactRBench indicate that larger models within same model family improve precision and recall, but high precision does not always correlate with high recall, underscoring the importance of comprehensive factuality assessment.

[Arxiv](https://arxiv.org/abs/2505.09701)