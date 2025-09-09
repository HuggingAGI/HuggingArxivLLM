# 多模态提示注入攻击：现代大型语言模型的风险与防御

发布时间：2025年09月06日

`LLM应用` `基础理论`

> Multimodal Prompt Injection Attacks: Risks and Defenses for Modern LLMs

# 摘要

> 近年来，大型语言模型（LLMs）迅速普及，各行业愈发依赖其维持竞争优势。这些模型擅长解读用户指令并生成类人化响应，因此被广泛应用于咨询、信息检索等多个领域。然而，其大规模部署也带来了严重的安全风险，其中最突出的便是提示注入和越狱攻击。
  为系统评估LLM的漏洞（尤其是外部提示注入漏洞），我们对八个商业模型开展了一系列实验。测试时未对模型进行额外净化处理，仅依靠其内置防护机制。结果显示，这些模型存在可利用的安全弱点，亟需加强防护措施。我们重点研究了四类攻击：直接注入、间接（外部）注入、图像注入及提示泄露。对比分析发现，Claude 3的健壮性相对较强；但实证结果表明，仍需输入规范化等额外防御手段才能实现可靠防护。

> Large Language Models (LLMs) have seen rapid adoption in recent years, with industries increasingly relying on them to maintain a competitive advantage. These models excel at interpreting user instructions and generating human-like responses, leading to their integration across diverse domains, including consulting and information retrieval. However, their widespread deployment also introduces substantial security risks, most notably in the form of prompt injection and jailbreak attacks.
  To systematically evaluate LLM vulnerabilities -- particularly to external prompt injection -- we conducted a series of experiments on eight commercial models. Each model was tested without supplementary sanitization, relying solely on its built-in safeguards. The results exposed exploitable weaknesses and emphasized the need for stronger security measures. Four categories of attacks were examined: direct injection, indirect (external) injection, image-based injection, and prompt leakage. Comparative analysis indicated that Claude 3 demonstrated relatively greater robustness; nevertheless, empirical findings confirm that additional defenses, such as input normalization, remain necessary to achieve reliable protection.

[Arxiv](https://arxiv.org/abs/2509.05883)