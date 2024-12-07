# 大型语言模型中的思维链：包括解码、投影与激活

发布时间：2024年12月05日

`LLM理论` `语言模型`

> Chain-of-Thought in Large Language Models: Decoding, Projection, and Activation

# 摘要

> Chain-of-Thought 提示极大地提升了大型语言模型的推理能力，众多研究都在探寻影响其性能的因素。然而，其内在机制仍未被充分理解。为了进一步揭开其运作原理的神秘面纱，本研究考察了三个关键方面：解码、投影和激活，旨在阐明采用 Chain-of-Thought 时模型内部的变化。我们的发现表明，LLM 能有效地模仿示例格式，并将其与对问题的理解相融合，在生成过程中令牌的对数几率会有波动，但最终会产生更集中的对数几率分布，而且在最后几层会激活更广泛的神经元，这意味着与标准提示相比，能进行更广泛的知识检索。当论文被接收时，我们的代码和数据将会公开可用。

> Chain-of-Thought prompting has significantly enhanced the reasoning capabilities of large language models, with numerous studies exploring factors influencing its performance. However, the underlying mechanisms remain poorly understood. To further demystify the operational principles, this work examines three key aspects: decoding, projection, and activation, aiming to elucidate the changes that occur within models when employing Chainof-Thought. Our findings reveal that LLMs effectively imitate exemplar formats while integrating them with their understanding of the question, exhibiting fluctuations in token logits during generation but ultimately producing a more concentrated logits distribution, and activating a broader set of neurons in the final layers, indicating more extensive knowledge retrieval compared to standard prompts. Our code and data will be publicly avialable when the paper is accepted.

[Arxiv](https://arxiv.org/abs/2412.03944)