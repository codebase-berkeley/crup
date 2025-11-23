---
title: CRUP Final Project
nav_order: 3
layout: home
---

# <span style="color: #397DFF; font-weight: 350">CRUP Fall 2025 Final Project</span>

## <span style="color: #397DFF">Project Overview</span>
You will design and execute a complete Machine Learning project that answers a real-world question and present your findings through an interactive website. This project integrates both machine learning and software engineering skills.

## <span style="color: #397DFF">Core Requirements</span>
- Formulate a specific, real-world problem that can be solved with **Machine Learning**  
- Build and train an **ML model** using a real dataset  
- Create an **interactive website** that explains your process and allows users to interact with your model  

---

# <span style="color: #397DFF; font-weight: 350">Part A: Machine Learning Component</span>

## <span style="color: #397DFF">1. Problem Formulation & Dataset Selection</span>
Your task is to identify a clear, answerable question that requires machine learning to solve.

### Dataset Requirements
- Must come from a real dataset (e.g., **Kaggle**, **Hugging Face**)  
- Your project must be one of the following:  
  - **Classification** (e.g., “Will this customer churn?”)  
  - **Regression** (e.g., “What will this house sell for?”)  

---

## <span style="color: #397DFF">2. Complete ML Pipeline Implementation</span>
You must implement all stages of a professional ML workflow.

### a) Data Acquisition and Cleaning
- Download and load your dataset  
- Perform **Exploratory Data Analysis (EDA)** with visualizations and summary statistics  
- Handle missing values (remove, impute, etc.)  
- Encode categorical variables (e.g., one-hot encoding or label encoding)  

### b) Model Training and Hyperparameter Tuning
- Try multiple models appropriate for your task  
- Train each model  
- Tune hyperparameters using **Grid Search**, **Random Search**, etc.  

### c) Rigorous Model Evaluation

#### For Classification
- **F1 Score**  
- **AUC**  
- **Accuracy** (use carefully)  
- **Confusion Matrix**  

#### For Regression
- **R-squared (R²)**  
- **MAE**  
- **RMSE**  

### d) Artifact Preservation
- Save your trained model (e.g., using `pickle` or `torch.save`)  
- You will load this model into your website  

---

# <span style="color: #397DFF; font-weight: 350">Part B: Software Engineering Component</span>

## <span style="color: #397DFF">1. Public-Facing Website</span>
- Built using **React**  
- Serves as documentation + interactive demonstration  

## <span style="color: #397DFF">2. Required Website Content (Documentation)</span>

### a) Central Problem & Real-World Impact
Explain:
- What question you're answering  
- Why it matters  
- Who benefits  
- What real-world decisions your model could influence  

### b) Data Source & Nature
Include:
- Dataset link  
- What each row represents  
- Features included  
- Number of examples  
- Any limitations or biases  

### c) ML Methodology
Clarify:
- Which algorithms you tried  
- Which you chose  
- Why you chose it  
- What hyperparameters you tuned  

### d) Final Performance Metrics
Report:
- Your final evaluation metrics  
- A direct answer to your core question  
- Limitations + failure modes  

---

# <span style="color: #397DFF; font-weight: 350">3. Interactive Component (MANDATORY)</span>

Your website must include at least **one interactive ML-powered element**.

### Acceptable Options
- **Prediction Form** (user enters input → model predicts)  
- **Slider-Based Dynamic Prediction**  
- **Interactive Visualizations**  
- **Comparative Predictions (What-if Analysis)**  

---

# <span style="color: #397DFF; font-weight: 350">Part C: Deadlines & Deliverables</span>

## <span style="color: #397DFF">📅 Deadlines</span>
- **Research Proposal** — *Due: End of Thanksgiving Break*  
  - One paragraph  
  - Includes central question, dataset, and approach  
- **Final Project** — *Due: Before Banquet*  
  - Full ML pipeline  
  - Fully functional website  
  - Complete documentation  

## <span style="color: #397DFF">✅ Deliverables Checklist</span>
- [ ] **Research Proposal**  
- [ ] **ML Solution**  
  - Dataset acquired & cleaned  
  - Multiple models compared  
  - Best model selected  
  - Model evaluated  
  - Model saved  
- [ ] **Website Component**  
  - React website (public-facing)  
  - Full documentation  
  - At least one interactive component  
  - Accessible, clear design  

---

# <span style="color: #397DFF; font-weight: 350">🌟 Exemplary Projects for Inspiration</span>
- https://llm-attacks.org  
- https://thinkingmachines.ai/blog/modular-manifolds  
- Distill-style explorations:  
  - Feature Visualization  
  - Activation Atlas  
  - Handwriting with Neural Networks  
  - Building Blocks of Interpretability  
- https://distill.pub  

---

# <span style="color: #397DFF; font-weight: 350">Tips for Success</span>
- Choose a **focused** question  
- Select a **manageable dataset**  
- Document continuously  
- Build the interactive component early  
- Make explanations accessible to non-ML audiences  

Good luck! 🚀
