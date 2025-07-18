# 🧘🏻‍♂ Zenify: Mental Health & Self-Care Recommender System
## Team project

Zenify is a personalized mental health and self-care recommender system designed to help you find balance and tranquility in your daily life. By understanding your emotions, preferences, and needs, Zenify suggests tailored mindfulness activities, stress-relief techniques, and self-care resources to support your mental wellness journey.
At Zenify, we believe mental wellness should be accessible to everyone. Our mission is to provide intelligent, adaptive self-care recommendations that empower users to achieve a happier and healthier mind.

## Features

- Personalized self-care suggestions based on user responses.

- Mindfulness and stress-relief activity recommendations.

- Adaptive recommendations using machine learning.

- Clean, user-friendly interface with real-time feedback.

## Tech Stack

| Component                | Technology                          |
| ------------------------ | ----------------------------------- |
|  Frontend              | HTML, CSS                           |
|  Backend               | Python (Flask)                      |
|  Recommendation Engine | TensorFlow / Keras                  |
|  Database (optional)   | SQLite / MongoDB                    |
|  Package Management    | pip / requirements.txt              |
|  Data Preprocessing    | pandas, scikit-learn                |

## Requirements

- Python 3.8+

- pip (Python package manager)

- Virtualenv (recommended)

- [Optional] GPU for TensorFlow acceleration

#### Python Dependencies

    flask
    tensorflow
    pandas
    scikit-learn
    numpy
    
#### Install with:

    pip install -r requirements.txt

## Installation
### 1. Clone the repository
    git clone https://github.com/your-username/zenify.git
    cd zenify

### 2. Create Virtual Environment (recommended)
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install dependencies
    pip install -r requirements.txt

### 4. Run the app
    python app.py
    
### 5. Open your browser at http://127.0.0.1:5000

## System Architecture

           +-------------------------+
           |   User Profile Input    |
           +-------------------------+
                      |
                      v
     +-----------------------------------------+
     | Preprocessing & Feature Engineering     |
     +-----------------------------------------+
                      |
          +---------------------------+
          |   Hybrid Recommender      |
          |  (Content + Collaborative)|
          +---------------------------+
                      |
                      v
         +-------------------------------+
         |  Personalized Recommendations |
         +-------------------------------+
                      |
                      v
           +-------------------------+
           |     Web Interface       |
           +-------------------------+

##  Performance Optimizations
- Used embeddings for user/item representations
- Hybrid model combines content similarity with user behavior
- Lightweight Flask server for rapid deployment
- Batch prediction for faster recommendations

## Troubleshooting
| Issue                              | Solution                              |
| ---------------------------------- | ------------------------------------- |
| `ModuleNotFoundError: flask`       | Run `pip install flask`               |
| `No module named tensorflow.keras` | Run `pip install tensorflow`          |
| VS Code showing missing imports    | Check Python Interpreter & Virtualenv |
| App not opening on browser         | Ensure Flask is running on port 5000  |

## Results

![image](https://github.com/user-attachments/assets/a4041e8d-0fe0-482f-b1d4-c1e7f1ea6b13)

![image](https://github.com/user-attachments/assets/d87e26f7-698a-4681-84b0-0f25fdbfbcb4)

![image](https://github.com/user-attachments/assets/6a90f394-f7fa-4882-9f15-40cf39796cc9)

![image](https://github.com/user-attachments/assets/8ccac7f8-3faa-4245-b416-2640534a5c49)

![image](https://github.com/user-attachments/assets/f14e367d-47a0-4502-aab1-1d475241945f)


##  Notes
Dataset: 96 user survey responses (processed and cleaned)

Hybrid model balances personalization and general trends

Designed for college-level projects but can scale further

