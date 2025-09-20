# Assignment_Classification_with_Machine_Learning_Models

 flowchart TD
    A[Start: Load Dataset] --> B[Data Understanding]
    B --> B1[Display first few rows]
    B --> B2[Identify input features & target]
    B --> B3[Check data types]
    B --> B4[Check missing values & duplicates]

    B4 --> C[Exploratory Data Analysis (EDA)]
    C --> C1[Plot target distribution]
    C --> C2[Feature vs Target visualizations]
    C --> C3[Compare categorical features]
    C --> C4[Correlation heatmap]

    C4 --> D[Data Preprocessing]
    D --> D1[Encode categorical variables]
    D --> D2[Scale numerical features]
    D --> D3[Handle missing values]
    D --> D4[Split into train/test sets]

    D4 --> E[Model Building]
    E --> E1[Decision Tree]
    E --> E2[Random Forest]
    E --> E3[AdaBoost]
    E --> E4[XGBoost]
    E --> E5[CatBoost]

    E1 --> F1[Evaluate: Accuracy, Precision, Recall, F1, Confusion Matrix]
    E2 --> F2
    E3 --> F3
    E4 --> F4
    E5 --> F5

    F1 --> G[Model Optimization]
    F2 --> G
    F3 --> G
    F4 --> G
    F5 --> G

    G --> G1[Hyperparameter Tuning (e.g. RF & XGB)]
    G1 --> G2[Compare Tuned vs Default]
    G2 --> G3[Discuss Overfitting/Underfitting]

    G3 --> H[Model Evaluation & Comparison]
    H --> H1[Performance Summary Table]
    H --> H2[Best Model Identification]
    H --> H3[Feature Importance Plots]

    H3 --> I[End]
