# Google Summer of Code '24 Final Report
* **Name: [Aman Kumar][res-github-aman]**
* **Project: [Analytics Edge Ecosystem Workloads][res-gsoc-project]**
* **Organization: [openSUSE Project][res-gsoc-project]**
* **Mentor: [Bryan Gartner][res-linkedin-bryan], [Navin Chandra][res-linkedin-navin], [Terry Smith][res-linkedin-terry], [Ann Daivs][res-github-ann]**



[res-linkedin-bryan]:<https://www.linkedin.com/in/bryangartner/>
[res-linkedin-navin]:<https://www.linkedin.com/in/navin-chandra-b610b2144/>
[res-linkedin-terry]:<https://www.linkedin.com/in/tlsmith42/>
[res-github-ann]:<https://github.com/andavissuse>


This report summarizes the work done by [me][res-github-aman] in the [Google Summer of Code][res-gsoc] 2024 program as a contributor for the [OpenSUSE][res-gsoc-ga4gh] organization, under the guidance of the mentors [Bryan Gartner][res-linkedin-bryan], [Navin Chandra][res-linkedin-navin], [Terry Smith][res-linkedin-terry], [Ann Daivs][res-github-ann].


## Overview
This project aims to leverage machine learning and generative AI to help address some of the challenges that patients and doctors face with medical prescriptions.

AI/ML and GenAI workload will be developed to address the challenges faced in the healthcare/medical industry. Development of this project includes open-source deployment of AI/ML and GenAI workloads as well as deployments on Kubernetes using Rancher by SUSE while having openSUSE Leap as the base layer operating system. Also, K3s will be used as a lightweight Kubernetes designed for the Edge.

## Implementation

- Data extraction and transformation : Medical data from mediline FDA approved repositories and also from other trusted sources.

- Feature engineering and data cleaning will be performed after extraction
Data conversion to an embedding, stored in a vector database for RAG
	
- Retrieval-augmented generation (RAG) : Leverage open-source LLMs to power implement RAG for this medication use case.

User Interface and LLMOps
Create user interface
Define end-to-end LLMOps pipeline to enable additional training and End-to-End Advanced RAG.

**Technologies Used**: Python, TensorFlow, OpenCV, Tesseract, Pinecone, Embedddings, Kubernetes, SUSE Rancher, LLMs, ReportLab.


### Data Sources
- [Government medical data source](https://medlineplus.gov)
- [Advance medical data Gov source](https://www.nlm.nih.gov/databases) -> Licensed required
- [Medical Encyclopedia](https://medlineplus.gov/encyclopedia.html)
- [Journal lists](https://www.ncbi.nlm.nih.gov/pmc/journals/)


**Project Covers** several tech stacks such as DataOps to manage Data pipelines, MLOps, and LLMOps to manage ML and LLM pipelines—Platform Engineering and ITOps to manage platforms, etc.


## What it's Going to Solve
**Problem:** Patients often struggle to understand medication labels, including dosage, side effects, and expiry dates, leading to potential misuse or non-compliance with prescribed treatments.

**Solution:** The Medicine Scanner feature of your project allows patients to scan medication labels to receive clear,   detailed information about the medicine, its correct usage, side effects, and expiration dates. This reduces the risk of incorrect medication usage.

## What did I achieve?

**Improved Patient Experience:** You developed tools that simplify the interaction between patients and their medical data, such as scanning and interpreting medicine labels, medical reports, and handwritten prescriptions. This can lead to better understanding and adherence to medical instructions.

**Addressing Healthcare Challenges:** The project directly addresses challenges in the healthcare industry, particularly in medication management and prescription accuracy, making it a valuable contribution to improving healthcare delivery.

**Multi-Language Support:** The project's capability to provide information in multiple languages broadens its applicability, making it accessible to a diverse patient population.

**Enhanced Doctor Efficiency:** The prescription generator streamlines the process for doctors, enabling them to quickly produce clear and accurate prescriptions, reducing the risk of misinterpretation.

## User Friendly Interface
![alt text](image-2.png)

## Ask About your Medicines
![alt text](image-1.png)

[res-github-aman]:<https://github.com/Aman123lug>
[res-gsoc-project]:<https://summerofcode.withgoogle.com/programs/2024/projects/hDIDPCCB>
[res-gsoc-ga4gh]:<https://summerofcode.withgoogle.com/programs/2024/organizations/opensuse-project>
[res-gsoc]:<https://summerofcode.withgoogle.com>
[elixir-cloud-aai]:<https://github.com/elixir-cloud-aai>


## Acknowledgments
Thanks to the open-source community for providing various tools and frameworks.
Special thanks to Lama3, Governement Data Sources, and other trusted sources for providing the datasets.
Gratitude to SUSE, openSUSE Leap, and Rancher for their powerful tools enabling Kubernetes deployments.

## Future Work

The project aims to continually improve and expand its features. Future work includes:

- Enhanced Model Training: Continuously improve the accuracy and efficiency by putting more and more Data.

- Integration with More Data Sources: Expand the data sources to include more comprehensive and diverse medical data.

- User Feedback Mechanism: Implement a feedback system for users to report issues and suggest improvements.

- Mobile Application: Develop a mobile application to make the solution more accessible to patients and healthcare providers.

## Authors
[Aman Kumar][res-github-aman] - Initial work

# Support
If you need support, please open an issue on the [GitHub repository][res-github-aman-repo].

[res-github-aman-repo]:<https://github.com/Aman123lug/GSOC-project-24-medical>
