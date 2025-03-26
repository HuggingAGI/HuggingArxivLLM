# 基于可验证临床计算器及其元数据的 LLM 驱动临床计算器聊天机器人

发布时间：2025年03月21日

`LLM应用

理由：这篇论文展示了大型语言模型（LLMs）在医疗领域的实际应用，通过结合RAG技术设计了一个聊天机器人，用于调用临床计算器并进行准确计算。尽管提到了RAG技术，但论文的重点在于应用层面，因此归类为LLM应用。` `聊天机器人`

> An LLM-Powered Clinical Calculator Chatbot Backed by Verifiable Clinical Calculators and their Metadata

# 摘要

> 临床计算器在医疗领域广泛应用，而大型语言模型（LLMs）让通过自然语言与它们互动成为可能。我们展示了一个专门设计的聊天机器人，它通过结合LLM工具和检索增强生成（RAG）技术，能够准确调用可验证临床计算器的软件实现及其元数据。在四个自然语言对话任务的对比测试中，我们的聊天机器人表现优异：在查询计算器元数据内容时达到了100%的准确率；在使用完整句子时，临床计算准确率达到86.4%，远超现成LLM的61.8%；在使用医学简写时，准确率也达到79.2%，高于现成LLM的62.0%。值得注意的是，我们的聊天机器人在使用完整句子时完全避免了计算错误（0% vs. 16.8%），而在使用医学简写时，错误率也大幅降低至2.4%（vs. 18%）。尽管目前该聊天机器人尚未准备好投入临床使用，但这些结果表明我们在减少错误计算方面取得了显著进展。

> Clinical calculators are widely used, and large language models (LLMs) make it possible to engage them using natural language. We demonstrate a purpose-built chatbot that leverages software implementations of verifiable clinical calculators via LLM tools and metadata about these calculators via retrieval augmented generation (RAG). We compare the chatbot's response accuracy to an unassisted off-the-shelf LLM on four natural language conversation workloads. Our chatbot achieves 100% accuracy on queries interrogating calculator metadata content and shows a significant increase in clinical calculation accuracy vs. the off-the-shelf LLM when prompted with complete sentences (86.4% vs. 61.8%) or with medical shorthand (79.2% vs. 62.0%). It eliminates calculation errors when prompted with complete sentences (0% vs. 16.8%) and greatly reduces them when prompted with medical shorthand (2.4% vs. 18%). While our chatbot is not ready for clinical use, these results show progress in minimizing incorrect calculation results.

[Arxiv](https://arxiv.org/abs/2503.17550)