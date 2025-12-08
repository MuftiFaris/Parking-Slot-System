# <p align="center">🚀 Parking Slot System with Maven and JavaFX</p>

---

## 📖 Brief Description

This project implements **Parking Slot System** in **Java** with an interactive **JavaFX and Maven**. You can log-in as admin or users and check the parking slot, admin can do alot of things but users only can see the spot . 

---

## 👥 Team Members

| Name                   | NIM / ID        |
| -------------------    | --------------- |
| Mufti Faris Murtadho   | L0124133        |
| Fairuz Siba Al Khirza  | L0124014        |
| Adrian Alviano Susatyo | L0124001        |

---

## 🧰 Technologies Used

- **Language**: Python 3.9+  
- **Libraries & Frameworks**:  
  - OpenCV  
  - NumPy  
  - scikit-learn  
  - Streamlit  
  - Pillow  
- **Tools & Platforms**:  
  - Git & GitHub  
  - GitHub Actions (CI/CD)

---

## 📁 Structure Project

```text
PBOProject/
├── pom.xml
├── src/
│   └── main/
│       ├── java/
│       │   └── org/
│       │       └── example/
│       │           ├── controller/
│       │           ├── model/
│       │           ├── service/
│       │           └── main/
│       └── resources/  
│           ├── fxml/
│           │   ├── login.fxml
│           │   ├── admin.fxml  
│           │   └── display.fxml
│           └── css/
│               └── style.css
└── README.md
```

---

## ⚙️ Setup Instructions

You can setup your project by cloning this repository and install the libraries above.

1. (Optional but recommended) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # macOS / Linux
   venv\Scripts\activate      # Windows

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
   Or, manually install each package:
   ```bash
   pip install opencv-python
   pip install numpy
   pip install scikit-learn
   pip install streamlit
   pip install pillow
   ```
   💡 Make sure you're using Python 3.9 or later to avoid compatibility issues.

3. How to Run the App
   ```bash
   streamlit run main.py
   ```
   You will see the web interface where you can:
   Upload a face image
   View preprocessing steps
   Get prediction results using Eigenface algorithm

---

## Screenshots
### Figure 1
MAIN MENU
![Figure 1: Main Menu](ss/main.png)

### Figure 2
EIGENFACE
![Figure 2: Result](ss/Eigenface.png)

### Figure 3
VARIANCE & MEAN FACE
![Figure 3: Result](ss/Variance.png)

### Figure 4
VEKTOR
![Figure 4: Result](ss/Vektor.png)

### Figure 5
RESULT
![Figure 5: Result](ss/result.png)

---

## NOTE
For the contents of the "test" folder it is necessary to download from https://www.kaggle.com/datasets/hereisburak/pins-face-recognition , which contains a downloadable face database.
