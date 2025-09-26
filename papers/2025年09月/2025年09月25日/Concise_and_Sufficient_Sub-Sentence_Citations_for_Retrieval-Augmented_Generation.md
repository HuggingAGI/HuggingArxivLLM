# 面向检索增强生成的简洁充分子句级引用

发布时间：2025年09月25日

`RAG` `基础理论`

> Concise and Sufficient Sub-Sentence Citations for Retrieval-Augmented Generation

# 摘要

> 在检索增强生成（RAG）问答系统中，为大型语言模型（LLM）的输出生成引用可增强结果的可验证性，并帮助用户识别潜在的幻觉内容。然而，现有归因方法生成的引用存在两个问题：一是引用多停留在句子甚至段落层面，长句或段落往往夹杂大量无关信息；二是句子级引用可能遗漏验证所需的关键信息，导致用户不得不阅读上下文。为此，本文提出生成子句级引用——这类引用既简洁又充分，可减少用户验证生成结果正确性的工作量。具体而言，我们首先制定了子句引用的标注指南并构建了对应数据集，随后提出了一个归因框架以生成符合上述标准的引用。该框架借助LLM自动生成任务所需的微调数据，并通过信用模型过滤低质量样本。在构建的数据集上进行的实验表明，该方法可生成高质量且可读性更强的引用。

> In retrieval-augmented generation (RAG) question answering systems, generating citations for large language model (LLM) outputs enhances verifiability and helps users identify potential hallucinations. However, we observe two problems in the citations produced by existing attribution methods. First, the citations are typically provided at the sentence or even paragraph level. Long sentences or paragraphs may include a substantial amount of irrelevant content. Second, sentence-level citations may omit information that is essential for verifying the output, forcing users to read the surrounding context. In this paper, we propose generating sub-sentence citations that are both concise and sufficient, thereby reducing the effort required by users to confirm the correctness of the generated output. To this end, we first develop annotation guidelines for such citations and construct a corresponding dataset. Then, we propose an attribution framework for generating citations that adhere to our standards. This framework leverages LLMs to automatically generate fine-tuning data for our task and employs a credit model to filter out low-quality examples. Our experiments on the constructed dataset demonstrate that the propose approach can generate high-quality and more readable citations.

[Arxiv](https://arxiv.org/abs/2509.20859)