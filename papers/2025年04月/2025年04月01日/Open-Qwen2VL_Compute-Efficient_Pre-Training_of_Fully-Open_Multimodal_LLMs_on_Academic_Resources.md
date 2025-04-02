# Open-Qwen2VL: 基于学术资源实现计算高效且完全开放的多模态大语言模型预训练

发布时间：2025年04月01日

`LLM理论` `大型语言模型` `多模态`

> Open-Qwen2VL: Compute-Efficient Pre-Training of Fully-Open Multimodal LLMs on Academic Resources

# 摘要

> 多模态 LLM 的预训练在数据筛选、多模态数据混合策略、序列打包技术和训练框架等每个环节都面临挑战。我们推出了完全开源的 Open-Qwen2VL，这是一个 20 亿参数的多模态大型语言模型，仅使用 442 个 A100-40G GPU 小时，在 2900 万张图像-文本对上高效预训练而成。我们的方法采用了动态图像分辨率和多模态序列打包技术，显著提升了预训练效率。在数据处理方面，我们结合了基于 MLLM 的过滤技术和传统的 CLIP 过滤方法，大幅提高了数据质量和训练效率。在 UCSB 的 8xA100-40G GPU 集群上，Open-Qwen2VL 使用了 50 亿个打包的多模态令牌进行预训练，仅占 Qwen2-VL 的 1.4T 预训练令牌的 0.36%。最终经过指令微调的 Open-Qwen2VL 在 MMBench、SEEDBench、MMstar 和 MathVista 等多模态基准测试中优于部分开源的 Qwen2-VL-2B，展现了其卓越的训练效率。我们开源了所有相关资源，包括高效训练细节、数据过滤方法、序列打包脚本、WebDataset 格式的预训练数据、FSDP 基础的训练代码库，以及基础模型和指令微调后的模型检查点。我们重新定义了多模态 LLM 的“完全开源”为：1）完整开放训练代码库，2）详细的数据过滤技术，3）全部用于开发的预训练和监督微调数据。

> The reproduction of state-of-the-art multimodal LLM pre-training faces barriers at every stage of the pipeline, including high-quality data filtering, multimodal data mixture strategies, sequence packing techniques, and training frameworks. We introduce Open-Qwen2VL, a fully open-source 2B-parameter Multimodal Large Language Model pre-trained efficiently on 29M image-text pairs using only 442 A100-40G GPU hours. Our approach employs low-to-high dynamic image resolution and multimodal sequence packing to significantly enhance pre-training efficiency. The training dataset was carefully curated using both MLLM-based filtering techniques (e.g., MLM-Filter) and conventional CLIP-based filtering methods, substantially improving data quality and training efficiency. The Open-Qwen2VL pre-training is conducted on academic level 8xA100-40G GPUs at UCSB on 5B packed multimodal tokens, which is 0.36\% of 1.4T multimodal pre-training tokens of Qwen2-VL. The final instruction-tuned Open-Qwen2VL outperforms partially-open state-of-the-art MLLM Qwen2-VL-2B on various multimodal benchmarks of MMBench, SEEDBench, MMstar, and MathVista, indicating the remarkable training efficiency of Open-Qwen2VL. We open-source all aspects of our work, including compute-efficient and data-efficient training details, data filtering methods, sequence packing scripts, pre-training data in WebDataset format, FSDP-based training codebase, and both base and instruction-tuned model checkpoints. We redefine "fully open" for multimodal LLMs as the complete release of: 1) the training codebase, 2) detailed data filtering techniques, and 3) all pre-training and supervised fine-tuning data used to develop the model.

[Arxiv](https://arxiv.org/abs/2504.00595)