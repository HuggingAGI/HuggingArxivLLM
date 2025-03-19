# # 基于检索增强生成的大型语言模型对名人善恶声誉的判断

发布时间：2025年03月18日

`LLM应用` `公共关系`

> Good/Evil Reputation Judgment of Celebrities by LLMs via Retrieval Augmented Generation

# 摘要

> 本文探讨了大型语言模型（LLMs）能否辨别善恶，特别是在判断名人声誉方面的能力。具体来说，我们首先利用 ChatGPT 从网页名人文章中提取提及目标名人的句子。随后，ChatGPT 根据内容对这些句子进行分类并命名，这些名称即为名人的“方面”。通过检索增强生成（RAG）框架，我们发现大语言模型在评估名人各方面声誉方面表现出色。最后，我们证明了该方法在判断名人声誉方面显著优于现有集成 RAG 功能的服务，凸显了其优势。

> The purpose of this paper is to examine whether large language models (LLMs) can understand what is good and evil with respect to judging good/evil reputation of celebrities. Specifically, we first apply a large language model (namely, ChatGPT) to the task of collecting sentences that mention the target celebrity from articles about celebrities on Web pages. Next, the collected sentences are categorized based on their contents by ChatGPT, where ChatGPT assigns a category name to each of those categories. Those assigned category names are referred to as "aspects" of each celebrity. Then, by applying the framework of retrieval augmented generation (RAG), we show that the large language model is quite effective in the task of judging good/evil reputation of aspects and descriptions of each celebrity. Finally, also in terms of proving the advantages of the proposed method over existing services incorporating RAG functions, we show that the proposed method of judging good/evil of aspects/descriptions of each celebrity significantly outperform an existing service incorporating RAG functions.

[Arxiv](https://arxiv.org/abs/2503.14382)