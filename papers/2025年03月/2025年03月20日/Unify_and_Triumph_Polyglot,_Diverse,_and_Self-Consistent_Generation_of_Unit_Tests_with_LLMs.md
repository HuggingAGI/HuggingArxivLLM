# # 聚力致胜：LLMs驱动的多语言、多样化且自我一致的单元测试生成

发布时间：2025年03月20日

`LLM应用` `软件工程` `测试生成`

> Unify and Triumph: Polyglot, Diverse, and Self-Consistent Generation of Unit Tests with LLMs

# 摘要

> 基于大型语言模型（LLM）的测试生成在软件工程领域备受关注。然而，现有研究多局限于评估LLM在单次尝试中为特定语言生成单元测试的能力，忽视了LLM多样性在提升测试稳健性方面的潜力。本文提出了一种名为PolyTest的创新方法，通过多语言支持和温度控制的多样化策略，显著提升了测试生成的效果。PolyTest从两个互补维度系统性地利用这些特性：（1）跨语言测试生成，即在零温度下生成多语言测试并统一整合；（2）多样化测试采样，即在同一种语言下以较高温度生成多个测试集后统一整合。研究发现，LLM能够生成多样且相互矛盾的测试——相同输入，不同预期输出——这些测试跨越不同语言和生成轮次。PolyTest通过统一整合测试集，促进自我一致性，从而显著提升整体测试质量。与传统单语言或单次尝试的方法不同，PolyTest无需实时执行即可增强测试能力，这对表现较弱的语言尤其有益。我们在Llama3-70B、GPT-4o和GPT-3.5上使用EvalPlus对PolyTest进行了全面评估，生成了五种语言（Java、C、Python、JavaScript和基于CSV的格式）的测试，温度设为0，并在温度设为1时采样多个测试集。实验结果表明，LLM在不同设置下常生成相互矛盾的测试，而PolyTest在所有关键指标（包括测试数量、通过率、语句/分支覆盖率（最高提升9.01%）和变异分数（最高提升11.23%））上显著优于传统方法。最终，PolyTest在测试生成、通过率和变异分数方面全面超越Pynguin，展现出显著的优越性。

> Large language model (LLM)-based test generation has gained attention in software engineering, yet most studies evaluate LLMs' ability to generate unit tests in a single attempt for a given language, missing the opportunity to leverage LLM diversity for more robust testing. This paper introduces PolyTest, a novel approach that enhances test generation by exploiting polyglot and temperature-controlled diversity. PolyTest systematically leverages these properties in two complementary ways: (1) Cross-lingual test generation, where tests are generated in multiple languages at zero temperature and then unified; (2) Diverse test sampling, where multiple test sets are generated within the same language at a higher temperature before unification. A key insight is that LLMs can generate diverse yet contradicting tests -- same input, different expected outputs -- across languages and generations. PolyTest mitigates inconsistencies by unifying test sets, fostering self-consistency and improving overall test quality. Unlike single-language or single-attempt approaches, PolyTest enhances testing without requiring on-the-fly execution, making it particularly beneficial for weaker-performing languages. We evaluate PolyTest on Llama3-70B, GPT-4o, and GPT-3.5 using EvalPlus, generating tests in five languages (Java, C, Python, JavaScript, and a CSV-based format) at temperature 0 and sampling multiple sets at temperature 1. We observe that LLMs frequently generate contradicting tests across settings, and that PolyTest significantly improves test quality across all considered metrics -- number of tests, passing rate, statement/branch coverage (up to +9.01%), and mutation score (up to +11.23%). Finally, PolyTest outperforms Pynguin in test generation, passing rate, and mutation score.

[Arxiv](https://arxiv.org/abs/2503.16144)