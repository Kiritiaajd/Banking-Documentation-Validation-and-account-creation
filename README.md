# Banking Documentation Validation and Account Creation

## Project Overview
This project automates **KYC (Know Your Customer)** document validation, **data extraction**, and **account creation** in the banking domain using advanced deep learning techniques. The system is designed to streamline the onboarding process by leveraging **computer vision** (CNNs) and **Optical Character Recognition (OCR)**, reducing manual intervention, and improving efficiency.

## Features
- **Document Identification**: Using **Object Detection** techniques to identify key KYC documents (e.g., identity proof, address proof).
- **OCR Integration**: Extracts relevant customer data from the documents for further processing.
- **Automatic Account Creation**: The extracted data is used to automatically create user accounts without human intervention.
- **Notification System**: Customers receive notifications about successful account creation.
- **Scalability**: Designed to be easily scalable with cloud-based deployment.
- **Deployment-Ready Architecture**: The solution includes scripts and configurations to deploy on cloud platforms like **AWS**.

## Folder Structure
- **`data/`**: Contains raw and pre-processed data used for model training and testing.
- **`models/`**: Stores trained models for object detection and OCR. Includes versions for easy updates and testing.
- **`scripts/`**: Utility scripts for data preprocessing, model training, and validation.
- **`logs/`**: Stores log files for tracking training progress, validation results, and any errors during execution.
- **`deployment/`**: Scripts and configurations for deploying the solution to cloud platforms like **AWS**. Includes **CI/CD** pipeline setups for smooth deployment.
- **`tests/`**: Unit tests and integration tests to ensure the robustness of the system.

## Technologies Used
- **Deep Learning**: Convolutional Neural Networks (CNN) for document identification and data extraction.
- **OCR**: For extracting information from KYC documents.
- **Cloud**: **AWS** Cloud APIs used for document processing and account creation automation.
- **Frameworks**: **PyTorch**, **OpenCV**, and **TensorFlow** for model development.
- **Databases**: **Cassandra** for storing customer data.
- **Deployment**: **Docker**, **Flask**, **Jenkins**, and **Kubernetes** for deployment and scaling.
- **Version Control**: **GitHub** for version control and collaboration.

## Results
- **Accuracy**: Achieved 90% classification accuracy in identifying KYC documents and extracting relevant data.
- **Time Efficiency**: Reduced manual verification time by 30%, improving operational efficiency.
- **Scalability**: Successfully implemented the system on AWS Cloud for automatic scaling.
- **Customer Experience**: Improved customer onboarding speed and accuracy, reducing errors and manual intervention.

## How to Use
1. Clone the repository:  
   `git clone https://github.com/kiritiaajd/Banking-Documentation-Validation.git`
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Run the training script for object detection and OCR:  
   `python scripts/train_model.py`
4. Deploy the system using Docker and Kubernetes:  
   Follow the deployment instructions in the `deployment/` folder.
5. Test the system using the sample test cases:  
   `python tests/test_system.py`

## Future Enhancements
- Implement **AI Ops** pipelines for efficient monitoring and maintenance.
- Expand the document validation system to handle more document types.
- Improve OCR accuracy with better pre-processing techniques and custom models.
