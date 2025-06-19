# Executive-Simulation-AI: Machine Learning for Sustainable Development

**GitHub Repo:** [Executive-Simulation-AI](https://github.com/MykeShale/Executive-Simulation-AI)

---

## 🌍 Project Overview
This project is part of the PLP Week 2 Assignment: "Machine Learning Meets the UN Sustainable Development Goals (SDGs)". Our team designed an AI-driven solution to address a real-world challenge aligned with the UN SDGs, demonstrating how machine learning can drive positive global impact.

---

## 1. SDG Focus & Problem Statement

- **Chosen SDG:** SDG 3 – Good Health and Well-being
- **Problem:** Predicting malaria outbreaks using climate and health data to enable early intervention and resource allocation in vulnerable regions.

---

## 2. Team & Roles

| Name      | Role & Contribution                                                                 |
|-----------|-------------------------------------------------------------------------------------|
| Mike      | Data acquisition, preprocessing, and exploratory data analysis                      |
| Violet    | Model selection, training, and evaluation (supervised learning: Random Forest)      |
| Lukhanyo  | Visualization, result interpretation, and ethical reflection                        |
| Tshimo    | Documentation, presentation, and project coordination                               |

---

## 3. Machine Learning Approach

- **Type:** Supervised Learning
- **Algorithm:** Random Forest Classifier
- **Task:** Predict malaria outbreak risk (binary classification) based on climate and disease data.
- **Dataset:** `climate_disease.csv` (open-source, see `/malaria-outbreak-ai/data/`)
- **Tools:** Python, Jupyter Notebook, scikit-learn, pandas, matplotlib, seaborn

---

## 4. Workflow

1. **Data Collection & Preprocessing**
   - Cleaned and normalized climate and disease data.
   - Handled missing values and encoded categorical variables.
2. **Exploratory Data Analysis**
   - Visualized correlations between climate factors and malaria cases.
   - Identified key features influencing outbreaks.
3. **Model Training & Evaluation**
   - Split data into training and test sets.
   - Trained a Random Forest Classifier.
   - Evaluated using accuracy, precision, recall, and F1-score.
4. **Visualization**
   - Feature importance plot
   - Correlation heatmap
   - Regional case distribution
5. **Ethical Reflection**
   - Discussed data bias, fairness, and sustainability implications.

---

## 5. Results

- **Accuracy:** _[Insert value from notebook]_
- **Key Features:** Temperature, rainfall, humidity, previous case counts
- **Visualizations:**
  - ![Feature Importance](malaria-outbreak-ai/feature_importance.png)
  - ![Correlation Heatmap](malaria-outbreak-ai/correlation_heatmap.png)
  - ![Regional Cases](malaria-outbreak-ai/region_cases.png)

---

## 6. Ethical & Social Reflection

- **Bias:** Data may underrepresent remote or underreported regions, potentially skewing predictions.
- **Fairness:** The model aims to support equitable resource allocation, but must be regularly updated with diverse data.
- **Sustainability:** Early outbreak prediction enables targeted interventions, reducing disease burden and supporting healthier communities.

---

## 7. How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MykeShale/Executive-Simulation-AI.git
   cd Executive-Simulation-AI/malaria-outbreak-ai
   ```
2. **Install dependencies:**
   - Recommended: Use a virtual environment.
   - Install required packages:
     ```bash
     pip install -r requirements.txt
     ```
3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook malaria_model.ipynb
   ```
   - Follow the notebook cells to reproduce the analysis, model training, and visualizations.
4. **View Results:**
   - Screenshots and output plots are available in the `malaria-outbreak-ai/` directory and `screenshots/`.

---

## 8. Screenshots

See `/malaria-outbreak-ai/screenshots/` for demo images and results.

---

## 9. References

- [World Bank Open Data](https://data.worldbank.org/)
- [UN SDG Database](https://unstats.un.org/sdgs/)
- [Kaggle Datasets](https://www.kaggle.com/datasets)

---

## 10. License

This project is for educational purposes as part of the PLP Academy.

---

## 11. Team Contacts

- Mike: [GitHub](https://github.com/MykeShale)
- Violet: [Add link]
- Lukhanyo: (https://github.com/Luu-17)
- Tshimo: [Add link]

---

> “AI can be the bridge between innovation and sustainability.” — UN Tech Envoy

---

For more details, see the [`malaria_model.ipynb`](malaria-outbreak-ai/malaria_model.ipynb) notebook and project screenshots.

**[Project GitHub Link](https://github.com/MykeShale/Executive-Simulation-AI)**
