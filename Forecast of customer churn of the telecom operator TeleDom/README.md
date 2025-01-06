# Project: Forecast of customer churn of the telecom operator TeleDom

## Project Description
The telecommunications company "TeleDom" aims to reduce customer churn. To achieve this, they plan to offer promotional codes and special conditions to customers who are likely to cancel their services. To identify such customers in advance, "TeleDom" needs a predictive model that forecasts whether a customer will terminate their contract. The operator's team has collected personal data, tariff information, and service usage details for some customers. Your task is to train a model to predict customer churn using this data.

## Service Description
The operator provides two main types of services:
- **Landline Telephone Service:** The phone can be connected to multiple lines simultaneously.
- **Internet Service:** There are two connection types available: DSL (Digital Subscriber Line) or Fiber Optic.

Additional services include:
- **Internet Security:** Antivirus (DeviceProtection) and unsafe site blocking (OnlineSecurity).
- **Dedicated Technical Support Line (TechSupport).**
- **Online Backup:** Cloud file storage for data backups.
- **Streaming TV and Movie Catalog (StreamingMovies).**

Customers can either pay monthly or sign a 1–2 year contract. Various payment methods are available, along with the option to receive an electronic bill.

## Data Description
The data consists of several files from different sources:
- `contract_new.csv`: Contract information.
- `personal_new.csv`: Personal customer data.
- `internet_new.csv`: Internet service details.
- `phone_new.csv`: Telephone service details.

### `contract_new.csv`
- `customerID`: Customer identifier.
- `BeginDate`: Contract start date.
- `EndDate`: Contract end date.
- `Type`: Payment type (annual, biennial, or monthly).
- `PaperlessBilling`: Electronic billing.
- `PaymentMethod`: Payment method.
- `MonthlyCharges`: Monthly expenses.
- `TotalCharges`: Total customer expenses.

### `personal_new.csv`
- `customerID`: Customer identifier.
- `gender`: Gender.
- `SeniorCitizen`: Whether the customer is a senior citizen.
- `Partner`: Whether the customer has a spouse.
- `Dependents`: Whether the customer has dependents.

### `internet_new.csv`
- `customerID`: Customer identifier.
- `InternetService`: Connection type.
- `OnlineSecurity`: Unsafe site blocking.
- `OnlineBackup`: Cloud storage for data backups.
- `DeviceProtection`: Antivirus.
- `TechSupport`: Dedicated technical support line.
- `StreamingTV`: Streaming TV.
- `StreamingMovies`: Movie catalog.

### `phone_new.csv`
- `customerID`: Customer identifier.
- `MultipleLines`: Phone connection to multiple lines.

The `customerID` column in all files contains the customer code. Contract information is valid as of February 1, 2020. The data is also available in the `/datasets/` folder in the simulator.

## Project Plan
Congratulations on completing many lessons! You are now graduates. While you're expected to outline and follow the main project stages, here's a brief plan to guide you:

### Step 1: Data Loading
- Load the data and perform an initial review.

### Step 2: Exploratory Data Analysis and Preprocessing
- Conduct an exploratory analysis for each DataFrame and preprocess if necessary. Determine which features are essential for model training.

### Step 3: Data Merging
- Merge selected features into a single DataFrame using the customer ID as the key.

### Step 4: Exploratory Analysis and Preprocessing of the Merged DataFrame
- Perform exploratory analysis on the merged DataFrame, visualize feature distributions, and preprocess as needed. Conduct a correlation analysis and consider generating new features.

### Step 5: Data Preparation
- Prepare the data for model training. Split the data into training and test sets, and consider scaling and encoding specific to the data and models.

### Step 6: Training Machine Learning Models
- Train at least two models. Optimize at least two hyperparameters for one model.

### Step 7: Best Model Selection
- Select the best model and evaluate its performance on the test set.

### Step 8: Conclusion and Business Recommendations
- Summarize the project: describe the main stages, key findings, and provide business recommendations based on the results.
