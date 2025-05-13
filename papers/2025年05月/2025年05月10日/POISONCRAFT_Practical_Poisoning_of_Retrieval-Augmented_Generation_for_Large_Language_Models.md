# POISONCRAFT：大型语言模型中增强检索生成的实用投毒策略

发布时间：2025年05月10日

`RAG` `人工智能` `系统安全`

> POISONCRAFT: Practical Poisoning of Retrieval-Augmented Generation for Large Language Models

# 摘要

> 大型语言模型（LLMs）凭借强大的推理与文本生成能力，在多个领域取得了显著成功。然而，尽管表现出色，LLMs易产生幻觉，导致错误或误导性输出，这主要源于缺乏最新知识或领域特定信息。检索增强生成（RAG）通过利用外部知识源，成为缓解幻觉的有前途方法。然而，RAG系统的安全性尚未得到充分研究。

本文提出了一种针对RAG系统的中毒攻击——POISONCRAFT，可误导模型引用欺诈网站。与现有攻击相比，POISONCRAFT更具实用性，无需访问目标用户查询信息或编辑查询内容。它不仅确保注入文本可被模型检索，还确保LLM在响应中引用这些文本。

我们在不同数据集、检索器和语言模型的RAG流水线上验证了POISONCRAFT的有效性，发现其在跨检索器转移，包括黑盒系统时仍具效力。通过案例研究，揭示了攻击对检索行为及生成模型中逐步推理轨迹的影响，并评估了其在多种防御机制下的鲁棒性。

实验结果验证了我们威胁模型的实际性，突显了RAG系统在现实应用中的关键安全风险。我们发布了代码ootnote{https://github.com/AndyShaw01/PoisonCraft}，支持未来对现实环境中RAG系统安全与鲁棒性的研究。

> Large language models (LLMs) have achieved remarkable success in various domains, primarily due to their strong capabilities in reasoning and generating human-like text. Despite their impressive performance, LLMs are susceptible to hallucinations, which can lead to incorrect or misleading outputs. This is primarily due to the lack of up-to-date knowledge or domain-specific information. Retrieval-augmented generation (RAG) is a promising approach to mitigate hallucinations by leveraging external knowledge sources. However, the security of RAG systems has not been thoroughly studied. In this paper, we study a poisoning attack on RAG systems named POISONCRAFT, which can mislead the model to refer to fraudulent websites. Compared to existing poisoning attacks on RAG systems, our attack is more practical as it does not require access to the target user query's info or edit the user query. It not only ensures that injected texts can be retrieved by the model, but also ensures that the LLM will be misled to refer to the injected texts in its response. We demonstrate the effectiveness of POISONCRAFTacross different datasets, retrievers, and language models in RAG pipelines, and show that it remains effective when transferred across retrievers, including black-box systems. Moreover, we present a case study revealing how the attack influences both the retrieval behavior and the step-by-step reasoning trace within the generation model, and further evaluate the robustness of POISONCRAFTunder multiple defense mechanisms. These results validate the practicality of our threat model and highlight a critical security risk for RAG systems deployed in real-world applications. We release our code\footnote{https://github.com/AndyShaw01/PoisonCraft} to support future research on the security and robustness of RAG systems in real-world settings.

[Arxiv](https://arxiv.org/abs/2505.06579)