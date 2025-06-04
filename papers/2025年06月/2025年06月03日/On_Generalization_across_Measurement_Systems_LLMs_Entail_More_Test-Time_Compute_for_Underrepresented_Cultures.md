# # 跨测量系统泛化：大语言模型对少数文化群体的测试计算需求更高

发布时间：2025年06月03日

`LLM应用` `跨文化交流` `人工智能`

> On Generalization across Measurement Systems: LLMs Entail More Test-Time Compute for Underrepresented Cultures

# 摘要

> 测量系统（如货币）在不同文化中各不相同，但它们之间的转换规则明确，使得人们可以自由选择测量系统来表达事实。大型语言模型（LLMs）服务于来自多元文化背景的用户，理应能准确传达信息，无论当前使用的测量系统为何。我们通过新编的数据集，测试了七种开源LLMs是否符合这一预期，并围绕三个关键问题展开研究：（RQ1）LLMs在各类测量任务中默认采用何种系统？（RQ2）不同测量系统下，LLMs的回答及其准确性是否存在差异？（RQ3）LLMs能否通过推理缓解代表性不足测量系统带来的挑战？研究发现，LLMs默认采用数据集中主要使用的测量系统。此外，我们观察到在不同测量系统下，LLMs的表现存在显著波动和差异。虽然链式思维（CoT）等推理方法可在一定程度上缓解这种波动，但这会导致更长的响应时间，从而大幅增加测试时的计算需求（及推理成本），使得来自使用代表性不足测量系统文化背景的用户被边缘化。

> Measurement systems (e.g., currencies) differ across cultures, but the conversions between them are well defined so that humans can state facts using any measurement system of their choice. Being available to users from diverse cultural backgrounds, large language models (LLMs) should also be able to provide accurate information irrespective of the measurement system at hand. Using newly compiled datasets we test if this is the case for seven open-source LLMs, addressing three key research questions: (RQ1) What is the default system used by LLMs for each type of measurement? (RQ2) Do LLMs' answers and their accuracy vary across different measurement systems? (RQ3) Can LLMs mitigate potential challenges w.r.t. underrepresented systems via reasoning? Our findings show that LLMs default to the measurement system predominantly used in the data. Additionally, we observe considerable instability and variance in performance across different measurement systems. While this instability can in part be mitigated by employing reasoning methods such as chain-of-thought (CoT), this implies longer responses and thereby significantly increases test-time compute (and inference costs), marginalizing users from cultural backgrounds that use underrepresented measurement systems.

[Arxiv](https://arxiv.org/abs/2506.02591)