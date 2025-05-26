# 思考时并非所有token都是你需要的

发布时间：2025年05月23日

`LLM应用`

> Not All Tokens Are What You Need In Thinking

# 摘要

> 现代推理模型，如 OpenAI 的 o1 和 DeepSeek-R1，虽然在解决问题方面表现出色，但存在推理延迟高、计算资源消耗大以及过度思考等问题，表现为生成冗长且充满冗余标记的思考链（CoT），这些冗余标记对最终答案贡献甚微。为解决这些问题，我们提出了条件令牌选择（CTS），这是一种具有灵活压缩比率的令牌级压缩框架，专注于识别并保留 CoT 中最关键的标记。通过条件重要性评分，CTS 评估每个令牌对正确答案的贡献，随后在压缩后的 CoT 上进行模型训练。大量实验表明，CTS 能够有效压缩长 CoT，同时保持强大的推理性能。值得注意的是，在 GPQA 基准测试中，使用 CTS 训练的 Qwen2.5-14B-Instruct 在推理令牌减少 13.2% 的情况下，准确率提高了 9.1%。进一步减少 42% 的训练令牌仅导致准确率下降 5%，同时推理令牌减少了 75.8%，这凸显了现有 CoT 中冗余的普遍性。

> Modern reasoning models, such as OpenAI's o1 and DeepSeek-R1, exhibit impressive problem-solving capabilities but suffer from critical inefficiencies: high inference latency, excessive computational resource consumption, and a tendency toward overthinking -- generating verbose chains of thought (CoT) laden with redundant tokens that contribute minimally to the final answer. To address these issues, we propose Conditional Token Selection (CTS), a token-level compression framework with a flexible and variable compression ratio that identifies and preserves only the most essential tokens in CoT. CTS evaluates each token's contribution to deriving correct answers using conditional importance scoring, then trains models on compressed CoT. Extensive experiments demonstrate that CTS effectively compresses long CoT while maintaining strong reasoning performance. Notably, on the GPQA benchmark, Qwen2.5-14B-Instruct trained with CTS achieves a 9.1% accuracy improvement with 13.2% fewer reasoning tokens (13% training token reduction). Further reducing training tokens by 42% incurs only a marginal 5% accuracy drop while yielding a 75.8% reduction in reasoning tokens, highlighting the prevalence of redundancy in existing CoT.

[Arxiv](https://arxiv.org/abs/2505.17827)