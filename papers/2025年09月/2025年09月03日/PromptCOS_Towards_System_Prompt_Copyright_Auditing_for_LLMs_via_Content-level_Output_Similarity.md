# PromptCOS：基于内容级输出相似度的大型语言模型（LLMs）系统提示词版权审计

发布时间：2025年09月03日

`LLM应用` `法律科技`

> PromptCOS: Towards System Prompt Copyright Auditing for LLMs via Content-level Output Similarity

# 摘要

> 大型语言模型（LLMs）的飞速发展显著提升了推理任务性能，并推动了基于LLM的应用开发。而提升这类应用性能的关键在于设计有效的系统提示——它们对LLMs的行为模式和输出质量有着决定性影响。但系统提示极易被窃取和滥用，进而损害提示所有者的权益。现有方法虽通过水印注入与验证保护提示版权，却因依赖LLM的中间输出（如logits）而面临瓶颈，实际应用受限。
  为此，本文提出PromptCOS——一种基于内容层面输出相似度的提示版权审计方法。该方法通过优化提示嵌入水印，同时协同优化特殊的验证查询与内容层面的信号标记。具体而言，它利用循环输出信号并注入辅助标记，确保在仅依赖内容的场景下也能实现可靠审计。此外，该方法还引入掩护标记，防止水印被恶意删除。在版权验证阶段，PromptCOS通过比对可疑输出与信号标记的相似度来识别未授权使用行为。实验结果显示，该方法具备多项优势：高有效性（平均水印相似度达99.3%）、强区分度（较最佳基线提升60.8%）、高保真度（准确率下降不超过0.58%）、鲁棒性（可抵御三类潜在攻击）以及计算高效性（计算成本降低高达98.1%）。相关代码已开源至GitHub：https://github.com/LianPing-cyber/PromptCOS。

> The rapid progress of large language models (LLMs) has greatly enhanced reasoning tasks and facilitated the development of LLM-based applications. A critical factor in improving LLM-based applications is the design of effective system prompts, which significantly impact the behavior and output quality of LLMs. However, system prompts are susceptible to theft and misuse, which could undermine the interests of prompt owners. Existing methods protect prompt copyrights through watermark injection and verification but face challenges due to their reliance on intermediate LLM outputs (e.g., logits), which limits their practical feasibility.
  In this paper, we propose PromptCOS, a method for auditing prompt copyright based on content-level output similarity. It embeds watermarks by optimizing the prompt while simultaneously co-optimizing a special verification query and content-level signal marks. This is achieved by leveraging cyclic output signals and injecting auxiliary tokens to ensure reliable auditing in content-only scenarios. Additionally, it incorporates cover tokens to protect the watermark from malicious deletion. For copyright verification, PromptCOS identifies unauthorized usage by comparing the similarity between the suspicious output and the signal mark. Experimental results demonstrate that our method achieves high effectiveness (99.3% average watermark similarity), strong distinctiveness (60.8% greater than the best baseline), high fidelity (accuracy degradation of no more than 0.58%), robustness (resilience against three types of potential attacks), and computational efficiency (up to 98.1% reduction in computational cost). Our code is available at GitHub https://github.com/LianPing-cyber/PromptCOS.

[Arxiv](https://arxiv.org/abs/2509.03117)