---
layout: archive
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
  - /projects.html
---
{% include base_path %}
<img src="/images/wordcloud.svg" alt="Word Cloud" style="width: 550%;">

[**TorchBiphasicAxonMapSpatial Model**](https://github.com/pulse2percept/pulse2percept/pull/621) **for Bionic Vision Lab's Pulse-to-Percept Project**

<div style="text-align: center;">
  <img src="/images/p2p_cite.gif" alt="p2p model" style="width: 400px; display: block; margin: auto;">
  <div style="font-size: small; color: gray;">Image Cited From Granley & Beyeler et al., 2021</div>
</div>


A Torch deep learning model of phosphene appearance for Epiretinal Prostheses, based on [Granley & Beyeler et al., 2021](https://ieeexplore.ieee.org/document/9629663)
- Developed a deep learning model for phosphene appearance in epiretinal prostheses, enhancing perceptual accuracy through parameter tunings and torch foward computation, and improving computational efficiency via spatial and temporal scaling algorithms
- Modulated visual perceptions of electrical stimulation on the retina based on exponentially decaying impulse parameters
- Converted models to ONNX format and deployed with ONNX runtime, facilitating models’ availability to CUDA and Nvidia GPUs
- Designed test cases for models using Pytest to ensure the correctness of predictions and optimized runtime for PyTorch models

---

[**Real-time Contextual Object Detection System**](https://github.com/HououinKyouma-2036/Contextual-Object-Detection)

<div style="text-align: center;">
  <img src="/images/291_img2.png" alt="291 image" style="width: 400px; display: block; margin: auto;">
</div>

A system utilized YOLO-NAS and transformer-based visual language models for precise scene understanding, contextual object detection, object localization, and AR marker placement.

- Engineered an object detection system utilizing YOLO-NAS and transformer-based visual language models for precise scene understanding, contextual object detection, and object localization, achieving 89.2% accuracy within 5 seconds
- Architected 4 algorithms for image processing with matrix masks and spatial relationship-based pixel 2D coordinate calculations
- Raycasted 2D coordinates to 3D for precise AR marker placement and developed IOS AR app with Swift, Flask, and Python

---

[**Optical Character Recognition for Font Identification**](https://github.com/Fontier-Team/Font-recognition)
<div style="text-align: center;">
  <img src="/images/fontier_img.png" alt="fontier image" style="width: 500px; display: block; margin: auto;">
</div>

- Engineered and cross-validated  machine learning solution, using Adobe Font Database, with optical character recognition models to accurately recognize font types from text embedded in images with 84.7% font recognition accuracy and improved faster model training by 26.7% 
- Deployed a web app that optimized font design process, promoted to designer's community in ArtCenter College of Design (ACCD)
- Link: https://fontier.vercel.app/

---

[**UCSB Platinum Smart Course Search Software**](https://github.com/HououinKyouma-2036/UCSB-Platinum-Software.git)
<div style="text-align: center;">
  <img src="/images/148_img.png" alt="148 image" style="width: 500px; display: block; margin: auto;">
</div>
A smart course searching and major sheet planning software based on GPT4 model.

- Engineered a LLM-based smart course recommendation web software, recommending UCSB course given any relevant keywords
- Developed pipelines to populate database with large-scale dataset and fine-tuned GPT for keyword targeting with 96% accuracy
- Implemented CRUD operations for course cart and a ranking system, utilizing relevance, grade distribution, and professor ratings
- Preprocessed and engineered features for model training, deployed model on Google Cloud, ensuring scalability and reliability
- Tools: Django, React, JavaScript, Python, MySQL, OpenAI API, Google Cloud, Next.js

---

[**UCSB Organic Course Software**](https://github.com/ucsb-cs156-f23/proj-organic-f23-6pm-3)
<div style="text-align: center;">
  <img src="/images/156_1.png" alt="156 image" style="width: 700px; display: block; margin: auto;">
</div>
<div style="text-align: center;">
  <img src="/images/156_2.png" alt="Image 1" style="width: 400px; display: inline-block; margin: auto;">
  <img src="/images/156_3.png" alt="Image 2" style="width: 400px; display: inline-block; margin: auto;">
</div>

- Architected a course management system, as project team leader, enabling users to efficiently edit records within 6 data tables
- Designed and migrated the H2 database, implemented backend CRUD operations and controllers for efficient user interactions
- Implemented a hierarchical frontend interface and constructed 30 tests with mock endpoints for 100% functionality coverage






