# 针对RESTful API测试，结合静态与动态方法挖掘与测试约束

发布时间：2025年04月24日

`LLM应用

摘要中提到，论文结合静态分析和动态分析，利用大型语言模型（LLMs）来理解API规范、提取约束并生成测试用例。这表明研究的重点是将LLMs应用于API测试，属于LLM的实际应用。因此，分类为LLM应用。` `软件工程` `软件测试`

> Combining Static and Dynamic Approaches for Mining and Testing Constraints for RESTful API Testing

# 摘要

> 在API测试中，生成覆盖RESTful API各个方面的测试用例，离不开从API响应体中提取逻辑约束。然而，现有方法仅限于动态分析，通过API执行提取约束，但输入多样性不足，难以揭示实际约束。本文提出结合静态分析（从API规范中提取约束）与动态分析（依赖API执行数据）。我们利用大型语言模型（LLMs）理解API规范、提取约束并生成测试用例。为减少LLMs的幻觉，我们采用观察-确认（OC）方案，通过初始提示上下文化约束，使后续提示更准确确认其存在。实验结果显示，采用OC提示的LLMs在约束提取方面平均精度达91.2%。结合静态与动态分析，我们的工具RBCTest实现78.5%的精度，检测到动态方法遗漏的107个约束及46个更精确约束。我们还利用RBCTest生成的测试用例，发现8个真实API中API规范与实际响应数据的21个不匹配，其中4个已获开发者论坛报告。

> In API testing, deriving logical constraints on API response bodies is crucial in generating the test cases to cover various aspects of RESTful APIs. However, existing approaches are limited to dynamic analysis in which constraints are extracted from the execution of APIs as part of the system under test. The key limitation of such a dynamic approach is its under-estimation in which inputs in API executions are not sufficiently diverse to uncover actual constraints on API response bodies. In this paper, we propose to combine a novel static analysis approach (in which the constraints for API response bodies are mined from API specifications), with the dynamic approach (which relies on API execution data). We leverage large language models (LLMs) to comprehend the API specifications, mine constraints for response bodies, and generate test cases. To reduce LLMs' hallucination, we apply an Observation-Confirmation (OC) scheme which uses initial prompts to contextualize constraints. %, allowing subsequent prompts to more accurately confirm their presence. Our empirical results show that~LLMs with OC prompting achieve high precision in constraint mining with the average of 91.2%. When combining static and dynamic analysis, our tool, RBCTest , achieves a precision of 78.5%. RBCTest detects 107 constraints that the dynamic approach misses and 46 more precise constraints. We also use its generated test cases to detect 21 mismatches between the API specification and actual response data for 8 real-world APIs. Four of the mismatches were, in fact, reported in developers' forums.

[Arxiv](https://arxiv.org/abs/2504.17287)