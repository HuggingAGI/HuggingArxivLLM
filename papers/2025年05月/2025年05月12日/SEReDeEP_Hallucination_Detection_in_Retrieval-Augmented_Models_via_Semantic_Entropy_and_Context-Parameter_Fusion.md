# SEReDeEP：针对检索增强模型的语义熵与上下文参数融合幻觉检测方法

发布时间：2025年05月12日

`RAG` `问答系统`

> SEReDeEP: Hallucination Detection in Retrieval-Augmented Models via Semantic Entropy and Context-Parameter Fusion

# 摘要

> 检索增强生成（RAG）模型在整合外部信息与内部参数化知识时，常常会出现幻觉现象。研究表明，外部上下文信息与内部参数化知识的失衡是导致幻觉生成的主要原因。现有方法大多只关注外部或内部机制中的某一方面，忽视了两者的协同作用。ReDeEP框架将这两个机制分离，识别出导致幻觉的两大关键因素：对前馈网络（FFN）中编码的参数化知识过度依赖，以及注意力机制（尤其是复制头）对外部信息的利用率不足。ReDeEP通过量化评估这些因素来检测幻觉，并动态调节FFN和复制头的贡献以减少幻觉的发生。然而，ReDeEP和其他许多方法主要应用于逻辑层面的不确定性估计或语言层面的自洽性评估，未能充分考虑模型响应的语义维度，导致在RAG实现中对幻觉的评估结果不一致。本文在此基础上提出了SEReDeEP框架，通过训练线性探测器捕捉语义熵来优化计算过程，从而实现更准确反映真实评估的幻觉检测。

> Retrieval-Augmented Generation (RAG) models frequently encounter hallucination phenomena when integrating external information with internal parametric knowledge. Empirical studies demonstrate that the disequilibrium between external contextual information and internal parametric knowledge constitutes a primary factor in hallucination generation. Existing hallucination detection methodologies predominantly emphasize either the external or internal mechanism in isolation, thereby overlooking their synergistic effects. The recently proposed ReDeEP framework decouples these dual mechanisms, identifying two critical contributors to hallucinations: excessive reliance on parametric knowledge encoded in feed-forward networks (FFN) and insufficient utilization of external information by attention mechanisms (particularly copy heads). ReDeEP quantitatively assesses these factors to detect hallucinations and dynamically modulates the contributions of FFNs and copy heads to attenuate their occurrence. Nevertheless, ReDeEP and numerous other hallucination detection approaches have been employed at logit-level uncertainty estimation or language-level self-consistency evaluation, inadequately address the semantic dimensions of model responses, resulting in inconsistent hallucination assessments in RAG implementations. Building upon ReDeEP's foundation, this paper introduces SEReDeEP, which enhances computational processes through semantic entropy captured via trained linear probes, thereby achieving hallucination assessments that more accurately reflect ground truth evaluations.

[Arxiv](https://arxiv.org/abs/2505.07528)