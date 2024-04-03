# KidneyDiagnose: Pioneering AI-driven Solutions for Advanced Renal Health Diagnosis
![_bb56a444-2b84-4d35-9b0c-061d72300533](https://github.com/Dishantkharkar/KidneyDiagnose-DL/assets/130529528/a887fc16-4951-497f-913f-5c39afedd4ba)

Welcome to KidneyDiagnose, a pioneering project that leverages AI-driven solutions for advanced renal health diagnosis. Our repository hosts the codebase and resources for this project, which focuses on early tumor detection in kidney CT scans using Convolutional Neural Networks (CNN) and other machine-learning techniques.

## About

KidneyDiagnose aims to revolutionize healthcare by employing state-of-the-art CNN models to detect and diagnose kidney-related issues, particularly tumors, at an early stage. By utilizing advanced AI techniques, we strive to improve the accuracy and efficiency of renal health diagnosis, ultimately leading to better patient outcomes.

## Features

- **Early Tumor Detection:** Our primary focus is on early detection of tumors in kidney CT scans, enabled by powerful CNN models.
- **Modular Coding:** The project is built with a modular approach, making it easy to understand, extend, and maintain.
- **End-to-End Solution:** KidneyDiagnose provides an end-to-end solution for renal health diagnosis, from data preprocessing to model training and deployment.
- **AI-driven Diagnosis:** Leveraging the power of artificial intelligence, our project offers cutting-edge diagnostic capabilities for renal health issues.

## Workflows

To ensure smooth development and deployment, follow these workflows:

1. **Update config.yaml:** Make necessary updates to the `config.yaml` file to configure project settings.

2. **Update secrets.yaml (Optional):** If needed, update the `secrets.yaml` file to manage sensitive information securely.

3. **Update params.yaml:** Adjust parameters in the `params.yaml` file to fine-tune model performance and behavior.

4. **Update the entity:** Update the entity (e.g., data classes, database schema) as required to reflect changes in the project.

5. **Update the configuration manager in src config:** Modify the configuration manager in the `src/config` directory to accommodate new configurations or changes.

6. **Update the components:** Update project components (e.g., data preprocessing, model architecture) to incorporate new features or improvements.

7. **Update the pipeline:** Modify the pipeline to integrate changes in data processing, model training, evaluation, and deployment.

8. **Update the main.py:** Update the `main.py` file to reflect changes in project structure, dependencies, or functionality.

9. **Update the dvc.yaml:** Make necessary updates to the `dvc.yaml` file to manage data versioning and pipeline dependencies.

10. **Update app.py:** If applicable, update the `app.py` file for web application deployment or integration.

## Getting Started

To get started with KidneyDiagnose, follow these steps:

1. **Clone the Repository:** Clone this repository to your local machine using `git clone https://github.com/KidneyDiagnose.git`.
2. **Create a Conda Environment:** After opening the repository, create a conda environment using the following command:
   ```bash
   conda create -n cnncls python=3.8 -y
   conda activate cnncls
3. **Install Requirements**: Install the required dependencies by running:
```bash
pip install -r requirements.txt
```
4. **Run the Application**: Finally, run the following command:
```bash
python main.py
```
5. **Open Local Host**: Open your local host and port to access the application.

## Contributors

- **Dishant Kharkar** ([LinkedIn](https://www.linkedin.com/in/dishant-kharkar-17b508273/))

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
