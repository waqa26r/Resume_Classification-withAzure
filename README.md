# Resume_Classification-withAzure

███╗   ██╗██╗   ██╗██╗  ██╗███████╗██████╗ ██╗   ██╗
████╗  ██║██║   ██║██║  ██║██╔════╝██╔══██╗╚██╗ ██╔╝
██╔██╗ ██║██║   ██║███████║█████╗  ██████╔╝ ╚████╔╝ 
██║╚██╗██║╚██╗ ██╔╝██╔══██║██╔══╝  ██╔══██╗  ╚██╔╝  
██║ ╚████║ ╚████╔╝ ██║  ██║███████╗██║  ██║   ██║   
╚═╝  ╚═══╝  ╚═══╝  ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝   ╚═╝   

# Resume Classification with Azure Services


![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![License: waqa26r](https://img.shields.io/badge/License-waqa26r-<COLOR>.svg)

[License: waqa26r](https://github.com/waqa26r)


-Blog [License: waqa26r](https://waqa26r.blogspot.com/)




## Overview

This repository contains a project for classifying resumes based on the skills mentioned in them. The classification is done using Azure services and various technologies, including machine learning, big data analytics, and streamlit for GUI implementation. The main objective of this project is to help users quickly identify the category of a resume, such as Web Development, Machine Learning, or Big Data Analytics, by simply uploading the resume through the frontend.

## Features

- Resume classification based on skills: The project uses machine learning algorithms to automatically classify resumes into different categories based on the skills mentioned in them.

- Multiple classification categories: Resumes can be classified into various categories like Web Development, Machine Learning, Big Data Analytics, and more, depending on the skills found in the resume.

- Excel file generation: The project generates an Excel file containing the list of classified resumes along with their respective categories, making it easy for users to keep track of the results.

- Streamlit GUI: A user-friendly frontend is developed using Streamlit, allowing users with limited technical knowledge to upload their resume and receive the classified resume in PDF format.

## Requirements

To run the project locally, you'll need the following:

- Python 3.x
- Azure account with access to the necessary services (e.g., Azure Machine Learning, Azure Storage)
- Streamlit library (Install using `pip install streamlit`)
- Other necessary libraries specified in the `requirements.txt` file

## Getting Started

1. Clone the repository to your local machine using the following command:

## Git Repositories
git clone https://github.com/yourusername/resume-classification-azure.git


2. Set up Azure services: Ensure you have an Azure account and create the necessary services like Azure Machine Learning and Azure Storage.

3. Configure Azure credentials: Update the credentials or API keys in the project files where needed to connect to Azure services.

4. Install the required dependencies by running:

pip install -r requirements.txt


5. Run the Streamlit app:


6. Access the application on your browser at `http://localhost:8501` and use the frontend to upload resumes for classification.

## Project Structure

The repository is organized as follows:

- `app.py`: The Streamlit application frontend code.
- `classifier.py`: The machine learning classification algorithms.
- `generate_excel.py`: Script to generate the Excel file with classified resumes.
- `data`: Contains sample resumes used for testing.
- `models`: Stores pre-trained machine learning models (if any).
- `output`: Contains the generated Excel file and classified resume PDFs.
- `requirements.txt`: Lists all the required Python libraries and dependencies.

## Contributions

Contributions to this project are welcome! If you have any ideas, bug fixes, or improvements, feel free to submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to contact the project maintainer:

- Name: Waqar Farooqui
- Email: waqarnizamuddin@gmail.com

Thank you for using our Resume Classification with Azure Services project! We hope it proves to be useful for your needs. Happy classifying!


