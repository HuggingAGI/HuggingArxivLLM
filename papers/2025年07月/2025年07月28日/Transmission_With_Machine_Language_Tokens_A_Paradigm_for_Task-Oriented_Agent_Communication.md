# 基于机器语言令牌的传输：任务导向型智能体通信的新范式

发布时间：2025年07月28日

`Agent` `智能体通信系统` `面向任务的通信系统`

> Transmission With Machine Language Tokens: A Paradigm for Task-Oriented Agent Communication

# 摘要

> 大型基础模型的迅猛发展正在推动各行各业的范式转变。其中一大重要变革是，未来的生产过程中，智能体将取代传统机器或人类，成为主要参与者。这一转变要求一种全新的、专为智能体通信设计的AI原生通信系统。将大型语言模型（LLMs）的能力与面向任务的语义通信相结合，是一个有潜力的解决方案。然而，现有LLM的输出是人类语言，这对于智能体之间的通信而言，具有高度约束且不够理想。本文中，我们创新性地提出了一种面向任务的智能体通信系统。具体而言，我们利用原始LLM学习一种由令牌嵌入表示的专用机器语言。同时，我们训练一个多模态LLM来理解应用任务，并从多模态输入中提取关键的隐含信息，随后使用机器语言令牌对其进行表达。这种表示方法在空口传输中显著提高了效率。此外，为了降低传输开销，我们引入了一种联合令牌与信道编码（JTCC）方案，通过利用令牌序列的稀疏性对其进行压缩，同时增强其在信道噪声下的鲁棒性。大量实验表明，我们的方法在降低下游任务传输开销的同时，相较于现有最优方法（SOTA）提升了准确性。

> The rapid advancement in large foundation models is propelling the paradigm shifts across various industries. One significant change is that agents, instead of traditional machines or humans, will be the primary participants in the future production process, which consequently requires a novel AI-native communication system tailored for agent communications. Integrating the ability of large language models (LLMs) with task-oriented semantic communication is a potential approach. However, the output of existing LLM is human language, which is highly constrained and sub-optimal for agent-type communication. In this paper, we innovatively propose a task-oriented agent communication system. Specifically, we leverage the original LLM to learn a specialized machine language represented by token embeddings. Simultaneously, a multi-modal LLM is trained to comprehend the application task and to extract essential implicit information from multi-modal inputs, subsequently expressing it using machine language tokens. This representation is significantly more efficient for transmission over the air interface. Furthermore, to reduce transmission overhead, we introduce a joint token and channel coding (JTCC) scheme that compresses the token sequence by exploiting its sparsity while enhancing robustness against channel noise. Extensive experiments demonstrate that our approach reduces transmission overhead for downstream tasks while enhancing accuracy relative to the SOTA methods.

[Arxiv](https://arxiv.org/abs/2507.21454)