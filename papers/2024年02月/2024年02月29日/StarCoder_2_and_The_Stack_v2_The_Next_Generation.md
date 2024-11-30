# StarCoder 2 与 The Stack v2：引领下一代创新潮流

发布时间：2024年02月29日

`Agent`

> StarCoder 2 and The Stack v2: The Next Generation

# 摘要

> BigCode项目致力于负责任地开发大型代码语言模型（Code LLMs），并携手Software Heritage（SWH）推出StarCoder2。基于SWH丰富的源代码档案，我们打造了一个名为The Stack v2的强大基础。在囊括619种编程语言的SWH仓库基础上，我们精选了GitHub PR、Kaggle笔记本和代码文档等优质数据源，构建出比首版StarCoder大四倍的训练集。我们在此基础上训练了拥有3B、7B和15B参数的StarCoder2系列模型，它们在3.3万亿至4.3万亿个令牌上进行训练，并在广泛的Code LLM基准测试中接受了深度评测。其中，小巧的StarCoder2-3B在多数基准测试中击败了同级规模的其他Code LLM，并超越了StarCoderBase-15B。而大体量的StarCoder2-15B则在同等尺寸模型中一骑绝尘，甚至能与体积超过自身两倍的CodeLlama-34B平分秋色，甚至在某些数学、代码推理及低资源语言任务上胜出。尽管DeepSeekCoder-33B在高资源语言的代码补全任务上表现出色，但在数学和代码推理基准测试以及若干低资源语言场景下，StarCoder2-15B的表现更为优秀。我们已将模型权重以OpenRAIL许可开放，并通过公开源代码数据的SoftWare Heritage持久标识符（SWHIDs），保证了训练数据的完全透明。

> The BigCode project, an open-scientific collaboration focused on the responsible development of Large Language Models for Code (Code LLMs), introduces StarCoder2. In partnership with Software Heritage (SWH), we build The Stack v2 on top of the digital commons of their source code archive. Alongside the SWH repositories spanning 619 programming languages, we carefully select other high-quality data sources, such as GitHub pull requests, Kaggle notebooks, and code documentation. This results in a training set that is 4x larger than the first StarCoder dataset. We train StarCoder2 models with 3B, 7B, and 15B parameters on 3.3 to 4.3 trillion tokens and thoroughly evaluate them on a comprehensive set of Code LLM benchmarks. We find that our small model, StarCoder2-3B, outperforms other Code LLMs of similar size on most benchmarks, and also outperforms StarCoderBase-15B. Our large model, StarCoder2- 15B, significantly outperforms other models of comparable size. In addition, it matches or outperforms CodeLlama-34B, a model more than twice its size. Although DeepSeekCoder- 33B is the best-performing model at code completion for high-resource languages, we find that StarCoder2-15B outperforms it on math and code reasoning benchmarks, as well as several low-resource languages. We make the model weights available under an OpenRAIL license and ensure full transparency regarding the training data by releasing the SoftWare Heritage persistent IDentifiers (SWHIDs) of the source code data.

[Arxiv](https://arxiv.org/abs/2402.19173)