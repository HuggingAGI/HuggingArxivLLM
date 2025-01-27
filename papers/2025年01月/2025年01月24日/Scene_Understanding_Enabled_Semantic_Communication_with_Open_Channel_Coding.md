# 基于场景理解的语义通信与开放信道编码

发布时间：2025年01月24日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来改进6G网络中的语义通信系统。论文提出的OpenSC系统结合了场景理解、LLMs和开放信道编码，旨在提升语义通信的适应性和效率。虽然论文涉及了语义通信和6G网络的技术背景，但其核心创新点在于利用LLMs来实现动态、自适应的编码策略，因此应归类为LLM应用。` `语义理解`

> Scene Understanding Enabled Semantic Communication with Open Channel Coding

# 摘要

> 随着通信系统从符号传输转向信息传递，6G网络开始重视语义通信。这种方法优先处理高层语义信息，提升鲁棒性并减少跨模态（如文本、语音和图像）的冗余。然而，传统语义通信存在静态编码策略、泛化能力差以及对特定任务知识库的依赖等问题，限制了其适应性。为此，我们提出了一种名为 	extbf{OpenSC} 的新系统，结合了场景理解、大型语言模型（LLMs）和开放信道编码。传统系统依赖固定的领域知识库，泛化能力有限。而我们的开放信道编码方法利用共享的公开知识，实现了灵活、自适应的编码。这种动态系统减少了对静态任务数据的依赖，增强了跨任务和环境的适应性。此外，我们使用场景图进行结构化语义编码，捕捉对象关系和上下文，从而提升视觉问答（VQA）等任务的表现。我们的方法选择性地编码关键语义元素，减少冗余并提高传输效率。实验结果表明，该系统在语义理解和效率方面均有显著提升，推动了6G网络中自适应、可泛化的语义通信的发展。

> As communication systems transition from symbol transmission to conveying meaningful information, sixth-generation (6G) networks emphasize semantic communication. This approach prioritizes high-level semantic information, improving robustness and reducing redundancy across modalities like text, speech, and images. However, traditional semantic communication faces limitations, including static coding strategies, poor generalization, and reliance on task-specific knowledge bases that hinder adaptability. To overcome these challenges, we propose a novel system combining scene understanding, Large Language Models (LLMs), and open channel coding, named \textbf{OpenSC}. Traditional systems rely on fixed domain-specific knowledge bases, limiting their ability to generalize. Our open channel coding approach leverages shared, publicly available knowledge, enabling flexible, adaptive encoding. This dynamic system reduces reliance on static task-specific data, enhancing adaptability across diverse tasks and environments. Additionally, we use scene graphs for structured semantic encoding, capturing object relationships and context to improve tasks like Visual Question Answering (VQA). Our approach selectively encodes key semantic elements, minimizing redundancy and improving transmission efficiency. Experimental results show significant improvements in both semantic understanding and efficiency, advancing the potential of adaptive, generalizable semantic communication in 6G networks.

[Arxiv](https://arxiv.org/abs/2501.14520)