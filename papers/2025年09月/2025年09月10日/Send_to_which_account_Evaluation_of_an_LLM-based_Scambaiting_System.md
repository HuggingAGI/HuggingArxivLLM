# 该往哪个账户转账？基于大型语言模型的反诈骗钓鱼系统评估

发布时间：2025年09月10日

`LLM应用` `金融科技`

> Send to which account? Evaluation of an LLM-based Scambaiting System

# 摘要

> 诈骗分子正愈发频繁地利用生成式AI（GenAI）技术，大规模制作足以乱真的钓鱼内容，加剧金融诈骗，动摇公众信任。尽管检测算法、用户培训和被动删除行动等传统防御措施仍不可或缺，但它们往往难以有效摧毁诈骗分子赖以生存的基础设施，包括钱骡银行账户和加密货币钱包。为弥合这一短板，一种主动且新兴的策略应运而生——利用对话式蜜罐与诈骗分子周旋，从中提取可操作的威胁情报。本文首次对基于大型语言模型（LLMs）驱动的反诈骗诱捕系统开展了大规模真实场景评估。经过五个月的部署，该系统与真实诈骗分子展开了2600余次互动，积累了超过18700条消息的数据集。其信息披露率（IDR）约达32%，成功获取了钱骡账户等敏感金融信息。此外，该系统的人工接受率（HAR）稳定在70%左右，表明LLM生成的回复与人工操作员的偏好高度契合。在取得上述成果的同时，我们的分析也揭示了核心的运营难题：系统在互动启动环节表现不佳，仅有48.7%的诈骗分子会回复防御者发送的初始诱饵消息。这些发现不仅凸显了进一步优化的必要性，也为改进自动化反诈骗诱捕系统的设计提供了切实可行的思路。

> Scammers are increasingly harnessing generative AI(GenAI) technologies to produce convincing phishing content at scale, amplifying financial fraud and undermining public trust. While conventional defenses, such as detection algorithms, user training, and reactive takedown efforts remain important, they often fall short in dismantling the infrastructure scammers depend on, including mule bank accounts and cryptocurrency wallets. To bridge this gap, a proactive and emerging strategy involves using conversational honeypots to engage scammers and extract actionable threat intelligence. This paper presents the first large-scale, real-world evaluation of a scambaiting system powered by large language models (LLMs). Over a five-month deployment, the system initiated over 2,600 engagements with actual scammers, resulting in a dataset of more than 18,700 messages. It achieved an Information Disclosure Rate (IDR) of approximately 32%, successfully extracting sensitive financial information such as mule accounts. Additionally, the system maintained a Human Acceptance Rate (HAR) of around 70%, indicating strong alignment between LLM-generated responses and human operator preferences. Alongside these successes, our analysis reveals key operational challenges. In particular, the system struggled with engagement takeoff: only 48.7% of scammers responded to the initial seed message sent by defenders. These findings highlight the need for further refinement and provide actionable insights for advancing the design of automated scambaiting systems.

[Arxiv](https://arxiv.org/abs/2509.08493)