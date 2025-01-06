# Project: Customer Age Determination

## Project Description
The "Khleb-Sol" supermarket chain is implementing a computer vision system to process customer photos. The goal is to determine the age of customers, which will help to:
- Analyze purchases and suggest products that may interest the respective age group.
- Ensure cashiers adhere to regulations when selling alcohol.

To achieve this, a model needs to be developed that can estimate a person's age from a photograph.

## Project Stages
1. **Exploratory Data Analysis (EDA):**
   - Analyzing the structure and size of the dataset.
   - Plotting the age distribution graph.
   - Visual inspection of 10-15 images from the dataset.
   - Drawing conclusions about how the data will impact model training.
2. **Data Preparation for Training.**
3. **Neural Network Training and Quality Evaluation.**
4. **Final Presentation of the Analysis, Code, and Results.**

## Data Description
The data is sourced from the ChaLearn Looking at People website and is located in the `/datasets/faces/` folder. Available resources:
- A folder with images: `/final_files`
- A CSV file `labels.csv` with the following columns:
  - `file_name`: the name of the image file.
  - `real_age`: the actual age of the person in the photo.

The `ImageDataGenerator` method with the `flow_from_dataframe()` function is used to extract data.

## Exploratory Data Analysis (EDA)
### Analysis Steps
1. **Dataset Size Analysis:**
   - Assessing the total number of images and the age distribution.
   
2. **Age Distribution Graph:**
   - Creating a histogram to visualize the age distribution.

3. **Visual Inspection of Photos:**
   - Displaying 10-15 images from the dataset to check their quality and variety.
