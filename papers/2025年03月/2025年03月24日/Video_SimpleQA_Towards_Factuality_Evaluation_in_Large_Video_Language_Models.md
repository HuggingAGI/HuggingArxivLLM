# 视频问答：探索大型视频语言模型的事实性评估

发布时间：2025年03月24日

`LLM应用` `视频分析` `人工智能`

> Video SimpleQA: Towards Factuality Evaluation in Large Video Language Models

# 摘要

> # 摘要
近期大型视频语言模型（LVLMs）的突破性进展凸显了其在多模态理解方面的潜力。然而，在视频情境下评估其事实依据仍然是一个关键的未解难题。为了解决这一空白，我们提出了Video SimpleQA，这是首个专为评估LVLMs事实性而设计的综合性基准测试。

我们的工作通过以下关键特征与现有视频基准区分开来：
1. **知识需求**：要求整合超越视频显性叙述的外部知识；
2. **求实问题**：针对客观、无争议的事件或关系，避免主观解读；
3. **明确且简短的答案**：答案以简洁、无歧义且确定正确的方式构建，通过LLM作为评判框架进行自动化评估，确保评分差异最小；
4. **外部来源验证**：所有标注均经过严格的权威外部参考资料验证，以确保可靠性；
5. **时间推理需求**：标注的问题类型涵盖静态单帧理解和动态时间推理，明确评估LVLMs在长上下文依赖下的事实性。

我们对41个最先进 LVLMs进行了全面评估，并总结关键发现如下：
1. 当前 LVLMs 在事实遵循方面存在显著不足，尤其是开源模型。表现最佳的模型Gemini-1.5-Pro仅达到54.4%的F分数；
2. 测试时间计算范式未带来显著性能提升，揭示了通过后处理计算增强事实性的根本限制；
3. 检索增强生成在推理时间增加的代价下表现出一致的改进，呈现出效率与性能之间的关键权衡。


> Recent advancements in Large Video Language Models (LVLMs) have highlighted their potential for multi-modal understanding, yet evaluating their factual grounding in video contexts remains a critical unsolved challenge. To address this gap, we introduce Video SimpleQA, the first comprehensive benchmark tailored for factuality evaluation of LVLMs. Our work distinguishes from existing video benchmarks through the following key features: 1) Knowledge required: demanding integration of external knowledge beyond the explicit narrative; 2) Fact-seeking question: targeting objective, undisputed events or relationships, avoiding subjective interpretation; 3) Definitive & short-form answer: Answers are crafted as unambiguous and definitively correct in a short format, enabling automated evaluation through LLM-as-a-judge frameworks with minimal scoring variance; 4) External-source verified: All annotations undergo rigorous validation against authoritative external references to ensure the reliability; 5) Temporal reasoning required: The annotated question types encompass both static single-frame understanding and dynamic temporal reasoning, explicitly evaluating LVLMs factuality under the long-context dependencies. We extensively evaluate 41 state-of-the-art LVLMs and summarize key findings as follows: 1) Current LVLMs exhibit notable deficiencies in factual adherence, particularly for open-source models. The best-performing model Gemini-1.5-Pro achieves merely an F-score of 54.4%; 2) Test-time compute paradigms show insignificant performance gains, revealing fundamental constraints for enhancing factuality through post-hoc computation; 3) Retrieval-Augmented Generation demonstrates consistent improvements at the cost of additional inference time overhead, presenting a critical efficiency-performance trade-off.

[Arxiv](https://arxiv.org/abs/2503.18923)