---
layout: about
title: About
permalink: /
subtitle: LLM Engineer | ex Moreh, Menlo Research, Viettel

profile:
  align: right
  image: charles.png
  image_circular: false # crops the image to make it circular
  address: >
   

news: true  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---
Hi! I'm Charles 👋 Interested in LLM Systems.

**Industry:**

* Implemented a [pure HIP C++ of OpenAI’s GPT-OSS from scratch](https://github.com/tuanlda78202/gpt-oss-amd), optimizing model loading, multi-streaming, multi-GPU communication, CPU-GPU-SRAM memory access, FlashAttention 2, matrix-core GEMM, MoE load balancing, etc. Achieved 30k TPS (20B) and 10k TPS (120B) on a single node with 8× AMD MI250x GPUs.

* Architected [Leo](https://github.com/tuanlda78202/leo) - an end-to-end LLMOps system for a personal AI assistant, unifying data, feature, training, inference, and observability layers under clean architecture principles. Built offline pipelines for data retrieval, ETL, SFT, and RAG indexing managed by an orchestrator, and designed an agentic RAG-based online system with API integration, MCP support, contextual retrieval, and prompt caching/monitoring.

* Developed a multimodal, multi-agent conversational recommendation system with vision and speech-to-speech interaction; integrated AdaptiveICL, synthetic data generation, retrieval-ranking pipelines with API communication between application and infrastructure layers and **achieved Top 1 in track DSAI at Viettel Digital Talent**.

**Research:**

* My graduation thesis focused on Continual Object Detection, presenting an ["Efficient Continual Detection Transformer"](https://www.linkedin.com/feed/update/urn:li:activity:7209885129920368640/) that utilizes pseudo-labeling, knowledge distillation, and LoRA to achieve superior performance with only 3% of trainable parameters on the COCO dataset, effectively addressing Catastrophic Forgetting and optimizing computational efficiency. My past work includes developing Implicit Neural Representations for video tasks - reconstruction, compression, and in-painting; Medical Image Segmentation for MRI, specifically for rectal cancer diagnosis and treatment.

**Community:**

* Passionate commitment to sharing knowledge and organizing events in the research and developer community is evident. This dedication has resulted in the successful coordination of several key events, such as AI Day 2022, Google I/O Extended Hanoi 2022/2023/2024, Google DevFest Hanoi 2022/2023, IWD x FFE Hanoi 2023, Google Build with AI 2024.
  
* The opportunity to speak at Google DevFest 2022 was an honor for me, where the topic of my presentation was ["Detecting Cheating in Examinations"](https://www.facebook.com/GDGhanoi/photos/a.295913770557546/2473122272836674/).
  * DCE entails researching and deploying a real-time cheating detection solution for 100-person exam rooms; featured on [VTV24](https://www.facebook.com/tintucvtv24/videos/772744667380774), [HUST](https://hust.edu.vn/vi/news/tin-tuc-su-kien/phan-mem-chong-gian-lan-thi-cu-duoc-nhom-sinh-vien-thu-nghiem-thanh-cong-648900.html), [DanTri](https://dantri.com.vn/giao-duc/phan-mem-chong-gian-lan-thi-cu-duoc-nhom-sinh-vien-thu-nghiem-thanh-cong-20220906211003512.htm), etc.
