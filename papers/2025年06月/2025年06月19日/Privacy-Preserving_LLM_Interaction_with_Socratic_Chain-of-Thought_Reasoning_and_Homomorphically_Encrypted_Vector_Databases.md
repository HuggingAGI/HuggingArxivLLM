# 结合苏格拉底式链式推理与同态加密向量数据库，实现隐私保护的大型语言模型交互。

发布时间：2025年06月19日

`Agent` `隐私保护`

> Privacy-Preserving LLM Interaction with Socratic Chain-of-Thought Reasoning and Homomorphically Encrypted Vector Databases

# 摘要

> 大型语言模型（LLMs）正越来越多地作为个人代理，访问用户的日历、邮件和医疗记录等敏感信息。用户目前面临两难选择：将私人记录（多存储于远程数据库）发送给强大但不可信的LLM提供商，增加隐私风险；或在本地运行较弱的模型。我们提出了一个解决方案。我们的苏格拉底式链式思维推理方法首先将通用的非私人查询发送给强大但不可信的LLM，生成链式思维（CoT）提示和详细子查询，全程不接触用户数据。随后，我们将这些子查询嵌入，并利用全同态加密向量数据库，在百万级个人数据中完成亚秒级加密语义搜索。这一规模足以涵盖多年积累的个人文档、邮件和记录。最后，我们将CoT提示和解密数据输入本地语言模型，生成最终响应。在LoCoMo长上下文问答基准测试中，结合GPT-4o和本地Llama-3.2-1B模型的混合框架，相比单独使用GPT-4o，性能提升高达7.1个百分点。这标志着任务分解和拆分系统的第一步，实现了将任务分配给不可信的强大LLM和较弱的本地模型，同时保护用户隐私。

> Large language models (LLMs) are increasingly used as personal agents, accessing sensitive user data such as calendars, emails, and medical records. Users currently face a trade-off: They can send private records, many of which are stored in remote databases, to powerful but untrusted LLM providers, increasing their exposure risk. Alternatively, they can run less powerful models locally on trusted devices. We bridge this gap. Our Socratic Chain-of-Thought Reasoning first sends a generic, non-private user query to a powerful, untrusted LLM, which generates a Chain-of-Thought (CoT) prompt and detailed sub-queries without accessing user data. Next, we embed these sub-queries and perform encrypted sub-second semantic search using our Homomorphically Encrypted Vector Database across one million entries of a single user's private data. This represents a realistic scale of personal documents, emails, and records accumulated over years of digital activity. Finally, we feed the CoT prompt and the decrypted records to a local language model and generate the final response. On the LoCoMo long-context QA benchmark, our hybrid framework, combining GPT-4o with a local Llama-3.2-1B model, outperforms using GPT-4o alone by up to 7.1 percentage points. This demonstrates a first step toward systems where tasks are decomposed and split between untrusted strong LLMs and weak local ones, preserving user privacy.

[Arxiv](https://arxiv.org/abs/2506.17336)