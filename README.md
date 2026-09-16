# Marzieh Babaali

**PhD Researcher** · University of Isfahan  
NLP & Generative AI — Persian RAG, question answering, virtual try-on, and multimodal AI (text · image · video · voice)

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=eOcempcAAAAJ&hl=en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marzieh-babaali-75934266)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-2209-9745)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:babaalimarzieh@gmail.com)

I build **published research datasets and models** plus **runnable Kaggle demos** (Gradio UIs, bundled sample data, free GPU/CPU tier) so others can reproduce and try my work quickly.

---

## Featured Projects

| | Project | Highlights |
|:---:|---------|------------|
| 📊 | **[FSQD](https://github.com/mahsamb/FSQD)** | Fine-Grained Question Subjectivity Dataset — 10,000 annotated questions · [PLOS ONE 2024](https://doi.org/10.1371/journal.pone.0301696) |
| 📄 | **[SCRQD](https://github.com/mahsamb/SCRQD)** | Subjective Comparative Relation Quintuples + SCRQE model · [PLOS ONE 2025](https://doi.org/10.1371/journal.pone.0319824) |
| 🤖 | **[persian-pdf-rag-kaggle](https://github.com/mahsamb/persian-pdf-rag-kaggle)** | Persian/English PDF RAG chatbot — multilingual-e5, FAISS, Qwen2.5-3B, Gradio UI |
| 👓 | **[virtual-glasses-tryon-kaggle](https://github.com/mahsamb/virtual-glasses-tryon-kaggle)** | Eyeglasses virtual try-on — MediaPipe Face Mesh + rembg, runs on Kaggle CPU |
| 📈 | **[chartqa-self-refining-vlm-kaggle](https://github.com/mahsamb/chartqa-self-refining-vlm-kaggle)** | Chart QA with inference-time self-reflection — Qwen2-VL-2B, ChartQA-H, no finetuning |

---

## Publications

| Year | Paper | Venue | Code / Data |
|------|-------|-------|-------------|
| 2025 | [SCRQE: Subjective comparative relation quintuple extraction from questions in product domain](https://doi.org/10.1371/journal.pone.0319824) | PLOS ONE | [SCRQD](https://github.com/mahsamb/SCRQD) |
| 2024 | [Creating and validating the Fine-Grained Question Subjectivity Dataset (FQSD)](https://doi.org/10.1371/journal.pone.0301696) | PLOS ONE | [FSQD](https://github.com/mahsamb/FSQD) |
| 2024 | [Aspect extraction with enriching word representation and post-processing rules](https://doi.org/10.1016/j.eswa.2024.124174) | Expert Systems with Applications | — |

---

## Research Repositories

- **[FSQD](https://github.com/mahsamb/FSQD)** — Fine-Grained Question Subjectivity Dataset (10,000 annotated questions)
- **[SCRQD](https://github.com/mahsamb/SCRQD)** — Subjective Comparative Relation Quintuples Dataset & SCRQE model

---

## LLM & Chatbots

- **[persian-pdf-rag-kaggle](https://github.com/mahsamb/persian-pdf-rag-kaggle)** — Persian/English PDF RAG chatbot on Kaggle free GPU (multilingual-e5, FAISS, Qwen2.5-3B, Gradio UI, bundled demo PDFs)
- **[persian-products-elasticsearch-kaggle](https://github.com/mahsamb/persian-products-elasticsearch-kaggle)** — Persian fashion catalog hybrid search with Elasticsearch (BM25 + multilingual embeddings, bundled demo data)
- **[persian-chatbot-kaggle](https://github.com/mahsamb/persian-chatbot-kaggle)** — Persian chatbot on Kaggle free GPU (Qwen2.5-3B-Instruct, 4-bit, Gradio UI, no API token)
- **[ollama-mcp-assistant](https://github.com/mahsamb/ollama-mcp-assistant)** — Local document Q&A with Ollama via FastMCP (Persian answers, Streamlit + browser UI, bundled demo context)

---

## Generative AI Projects

### Text-to-Image

- **[krea2-kaggle](https://github.com/mahsamb/krea2-kaggle)** — Krea 2 text-to-image on free Kaggle GPU (Gradio app, CPU offloading for 12B model on T4)
- **[sdxl-kaggle](https://github.com/mahsamb/sdxl-kaggle)** — SDXL / SDXL-Turbo text-to-image on Kaggle (fast few-step generation)

### Text-to-Video

- **[text-to-video-kaggle](https://github.com/mahsamb/text-to-video-kaggle)** — ModelScope 1.7B text-to-video on Kaggle (256×256, Gradio UI)
- **[zeroscope-kaggle](https://github.com/mahsamb/zeroscope-kaggle)** — Zeroscope v2 576w text-to-video on Kaggle (576×320 widescreen, Gradio UI)

### Image-to-Video

- **[image-to-video-kaggle](https://github.com/mahsamb/image-to-video-kaggle)** — Stable Video Diffusion XT on Kaggle (animate a still image, Gradio UI)
- **[image-story-to-video-kaggle](https://github.com/mahsamb/image-story-to-video-kaggle)** — CogVideoX image + story paragraph → video on Kaggle (720×480, Gradio UI)

### Video Question Answering

- **[video-question-answering-kaggle](https://github.com/mahsamb/video-question-answering-kaggle)** — Video-LLaVA-7B video QA on Kaggle (upload a clip, ask questions, Gradio UI, 4-bit on T4)

### Visual Reasoning

- **[chartqa-self-refining-vlm-kaggle](https://github.com/mahsamb/chartqa-self-refining-vlm-kaggle)** — inference-time self-reflection for chart QA on Kaggle (Qwen2-VL-2B, ChartQA-H, initial → critique → refined answer, no finetuning)

### Voice & Face

- **[liveportrait-kaggle](https://github.com/mahsamb/liveportrait-kaggle)** — LivePortrait portrait animation from driving video on Kaggle (Gradio UI, Pexels demo inputs)
- **[family-photo-animator-kaggle](https://github.com/mahsamb/family-photo-animator-kaggle)** — colorize, restore, and animate old family photos on Kaggle (DDColor + CodeFormer + LivePortrait)
- **[sadtalker-lipsync-kaggle](https://github.com/mahsamb/sadtalker-lipsync-kaggle)** — SadTalker audio-driven talking-head lip-sync on Kaggle (Gradio UI, bundled demo portrait + speech)
- **[wav2lip-persian-kaggle](https://github.com/mahsamb/wav2lip-persian-kaggle)** — Wav2Lip Persian visual dubbing on Kaggle (edge-tts Farsi voices, Gradio UI, bundled demo audio)
- **[portrait-background-replacement-kaggle](https://github.com/mahsamb/portrait-background-replacement-kaggle)** — RobustVideoMatting portrait background swap on Kaggle (fast + precision notebooks, Pexels demo inputs, preserves audio)
- **[rvc-voice-conversion-kaggle](https://github.com/mahsamb/rvc-voice-conversion-kaggle)** — RVC speech-to-speech voice conversion on Kaggle (Gradio UI)
- **[face-swap-kaggle](https://github.com/mahsamb/face-swap-kaggle)** — InsightFace video face swap on Kaggle (Gradio UI, preserves audio)

### 3D & Product Photography

- **[triposr-3d-kaggle](https://github.com/mahsamb/triposr-3d-kaggle)** — single product photo → 3D mesh (.obj) with TripoSR on Kaggle (Gradio Model3D viewer, demo product image)
- **[zero123plus-multiview-kaggle](https://github.com/mahsamb/zero123plus-multiview-kaggle)** — product photo → 6 novel views with Zero123++ on Kaggle (Gradio UI, demo product image)

### Fashion & Segmentation

- **[persian-product-image-description-kaggle](https://github.com/mahsamb/persian-product-image-description-kaggle)** — Persian fashion catalog descriptions from product photos on Kaggle (SmolVLM + mT5; single-image + Excel batch notebooks, demo sample data)
- **[virtual-lip-makeup-kaggle](https://github.com/mahsamb/virtual-lip-makeup-kaggle)** — virtual lip makeup with MediaPipe Face Landmarker on Kaggle CPU (Gradio UI, demo portraits)

### Virtual Try-On

- **[virtual-glasses-tryon-kaggle](https://github.com/mahsamb/virtual-glasses-tryon-kaggle)** — eyeglasses overlay with MediaPipe Face Mesh + rembg on Kaggle CPU (Gradio UI)
- **[virtual-jewelry-necklaces-kaggle](https://github.com/mahsamb/virtual-jewelry-necklaces-kaggle)** — necklace try-on with MediaPipe Face Landmarker on Kaggle CPU (procedural demo necklaces)
- **[virtual-jewelry-earrings-kaggle](https://github.com/mahsamb/virtual-jewelry-earrings-kaggle)** — earring try-on with MediaPipe Face Landmarker on Kaggle CPU
- **[virtual-clothing-tryon-kaggle](https://github.com/mahsamb/virtual-clothing-tryon-kaggle)** — IDM-VTON garment try-on on Kaggle free GPU (ipywidgets + Gradio UI)
- **[virtual-hair-tryon-kaggle](https://github.com/mahsamb/virtual-hair-tryon-kaggle)** — hairstyle change with CLIPSeg + Stable Diffusion inpainting on Kaggle GPU (Gradio presets)
- **[virtual-jewelry-rings-kaggle](https://github.com/mahsamb/virtual-jewelry-rings-kaggle)** — ring try-on with MediaPipe Hand Landmarker on Kaggle CPU (procedural + Pexels demo assets)
- **[clothes-segmentation-kaggle](https://github.com/mahsamb/clothes-segmentation-kaggle)** — SegFormer B2 clothing & accessory segmentation on Kaggle (Gradio overlay + legend, bundled Unsplash demo photos)
- **[women-outfit-recommender-kaggle](https://github.com/mahsamb/women-outfit-recommender-kaggle)** — CLIP-based women's outfit recommender with bundled `my_images` demo catalog
- **[women-outfit-recommender-advanced-kaggle](https://github.com/mahsamb/women-outfit-recommender-advanced-kaggle)** — scaled recommender for large fashion catalogs (embedding cache, top-K search, bundled dataset)

---

## Skills

`Python` · `PyTorch` · `Transformers` · `Qwen` · `Qwen2-VL` · `FAISS` · `RAG` · `Elasticsearch` · `SmolVLM` · `CLIP` · `SegFormer` · `Diffusers` · `Stable Diffusion XL` · `Zero123++` · `TripoSR` · `LivePortrait` · `MediaPipe` · `Text-to-Video` · `Image-to-Video` · `Video-LLaVA` · `Video Question Answering` · `ChartQA` · `Visual Reasoning` · `SadTalker` · `Wav2Lip` · `Semantic Segmentation` · `RobustVideoMatting` · `Video Matting` · `Voice Conversion` · `InsightFace` · `Recommendation Systems` · `Gradio` · `Hugging Face` · `Persian NLP` · `NLP` · `Dataset Creation` · `Information Extraction` · `Question Answering` · `Multi-task Learning`

---

## Contact

📧 babaalimarzieh@gmail.com
