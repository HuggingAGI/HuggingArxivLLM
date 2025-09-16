# CBP-Tuning：面向黑盒大型语言模型的高效本地定制

发布时间：2025年09月15日

`LLM应用` `医疗健康` `金融科技`

> CBP-Tuning: Efficient Local Customization for Black-box Large Language Models

# 摘要

> 定制大型语言模型（LLMs）的成本高昂，这从根本上限制了其对用户个性化需求的适应性。因此，LLMs正越来越多地以云服务形式提供，但这种模式存在严重局限：提供商难以大规模支持个性化定制，而用户在暴露敏感数据时则面临隐私风险。为解决这一双重难题，我们提出了定制化黑盒提示调优（CBP-Tuning）——一种新颖框架，可在保护双向隐私的同时实现高效本地定制。具体而言，我们设计了两阶段框架：（1）服务器端训练提示生成器，以捕捉特定领域及与任务无关的能力；（2）用户端通过无梯度优化为单个任务定制软提示。该方法无需用户访问模型权重或上传私有数据，每个任务仅需一个定制向量即可实现有效适配。此外，在常识推理、医疗和金融领域的评估显示，CBP-Tuning的性能优于基线方法，充分彰显了其在任务无关处理和隐私保护方面的优势。

> The high costs of customizing large language models (LLMs) fundamentally limit their adaptability to user-specific needs. Consequently, LLMs are increasingly offered as cloud-based services, a paradigm that introduces critical limitations: providers struggle to support personalized customization at scale, while users face privacy risks when exposing sensitive data. To address this dual challenge, we propose Customized Black-box Prompt Tuning (CBP-Tuning), a novel framework that facilitates efficient local customization while preserving bidirectional privacy. Specifically, we design a two-stage framework: (1) a prompt generator trained on the server-side to capture domain-specific and task-agnostic capabilities, and (2) user-side gradient-free optimization that tailors soft prompts for individual tasks. This approach eliminates the need for users to access model weights or upload private data, requiring only a single customized vector per task while achieving effective adaptation. Furthermore, the evaluation of CBP-Tuning in the commonsense reasoning, medical and financial domain settings demonstrates superior performance compared to baselines, showcasing its advantages in task-agnostic processing and privacy preservation.

[Arxiv](https://arxiv.org/abs/2509.12112)