# HSE FCS Multimodal Modals Course

Course materials for the “Multimodal Models” course at HSE Faculty of Computer Science: lectures, notebooks, and homework assignments.

## Course authors and lecturers

Boris Zhestkov

Albina Burlova


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

Late policy: 0.1 points per day, capped at −0.7 for that homework.  
Re-submissions are allowed until the hard deadline; the latest counts.

All deadlines are MSK 23:59.

| HW  | Task              |         Release |           Soft |             Hard |
| --- |-------------------|----------------:|---------------:|-----------------:|
| HW1 | CLAP→CLIP adapter |  Tue 11 Nov | Fri 21 Nov |   Fri 28 Nov |
| HW2 | MLLM captioning   |  Fri 21 Nov | Tue 02 Dec |   Mon 08 Dec |
| HW3 | VQA with RAG      |  Tue 02 Dec | Tue 16 Dec |   Fri 19 Dec |

## Grading

**Final grade:** `0.3 * HW1 + 0.3 * HW2 + 0.4 * HW3`
