🏥 Overview

POOC is a web-based healthcare application designed to predict the risk of Post-Operative Pulmonary Complications (PPC) in surgical patients using clinical parameters and machine learning models.

The system assists doctors and hospitals in early risk assessment, prevention planning, and improved patient outcomes.

<img width="1042" height="296" alt="Screenshot 2026-02-02 110946" src="https://github.com/user-attachments/assets/0dbdb133-c36d-4f5e-b9ad-1605e643481e" />

✨ Features

✅ Patient data entry form
✅ Automated PPC risk prediction using ML
✅ Rule-based + ML hybrid model
✅ Risk score calculation (Low / Medium / High)
✅ Doctor dashboard
✅ Secure authentication system
✅ Medical report generation
✅ Responsive & clean UI
✅ Django backend with database storage


![Alt text]<img width="209" height="712" alt="Screenshot 2026-01-20 153551" src="https://github.com/user-attachments/assets/1b076486-b5d5-4776-9158-2b9046e95141" />

🧠 How It Works

1. Doctor enters patient details:

 - Age, BMI

 - Smoking status

 - COPD/Asthma history

 - Surgery duration

 - Oxygen levels

 - Comorbidities

2. System processes:

 - Preprocessing

 - Feature extraction

 - ML prediction

3. Output:

 - Risk percentage

 - Risk category

 - Preventive recommendations

🏗️ Tech Stack
1. Backend
 - Python
 - Django
 - Django REST Framework
 - Qwen LLM model finetuned
 - MYSQL workbench

2. Frontend
 - XML
 - Java

3.Deployment
 - playstore
 - college server

📂 Project Structure
POOC/
│── manage.py
│── requirements.txt
│── README.md
│
├── pooc/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── app/
    ├── models.py
    ├── views.py
    ├── forms.py
    ├── ml_model.py
    ├── templates/
    └── static/


📊 Dataset Used

 - Clinical patient parameters

 - Surgery details

 - Pulmonary history

 - Postoperative outcomes

🧪 ML Model

+ Algorithms tested:

 - LLM qwen

Best model selected based on:

 - Accuracy

 - Precision

 - Recall

 - F1-score

   
![Alt text]<img width="530" height="716" alt="Screenshot 2026-02-02 120229" src="https://github.com/user-attachments/assets/254c7f5b-9889-4219-868e-6f28529ed300" />
<img width="319" height="713" alt="Screenshot 2026-01-20 153419" src="https://github.com/user-attachments/assets/fc2feca6-e39e-4596-bcc8-ca7f1e1ce7db" />


📈 Output Example


 - Patient	Risk Score	Category
+ P001	18%	Low
+ P002	56%	Medium
+ P003	82%	High


🔐 Security Features

 - User authentication

 - Role-based access

 - Secure form validation

 - Protected medical records

🚀 Future Improvements

 - Deep learning model integration

+ Real-time hospital dashboard

 - PDF report export

 - API integration

 - Mobile app support

👨‍💻 Author

S VENKATA SAINADH REDDY
B.R Final Year Project
GitHub: [https://github.com/yourusername](https://github.com/svsainadhreddy/SIMATS_PDD/)

📜 License

This project is developed for academic and research purposes.

❤️ Acknowledgements

- Django Documentation
- Scikit-learn
- Medical research references for PPC risk.
- modern Risk pridiction for Postoperational PUlmanary Complications.
  





