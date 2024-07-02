SageMaker IT Domain Expert Project

Project Context
This repository contains a proof-of-concept (POC) project titled "Introducing Generative AI with AWS." The focus of this project is on fine-tuning large language models using AWS SageMaker. The aim is to develop a domain expert model tailored specifically for the Information Technology (IT) domain, equipping students with advanced machine learning (ML) and large language model (LLM) skills. By leveraging AWS tools, the project trains a language model capable of generating contextually relevant text responses. It emphasizes rigorous evaluation by comparing the performance of the fine-tuned model against the original, serving as a resource for developing high-quality ML solutions.

Project Overview
This project aims to create a domain expert model for the IT domain. By employing advanced natural language processing (NLP) techniques, the project trains and deploys a large language model in AWS SageMaker. The goal is for the model to generate informative and contextually relevant text responses related to IT.

Dataset Description
The selected dataset focuses on the challenges in ubiquitous data management within the IT domain. It includes discussions on mobility support, context awareness, collaboration support, adaptivity, and user interaction within ubiquitous computing environments. This dataset serves as the training material for fine-tuning the language model to specialize in IT-related text generation.

Project Steps
Dataset Selection:
Chose a relevant dataset containing unstructured text about the challenges and requirements in ubiquitous data management within the IT domain.

Environment Configuration:
Configured an AWS SageMaker IAM role to provide the necessary permissions for accessing AWS resources.
Set up an AWS SageMaker Notebook Instance for developing and running code.
Requested a GPU instance (ml.g5.2xlarge) for fine-tuning the language model.

Fine-tuning the Language Model:
Deployed the Meta Llama 2 7B foundation model on the AWS platform.
Used Python scripts to fine-tune the model on the selected IT domain dataset, enhancing its understanding of domain-specific language and concepts.

Model Deployment:
Deployed the fine-tuned language model on SageMaker to make it accessible for inference.

Testing and Evaluation:
Tested and evaluated the model's responses to domain-specific knowledge and text-generation tasks relevant to the IT domain.
Conducted a comparative analysis between the fine-tuned model and the original model to assess performance differences, aiming to validate the effectiveness of domain-specific fine-tuning.

Technologies Used
Amazon SageMaker: Utilized for building, training, and deploying machine learning models.
Meta Llama 2 7B Model: The foundation model used for fine-tuning, pre-trained for text-generation tasks, and adapted to the IT domain.
Python: Extensively used for scripting and interacting with AWS services, including SageMaker.
AWS Services: Leveraged various AWS services, including:
IAM: Managed access to AWS services securely.
EC2: Requested GPU instances for model training.
S3: Stored datasets and model artifacts.

Comparative Analysis
The project includes a detailed comparative analysis between the fine-tuned and original models. This analysis evaluates the models' performance, validating the effectiveness of fine-tuning the language model with domain-specific data.

Documentation and Submission
A comprehensive report documenting the process, challenges, and solutions is prepared and submitted for review.
