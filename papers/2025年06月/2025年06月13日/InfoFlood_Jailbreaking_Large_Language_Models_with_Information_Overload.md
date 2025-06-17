# InfoFlood: 通过信息过载实现对大型语言模型的越狱

发布时间：2025年06月13日

`LLM应用

摘要讨论了大型语言模型（LLMs）在越狱攻击中的漏洞，特别是通过信息过载技术绕过安全机制。研究提出了一种新的攻击方法InfoFlood，并在多个模型上进行了验证，属于LLM的应用层面研究。` `AI安全` `对抗攻击`

> InfoFlood: Jailbreaking Large Language Models with Information Overload

# 摘要

> 大型语言模型（LLMs）在多个领域展现非凡能力，但其生成有害内容的潜力引发社会和监管担忧，尤其在面对“越狱”攻击时。现有越狱方法通常通过附加前缀或后缀绕过模型安全机制。

我们发现一种新漏洞：过度语言复杂性可扰乱模型安全机制，无需附加内容，使攻击者直接诱发出有害输出。我们称此现象为“信息过载”。

为利用此漏洞，我们提出InfoFlood，一种越狱攻击方法，将恶意查询转化为复杂且信息过载的查询以绕过安全机制。InfoFlood特点包括：(1) 使用语言变换技术重新表述恶意查询，(2) 识别失败原因，(3) 优化提示结构同时保持恶意意图。

我们在GPT-4o、GPT-3.5-turbo、Gemini 2.0和LLaMA 3.1上验证InfoFlood效果，其越狱成功率是基线攻击的三倍。常见防御措施如OpenAI的Moderation API、Perspective API和SmoothLLM均无法有效缓解此类攻击，凸显传统AI安全护栏在信息过载攻击下的弱点。


> Large Language Models (LLMs) have demonstrated remarkable capabilities across various domains. However, their potential to generate harmful responses has raised significant societal and regulatory concerns, especially when manipulated by adversarial techniques known as "jailbreak" attacks. Existing jailbreak methods typically involve appending carefully crafted prefixes or suffixes to malicious prompts in order to bypass the built-in safety mechanisms of these models.
  In this work, we identify a new vulnerability in which excessive linguistic complexity can disrupt built-in safety mechanisms-without the need for any added prefixes or suffixes-allowing attackers to elicit harmful outputs directly. We refer to this phenomenon as Information Overload.
  To automatically exploit this vulnerability, we propose InfoFlood, a jailbreak attack that transforms malicious queries into complex, information-overloaded queries capable of bypassing built-in safety mechanisms. Specifically, InfoFlood: (1) uses linguistic transformations to rephrase malicious queries, (2) identifies the root cause of failure when an attempt is unsuccessful, and (3) refines the prompt's linguistic structure to address the failure while preserving its malicious intent.
  We empirically validate the effectiveness of InfoFlood on four widely used LLMs-GPT-4o, GPT-3.5-turbo, Gemini 2.0, and LLaMA 3.1-by measuring their jailbreak success rates. InfoFlood consistently outperforms baseline attacks, achieving up to 3 times higher success rates across multiple jailbreak benchmarks. Furthermore, we demonstrate that commonly adopted post-processing defenses, including OpenAI's Moderation API, Perspective API, and SmoothLLM, fail to mitigate these attacks. This highlights a critical weakness in traditional AI safety guardrails when confronted with information overload-based jailbreaks.

[Arxiv](https://arxiv.org/abs/2506.12274)