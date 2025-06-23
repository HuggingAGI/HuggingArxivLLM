# 安全提醒：通过软提示重新激活视觉-语言模型的安全意识

发布时间：2025年06月15日

`LLM应用` `软件开发` `人工智能`

> The Safety Reminder: A Soft Prompt to Reactivate Delayed Safety Awareness in Vision-Language Models

# 摘要

> 随着视觉语言模型（VLMs）在代码生成和聊天机器人辅助等实际应用中展现出越来越强大的能力，确保其安全性变得至关重要。与传统的大型语言模型（LLMs）不同，VLMs由于其多模态的特性，面临着独特的漏洞，使得攻击者可以修改视觉或文本输入，绕过安全护栏，触发有害内容的生成。

通过对VLM在攻击环境下的行为进行系统性分析，我们发现了一种称为“延迟安全意识”的新现象。具体来说，尽管安全对齐的VLMs最初可能被攻破以生成有害内容，但最终它们会意识到相关风险并尝试自我纠正。这一模式表明，VLMs保留了其内在的安全意识，但其激活存在时间上的延迟。

基于这一见解，我们假设可以通过精心设计的提示词来主动重新激活VLMs的安全意识。为此，我们引入了“安全提醒”，这是一种软提示调优方法，通过优化可学习的提示词令牌，并在文本生成过程中定期注入这些令牌，从而增强安全意识，有效防止有害内容的生成。此外，我们的安全提醒仅在检测到有害内容时激活，不影响正常对话，同时保留模型在良性任务上的性能。

通过在三个 established safety benchmarks 和一个对抗攻击上的全面评估，我们证明了我们的方法显著降低了攻击成功率，同时保持了模型的实用性，为在实际应用中部署更安全的VLMs提供了一种实用的解决方案。

> As Vision-Language Models (VLMs) demonstrate increasing capabilities across real-world applications such as code generation and chatbot assistance, ensuring their safety has become paramount. Unlike traditional Large Language Models (LLMs), VLMs face unique vulnerabilities due to their multimodal nature, allowing adversaries to modify visual or textual inputs to bypass safety guardrails and trigger the generation of harmful content. Through systematic analysis of VLM behavior under attack, we identify a novel phenomenon termed ``delayed safety awareness''. Specifically, we observe that safety-aligned VLMs may initially be compromised to produce harmful content, but eventually recognize the associated risks and attempt to self-correct. This pattern suggests that VLMs retain their underlying safety awareness but experience a temporal delay in their activation. Building on this insight, we hypothesize that VLMs' safety awareness can be proactively reactivated through carefully designed prompts. To this end, we introduce ``The Safety Reminder'', a soft prompt tuning approach that optimizes learnable prompt tokens, which are periodically injected during the text generation process to enhance safety awareness, effectively preventing harmful content generation. Additionally, our safety reminder only activates when harmful content is detected, leaving normal conversations unaffected and preserving the model's performance on benign tasks. Through comprehensive evaluation across three established safety benchmarks and one adversarial attacks, we demonstrate that our approach significantly reduces attack success rates while maintaining model utility, offering a practical solution for deploying safer VLMs in real-world applications.

[Arxiv](https://arxiv.org/abs/2506.15734)