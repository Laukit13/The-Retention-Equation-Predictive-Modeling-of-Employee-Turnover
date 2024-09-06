# Employee Attrition Prediction Project

This project aims to predict employee attrition using machine learning techniques. It includes data preprocessing, exploratory data analysis (EDA), and a neural network model for prediction.

## Tools and Techniques

### Data Visualization and EDA
- Matplotlib
- Plotly
- Seaborn

### Data Manipulation and Preprocessing
- NumPy
- Pandas
- Min-Max Scaler (for data normalization)
- One-Hot Encoding (for categorical variables)

### Handling Imbalanced Data
- SMOTE (Synthetic Minority Over-sampling Technique)

### Machine Learning Model
- TensorFlow and Keras for building and training the neural network

## Project Structure

1. **Data Preprocessing**
   - Loading and cleaning the data
   - Handling missing values (if any)
   - Feature engineering
   - Normalization using Min-Max Scaler
   - One-Hot Encoding for categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions and relationships in the data
   - Identifying patterns and insights

3. **Handling Imbalanced Data**
   - Applying SMOTE to balance the dataset

4. **Model Building**
   - Creating a neural network using TensorFlow and Keras
   - Model architecture:
     - Input layer: 50 features
     - Hidden layers: 65 neurons (ReLU), 35 neurons (ReLU), 15 neurons (ReLU)
     - Output layer: 1 neuron (Sigmoid)

5. **Model Training**
   - Using Adam optimizer with a learning rate of 0.001
   - Binary cross-entropy loss function
   - Early stopping to prevent overfitting

6. **Model Evaluation**
   - Printing classification report to assess model performance

## Results

The model demonstrates excellent performance in predicting employee attrition. 

Key observations:
- The model achieves an overall accuracy of 90%.
- Both classes (0 and 1) show balanced performance with precision, recall, and F1-score all at or above 0.89.
- The model performs equally well for both attrition (1) and non-attrition (0) cases, which is particularly impressive given the initial class imbalance.

These results indicate that the model is highly effective at predicting employee attrition, with a good balance between identifying potential leavers and retainers.

## Future Work

- Experiment with different model architectures
- Try other machine learning algorithms (e.g., Random Forest, XGBoost)
- Perform feature importance analysis to identify key factors influencing attrition
- Collect more data or generate synthetic samples to further improve model performance
- Conduct a thorough error analysis to understand misclassified cases
- Develop an interpretable model to provide actionable insights for HR departments

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests as the project evolves.

## License

This project is licensed under the [MIT License](LICENSE).

