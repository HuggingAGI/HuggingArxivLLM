# 指令边界：量化不同覆盖度下LLM推理的偏差

发布时间：2025年09月24日

`LLM应用` `基础理论`

> Instruction Boundary: Quantifying Biases in LLM Reasoning under Various Coverage

# 摘要

> 大型语言模型（LLM）推理一直被视作跨领域解决问题的利器，为非专家提供宝贵建议。然而，其局限性——尤其是源于提示词设计的局限——尚未得到深入探究。用户可能会提供有偏见或不完整的提示词（往往是无心之失），这会误导LLMs，进而削弱其可靠性，带来风险。我们将这种脆弱性称为“指令边界”。为探究这一现象，我们将其归纳为八个具体维度，并引入BiasDetector框架，用于衡量三种指令类型（完整型、冗余型和不足型）引发的偏见。我们对多款主流LLMs进行了评估，结果显示，尽管LLMs的标题准确率亮眼，但受提示词覆盖范围的直接影响，许多下游任务中仍存在显著偏见。实证研究表明，LLM推理的可靠性仍有很大提升潜力。我们还分析了这些偏见的实际影响，并提出了缓解策略。研究结果强调，开发人员需着手解决偏见问题，用户则应谨慎设计提示词选项。

> Large-language-model (LLM) reasoning has long been regarded as a powerful tool for problem solving across domains, providing non-experts with valuable advice. However, their limitations - especially those stemming from prompt design - remain underexplored. Because users may supply biased or incomplete prompts - often unintentionally - LLMs can be misled, undermining reliability and creating risks. We refer to this vulnerability as the Instruction Boundary. To investigate the phenomenon, we distill it into eight concrete facets and introduce BiasDetector, a framework that measures biases arising from three instruction types: complete, redundant, and insufficient. We evaluate several mainstream LLMs and find that, despite high headline accuracy, substantial biases persist in many downstream tasks as a direct consequence of prompt coverage. Our empirical study confirms that LLM reasoning reliability can still be significantly improved. We analyze the practical impact of these biases and outline mitigation strategies. Our findings underscore the need for developers to tackle biases and for users to craft options carefully.

[Arxiv](https://arxiv.org/abs/2509.20278)