# **Spa-VLM：针对基于 RAG 的视觉语言模型的隐秘投毒攻击**

发布时间：2025年05月28日

`RAG` `计算机视觉` `网络安全`

> Spa-VLM: Stealthy Poisoning Attacks on RAG-based VLM

# 摘要

> 随着视觉语言模型（VLM）的快速发展，视觉问答任务取得了长足进步。然而，现有VLM由于知识更新不及时，常常生成错误答案。为解决这一问题，最近研究将大型语言模型中的检索增强生成（RAG）技术引入VLM，融合外部多模态知识，提升VLM系统的准确性和实用性。然而，LLM中的RAG技术可能易受数据中毒攻击，基于RAG的VLM也可能面临此类威胁。本文首先揭示了基于RAG的大模型在中毒攻击下的脆弱性，发现现有单模态RAG中毒攻击在多模态RAG场景下完全失效。为解决这一问题，我们提出Spa-VLM，一种针对基于RAG的VLM的隐秘中毒攻击新范式。我们精心设计了包含对抗性图像和误导性文本的恶意多模态知识条目，并将其注入RAG的知识库。当用户访问VLM服务时，系统可能会生成误导性输出。我们在两个维基百科数据集和两种不同RAG上评估Spa-VLM。结果表明，仅需向包含10万和200万条目的知识库中注入5个恶意条目，攻击成功率便超过80%，优于现有针对基于RAG的LLM的中毒攻击。此外，我们评估了多种防御机制，结果均未能有效防御Spa-VLM，证明了我们攻击的有效性和鲁棒性。

> With the rapid development of the Vision-Language Model (VLM), significant progress has been made in Visual Question Answering (VQA) tasks. However, existing VLM often generate inaccurate answers due to a lack of up-to-date knowledge. To address this issue, recent research has introduced Retrieval-Augmented Generation (RAG) techniques, commonly used in Large Language Models (LLM), into VLM, incorporating external multi-modal knowledge to enhance the accuracy and practicality of VLM systems. Nevertheless, the RAG in LLM may be susceptible to data poisoning attacks. RAG-based VLM may also face the threat of this attack. This paper first reveals the vulnerabilities of the RAG-based large model under poisoning attack, showing that existing single-modal RAG poisoning attacks have a 100\% failure rate in multi-modal RAG scenarios. To address this gap, we propose Spa-VLM (Stealthy Poisoning Attack on RAG-based VLM), a new paradigm for poisoning attacks on large models. We carefully craft malicious multi-modal knowledge entries, including adversarial images and misleading text, which are then injected into the RAG's knowledge base. When users access the VLM service, the system may generate misleading outputs. We evaluate Spa-VLM on two Wikipedia datasets and across two different RAGs. Results demonstrate that our method achieves highly stealthy poisoning, with the attack success rate exceeding 0.8 after injecting just 5 malicious entries into knowledge bases with 100K and 2M entries, outperforming state-of-the-art poisoning attacks designed for RAG-based LLMs. Additionally, we evaluated several defense mechanisms, all of which ultimately proved ineffective against Spa-VLM, underscoring the effectiveness and robustness of our attack.

[Arxiv](https://arxiv.org/abs/2505.23828)