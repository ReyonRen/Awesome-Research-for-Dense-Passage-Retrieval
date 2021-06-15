# Awesome-Research-for-Dense-Passage-Retrieval


> A curated list of awesome papers related to dense passage retrieval retrieval. Any feedback and contribution are welcome!



## Table of Contents

- [Survey paper](#survey-paper)
- [Ad-hoc Dense Passage Retrieval](#first-stage-retrieval)
- [Design Pre-training Task(s)](#re-ranking-stage)
  - [End-to-End Training](#directly-apply-pre-trained-models-to-IR)
  - [Pre-training then Fine-tuning on original task](#design-new-pre-training-tasks-for-reranking)
- [Negative Sampling](#multimodal-retrieval)
  - [Ad-hoc Negative Sampling]
  - [Utilize Cross-encoder](#unified-single-stream-architecture)
- [Other Resources](#other-resources)


 
## Survey Paper
- [Pretrained Transformers for Text Ranking: BERT and Beyond.](https://arxiv.org/abs/2010.06467) *Jimmy Lin et.al.*
- [Semantic Models for the First-stage Retrieval: A Comprehensive Review.](https://arxiv.org/pdf/2103.04831.pdf) *Yinqiong Cai et.al.*

## Ad-hoc Dense Passage Retrieval
- [DC-BERT: Decoupling Question and Document for Efficient Contextual Encoding.](https://arxiv.org/pdf/2002.12591.pdf) *Yuyu Zhang, Ping Nie et.al.* SIGIR 2020 short. (**DC-BERT**)
- [Dense Passage Retrieval for Open-Domain Question Answering.](https://arxiv.org/pdf/2004.04906.pdf) *Vladimir Karpukhin,Barlas Oguz et.al.* EMNLP 2020 [[code](https://github.com/facebookresearch/DPR)] (**DPR**)
- [Poly-encoders: Architectures and pre-training strategies for fast and accurate multi-sentence scoring.](https://arxiv.org/pdf/1905.01969.pdf) *Samuel Humeau,Kurt Shuster et.al.* ICLR 2020. [[code](https://github.com/facebookresearch/ParlAI/tree/master/projects/polyencoder)] (**Poly-encoders**)
- [ColBERT: Efficient and Effective Passage Search via Contextualized Late Interaction over BERT.](https://arxiv.org/pdf/2004.12832.pdf) *Omar Khattab et.al.* SIGIR 2020. [[code](https://github.com/stanford-futuredata/ColBERT)] (**ColBERT**)
- [Modularized Transfomer-based Ranking Framework](https://arxiv.org/pdf/2004.13313.pdf) *Luyu Gao et.al.* EMNLP 2020. [[code](https://github.com/luyug/MORES)] (**MORES, similar to Poly-encoders**)
- [Approximate Nearest Neighbor Negative Contrastive Learning for Dense Text Retrieval.](https://arxiv.org/pdf/2007.00808.pdf) *Lee Xiong, Chenyan Xiong et.al.* [[code](https://github.com/microsoft/ANCE)] (**ANCE**)
- [RepBERT: Contextualized Text Embeddings for First-Stage Retrieval.](https://arxiv.org/pdf/2006.15498.pdf) *Jingtao Zhan et.al.* Arxiv 2020. [[code](https://github.com/jingtaozhan/RepBERT-Index)] (**RepBERT**)


## Design Pre-training Task(s)
- [End-to-End Training](#directly-apply-pre-trained-models-to-IR)
- [Pre-training then Fine-tuning on original task](#design-new-pre-training-tasks-for-reranking)

### End-to-End Training
- [Latent Retrieval for Weakly Supervised Open Domain Question Answering.](https://arxiv.org/pdf/1906.00300.pdf) *Kenton Lee et.al.* ACL 2019. [[code](https://github.com/google-research/language/blob/master/language/orqa/README.md)] (**ORQA, ICT**)
- [REALM: Retrieval-Augmented Language Model Pre-Training.](https://arxiv.org/pdf/2002.08909.pdf) *Kelvin Guu, Kenton Lee et.al.* ICML 2020. [[code](https://github.com/google-research/language/blob/master/language/realm/README.md)] (**REALM**)
- [End-to-End Training of Neural Retrievers for Open-Domain Question Answering.](https://arxiv.org/abs/2101.00408) *Devendra Singh Sachan et.al.* ACL 2021.


### Pre-training then Fine-tuning on original task
- [Pre-training tasks for embedding-based large scale retrieval.](https://arxiv.org/pdf/2002.03932.pdf) *Wei-Cheng Chang et.al.* ICLR 2020. (**ICT, BFS and WLP**)
- PAIR


## Negative Sampling
- [Ad-hoc Negative Sampling]
- [Utilize Cross-encoder]

### Ad-hoc Negative Sampling

### Utilize Cross-encoder

-----------------------------------------------------------------------------------------------------------


### Decouple the encoding of query and document

**In traditional ad-hoc retrieval**
- [ColBERT: Efficient and Effective Passage Search via Contextualized Late Interaction over BERT.](https://arxiv.org/pdf/2004.12832.pdf) *Omar Khattab et.al.* SIGIR 2020. [[code](https://github.com/stanford-futuredata/ColBERT)] (**ColBERT**)
- [Efficient Document Re-Ranking for Transformers by Precomputing Term Representations.](https://arxiv.org/pdf/2004.14255.pdf) *Sean MacAvaney et.al.* SIGIR 2020. [[code](https://github.com/Georgetown-IR-Lab/prettr-neural-ir)] (**PreTTR**)
- [Poly-encoders: Architectures and pre-training strategies for fast and accurate multi-sentence scoring.](https://arxiv.org/pdf/1905.01969.pdf) *Samuel Humeau,Kurt Shuster et.al.* ICLR 2020. [[code](https://github.com/facebookresearch/ParlAI/tree/master/projects/polyencoder)] (**Poly-encoders**)
- [Modularized Transfomer-based Ranking Framework](https://arxiv.org/pdf/2004.13313.pdf) *Luyu Gao et.al.* EMNLP 2020. [[code](https://github.com/luyug/MORES)] (**MORES, similar to Poly-encoders**)
- [Approximate Nearest Neighbor Negative Contrastive Learning for Dense Text Retrieval.](https://arxiv.org/pdf/2007.00808.pdf) *Lee Xiong, Chenyan Xiong et.al.* [[code](https://github.com/microsoft/ANCE)] (**ANCE**)
- [RepBERT: Contextualized Text Embeddings for First-Stage Retrieval.](https://arxiv.org/pdf/2006.15498.pdf) *Jingtao Zhan et.al.* Arxiv 2020. [[code](https://github.com/jingtaozhan/RepBERT-Index)] (**RepBERT**)
- [RocketQA: An Optimized Training Approach to Dense Passage Retrieval for Open-Domain Question Answering.](https://arxiv.org/pdf/2010.08191.pdf) *Yingqi Qu et.al.* Arxiv 2020. (**RocketQA**)
- [Optimizing Dense Retrieval Model Training with Hard Negatives.](https://arxiv.org/pdf/2104.08051.pdf) *Jingtao Zhan et.al.* SIGIR 2021.[[code](https://github.com/jingtaozhan/DRhard)] (**ADORE&STAR, query-side finetuning**)
- [Efficiently Teaching an Effective Dense Retriever with Balanced Topic Aware Sampling.](https://arxiv.org/pdf/2104.06967.pdf) *Sebastian Hofstätter et.al.* SIGIR 2021.[[code](https://github.com/sebastian-hofstaetter/tas-balanced-dense-retrieval)] (**TAS-Balanced, sample from query cluster**)

**In open domain question answering**
- [Real-Time Open-Domain Question Answering with Dense-Sparse Phrase Index.](https://arxiv.org/pdf/1906.05807.pdf) *Minjoon Seo,Jinhyuk Lee et.al.* ACL 2019. [[code](https://github.com/uwnlp/denspi)] (**DENSPI**)
- [Dense Passage Retrieval for Open-Domain Question Answering.](https://arxiv.org/pdf/2004.04906.pdf) *Vladimir Karpukhin,Barlas Oguz et.al.* EMNLP 2020 [[code](https://github.com/facebookresearch/DPR)] (**DPR**)
- [Contextualized Sparse Representations for Real-Time Open-Domain Question Answering.](https://arxiv.org/pdf/1911.02896.pdf) *Jinhyuk Lee, Minjoon Seo et.al.* ACL 2020. [[code](https://github.com/jhyuklee/sparc)] (**SPARC, sparse vectors**)
- [DC-BERT: Decoupling Question and Document for Efficient Contextual Encoding.](https://arxiv.org/pdf/2002.12591.pdf) *Yuyu Zhang, Ping Nie et.al.* SIGIR 2020 short. (**DC-BERT**)
- [Distilling Knowledge from Reader to Retriever for Question Answering.](https://arxiv.org/pdf/2012.04584.pdf) *Gautier Izacard1 et.al.* ICLR 2021.
- [Learning Dense Representations of Phrases at Scale.](https://arxiv.org/pdf/2012.12624.pdf) *Jinhyuk Lee, Danqi Chen et.al.* ArxiV 2021. [[code](https://github.com/jhyuklee/DensePhrases)] (**DensePhrases**)


## Re-ranking Stage
- [Directly apply pre-trained models to IR](#directly-apply-pre-trained-models-to-IR)
- [Design new pre-training tasks for reranking](#design-new-pre-training-tasks-for-reranking)
- [Modify on top of the existing pre-trained models](#modify-on-top-of-the-existing-pre-trained-models)


### Directly apply pre-trained models to IR
- [Passage Re-ranking with BERT.](https://arxiv.org/pdf/1901.04085.pdf) *Rodrigo Nogueira et.al.* [[code](https://github.com/nyu-dl/dl4marco-bert)] (**monoBERT: Maybe the first work on applying BERT to IR**) 
- [Multi-Stage Document Ranking with BERT,](https://arxiv.org/pdf/1910.14424.pdf) [The Expando-Mono-Duo Design Pattern for Text Ranking with Pretrained Sequence-to-Sequence Models.](https://arxiv.org/pdf/2101.05667.pdf) *Rodrigo Nogueira et.al.* Arxiv 2020. (**Expando-Mono-Duo: doc2query+pointwise+pairwise**)
- [Simple Applications of BERT for Ad Hoc Document Retrieval,](https://arxiv.org/pdf/1903.10972.pdf) [Applying BERT to Document Retrieval with Birch,](https://www.aclweb.org/anthology/D19-3004.pdf) [Cross-Domain Modeling of Sentence-Level Evidence for Document Retrieval.](https://www.aclweb.org/anthology/D19-1352.pdf) *Wei Yang, Haotian Zhang et.al.* Arxiv 2020, *Zeynep Akkalyoncu Yilmaz et.al.* EMNLP 2019 short. [[code](https://github.com/castorini/birch)] (**Birch: Sentence-level**)
- [Deeper Text Understanding for IR with Contextual Neural Language Modeling.](https://arxiv.org/pdf/1905.09217.pdf) *Zhuyun Dai et.al.* SIGIR 2020 short. [[code](https://github.com/AdeDZY/SIGIR19-BERT-IR)] (**BERT-MaxP, BERT-firstP, BERT-sumP: Passage-level**)
- [CEDR: Contextualized Embeddings for Document Ranking.](https://arxiv.org/pdf/1904.07094.pdf) *Sean MacAvaney et.al.* SIGIR 2020 short. [[code](https://github.com/Georgetown-IR-Lab/cedr)] (**CEDR: BERT+ranking model**)
- [Training Curricula for Open Domain Answer Re-Ranking.](https://arxiv.org/pdf/2004.14269.pdf) *Sean MacAvaney et.al.* SIGIR 2020. [[code](https://github.com/Georgetown-IR-Lab/curricula-neural-ir)] (**curriculum learning based on BM25**)
- [Leveraging Passage-level Cumulative Gain for Document Ranking.](https://dl.acm.org/doi/pdf/10.1145/3366423.3380305) *Zhijing Wu et.al.* WWW 2020. (**PCGM**)
- [Selective Weak Supervision for Neural Information Retrieval.](https://arxiv.org/pdf/2001.10382.pdf) *Kaitao Zhang et.al.* WWW 2020. [[code](https://github.com/thunlp/ReInfoSelect)] (**ReInfoSelect**)
- [Document Ranking with a Pretrained Sequence-to-Sequence Model.](https://arxiv.org/pdf/2003.06713.pdf) *Rodrigo Nogueira, Zhiying Jiang et.al.* EMNLP 2020. [[code](https://github.com/castorini/pygaggle/)] (**using T5**)
<!-- - [CLIRMatrix: A massively large collection of bilingual and multilingual datasets for Cross-Lingual Information Retrieval.](https://www.aclweb.org/anthology/2020.emnlp-main.340.pdf) *Shuo Sun et.al.* EMNLP 2020. [[code](https://github.com/ssun32/CLIRMatrix)] (**Multilingual dataset: CLIRMatrix**) -->
- [Beyond [CLS] through Ranking by Generation.](https://arxiv.org/pdf/2010.03073.pdf) *Cicero Nogueira dos Santos et.al.* EMNLP 2020 short. (**query likelihood computed by GPT**)
- [BERT-QE: Contextualized Query Expansion for Document Re-ranking.](https://arxiv.org/pdf/2009.07258.pdf) *Zhi Zheng et.al.* EMNLP 2020 Findings. [[code](https://github.com/zh-zheng/BERT-QE)] (**BERT-QE**)
- [Cross-lingual Retrieval for Iterative Self-Supervised Training.](https://arxiv.org/pdf/2006.09526.pdf) *Chau Tran et.al.* NIPS 2020. [[code](https://github.com/pytorch/fairseq/tree/master/examples/criss)] (**CRISS**)
<!-- - [A Linguistic Study on Relevance Modeling in Information Retrieval.](https://arxiv.org/pdf/2103.00956.pdf) *Yixing Fan, Jiafeng Guo et.al.* WWW 2021. (**Prob & Intervention**) -->
- [Generalizing Discriminative Retrieval Models using Generative Tasks.]() *Bingsheng Liu, Hamed Zamani et.al.* WWW 2021. (**GDMTL,joint discriminative and generative model with multitask learning**)


### Design new pre-training tasks for reranking
- [PROP: Pre-training with Representative Words Prediction for Ad-hoc Retrieval.](https://arxiv.org/pdf/2010.10137.pdf) *Xinyu Ma et.al.* WSDM 2021. [[code](https://github.com/Albert-Ma/PROP)] (**PROP**)
- [Cross-lingual Language Model Pretraining for Retrieval.]() *Puxuan Yu et.al.* WWW 2021. 
- [B-PROP: Bootstrapped Pre-training with Representative Words Prediction for Ad-hoc Retrieval.](https://arxiv.org/pdf/2104.09791.pdf) *Xinyu Ma et.al.* SIGIR 2021. [[code](https://github.com/Albert-Ma/PROP)] (**B-PROP**)

### Modify on top of the existing pre-trained models
- [Local Self-Attention over Long Text for Efficient Document Retrieval.](https://arxiv.org/pdf/2005.04908.pdf) *Sebastian Hofstätter et.al.* SIGIR 2020 short. [[code](https://github.com/sebastian-hofstaetter/transformer-kernel-ranking)] (**TKL:Transformer-Kernel for long text**)
- [The Cascade Transformer: an Application for Efficient Answer Sentence Selection.](https://arxiv.org/pdf/2005.02534.pdf) *Luca Soldaini et.al.* ACL 2020.[[code](https://github.com/alexa/wqa-cascade-transformers)] (**Cascade Transformer**)
- [Using Prior Knowledge to Guide BERT’s Attention in Semantic Textual Matching Tasks.](https://arxiv.org/pdf/2102.10934.pdf) *Tingyu Xia et.al.* WWW 2021.[[code](https://github.com/xiatingyu/Bert_sim)] (**Text Matching: Guide BERT's Attention**)


## Multimodal Retrieval

### Unified Single-stream Architecture
- [Unicoder-VL: A Universal Encoder for Vision and Language by Cross-modal Pre-training.](https://arxiv.org/pdf/1908.06066.pdf) *Gen Li, Nan Duan et.al.* AAAI 2020.  [[code](https://github.com/microsoft/Unicoder)] (**Unicoder-VL**)
- [XGPT: Cross-modal Generative Pre-Training for Image Captioning.](https://arxiv.org/pdf/2003.01473.pdf) *Qiaolin Xia, Haoyang Huang, Nan Duan et.al.* Arxiv 2020.  [[code](https://github.com/microsoft/Unicoder)] (**XGPT**)
- [UNITER: UNiversal Image-TExt Representation Learning.](https://arxiv.org/pdf/1909.11740.pdf) *Yen-Chun Chen, Linjie Li et.al.* ECCV 2020.  [[code](https://github.com/ChenRocks/UNITER)] (**UNITER**)
- [Oscar: Object-Semantics Aligned Pre-training for Vision-Language Tasks.](https://arxiv.org/pdf/2004.06165.pdf) *Xiujun Li, Xi Yin et.al.* ECCV 2020.  [[code](https://github.com/microsoft/Oscar)] (**Oscar**)
- [VinVL: Making Visual Representations Matter in Vision-Language Models.](https://arxiv.org/pdf/2101.00529.pdf) *Pengchuan Zhang, Xiujun Li et.al.* ECCV 2020.  [[code](https://github.com/microsoft/Oscar)] (**VinVL**)


### Multi-stream Architecture Applied on Input
- [ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks.](https://arxiv.org/pdf/1908.02265.pdf) *Jiasen Lu, Dhruv Batra et.al.* NeurIPS 2019.  [[code](https://github.com/facebookresearch/vilbert-multi-task)] (**VilBERT**)
- [12-in-1: Multi-Task Vision and Language Representation Learning.](https://arxiv.org/pdf/1912.02315.pdf) *Jiasen Lu, Dhruv Batra et.al.* CVPR 2020.  [[code](https://github.com/facebookresearch/vilbert-multi-task)] (**A multi-task model based on VilBERT**)
- [Learning Transferable Visual Models From Natural Language Supervision.](https://arxiv.org/pdf/2103.00020.pdf) *Alec Radford et.al.* CVPR 2020.  [[code](https://github.com/OpenAI/CLIP)] (**CLIP, GPT team**)
- [ERNIE-ViL: Knowledge Enhanced Vision-Language Representations Through Scene Graph.](https://arxiv.org/pdf/2006.16934.pdf) *Fei Yu, Jiji Tang et.al.* Arxiv 2020. [[code](https://github.com/PaddlePaddle/ERNIE/tree/repro/ernie-vil)]  (**ERNIE-ViL，1st place on the VCR leaderboard**)
- [M6-v0: Vision-and-Language Interaction for Multi-modal Pretraining.](https://arxiv.org/pdf/2003.13198.pdf) *Junyang Lin, An Yang et.al.* KDD 2020.  (**M6-v0/InterBERT**)
- [M3P: Learning Universal Representations via Multitask Multilingual Multimodal Pre-training.](https://arxiv.org/pdf/2006.02635.pdf) *Haoyang Huang, Lin Su et.al.* CVPR 2021. [[code](https://github.com/microsoft/M3P)]  (**M3P, MILD dataset**)


## Other Resources

### Some Retrieval Toolkits
- [Faiss: a library for efficient similarity search and clustering of dense vectors](https://github.com/facebookresearch/faiss)
- [Pyserini: a Python Toolkit to Support Sparse and Dense Representations](https://github.com/castorini/pyserini/)
- [MatchZoo: a library consisting of many popular neural text matching models](https://github.com/NTMC-Community/MatchZoo)

### Other Resources About Pre-trained Models in NLP
- [Pre-trained Models for Natural Language Processing: A Survey.](https://arxiv.org/abs/2003.08271) *Xipeng Qiu et.al.* 
- [BERT-related-papers](https://github.com/tomohideshibata/BERT-related-papers)
- [Pre-trained Languge Model Papers from THU-NLP](https://github.com/thunlp/PLMpapers)

### Surveys About Efficient Transformers
- [Efficient Transformers: A Survey.](https://arxiv.org/pdf/2009.06732.pdf) *Yi Tay, Mostafa Dehghani et.al.* Arxiv 2020. 

