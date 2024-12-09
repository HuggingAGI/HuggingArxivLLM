# SurgBox：由代理驱动、带有手术副驾驶的手术室沙盒

发布时间：2024年12月06日

`Agent` `外科手术`

> SurgBox: Agent-Driven Operating Room Sandbox with Surgery Copilot

# 摘要

> 外科手术干预，尤其是在神经学领域，是复杂且高风险的情形，给手术团队造成了沉重的认知负担。尽管精心的教育和实践能够提升认知能力，然而出于患者安全的考虑，手术培训的机会依旧有限。为应对手术培训与操作中的这些认知难题，我们提出了 SurgBox，这是一个由代理驱动的沙盒框架，旨在沉浸式手术模拟中系统性地增强外科医生的认知能力。具体而言，我们的 SurgBox 借助大型语言模型（LLMs）和定制的检索增强生成（RAG），真实地复刻各种手术角色，为审慎的实践营造逼真的培训环境。特别地，我们设计了 Surgery Copilot，这是一个由人工智能驱动的助手，能够积极协调手术信息流并支持临床决策，进而减轻手术期间手术团队的认知工作量。通过融入一种新颖的长短期记忆机制，我们的 Surgery Copilot 能够有效地平衡即时的程序协助与全面的手术知识。通过使用真实的神经外科手术程序记录开展的大量实验，验证了我们的 SurgBox 框架在提升手术认知能力和支持临床决策方面的成效。通过提供解决认知挑战的培训与操作支持的集成方案，我们的 SurgBox 框架推动了外科教育与实践，有可能改变手术结果和医疗保健质量。代码可在 https://github.com/franciszchen/SurgBox 获取。

> Surgical interventions, particularly in neurology, represent complex and high-stakes scenarios that impose substantial cognitive burdens on surgical teams. Although deliberate education and practice can enhance cognitive capabilities, surgical training opportunities remain limited due to patient safety concerns. To address these cognitive challenges in surgical training and operation, we propose SurgBox, an agent-driven sandbox framework to systematically enhance the cognitive capabilities of surgeons in immersive surgical simulations. Specifically, our SurgBox leverages large language models (LLMs) with tailored Retrieval-Augmented Generation (RAG) to authentically replicate various surgical roles, enabling realistic training environments for deliberate practice. In particular, we devise Surgery Copilot, an AI-driven assistant to actively coordinate the surgical information stream and support clinical decision-making, thereby diminishing the cognitive workload of surgical teams during surgery. By incorporating a novel Long-Short Memory mechanism, our Surgery Copilot can effectively balance immediate procedural assistance with comprehensive surgical knowledge. Extensive experiments using real neurosurgical procedure records validate our SurgBox framework in both enhancing surgical cognitive capabilities and supporting clinical decision-making. By providing an integrated solution for training and operational support to address cognitive challenges, our SurgBox framework advances surgical education and practice, potentially transforming surgical outcomes and healthcare quality. The code is available at https://github.com/franciszchen/SurgBox.

[Arxiv](https://arxiv.org/abs/2412.05187)