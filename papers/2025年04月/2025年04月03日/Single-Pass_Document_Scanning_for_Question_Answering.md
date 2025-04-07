# 单次文档扫描助力问答任务

发布时间：2025年04月03日

`LLM应用` `问答系统` `信息检索`

> Single-Pass Document Scanning for Question Answering

# 摘要

> 处理大型文档进行问答极具挑战性：基于分块的嵌入方法常会忽略重要的全局上下文，而全上下文的 transformer 对于数十万计的标记来说计算成本往往过高。我们提出了一种单次文档扫描方法，能在线性时间内处理整个文本，同时在决定哪些句子与查询最相关时保持全局连贯性。在41个问答基准测试中，我们的单次扫描器始终优于基于分块的嵌入方法，并且在计算成本仅为大语言模型一小部分的情况下与之竞争。通过在不中断分块的情况下基于整个先前上下文进行条件处理，该方法保持了全局连贯性，这对长文档尤为重要。总体而言，单次文档扫描为处理海量文本的问答提供了一个简单而有效的解决方案。所有代码、数据集和模型检查点均可在 https://github.com/MambaRetriever/MambaRetriever 获取。

> Handling extremely large documents for question answering is challenging: chunk-based embedding methods often lose track of important global context, while full-context transformers can be prohibitively expensive for hundreds of thousands of tokens. We propose a single-pass document scanning approach that processes the entire text in linear time, preserving global coherence while deciding which sentences are most relevant to the query. On 41 QA benchmarks, our single-pass scanner consistently outperforms chunk-based embedding methods and competes with large language models at a fraction of the computational cost. By conditioning on the entire preceding context without chunk breaks, the method preserves global coherence, which is especially important for long documents. Overall, single-pass document scanning offers a simple solution for question answering over massive text. All code, datasets, and model checkpoints are available at https://github.com/MambaRetriever/MambaRetriever

[Arxiv](https://arxiv.org/abs/2504.03101)