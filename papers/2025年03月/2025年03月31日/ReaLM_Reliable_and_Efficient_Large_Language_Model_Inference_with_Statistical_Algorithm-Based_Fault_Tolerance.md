# ReaLM：通过统计算法容错实现可靠高效的大语言模型推理

发布时间：2025年03月31日

`LLM应用

理由：这篇论文探讨了如何通过硬件和算法协同设计来优化大型语言模型的推理效率和容错能力，属于LLM的应用层面改进。` `计算机科学` `硬件设计`

> ReaLM: Reliable and Efficient Large Language Model Inference with Statistical Algorithm-Based Fault Tolerance

# 摘要

> 高效大型语言模型（LLM）推理的需求推动了专用加速器的发展。然而，现有加速器设计往往忽视了LLM本身的容错能力，导致计算和能源开销过高。为实现可靠且高效的LLM推理，本文提出了一种全新的算法/电路协同设计框架——ReaLM。通过大规模错误注入研究，我们首次系统地表征了LLMs及自然语言理解任务的容错能力。基于此，我们提出了一种统计型ABFT算法，充分挖掘错误鲁棒性以减少恢复成本。同时，我们定制了低成本的在线错误统计收集电路。实验表明，ReaLM仅需1.42%的电路面积和1.79%的功耗开销，即可将困惑度下降从18.54降至0.29。与现有方法相比，ReaLM在不同工作电压下均显著降低了恢复成本，并将能效提升了高达35.83%，同时保持LLM性能。我们的错误注入代码可在GitHub上获取。


> The demand for efficient large language model (LLM) inference has propelled the development of dedicated accelerators. As accelerators are vulnerable to hardware faults due to aging, variation, etc, existing accelerator designs often reserve a large voltage margin or leverage algorithm-based fault tolerance (ABFT) techniques to ensure LLM inference correctness. However, previous methods often overlook the inherent fault tolerance of LLMs, leading to high computation and energy overhead. To enable reliable yet efficient LLM inference, in this paper, we propose a novel algorithm/circuit co-design framework, dubbed ReaLM. For the first time, we systematically characterize the fault tolerance of LLMs by performing a large-scale error injection study of representative LLMs and natural language understanding tasks. Then, we propose a statistical ABFT algorithm that fully leverages the error robustness to minimize error recovery as much as possible. We also customize the error detection circuits to enable a low-cost online collection of error statistics. Extensive experiments show that with only 1.42% circuit area and 1.79% power overhead, our ReaLM can reduce perplexity degradation from 18.54 to 0.29. Compared to existing methods, ReaLM consistently reduces recovery costs across different operating voltages and improves energy efficiency by up to 35.83% without compromising LLM performance. Our error injection code is available at https://github.com/2000012835xt/ReaLM-DAC.

[Arxiv](https://arxiv.org/abs/2503.24053)