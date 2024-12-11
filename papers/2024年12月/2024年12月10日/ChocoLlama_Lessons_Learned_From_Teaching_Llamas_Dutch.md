# ChocoLlama：教授羊驼荷兰语的经验教训

发布时间：2024年12月10日

`LLM应用` `荷兰语语言模型`

> ChocoLlama: Lessons Learned From Teaching Llamas Dutch

# 摘要

> 尽管大型语言模型（LLMs）在自然语言理解和生成方面表现出色，然而由于训练数据的偏差，它们在资源较少的非英语语言（如荷兰语）中的表现常常不尽人意。在本研究中，我们探索了将以英语为主的 LLMs（Llama-2 和 Llama-3）适配到荷兰语的策略。荷兰语虽有 3000 万人使用，但在 LLM 开发中常被忽视。我们从多方收集了 104GB 的荷兰语文本（320 亿个标记），先是运用低秩自适应（LoRA）进行持续预训练，再结合前人工作提供的荷兰语后训练策略。对于 Llama-2，我们考虑了（i）使用原模型的标记器，（ii）训练新的、荷兰语专用的标记器并结合嵌入重新初始化。我们在标准基准和新的荷兰语基准 ChocoLlama-Bench 上对适配后的模型 ChocoLlama-2 进行了评估。结果显示，LoRA 能有效用于语言适配，通过精心的权重重新初始化来修改标记器能提升性能。值得一提的是，Llama-3 在项目进行期间发布，经评估，其荷兰语能力优于我们适配的荷兰语版 Llama-2。于是，我们用其原始标记器将相同的适配技术应用于 Llama-3。虽然我们的适配方法提升了 Llama-2 的荷兰语能力，但应用于 Llama-3 时收效甚微。这表明对于不断改进的多语言基础模型，语言适配技术或许更应侧重于特定语言的后训练，而非持续预训练。我们期望本研究有助于更深入地理解将 LLMs 适配到资源较少的语言，尤其是荷兰语 LLMs 的开发。

> While Large Language Models (LLMs) have shown remarkable capabilities in natural language understanding and generation, their performance often lags in lower-resource, non-English languages due to biases in the training data. In this work, we explore strategies for adapting the primarily English LLMs (Llama-2 and Llama-3) to Dutch, a language spoken by 30 million people worldwide yet often underrepresented in LLM development. We collect 104GB of Dutch text ($32$B tokens) from various sources to first apply continued pretraining using low-rank adaptation (LoRA), complemented with Dutch posttraining strategies provided by prior work. For Llama-2, we consider using (i) the tokenizer of the original model, and (ii) training a new, Dutch-specific tokenizer combined with embedding reinitialization. We evaluate our adapted models, ChocoLlama-2, both on standard benchmarks and a novel Dutch benchmark, ChocoLlama-Bench. Our results demonstrate that LoRA can effectively scale for language adaptation, and that tokenizer modification with careful weight reinitialization can improve performance. Notably, Llama-3 was released during the course of this project and, upon evaluation, demonstrated superior Dutch capabilities compared to our Dutch-adapted versions of Llama-2. We hence apply the same adaptation technique to Llama-3, using its original tokenizer. While our adaptation methods enhanced Llama-2's Dutch capabilities, we found limited gains when applying the same techniques to Llama-3. This suggests that for ever improving, multilingual foundation models, language adaptation techniques may benefit more from focusing on language-specific posttraining rather than on continued pretraining. We hope this work contributes to the broader understanding of adapting LLMs to lower-resource languages, and to the development of Dutch LLMs in particular.

[Arxiv](https://arxiv.org/abs/2412.07633)