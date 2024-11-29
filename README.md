# Diamond Price Prediction Analysis Using Regression
![diamond image](./diamond.jpg)

## Objective  
The objective of this project is to analyze diamond characteristics and develop a predictive model to estimate the prices of diamonds using regression techniques.

---

## About the Dataset  
The dataset contains 53,940 rows and 10 variables, providing information on various physical and qualitative attributes of diamonds:

| **Feature** | **Description** |
|-------------|-----------------|
| **price**   | Price in US dollars (\$326–\$18,823). |
| **carat**   | Weight of the diamond (0.2–5.01). |
| **cut**     | Quality of the cut (Fair, Good, Very Good, Premium, Ideal). |
| **color**   | Diamond color, graded from J (worst) to D (best). |
| **clarity** | Clarity of the diamond, graded from I1 (worst) to IF (best). |
| **x**       | Length in mm (0–10.74). |
| **y**       | Width in mm (0–58.9). |
| **z**       | Depth in mm (0–31.8). |
| **depth**   | Total depth percentage = 2 * z / (x + y) (43–79). |
| **table**   | Width of the top of the diamond relative to the widest point (43–95). |

---

## Project Highlights  

### 1. **Exploratory Data Analysis (EDA)**  
- Visualized relationships between diamond features and price.  
- Assessed feature distributions, outliers, and correlations.  
- Identified key factors influencing diamond prices.

### 2. **Data Preprocessing**  
- Handled missing and duplicate data.  
- Encoded categorical features (e.g., `cut`, `color`, `clarity`).  
- Normalized numerical features to improve model performance.  

### 3. **Feature Engineering**  
- Analyzed interactions between features like `carat`, `cut`, and `color`.  
- Created additional derived features to enhance predictions.

### 4. **Model Development**  
- Employed regression techniques including:  
  - **Linear Regression**  
  - **Ridge and Lasso Regression**  
  - **Decision Tree Regression**  
  - **Random Forest Regression**  
- Evaluated models using metrics such as **R² score**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.

### 5. **Model Optimization**  
- Fine-tuned hyperparameters to improve model accuracy.  
- Compared model performances and selected the best-performing model.  

---

## Results  
- Developed a predictive model capable of estimating diamond prices with high accuracy.  
- Identified that `carat`, `cut`, and `color` significantly impact diamond prices.  

---

## Tools and Technologies  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

---

## How to Run  
1. Clone this repository:  
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script to analyze and predict diamond prices.  

---

## Future Scope  
- Implement advanced regression techniques like Gradient Boosting or Neural Networks.  
- Expand dataset for a more diverse range of diamonds.  
- Develop a web-based interface for real-time price prediction.  

---

## Contact  
For queries, feel free to reach out:  
**Email**: [Your Email Address]  
**LinkedIn**: [Your LinkedIn Profile]  

---  
