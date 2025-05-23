# 在提示之间解读：刻板印象如何影响大型语言模型的隐性个性化能力

发布时间：2025年05月22日

`LLM理论

理由：这篇论文探讨了生成式大型语言模型（LLMs）在处理隐含用户信息时的行为，分析了模型的内部机制和如何通过技术手段干预以减少偏见。研究重点在于理解模型的工作原理及其潜在偏见，属于理论层面的探讨。` `人工智能` `人工智能伦理`

> Reading Between the Prompts: How Stereotypes Shape LLM's Implicit Personalization

# 摘要

> 生成式大型语言模型（LLMs）能够通过对话中的细微线索推断出用户的群体信息，这种现象被称为隐式个性化。先前的研究表明，即使没有明确提供人口统计信息，这种推断也可能导致少数群体用户获得质量较低的回复。在本研究中，我们通过使用受控合成对话，系统性地探讨了LLMs对刻板印象线索的反应。我们通过分析模型内部机制和对用户针对性问题的回答，深入研究了模型对潜在用户表示的推断。研究发现，LLMs确实会根据这些刻板印象信号推断人口属性，这种现象在许多群体中甚至在用户明确表示属于不同群体时仍然存在。最后，我们展示了通过使用训练好的线性探测器干预模型的内部表示，可以有效缓解这种由刻板印象驱动的隐式个性化。我们的研究结果强调了在LLMs表示用户身份时，提高透明度和控制力度的必要性。

> Generative Large Language Models (LLMs) infer user's demographic information from subtle cues in the conversation -- a phenomenon called implicit personalization. Prior work has shown that such inferences can lead to lower quality responses for users assumed to be from minority groups, even when no demographic information is explicitly provided. In this work, we systematically explore how LLMs respond to stereotypical cues using controlled synthetic conversations, by analyzing the models' latent user representations through both model internals and generated answers to targeted user questions. Our findings reveal that LLMs do infer demographic attributes based on these stereotypical signals, which for a number of groups even persists when the user explicitly identifies with a different demographic group. Finally, we show that this form of stereotype-driven implicit personalization can be effectively mitigated by intervening on the model's internal representations using a trained linear probe to steer them toward the explicitly stated identity. Our results highlight the need for greater transparency and control in how LLMs represent user identity.

[Arxiv](https://arxiv.org/abs/2505.16467)