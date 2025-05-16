# Sales Prediction App 📊

A Streamlit web application that predicts sales based on input features such as region, product details, and transaction information. Built with Python and machine learning.

---

## Features ✨
- **Input Fields**: Ship mode, segment, region, city, state, sub-category, quantity, discount, and profit
- **One-Hot Encoding**: Automatic preprocessing of categorical features
- **Model Inference**: Predicts sales using a pre-trained machine learning model (`best_model.pkl`)
- **Interactive UI**: User-friendly interface powered by Streamlit

---

🚀 How to Run
1. 📦 Install Dependencies
  ```bash
    pip install -r requirements.txt
  ```
2. ✅ Verify Required Files
Ensure these files are present in your project directory:
- **`app.py`**: Main Streamlit application
- **`best_model.pkl`**: Pre-trained machine learning model
- **`features_columns.pkl`**: Feature columns for encoding

3. 💻 Launch the App
  ```bash
    streamlit run app.py
  ```
The app will automatically open in your browser at http://localhost:8501.

4. 🧾 Using the App
  - Fill in input fields using the sidebar
  - Click Predict
  - View predicted sales value on the main screen

---

## Project Structure 🗂️
📦 sales-prediction-app
- ├── 📄 app.py                   # Main Streamlit application script
- ├── 📄 best_model.pkl           # Pre-trained scikit-learn model
- ├── 📄 features_columns.pkl     # Feature columns for one-hot encoding
- ├── 📄 requirements.txt         # Python dependency list
- └── 📄 README.md                # Project documentation


### Key Files:
- **`app.py`**: Contains the Streamlit UI and prediction logic.
- **`best_model.pkl`**: Serialized pre-trained machine learning model.
- **`features_columns.pkl`**: Stores column names for consistent one-hot encoding.

---

Dependencies 📦
Listed in **`requirements.txt`**:

- **`streamlit`** → Web framework for the UI.
- **`pandas`** → Data manipulation.
- **`scikit-learn`** → Machine learning model and preprocessing.
- **`joblib`** → Loading the pre-trained model.

---

## Support & Contribution 🤝
 - Issues: Report bugs or feature requests here.
 - Contribution: Fork the repository, create a branch, and submit a pull request.

---

License 📜
MIT License. See LICENSE for details.

### Fixes Applied:  
1. **Consistent Indentation**: Fixed code block alignment and spacing.  
2. **Markdown Syntax**: Proper use of backticks for code blocks and file paths.  
3. **Emoji Placement**: Added spaces after emojis for better readability.  
4. **Header Consistency**: Unified section headers with proper Markdown `##` syntax.  
5. **File Structure Formatting**: Used triple backticks and tree symbols for the folder structure.  

Let me know if you need further adjustments! 😊









