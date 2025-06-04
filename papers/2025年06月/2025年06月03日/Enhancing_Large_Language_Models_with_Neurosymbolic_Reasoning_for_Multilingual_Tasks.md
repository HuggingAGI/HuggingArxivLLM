# 提升大型语言模型的多语言能力，借助神经符号推理

发布时间：2025年06月03日

`LLM应用` `人工智能` `多语言处理`

> Enhancing Large Language Models with Neurosymbolic Reasoning for Multilingual Tasks

# 摘要

> 大型语言模型 (LLMs) 在处理长上下文场景下的多目标推理时常常面临挑战，因为相关信息往往分散在大量文档中。为解决这一难题，我们提出了神经符号增强推理 (NSAR)，它巧妙地结合了神经推理和符号推理的优势。NSAR 通过从文本中显式提取符号事实，并生成可执行的 Python 代码来处理复杂的推理步骤。通过在七种语言和多种上下文长度下进行的大量实验，我们证明了 NSAR 在准确识别和综合多条信息方面，显著超越了传统的 RAG 基线方法和先进的提示策略。我们的研究结果表明，在多语言环境下，将显式符号操作与神经推理相结合，能够实现稳健、可解释且可扩展的推理能力。

> Large language models (LLMs) often struggle to perform multi-target reasoning in long-context scenarios where relevant information is scattered across extensive documents. To address this challenge, we introduce NeuroSymbolic Augmented Reasoning (NSAR), which combines the benefits of neural and symbolic reasoning during inference. NSAR explicitly extracts symbolic facts from text and generates executable Python code to handle complex reasoning steps. Through extensive experiments across seven languages and diverse context lengths, we demonstrate that NSAR significantly outperforms both a vanilla RAG baseline and advanced prompting strategies in accurately identifying and synthesizing multiple pieces of information. Our results highlight the effectiveness of combining explicit symbolic operations with neural inference for robust, interpretable, and scalable reasoning in multilingual settings.

[Arxiv](https://arxiv.org/abs/2506.02483)