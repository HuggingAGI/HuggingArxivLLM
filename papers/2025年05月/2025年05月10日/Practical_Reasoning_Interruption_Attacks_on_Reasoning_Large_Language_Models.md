# 实用推理攻击在推理大模型中的研究

发布时间：2025年05月10日

`LLM应用` `网络安全`

> Practical Reasoning Interruption Attacks on Reasoning Large Language Models

# 摘要

> 推理型大型语言模型（RLLMs）在多种任务中表现出色，但同时也暴露了大量安全漏洞。这些漏洞大多集中在生成不安全内容方面。然而，近期研究发现DeepSeek-R1存在一种独特的“思考停止”漏洞：在对抗性提示下，模型的推理过程在系统层面终止，并生成一个空的最终答案。基于这一漏洞，研究人员开发了一种新型提示注入攻击，称为推理中断攻击，并初步分析了其根本原因。通过大量实验，我们验证了之前的分析，根据三项实验发现纠正关键错误，并对漏洞的根本原因提供了更严谨的解释。此外，现有攻击通常需要超过2,000个令牌，带来显著开销，降低了实用性且容易被检测。为克服这些限制，我们提出了首个实用的推理中断攻击。它仅需109个令牌，通过利用新发现的“推理令牌溢出”（RTO）效应，覆盖模型的最终答案，迫使其返回无效响应。实验结果表明，我们的攻击非常有效。此外，我们发现触发RTO的方法在官方DeepSeek-R1版本与常见非官方部署之间存在差异。作为RTO的扩展应用，我们还构建了一种新型越狱攻击，使推理令牌中的不安全内容能够传递到最终答案，从而暴露给用户。我们的研究对提升RLLMs的安全性具有重要意义。


> Reasoning large language models (RLLMs) have demonstrated outstanding performance across a variety of tasks, yet they also expose numerous security vulnerabilities. Most of these vulnerabilities have centered on the generation of unsafe content. However, recent work has identified a distinct "thinking-stopped" vulnerability in DeepSeek-R1: under adversarial prompts, the model's reasoning process ceases at the system level and produces an empty final answer. Building upon this vulnerability, researchers developed a novel prompt injection attack, termed reasoning interruption attack, and also offered an initial analysis of its root cause. Through extensive experiments, we verify the previous analyses, correct key errors based on three experimental findings, and present a more rigorous explanation of the fundamental causes driving the vulnerability. Moreover, existing attacks typically require over 2,000 tokens, impose significant overhead, reduce practicality, and are easily detected. To overcome these limitations, we propose the first practical reasoning interruption attack. It succeeds with just 109 tokens by exploiting our newly uncovered "reasoning token overflow" (RTO) effect to overwrite the model's final answer, forcing it to return an invalid response. Experimental results demonstrate that our proposed attack is highly effective. Furthermore, we discover that the method for triggering RTO differs between the official DeepSeek-R1 release and common unofficial deployments. As a broadened application of RTO, we also construct a novel jailbreak attack that enables the transfer of unsafe content within the reasoning tokens into final answer, thereby exposing it to the user. Our work carries significant implications for enhancing the security of RLLMs.

[Arxiv](https://arxiv.org/abs/2505.06643)