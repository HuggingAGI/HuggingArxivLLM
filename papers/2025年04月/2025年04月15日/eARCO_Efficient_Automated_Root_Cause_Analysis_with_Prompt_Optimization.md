# eARCO：高效自动化的根因分析结合提示优化

发布时间：2025年04月15日

`LLM应用` `人工智能`

> eARCO: Efficient Automated Root Cause Analysis with Prompt Optimization

# 摘要

> 大规模云系统中的根本原因分析（RCA）是一项复杂且耗时的任务，通常需要值班工程师投入大量手动工作。提升RCA能力对于加快事件解决流程、减少服务停机时间和人工投入至关重要。大型语言模型（LLMs）的最新进展已被证明在解决事件管理生命周期的不同阶段（包括RCA）方面非常有效。

然而，现有的基于LLM的RCA建议通常依赖于默认微调或检索增强生成（RAG）方法，这些方法使用静态的、手动设计的提示，导致建议次优。在本研究中，我们利用'PromptWizard'，一种先进的提示优化技术，自动识别最佳优化的提示指令，并结合语义相似的历史示例，在推理过程中用于查询底层LLMs。此外，通过利用微软超过18万的历史事件数据，我们开发了成本效益高的微调小型语言模型（SLMs）用于生成RCA建议，并展示了在这些领域适应模型上提示优化的强大效果。

我们广泛的实验结果表明，与基于RAG的LLMs和微调的SLMs相比，提示优化在3000个测试事件上分别将RCA建议的准确性提高了21%和13%。最后，我们与事件所有者进行的人工评估证明了提示优化在RCA建议任务中的有效性。这些发现强调了将提示优化纳入AIOps系统的优势，无需增加计算开销即可实现显著提升。


> Root cause analysis (RCA) for incidents in large-scale cloud systems is a complex, knowledge-intensive task that often requires significant manual effort from on-call engineers (OCEs). Improving RCA is vital for accelerating the incident resolution process and reducing service downtime and manual efforts. Recent advancements in Large-Language Models (LLMs) have proven to be effective in solving different stages of the incident management lifecycle including RCA. However, existing LLM-based RCA recommendations typically leverage default finetuning or retrieval augmented generation (RAG) methods with static, manually designed prompts, which lead to sub-optimal recommendations. In this work, we leverage 'PromptWizard', a state-of-the-art prompt optimization technique, to automatically identify the best optimized prompt instruction that is combined with semantically similar historical examples for querying underlying LLMs during inference. Moreover, by utilizing more than 180K historical incident data from Microsoft, we developed cost-effective finetuned small language models (SLMs) for RCA recommendation generation and demonstrate the power of prompt optimization on such domain-adapted models. Our extensive experimental results show that prompt optimization can improve the accuracy of RCA recommendations by 21% and 13% on 3K test incidents over RAG-based LLMs and finetuned SLMs, respectively. Lastly, our human evaluation with incident owners have demonstrated the efficacy of prompt optimization on RCA recommendation tasks. These findings underscore the advantages of incorporating prompt optimization into AI for Operations (AIOps) systems, delivering substantial gains without increasing computational overhead.

[Arxiv](https://arxiv.org/abs/2504.11505)