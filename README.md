```latex
\textbf{Job Salary Prediction Using Neural Networks and Model Comparisons} \\
\textbf{Situation:} Worked with a Kaggle dataset containing demographic, experience, and job title information to predict salaries, requiring preprocessing of both structured and unstructured data. \\
\textbf{Task:} Build and evaluate predictive models, including a PyTorch-based neural network, to determine factors influencing salary and assess the most effective approach. \\
\textbf{Action:} 
\begin{itemize}
    \item Cleaned and standardized data, removing nulls and harmonizing inconsistent categorical entries.
    \item Engineered features from job titles using \texttt{TF-IDF} vectorization and one-hot encoded categorical fields.
    \item Conducted exploratory data analysis, revealing correlations between education, gender, experience, and salary.
    \item Implemented a multi-layer neural network in PyTorch (128 $\rightarrow$ 64 $\rightarrow$ 1) with ReLU activations, trained with Adam optimizer and MSE loss.
    \item Compared performance against a \texttt{RandomForestRegressor} baseline with 100 estimators.
\end{itemize}
\textbf{Result:} Achieved a 97\% $R^2$ score with the Random Forest model, outperforming the neural network. Demonstrated that ensemble tree methods excel on structured tabular data, while the neural network captured trends but underfit without further tuning.

I used data from Kaggle to do this: https://www.kaggle.com/datasets/mohithsairamreddy/salary-data
```
