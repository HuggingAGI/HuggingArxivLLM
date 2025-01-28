# 基于RAG的LLMs实现的高级实时欺诈检测

发布时间：2025年01月25日

`RAG

理由：该论文摘要提到了一种创新的实时欺诈检测机制，利用检索增强生成技术（RAG）来应对欺诈电话和用户冒充的挑战。具体来说，系统通过基于RAG的模型来验证呼叫者是否在索取私人信息，并采用两步验证流程来确认呼叫者身份。这些内容明确提到了RAG技术的应用，因此将其分类为RAG。`

> Advanced Real-Time Fraud Detection Using RAG-Based LLMs

# 摘要

> 人工智能在现代社会中犹如一把双刃剑，既是福音也是隐患。它赋予个人力量的同时，也为恶意行为者提供了实施欺诈的机会，如欺诈电话和用户冒充。面对这一日益严峻的威胁，我们亟需一个强大的保护系统。本文提出了一种创新的实时欺诈检测机制，利用检索增强生成技术，从两个方面应对这一挑战。首先，我们的系统具备持续更新的政策检查功能，能够实时转录电话通话，并通过基于RAG的模型验证呼叫者是否在索取私人信息，确保对话的透明性和真实性。其次，我们采用两步验证流程，实时检查用户冒充行为，确认呼叫者身份，确保问责制。我们系统的一大创新在于，无需重新训练整个模型即可更新政策，极大提升了系统的适应性。通过使用合成电话录音进行验证，我们的基于RAG的方法在100次通话中实现了97.98%的准确率和97.44%的F1分数，表现优于现有最先进的方法。这种强大且灵活的欺诈检测系统非常适合实际应用。

> Artificial Intelligence has become a double edged sword in modern society being both a boon and a bane. While it empowers individuals it also enables malicious actors to perpetrate scams such as fraudulent phone calls and user impersonations. This growing threat necessitates a robust system to protect individuals In this paper we introduce a novel real time fraud detection mechanism using Retrieval Augmented Generation technology to address this challenge on two fronts. First our system incorporates a continuously updating policy checking feature that transcribes phone calls in real time and uses RAG based models to verify that the caller is not soliciting private information thus ensuring transparency and the authenticity of the conversation. Second we implement a real time user impersonation check with a two step verification process to confirm the callers identity ensuring accountability. A key innovation of our system is the ability to update policies without retraining the entire model enhancing its adaptability. We validated our RAG based approach using synthetic call recordings achieving an accuracy of 97.98 percent and an F1score of 97.44 percent with 100 calls outperforming state of the art methods. This robust and flexible fraud detection system is well suited for real world deployment.

[Arxiv](https://arxiv.org/abs/2501.15290)