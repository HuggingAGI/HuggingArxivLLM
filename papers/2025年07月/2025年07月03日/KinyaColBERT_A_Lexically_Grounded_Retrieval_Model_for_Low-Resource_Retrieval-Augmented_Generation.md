# KinyaColBERT: 专为低资源环境下的检索增强生成设计的基于词汇检索模型

发布时间：2025年07月03日

`RAG`

> KinyaColBERT: A Lexically Grounded Retrieval Model for Low-Resource Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLM）技术的广泛应用正在推动各个领域中聊天机器人和虚拟助手的新型应用。为了将LLM扎根于可信领域并避免幻觉问题，检索增强生成（RAG）作为一种可行的解决方案应运而生。为了在资源有限的环境中部署可持续的RAG系统，实现高检索准确性不仅是使用上的要求，也是节省成本的策略。通过在基尼亚卢旺达语数据集上的实证评估，我们发现，预训练语言模型中有限的语言覆盖范围和不充分的子词分词是实现高检索准确性的最大限制因素。我们提出了一种新的检索器模型KinyaColBERT，它结合了查询与文档之间的后期词级别交互，以及基于形态学的分词与两级变换器编码相结合的方法。这一方法生成了既精细又自洽的词法上下文嵌入。我们的评估结果表明，KinyaColBERT在基尼亚卢旺达语农业检索基准上优于强大的基线模型和领先的商业文本嵌入API。通过采用这种检索策略，我们相信，其他资源有限环境中的实践者不仅可以实现可靠的RAG系统，还能部署更经济高效的解决方案。

> The recent mainstream adoption of large language model (LLM) technology is enabling novel applications in the form of chatbots and virtual assistants across many domains. With the aim of grounding LLMs in trusted domains and avoiding the problem of hallucinations, retrieval-augmented generation (RAG) has emerged as a viable solution. In order to deploy sustainable RAG systems in low-resource settings, achieving high retrieval accuracy is not only a usability requirement but also a cost-saving strategy. Through empirical evaluations on a Kinyarwanda-language dataset, we find that the most limiting factors in achieving high retrieval accuracy are limited language coverage and inadequate sub-word tokenization in pre-trained language models. We propose a new retriever model, KinyaColBERT, which integrates two key concepts: late word-level interactions between queries and documents, and a morphology-based tokenization coupled with two-tier transformer encoding. This methodology results in lexically grounded contextual embeddings that are both fine-grained and self-contained. Our evaluation results indicate that KinyaColBERT outperforms strong baselines and leading commercial text embedding APIs on a Kinyarwanda agricultural retrieval benchmark. By adopting this retrieval strategy, we believe that practitioners in other low-resource settings can not only achieve reliable RAG systems but also deploy solutions that are more cost-effective.

[Arxiv](https://arxiv.org/abs/2507.03241)