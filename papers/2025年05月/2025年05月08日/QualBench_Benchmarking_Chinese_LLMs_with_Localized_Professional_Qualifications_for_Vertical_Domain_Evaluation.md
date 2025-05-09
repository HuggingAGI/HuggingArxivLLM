# QualBench：基于领域专业认证的中文大语言模型垂直领域评估基准

发布时间：2025年05月08日

`LLM应用`

> QualBench: Benchmarking Chinese LLMs with Localized Professional Qualifications for Vertical Domain Evaluation

# 摘要

> 中文大型语言模型（LLMs）的快速发展凸显了领域特定评估的重要性，以确保可靠的应用。然而，现有的基准测试通常缺乏对垂直领域的覆盖，并且对中文工作环境的洞察有限。我们利用资格考试作为统一的人类专业知识评估框架，引入了QualBench，这是首个专注于对中国LLMs进行本地化评估的多领域中文问答基准。该数据集包含六个垂直领域的17,000多个问题，数据选择基于24个中国资格认证，紧密贴合国家政策和工作标准。通过全面评估，Qwen2.5模型的表现优于更先进的GPT-4，中文LLMs在整体上也优于非中文模型，突显了本地化领域知识在满足资格要求中的重要性。最佳性能75.26%揭示了模型能力在领域覆盖方面的现有差距。此外，我们展示了LLM与 crowdsourcing 机制协作的失败，并提出了多领域知识增强和基于联邦学习的垂直领域LLM训练的机会。

> The rapid advancement of Chinese large language models (LLMs) underscores the need for domain-specific evaluations to ensure reliable applications. However, existing benchmarks often lack coverage in vertical domains and offer limited insights into the Chinese working context. Leveraging qualification exams as a unified framework for human expertise evaluation, we introduce QualBench, the first multi-domain Chinese QA benchmark dedicated to localized assessment of Chinese LLMs. The dataset includes over 17,000 questions across six vertical domains, with data selections grounded in 24 Chinese qualifications to closely align with national policies and working standards. Through comprehensive evaluation, the Qwen2.5 model outperformed the more advanced GPT-4o, with Chinese LLMs consistently surpassing non-Chinese models, highlighting the importance of localized domain knowledge in meeting qualification requirements. The best performance of 75.26% reveals the current gaps in domain coverage within model capabilities. Furthermore, we present the failure of LLM collaboration with crowdsourcing mechanisms and suggest the opportunities for multi-domain RAG knowledge enhancement and vertical domain LLM training with Federated Learning.

[Arxiv](https://arxiv.org/abs/2505.05225)