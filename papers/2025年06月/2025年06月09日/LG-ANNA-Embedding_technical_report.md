# LG-ANNA-Embedding技术报告

发布时间：2025年06月09日

`LLM应用` `信息检索`

> LG-ANNA-Embedding technical report

# 摘要

> 本报告提出了一种统一的指令驱动框架，用于学习同时优化信息检索（IR）和非IR任务的泛化文本嵌入。我们的方法基于解码器型大型语言模型（Mistral-7B），整合了上下文学习、软监督和自适应难例挖掘，无需特定任务的微调即可生成上下文感知的嵌入。通过结构化指令和少量示例，模型能够跨多种任务进行引导，实现在分类、语义相似度、聚类和重排序基准上的强劲表现。为了提升语义区分度，我们采用了一种软标签框架，其中从高性能密集检索器和重排序器中蒸馏出的连续相关性分数作为精细的监督信号。此外，我们引入了基于自适应边界的难例挖掘，通过过滤与正例语义模糊的负例，增强了训练稳定性和检索鲁棒性。我们的模型在新引入的MTEB（英语，v2）基准上进行了评估，涵盖七个类别的41项任务。结果显示，我们的方法实现了强大的泛化能力，并在Borda得分中跻身表现最佳的模型之列，超越了多个更大规模或完全微调的基线模型。这些发现凸显了将上下文提示、软监督和自适应采样相结合在生成可扩展高质量嵌入方面的有效性。


> This report presents a unified instruction-based framework for learning generalized text embeddings optimized for both information retrieval (IR) and non-IR tasks. Built upon a decoder-only large language model (Mistral-7B), our approach combines in-context learning, soft supervision, and adaptive hard-negative mining to generate context-aware embeddings without task-specific fine-tuning. Structured instructions and few-shot examples are used to guide the model across diverse tasks, enabling strong performance on classification, semantic similarity, clustering, and reranking benchmarks. To improve semantic discrimination, we employ a soft labeling framework where continuous relevance scores, distilled from a high-performance dense retriever and reranker, serve as fine-grained supervision signals. In addition, we introduce adaptive margin-based hard-negative mining, which filters out semantically ambiguous negatives based on their similarity to positive examples, thereby enhancing training stability and retrieval robustness. Our model is evaluated on the newly introduced MTEB (English, v2) benchmark, covering 41 tasks across seven categories. Results show that our method achieves strong generalization and ranks among the top-performing models by Borda score, outperforming several larger or fully fine-tuned baselines. These findings highlight the effectiveness of combining in-context prompting, soft supervision, and adaptive sampling for scalable, high-quality embedding generation.

[Arxiv](https://arxiv.org/abs/2506.07438)