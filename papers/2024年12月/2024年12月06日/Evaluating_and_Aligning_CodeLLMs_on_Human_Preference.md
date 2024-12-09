# 对基于人类偏好的 CodeLLMs 进行评估和调整

发布时间：2024年12月06日

`LLM应用` `软件开发` `代码生成`

> Evaluating and Aligning CodeLLMs on Human Preference

# 摘要

> 代码大型语言模型（codeLLMs）在代码生成领域取得了重大进步。以往多数与代码相关的基准测试，涵盖了各类编程练习及相应的测试用例，常被用于评估代码LLMs的性能与能力。然而，当下的代码LLMs只注重合成正确的代码片段，却忽视了与人类偏好的契合，其中查询应从实际应用场景中抽取，模型生成的响应也应符合人类偏好。为了填补模型生成的响应与人类偏好之间的鸿沟，我们推出了严格人工策划的基准CodeArena，以模拟真实世界编码任务的复杂性和多样性，其中精心从用户查询中筛选出了397个高质量样本，涵盖40个类别和44种编程语言。此外，我们还通过从网站扩展指令构建了一个多样化的合成指令语料库SynCode-Instruct（近200亿个标记），以验证大规模合成指令微调的有效性，完全基于合成指令数据训练的Qwen2.5-SynCoder能够达到开源代码LLMs的顶尖性能。结果表明，基于执行的基准测试和CodeArena之间存在性能差异。我们针对40多个LLMs开展的CodeArena系统实验揭示了开放的SOTA代码LLMs（如Qwen2.5-Coder）与专有LLMs（如OpenAI o1）之间存在显著的性能差距，凸显了与人类偏好契合的重要性。ootnote{url{https://codearenaeval.github.io/ }}

> Code large language models (codeLLMs) have made significant strides in code generation. Most previous code-related benchmarks, which consist of various programming exercises along with the corresponding test cases, are used as a common measure to evaluate the performance and capabilities of code LLMs. However, the current code LLMs focus on synthesizing the correct code snippet, ignoring the alignment with human preferences, where the query should be sampled from the practical application scenarios and the model-generated responses should satisfy the human preference. To bridge the gap between the model-generated response and human preference, we present a rigorous human-curated benchmark CodeArena to emulate the complexity and diversity of real-world coding tasks, where 397 high-quality samples spanning 40 categories and 44 programming languages, carefully curated from user queries. Further, we propose a diverse synthetic instruction corpus SynCode-Instruct (nearly 20B tokens) by scaling instructions from the website to verify the effectiveness of the large-scale synthetic instruction fine-tuning, where Qwen2.5-SynCoder totally trained on synthetic instruction data can achieve top-tier performance of open-source code LLMs. The results find performance differences between execution-based benchmarks and CodeArena. Our systematic experiments of CodeArena on 40+ LLMs reveal a notable performance gap between open SOTA code LLMs (e.g. Qwen2.5-Coder) and proprietary LLMs (e.g., OpenAI o1), underscoring the importance of the human preference alignment.\footnote{url{https://codearenaeval.github.io/ }}

[Arxiv](https://arxiv.org/abs/2412.05210)