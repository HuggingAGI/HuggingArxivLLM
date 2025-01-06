# 多智能体对话在线学习：自适应LLM响应识别

发布时间：2025年01月03日

`Agent

理由：这篇论文主要讨论了通过多个本地代理（如智能手机）来加速在线LLM响应识别，并引入了一种创新的对话机制来征求用户偏好。这些内容涉及到多代理系统（Multi-Agent System）的设计和应用，因此将其分类为Agent。` `个性化推荐`

> Multi-Agent Conversational Online Learning for Adaptive LLM Response Identification

# 摘要

> 大型语言模型（LLMs）的强大生成能力激发了人们对自动生成多样化应用响应的浓厚兴趣。由于用户偏好的多变性和LLM响应的不确定性，设计高效的在线学习算法来识别最优LLM响应（即高质量且符合用户偏好的响应）显得尤为重要。现有在线算法大多采用集中式方法，未能充分利用显式用户偏好来实现更高效、个性化的LLM响应识别。本文提出的	extit{MACO}（underline{M}ulti-underline{A}gent underline{C}onversational underline{O}nline Learning for Adaptive LLM Response Identification）则不同：1）通过多个本地代理（如智能手机）加速在线LLM响应识别，同时提升数据隐私；2）引入了一种创新的对话机制，自适应地征求用户偏好（例如，偏好幽默而非严肃的响应语气），从而最小化偏好估计的不确定性。理论分析表明，\cadi\ 在累积遗憾方面接近最优，并通过摒弃传统计算密集型的“G-最优设计”，显著降低了通信成本和计算复杂度。基于开源LLM 	extit{Llama} 以及Google和OpenAI的两种嵌入模型的大量实验证明，\cadi\ 在在线LLM响应识别方面远超当前最优方法。

> The remarkable generative capability of large language models (LLMs) has sparked a growing interest in automatically generating responses for different applications. Given the dynamic nature of user preferences and the uncertainty of LLM response performance, it is crucial to design efficient online learning algorithms to identify optimal LLM responses (i.e., high-quality responses that also meet user preferences). Most existing online algorithms adopt a centralized approach and fail to leverage explicit user preferences for more efficient and personalized LLM response identification. In contrast, this paper introduces \textit{MACO} (underline{M}ulti-underline{A}gent underline{C}onversational underline{O}nline Learning for Adaptive LLM Response Identification): 1) The online LLM response identification process is accelerated by multiple local agents (such as smartphones), while enhancing data privacy; 2) A novel conversational mechanism is proposed to adaptively conduct conversations for soliciting user preferences (e.g., a preference for a humorous tone over a serious one in generated responses), so to minimize uncertainty in preference estimation. Our theoretical analysis demonstrates that \cadi\ is near-optimal regarding cumulative regret. Additionally, \cadi\ offers reduced communication costs and computational complexity by eliminating the traditional, computing-intensive ``G-optimal design" found in previous works. Extensive experiments with the open LLM \textit{Llama}, coupled with two different embedding models from Google and OpenAI for text vector representation, demonstrate that \cadi\ significantly outperforms the current state-of-the-art in online LLM response identification.

[Arxiv](https://arxiv.org/abs/2501.01849)