# GuardVal：大型语言模型的动态越狱评估，助力全面安全测试

发布时间：2025年07月10日

`LLM应用` `人工智能安全`

> GuardVal: Dynamic Large Language Model Jailbreak Evaluation for Comprehensive Safety Testing

# 摘要

> 越狱攻击揭示了大型语言模型（LLMs）的关键漏洞，这些攻击会导致模型生成有害或不道德的内容。由于LLMs的不断演进以及有效探测其漏洞所需的高度复杂性，评估这些威胁尤其具有挑战性。当前的基准测试和评估方法难以全面应对这些挑战，导致对LLMs漏洞的评估存在不足。本文综述了现有的越狱攻击评估实践，并识别出三种假设性的理想目标，以构建一个有效的越狱攻击评估协议。为应对这些挑战，我们引入了GuardVal，这是一种新的评估协议，能够根据防御方LLM的状态动态生成和优化越狱提示，从而更准确地评估防御方LLM在处理安全关键情况方面的能力。此外，我们提出了一种新的优化方法，能够在提示优化过程中防止停滞，确保生成越来越有效的越狱提示，从而揭示防御方LLM更深层次的弱点。我们将这一协议应用于从Mistral-7b到GPT-4的一系列模型，并涵盖10个安全领域。我们的研究发现揭示了这些模型之间不同的行为模式，提供了对其稳健性的全面视角。此外，我们的评估过程加深了对LLM行为的理解，提供了可指导未来研究并推动更安全模型开发的见解。

> Jailbreak attacks reveal critical vulnerabilities in Large Language Models (LLMs) by causing them to generate harmful or unethical content. Evaluating these threats is particularly challenging due to the evolving nature of LLMs and the sophistication required in effectively probing their vulnerabilities. Current benchmarks and evaluation methods struggle to fully address these challenges, leaving gaps in the assessment of LLM vulnerabilities. In this paper, we review existing jailbreak evaluation practices and identify three assumed desiderata for an effective jailbreak evaluation protocol. To address these challenges, we introduce GuardVal, a new evaluation protocol that dynamically generates and refines jailbreak prompts based on the defender LLM's state, providing a more accurate assessment of defender LLMs' capacity to handle safety-critical situations. Moreover, we propose a new optimization method that prevents stagnation during prompt refinement, ensuring the generation of increasingly effective jailbreak prompts that expose deeper weaknesses in the defender LLMs. We apply this protocol to a diverse set of models, from Mistral-7b to GPT-4, across 10 safety domains. Our findings highlight distinct behavioral patterns among the models, offering a comprehensive view of their robustness. Furthermore, our evaluation process deepens the understanding of LLM behavior, leading to insights that can inform future research and drive the development of more secure models.

[Arxiv](https://arxiv.org/abs/2507.07735)