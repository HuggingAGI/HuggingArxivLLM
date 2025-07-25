# Scout: 侦察兵——借助大型语言模型快速发掘数字证据

发布时间：2025年07月24日

`LLM应用

摘要中提到Scout框架利用大型语言模型进行初步证据处理和优先级排序，属于将LLM应用于特定任务的场景，因此归类为LLM应用。` `数字取证`

> Scout: Leveraging Large Language Models for Rapid Digital Evidence Discovery

# 摘要

> 技术的快速发展和其在日常生活中的广泛应用，使得数字证据在法律调查中的出现概率显著上升。消费者级硬件设备的性能日益强大，内存和存储容量不断扩大，处理器能力也显著提升。数字取证调查人员在处理案件时，常常需要从海量数据中寻找线索，这一过程耗时费力。幸运的是，内存取证、磁盘分析等任务有先进的工具支持，这些工具通过提供字符串搜索、分析图像文件等功能，大大降低了取证调查人员的工作强度。然而，在调查过程中会发现大量误报信息，这些误报需要被尽可能地减少。本文介绍了一个名为Scout的数字取证框架，该框架利用大型语言模型进行初步证据处理和优先级排序。Scout能够从大量潜在证据文件（如磁盘镜像、捕获的网络数据包、内存转储等）中快速识别相关证据。对于包含文本信息的文件，Scout采用基于文本的大型语言模型进行处理。而对于音频、图像、视频、办公文档等多媒体文件的取证分析，Scout则运用多模态模型。Scout成功识别并提取了对调查人员可能感兴趣的证据文件，显著提高了取证效率。

> Recent technological advancements and the prevalence of technology in day to day activities have caused a major increase in the likelihood of the involvement of digital evidence in more and more legal investigations. Consumer-grade hardware is growing more powerful, with expanding memory and storage sizes and enhanced processor capabilities. Forensics investigators often have to sift through gigabytes of data during an ongoing investigation making the process tedious. Memory forensics, disk analysis all are well supported by state of the art tools that significantly lower the effort required to be put in by a forensic investigator by providing string searches, analyzing images file etc. During the course of the investigation a lot of false positives are identified that need to be lowered. This work presents Scout, a digital forensics framework that performs preliminary evidence processing and prioritizing using large language models. Scout deploys foundational language models to identify relevant artifacts from a large number of potential evidence files (disk images, captured network packets, memory dumps etc.) which would have taken longer to get identified. Scout employs text based large language models can easily process files with textual information. For the forensic analysis of multimedia files like audio, image, video, office documents etc. multimodal models are employed by Scout. Scout was able to identify and realize the evidence file that were of potential interest for the investigator.

[Arxiv](https://arxiv.org/abs/2507.18478)