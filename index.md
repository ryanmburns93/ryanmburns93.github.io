---
title: Project Portfolio
---

<details><summary style="font-size: 120%;"><b>Certilytics Projects</b></summary>
<hr>
<details><summary style="font-size: 100%;">GenAI Patient Healthcare Pathway Modeling</summary>
<p>
<br>
This project focused on leveraging advanced generative AI to model complex treatment pathways and provide actionable insights for improving patient outcomes and provider performance while reducing costs. Utilizing a GPT-2 language model, I engineered a novel approach to learn underlying disease pathways from extensive claims data. 
<br>
<br>
A key innovation involved developing a custom tokenizer with a specialized vocabulary derived directly from healthcare claims elements, ensuring precise representation of medical events. Furthermore, I proactively integrated a Rotary Position Embedding (RoPE) mechanism into the GPT-2 architecture, based on recent research and implemented prior to its mainstream availability, which significantly enhanced model performance by nearly 2x. This robust generative model was then applied to critical healthcare tasks, including high-cost claimant classification, enabling early identification of at-risk individuals; provider rank ordering for optimized resource utilization; and in-depth at-risk population analysis to inform targeted interventions.
<br>
</p>
<br>
</details>

<hr>
<details><summary style="font-size: 100%;">Word Embedding Hyperparameter Tuning</summary>
<p>
<br>
I retrained a word embedding deep representation model on newly-acquired data containing patient-level medical system utilization sequences and applied hyperparameter tuning testing and analysis. I tested a hyperparameter grid by generating 22 model configurations, and the optimal hyperparameter setting ultimately selected resulted in an average improvement of 5% AUC or R<sup>2</sup> score (depending on whether the application was a classification or regression problem) across the entire model suite.
<br>
<br>
In order to evaluate the performance of each word embedding, I trained four end-to-end models for each embedding contained in the four model pipelines, and I scored these four models to allow me to conduct cross-model extrinsic evaluations. After completing the extrinsic evaluations to select the optimal final configuration, I partnered with Certilytics' internal clinical expert to conduct an intrinsic evaluation of the model using a custom clustering challenge on hand-selected medical codes which would be naturally expected to exhibit clusters or distance between similar and dissimilar codes respectively.
<br>
<br>
The final embedding sits centrally in most model pipelines within Certilytics model suite.
<br>
</p>
</details>
</details>

<hr>

<details><summary style="font-size: 120%;"><b>AIR Communities Projects</b></summary>
<hr>
<details><summary style="font-size: 100%;">Future Lease Projection Application</summary>
<p>
<br>
I was tasked with building a program to create projection scenarios for future leases across AIR Communities' apartment property portfolio. The projections informed the budget and forecasting process for the organization, and I was initially approached to own this project after a single property projection (of ~100 owned) built in Excel was unable to handle the complete unit-level output and had a runtime of close to an hour.
<br>
<br>
I built the logic into a Python program which output results to a new SQL table available to the Decision Support team consuming the projections for forecasting. While the logic and calculations feeding the forecast are highly proprietary, I have included the video below which shows the GUI application I built on top of the program and bundled into an executable to enable Decision Support staff to independently rerun the program while tweaking model inputs. I used Tkinter to develop the GUI and PyInstaller to create the executable.
<br>
<br>
This project proved to be a disruptive innovation to the forecasting process at AIR Communities, expanding the forecast horizon and predictive capabilities of the financial future of the organization across a greater number of scenarios due to the quick, user-friendly deliverable.
<br>
</p>
<br>
</details>

<hr>

<details><summary style="font-size: 100%;">CoStar Property Data Scraping</summary>
<p>
<br>
This project sought to collect over forty attributes for more than 850 competitor multi-family apartment home properties from the <a href="https://www.costar.com/">CoStar property research platform</a>. The program achieved data collection, cleansing, and injection into storage in less than eight minutes start to finish. CoStar recently updated the service's <a href="https://www.costar.com/about/terms-conditions">Terms of Use</a> to explicitly prohibit the web scraping techniques and reverse-engineering of the CoStar product utilized in this program. I ultimately led the project in an alternate direction to acquire similar data while keeping the business in compliance with CoStar's Terms of Use, and have shared the original program as proof of work.
</p>
<br>

<a href="https://github.com/ryanmburns93/CoStar_Property_Data_Scraping"><img src="https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub" alt="View on GitHub">
</a>

<a href="https://www.codefactor.io/repository/github/ryanmburns93/CoStar_Property_Data_Scraping"><img src="https://www.codefactor.io/repository/github/ryanmburns93/CoStar_Property_Data_Scraping/badge" alt="CodeFactor Repo Grade" /></a>
</details>

<hr>

<details><summary style="font-size: 100%;">AutoML Demo with DataRobot</summary>
<p>
<br>
I created a tutorial and video demonstration of the automatic machine learning (AutoML) tool DataRobot. The tutorial provides a simple demonstration of DataRobot integration into a project applying sentiment analysis to daily chatbot message data to rank order prospect follow-up outreach conducted the following day. The final application can be viewed in the separate <a href="https://github.com/ryanmburns93/Prospect_Ranked_Followup_App">Prospect Ranked Follow-up Application</a> repository.
</p>
<br>

<a href="https://github.com/ryanmburns93/DataRobot_Demo"><img src="https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub" alt="View on GitHub">
</a>

<a href="https://www.codefactor.io/repository/github/ryanmburns93/datarobot_demo"><img src="https://www.codefactor.io/repository/github/ryanmburns93/datarobot_demo/badge" alt="CodeFactor Repo Grade" class="CF-Badge"/></a>
</details>
</details>

<hr>

<details><summary style="font-size: 120%;"><b>Personal Projects</b></summary>
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
<br>

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
