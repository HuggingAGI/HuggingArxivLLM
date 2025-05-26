# 数据注入是 doping 还是真实智能？评估注入知识在 LLM 中的迁移能力。

发布时间：2025年05月22日

`LLM理论` `人工智能`

> Data Doping or True Intelligence? Evaluating the Transferability of Injected Knowledge in LLMs

# 摘要

> 大型语言模型 (LLMs) 的知识会随着时间推移而过时，因此高效更新模型的需求日益增长，尤其是在注入专有信息时。研究发现，以理解为核心的微调任务（如问答和填空）在知识保留率（48%）上显著优于以映射为导向的任务（如翻译 17% 或文本到 JSON 转换 20%），尽管它们接触到相同的内容。这一模式在不同模型架构中持续存在，并遵循扩展定律，更大的模型在所有任务类型中都表现出更好的知识保留能力。然而，所有模型在更广泛的上下文中应用注入的知识时都表现出显著的性能下降，这表明语义整合能力有限。这些发现凸显了任务选择在更新 LLM 知识中的重要性，表明有效的知识注入不仅依赖于数据暴露，还取决于微调过程中认知参与的深度。

> As the knowledge of large language models (LLMs) becomes outdated over time, there is a growing need for efficient methods to update them, especially when injecting proprietary information. Our study reveals that comprehension-intensive fine-tuning tasks (e.g., question answering and blanks) achieve substantially higher knowledge retention rates (48%) compared to mapping-oriented tasks like translation (17%) or text-to-JSON conversion (20%), despite exposure to identical factual content. We demonstrate that this pattern persists across model architectures and follows scaling laws, with larger models showing improved retention across all task types. However, all models exhibit significant performance drops when applying injected knowledge in broader contexts, suggesting limited semantic integration. These findings show the importance of task selection in updating LLM knowledge, showing that effective knowledge injection relies not just on data exposure but on the depth of cognitive engagement during fine-tuning.

[Arxiv](https://arxiv.org/abs/2505.17140)