# 有保障的猜测方法：一种用于CISC到RISC转译的语言建模方法，并提供测试保证

发布时间：2025年06月17日

`LLM应用` `计算机体系结构`

> Guaranteed Guess: A Language Modeling Approach for CISC-to-RISC Transpilation with Testing Guarantees

# 摘要

> 硬件生态系统正在迅速发展，研究者们正致力于快速、灵活且准确地实现跨指令集架构（ISA）的低级程序翻译，以提升现有代码的可移植性和使用寿命。其中，复杂指令集（CISC）与精简指令集（RISC）架构之间的翻译尤为具有挑战性，主要源于指令复杂性、内存模型及执行范式之间的根本差异。在本研究中，我们提出了GG（Guaranteed Guess）——一种以ISA为中心的翻译管道，它巧妙地结合了预训练大型语言模型（LLMs）的强大翻译能力与现有软件测试构造的严谨性。我们的方法利用LLM从一种ISA生成候选翻译到另一种ISA，并将这些翻译嵌入到软件测试框架中，以建立对翻译结果的可量化信心。我们在两个多样化数据集上对GG方法进行了评估，实现了超过98%的代码覆盖率，并在HumanEval程序中达到了99%的功能/语义正确性，在BringupBench程序中达到了49%。此外，我们将我们的方法与苹果硅上的最新Rosetta 2框架进行了对比，结果显示我们的翻译代码在运行时间性能上提升了1.73倍，能效提高了1.47倍，内存使用效率提升了2.41倍，充分证明了GG在现实世界CISC到RISC翻译任务中的有效性。我们计划开源我们的代码、数据、模型和基准测试，为ISA级代码翻译研究奠定坚实的基础。

> The hardware ecosystem is rapidly evolving, with increasing interest in translating low-level programs across different instruction set architectures (ISAs) in a quick, flexible, and correct way to enhance the portability and longevity of existing code. A particularly challenging class of this transpilation problem is translating between complex- (CISC) and reduced- (RISC) hardware architectures, due to fundamental differences in instruction complexity, memory models, and execution paradigms. In this work, we introduce GG (Guaranteed Guess), an ISA-centric transpilation pipeline that combines the translation power of pre-trained large language models (LLMs) with the rigor of established software testing constructs. Our method generates candidate translations using an LLM from one ISA to another, and embeds such translations within a software-testing framework to build quantifiable confidence in the translation. We evaluate our GG approach over two diverse datasets, enforce high code coverage (>98%) across unit tests, and achieve functional/semantic correctness of 99% on HumanEval programs and 49% on BringupBench programs, respectively. Further, we compare our approach to the state-of-the-art Rosetta 2 framework on Apple Silicon, showcasing 1.73x faster runtime performance, 1.47x better energy efficiency, and 2.41x better memory usage for our transpiled code, demonstrating the effectiveness of GG for real-world CISC-to-RISC translation tasks. We will open-source our codes, data, models, and benchmarks to establish a common foundation for ISA-level code translation research.

[Arxiv](https://arxiv.org/abs/2506.14606)