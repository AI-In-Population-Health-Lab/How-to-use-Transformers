![title](title.jpg)

[Transformers](https://huggingface.co/docs/transformers/index) 是由 [Hugging Face](https://huggingface.co/) 开发的一个 NLP 包，支持加载目前绝大部分的预训练模型。随着 BERT、GPT 等大规模语言模型的兴起，越来越多的公司和研究者采用 Transformers 库来构建 NLP 应用。

该项目为[《Transformers 库快速入门》](https://transformers.run/)系列教程的代码仓库，按照以下方式组织代码：

- *data*：存储使用到的数据集；
- *src*：存储所有的任务 Demo，每个任务一个文件夹，可以下载下来单独使用。

> 该教程暂未包含 [LLaMa](https://github.com/facebookresearch/llama) 等大规模语言模型 (LLM) 的使用方法。我最近也正在系统地学习，之后会把 LLM 内容添加进来，敬请期待。

## Transformers 库快速入门

- **第一部分：背景知识**
  - 第一章：[自然语言处理](https://transformers.run/c1/nlp/)
  - 第二章：[Transformer 模型](https://transformers.run/c1/transformer/)
  - 第三章：[注意力机制](https://transformers.run/c1/attention/)

- **第二部分：初识 Transformers**
  - 第四章：[开箱即用的 pipelines](https://transformers.run/c2/2021-12-08-transformers-note-1/)
  - 第五章：[模型与分词器](https://transformers.run/c2/2021-12-11-transformers-note-2/)
  - 第六章：[必要的 Pytorch 知识](https://transformers.run/c2/2021-12-14-transformers-note-3/)
  - 第七章：[微调预训练模型](https://transformers.run/c2/2021-12-17-transformers-note-4/)

- **第三部分：Transformers 实战**
  - 第八章：[快速分词器](https://transformers.run/c3/2022-03-08-transformers-note-5/)
  - 第九章：[序列标注任务](https://transformers.run/c3/2022-03-18-transformers-note-6/)
  - 第十章：[翻译任务](https://transformers.run/c3/2022-03-24-transformers-note-7/)
  - 第十一章：[文本摘要任务](https://transformers.run/c3/2022-03-29-transformers-note-8/)
  - 第十二章：[抽取式问答](https://transformers.run/c3/2022-04-02-transformers-note-9/)
  - 第十三章：[Prompt 情感分析](https://transformers.run/c3/2022-10-10-transformers-note-10/)

- **第四部分：大模型时代**
  - 第十四章：大模型简介
  - 第十五章：指令微调 FlanT5-XXL
  - 第十六章：指令微调 Llama2-7b

## Demo 一览

- [pairwise_cls_similarity_afqmc](https://github.com/jsksxs360/How-to-use-Transformers/tree/main/src/pairwise_cls_similarity_afqmc)：句子对分类任务，[金融同义句判断](https://transformers.run/c2/2021-12-17-transformers-note-4/)。
- [sequence_labeling_ner_cpd](https://github.com/jsksxs360/How-to-use-Transformers/tree/main/src/sequence_labeling_ner_cpd)：序列标注任务，[命名实体识别](https://transformers.run/c3/2022-03-18-transformers-note-6/)。
- [seq2seq_translation](https://github.com/jsksxs360/How-to-use-Transformers/tree/main/src/seq2seq_translation)：seq2seq任务，[中英翻译](https://transformers.run/c3/2022-03-24-transformers-note-7/)。
- [seq2seq_summarization](https://github.com/jsksxs360/How-to-use-Transformers/tree/main/src/seq2seq_summarization)：seq2seq任务，[文本摘要](https://transformers.run/c3/2022-03-29-transformers-note-8/)。
- [sequence_labeling_extractiveQA_cmrc](https://github.com/jsksxs360/How-to-use-Transformers/tree/main/src/sequence_labeling_extractiveQA_cmrc)：序列标注任务，[抽取式问答](https://transformers.run/c3/2022-04-02-transformers-note-9/)。
- [text_cls_prompt_senti_chnsenticorp](https://github.com/jsksxs360/How-to-use-Transformers/tree/main/src/text_cls_prompt_senti_chnsenticorp)：文本分类任务，[Prompt 情感分析](https://transformers.run/c3/2022-10-10-transformers-note-10/)。
