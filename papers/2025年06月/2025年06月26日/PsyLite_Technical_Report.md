# # PsyLite技术报告

发布时间：2025年06月26日

`LLM应用`

> PsyLite Technical Report

# 摘要

> 数字技术的迅猛发展推动了人工智能驱动的心理咨询成为心理健康领域的重要研究方向。然而，现有模型在对话安全性、场景细节处理和轻量化部署方面仍存在不足。为了解决这些问题，本研究提出了一种名为 PsyLite 的轻量级心理咨询大型语言模型代理，基于 InternLM2.5-7B-chat 开发。通过采用混合蒸馏数据微调和 ORPO 优化的两阶段训练策略，PsyLite 在深度推理、心理咨询和安全对话能力上得到了显著提升。部署后，利用 Ollama 和 Open WebUI 创建了自定义工作流，通过 Pipelines 实现。创新设计的条件式 RAG 在心理咨询过程中适时引入幽默元素，提升用户体验，同时拒绝危险请求，加强对话安全性。评估结果显示，PsyLite 在 CEval、CPsyCounE 和 SafeDialBench 等评估中表现优异，尤其在心理咨询专业性（CPsyCounE 评分提升 47.6%）和对话安全性（\safe{} 评分提升 2.4%）方面表现突出。此外，通过量化技术（GGUF q4\_k\_m）实现低硬件部署（5GB 内存即可运行），为资源受限环境下的心理咨询应用提供了可行的解决方案。

> With the rapid development of digital technology, AI-driven psychological counseling has gradually become an important research direction in the field of mental health. However, existing models still have deficiencies in dialogue safety, detailed scenario handling, and lightweight deployment. To address these issues, this study proposes PsyLite, a lightweight psychological counseling large language model agent developed based on the base model InternLM2.5-7B-chat. Through a two-stage training strategy (hybrid distillation data fine-tuning and ORPO preference optimization), PsyLite enhances the model's deep-reasoning ability, psychological counseling ability, and safe dialogue ability. After deployment using Ollama and Open WebUI, a custom workflow is created with Pipelines. An innovative conditional RAG is designed to introduce crosstalk humor elements at appropriate times during psychological counseling to enhance user experience and decline dangerous requests to strengthen dialogue safety. Evaluations show that PsyLite outperforms the baseline models in the Chinese general evaluation (CEval), psychological counseling professional evaluation (CPsyCounE), and dialogue safety evaluation (SafeDialBench), particularly in psychological counseling professionalism (CPsyCounE score improvement of 47.6\%) and dialogue safety (\safe{} score improvement of 2.4\%). Additionally, the model uses quantization technology (GGUF q4\_k\_m) to achieve low hardware deployment (5GB memory is sufficient for operation), providing a feasible solution for psychological counseling applications in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2506.21536)