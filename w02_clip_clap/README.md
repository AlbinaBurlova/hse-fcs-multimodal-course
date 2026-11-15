## Week 02 — CLIP/CLAP

### Lecture 2: Contrastive learning, CLIP/CLAP

Lecture introduces contrastive learning as a way to learn representations in a shared embedding space, then uses CLIP as the main case study: image–text architecture, InfoNCE-style training on web-scale image-caption pairs and zero-shot transfer to downstream tasks.

### Seminar 2: Zero-shot with CLIP and CLAP

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlbinaBurlova/hse-fcs-multimodal-course/blob/2026/w02_clip_clap/sem2_CLIP.ipynb)

The seminar uses CLIP and CLAP for zero-shot image and audio classification. We compare prompt templates on CIFAR-100, examine how candidate lists and image crops affect predictions, and study a CLAP error when more classes are added. We then use Qwen3-VL to select labels and describe images and compare sequential and batched inference with vLLM.

### References and materials

- Learning Transferable Visual Models From Natural Language Supervision (CLIP) - [arXiv:2103.00020](https://arxiv.org/abs/2103.00020)  
- Learning a Similarity Metric Discriminatively, with Application to Face Verification - [PDF](http://yann.lecun.com/exdb/publis/pdf/chopra-05.pdf)  
- A Simple Framework for Contrastive Learning of Visual Representations (SimCLR) - [PMLR](https://proceedings.mlr.press/v119/chen20j/chen20j.pdf)  
- The Illustrated SimCLR Framework - [blog post](https://amitness.com/posts/simclr)  
- Debiased Contrastive Learning - [arXiv:2007.00224](https://arxiv.org/abs/2007.00224)  
- Supervised Contrastive Learning - [arXiv:2004.11362](https://arxiv.org/abs/2004.11362)  
- PANNs: Large-Scale Pretrained Audio Neural Networks for Audio Pattern Recognition (CNN14 backbone for audio encoders) - [arXiv:1912.10211](https://arxiv.org/abs/1912.10211)  
- Large-scale Contrastive Language-Audio Pretraining with Feature Fusion and Keyword-to-Caption Augmentation (CLAP) - [arXiv:2211.06687](https://arxiv.org/abs/2211.06687)  
- AudioCLIP: Extending CLIP to Image, Text and Audio - [arXiv:2106.13043](https://arxiv.org/abs/2106.13043)  
- ImageBind: One Embedding Space To Bind Them All --[arXiv:2305.05665](https://arxiv.org/abs/2305.05665)  
- LanguageBind: Extending Video-Language Pretraining to N-Modality by Language-Based Semantic Alignment - [ICLR 2024](https://proceedings.iclr.cc/paper_files/paper/2024/file/2862ccf01e3843c81623b246895bcc45-Paper-Conference.pdf)  
- OmniBind: Large-scale Omni Multimodal Representation via Binding Spaces - [ICLR 2025](https://proceedings.iclr.cc/paper_files/paper/2025/file/358f79dbc9ba5796ddad7e32a275c321-Paper-Conference.pdf)  
- [OpenAI CLIP code and docs](https://github.com/openai/CLIP)
- [CLAP](https://github.com/microsoft/CLAP)
- [LAION CLAP implementation](https://github.com/LAION-AI/CLAP)
- Qwen3-VL [model card](https://huggingface.co/Qwen/Qwen3-VL-2B-Instruct), [Transformers documentation](https://huggingface.co/docs/transformers/v4.57.3/en/model_doc/qwen3_vl)
- [vLLM](https://docs.vllm.ai/en/v0.11.0/examples/offline_inference/vision_language.html)
