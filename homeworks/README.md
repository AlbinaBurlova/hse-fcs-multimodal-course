## Homeworks

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/AlbinaBurlova/hse-fcs-multimodal-course/tree/main/homeworks
)

- HW1: Audio-Text CLAP on AudioCaps
  
Homework focuses on training a CLAP-style audio–text model on the AudioCaps dataset: frozen audio and CLIP text encoders produce embeddings, a linear projection maps audio vectors into the CLIP text space via contrastive loss, and the resulting model is evaluated on an audio retrieval/classification task using accuracy@k against a random baseline.

- HW2: Multimodal Adapter for Qwen3-0.6B

Second homework introduces a multimodal adapter for Qwen3-0.6B: a pretrained audio or vision encoder is kept frozen, its temporal/spatial features are compressed by a small Conv/Linear pooling module into Qwen’s hidden space, and these embeddings are used as a prefix for text generation. The model is trained with teacher forcing on a captioning-style dataset (audio or image descriptions).
