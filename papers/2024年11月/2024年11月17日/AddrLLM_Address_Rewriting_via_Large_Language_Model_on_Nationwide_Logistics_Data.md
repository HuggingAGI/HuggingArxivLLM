# AddrLLM：基于大型语言模型对全国物流数据进行地址重写

发布时间：2024年11月17日

`LLM应用` `地址重写`

> AddrLLM: Address Rewriting via Large Language Model on Nationwide Logistics Data

# 摘要

> 对物理位置的文字描述，也就是通常所说的地址，在诸如按需配送和导航这类基于位置的服务（LBS）里发挥着重要作用。然而，异常地址（那些包含无法精准定位的错误信息的地址）的大量存在，造成了巨大的成本。地址重写由此成为纠正这些异常地址的解决方案。尽管需求紧迫，但现有的地址重写方法存在局限性，往往是为纠正特定错误类型而定制的，或者常常需要重新训练才能有效处理新的地址数据。在本研究中，我们推出了 AddrLLM，这是一个基于检索增强型大型语言模型构建的创新框架，用于地址重写。AddrLLM 通过精心设计的监督微调模块、以地址为中心的检索增强生成模块以及无偏差目标对齐模块，克服了上述种种限制。据我们所知，本研究率先应用基于 LLM 的地址重写方法来解决异常地址的问题。通过对全国范围内的真实数据展开全面的离线测试，以及后续的在线部署，AddrLLM 在与现有物流系统的整合中展现出了卓越的性能。它大幅降低了包裹重新路由的比率约 43%，凸显了其在实际应用中的非凡成效。

> Textual description of a physical location, commonly known as an address, plays an important role in location-based services(LBS) such as on-demand delivery and navigation. However, the prevalence of abnormal addresses, those containing inaccuracies that fail to pinpoint a location, have led to significant costs. Address rewriting has emerged as a solution to rectify these abnormal addresses. Despite the critical need, existing address rewriting methods are limited, typically tailored to correct specific error types, or frequently require retraining to process new address data effectively. In this study, we introduce AddrLLM, an innovative framework for address rewriting that is built upon a retrieval augmented large language model. AddrLLM overcomes aforementioned limitations through a meticulously designed Supervised Fine-Tuning module, an Address-centric Retrieval Augmented Generation module and a Bias-free Objective Alignment module. To the best of our knowledge, this study pioneers the application of LLM-based address rewriting approach to solve the issue of abnormal addresses. Through comprehensive offline testing with real-world data on a national scale and subsequent online deployment, AddrLLM has demonstrated superior performance in integration with existing logistics system. It has significantly decreased the rate of parcel re-routing by approximately 43\%, underscoring its exceptional efficacy in real-world applications.

[Arxiv](https://arxiv.org/abs/2411.13584)