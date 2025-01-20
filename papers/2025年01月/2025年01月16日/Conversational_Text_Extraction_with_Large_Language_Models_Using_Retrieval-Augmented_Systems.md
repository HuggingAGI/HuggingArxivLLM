# 基于检索增强系统的大型语言模型对话文本提取

发布时间：2025年01月16日

`RAG

理由：该论文描述了一个基于大型语言模型（LLMs）的系统，该系统通过检索增强生成（RAG）技术来增强用户与PDF文档的交互。RAG技术结合了检索和生成，能够从文档中检索相关信息并生成上下文感知的答案。因此，该论文应归类为RAG。` `文档处理` `知识管理`

> Conversational Text Extraction with Large Language Models Using Retrieval-Augmented Systems

# 摘要

> 本研究提出了一种基于大型语言模型（LLMs）的系统，通过对话界面增强用户与PDF文档的交互。该系统采用检索增强生成（RAG）技术，能够为用户查询提供信息丰富的响应，并突出显示PDF中的相关段落。用户上传PDF后，系统会处理文档并生成特定于文档的向量存储，以便高效检索与用户查询相关的部分。随后，LLM通过对话交流，利用检索到的信息提取文本并生成全面、上下文感知的答案。尽管我们的方法在文本提取和摘要方面与现有最先进技术相比表现出具有竞争力的ROUGE值，但我们仍需进一步定性评估以全面评估其在实际应用中的有效性。该系统为研究人员、学生以及任何希望通过直观的问答界面高效提取知识并从文档中获得见解的人提供了一个有价值的工具。

> This study introduces a system leveraging Large Language Models (LLMs) to extract text and enhance user interaction with PDF documents via a conversational interface. Utilizing Retrieval-Augmented Generation (RAG), the system provides informative responses to user inquiries while highlighting relevant passages within the PDF. Upon user upload, the system processes the PDF, employing sentence embeddings to create a document-specific vector store. This vector store enables efficient retrieval of pertinent sections in response to user queries. The LLM then engages in a conversational exchange, using the retrieved information to extract text and generate comprehensive, contextually aware answers. While our approach demonstrates competitive ROUGE values compared to existing state-of-the-art techniques for text extraction and summarization, we acknowledge that further qualitative evaluation is necessary to fully assess its effectiveness in real-world applications. The proposed system gives competitive ROUGE values as compared to existing state-of-the-art techniques for text extraction and summarization, thus offering a valuable tool for researchers, students, and anyone seeking to efficiently extract knowledge and gain insights from documents through an intuitive question-answering interface.

[Arxiv](https://arxiv.org/abs/2501.09801)