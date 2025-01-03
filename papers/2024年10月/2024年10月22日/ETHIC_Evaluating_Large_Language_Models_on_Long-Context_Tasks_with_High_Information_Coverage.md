# ETHIC: 评估LLM在长上下文高信息覆盖任务中的表现

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要关注的是大型语言模型（LLM）在处理长上下文时的能力评估，提出了一个新的评估指标（信息覆盖率，IC）和一个新的基准（ETHIC）。这些工作属于对LLM的理论研究和性能评估，旨在深入理解LLM在处理长上下文时的表现和局限性。因此，这篇论文应归类为LLM理论。` `基准测试`

> ETHIC: Evaluating Large Language Models on Long-Context Tasks with High Information Coverage

# 摘要

> # 摘要
近期，能够处理超长文本的大型语言模型（LLM）取得了显著进展，这促使我们急需一个专门的评估基准来测试它们的长上下文处理能力。然而，现有的评估方法，如“大海捞针”测试，并不能有效验证模型是否充分利用了上下文信息，这让人对当前评估技术的可靠性产生了疑问。为了深入探究现有基准的有效性，我们提出了一个新指标——信息覆盖率（IC），用于量化回答查询所需的输入上下文比例。研究发现，现有基准的IC值普遍偏低，尽管输入上下文可能非常庞大，但实际可用的上下文却往往有限。为此，我们推出了ETHIC，这是一个旨在全面评估LLMs利用整个上下文能力的新基准。ETHIC包含2,648个测试实例，覆盖了书籍、辩论、医学和法律四个领域的长上下文任务，这些任务的IC分数较高。评估结果显示，当代LLMs在处理长上下文时性能显著下降，这突显了一个关键挑战。ETHIC基准可在https://github.com/dmis-lab/ETHIC获取。

> Recent advancements in large language models (LLM) capable of processing extremely long texts highlight the need for a dedicated evaluation benchmark to assess their long-context capabilities. However, existing methods, like the needle-in-a-haystack test, do not effectively assess whether these models fully utilize contextual information, raising concerns about the reliability of current evaluation techniques. To thoroughly examine the effectiveness of existing benchmarks, we introduce a new metric called information coverage (IC), which quantifies the proportion of the input context necessary for answering queries. Our findings indicate that current benchmarks exhibit low IC; although the input context may be extensive, the actual usable context is often limited. To address this, we present ETHIC, a novel benchmark designed to assess LLMs' ability to leverage the entire context. Our benchmark comprises 2,648 test instances spanning four long-context tasks with high IC scores in the domains of books, debates, medicine, and law. Our evaluations reveal significant performance drops in contemporary LLMs, highlighting a critical challenge in managing long contexts. Our benchmark is available at https://github.com/dmis-lab/ETHIC.

[Arxiv](https://arxiv.org/abs/2410.16848)