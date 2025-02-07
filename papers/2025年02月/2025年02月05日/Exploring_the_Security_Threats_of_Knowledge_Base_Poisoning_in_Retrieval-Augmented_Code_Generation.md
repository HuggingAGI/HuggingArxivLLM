# 探究知识库中毒对检索增强代码生成的安全威胁

发布时间：2025年02月05日

`RAG

理由：这篇论文主要讨论了检索增强代码生成（RACG）系统的安全问题，特别是知识库中易受攻击的代码示例对生成代码安全性的影响。RACG系统属于检索增强生成（RAG）的范畴，因为它利用外部知识库中的信息来增强代码生成。因此，这篇论文应被分类为RAG。` `软件开发` `信息安全`

> Exploring the Security Threats of Knowledge Base Poisoning in Retrieval-Augmented Code Generation

# 摘要

> 大型语言模型（LLMs）与软件开发的结合彻底改变了这一领域，尤其是通过检索增强代码生成（RACG）系统，该系统利用外部知识库中的信息来增强代码生成。然而，RACG系统的安全影响，特别是知识库中易受攻击的代码示例所带来的风险，仍然在很大程度上未被探索。考虑到公共代码库通常是RACG系统中知识库收集的来源，而这些代码库通常对社区中的任何人都是可访问的，这一风险尤其令人担忧。恶意攻击者可以利用这种可访问性将易受攻击的代码注入知识库，使其变得有毒。一旦这些被污染的样本被检索并整合到生成的代码中，它们就会将安全漏洞传播到最终产品中。本文首次全面研究了与RACG系统相关的安全风险，重点关注知识库中的易受攻击代码如何影响生成代码的安全性。我们通过使用四个主要LLM、两个检索器和两种污染场景的广泛实验，研究了不同设置下LLM生成的代码安全性。我们的研究结果突显了知识库污染的严重威胁，即使是一个被污染的代码示例也可能危及高达48%的生成代码。我们的研究结果为RACG系统中的漏洞引入提供了关键的见解，并提供了实用的缓解建议，从而有助于在未来工作中提高LLM生成代码的安全性。

> The integration of Large Language Models (LLMs) into software development has revolutionized the field, particularly through the use of Retrieval-Augmented Code Generation (RACG) systems that enhance code generation with information from external knowledge bases. However, the security implications of RACG systems, particularly the risks posed by vulnerable code examples in the knowledge base, remain largely unexplored. This risk is particularly concerning given that public code repositories, which often serve as the sources for knowledge base collection in RACG systems, are usually accessible to anyone in the community. Malicious attackers can exploit this accessibility to inject vulnerable code into the knowledge base, making it toxic. Once these poisoned samples are retrieved and incorporated into the generated code, they can propagate security vulnerabilities into the final product. This paper presents the first comprehensive study on the security risks associated with RACG systems, focusing on how vulnerable code in the knowledge base compromises the security of generated code. We investigate the LLM-generated code security across different settings through extensive experiments using four major LLMs, two retrievers, and two poisoning scenarios. Our findings highlight the significant threat of knowledge base poisoning, where even a single poisoned code example can compromise up to 48% of generated code. Our findings provide crucial insights into vulnerability introduction in RACG systems and offer practical mitigation recommendations, thereby helping improve the security of LLM-generated code in future works.

[Arxiv](https://arxiv.org/abs/2502.03233)