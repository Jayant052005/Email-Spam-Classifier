# INTERN ID : CITS1359
# NAME : JAYANT KUMAR SHARMA
# NO OF WEEKS : 6 WEEKS
# PROJECT NAME : EMAIL SPAM CLASSIFIER

# 📧 Email Spam Classifier 
A machine learning-based Email Spam Classifier developed using **Python**, **Flask**, **HTML**, and **CSS**. The application analyzes email text and predicts whether the message is **Spam** or **Not Spam (Ham)** using a trained machine learning model.

## 🚀 Features 
- User-friendly web interface
- Detects spam and non-spam emails
- Machine Learning-based classification
- Fast and accurate predictions
- Pre-trained model for instant results

 ## 🛠️ Technologies Used 
 - Python
 - Flask
 - Scikit-learn
 - HTML5
 - CSS3
 - Pickle (.pkl) Models
 
  ## 📂 Project Structure 
Email-Spam-Classifier/
├── app.py 
├── train_model.py 
├── spam_model.pkl 
├── vectorizer.pkl 
├── documentation.txt 
├── README.md 
├── templates/ 
│      └── index.html
├── static/
      ├── style.css
      └── images

## ⚙️ Installation 
### 1. Clone the Repository ```bash git clone https://github.com/your-username/Email-Spam-Classifier.git
### 2. Navigate to Project Directory
cd Email-Spam-Classifier
### 3. Install Required Libraries
pip install flask scikit-learn pandas numpy
### 4. Run the Application
python app.py 
### 5. Open Browser
http://127.0.0.1:5000 

## 📖 How It Works
- User enters an email message.
- The text is processed using a trained vectorizer.
- The machine learning model analyzes the text.
- The application predicts: 
       Spam
       Not Spam (Ham)
- The result is displayed instantly on the webpage.

## 🤖 Machine Learning Model
The project uses:
- Text Vectorization (TF-IDF / Count Vectorizer)
- Scikit-learn Classification Model
- Serialized model files (spam_model.pkl and vectorizer.pkl) for prediction

## 📸 Screenshots
- Project screenshots are available in the screenshots folder.

## 🔮 Future Improvements
- Support for bulk email classification
- Confidence score for predictions
- Email attachment analysis
- Real-time spam filtering
- Deep Learning integration

## 👨‍💻 Author
- Jayant Kumar Sharma
- GitHub: https://github.com/Jayant052005

## 📜 License
- This project is developed for educational and learning purposes.
