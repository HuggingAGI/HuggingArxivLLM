# 你的 LLM 在过度收费吗？分词、透明度与激励机制

发布时间：2025年05月27日

`LLM应用

摘要讨论了大型语言模型（LLM）云服务的定价机制，特别是基于token计费的问题，以及如何改进这一机制以防止欺诈。这属于LLM的实际应用和优化，因此归类为LLM应用。` `云计算` `经济学`

> Is Your LLM Overcharging You? Tokenization, Transparency, and Incentives

# 摘要

> 当前最先进的大型语言模型运行需要专用硬件和大量能源支持，因此提供模型访问的云服务变得非常流行。这些服务根据模型生成输出时所使用的token数量来定价，用户支付的费用与token数量挂钩，即每token收取固定费用。然而，这种定价机制为服务提供商创造了财务动机，促使他们策划并虚报模型生成输出所使用的token数量，而用户往往无法察觉甚至怀疑自己是否被多收费用。尽管如此，如果服务提供商被迫公开模型生成过程，虚报token数量而不引起怀疑将变得困难。作为一种概念验证，我们开发了一个高效的启发式算法，允许提供商在不引起怀疑的情况下显著多收费用，这凸显了用户在当前按token付费机制下的脆弱性。为了彻底消除策划的财务动机，我们提出了一种简单的激励兼容的token定价机制，用户支付的费用将与输出的字符数量挂钩，即每字符收取固定费用。为了验证我们的理论，我们使用来自《Llama》、《Gemma》和《Ministral》系列的多个大型语言模型，以及来自LMSYS Chatbot Arena平台的输入提示进行了实验。

> State-of-the-art large language models require specialized hardware and substantial energy to operate. As a consequence, cloud-based services that provide access to large language models have become very popular. In these services, the price users pay for an output provided by a model depends on the number of tokens the model uses to generate it -- they pay a fixed price per token. In this work, we show that this pricing mechanism creates a financial incentive for providers to strategize and misreport the (number of) tokens a model used to generate an output, and users cannot prove, or even know, whether a provider is overcharging them. However, we also show that, if an unfaithful provider is obliged to be transparent about the generative process used by the model, misreporting optimally without raising suspicion is hard. Nevertheless, as a proof-of-concept, we introduce an efficient heuristic algorithm that allows providers to significantly overcharge users without raising suspicion, highlighting the vulnerability of users under the current pay-per-token pricing mechanism. Further, to completely eliminate the financial incentive to strategize, we introduce a simple incentive-compatible token pricing mechanism. Under this mechanism, the price users pay for an output provided by a model depends on the number of characters of the output -- they pay a fixed price per character. Along the way, to illustrate and complement our theoretical results, we conduct experiments with several large language models from the $\texttt{Llama}$, $\texttt{Gemma}$ and $\texttt{Ministral}$ families, and input prompts from the LMSYS Chatbot Arena platform.

[Arxiv](https://arxiv.org/abs/2505.21627)