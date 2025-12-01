# TrayectorIA UNI 💡
This project aims to develop a traceability system to monitor and analyze students' academic performance from admission to graduation. Using data analysis techniques and predictive models, the project seeks to identify critical factors that influence academic success or dropout, enabling the implementation of early and effective interventions. Subsequently, through the use of Artificial Intelligence, it will generate recommendations and personalized programs to address those students most likely to drop out in order to improve their educational quality and bring them back on the path to success.

![image](https://github.com/user-attachments/assets/ca93ffd7-c26f-47a6-9783-0dc0052086b8)
![image](https://github.com/user-attachments/assets/6aa43b85-7961-4216-9b9d-ac55544cb279)

📁 Project Structure

The repository is organized into four main sections, following a clear and reproducible workflow for data analysis, model development, and reporting.

1. data/
Contains the datasets used for the public version of the project.
- 01.data_final.csv - Final processed dataset with anonymized and synthetic values for reproducibility.
- 02.images.csv - File containing metadata or links related to images used in the dashboard and documentation.

2. notebooks/
Jupyter notebooks that walk through the analytical and modeling workflow.
- 01_eda.ipynb - Exploratory data analysis.
- 02_data_prep.ipynb - Data preparation and cleansing workflow.
- 03_feature_engineering.ipynb - Creation and transformation of predictive features.
- 04_target_dropout.ipynb - Construction of the dropout target definition and labeling logic.
- 05_target_validation.ipynb - Validation of target consistency, distribution checks, and quality assurance.

3. src/
Source files for modeling and visualization.
- 01.model_train.ipynb - Model development (e.g., Logistic Regression, Decision Trees, and baseline comparisons).
- 02.model_test.ipynb - Model evaluation using accuracy, recall, F1-score, and AUC, including OOT-like validation.
- 03.trayectoria_uni.pbix - Power BI dashboard file illustrating key insights, model outputs, and institutional reporting views.

4. docs/
Documentation and communication materials.
- 01.presentation-trayectoria-uni.pdf - Final project presentation.
- 02.presentation-trayectoria-uni.pptx - Editable version of the final presentation.
- 03.methodology_flow.docx - Detailed methodology document describing the analytical pipeline and modeling framework.

📝 Overview
This project develops a machine-learning framework to predict university dropout risk using anonymized student records. The solution integrates:
- Exploratory data analysis
- Feature engineering
- Predictive modeling (ML)
- Validation and interpretability
- Dashboard visualization using Power BI

The goal is to provide institutions with early-warning signals and support evidence-based interventions that reduce student attrition.

📦 Requirements
- Tools & Environment
- Python 3.x
- Visual Studio Code (recommended)
- Power BI Desktop
- Jupyter Notebook

▶️ How to Use This Project
1. Set Up the Environment
- Clone this repository to your local machine.
- Install dependencies using the command above.
- Open the repository in Visual Studio Code or your preferred environment.

2. Run the Analysis
- Start with the notebooks in the notebooks/ folder to explore, clean, and prepare the data.
- Proceed to the src/ notebooks to train and evaluate predictive models.
- Open the .pbix file in Power BI Desktop to explore the dashboard and its visual insights.
Review the documentation in the docs/ folder for methodological details and presentation materials.

🤝 Contributing
If you would like to contribute:
- Fork the repository.
- Create a feature branch: git checkout -b feature/new-feature
- Commit your changes: git commit -am "Add new feature"
- Push the branch: git push origin feature/new-feature
- Open a Pull Request.

📬 Contact
For questions or suggestions, feel free to reach out Omar Cano Contreras
📧 omarcanoc23@gmail.com
🔗 www.linkedin.com/in/omarcanoc23/
