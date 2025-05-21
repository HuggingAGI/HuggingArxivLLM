# 大型语言模型的安全查询路由设计

发布时间：2025年05月20日

`LLM应用`

> Guarded Query Routing for Large Language Models

# 摘要

> 将用户查询分配到不同大型语言模型（LLM）端点的查询路由任务，本质上是一个文本分类问题。然而，必须妥善处理分布外查询，因为这些查询可能涉及无关领域、使用其他语言，甚至包含不安全内容。为此，我们研究了一个有保护机制的查询路由问题，并引入了有保护机制的查询路由基准测试（GQR-Bench），该基准涵盖了法律、金融和医疗三个典型领域，以及七个数据集用于测试对抗分布外查询的鲁棒性。我们利用GQR-Bench对比了基于LLM的路由机制（GPT-4o-mini、Llama-3.2-3B和Llama-3.1-8B）、标准的LLM保护措施（LlamaGuard和NVIDIA NeMo Guardrails）、连续词袋分类器（WideMLP和fastText）以及传统机器学习模型（SVM和XGBoost）的有效性和效率。结果显示，增强分布外检测能力的WideMLP在准确率（88%）和速度（<4ms）之间取得了最佳平衡。基于嵌入的fastText在速度（<1ms）上表现出色，同时具有可接受的准确率（80%），而LLMs提供了最高的准确率（91%），但速度相对较慢（本地Llama-3.1:8B为62ms，远程GPT-4o-mini调用为669ms）。我们的研究结果挑战了对LLMs在（有保护机制的）查询路由中的自动依赖，并为实际应用提供了具体建议。GQR-Bench将作为Python包发布——	exttt{gqr}。

> Query routing, the task to route user queries to different large language model (LLM) endpoints, can be considered as a text classification problem. However, out-of-distribution queries must be handled properly, as those could be questions about unrelated domains, queries in other languages, or even contain unsafe text. Here, we thus study a \emph{guarded} query routing problem, for which we first introduce the Guarded Query Routing Benchmark (GQR-Bench), which covers three exemplary target domains (law, finance, and healthcare), and seven datasets to test robustness against out-of-distribution queries. We then use GQR-Bench to contrast the effectiveness and efficiency of LLM-based routing mechanisms (GPT-4o-mini, Llama-3.2-3B, and Llama-3.1-8B), standard LLM-based guardrail approaches (LlamaGuard and NVIDIA NeMo Guardrails), continuous bag-of-words classifiers (WideMLP, fastText), and traditional machine learning models (SVM, XGBoost). Our results show that WideMLP, enhanced with out-of-domain detection capabilities, yields the best trade-off between accuracy (88\%) and speed (<4ms). The embedding-based fastText excels at speed (<1ms) with acceptable accuracy (80\%), whereas LLMs yield the highest accuracy (91\%) but are comparatively slow (62ms for local Llama-3.1:8B and 669ms for remote GPT-4o-mini calls). Our findings challenge the automatic reliance on LLMs for (guarded) query routing and provide concrete recommendations for practical applications. GQR-Bench will be released as a Python package -- \texttt{gqr}.

[Arxiv](https://arxiv.org/abs/2505.14524)