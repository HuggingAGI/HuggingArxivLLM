# AI驱动工具在现代软件质量保证中的探析：优势、挑战与未来方向分析

发布时间：2025年06月19日

`LLM应用

理由：这篇论文主要探讨了将AI工具，特别是基于大型语言模型（LLMs）的技术，整合到软件质量保证（QA）流程中的应用和影响。研究分析了AI在测试生成、优化和执行等方面的优势和挑战，强调了其在实际QA中的潜力和限制。因此，它属于LLM应用类别。` `软件工程` `质量保证`

> AI-Driven Tools in Modern Software Quality Assurance: An Assessment of Benefits, Challenges, and Future Directions

# 摘要

> 传统质量保证（QA）方法在应对现代软件系统的复杂性、规模及快速迭代周期方面面临严峻挑战，同时受限于资源匮乏，导致质量问题产生的高昂成本。本研究聚焦于现代分布式软件应用的质量保证流程，旨在评估将AI工具整合到QA流程中的优势、挑战及前景。我们全面分析了AI工具对验证与确认过程的影响，涵盖探索性测试分析、等价类划分与边界分析、变形测试、发现验收标准（AC）中的不一致、静态分析、测试用例生成、单元测试生成、测试套件优化与评估、端到端场景执行。通过利用AI代理对生成的测试场景进行端到端回归，我们展示了本研究的实际应用价值。结果显示，仅8.3%的生成测试用例执行结果不稳定，表明所提出的方案具有显著潜力。然而，研究也识别出在实际应用中面临的重大挑战，包括生成语义相同覆盖范围的困难、基于先进大型语言模型（LLMs）的“黑箱”特性及其缺乏可解释性、修正变异测试用例以匹配预期结果的倾向，凸显了对生成 artifacts 和测试执行结果进行全面验证的必要性。研究展示了AI在质量保证领域的变革潜力，但强调了在考虑已识别限制及开发适当验证方法论的前提下，采取战略性方法实施这些技术的重要性。

> Traditional quality assurance (QA) methods face significant challenges in addressing the complexity, scale, and rapid iteration cycles of modern software systems and are strained by limited resources available, leading to substantial costs associated with poor quality. The object of this research is the Quality Assurance processes for modern distributed software applications. The subject of the research is the assessment of the benefits, challenges, and prospects of integrating modern AI-oriented tools into quality assurance processes. We performed comprehensive analysis of implications on both verification and validation processes covering exploratory test analyses, equivalence partitioning and boundary analyses, metamorphic testing, finding inconsistencies in acceptance criteria (AC), static analyses, test case generation, unit test generation, test suit optimization and assessment, end to end scenario execution. End to end regression of sample enterprise application utilizing AI-agents over generated test scenarios was implemented as a proof of concept highlighting practical use of the study. The results, with only 8.3% flaky executions of generated test cases, indicate significant potential for the proposed approaches. However, the study also identified substantial challenges for practical adoption concerning generation of semantically identical coverage, "black box" nature and lack of explainability from state-of-the-art Large Language Models (LLMs), the tendency to correct mutated test cases to match expected results, underscoring the necessity for thorough verification of both generated artifacts and test execution results. The research demonstrates AI's transformative potential for QA but highlights the importance of a strategic approach to implementing these technologies, considering the identified limitations and the need for developing appropriate verification methodologies.

[Arxiv](https://arxiv.org/abs/2506.16586)