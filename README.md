Solution Summary
This project aimed to innovate the approach our company takes toward curating a wine selection that aligns with the refined tastes of our clientele. By developing a machine learning application within a Jupyter Notebook, we have enabled a data-driven evaluation of wine quality, hitherto reliant on subjective taste tests.
The implemented solution translates numerous physicochemical characteristics of wines into a quality score, drawing from a robust dataset. This has been encapsulated in a predictive model, deployed via a user-friendly Python-based application, allowing non-expert users to estimate wine quality accurately.
Data Summary
Data for this project was sourced from an extensive and well-regarded dataset comprising several physicochemical attributes of wines, alongside expert quality ratings. The collected data underwent a comprehensive preprocessing phase, including cleaning and normalization, to ensure it was primed for the machine learning process.
Throughout the development cycle, data integrity and processing quality were paramount. Careful management ensured the application could evaluate new data in real-time, providing immediate quality assessments.
Machine Learning
A Linear Regression model was selected for its simplicity and efficiency in predicting continuous outcomes, such as our quality scores. This model was trained, tested, and refined within the Jupyter Notebook environment, showcasing a transparent and iterative development process.
The machine learning pipeline was established using scikit-learn, a robust and widely-used Python library, which was instrumental in the model's development. This included data partitioning into training and test sets, model training, prediction generation, and performance evaluation using mean squared error as a metric for accuracy.
Validation
Validation of the model's predictive power was conducted on a separate testing set, ensuring that the evaluation of the model's effectiveness was unbiased and indicative of real-world performance. The mean squared error reported for test predictions reflects a robust model that is anticipated to perform well on unseen data.
Visualizations
The application includes a suite of visualizations, providing insightful and understandable representations of the dataset and the model's performance. Histograms and boxplots render the distribution of each feature, while density plots and pair plots offer deeper insights into the relationships between variables.
User Guide
* 		Open the Jupyter Notebook (WineQP.ipynb) in an environment that supports Python 3, such as Anaconda Navigator or directly through the JupyterLab interface.
* 		Install the required Python packages (pandas, matplotlib, seaborn, scikit-learn) if they are not already installed in your environment.
* 		Run each cell sequentially by pressing Shift + Enter, which will execute the code and display the results, including the data visualizations.
* 		To predict the quality of a new wine sample, navigate to the final cell containing the get_user_input_and_predict function.
* 		Enter the physicochemical properties when prompted. These should be numerical values corresponding to the features in the dataset.
* 		The predicted quality score will be output by the application, providing an instant assessment of the wine.
