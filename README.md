# Explainable_AI

This repository contains implementations of various explainable AI techniques applied to text, image, and tabular data. The notebooks explore feature attributions, sensitivity analysis, and model explanation tools to enhance the transparency and understanding of machine learning models.

Model Explanation Techniques

- `deep_explainer.ipynb`  
  SHAP DeepExplainer applied to neural networks for feature attribution.
- `linear_explainers.ipynb`  
  SHAP explanations for linear models.
- `tree_explainer.ipynb`  
  SHAP TreeExplainer for interpreting tree-based models like XGBoost, LightGBM.
- `shapp.ipynb`  
  General overview and demonstration of SHAP library functionalities.
- `Featureimportance_Sensitivityanal.ipynb`  
  Global feature importance and local sensitivity analysis.
- `PDP.ipynb`  
  Partial Dependence Plots (PDPs) for interpreting feature impact.

Image Explanations

- `GRAD_CAM.ipynb`  
  Grad-CAM visualizations for CNNs on image data.
- `Guided_propagation.ipynb`  
  Guided backpropagation for visualizing important pixels.
- `EDA_on_Images.ipynb`  
  Exploratory analysis on image datasets before explanation.

  Text and Tabular Explanations with LIME

- `Lime_Titanic.ipynb`  
  LIME explanations on the Titanic survival prediction (tabular data).
- `Lime_Oxford.ipynb`  
  LIME applied to image classification (Oxford dataset).
- `Lime_for_Text.ipynb`  
  LIME for text classification model interpretability.

Exploratory Data Analysis

- `EDA_on_IMDB.ipynb`  
  EDA on the IMDB text dataset for sentiment classification.

TCAV (Testing with Concept Activation Vectors)

- `TCAV1.ipynb`  
  Introduction and setup for TCAV.
- `TCAV2.ipynb`  
  Concept-based sensitivity analysis.
- `TCAV3.ipynb`  
  Advanced TCAV workflows for interpretability.

Tools & Libraries

- SHAP
- LIME
- TCAV
- Matplotlib, Seaborn
- TensorFlow / Keras / PyTorch
- Scikit-learn

