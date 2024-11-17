---
layout: post
title: My career so far
subtitle: as a Data Scientist
gh-repo: thbdoux/
tags: [data science, headmind partners ai]
thumbnail-img: /assets/img/headmind-tableau.jpg
comments: true
mathjax: true
author: Thibault Doux
---
At HeadMind Partners AI, I contributed to the development of deep learning solutions for audio processing, LLM-driven applications, and cutting-edge operational research systems. My work spanned from building speech emotion recognition models and meeting summarizers to optimizing supply chains for luxury brands. 

---

<img src="https://join.headmind.com/wp-content/uploads/2021/12/Logo-HeadMind-Partners-PNG-BLEU.png" alt="" style="width:500px; height:auto;" class="center">

## Internship (April 2023 - October 2023)

During my internship at **HeadMind Partners AI & Blockchain**, I focused on innovative research and development projects that combined deep learning and audio processing:

### Speech Emotion Recognition (R&D)
  - Fine-tuned **wav2vec2** and **HuBERT** encoders, adding a fully connected layer for **valence/arousal regression**, achieving **state-of-the-art (SOTA)** results on well-known datasets such as **RAVDESS** and **IEMOCAP**. This project explored the depths of emotional analysis through audio signals.

### Audio Generation and Conversion (R&D)
  - Partially fine-tuned the **Tortoise model** (a blend of **ViT + GPT-2**, with a frozen diffusion model) to generate French speech. The results were somewhat disappointing due to the limited variety in French audio datasets, often featuring a distinct Canadian accent.
  - Fine-tuned a **voice cloning model (RVC)** on multiple voices, including my manager’s, achieving highly realistic cloning. One memorable highlight was pranking a colleague using **real-time voice conversion** over the phone — and it worked brilliantly (shout-out to him for being a good sport)!

---

## Full-Time Data Scientist Role (November 2023 - September 2024)

Upon transitioning to a full-time role, I worked on impactful client missions and pursued further R&D initiatives:

### Supply Chain Optimization for a French Luxury Brand 
  - Can't Say the Name, But It Starts with 'H' and Ends with 'ermès' 🤫
  - Designed and built an optimization solver using **Google OR-Tools**.

<img src="https://avatars.githubusercontent.com/u/65553074?v=4" alt="Google OR-Tools Logo" style="width:80px; height:auto;" class="float-right">

  - Implemented a **multi-objective optimization framework** following the **Pareto optimum paradigm**, optimizing complex trade-offs between objectives. 
  - Leveraged production-ready data from the supply chain, including stocks, historical data, feasibility constraints, and commands.
  - Conducted **hyperparameter optimization** and integrated algorithmic explainability to assist users in selecting hyperparameters and configurations that suited their needs.
  - Established a **real-time connection** with the client's **Snowflake datamart** and deployed the solution on **AWS** using **ECS with a CI/CD pipeline** for automated integration and delivery. Initially deployed using **SageMaker**, we transitioned to **Batch instances** for cost-effective, intensive optimization processes, while storing results in **S3**.
  - The system was successfully used in production for four months, achieving a **30% reduction in combinatorial costs**.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/1200px-Amazon_Web_Services_Logo.svg.png" alt="AWS" style="width:200px; height:auto;" class="center">


### Deepfake Generation
  - Mission for a company from the energy sector.
  - Developed real-time **audio and video deepfake** capabilities using **lip-sync** and **motion transfer** for video, combined with **text-to-speech (TTS)** and **voice conversion** for speech manipulation. This system aimed to raise awareness among executives about potential digital risks.

### Meeting Summarizer with WhisperX, Diarization, and LLMs (R&D)
  - Built a locally deployed meeting summarization system combining **WhisperX** for speech recognition, **diarization and speaker detection**, and **LLMs** for generating summaries and reports using **LangChain** integrated with a locally hosted **Mistral 7B** model (GGUF quantized model). This comprehensive pipeline provided accurate and detailed meeting notes with speaker differentiation and contextual reporting.


<img src="https://d1muf25xaso8hp.cloudfront.net/https%3A%2F%2Fmeta-l.cdn.bubble.io%2Ff1695308256768x626644891139990000%2Fopen-ai.png?w=&h=&auto=compress&dpr=1&fit=max" alt="OpenAI Whisper" style="width:100px; height:auto;" class="left">
<img src="https://cdn.jaimelesstartups.fr/wp-content/uploads/2024/02/Logo%20de%20la%20startup%20Mistral.ai.png" alt="Mistral AI" style="width:200px; height:auto;" class="right">


### Vocal Assistant (R&D)
  - Designed an end-to-end **speech-to-text (STT) + LLM agents + text-to-speech (TTS)** pipeline for a fully experimental vocal assistant. 
  - Integrated **LangChain-based LLM agents** to handle specific functions, including web search, language recognition to provide responses in the appropriate language, and **retrieval-augmented generation (RAG)** with a simple vectorstore for contextual answers.


