# 运行在CIRCLE中？探索LLM代码解释器安全的简单基准测试。

发布时间：2025年07月25日

`LLM应用` `网络安全` `人工智能`

> Running in CIRCLE? A Simple Benchmark for LLM Code Interpreter Security

# 摘要

> 随着大型语言模型（LLMs）逐步集成原生代码解释器，其应用范围得到了显著扩展，同时具备了强大的实时执行能力。然而，这种集成方式也带来了与传统提示漏洞截然不同的系统级网络安全威胁。为系统性评估这些解释器特有的风险，我们提出了CIRCLE（用于LLM漏洞的代码解释器弹性检查），这是一个包含1,260个提示的基准测试，旨在检测针对CPU、内存和磁盘资源耗尽的潜在风险。每个风险类别下，我们设计了明确恶意的（“直接”）和看似无害的（“间接”）两种提示变体。

我们的自动化评估框架不仅能够判断LLMs是否拒绝或生成危险代码，还会在解释器环境中实际执行生成的代码，以全面评估代码的正确性、LLM为确保安全所做的简化处理，或是否存在执行超时等问题。通过对OpenAI和Google的7个商用模型进行评估，我们发现了显著且不一致的安全漏洞。例如，评估结果显示，即使在同一供应商内部也存在巨大差异——OpenAI的o4-mini正确拒绝危险请求的比例为7.1%，远高于GPT-4.1的0.5%。特别值得注意的是，间接的、社会工程学设计的提示对模型防御能力的削弱作用尤为明显。

这些发现凸显了建立专门针对代码解释器的网络安全基准、开发相应的缓解工具（如护栏）以及制定明确的行业标准的迫切需求，以确保LLM解释器集成的安全性和负责任的部署。为了推动进一步研究，我们已公开发布了基准数据集和评估代码。

> As large language models (LLMs) increasingly integrate native code interpreters, they enable powerful real-time execution capabilities, substantially expanding their utility. However, such integrations introduce potential system-level cybersecurity threats, fundamentally different from prompt-based vulnerabilities. To systematically evaluate these interpreter-specific risks, we propose CIRCLE (Code-Interpreter Resilience Check for LLM Exploits), a simple benchmark comprising 1,260 prompts targeting CPU, memory, and disk resource exhaustion. Each risk category includes explicitly malicious ("direct") and plausibly benign ("indirect") prompt variants. Our automated evaluation framework assesses not only whether LLMs refuse or generates risky code, but also executes the generated code within the interpreter environment to evaluate code correctness, simplifications made by the LLM to make the code safe, or execution timeouts. Evaluating 7 commercially available models from OpenAI and Google, we uncover significant and inconsistent vulnerabilities. For instance, evaluations show substantial disparities even within providers - OpenAI's o4-mini correctly refuses risky requests at 7.1%, notably higher rates compared to GPT-4.1 at 0.5%. Results particularly underscore that indirect, socially-engineered prompts substantially weaken model defenses. This highlights an urgent need for interpreter-specific cybersecurity benchmarks, dedicated mitigation tools (e.g., guardrails), and clear industry standards to guide safe and responsible deployment of LLM interpreter integrations. The benchmark dataset and evaluation code are publicly released to foster further research.

[Arxiv](https://arxiv.org/abs/2507.19399)