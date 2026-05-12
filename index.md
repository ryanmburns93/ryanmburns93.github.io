---
title: Project Portfolio
---

<details open><summary style="font-size: 120%;"><b>Certilytics Projects</b></summary>
<hr>
<details open>
  <summary style="font-size: 100%;">GenAI Patient Healthcare Pathway Modeling</summary>
  <p>
    <br>
    <strong>Impact:</strong> Developed and productionalized custom transformer architectures that achieved high-precision denial predictions, streamlining claims processing and improving financial efficiency.
    <br><br>
    To address the operational challenge of health insurance claim denials, I designed <strong>custom transformer-based neural network architectures</strong>. Unlike off-the-shelf solutions, these models were specifically tailored to capture the intricate relationships within complex claims data, resulting in high-performance metrics for both binary (denial vs. approval) and multi-class (denial reason) predictions.
    <br><br>
    I led the end-to-end deployment of these models into production for daily batch inference. The implementation utilized:
    <ul>
      <li><strong>MLFlow:</strong> For comprehensive model lifecycle management, including experiment tracking and versioning.</li>
      <li><strong>AWS:</strong> For building a scalable and reliable cloud infrastructure.</li>
      <li><strong>Operational Excellence:</strong> Empowering organizations to proactively address denials and optimize patient experiences through automated insights.</li>
    </ul>
  </p>
</details>

<hr>
<details open>
  <summary style="font-size: 100%;">Health Insurance Claims Denial Neural Network</summary>
  <p>
    <br>
    <strong>Impact:</strong> Productionalized custom transformer architectures that achieved high-precision denial predictions, directly optimizing financial recovery and claims processing efficiency.
    <br><br>
    To tackle the financial strain caused by unpredictable health insurance claim denials, I designed <strong>custom transformer-based neural network architectures</strong> tailored to the non-linear complexities of medical billing data. While standard models often struggle with the multi-dimensional relationships in claims, these specific architectures were engineered to identify potential denials and their underlying reasons before they impacted the bottom line.
    <br><br>
    I led the end-to-end deployment of these models for daily batch inference, ensuring a scalable and reliable production environment. The implementation featured:
    <ul>
      <li><strong>Advanced Architecture:</strong> Developed specialized transformers to capture intricate data relationships that off-the-shelf solutions missed.</li>
      <li><strong>MLOps Excellence:</strong> Utilized <strong>MLFlow</strong> for comprehensive model lifecycle management—including experiment tracking and versioning—and <strong>AWS</strong> for cloud-scale infrastructure.</li>
      <li><strong>Operational Value:</strong> By automating the identification of both binary and multi-class denial outcomes, the system enables proactive intervention and significantly reduces manual review time.</li>
    </ul>
  </p>
</details>

<hr>
<details open>
  <summary style="font-size: 100%;">Word Embedding Hyperparameter Tuning</summary>
  <p>
    <br>
    <strong>Impact:</strong> Optimized the core medical data representation layer for the entire model suite, driving a <strong>5% average performance lift</strong> across all downstream classification and regression tasks.
    <br><br>
    Following the acquisition of new patient-level medical utilization data, I led the retraining and optimization of the foundational word embeddings that power the Certilytics ecosystem. The objective was to identify the optimal hyperparameter configurations to represent complex medical sequences more effectively than baseline models.
    <br><br>
    To ensure the new embeddings were both statistically superior and clinically sound, I implemented a rigorous multi-stage validation process:
    <ul>
      <li><strong>Systematic Optimization:</strong> Executed a hyperparameter grid search across 22 distinct model configurations to isolate the settings that best captured medical utilization patterns.</li>
      <li><strong>Extrinsic Evaluation:</strong> Developed a robust testing framework that involved training four end-to-end models for every embedding candidate across four different pipelines, ensuring that improvements in the latent space translated to real-world predictive power.</li>
      <li><strong>Intrinsic Clinical Validation:</strong> Partnered with internal clinical experts to conduct a custom clustering challenge, verifying that the embeddings accurately reflected medical logic and established relationships between codes.</li>
      <li><strong>Enterprise Integration:</strong> Successfully deployed the final configuration, which resulted in a 5% improvement in AUC and R² scores and now serves as the central embedding layer for the majority of production pipelines.</li>
    </ul>
  </p>
</details>
</details>

<hr>

