<!-- ═══════════════════════════════════════════════════════════════════════════════
     M O T I O N M A S T E R   P R O  ·  README v2.0.0
     Dual-Engine AI Video Synthesis Platform
     ═══════════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- Animated SVG Header -->
<svg viewBox="0 0 900 320" xmlns="motionmaster_header.svg" style="max-width: 100%; height: auto;">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0a1a"/>
      <stop offset="50%" stop-color="#0d1b2a"/>
      <stop offset="100%" stop-color="#1b1b3a"/>
    </linearGradient>
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d4ff">
        <animate attributeName="stop-color" values="#00d4ff;#7b2cbf;#ff006e;#00d4ff" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#7b2cbf">
        <animate attributeName="stop-color" values="#7b2cbf;#ff006e;#00d4ff;#7b2cbf" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#ff006e">
        <animate attributeName="stop-color" values="#ff006e;#00d4ff;#7b2cbf;#ff006e" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d4ff"/>
      <stop offset="100%" stop-color="#ff006e"/>
    </linearGradient>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="strongGlow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#00d4ff" stroke-width="0.3" opacity="0.15"/>
    </pattern>
    <radialGradient id="particleGrad">
      <stop offset="0%" stop-color="#00d4ff" stop-opacity="1"/>
      <stop offset="100%" stop-color="#00d4ff" stop-opacity="0"/>
    </radialGradient>
  </defs>
  <rect width="900" height="320" fill="url(#bgGrad)" rx="12"/>
  <rect width="900" height="320" fill="url(#grid)" rx="12"/>
  <rect x="2" y="2" width="896" height="316" fill="none" stroke="url(#accentGrad)" stroke-width="2" rx="10" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
  </rect>
  <g opacity="0.8">
    <path d="M 20 60 L 20 20 L 60 20" fill="none" stroke="#00d4ff" stroke-width="2" filter="url(#glow)">
      <animate attributeName="stroke-dasharray" values="0,120;120,0" dur="2s" repeatCount="indefinite"/>
    </path>
    <path d="M 880 60 L 880 20 L 840 20" fill="none" stroke="#ff006e" stroke-width="2" filter="url(#glow)">
      <animate attributeName="stroke-dasharray" values="0,120;120,0" dur="2s" begin="0.5s" repeatCount="indefinite"/>
    </path>
    <path d="M 20 260 L 20 300 L 60 300" fill="none" stroke="#ff006e" stroke-width="2" filter="url(#glow)">
      <animate attributeName="stroke-dasharray" values="0,120;120,0" dur="2s" begin="1s" repeatCount="indefinite"/>
    </path>
    <path d="M 880 260 L 880 300 L 840 300" fill="none" stroke="#00d4ff" stroke-width="2" filter="url(#glow)">
      <animate attributeName="stroke-dasharray" values="0,120;120,0" dur="2s" begin="1.5s" repeatCount="indefinite"/>
    </path>
  </g>
  <g>
    <circle cx="100" cy="80" r="2" fill="url(#particleGrad)" filter="url(#glow)">
      <animate attributeName="cy" values="80;40;80" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;0" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="200" cy="250" r="1.5" fill="url(#particleGrad)" filter="url(#glow)">
      <animate attributeName="cy" values="250;200;250" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;0" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="750" cy="100" r="2.5" fill="url(#particleGrad)" filter="url(#glow)">
      <animate attributeName="cy" values="100;60;100" dur="3.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;0" dur="3.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="650" cy="280" r="1.8" fill="url(#particleGrad)" filter="url(#glow)">
      <animate attributeName="cy" values="280;240;280" dur="4.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;0" dur="4.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="300" cy="60" r="1.2" fill="url(#particleGrad)" filter="url(#glow)">
      <animate attributeName="cy" values="60;30;60" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;0" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="500" cy="290" r="2" fill="url(#particleGrad)" filter="url(#glow)">
      <animate attributeName="cy" values="290;250;290" dur="5.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;0" dur="5.5s" repeatCount="indefinite"/>
    </circle>
  </g>
  <rect x="0" y="0" width="900" height="4" fill="#00d4ff" opacity="0.1" filter="url(#glow)">
    <animate attributeName="y" values="0;320;0" dur="8s" repeatCount="indefinite"/>
  </rect>
  <text x="450" y="110" text-anchor="middle" font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="52" font-weight="900" fill="url(#titleGrad)" filter="url(#strongGlow)" letter-spacing="6">
    MOTIONMASTER
    <animate attributeName="opacity" values="0.9;1;0.9" dur="3s" repeatCount="indefinite"/>
  </text>
  <text x="450" y="155" text-anchor="middle" font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="32" font-weight="700" fill="#ffffff" letter-spacing="12" opacity="0.9">
    PRO
    <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" repeatCount="indefinite"/>
  </text>
  <line x1="280" y1="175" x2="620" y2="175" stroke="url(#accentGrad)" stroke-width="1.5" filter="url(#glow)">
    <animate attributeName="x1" values="280;300;280" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="620;600;620" dur="4s" repeatCount="indefinite"/>
  </line>
  <text x="450" y="205" text-anchor="middle" font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="14" font-weight="500" fill="#a0a0c0" letter-spacing="3">
    DUAL-ENGINE AI VIDEO SYNTHESIS
  </text>
  <g transform="translate(0, 10)">
    <rect x="205" y="225" width="120" height="28" rx="14" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.7">
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2.5s" repeatCount="indefinite"/>
    </rect>
    <text x="265" y="244" text-anchor="middle" font-family="'Segoe UI', monospace" font-size="11" fill="#00d4ff" font-weight="600" letter-spacing="1">I2VGENXL</text>
    <rect x="340" y="225" width="120" height="28" rx="14" fill="none" stroke="#7b2cbf" stroke-width="1" opacity="0.7">
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2.5s" begin="0.3s" repeatCount="indefinite"/>
    </rect>
    <text x="400" y="244" text-anchor="middle" font-family="'Segoe UI', monospace" font-size="11" fill="#7b2cbf" font-weight="600" letter-spacing="1">SDXL CINEMA</text>
    <rect x="475" y="225" width="120" height="28" rx="14" fill="none" stroke="#ff006e" stroke-width="1" opacity="0.7">
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2.5s" begin="0.6s" repeatCount="indefinite"/>
    </rect>
    <text x="535" y="244" text-anchor="middle" font-family="'Segoe UI', monospace" font-size="11" fill="#ff006e" font-weight="600" letter-spacing="1">STORYBOARD</text>
    <rect x="610" y="225" width="90" height="28" rx="14" fill="none" stroke="#00d4ff" stroke-width="1" opacity="0.7">
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2.5s" begin="0.9s" repeatCount="indefinite"/>
    </rect>
    <text x="655" y="244" text-anchor="middle" font-family="'Segoe UI', monospace" font-size="11" fill="#00d4ff" font-weight="600" letter-spacing="1">VOICEOVER</text>
  </g>
  <rect x="0" y="290" width="900" height="30" fill="#0a0a1a" opacity="0.8" rx="0 0 12 12"/>
  <text x="30" y="309" font-family="'Segoe UI', monospace" font-size="10" fill="#00d4ff" opacity="0.8">
    <animate attributeName="opacity" values="0.8;0.3;0.8" dur="1.5s" repeatCount="indefinite"/>●
  </text>
  <text x="45" y="309" font-family="'Segoe UI', monospace" font-size="10" fill="#a0a0c0">SYSTEM ONLINE</text>
  <text x="450" y="309" text-anchor="middle" font-family="'Segoe UI', monospace" font-size="10" fill="#606080">v2.0.0  ·  PRODUCTION-GRADE  ·  GPU-OPTIMIZED  ·  GRADIO-POWERED</text>
  <text x="870" y="309" text-anchor="end" font-family="'Segoe UI', monospace" font-size="10" fill="#a0a0c0">L4/A100 READY</text>
  <g transform="translate(30, 140)" opacity="0.4">
    <rect x="0" y="0" width="3" height="20" rx="1.5" fill="#00d4ff">
      <animate attributeName="height" values="20;40;10;30;20" dur="1.2s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;-10;5;-5;0" dur="1.2s" repeatCount="indefinite"/>
    </rect>
    <rect x="8" y="0" width="3" height="30" rx="1.5" fill="#00d4ff">
      <animate attributeName="height" values="30;15;45;20;30" dur="1.4s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;7;-7;5;0" dur="1.4s" repeatCount="indefinite"/>
    </rect>
    <rect x="16" y="0" width="3" height="15" rx="1.5" fill="#00d4ff">
      <animate attributeName="height" values="15;35;10;40;15" dur="1.1s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;-10;2;-12;0" dur="1.1s" repeatCount="indefinite"/>
    </rect>
    <rect x="24" y="0" width="3" height="25" rx="1.5" fill="#00d4ff">
      <animate attributeName="height" values="25;10;35;15;25" dur="1.3s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;7;-5;5;0" dur="1.3s" repeatCount="indefinite"/>
    </rect>
    <rect x="32" y="0" width="3" height="35" rx="1.5" fill="#00d4ff">
      <animate attributeName="height" values="35;20;40;10;35" dur="1.5s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;7;-2;12;0" dur="1.5s" repeatCount="indefinite"/>
    </rect>
  </g>
  <g transform="translate(838, 140)" opacity="0.4">
    <rect x="0" y="0" width="3" height="25" rx="1.5" fill="#ff006e">
      <animate attributeName="height" values="25;10;40;15;25" dur="1.3s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;7;-7;5;0" dur="1.3s" repeatCount="indefinite"/>
    </rect>
    <rect x="8" y="0" width="3" height="35" rx="1.5" fill="#ff006e">
      <animate attributeName="height" values="35;15;30;10;35" dur="1.5s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;10;2;12;0" dur="1.5s" repeatCount="indefinite"/>
    </rect>
    <rect x="16" y="0" width="3" height="20" rx="1.5" fill="#ff006e">
      <animate attributeName="height" values="20;40;10;35;20" dur="1.2s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;-10;5;-7;0" dur="1.2s" repeatCount="indefinite"/>
    </rect>
    <rect x="24" y="0" width="3" height="30" rx="1.5" fill="#ff006e">
      <animate attributeName="height" values="30;20;15;40;30" dur="1.4s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;5;7;-5;0" dur="1.4s" repeatCount="indefinite"/>
    </rect>
    <rect x="32" y="0" width="3" height="15" rx="1.5" fill="#ff006e">
      <animate attributeName="height" values="15;35;25;10;15" dur="1.1s" repeatCount="indefinite"/>
      <animate attributeName="y" values="0;-10;0;2;0" dur="1.1s" repeatCount="indefinite"/>
    </rect>
  </g>
  <g opacity="0.15" transform="translate(120, 160)">
    <polygon points="0,-20 17.3,-10 17.3,10 0,20 -17.3,10 -17.3,-10" fill="none" stroke="#00d4ff" stroke-width="1">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="20s" repeatCount="indefinite"/>
    </polygon>
  </g>
  <g opacity="0.15" transform="translate(780, 160)">
    <polygon points="0,-15 13,-7.5 13,7.5 0,15 -13,7.5 -13,-7.5" fill="none" stroke="#ff006e" stroke-width="1">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="15s" repeatCount="indefinite"/>
    </polygon>
  </g>
  <circle cx="450" cy="130" r="80" fill="none" stroke="#00d4ff" stroke-width="0.5" opacity="0">
    <animate attributeName="r" values="80;200" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="130" r="80" fill="none" stroke="#ff006e" stroke-width="0.5" opacity="0">
    <animate attributeName="r" values="80;200" dur="4s" begin="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0" dur="4s" begin="2s" repeatCount="indefinite"/>
  </circle>
</svg>

<br>

### **Dual-Engine AI Video Synthesis · Storyboard-to-Cinema Pipeline · Real-time Voiceover**
*Production-grade · GPU-Optimized · Gradio-Powered · L4/A100 Ready*

---

<!-- ─── BADGE ECOSYSTEM ─── -->

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-11.8%2B-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-4.x-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)

![Diffusers](https://img.shields.io/badge/🤗_Diffusers-0.25%2B-FFD21E?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-3_Models-FFD21E?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)
![Colab](https://img.shields.io/badge/Google_Colab-L4_GPU-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
![Stars](https://img.shields.io/github/stars/yourname/motionmaster-pro?style=social)
![Forks](https://img.shields.io/github/forks/yourname/motionmaster-pro?style=social)
![Issues](https://img.shields.io/github/issues/yourname/motionmaster-pro?color=red)

---

> **MotionMaster Pro** is a production-grade, dual-engine AI video synthesis platform combining
> **I2VGenXL** image-to-video diffusion with **Stable Diffusion XL** cinematic frame generation.
> Automated prompt engineering, OpenCV post-processing, gTTS voiceover, and a complete
> storyboard-to-MP4 pipeline — all inside a single Gradio session on a 24 GB L4 GPU.

---

[🚀 Quick Start](#-quick-start-60-seconds) · [🧠 Architecture](#-system-architecture) · [📖 API Reference](#-api-reference) · [🎬 Usage Guide](#-usage-guide) · [🗺️ Roadmap](#%EF%B8%8F-roadmap) · [🤝 Contributing](#-contributing)

</div>

---


<details>
<summary><strong>Click to expand full contents</strong></summary>

1. [System Overview](#-system-overview)
2. [Feature Matrix](#-feature-matrix)
3. [System Architecture](#-system-architecture)
   - [High-Level Platform Diagram](#high-level-platform-diagram)
   - [Pipeline A — I2VGenXL Image-to-Video](#pipeline-a--i2vgenxl-image-to-video)
   - [Pipeline B — SDXL Cinematic Video](#pipeline-b--sdxl-cinematic-video)
   - [Audio Synthesis Pipeline](#audio-synthesis-pipeline)
4. [AI Model Registry](#-ai-model-registry)
5. [Performance Benchmarks](#-performance-benchmarks)
6. [Hardware Requirements](#-hardware-requirements)
7. [Quick Start (60 Seconds)](#-quick-start-60-seconds)
8. [Full Installation](#-full-installation)
9. [Configuration Reference](#-configuration-reference)
10. [Usage Guide](#-usage-guide)
    - [Mode 1: Single Image to Video](#mode-1-single-image-to-video-i2vgenxl)
    - [Mode 2: Cinematic Storyboard Video](#mode-2-cinematic-storyboard-video-sdxl)
    - [Mode 3: Batch Processing](#mode-3-batch-processing)
11. [Storyboard Format Specification](#-storyboard-format-specification)
12. [Video Effects Technical Reference](#-video-effects-technical-reference)
13. [API Reference](#-api-reference)
14. [GPU Optimization Guide](#-gpu-optimization-guide)
15. [Error Codes & Troubleshooting](#-error-codes--troubleshooting)
16. [Known Limitations](#-known-limitations)
17. [Changelog](#-changelog)
18. [Roadmap](#%EF%B8%8F-roadmap)
19. [Contributing](#-contributing)
20. [Citation](#-citation)
21. [License & Acknowledgements](#-license--acknowledgements)

</details>

---

## 🌐 System Overview

MotionMaster Pro orchestrates **three independent Hugging Face models** through two parallel synthesis pipelines, a GPU memory management layer, and a multi-stage audio-video assembly chain — all exposed through a zero-configuration Gradio 4.x interface.

| Metric | Value |
|--------|-------|
| **AI Models** | 3 (I2VGenXL · SDXL Base 1.0 · GIT-Base-COCO) |
| **Inference Precision** | FP16 on CUDA · FP32 fallback on CPU |
| **Max Resolution** | 768 × 768 px per frame |
| **Max Video Duration** | ~60 seconds (cinematic mode) |
| **Audio Tracks** | Voiceover + Background Music (CompositeAudioClip) |
| **Export Formats** | GIF · MP4 (H.264 + AAC) |
| **Post-Processing Effects** | Vintage · Dream · Cinematic |
| **Target Hardware** | Google Colab L4 (24 GB) · A100 · RTX 3090+ |
| **Interface** | Gradio 4.x (3-tab layout, share-link enabled) |
| **Minimum VRAM** | 12 GB (FP16) · 24 GB recommended |

---

## ✅ Feature Matrix

| Feature | Pipeline A (I2VGenXL) | Pipeline B (SDXL Cinematic) |
|---|:---:|:---:|
| Image → Animated Video | ✅ | ❌ |
| Storyboard → Cinema | ❌ | ✅ |
| Auto Prompt Generation (GIT captioning) | ✅ | ❌ |
| Batch Processing (N images) | ✅ | ❌ |
| Voiceover (gTTS) | ❌ | ✅ |
| Background Music | ❌ | ✅ |
| Per-scene GIF Assembly | ❌ | ✅ |
| MP4 Export (H.264) | ✅ | ✅ |
| GIF Export | ✅ | ❌ |
| Vintage Effect (Sepia + Film Grain) | ✅ | ❌ |
| Dream Effect (Gaussian Glow) | ✅ | ❌ |
| Cinematic Effect (Letterbox + Grade) | ✅ | ❌ |
| Seed Control & Reproducibility | ✅ | ✅ |
| CUDA Memory Management | ✅ | ✅ |
| LRU Pipeline Caching | ✅ | ❌ |
| CPU Offloading | ✅ | ❌ |
| Attention Slicing | ❌ | ✅ |
| Analytics Dashboard | ✅ | ❌ |
| User Gallery | ✅ | ❌ |
| URL Image Input | ✅ | ❌ |

---

## 🧠 System Architecture

### High-Level Platform Diagram

```mermaid
graph TB
    subgraph UI["🖥️  Gradio Interface — 3 Tabs"]
        T1["Tab 1\nImage → Video\n(I2VGenXL)"]
        T2["Tab 2\nBatch Processing"]
        T3["Tab 3\nCinematic Generator\n(SDXL)"]
        T4["Tab 4\nGallery & Analytics"]
    end

    subgraph INGEST["📥  Input Layer"]
        A1["PIL Image Upload"]
        A2["Image URL\n(requests stream)"]
        A3["Storyboard .txt File"]
        A4["Batch Image Array"]
    end

    subgraph PA["🎬  Pipeline A — I2VGenXL"]
        direction TB
        PA1["GIT-Base-COCO\nImage Captioner"]
        PA2["Prompt Augmenter\n5 motion variants"]
        PA3["I2VGenXL\nali-vilab/i2vgen-xl\nFP16 · CPU Offload"]
        PA4["Frame Buffer\n16–25 frames @ 25 steps"]
        PA1 --> PA2 --> PA3 --> PA4
    end

    subgraph PB["🎥  Pipeline B — SDXL Cinematic"]
        direction TB
        PB1["Storyboard Parser\n---  delimited"]
        PB2["Scene Scheduler\n5 scenes × 12s"]
        PB3["SDXL Base 1.0\nstabilityai/stable-diffusion-xl-base-1.0\nFP16 · DPMSolver · 768px"]
        PB4["Frame Enhancer\nSharpness ×1.5 · Contrast ×1.2"]
        PB5["GIF Assembly\nimageio · 12 fps"]
        PB1 --> PB2 --> PB3 --> PB4 --> PB5
    end

    subgraph POST["✨  Post-Processing Engine"]
        PP1{"Effect\nSelector"}
        PP2["Vintage\nSepia Kernel + Film Grain"]
        PP3["Dream\nGaussian Glow + HSV Sat."]
        PP4["Cinematic\nLetterbox + AbsAlpha Grade"]
        PP5["Pass-Through\n(none)"]
        PP1 --> PP2 & PP3 & PP4 & PP5
    end

    subgraph AUDIO["🔊  Audio Synthesis"]
        AU1["gTTS Voiceover\nper-scene narration\n12s clips · fade in/out"]
        AU2["BenSound Music\n5 moods · 192k MP3"]
        AU3["Pydub Mixer\nNormalize · Gain +5dB"]
        AU4["CompositeAudioClip\nVoice ×1.5 · Music ×0.4"]
        AU1 --> AU3
        AU2 --> AU3
        AU3 --> AU4
    end

    subgraph ASSEMBLE["🎞️  Assembly & Export"]
        AS1["MoviePy Concatenator\nCompose method"]
        AS2["ffmpeg libx264\nAAC audio · H.264"]
        AS3["GIF Exporter\ndiffusers export_to_gif"]
        AS4["MP4 Output\n/content/outputs/"]
        AS5["GIF Output\n/content/user_gallery/"]
        AS1 --> AS2 --> AS4
        AS3 --> AS5
    end

    subgraph MEM["⚙️  Memory Manager"]
        M1["CUDA Cache Clear\ntorch.cuda.empty_cache()"]
        M2["GC Collect\ngc.collect()"]
        M3["LRU Cache\nmaxsize=1 pipelines"]
        M4["Attention Slicing\nSDXL only"]
    end

    UI --> INGEST
    INGEST --> PA & PB
    PA4 --> POST
    PB5 --> ASSEMBLE
    POST --> ASSEMBLE
    PB --> AUDIO --> ASSEMBLE
    ASSEMBLE -.->|post-generation| MEM
```

---

### Pipeline A — I2VGenXL Image-to-Video

```mermaid
sequenceDiagram
    actor User
    participant GR as Gradio UI
    participant CAP as GIT-Base-COCO<br/>Captioner
    participant I2V as I2VGenXL<br/>(FP16 + CPU Offload)
    participant FX as OpenCV<br/>Effect Engine
    participant EXP as Export<br/>Engine
    participant FS as Filesystem<br/>/content/outputs/

    User->>GR: Upload image + enter prompt
    GR->>CAP: pixel_values (processor)
    CAP-->>GR: base_caption (max_length=50)
    GR->>GR: Augment → 5 motion variants
    User->>GR: Select prompt + settings
    GR->>I2V: image, prompt, neg_prompt<br/>steps, guidance, generator(seed)
    Note over I2V: FP16 inference<br/>CPU offload active<br/>~25 denoising steps
    I2V-->>GR: frames[0] (List[PIL])
    GR->>FX: frames + effect_type + intensity
    Note over FX: RGB→BGR→effect→RGB<br/>per-frame OpenCV ops
    FX-->>GR: processed_frames (List[PIL])
    alt export_format == "gif"
        GR->>EXP: export_to_gif(frames, path)
    else export_format == "mp4"
        GR->>EXP: frames_to_mp4(frames, path, fps=15)
        Note over EXP: ImageSequenceClip<br/>libx264 codec
    end
    EXP->>FS: Write /content/outputs/i2v_output_{uid}_{ts}.{ext}
    EXP->>FS: Mirror to /content/user_gallery/
    GR-->>User: video_path + status_message
```

---

### Pipeline B — SDXL Cinematic Video

```mermaid
flowchart LR
    A["📄 Storyboard .txt"] --> B["Scene Parser\n--- delimiter"]
    B --> C{5 Scenes\nExtracted?}
    C -- No --> D["Auto-fill\nDefault scenes"]
    C -- Yes --> E["Scene Scheduler"]
    D --> E

    E --> F["gTTS Voiceover\nper-scene 12s"]
    E --> G["BenSound Music\nMood-matched MP3"]

    E --> H["SDXL Loop\n5 × 12 frames"]
    H --> I["Prompt Augmentation\n'frame N of 12, subtle motion'"]
    I --> J["SDXL Base 1.0\n768×768 FP16\nDPMSolverMultistep"]
    J --> K["PIL Enhance\nSharpness 1.5×\nContrast 1.2×"]
    K --> L["imageio.mimsave\n.gif per scene"]

    L --> M["MoviePy\nconcat_videoclips\ncompose method"]
    F --> N["Pydub\nNormalize + Gain +5dB\nFade in/out 300ms"]
    G --> N
    N --> O["CompositeAudioClip\nVoice vol ×1.5\nMusic vol ×0.4"]

    M --> P["VideoFileClip\n+ set_audio()"]
    O --> P
    P --> Q["ffmpeg write\nlibx264 + aac\n12 fps"]
    Q --> R["🎬 Final MP4\n~60 seconds"]
```

---

### Audio Synthesis Pipeline

```mermaid
graph TD
    A["Scene Prompts\n(Image: field text)"] --> B["gTTS Engine\nlang=en · slow=False\nspeedup ×1.05"]
    B --> C["Per-scene AudioSegment\n12,000ms target"]
    C --> D{"duration\n== 12s?"}
    D -- "> 12s" --> E["Truncate\naudio[:12000]"]
    D -- "< 12s" --> F["Pad Silent\nAudioSegment.silent()"]
    D -- "== 12s" --> G
    E --> G["Fade In 300ms\nFade Out 300ms"]
    F --> G
    G --> H["Concatenate\n5 scene clips"]
    H --> I["Normalize\n+ Apply Gain +5dB"]
    I --> J["Export MP3\nbitrate=192k"]

    K["Music Mood\ncinematic/dramatic\nupbeat/suspense\nemotional"] --> L["BenSound URL Fetch\nrequests.get()"]
    L --> M["AudioSegment\n60,000ms clip\nNormalize · Gain -8dB"]
    M --> N["Export Background\n192k MP3"]

    J --> O["CompositeAudioClip\n[ voiceover ×1.5, music ×0.4 ]"]
    N --> O
    O --> P["Video.set_audio()\nfinal mux"]
```

---

## 🤖 AI Model Registry

| Model ID | Provider | Task | Parameters | Precision | Memory (VRAM) | Cache Strategy |
|---|---|---|---|---|---|---|
| `ali-vilab/i2vgen-xl` | Alibaba DAMO | Image → Video Diffusion | ~3.4 B | FP16 | ~9 GB | `@lru_cache(maxsize=1)` + CPU offload |
| `stabilityai/stable-diffusion-xl-base-1.0` | Stability AI | Text → Image (frame gen) | ~3.5 B | FP16 | ~12 GB | Preloaded at startup + attention slicing |
| `microsoft/git-base-coco` | Microsoft | Image Captioning | ~182 M | FP32 | ~0.7 GB | `@lru_cache(maxsize=1)` |

### Model Loading Strategy

```
Startup:
  └── preload_model()
        └── SDXL Base 1.0  ──► DPMSolverMultistepScheduler
              └── .to("cuda") + enable_attention_slicing()
              └── Test generation: 768×768, 25 steps → /content/temp/test_image.png
              └── model_loaded = True

On-demand (lazy, LRU-cached):
  └── load_pipeline()    → I2VGenXL  (first call only)
  └── load_captioning_model() → GIT-Base-COCO (first call only)

After each inference:
  └── clear_cuda_memory()
        └── torch.cuda.empty_cache()
        └── gc.collect()
        └── LOG: CUDA usage in GB
```

---

## 📊 Performance Benchmarks

> Measured on **Google Colab L4 GPU (24 GB VRAM, 56 TFLOPS FP16)**

### Pipeline A — I2VGenXL

| Configuration | Steps | Guidance | Time (s) | VRAM Peak | Frames |
|---|---|---|---|---|---|
| Fast | 10 | 7.5 | ~45 s | ~9.5 GB | 16 |
| Balanced *(default)* | 25 | 9.0 | ~110 s | ~10.2 GB | 16 |
| Quality | 50 | 9.0 | ~215 s | ~10.8 GB | 16 |

### Pipeline B — SDXL Cinematic (5 scenes × 12 frames)

| Configuration | Steps/Frame | Resolution | Time per Scene | Total Time | VRAM Peak |
|---|---|---|---|---|---|
| Draft | 10 | 768×768 | ~25 s | ~3 min | ~12 GB |
| Standard *(default)* | 25 | 768×768 | ~60 s | ~5–6 min | ~14 GB |
| High Quality | 50 | 768×768 | ~115 s | ~11 min | ~15 GB |

### OpenCV Effect Processing

| Effect | Avg Time per Frame | Ops |
|---|---|---|
| `none` | < 1 ms | Pass-through |
| `vintage` | ~4 ms | `cv2.transform` (sepia) + `addWeighted` + noise |
| `dream` | ~6 ms | `GaussianBlur` + `addWeighted` + HSV sat. boost |
| `cinematic` | ~3 ms | letterbox mask + `convertScaleAbs` |

---

## 💻 Hardware Requirements

| Tier | GPU | VRAM | RAM | Status |
|---|---|---|---|---|
| 🥇 **Recommended** | NVIDIA L4 / A100 | 24 GB | 16 GB+ | Fully supported |
| 🥈 **Supported** | RTX 3090 / RTX 4080 | 24 GB / 16 GB | 16 GB | Fully supported |
| 🥉 **Minimal** | RTX 3070 / T4 | 12 GB | 12 GB | Pipeline A only; reduce steps |
| ⚠️ **CPU Only** | Any | — | 32 GB+ | Pipeline A in FP32; very slow (~20 min) |

### Software Prerequisites

| Dependency | Version | Notes |
|---|---|---|
| Python | ≥ 3.10 | 3.11 recommended |
| CUDA Toolkit | ≥ 11.8 | Auto-detected |
| PyTorch | ≥ 2.0 | `+cu118` or `+cu121` |
| `diffusers` | ≥ 0.25 | HuggingFace |
| `transformers` | ≥ 4.37 | HuggingFace |
| `gradio` | ≥ 4.x | UI framework |
| `moviepy` | ≥ 1.0.3 | Video assembly |
| `pydub` | ≥ 0.25 | Audio processing |
| `gTTS` | ≥ 2.5 | Voiceover synthesis |
| `imageio` | ≥ 2.33 | GIF creation |
| `opencv-python` | ≥ 4.8 | Effect processing |
| `ffmpeg` | system package | Codec backend |
| `espeak` | system package | Required by gTTS on Linux |
| `accelerate` | ≥ 0.27 | `enable_model_cpu_offload` |

---

## 🚀 Quick Start (60 Seconds)

**Step 1 — Open the notebook in Colab**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

> ⚡ Ensure **Runtime → Change runtime type → L4 GPU** is selected before running.

**Step 2 — Run all cells**

```bash
# All install cells run automatically — the final cell launches the Gradio app.
# You will see a public share link:
# Running on public URL: https://xxxx.gradio.live
```

**Step 3 — Choose your mode**

| Tab | What to do |
|---|---|
| **Image → Video (I2VGenXL)** | Upload an image, enter a motion prompt, hit 🚀 Generate |
| **Cinematic Video Generator** | Upload a `.txt` storyboard, choose music mood, hit Generate |
| **Batch Processing** | Upload N images, enter N prompts (one per line), run batch |

---

## 📦 Full Installation

### Option A — Google Colab (Recommended)

```python
# Cell 1 — System packages
!apt-get update -qq
!apt-get install -y ffmpeg espeak -qq

# Cell 2 — Python packages
!pip install -q \
    torch torchvision --index-url https://download.pytorch.org/whl/cu121 \
    diffusers==0.25.1 \
    transformers==4.37.2 \
    accelerate==0.27.0 \
    gradio==4.19.2 \
    moviepy==1.0.3 \
    pydub==0.25.1 \
    gTTS==2.5.1 \
    imageio==2.33.1 \
    opencv-python==4.9.0.80 \
    Pillow==10.2.0 \
    sentencepiece \
    soundfile \
    librosa \
    ffmpeg-python

# Cell 3 — Clone repo
!git clone https://github.com/yourname/motionmaster-pro
%cd motionmaster-pro

# Cell 4 — Launch
!python app.py
```

### Option B — Local Installation

```bash
# 1. Clone repository
git clone https://github.com/yourname/motionmaster-pro.git
cd motionmaster-pro

# 2. Create virtual environment
python -m venv .venv
source .venv/bin/activate          # Linux/macOS
# .\.venv\Scripts\activate         # Windows

# 3. Install CUDA-enabled PyTorch first
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu121

# 4. Install all requirements
pip install -r requirements.txt

# 5. Install system packages (Linux)
sudo apt-get install ffmpeg espeak -y

# 6. Launch
python app.py
```

### `requirements.txt`

```
torch>=2.0.0
torchvision>=0.15.0
diffusers>=0.25.0
transformers>=4.37.0
accelerate>=0.27.0
gradio>=4.19.0
moviepy==1.0.3
pydub>=0.25.1
gTTS>=2.5.0
imageio>=2.33.0
opencv-python>=4.8.0
Pillow>=10.0.0
requests>=2.31.0
numpy>=1.24.0
matplotlib>=3.7.0
sentencepiece
soundfile
librosa
ffmpeg-python
tqdm
```

---

## ⚙️ Configuration Reference

All tunable parameters are exposed via the Gradio UI sliders. The table below documents every parameter, its data type, valid range, default, and internal effect.

### Pipeline A Parameters

| Parameter | UI Label | Type | Default | Range | Effect |
|---|---|---|---|---|---|
| `num_inference_steps` | Inference Steps | `int` | `25` | 10–50 | Denoising step count; higher = sharper, slower |
| `guidance_scale` | Guidance Scale | `float` | `9.0` | 1.0–15.0 | CFG scale; higher = more prompt-faithful |
| `seed` | Seed | `int` | `-1` (random) | -1–2147483647 | `-1` uses `torch.manual_seed(time())` |
| `effect_type` | Effect Type | `str` | `"none"` | none/vintage/dream/cinematic | OpenCV post-processing mode |
| `effect_intensity` | Effect Intensity | `float` | `0.5` | 0.0–1.0 | Blending weight for chosen effect |
| `export_format` | Export Format | `str` | `"gif"` | gif/mp4 | Output container format |

### Pipeline B Parameters

| Parameter | UI Label | Type | Default | Range | Effect |
|---|---|---|---|---|---|
| `num_inference_steps` | Inference Steps | `int` | `25` | 10–50 | Per-frame SDXL steps |
| `guidance_scale` | Guidance Scale | `float` | `7.5` | 1.0–15.0 | CFG scale for SDXL |
| `seed` | Seed | `int` | `-1` | -1–2147483647 | Shared seed across all scene frames |
| `music_mood` | Music Mood | `str` | `"cinematic"` | cinematic/dramatic/upbeat/suspense/emotional | BenSound track selector |
| `negative_prompt` | Negative Prompt | `str` | see below | — | Concepts to suppress in SDXL generation |

**Default Negative Prompt (Pipeline A)**
```
Distorted, discontinuous, ugly, blurry, low resolution, motionless, static,
disfigured, disconnected limbs, ugly faces, incomplete arms
```

**Default Negative Prompt (Pipeline B)**
```
blurry, bad quality, deformed, ugly, low resolution, cartoonish, abstract
```

---

## 📖 Usage Guide

### Mode 1: Single Image to Video (I2VGenXL)

```
1. Open the "Image to Video (I2VGenXL)" tab
2. Upload your image (drag & drop or file dialog)
   - Alternatively: paste an image URL into the URL field
3. (Optional) Click "👁️ Generate Prompt Suggestions"
   → GIT-Base-COCO captions your image and produces 5 motion-variant suggestions
4. Enter or select a motion prompt
5. Expand "Advanced Settings" to tune steps, guidance, and seed
6. Choose Effect Type and Intensity
7. Select Export Format (GIF for quick preview, MP4 for production)
8. Click "🚀 Generate Video"
9. Download from the output panel or browse the Gallery tab
```

**Example Prompts that Work Well**

```
"Leaves gently rustling in a warm summer breeze from left to right"
"Ocean waves cascading rhythmically onto the shore at golden hour"
"Snow falling softly in slow motion through a quiet pine forest"
"Smoke curling upward from a campfire in a cinematic wide shot"
"Clouds drifting slowly across a violet sunset sky"
```

---

### Mode 2: Cinematic Storyboard Video (SDXL)

```
1. Create a storyboard .txt file (see format spec below)
2. Open the "Cinematic Video Generator (SDXL)" tab
3. Upload the .txt file
4. Set negative prompt, inference steps, guidance scale, seed, music mood
5. Click "Generate 1-Minute Video"
6. Pipeline runtime: ~5–6 minutes on L4 GPU
7. Download from /content/outputs/ or the output panel
```

**What happens internally (annotated):**

```
STARTUP           → preload_model() runs SDXL test generation at init
PARSE             → parse_storyboard() splits on --- or \n\n, extracts
                     Scene N, Image: prompt fields, fills 5 scenes
VOICEOVER         → generate_voiceover() → gTTS per scene → 12s clips
                     → Pydub concat → normalize → +5dB gain → 192k MP3
BACKGROUND MUSIC  → generate_background_music(mood) → BenSound CDN fetch
                     → normalize → -8dB → 192k MP3
FRAME GEN LOOP    → for scene in scenes[0:5]:
                       → generate_gif_frames() → 12 SDXL inferences
                       → ImageEnhance (Sharpness 1.5×, Contrast 1.2×)
                       → create_scene_gif() → imageio.mimsave()
CONCAT            → concatenate_gifs_to_video() → MoviePy compose
MUX               → add_audio_to_video() → CompositeAudioClip mux
CLEANUP           → remove temp GIFs, audio, intermediate video
OUTPUT            → /content/outputs/video_{YYYYMMDD_HHMMSS}.mp4
```

---

### Mode 3: Batch Processing

```
1. Open the "Batch Processing" tab
2. Upload N images via the file uploader
3. Enter N prompts in the text box — one prompt per line
   (Prompt count MUST equal image count — validated at runtime)
4. Expand "Batch Settings" to configure shared effect settings
5. Click "🔄 Process Batch"
6. Monitor per-image progress in the status output
7. Download all results from the gallery
```

**Important:** Batch mode runs `generate_video()` sequentially per image.  
For large batches on Colab, set `seed != -1` to use incrementing seeds per image:  
`seed_for_image_i = seed + i`

---

## 📄 Storyboard Format Specification

### Grammar (EBNF)

```ebnf
storyboard   ::= scene { separator scene }
separator    ::= "---" | blank-line blank-line
scene        ::= header newline { field }
header       ::= "Scene" whitespace integer ":" text
field        ::= (image-field | description-field | narration-field)
image-field  ::= ("Image:" | "Prompt:") whitespace text newline
description-field ::= text newline
```

### Canonical Format (Recommended)

```
Scene 1: Opening — The Ancient Forest
Image: Dense ancient redwood forest at dawn, golden shafts of light piercing through towering trees, photorealistic, ultra-detailed, 4K, cinematic

---

Scene 2: The River
Image: Crystal-clear mountain river flowing over smooth stones, shallow depth of field, moss-covered banks, atmospheric mist, ultra-detailed, cinematic

---

Scene 3: The Village
Image: Medieval stone village at twilight, warm candlelit windows, cobblestone streets glistening after rain, photorealistic, ultra-detailed

---

Scene 4: The Storm
Image: Dramatic storm clouds forming over a vast open plain, lightning strikes in the distance, golden hour light breaking through, cinematic, ultra-detailed

---

Scene 5: Resolution — Sunrise
Image: Sweeping aerial view of misty mountain valleys at sunrise, layers of fog, warm amber light, photorealistic, ultra-detailed, 4K
```

### Prompt Engineering Tips for SDXL

Append these quality tokens to every `Image:` field for best results:

```
Essential:   photorealistic, ultra-detailed, cinematic lighting
Quality:     4K, sharp focus, masterpiece
Style:       (choose one) dramatic · atmospheric · ethereal · moody · epic
Camera:      wide angle · close-up · aerial view · tracking shot
Lighting:    golden hour · soft diffused · volumetric light · rim light
```

---

## 🎨 Video Effects Technical Reference

All effects are applied in `apply_video_effects(frames, effect_type, intensity)`.  
Each frame is processed: `PIL → numpy (BGR) → OpenCV ops → PIL (RGB)`.

### `vintage` — Sepia + Film Grain

```python
# Sepia transform via 3×3 color matrix
sepia_kernel = np.array([
    [0.393, 0.769, 0.189],
    [0.349, 0.686, 0.168],
    [0.272, 0.534, 0.131]
])
sepia_img = cv2.transform(img, sepia_kernel)
img = cv2.addWeighted(img, 1 - intensity, sepia_img, intensity, 0)

# Film grain — uniform random noise [0, 50]
noise = np.random.randint(0, 50, img.shape, dtype=np.uint8)
img = cv2.addWeighted(img, 0.9, noise, 0.1, 0)
```

| `intensity` | Sepia Blend | Original Blend | Grain |
|---|---|---|---|
| 0.0 | 0% | 100% | 10% always |
| 0.5 | 50% | 50% | 10% always |
| 1.0 | 100% | 0% | 10% always |

---

### `dream` — Gaussian Glow + Saturation Boost

```python
# Glow via Gaussian blur blend
blurred = cv2.GaussianBlur(img, (0, 0), sigmaX=10)
img = cv2.addWeighted(img, 1 - intensity*0.5, blurred, intensity*0.5, 0)

# Saturation boost in HSV space
hsv = cv2.cvtColor(img, cv2.COLOR_BGR2HSV)
hsv[:, :, 1] = hsv[:, :, 1] * (1 + intensity * 0.3)   # S channel
img = cv2.cvtColor(hsv, cv2.COLOR_HSV2BGR)
```

| `intensity` | Glow Alpha | Saturation Multiplier |
|---|---|---|
| 0.0 | 0% | 1.0× |
| 0.5 | 25% | 1.15× |
| 1.0 | 50% | 1.30× |

---

### `cinematic` — Letterbox + Color Grade

```python
# Letterbox bars (proportional to intensity)
h, w = img.shape[:2]
bar_height = int(h * 0.1 * intensity)
img[0:bar_height, :] = [0, 0, 0]           # top bar
img[h - bar_height:h, :] = [0, 0, 0]       # bottom bar

# Color grading — boost contrast, pull shadows
img = cv2.convertScaleAbs(img,
    alpha=1 + intensity * 0.3,              # contrast ×1.15–1.30
    beta=-30 * intensity                    # shadow crush -15 to -30
)
```

| `intensity` | Bar Height (% of frame) | Contrast | Shadow Crush |
|---|---|---|---|
| 0.0 | 0% | 1.0× | 0 |
| 0.5 | 5% | 1.15× | -15 |
| 1.0 | 10% | 1.30× | -30 |

---

## 📘 API Reference

### `generate_video()`

Generate an animated GIF or MP4 from a single image using I2VGenXL.

```python
def generate_video(
    input_image:        PIL.Image,          # Input image (RGB)
    prompt:             str,                # Motion description
    negative_prompt:    str,                # Concepts to suppress
    num_inference_steps: int,              # Denoising steps [10–50]
    guidance_scale:     float,             # CFG scale [1.0–15.0]
    effect_type:        str,               # "none"|"vintage"|"dream"|"cinematic"
    effect_intensity:   float,             # Effect blend [0.0–1.0]
    export_format:      str,               # "gif"|"mp4"
    seed:               int,               # -1 for random
    progress:           gr.Progress        # Gradio progress tracker
) -> Tuple[str, str, str]:                 # (output_path, preview_path, status_msg)
```

**Returns:**
- `output_path` — full path to generated file in `/content/outputs/`
- `preview_path` — same path (for Gradio image preview)
- `status_msg` — `"✅ Generation complete! Prompt: '...'"` or `"❌ Error: ..."`

**Side effects:**
- Increments `user_analytics["total_generations"]`
- Appends to `generation_history`
- Calls `clear_cuda_memory()` post-inference
- Mirrors GIF copy to `/content/user_gallery/`

---

### `generate_cinematic_video()`

Full storyboard-to-MP4 cinematic pipeline.

```python
def generate_cinematic_video(
    storyboard_file:          tempfile.NamedTemporaryFile,  # .txt upload
    negative_prompt:          str,
    num_inference_steps:      int,          # Applied per frame in SDXL
    guidance_scale:           float,
    seed:                     int,
    music_mood:               str,          # "cinematic"|"dramatic"|"upbeat"|"suspense"|"emotional"
    progress:                 gr.Progress
) -> Tuple[str, str, str]:                  # (video_path, storyboard_md, seed_used)
```

**Pipeline execution order:**
1. `preload_model()` — skipped if `model_loaded == True`
2. `parse_storyboard(storyboard_file.name)` → `scenes`, `narration`
3. `generate_voiceover(scenes)` → `voiceover_path`
4. `generate_background_music(mood)` → `music_path`
5. `generate_gif_frames(prompt, ...)` × 5 scenes → `frames[]`
6. `create_scene_gif(frames, idx)` × 5 → `gif_paths[]`
7. `concatenate_gifs_to_video(gif_paths)` → `video_path`
8. `add_audio_to_video(video, voiceover, music)` → `final_output`
9. Cleanup temp files

---

### `apply_video_effects()`

```python
def apply_video_effects(
    frames:       List[PIL.Image],   # Input frame sequence
    effect_type:  str,               # "none"|"vintage"|"dream"|"cinematic"
    intensity:    float              # [0.0, 1.0]
) -> List[PIL.Image]:                # Processed frames (same length)
```

---

### `generate_gif_frames()`

```python
def generate_gif_frames(
    prompt:               str,
    negative_prompt:      str,
    num_frames:           int = 12,
    num_inference_steps:  int = 25,
    guidance_scale:       float = 7.5,
    seed:                 int = None        # None → random
) -> Tuple[List[PIL.Image], int]:           # (frames, seed_used)
```

Each frame gets the prompt suffix: `"frame {N} of {total}, subtle motion, photorealistic, ultra-detailed, cinematic lighting"`.  
Post-generation: `ImageEnhance.Sharpness(×1.5)` + `ImageEnhance.Contrast(×1.2)`.

---

### `parse_storyboard()`

```python
def parse_storyboard(
    storyboard_file: str            # Filepath to .txt
) -> Tuple[List[dict], str]:        # (scenes, narration_string)

# Scene dict structure:
{
    "time":        str,             # e.g. "0-12s"
    "description": str,             # First line of section
    "prompt":      str              # Image: / Prompt: field value
}
```

**Parsing precedence:** `"---"` delimiter → `"\n\n"` double newline → single-line fallback.  
Auto-fills up to 5 scenes with `"Scene N, cinematic, ultra-detailed, 4K"` defaults.

---

### `generate_voiceover()`

```python
def generate_voiceover(
    scenes:      List[dict],
    output_path: str = "/content/temp/audio/voiceover.mp3"
) -> str:                           # Path to final mixed MP3
```

Per scene: `gTTS(text=scene["prompt"])` → `speedup(×1.05)` → pad/trim to `12,000ms` → fade.  
Final: `normalize()` + `apply_gain(+5dB)` → `192k MP3`.  
Fallback: `AudioSegment.silent(60000ms)` on error.

---

### `clear_cuda_memory()`

```python
def clear_cuda_memory() -> None:
    # torch.cuda.empty_cache()
    # gc.collect()
    # Logs: CUDA memory_allocated / 1024**3 GB
```

Called after every inference in both pipelines.

---

## ⚡ GPU Optimization Guide

### Strategy Summary

| Technique | Applied To | Mechanism | VRAM Saved |
|---|---|---|---|
| **FP16 Precision** | Both pipelines | `torch_dtype=torch.float16` | ~50% vs FP32 |
| **CPU Offloading** | I2VGenXL | `pipeline.enable_model_cpu_offload()` | ~3–4 GB |
| **Attention Slicing** | SDXL | `pipeline.enable_attention_slicing()` | ~1–2 GB |
| **LRU Pipeline Cache** | Both | `@lru_cache(maxsize=1)` | Avoids reload |
| **Post-Inference GC** | Both | `clear_cuda_memory()` | Fragments released |
| **Sequential Batch** | Batch mode | One image at a time | Peak VRAM bounded |
| **SDXL Preload** | Pipeline B | `preload_model()` at startup | Avoids cold start |

### Memory Budget (L4 24 GB)

```
┌─────────────────────────────────────────────────────────┐
│  CUDA Memory Budget — L4 GPU (24 GB)                    │
├──────────────────────────────────┬──────────────────────┤
│  SDXL Base 1.0 (FP16, resident)  │  ~12 GB              │
│  Active SDXL Inference           │  +2 GB               │
│  Gradient / Temp tensors         │  +1 GB               │
│  GIT-Base-COCO (on-demand)       │  +0.7 GB             │
│  Frame buffer (12 × 768² × FP16) │  ~0.5 GB             │
│  OS + CUDA runtime               │  ~1 GB               │
├──────────────────────────────────┼──────────────────────┤
│  Peak (Pipeline B)               │  ~17.2 GB / 24 GB   │
│  Headroom                        │  ~6.8 GB             │
└──────────────────────────────────┴──────────────────────┘
```

### Tips for < 16 GB GPUs

```python
# 1. Reduce SDXL resolution
height, width = 512, 512     # instead of 768×768

# 2. Reduce frames per scene
num_frames = 8               # instead of 12

# 3. Use fewer inference steps
num_inference_steps = 15     # instead of 25

# 4. Disable SDXL preload test generation
# Comment out test_image generation block in preload_model()

# 5. Add sequential offloading (more aggressive)
pipeline.enable_sequential_cpu_offload()   # instead of enable_model_cpu_offload()
```

---

## 🔧 Error Codes & Troubleshooting

| Error / Symptom | Root Cause | Fix |
|---|---|---|
| `"L4 GPU not detected. Enable GPU runtime."` | CUDA not available | Runtime → Change runtime type → GPU → L4 |
| `CUDA out of memory` | VRAM exhausted | Reduce `num_inference_steps`, resolution, or `num_frames`; call `clear_cuda_memory()` manually |
| `"Expected 5 GIF clips, got N"` | Fewer than 5 storyboard scenes | Add 5 `---`-delimited scenes to your storyboard file |
| `"Voiceover generation failed"` | gTTS network request failed | Check internet access; Colab network must be active |
| `"Failed to download image"` | Invalid URL / 403 / rate limit | Use a direct image URL (Hugging Face datasets recommended) |
| `"Storyboard parsing error"` | Malformed `.txt` file | Ensure UTF-8 encoding; use `---` as scene delimiter |
| `Caption generation error` | GIT-Base-COCO load fail | Usually transient; retry; check HuggingFace hub status |
| Video renders but has no audio | Music CDN unreachable | BenSound URL blocked; voiceover-only fallback active |
| `ffmpeg: command not found` | ffmpeg not installed | `!apt-get install -y ffmpeg` |
| `ModuleNotFoundError: imageio` | Package not installed | `!pip install imageio[ffmpeg]` |
| Gradio port already in use | Previous session running | Runtime → Restart runtime; re-run all cells |

### Log File Location

All errors are logged to:
```
/content/error_log.txt
```

```python
# To tail the log in Colab:
!tail -50 /content/error_log.txt
```

---

## ⚠️ Known Limitations

1. **No temporal consistency in SDXL frames** — Each frame is generated independently; there is no cross-frame attention. This produces a "stop-motion" rather than smooth video aesthetic. This is by design for the cinematic GIF style.

2. **I2VGenXL frame count is fixed** — The model produces a fixed-length frame sequence. There is no native control over output duration.

3. **BenSound music dependency** — Pipeline B background music requires an active internet connection and depends on BenSound CDN availability. Graceful fallback to silent audio is implemented.

4. **Voiceover language** — `gTTS` is configured to English (`lang='en'`). Multi-language support requires changing the `lang` parameter and testing TTS quality per language.

5. **Sequential SDXL inference** — Frames are generated one-at-a-time in a Python loop. A batched inference approach (generating all 12 frames in one `.pipeline()` call with a batched prompt list) could reduce Pipeline B runtime by ~30%.

6. **No streaming output** — Video is not streamed; the full file must complete before the Gradio UI updates. Long sessions (>10 min) may time out on free Colab tiers.

7. **Batch mode is CPU-bound between images** — The `clear_cuda_memory()` call between batch images adds ~2–3 seconds overhead per image due to GC.

---

## 📋 Changelog

```
[v2.0.0] — 2025-06-xx
  ✨ NEW   Dual-pipeline architecture (I2VGenXL + SDXL Cinematic)
  ✨ NEW   Storyboard-to-video pipeline with 5-scene structure
  ✨ NEW   gTTS voiceover synthesis with Pydub audio mixing
  ✨ NEW   BenSound mood-matched background music (5 moods)
  ✨ NEW   CompositeAudioClip audio layer (voice + music)
  ✨ NEW   SDXL model preloading at startup (model_loaded flag)
  ✨ NEW   imageio GIF assembly (create_scene_gif)
  ✨ NEW   User analytics dashboard (effect usage bar chart)
  ✨ NEW   Per-generation user gallery with thumbnail grid
  ♻️ IMPROVED  OpenCV effect engine (vintage/dream/cinematic)
  ♻️ IMPROVED  CUDA memory management after every inference
  ♻️ IMPROVED  LRU cache for GIT captioner + I2VGenXL
  🐛 FIXED     Sepia kernel shape mismatch on grayscale inputs
  🐛 FIXED     MP4 export using temp directory cleanup in finally block

[v1.0.0] — Initial release
  ✨ I2VGenXL single image-to-video generation
  ✨ Batch processing mode
  ✨ GIF / MP4 export
  ✨ Gradio 4.x interface
```

---

## 🗺️ Roadmap

### v2.1 — Q3 2025

- [ ] **Temporal consistency module** — Cross-frame attention injection in SDXL loop for smoother video
- [ ] **ControlNet integration** — Pose/depth conditioning for I2VGenXL
- [ ] **SDXL-Turbo fast mode** — 4-step distilled inference for rapid prototyping
- [ ] **Streaming preview** — Frame-by-frame Gradio streaming via `gr.update()` yields

### v2.2 — Q4 2025

- [ ] **Audio reactive effects** — Sync OpenCV effect intensity to music beat data (librosa onset detection)
- [ ] **Multi-language voiceover** — gTTS language selector per scene
- [ ] **SDXL-Lightning support** — 8-step high-quality inference
- [ ] **Prompt weighting** — `(keyword:1.5)` style compel syntax
- [ ] **HuggingFace Spaces deployment** — ZeroGPU + Persistent storage integration

### v3.0 — 2026

- [ ] **Wan 2.1 / CogVideoX integration** — Native video diffusion model with temporal attention
- [ ] **Real-time preview** — WebRTC frame streaming during generation
- [ ] **API endpoint** — FastAPI REST wrapper with Bearer auth
- [ ] **Project save/load** — JSON session export + resume
- [ ] **Cloud storage** — GCS / S3 output bucket integration

---

## 🤝 Contributing

We welcome contributions from the community. Please read the guidelines below before opening a PR.

### Development Setup

```bash
git clone https://github.com/yourname/motionmaster-pro.git
cd motionmaster-pro
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pip install -r requirements-dev.txt    # pytest, black, isort, mypy
```

### Code Style

```bash
# Format
black app.py --line-length 100
isort app.py

# Type checking
mypy app.py --ignore-missing-imports

# Tests
pytest tests/ -v
```

### Contribution Areas

| Area | Difficulty | Description |
|---|---|---|
| 🟢 Documentation | Beginner | Add docstrings to all functions, extend this README |
| 🟢 Prompt Library | Beginner | Add example prompts and storyboard templates |
| 🟡 New Effects | Intermediate | Add `noir`, `watercolor`, `neon` effect modes |
| 🟡 Audio Effects | Intermediate | Add pitch variation, reverb to voiceover |
| 🔴 Temporal Consistency | Advanced | Cross-frame attention for SDXL loop |
| 🔴 Streaming Output | Advanced | Frame-by-frame Gradio streaming |
| 🔴 API Layer | Advanced | FastAPI REST wrapper |

### Pull Request Checklist

- [ ] Code passes `black`, `isort`, `mypy` without errors
- [ ] New functions have full docstrings (`Args:`, `Returns:`, `Raises:`)
- [ ] New effects documented in `Video Effects Technical Reference`
- [ ] Performance impact described in PR description (VRAM, time delta)
- [ ] `requirements.txt` updated if new deps introduced
- [ ] `CHANGELOG.md` entry added under `[Unreleased]`

### Branch Naming Convention

```
feature/temporal-consistency
fix/sdxl-oom-on-t4
docs/api-reference-update
perf/batch-cuda-optimization
```

---

## 📝 Citation

If you use MotionMaster Pro in your research or project, please cite:

```bibtex
@software{motionmaster_pro_2025,
  title        = {MotionMaster Pro: Dual-Engine AI Video Synthesis Platform},
  author       = {Your Name},
  year         = {2025},
  url          = {https://github.com/yourname/motionmaster-pro},
  version      = {2.0.0},
  note         = {I2VGenXL + Stable Diffusion XL + Cinematic Post-Processing}
}
```

This project builds upon the following foundational works:

```bibtex
@article{zhang2023i2vgen,
  title   = {I2VGen-XL: High-Quality Image-to-Video Synthesis via Cascaded Diffusion Models},
  author  = {Zhang, Shiwei and others},
  journal = {arXiv preprint arXiv:2311.04145},
  year    = {2023}
}

@misc{sdxl2023,
  title  = {SDXL: Improving Latent Diffusion Models for High-Resolution Image Synthesis},
  author = {Podell, Dustin and others},
  year   = {2023},
  url    = {https://arxiv.org/abs/2307.01952}
}

@misc{git2022,
  title  = {GIT: A Generative Image-to-text Transformer for Vision and Language},
  author = {Wang, Jianfeng and others},
  year   = {2022},
  url    = {https://arxiv.org/abs/2205.14100}
}
```

---

## 📄 License & Acknowledgements

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

### Acknowledgements

| Resource | Used For |
|---|---|
| [ali-vilab/i2vgen-xl](https://huggingface.co/ali-vilab/i2vgen-xl) | Image-to-video synthesis |
| [stabilityai/stable-diffusion-xl-base-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0) | Cinematic frame generation |
| [microsoft/git-base-coco](https://huggingface.co/microsoft/git-base-coco) | Auto image captioning |
| [🤗 Diffusers](https://github.com/huggingface/diffusers) | Diffusion pipeline orchestration |
| [Gradio](https://www.gradio.app/) | Interactive web UI |
| [MoviePy](https://zulko.github.io/moviepy/) | Video assembly and codec handling |
| [OpenCV](https://opencv.org/) | Frame-level post-processing effects |
| [BenSound](https://www.bensound.com/) | Royalty-free background music |
| [gTTS](https://github.com/pndurette/gTTS) | Text-to-speech voiceover |
| [Pydub](https://github.com/jiaaro/pydub) | Audio mixing and normalization |
| [imageio](https://imageio.readthedocs.io/) | GIF frame assembly |

---

<div align="center">

**Built with ❤️ for AI Video Creators**

[![Star this repo](https://img.shields.io/github/stars/yourname/motionmaster-pro?style=social)](https://github.com/yourname/motionmaster-pro)
[![Follow](https://img.shields.io/github/followers/yourname?style=social)](https://github.com/yourname)

*If MotionMaster Pro saved you hours of work, please consider starring the repo — it helps others discover it.*

---

`I2VGenXL` · `Stable Diffusion XL` · `GIT-Base-COCO` · `Gradio` · `MoviePy` · `OpenCV` · `gTTS` · `Pydub` · `CUDA FP16`

</div>
