---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: AI intern (Research)
    company: SHL
    company_url: 'https://www.shl.com/about/'
    company_logo: logo-shl
    location: Gurgaon, India
    date_start: '2021-10-19'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * Analysing
        * Modelling
        * Deploying

  - title: Research intern
    company: Xu Lab, Carnegie Mellon University
    company_url: 'https://xulabs.github.io/'
    company_logo: cmu-logo
    location: Pennsylvania, USA
    date_start: '2021-09-01'
    date_end: ''
    description: |2-
        Overview:

        * Collaborating with a PhD student for a project focused on modeling continuous conformational changes in cryo-ET images with Unsupervised representation learning under the supervision of Dr. Min Xu.
        * Presently working on the initial literature review report.

  - title: MITACS Globalink Research intern
    company: MITACS
    company_url: 'https://www.mitacs.ca/en/programs/globalink globalink-research-internship'
    company_logo: mitacs-logo
    location: British Columbia, Canada
    date_start: '2021-05-17'
    date_end: '2021-08-16'
    description: |2-
      Overview:
      
      * Conducted cross-disciplinary research at the intersection of Deep learning and wireless communications, under the supervision of Dr. Omer Waqar from Thompson River's University, Canada. 
      * Authored a comprehensive review paper addressing a gap in literature on the bi-directional interplay of Federated learning and wireless communications, under review at the journal - **Transactions on Emerging Telecommunications Technologies**.
      * Designed a novel unsupervised learning algorithm for energy and power optimization in UAV networks, manuscript under preparation.
  
  - title: Research intern (PRISM program)
    company: Samsung Research
    company_url: https://www.samsungprism.com/
    company_logo: sr-logo
    location: Bangalore, India
    date_start: '2021-04-14'
    date_end: '2021-10-15'
    description: |2-
      Overview:

      * Leading the project on variable-length synthetic handwriting image generation using Generative Adversarial networks.
      * Academia-Industry colloraboration with a 6-member team consisting of myself, another student, Prof. Vimal Srivastava, Prof. Manoranjan Kumar and two mentors from Samsung Research, Bangalore.
      * Generated synthetic data is being utilized to train better handwritten text recognition (HTR) models for HTR feature in Samsung smartphone's OCR system.

  - title: Data Scientist
    company: Brand Love Intelligence
    company_url: https://brandloveintel.com/
    company_logo: bli-logo
    location: Assen, Netherlands
    date_start: '2021-04-01'
    date_end: ''
    description: |2-
      Overview:

      * Focused on building full stack data science pipeline from data collection to model deployment for powering the AI engine of Relevense
      (https://www.relevense.com/), a Flagship market intelligence product co-funded with grants of the **Europees Fonds voor Regionale Ontwikkeling (EFRO)** and **Samenwerkingsverband Noord Nederland (SNN)**.
      * Projects include Tweet based emotion recognition API, Big-5 personality classication API, Facial expression recognition, Receptive audience recommendation system.
      * Reduced the AWS costs by 60% by shifting the backend to a serverless architecture with multiple Lambda functions, DynamoDB, Timestream and S3.
      * Single handedly created end-to-end ML pipelines with all models beyond 95% accuracy along with efficient monitoring of out of training distribution inference events.
      * **Currently working only as a part-time maintainer of the AWS and data science backend of Relevense from September 2021, discontinued being full-time for exploring roles focused particularly on Computer Vision research**.
    
  - title: Lead Machine learning Engineer
    company: Omdena
    company_url: https://omdena.com/
    company_logo: logo-omdena
    location: California, USA
    date_start: '2020-09-10'
    date_end: '2021-04-01'
    description: |2-
      Overview:
      
      * Collaborated with a team of 48 while working with our client, World Resources Institute (https://www.wri.org/) on a project leveraging NLP to find geographical locations with climate hazards and potential gaps for minimizing climate change impacts across the globe. Deployed a dashboard designed with Streamlit for easy inference.
      * Led a team of 48 for building the data processing and machine learning backend for a Dutch client's market intelligence product. **Got a full-time offer from the client due to extraordinary contributions in the project**.
  
  - title: Research intern (volunteer)
    company: Emory University
    company_url: https://sites.google.com/stanford.edu/imon-banerjee-stanford/home
    company_logo: emory-logo
    location: Atlanta, USA
    date_start: '2021-02-01'
    date_end: '2021-05-01'
    description: |2-
      Overview:

      * Built an end-to-end NLP pipeline for Multi-document abstractive summarization
        of Radiology reports of COVID-19 patients
      * Trained longformer and BERT models on a Slurm multi-GPU cluster in an HIPAA protected server.
      * Achieved a ROUGE-1 score of 0.410 on test dataset.

  - title: Product and Engineering intern
    company: HighRadius
    company_url: https://www.highradius.com/
    company_logo: hrc-logo
    location: Odisha, India
    date_start: '2021-01-07'
    date_end: '2021-03-17'
    description: |2-
      Overview: 

      * Developed a full stack web-based invoice management application following an end-to-end Data science product development lifecycle guided by mentors.
      * Responsibilities included identifying appropriate user requirements, designing a great user experience and building appropriate data pipelines and machine learning models along with relevant UI components and backend design.
      * Developed a state-of-the-art payment prediction system using XGboost regression, with a root-mean-squared error of 0.1 on 5-fold cross validation.

design:
  columns: '2'
---
