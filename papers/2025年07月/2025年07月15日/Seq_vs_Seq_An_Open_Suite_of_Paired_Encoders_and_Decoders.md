# Seq与Seq：一个开放的配对编码器-解码器工具包

发布时间：2025年07月15日

`LLM理论`

> Seq vs Seq: An Open Suite of Paired Encoders and Decoders

# 摘要

> 当前，大型语言模型（LLM）研究领域几乎将全部注意力集中在解码器模型上，因其在文本生成任务中更为简便实用。然而，社区中仍有不少研究者沿用编码器模型处理分类或检索等任务。此前研究虽尝试对比分析这些架构，但受限于参数规模、训练方法和数据集的差异，对比结果难以全面。我们推出开源数据SOTA的Ettin模型套件，包含编码器模型与解码器模型，参数规模从1700万到10亿不等，基于高达2万亿token的数据进行训练。在编码器模型和解码器模型上采用相同的训练方法，使其在各自规模下均达到SOTA水平，其中编码器模型的表现超越了ModernBERT，而解码器模型则在13B参数规模下优于Llama 3.2和SmolLM2。与此前研究一致，编码器模型在分类和检索任务中表现优异，而解码器模型则在生成任务中更胜一筹。然而，我们发现，将解码器模型通过持续训练适应编码器任务（反之亦然），其效果不如直接使用相反目标模型（例如，400M参数的编码器在MNLI任务中优于1B参数的解码器，反之在生成任务中则相反）。我们开源了本研究的所有产物，包括训练数据、按检查点划分的训练顺序以及200多个检查点，以支持未来研究对训练过程的各个方面进行分析或扩展。

> The large language model (LLM) community focuses almost exclusively on decoder-only language models, since they are easier to use for text generation. However, a large subset of the community still uses encoder-only models for tasks such as classification or retrieval. Previous work has attempted to compare these architectures, but is forced to make comparisons with models that have different numbers of parameters, training techniques, and datasets. We introduce the SOTA open-data Ettin suite of models: paired encoder-only and decoder-only models ranging from 17 million parameters to 1 billion, trained on up to 2 trillion tokens. Using the same recipe for both encoder-only and decoder-only models produces SOTA recipes in both categories for their respective sizes, beating ModernBERT as an encoder and Llama 3.2 and SmolLM2 as decoders. Like previous work, we find that encoder-only models excel at classification and retrieval tasks while decoders excel at generative tasks. However, we show that adapting a decoder model to encoder tasks (and vice versa) through continued training is subpar compared to using only the reverse objective (i.e. a 400M encoder outperforms a 1B decoder on MNLI, and vice versa for generative tasks). We open-source all artifacts of this study including training data, training order segmented by checkpoint, and 200+ checkpoints to allow future work to analyze or extend all aspects of training.

[Arxiv](https://arxiv.org/abs/2507.11412)