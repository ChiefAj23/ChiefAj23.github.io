---
layout: page
title: Academic Text Summarizer
description: Lightweight transformer-based web application for summarizing academic and technical documents.
img: assets/img/Academic-Text-Summarizer-Arch.png
importance: 2
category: Research
---

<p align="justify"> In this project, we present a lightweight AI-powered web application for generating concise and coherent summaries of academic texts, research papers, technical articles, and scholarly documentation. The system is designed to support graduate students, researchers, and knowledge workers who regularly process large volumes of written material and need a faster way to distill key ideas. Built using <b>Python</b>, <b>Hugging Face Transformers</b>, <b>PyTorch</b>, and <b>Gradio</b>, the application provides an accessible browser-based interface for abstractive text summarization while remaining simple enough for local execution and offline use. </p>

<p align="justify"> The summarization engine is powered by the <b>sshleifer/distilbart-cnn-12-6</b> model, a distilled version of BART fine-tuned for high-quality summarization tasks. By leveraging transformer-based sequence-to-sequence learning, the system produces fluent and compact summaries from longer academic passages, helping reduce the manual effort involved in reviewing papers and extracting their main contributions. The application also supports local model storage, allowing users to download and run the model directly from disk for faster repeated inference and improved usability in low-connectivity or privacy-sensitive environments. </p>

<p align="justify"> A key strength of this project is its focus on practicality and accessibility. Rather than building a complex research framework, the system offers a streamlined end-to-end workflow in which users can launch the Gradio interface, paste or provide academic text, and instantly receive a summarized output in the browser. This makes the tool especially useful for literature review, concept familiarization, note preparation, and rapid comprehension of technical material. Overall, the project demonstrates how modern transformer models can be deployed in a lightweight and user-friendly format to improve research productivity and reduce the cognitive burden of academic reading. </p>

Implementation of entire project can be found here: <a href="https://github.com/ChiefAj23/AcademicTextSummarizer"> Code </a>