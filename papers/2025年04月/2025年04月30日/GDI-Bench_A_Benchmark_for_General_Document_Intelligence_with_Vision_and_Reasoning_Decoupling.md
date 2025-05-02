# GDI-Bench：解耦视觉与推理的通用文档智能基准

发布时间：2025年04月30日

`LLM应用` `文档智能` `计算机视觉`

> GDI-Bench: A Benchmark for General Document Intelligence with Vision and Reasoning Decoupling

# 摘要

> 多模态大语言模型（MLLMs）的迅猛发展掀起了一场深刻的文档领域变革，催生了丰富的应用场景。为全面评估这些模型在文档特定任务中的能力，建立一个完善的基准测试势在必行。然而，现有基准测试往往难以准确定位模型的短板，也难以提供系统性改进的指导。为此，我们推出了通用文档智能基准测试（GDI-Bench），涵盖9大关键场景与19项文档特定任务，包含1.9千张图像。通过分离视觉复杂度与推理复杂度，GDI-Bench构建了分级任务体系，支持按难度评估模型性能，从而帮助识别模型的短板并提供优化指导。我们对GDI-Bench进行了跨开源与闭源模型的全面评估，并在视觉与推理领域分别开展分离式分析。例如，GPT-4o模型在推理任务中表现出色，但在视觉能力上仍存在局限。为应对GDI-Bench中的多样化任务与领域，我们提出了一种GDI模型，通过智能保存式训练策略，在监督微调（SFT）过程中有效缓解灾难性遗忘问题。我们的模型在以往基准测试与GDI-Bench中均达到了前沿性能水平。我们的基准测试与模型均将开源，以促进相关研究的发展。

> The rapid advancement of multimodal large language models (MLLMs) has profoundly impacted the document domain, creating a wide array of application scenarios. This progress highlights the need for a comprehensive benchmark to evaluate these models' capabilities across various document-specific tasks. However, existing benchmarks often fail to locate specific model weaknesses or guide systematic improvements. To bridge this gap, we introduce a General Document Intelligence Benchmark (GDI-Bench), featuring 1.9k images across 9 key scenarios and 19 document-specific tasks. By decoupling visual complexity and reasoning complexity, the GDI-Bench structures graded tasks that allow performance assessment by difficulty, aiding in model weakness identification and optimization guidance. We evaluate the GDI-Bench on various open-source and closed-source models, conducting decoupled analyses in the visual and reasoning domains. For instance, the GPT-4o model excels in reasoning tasks but exhibits limitations in visual capabilities. To address the diverse tasks and domains in the GDI-Bench, we propose a GDI Model that mitigates the issue of catastrophic forgetting during the supervised fine-tuning (SFT) process through a intelligence-preserving training strategy. Our model achieves state-of-the-art performance on previous benchmarks and the GDI-Bench. Both our benchmark and model will be open source.

[Arxiv](https://arxiv.org/abs/2505.00063)