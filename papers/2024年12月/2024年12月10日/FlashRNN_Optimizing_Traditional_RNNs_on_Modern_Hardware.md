# FlashRNN：对现代硬件上的传统 RNN 进行优化

发布时间：2024年12月10日

`其他` `硬件优化` `序列建模`

> FlashRNN: Optimizing Traditional RNNs on Modern Hardware

# 摘要

> 摘要：尽管 Transformer 及其他序列可并行化的神经网络架构在序列建模领域看似处于前沿，但它们明显缺乏状态跟踪能力。这种能力对于时间序列任务和逻辑推理至关重要。传统的 RNN 如 LSTM 和 GRU，以及现代变体如 sLSTM 虽具备此能力，却以严格的顺序处理为代价。尽管这常被视作重大局限，但我们通过在 Triton 和 CUDA 中的硬件优化 FlashRNN 展示了这些网络能达到的高速。我们用一种并行化变体拓展了传统 RNN，它能并行处理多个隐藏状态较小的 RNN，类似于 Transformer 中的头向处理。为在不同 GPU 变体上实现灵活性，我们引入了针对硬件内部缓存大小、内存和计算处理的新优化框架。它在一种设定中利用类似多面体的约束（包含可除性概念）对硬件进行建模，加快了 ConstrINT 库中一般整数约束满足问题（整数 CSP）的求解过程。我们的内核比普通 PyTorch 实现快 50 倍，且与 Triton 实现相比，允许的隐藏大小大 40 倍。我们在此发布开源内核和优化库，以促进支持状态跟踪的 RNN 和序列建模方面的研究：url{这个 https URL}

> 
Abstract:While Transformers and other sequence-parallelizable neural network architectures seem like the current state of the art in sequence modeling, they specifically lack state-tracking capabilities. These are important for time-series tasks and logical reasoning. Traditional RNNs like LSTMs and GRUs, as well as modern variants like sLSTM do have these capabilities at the cost of strictly sequential processing. While this is often seen as a strong limitation, we show how fast these networks can get with our hardware-optimization FlashRNN in Triton and CUDA, optimizing kernels to the register level on modern GPUs. We extend traditional RNNs with a parallelization variant that processes multiple RNNs of smaller hidden state in parallel, similar to the head-wise processing in Transformers. To enable flexibility on different GPU variants, we introduce a new optimization framework for hardware-internal cache sizes, memory and compute handling. It models the hardware in a setting using polyhedral-like constraints, including the notion of divisibility. This speeds up the solution process in our ConstrINT library for general integer constraint satisfaction problems (integer CSPs). We show that our kernels can achieve 50x speed-ups over a vanilla PyTorch implementation and allow 40x larger hidden sizes compared to our Triton implementation. Our open-source kernels and the optimization library are released here to boost research in the direction of state-tracking enabled RNNs and sequence modeling: \url{this https URL}
    

[Arxiv](https://arxiv.org/pdf/2412.07752)