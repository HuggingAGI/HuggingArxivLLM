# PRSA：一种针对大型语言模型的新型攻击手段——Prompt Reverse Stealing，通过逆向窃取提示信息对LLM发起挑战。

发布时间：2024年02月29日

`LLM应用`

> PRSA: Prompt Reverse Stealing Attacks against Large Language Models

# 摘要

> 提示作为一种关键的知识产权，赋予LLMs无需微调就能胜任特定任务的能力，凸显其价值日益提升。如今，诸如提示市场和各类LLM应用等基于提示的服务不断涌现，服务商常借助展示输入-输出实例的方式揭示提示的强大功能，吸引用户关注。然而，这种做法带来一个核心安全隐患：公开输入-输出示例是否可能增加泄露潜在提示的风险，进而侵犯开发者的知识产权呢？当前，这一问题尚缺乏系统性研究。为此，本文首开先河，深度探究并构建了一套针对商业LLMs的创新逆向窃取提示攻击框架——PRSA。该框架的核心在于通过解析输入-输出对的关键特征，模拟并逐渐揭秘目标提示。PRSA包含两大关键步骤：提示变异与提示剪枝。在变异环节，我们设计了一种基于差异化反馈的提示注意力算法，精准捕获关键特征，助力高效推测目标提示。而在剪枝环节，则甄别并遮蔽那些依赖特定输入的词语，从而使提示能灵活应对多样化的输入，实现更好的泛化能力。经过大规模的实验验证，我们证实PRSA在现实场景下确实构成了重大威胁。目前，我们已将这些研究成果通报给相关提示服务提供商，并正积极与其协作，共同寻求实施保护措施以捍卫提示的版权权益。

> Prompt, recognized as crucial intellectual property, enables large language models (LLMs) to perform specific tasks without the need of fine-tuning, underscoring their escalating importance. With the rise of prompt-based services, such as prompt marketplaces and LLM applications, providers often display prompts' capabilities through input-output examples to attract users. However, this paradigm raises a pivotal security concern: does the exposure of input-output pairs pose the risk of potential prompt leakage, infringing on the intellectual property rights of the developers? To our knowledge, this problem still has not been comprehensively explored yet. To remedy this gap, in this paper, we perform the first in depth exploration and propose a novel attack framework for reverse-stealing prompts against commercial LLMs, namely PRSA. The main idea of PRSA is that by analyzing the critical features of the input-output pairs, we mimic and gradually infer (steal) the target prompts. In detail, PRSA mainly consists of two key phases: prompt mutation and prompt pruning. In the mutation phase, we propose a prompt attention algorithm based on differential feedback to capture these critical features for effectively inferring the target prompts. In the prompt pruning phase, we identify and mask the words dependent on specific inputs, enabling the prompts to accommodate diverse inputs for generalization. Through extensive evaluation, we verify that PRSA poses a severe threat in real world scenarios. We have reported these findings to prompt service providers and actively collaborate with them to take protective measures for prompt copyright.

[Arxiv](https://arxiv.org/abs/2402.19200)