# 双级指纹框架 DuFFin：用于保护大型语言模型的知识产权

发布时间：2025年05月22日

`LLM应用` `知识产权保护` `模型保护`

> DuFFin: A Dual-Level Fingerprinting Framework for LLMs IP Protection

# 摘要

> 大型语言模型（LLMs）因其高昂的训练成本被视为合法所有者的宝贵知识产权。保护这些模型免受恶意窃取或未经授权使用至关重要。尽管已有研究尝试通过水印和指纹识别来保护LLMs，但这些方法要么干扰文本生成，要么受限于黑盒环境下的访问权限，难以实际应用。因此，我们提出了DuFFin，一个专为黑盒环境设计的双级别指纹框架，用于模型所有权验证。DuFFin通过提取触发模式和知识层面的指纹特征，精准识别可疑模型的来源。我们在开源网站收集的多种模型上进行了实验，包括四个流行基线模型作为受保护的LLMs，以及它们的微调、量化和安全对齐版本，这些版本由大型企业、初创公司和个人开发者发布。实验结果表明，我们的方法能够准确验证基线受保护LLM在模型变体中的版权归属，实现了IP-ROC指标超过0.95的优异性能。我们的代码可在https://github.com/yuliangyan0807/llm-fingerprint获取。

> Large language models (LLMs) are considered valuable Intellectual Properties (IP) for legitimate owners due to the enormous computational cost of training. It is crucial to protect the IP of LLMs from malicious stealing or unauthorized deployment. Despite existing efforts in watermarking and fingerprinting LLMs, these methods either impact the text generation process or are limited in white-box access to the suspect model, making them impractical. Hence, we propose DuFFin, a novel $\textbf{Du}$al-Level $\textbf{Fin}$gerprinting $\textbf{F}$ramework for black-box setting ownership verification. DuFFin extracts the trigger pattern and the knowledge-level fingerprints to identify the source of a suspect model. We conduct experiments on a variety of models collected from the open-source website, including four popular base models as protected LLMs and their fine-tuning, quantization, and safety alignment versions, which are released by large companies, start-ups, and individual users. Results show that our method can accurately verify the copyright of the base protected LLM on their model variants, achieving the IP-ROC metric greater than 0.95. Our code is available at https://github.com/yuliangyan0807/llm-fingerprint.

[Arxiv](https://arxiv.org/abs/2505.16530)