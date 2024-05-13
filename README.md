**T-5000: Heart Failure Prediction**

This project, named T-5000, provides a web application built with Flask that assists in predicting the risk of heart failure.

**Functionality**

1. **User Interface:** The user interacts with a simple Flask web interface.
2. **Data Input:** Users are prompted to enter four key factors:
   - Age
   - Ejection Fraction (a measure of heart pumping strength)
   - Serum Sodium (an electrolyte level)
   - Serum Creatinine (a kidney function marker)
3. **Prediction:** Upon submission, the values are fed into a pre-trained Support Vector Machine (SVM) model.
4. **Output:** The model predicts the likelihood of the user experiencing heart failure. It's important to note that the overall accuracy of this model is 75%.

**Disclaimer**

This project is intended for educational and informational purposes only. It should not be used for self-diagnosis or medical decision-making. Always consult a qualified healthcare professional for any concerns about your health.

**Technology Stack**

- **Frontend:** Flask (Python web framework)
- **Backend:** Python (programming language)
- **Machine Learning Model:** SVM (Support Vector Machine)

**How to Use**

1. **Prerequisites:**
   - Python 3.5 or above installed on your system.
   - Basic understanding of Flask is helpful.
2. **Running the Project:**
   - Clone the repository: `git clone https://heyaryahere/t-5000.git`
   - Navigate to the project directory: `cd t-5000`
   - Run the Flask development server: `python app.py` (replace with your main script if different)
3. **Access the Application:**
   - Open your web browser and navigate to `http://127.0.0.1:5000/` (or the port specified by your server).

**Limitations**

- The 75% accuracy of the model means there's a 25% chance of an incorrect prediction.
- The model is based on a pre-trained dataset and may not generalize well to all individuals.

**Further Development**

- Consider incorporating a risk score instead of a binary prediction (high/low risk).
- Explore collecting additional health factors for more comprehensive prediction.
- Implement data validation and error handling on the user interface.

**Disclaimer**

The information provided in this README is based on the details you shared. It's recommended to adjust the instructions as needed for your specific project setup.
