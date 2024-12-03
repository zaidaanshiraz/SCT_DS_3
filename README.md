# Decision Tree Classifier for Predicting Customer Purchases

This project involves building a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The model is trained using the **Bank Marketing Dataset** from the UCI Machine Learning Repository. 

### Dataset

The dataset used for this project is the [Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing) from the UCI Machine Learning Repository. It contains data collected from a marketing campaign of a Portuguese banking institution. The goal of the campaign was to predict if a customer would subscribe to a term deposit based on various features like age, job, marital status, education, and past campaign interactions.

- **Data Features**: 
    - `age`: Age of the customer
    - `job`: Type of job (e.g., admin, blue-collar, technician)
    - `marital`: Marital status
    - `education`: Level of education
    - `default`: Whether the customer has credit in default
    - `housing`: Whether the customer has a housing loan
    - `loan`: Whether the customer has a personal loan
    - `contact`: Type of communication used (e.g., cellular, telephone)
    - `month`: Last contact month of the year
    - `day_of_week`: Last contact day of the week
    - `duration`: Duration of the last contact in seconds
    - `campaign`: Number of contacts performed during this campaign
    - `pdays`: Number of days since the client was last contacted from a previous campaign
    - `previous`: Number of contacts performed before this campaign
    - `poutcome`: Outcome of the previous marketing campaign
    - `y`: Whether the client subscribed to a term deposit (`yes` or `no`)

### Objective

The goal is to predict the value of the `y` column, which indicates whether a customer subscribed to a term deposit. This is a binary classification problem with two possible outcomes: `yes` or `no`.

### Steps Involved

1. **Data Preprocessing**:
    - Load and inspect the dataset.
    - Handle missing values (if any).
    - Encode categorical variables into numeric values (using `LabelEncoder`).
    - Split the dataset into training and testing sets.

2. **Modeling**:
    - Train a **Decision Tree Classifier** using the training dataset.
    - Evaluate the model using various metrics such as accuracy, confusion matrix, and classification report.

3. **Visualization**:
    - Visualize the trained Decision Tree using `plot_tree`.
    - Generate a confusion matrix heatmap to visualize performance.
    - Create additional visualizations such as feature importance, ROC curve, and precision-recall curve to further evaluate the model.
    - Name: Mohammed Zaidaan Shiraz Email: zaidaanshiraz8@gmail.com GitHub: zaidaanshiraz
