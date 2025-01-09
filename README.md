# 🚀 ML-Normalization

This repository contains implementations of various **normalization techniques** used in machine learning to preprocess data. Normalization ensures that the data scales properly, improving the performance of machine learning algorithms.

## 📂 Contents

- **📘 Notebooks**:
  - 📊 `feature-scaling-min-max-scaling.ipynb`: Demonstrates **Min-Max Scaling**.
  - 📏 `Mean-Max-Scaling.ipynb`: Implements **Mean-Max Scaling**.
  - 📈 `Max-Abs-Scaling.ipynb`: Explains **Max-Abs Scaling**.
  - 📉 `RobustScaling.ipynb`: Covers **Robust Scaling**.

- **📜 License**:
  - The repository is licensed under the **MIT License**.

## 🛠️ Techniques Covered

1. **⚖️ Min-Max Scaling**  
   - Scales the data to a fixed range, typically [0, 1].
   - [🔗 Example Notebook](https://www.kaggle.com/himelsarder/feature-scaling-min-max-scaling)

2. **📏 Mean-Max Scaling**  
   - Normalizes data using the mean and maximum values.

3. **📈 Max-Abs Scaling**  
   - Scales each feature by its maximum absolute value.

4. **🛡️ Robust Scaling**  
   - Removes the median and scales data according to the interquartile range, making it robust to outliers.

## 📝 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Himel-Sarder/ML-Normalization.git
   ```
2. Navigate to the repository:
   ```bash
   cd ML-Normalization
   ```
3. Open the desired Jupyter Notebook to explore and run the examples:
   ```bash
   jupyter notebook
   ```

## 📦 Requirements

- 🐍 Python 3.x
- 📓 Jupyter Notebook
- Required libraries:
  - 🧮 NumPy
  - 📊 Pandas
  - 🤖 Scikit-learn
  - 🎨 Matplotlib (optional for visualization)

Install the required libraries using:
```bash
pip install numpy pandas scikit-learn matplotlib
```

![image](https://github.com/user-attachments/assets/055d34c0-af35-4e62-b0cd-be127a8bbdc3)

## 🤝 Contributing

Contributions are welcome! 🎉 If you have suggestions for improvements or additional techniques, feel free to fork the repository and create a pull request.

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
