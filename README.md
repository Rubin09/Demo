# Flower Classification App 🌸

This **Flower Classification App** predicts the species of a flower based on its physical attributes (sepal length, sepal width, petal length, and petal width). The app uses a pre-trained machine learning model to classify the flower species, making it easy and interactive for users to get predictions.

---

## Features 🚀

- User-friendly interface built using **Streamlit**.
- Predicts flower species based on:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Leverages a pre-trained **Linear Regression Model** for prediction.
- Real-time predictions based on user inputs.

---

## Technologies Used 🛠️

- **Python**
- **Streamlit**: For the web interface.
- **Joblib**: For loading the saved model and feature data.
- **Pandas**: For data manipulation and input handling.

---

## Installation and Setup ⚙️

### Prerequisites

Ensure you have the following installed on your system:

- **Python 3.8+**
- **Streamlit**

### Steps to Run the Application

### Step 3: Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

#### Step 2: Place the necessary files in the root directory

Make sure the following files are in the same directory as the `app.py` script:

- `iris_linear.pkl`: Pre-trained model file.
- `iris_cols.pkl`: File containing the feature names.

#### Step 3: Run the Streamlit application

Use the following command to start the Streamlit app:

```bash
streamlit run app.py

```