<details open><summary style="font-size: 120%;">AIR Communities Projects</summary>
<hr>
<details>
  <summary style="font-size: 100%;">Future Lease Projection Application</summary>
  <p>
    <br>
    <strong>Impact:</strong> Replaced a slow, single-property Excel process with a high-performance Python application, enabling multi-scenario portfolio forecasting and reducing calculation time from hours to seconds.
    <br><br>
    <strong>Situation:</strong> The existing Excel-based projection tool was unable to handle unit-level data for the full ~100 property portfolio, with a runtime of nearly an hour per property.
    <br><br>
    <strong>Task:</strong> I was approached to engineer a scalable solution to create budget and forecasting projection scenarios across the entire portfolio independently.
    <br><br>
    <strong>Action:</strong>
    <ul>
      <li>Developed a <strong>Python-based engine</strong> to handle complex, unit-level calculations that previously overwhelmed spreadsheet software.</li>
      <li>Created a custom <strong>GUI using Tkinter</strong> and bundled the program into an executable via <strong>PyInstaller</strong>, allowing non-technical staff to run scenarios on-demand.</li>
      <li>Integrated output directly into <strong>SQL tables</strong>, streamlining data consumption for the Decision Support team.</li>
    </ul>
    <br>
    <strong>Result:</strong> Transformed the forecasting process into a "disruptive innovation" that expanded the forecast horizon and allowed the organization to analyze a significantly higher volume of financial scenarios with precision.
  </p>
</details>

<hr>

<details>
  <summary style="font-size: 100%;">CoStar Property Data Scraping</summary>
  <p>
    <br>
    This project sought to collect over forty attributes for more than 850 competitor multi-family apartment home properties from the <a href="https://www.costar.com/">CoStar property research platform</a>. The program achieved data collection, cleansing, and injection into storage in less than eight minutes start to finish. CoStar recently updated the service's <a href="https://www.costar.com/about/terms-conditions">Terms of Use</a> to explicitly prohibit the web scraping techniques and reverse-engineering of the CoStar product utilized in this program. I ultimately led the project in an alternate direction to acquire similar data while keeping the business in compliance with CoStar's Terms of Use, and have shared the original program as proof of work.
  </p>
  <br>

  <a href="https://github.com/ryanmburns93/CoStar_Property_Data_Scraping"><img src="https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub" alt="View on GitHub"></a>

  <a href="https://www.codefactor.io/repository/github/ryanmburns93/CoStar_Property_Data_Scraping"><img src="https://www.codefactor.io/repository/github/ryanmburns93/CoStar_Property_Data_Scraping/badge" alt="CodeFactor Repo Grade" /></a>
</details>

<hr>

<details>
  <summary style="font-size: 100%;">AutoML Demo with DataRobot</summary>
  <p>
    <br>
    I created a tutorial and video demonstration of the automatic machine learning (AutoML) tool DataRobot. The tutorial provides a simple demonstration of DataRobot integration into a project applying sentiment analysis to daily chatbot message data to rank order prospect follow-up outreach conducted the following day. The final application can be viewed in the separate <a href="https://github.com/ryanmburns93/Prospect_Ranked_Followup_App">Prospect Ranked Follow-up Application</a> repository.
  </p>
  <br>

  <a href="https://github.com/ryanmburns93/DataRobot_Demo"><img src="https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub" alt="View on GitHub"></a>

  <a href="https://www.codefactor.io/repository/github/ryanmburns93/datarobot_demo"><img src="https://www.codefactor.io/repository/github/ryanmburns93/datarobot_demo/badge" alt="CodeFactor Repo Grade" class="CF-Badge"/></a>
</details>
</details>

<hr>

<details open>
  <summary style="font-size: 120%;">Personal Projects</summary>
  <hr>
<details><summary style="font-size: 100%;">NLP Miniature BERT Model Case Study</summary>
<p>
<br>
This project is a case study on developing NLP applications in a low-resource corporate environment operating a client-centric, service-based business model. I pretrained miniature BERT masked language models on domain-adapted vocabulary sourced from client-facing research documents. I demonstrated light improvements in model performance over baseline when finetuned to categorize client consultation requests by topic.
</p>
<br>

<a href="https://github.com/ryanmburns93/NLP_Case_Study"><img src="https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub" alt="View on GitHub">
</a>

<a href="https://www.codefactor.io/repository/github/ryanmburns93/nlp_case_study"><img src="https://www.codefactor.io/repository/github/ryanmburns93/nlp_case_study/badge" alt="CodeFactor Repo Grade" /></a>
</details>

