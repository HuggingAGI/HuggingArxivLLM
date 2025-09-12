# 构建更优牙科AI：全景X光片分析的多模态基准与指令数据集

发布时间：2025年09月11日

`LLM应用` `医疗健康`

> Towards Better Dental AI: A Multimodal Benchmark and Instruction Dataset for Panoramic X-ray Analysis

# 摘要

> 近年来，大型视觉语言模型（LVLMs）在通用医疗任务中展现出卓越性能。但在牙科等专业领域，其实际效果尚未得到充分研究。尤其是全景X光片，作为口腔放射学中常用的成像方式，因其解剖结构密集且病理线索细微，解读难度较大，而现有的医疗基准或指令数据集均未涉及此类场景。为此，我们构建了MMOral——首个专为全景X光片解读打造的大规模多模态指令数据集与基准。该数据集包含20,563张标注图像，配套130万条覆盖多种任务类型的指令跟随实例，涵盖属性提取、报告生成、视觉问答及图像关联对话等任务。此外，我们还设计了MMOral-Bench——一套覆盖牙科五大关键诊断维度的综合评估工具。通过在MMOral-Bench上对64个LVLMs进行测试，我们发现即使是表现最佳的GPT-4o模型，准确率也仅为41.45%，这表明当前模型在该领域仍存在明显局限。为推动该领域发展，我们进一步提出OralGPT模型，通过我们精心构建的MMOral指令数据集在Qwen2.5-VL-7B基础上进行监督微调（SFT）。值得关注的是，仅需一轮SFT微调就能显著提升LVLMs的性能，其中OralGPT的性能提升达24.73%。MMOral与OralGPT有望成为智能牙科的核心基础，推动牙科领域更具临床价值的多模态AI系统落地。相关数据集、模型、基准及评估套件已在https://github.com/isbrycee/OralGPT开源。

> Recent advances in large vision-language models (LVLMs) have demonstrated strong performance on general-purpose medical tasks. However, their effectiveness in specialized domains such as dentistry remains underexplored. In particular, panoramic X-rays, a widely used imaging modality in oral radiology, pose interpretative challenges due to dense anatomical structures and subtle pathological cues, which are not captured by existing medical benchmarks or instruction datasets. To this end, we introduce MMOral, the first large-scale multimodal instruction dataset and benchmark tailored for panoramic X-ray interpretation. MMOral consists of 20,563 annotated images paired with 1.3 million instruction-following instances across diverse task types, including attribute extraction, report generation, visual question answering, and image-grounded dialogue. In addition, we present MMOral-Bench, a comprehensive evaluation suite covering five key diagnostic dimensions in dentistry. We evaluate 64 LVLMs on MMOral-Bench and find that even the best-performing model, i.e., GPT-4o, only achieves 41.45% accuracy, revealing significant limitations of current models in this domain. To promote the progress of this specific domain, we also propose OralGPT, which conducts supervised fine-tuning (SFT) upon Qwen2.5-VL-7B with our meticulously curated MMOral instruction dataset. Remarkably, a single epoch of SFT yields substantial performance enhancements for LVLMs, e.g., OralGPT demonstrates a 24.73% improvement. Both MMOral and OralGPT hold significant potential as a critical foundation for intelligent dentistry and enable more clinically impactful multimodal AI systems in the dental field. The dataset, model, benchmark, and evaluation suite are available at https://github.com/isbrycee/OralGPT.

[Arxiv](https://arxiv.org/abs/2509.09254)