# # LLMs Think, But Not In Your Flow: Reasoning-Level Personalization for Black-Box Large Language Models
大型语言模型在思考，但不在你的流程中——在推理层面实现对黑箱大型语言模型的个性化定制。

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了黑箱大型语言模型（LLMs）在实际应用中的个性化问题，并提出了一种新的推理级别的个性化方法（RPM框架）。它关注如何在不修改模型参数的情况下，通过建模用户的推理过程来实现更个性化的输出。这属于对大型语言模型的实际应用和改进，因此归类为LLM应用。` `个性化`

> LLMs Think, But Not In Your Flow: Reasoning-Level Personalization for Black-Box Large Language Models

# 摘要

> 大型语言模型（LLMs）在各类自然语言任务中表现卓越，如今已广泛应用于实际场景。其中，黑箱LLMs尤为突出，因其通过API提供服务，无需访问模型内部，凭借其良好的扩展性和便捷的部署特性，占据了主导地位。尽管这些模型功能强大，但它们通常生成通用回应，忽视了用户的个人偏好和推理风格。这激发了对黑箱LLM个性化技术的兴趣，旨在根据用户的特定背景调整模型输出，而无需修改模型参数。然而，现有的方法主要集中在回应级别的个性化上，试图匹配最终输出，却未建模个人思维过程。为克服这一局限，我们提出RPM框架，旨在实现推理级别的个性化，使模型推理过程与用户的个性化逻辑相匹配。RPM首先通过提取和分组用户历史中的影响回应特征，构建统计意义上的用户特定因素。然后，构建个性化推理路径，反映这些因素在具体情境中的应用方式。在推理阶段，RPM通过特征层面的相似性检索推理一致的实例，并基于结构化因素和检索到的推理路径进行推理，使模型遵循用户特定的推理轨迹。这种推理级别的个性化，通过结构化信息将模型输出植根于用户特定逻辑，从而提升预测准确性和可解释性。跨多样任务的广泛实验表明，RPM在推理级别个性化方法上表现优于回应级别个性化方法，证实了在黑箱LLM中推理级别个性化的效果。

> Large language models (LLMs) have recently achieved impressive performance across a wide range of natural language tasks and are now widely used in real-world applications. Among them, black-box LLMs--served via APIs without access to model internals--are especially dominant due to their scalability and ease of deployment. Despite their strong capabilities, these models typically produce generalized responses that overlook personal preferences and reasoning styles. This has led to growing interest in black-box LLM personalization, which aims to tailor model outputs to user-specific context without modifying model parameters. However, existing approaches primarily focus on response-level personalization, attempting to match final outputs without modeling personal thought process. To address this limitation, we propose RPM, a framework for reasoning-level personalization that aligns the model's reasoning process with a user's personalized logic. RPM first constructs statistical user-specific factors by extracting and grouping response-influential features from user history. It then builds personalized reasoning paths that reflect how these factors are used in context. In the inference stage, RPM retrieves reasoning-aligned examples for new queries via feature-level similarity and performs inference conditioned on the structured factors and retrieved reasoning paths, enabling the model to follow user-specific reasoning trajectories. This reasoning-level personalization enhances both predictive accuracy and interpretability by grounding model outputs in user-specific logic through structured information. Extensive experiments across diverse tasks show that RPM consistently outperforms response-level personalization methods, demonstrating the effectiveness of reasoning-level personalization in black-box LLMs.

[Arxiv](https://arxiv.org/abs/2505.21082)