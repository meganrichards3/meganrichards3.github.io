---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me
I'm a Computer Science PhD student at [NYU's Courant Institute for Mathematical Sciences](https://cims.nyu.edu/dynamic/), working with [Kyunghyun Cho](https://kyunghyuncho.me/). My PhD is supported by NYU's Dean's Doctoral Fellowship, and the [NSF Graduate Research Fellowship (GRFP)](https://www.nsfgrfp.org/). Previously, I was an AI Resident at [Meta AI](https://ai.meta.com/research/) (FAIR labs) where I was fortunate to be advised by [Mark Ibrahim](https://scholar.google.com/citations?hl=en&user=AqYyoCMAAAAJ&view_op=list_works&sortby=pubdate) and [Diane Bouchacourt](https://dianebouchacourt.github.io/). I graduated with departmental distinction from Duke University, where I studied Electrical and Computer Engineering with a concentration in Machine Learning.   

My current work at NYU focuses on building more scalable, general-purpose statistical tools, with the goal of improving the study of modern ML datasets and models.

At FAIR, I studied the reliability of vision-language models (during which I became convinced that we needed better tools to measure datasets). My work at FAIR included included studying the increasing divergence between imagenet-based benchmarks and global, crowdsourced data ([ICLR 2024](https://arxiv.org/abs/2307.13136)), investigating why vision models failed to generalize to images from non-western countries ([Spotlight, NeurIPS 2023](https://arxiv.org/abs/2304.05391)), and designing metrics for image generation ([Outstanding Paper, TiFA workshop ICML 2024](https://arxiv.org/abs/2406.11988)). I recently shared an overview of this line of work at CVPR's DemoDiv workshop ([slides](https://drive.google.com/file/d/13f-iCRfuA1etKQCdv1koyP9pefyuuGtf/view?usp=sharing)). 

I became motivated to work in machine learning research (and model reliability more specifically) after experiences building models in healthcare settings. At Duke, I worked with [Mark Sendak](https://scholar.google.com/citations?user=U0kHK8wAAAAJ&hl=en&oi=ao) as part of the Duke Institute for Healthcare Innovation ([DIHI](https://dihi.org/projects/)), to build risk prediction models for [severe pregnancy complications](https://static1.squarespace.com/static/59d5ac1780bd5ef9c396eda6/t/62eb0bc60a2601399afdfecf/1659571143037/108+MEWS_Abstract.pdf), which are now integrated and in silent trials. While at Duke, I also worked at the [Duke Center for Global Women's Health Technologies](https://www.dukegwht.org/) on a [self-screening device](https://spj.science.org/doi/full/10.34133/2022/9823184?adobe_mc=MCMID%3D14000684186094648760814905405683999528%7CMCORGID%3D242B6472541199F70A4C98A6%2540AdobeOrg%7CTS%3D1696809600) for cervical cancer designed for low-resource global settings, which earned a Best Research award at NIH's IEEE HIPOCT Conference in 2019. 

## Recent Updates
- **Nov '25** 📝 Check out our most recent preprint, [MIST: Mutual Information via Supervised Training](https://arxiv.org/abs/2511.18945)! We meta-learn mutual information estimators, building estimators that learn to estimate MI directly from samples (rather than computing density or density ratios through bounds). Our method achieves substantial gains for high-dimensional, low-sample settings, with massive improvements in inference efficiency.  

- **June '25**: Delighted to be speaking at CVPR's [DemoDiv](https://sites.google.com/view/cvpr-2025-demodiv/) workshop about some of our work studying geographic underrepresentation in computer vision. I made my presentation publicly available [here](https://drive.google.com/file/d/13f-iCRfuA1etKQCdv1koyP9pefyuuGtf/view?usp=sharing)!  
  
- **Nov '24**: 📝 Check out our new NAACL '25 work [On the Role of Speech Data in Reducing Toxicity Detection Bias](https://arxiv.org/abs/2411.08135), led by Samuel Bell! We generate and release a new set of multilingual toxicity annotations for MuTox, and find that when models have access to the audio itself, rather than a transcript, they are more accurate and less biased in detecting toxicity (w.r.t group mentions).  
  
- **July '24**:🎊 We're honored to receive an **outstanding paper award** at the ICML TiFA workshop for our work measuring geographic disparities in image generations! It was such a pleasure to help supervise this project, led by Abhishek Sureddy, Dishant Padelia, and Nandhinee Periyakaruppa. 

- **May '24**: 📝 Check out our [Introduction to Vision-Language Modeling](https://arxiv.org/abs/2405.17247), created through a broad collaboration of researchers (> 40 people across 10 institutions) to help democratize knowledge about VLMs! 

- **April '24**: 🎓 This fall, I will start a PhD at [NYU Computer Science](https://cs.nyu.edu/home/index.html), working with [Kyunghyun Cho](https://kyunghyuncho.me/). My work will be supported by NYU's [GSAS Dean's Doctoral Fellowship](https://gsas.nyu.edu/admissions/financial-aid/diversity-and-access-funding-programs.html), as well as the [NSF Graduate Research Fellowship (GRFP)](https://www.nsfgrfp.org/). 

## Publications
- **_MIST: Mutual Information via Supervised Training_** \
German Gritsai<sup>\*</sup>, Megan Richards<sup>\*</sup>,, Maxime Méloux<sup>\*</sup>,, Kyunghyun Cho, Maxime Peyrard \
 <sup>\*</sup>_joint first author_ \
 [[ArXiv](https://arxiv.org/abs/2511.18945)]

- **_On the Role of Speech Data in Reducing Toxicity Detection Bias_** \
   Samuel J. Bell<sup>\*</sup>, Mariano Coria Megliol<sup>\*</sup>, **Megan Richards**<sup>\*</sup>, Eduardo Sánchez<sup>\*</sup>, \
  Christophe Ropers, Skyler Wang, Adina Williams, Levent Sagun, Marta R. Costa-jussà<sup>\*</sup> \
  _<sup>\*</sup>core contributor_ \
  NAACL 2025 \
    [[ArXiv](https://arxiv.org/abs/2411.08135)]
  
- **_Decomposed Evaluations of Geographic Disparities in Text-To-Image Models_** \
   Abhishek Sureddy<sup>\*</sup>, Dishant Padalia<sup>\*</sup>, Nandhinee Periyakaruppa<sup>\*</sup>, Oindrila Saha, Adina Williams, Adriana Romero-Soriano, \
  **Megan Richards**<sup>\*\*</sup>, Polina Kirichenko<sup>\*\*</sup>, Melissa Hall<sup>\*\*</sup> \
   <sup>\*</sup>_joint first author_   _<sup>\*\*</sup>joint senior author_ \
  Outstanding Paper, Trustworthy Multi-modal Foundation Models and AI Agents (TiFA) Workshop, ICML 2024. \
  Next Generation of AI Safety Workshop, ICML 2024. \
    [[ArXiv](https://arxiv.org/abs/2406.11988)]
  
- **_An Introduction to Vision-Language Modeling_** \
    Florian Bordes, Richard Yuanzhe Pang, Anurag Ajay, ..., **Megan Richards**, ..., Kate Saenko, Asli Celikyilmaz, Vikas Chandra \
    [[ArXiv](https://arxiv.org/abs/2405.17247)]
  
- **_Does Progress On Object Recognition Benchmarks Improve Generalization on Crowdsourced, Global Data?_** \
    **Megan Richards**, Polina Kirichenko, Diane Bouchacourt, Mark Ibrahim \
    ICLR '24 \
    [[ICLR '24](https://openreview.net/forum?id=rhaQbS3K3R)]

- **_Exploring Why Object Recognition Performance Degrades Across Income Levels and Geographies_** \
    Laura Gustafson, **Megan Richards**, Melissa Hall, Caner Hazirbas, Diane Bouchacourt, Mark Ibrahim \
    [[(Spotlight) NeurIPS 2023 Datasets and Benchmarks](https://arxiv.org/abs/2304.05391)]. 

- **_Development and Validation of ML-DQA – a Machine Learning Data Quality Assurance Framework for Healthcare_** \
    Mark Sendak, Gaurav Sirdeshmukh, Timothy Ochoa, Hayley Premo, Linda Tang, Kira Niederhoffer, Sarah Reed, Kaivalya Deshpande, Emily Sterrett, Melissa Bauer, Laurie Snyder, Afreen Shariff, David Whellan, Jeffrey Riggio, David Gaieski, Kristin Corey, **Megan Richards**, Michael Gao, Marshall Nichols, Bradley Heintze, William Knechtle, William Ratliff, Suresh Balu \
  Machine Learning for Healthcare, 2022 \
    [[PMLR]( https://proceedings.mlr.press/v182/sendak22a.html)]
 
- **_Multicontrast Pocket Colposcopy Cervical Cancer Diagnostic Algorithm for Referral Populations_** \
    Erica Skerrett, Zichen Miao, Mercy N Asiedu, **Megan Richards**, Brian Crouch, Guillermo Sapiro, Qiang Qiu, Nirmala Ramanujam \
    BME Frontiers, 2022 \
    [[BME Frontiers](https://downloads.spj.sciencemag.org/bmef/2022/9823184.pdf)]
  
## Posters

- **_Does Progress On Object Recognition Benchmarks Improve Generalization on Crowdsourced, Global Data?_** \
    **Megan Richards**, Polina Kirichenko, Diane Bouchacourt, Mark Ibrahim \
    Poster, Data Centric Machine Learning (DMLR) Workship, ICML 2023 

- **_Towards Deploying Predictive Models for Maternal Health_** \
    Kaivalya Deshpande, Willie Boag, Freya Gulamali, **Megan Richards**, Michael Gao, Namita Kansal, Vaishakhi Mayya, Mark Sendak, Ashraf Habib, Terrence Allen, Sarah McWay Boling, Melissa Bauer, Jennifer Gilner, Brenna Hughes, Courtney Mitchell, Heather Tally, Amanda Craig, Suresh Balu, William Knechtle \
    Poster, Machine Learning for Healthcare, 2023 
  
- **_Phenotype Development and Validation for a Maternal Early Warning System_** \
    **Megan Richards**, MS Michael Gao, William Knechtle, Namita Kansal, Vaishakhi Mayya, MD Sendak, Ashraf Habib, Terrence Allen, Sarah McWay Boling, Melissa RN, DO Bauer, Jennifer Gilner, MD Courtney Mitchell \
    Poster, Machine Learning for Healthcare, 2022 

- **_Development of a Speculum-Free Liquid Applicator for At-Home Cervical Cancer Screening_** \
    Erica Skerrett, Mercy N Asiedu, **Megan Richards**, John Wilson Schmitt, Nirmala Ramanujam \
    **Best Poster**, NIH IEEE HIPOCT Conference, 2019 

## Talks

- **_CVPR 2025, DemoDiv Workshop_** \
    Geographic Underrepresentation in Computer Vision \
    [Slides](https://drive.google.com/file/d/13f-iCRfuA1etKQCdv1koyP9pefyuuGtf/view?usp=sharing)  

## Organizing 
I'm really excited by efforts to make machine learning/science more inclusive, and am proud to part of the following efforts: 

- **_Organizer, Queer In AI_** 🌈 \
I helped organize the QinAI NeurIPS 2023 workshop - see our NeurIPS website [here](https://www.queerinai.com/neurips-2023) and our org website [here](https://www.queerinai.com/).


- **_Discussion Lead, Women-In-Machine-Learning (WiML) at ICML 2023_** <img src="https://github.com/meganrichards3/meganrichards3.github.io/assets/31023715/dcaa9b14-911f-4c5b-a11a-c786256e35b1" width="25" height="12.5">
 \
I helped organize a breakout session on robustness and large-scale vision models at the [Women in Machine Learning](https://sites.google.com/wimlworkshop.org/wiml-unworkshop-2023/home?authuser=0) workshop at ICML 2023 ([slides](https://drive.google.com/file/d/19do6FdisYV5OFY26jH-nvbB9CihDAcBg/view?usp=sharing)). 

## Service 
- **_Reviewer, ICLR Workshops 2024_** \
  I was a reviewer for the Workshops at ICLR 2024. Excited to see so many great new avenues of research!
  
- **_Reviewer, DMLR Workshop at ICML 2023_** \
  I was a reviewer for the DMLR workshop at ICML 2023. See more about the workshop [here](https://dmlr.ai/). 
