# 基于LLM的推荐系统中后门攻击与防御的探索

发布时间：2025年04月15日

`LLM应用` `推荐系统` `电子商务`

> Exploring Backdoor Attack and Defense for LLM-empowered Recommendations

# 摘要

> 大型语言模型（LLMs）与推荐系统（RecSys）的融合，极大地推动了个性化推荐的发展，并吸引了广泛关注。然而，基于LLMs的推荐系统在后门攻击下的安全性仍研究不足。本文提出一个新问题：能否将带有特定触发词的后门注入到基于LLMs的推荐系统中，从而在商品标题中附加触发词时操纵推荐结果？

为研究这一问题，我们提出了一种新的攻击框架——针对推荐系统的后门注入投毒攻击（BadRec）。该框架通过在商品标题中嵌入特定触发词，并利用多个虚假用户与这些商品进行交互，从而有效投毒训练集，将后门注入到基于LLMs的推荐系统中。实验结果表明，仅需用对抗样本投毒1%的训练数据，即可成功植入后门，实现对推荐结果的操纵。

为了进一步缓解这一安全威胁，我们提出了一种通用防御策略——投毒扫描器（P-Scanner）。具体而言，我们引入了一种基于LLMs的投毒扫描器，通过LLMs强大的语言理解和丰富知识，检测出被投毒的商品。同时，我们还引入了触发词增强代理，生成多样化的合成触发词，引导投毒扫描器学习被投毒商品检测任务的领域知识。在三个真实数据集上的广泛实验验证了所提出的P-Scanner的有效性。

> The fusion of Large Language Models (LLMs) with recommender systems (RecSys) has dramatically advanced personalized recommendations and drawn extensive attention. Despite the impressive progress, the safety of LLM-based RecSys against backdoor attacks remains largely under-explored. In this paper, we raise a new problem: Can a backdoor with a specific trigger be injected into LLM-based Recsys, leading to the manipulation of the recommendation responses when the backdoor trigger is appended to an item's title? To investigate the vulnerabilities of LLM-based RecSys under backdoor attacks, we propose a new attack framework termed Backdoor Injection Poisoning for RecSys (BadRec). BadRec perturbs the items' titles with triggers and employs several fake users to interact with these items, effectively poisoning the training set and injecting backdoors into LLM-based RecSys. Comprehensive experiments reveal that poisoning just 1% of the training data with adversarial examples is sufficient to successfully implant backdoors, enabling manipulation of recommendations. To further mitigate such a security threat, we propose a universal defense strategy called Poison Scanner (P-Scanner). Specifically, we introduce an LLM-based poison scanner to detect the poisoned items by leveraging the powerful language understanding and rich knowledge of LLMs. A trigger augmentation agent is employed to generate diverse synthetic triggers to guide the poison scanner in learning domain-specific knowledge of the poisoned item detection task. Extensive experiments on three real-world datasets validate the effectiveness of the proposed P-Scanner.

[Arxiv](https://arxiv.org/abs/2504.11182)