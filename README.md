# HSE FCS Multimodal Modals Course

Course materials for the “Multimodal Models” course at HSE Faculty of Computer Science: lectures, notebooks, and homework assignments.

## Syllabus

**week01 · Multimodality Basics**  
- Core notions and problem space: modalities and signals. Representation–alignment–fusion. Typical pipelines. Canonical tasks (retrieval, captioning, VQA, grounding). Brief overview of metrics.

**week02 · Contrastive Learning: CLIP/CLAP & Zero-shot**  
- Dual-encoder objectives. Hard negatives. CLIP (image–text) and CLAP (audio–text). Zero-shot use. Limitations.

**week03 · Unimodal Encoders (Text · Vision · Audio · Video)**  
- Vision: CNN/ViT backbones.  
- Audio: spectrograms/MFCC and basic audio encoders.  
- Video: 3D CNN / ViViT (intro).
- Text: tokenization and compact encoders (brief).

**week04 · Multimodal Fusion & Joint Encoders**  
- Early/late/joint fusion. Cross-modal attention. Tasks: VQA, ITM, grounding, captioning.

**week05 · Generative Multimodal Models**  
- Text to Image generation (incl. Stable Diffusion basics). Captioning stacks and decoding. Reducing hallucinations at a high level.

**week06 · Multimodal LLMs (MLLMs)**  
- Connectors/adapters to LLMs. Frozen vs. instruction-tuned LLMs. RAG for multimodal QA. Thinker-talker. Instruction-tuning, preference optimization in multimodal settings. 

**week07 · Evaluation & Datasets**  
- Benchmarks for VLM/MLLM. Dataset creation basics. Metric limitations and common pitfalls.

## Homeworks & Deadlines

Late policy: 1 point deducted per day late, capped at 7 points per homework.  
Re-submissions are allowed until the hard deadline; the latest counts.

All deadlines are MSK 23:59.

| HW  | Task              |         Release |           Soft |             Hard |
| --- |-------------------|----------------:|---------------:|-----------------:|
| HW1 | CLAP→CLIP adapter |  Sat 15 Nov | Wed 26 Nov |   Sun 30 Nov |
| HW2 | MLLM captioning   |  Thu 27 Nov | Fri 12 Dec |   Tue 16 Dec |
| HW3 | VQA challenge     |  Fri 12 Dec | Fri 19 Dec |   Wed 24 Dec |

## Grading

**Final grade:** `0.3 * HW1 + 0.3 * HW2 + 0.4 * HW3`


## Course authors and lecturers

Boris Zhestkov

Albina Burlova