<hr>

<details><summary style="font-size: 100%;">Recording and Transcription Web Scraping Toolkit</summary>
<p>
<br>
I developed this toolkit to automate the collection of video recordings, recording metadata, and transcripts from a variety of different video conference, video hosting, and transcription service platforms. I personally utilized the tools during my four years working in client relationship management remotely supporting a territory containing hundreds of clients.
</p>
<br>

<a href="https://github.com/ryanmburns93/web_scraping_tools"><img src="https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub" alt="View on GitHub">
</a>

<a href="https://www.codefactor.io/repository/github/ryanmburns93/web_scraping_tools"><img src="https://www.codefactor.io/repository/github/ryanmburns93/web_scraping_tools/badge" alt="CodeFactor Repo Grade" /></a>
</details>

<hr>

<details><summary style="font-size: 100%;">Biweekly Sales Reports Automation</summary>
<p>
<br>
As the lucky husband to the founder of <a href="https://www.thebeverlycollective.co/">The Beverly Collective</a>, a Colorado-based art collective, I built this program to reduce the manual workload of sending out biweekly sales reports emails to the 30+ artists and makers vending through the collective. I completed coding for this program in less than 5 hours and reduced the hourly workload from 10 hours per month to only 2 hours focused on email validation, payment processing, and vendor support each month. I successfully leveraged the Gmail API to gather user permissions and create email drafts within the user email and consumed Excel files into the Python-based program using the OpenPyxl library.
</p>
<br>

<a href="https://github.com/ryanmburns93/Sales_Reporting_Automation"><img src="https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub" alt="View on GitHub">
</a>

<a href="https://www.codefactor.io/repository/github/ryanmburns93/sales_reporting_automation"><img src="https://www.codefactor.io/repository/github/ryanmburns93/sales_reporting_automation/badge" alt="CodeFactor Repo Grade" /></a>
</details>

<hr>

<details><summary style="font-size: 100%;">Continuous Glucose Monitor Modeling</summary>
<p>
<br>
This project is designed to extend personal diabetes data and insights into the realm of real-time streaming, IoT integrations, and data science predictive modeling techniques. The project is launched from a foundation of diabetes data democratization facilitated by <a href="https://nightscout.github.io/">Nightscout</a>, an open-source cloud application used by people with diabetes, providers, and caretakers to visualize, store and share the data from their Continuous Glucose Monitoring sensors in real-time.
<br>
<br>
Having recently established sensor data accessibility via a web-hosted MongoDB database, I am actively pursuing two aims with this project:
<br>
<br>
<ol>
    <li>Extend the data availability onto IoT technologies visualizing current blood glucose levels and directional trends.</li>
    <li>Apply cutting edge ML/AI modeling techniques to train novel predictive algorithms and compare performance to current industry standards.</li>
</ol>
</p>

<a href="https://github.com/ryanmburns93/cgm-glucose-modeling"><img src="https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub" alt="View on GitHub">
</a>

<a href="https://www.codefactor.io/repository/github/ryanmburns93/cgm-glucose-modeling"><img src="https://www.codefactor.io/repository/github/ryanmburns93/cgm-glucose-modeling/badge" alt="CodeFactor Repo Grade" /></a>
</details>

<hr>

<details><summary style="font-size: 100%;">PDGA Prediction Modeling Utility Scripts</summary>
<p>
<br>
I co-authored a blog series hosted on Ultiworld Disc Golf predicting disc golf player performance at elite series events. I contributed player performance web scraping and GIS data collection capabilities, cleaned and preprocessed data, and edited post content. The scripts hosted in this repository demonstrate some of the larger data collection efforts feeding parts of the model. This was my first time ever using Python, and I am in the process of revisiting the files to spruce up the content. 

The blog posts are available on the <a href="https://discgolf.ultiworld.com/author/rburns/">Ultiworld Disc Golf website</a>.
</p>
<br>

<a href="https://github.com/ryanmburns93/pdga_predictions_ml_scraping"><img src="https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub" alt="View on GitHub">
</a>

<a href="https://www.codefactor.io/repository/github/ryanmburns93/pdga_predictions_ml_scraping"><img src="https://www.codefactor.io/repository/github/ryanmburns93/pdga_predictions_ml_scraping/badge" alt="CodeFactor Repo Grade" /></a>
</details>
<br>
</details>
