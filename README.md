
# AI-powered Text Classification and Requirement Allocation

This project introduces an AI-powered solution to automate text classification and requirement allocation, which significantly improves the efficiency of the requirements management process at Kiewit. The system employs a combination of custom-made neural networks and OpenAI's API to achieve accurate and automated categorization of project-related text.

**Note:** The implementation details and source code for the custom neural network using TensorFlow and PyTorch are not publicly available in this repository due to proprietary considerations.

## Overview

The project addresses the challenge of manually categorizing and allocating information and requirements from large volumes of project-related text. Traditionally, this process could involve three months of work by a team of three people for projects with 70,000+ rows of content. With our AI-powered solution, this cumbersome task is now automated, saving valuable time and resources.

The automation process comprises two major steps:

1. **Text Classification**: A custom-made neural network trained on previous project data using TensorFlow and PyTorch is utilized to automatically designate whether a piece of text is "Information" or "Requirement." This step significantly reduces the need for manual intervention.

2. **Requirement Type and Discipline Allocation**: After the text is classified, the system further identifies the specific "Requirement Type" and the "Discipline" to which the text belongs on the project. This step is accomplished using OpenAI's powerful API and leveraging various prompts.

## Features

- **AI-driven Text Classification**: The neural network uses state-of-the-art machine learning techniques to accurately distinguish between "Information" and "Requirement" in project text.

- **Automated Requirement Allocation**: After text classification, the system employs OpenAI's API and prompts to automatically determine the "Requirement Type" and the "Discipline" associated with each piece of text.

- **Improved Efficiency**: The automation of text classification and requirement allocation significantly reduces the time and effort required for requirements management on large projects.

## Demo Videos

1. **Text Classification and Requirement Allocation in Action**:

https://github.com/benjakson/Requirements_Management_AI/assets/124751174/28206db6-f12c-4940-a0a0-5ffdcf24855e

3. **Custom Neural Network Working**: 

https://github.com/benjakson/Requirements_Management_AI/assets/124751174/234c1ab0-23d3-4900-9279-2abd5bab8214



## Model Images

1. **AI Architecture Overview**: ![AI Architecture]
  
   <img width="407" alt="Screenshot 2023-07-29 at 3 32 47 PM" src="https://github.com/benjakson/Requirements_Management_AI/assets/124751174/13a95169-636f-412c-9764-ce9b6fbe539a">


<img width="875" alt="Screenshot 2023-07-29 at 3 32 16 PM" src="https://github.com/benjakson/Requirements_Management_AI/assets/124751174/314dcd42-4cee-4804-9ea5-9ddc0cac7745">




## Contact

For inquiries or more information about this project and the AI-driven text classification and requirement allocation system, please reach out to the Kiewit team.

For more information about Kiewit and our projects, visit our [website](https://www.kiewit.com/).

---
*Disclaimer: This repository showcases the project's description and high-level overview. The actual source code and implementation details are not included here due to proprietary reasons and company policies.*
