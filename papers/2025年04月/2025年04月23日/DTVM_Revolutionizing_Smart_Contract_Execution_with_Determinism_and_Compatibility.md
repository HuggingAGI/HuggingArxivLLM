# DTVM：以确定性和兼容性重新定义智能合约执行

发布时间：2025年04月23日

`其他

理由：这篇论文主要讨论的是区块链网络中的智能合约执行框架，虽然提到了LLM的应用（如SmartCogent中的LLM和检索增强生成技术），但论文的核心贡献在于虚拟机设计、编译引擎优化和多语言支持，这些都属于计算机体系结构和编译原理的范畴，而不是直接专注于LLM的应用或理论。因此，这篇论文更适合归类为“其他”。` `区块链` `智能合约`

> DTVM: Revolutionizing Smart Contract Execution with Determinism and Compatibility

# 摘要

> 我们推出 DeTerministic Virtual Machine (DTVM) Stack，这是一个专为区块链网络设计的下一代智能合约执行框架，旨在解决性能、确定性和生态系统兼容性方面的关键挑战。DTVM 以 WebAssembly (Wasm) 为基础，同时完全兼容以太坊虚拟机 (EVM) 的 ABI 标准。它创新性地引入了 Deterministic Middle Intermediate Representation (dMIR) 和混合懒-JIT 编译引擎，实现了编译速度与执行效率的完美平衡。通过模块化适配层，DTVM 还支持多种指令集架构（如 EVM、RISC-V），并与混合懒-JIT 编译引擎无缝集成。该引擎能够在异构环境中动态优化性能，同时确保确定性执行。主要贡献包括：1) 在主流以太坊合约（如 ERC20/721/1155）执行中，DTVM 的速度是 evmone 的两倍，且斐波那契计算延迟较基于 Wasm 的虚拟机减少了 11.8% 至 40.5%。2) 独特的 trampoline hot-switch 机制实现了仅 0.95 毫秒的部署后调用时间，编译和调用效率提升了约 23 倍。3) 支持 Solidity、C++、Rust、Java、Go 和 AssemblyScript 等多语言开发，通过统一字节码转换实现，同时保持 EVM ABI 兼容性，使机器代码对象大小缩减 30.0% 至 72.6%，并采用最小可信计算基。4) 提供 SmartCogent，一个 AI 驱动的全栈开发解决方案，借助微调的 LLM 和检索增强生成技术，全面自动化智能合约开发、调试、安全审计和部署流程。DTVM Stack 已经开源，地址为 https://github.com/DTVMStack。

> We introduce the DeTerministic Virtual Machine (DTVM) Stack, a next-generation smart contract execution framework designed to address critical performance, determinism, and ecosystem compatibility challenges in blockchain networks. Building upon WebAssembly (Wasm) while maintaining full Ethereum Virtual Machine (EVM) ABI compatibility, DTVM introduces a Deterministic Middle Intermediate Representation (dMIR) and a hybrid lazy-JIT compilation engine to balance compilation speed and execution efficiency. DTVM further accommodates diverse instruction set architectures (e.g., EVM, RISC-V) through modular adaptation layers. This enables seamless integration with DTVM's hybrid lazy-JIT compilation engine, which dynamically optimizes performance while preserving deterministic execution guarantees across heterogeneous environments. The key contributions including: 1). The framework achieves up to 2$\times$ acceleration over evmone in dominant Ethereum contract (e.g. ERC20/721/1155) execution and reduces fibonacci computation latency by 11.8$\sim$40.5% compared to Wasm based VMs. 2). A novel trampoline hot-switch mechanism enables sub-millisecond (0.95ms) post-deployment invocation times, outperforming up to about 23$\times$ in compilation and invocation efficiency. 3). It supports multi-language development (Solidity, C++, Rust, Java, Go, and AssemblyScript) through unified bytecode conversion while maintaining EVM ABI compatibility for seamless invocation. It reduces machine code object sizes by 30.0$\sim$72.6%, coupled with a minimized Trusted Computing Base. 4). It offers SmartCogent, an AI-driven full-stack development experience, leveraging fine-tuned LLMs and retrieval-augmented generation to automate tasks across the smart contract lifecycle: development, debugging, security auditing, and deployment. DTVM Stack has been open-sourced (https://github.com/DTVMStack).

[Arxiv](https://arxiv.org/abs/2504.16552)