<h1 align="center">
  🌟 FaceFit - Facial Analysis for Customized Eyewear Fit
</h1>
<p align="center">Bangkit Product-Based Capstone Project | Team <b>C242-PS497</b> </p>

<p align="center">
  <img src="https://github.com/Capstone-FaceFit/capstone-facefit/blob/main/Logo.png" alt="logo" width="200" height="200">
</p>

## 🕹️ About FaceFit
FaceFit is a mobile application designed to enhance confidence in wearing glasses. By offering personalized recommendations for eyeglass frames that perfectly suit users' unique face shapes, the app aims to improve not just style but also user satisfaction. Leveraging AI technology, FaceFit analyzes face types to deliver a tailored and confidence-boosting eyewear experience.

<p align="center">
  <img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white">
  <img src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white">
  <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
  <img src="https://img.shields.io/badge/PIL-%23150458.svg?style=for-the-badge&logo=pypi&logoColor=white">
  <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">
  <img src="https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white">
  <img src="https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white">
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=javascript&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/OpenCV-5C3B6D?style=for-the-badge&logo=opencv&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/App_Engine-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white">
  <img src="https://img.shields.io/badge/Cloud_SQL-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white">
</p>

## 🎭 The Capstone Members
|            Member           | Student ID |        Path        |                    Role                    |                                                       GitHub Profile                                                      |
| :-------------------------: | :--------: | :----------------: | :----------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: |
| Nicolas Ray Amarco Tambunan  | M312B4KY3363  |  Machine Learning  | Machine Learning Engineer | [nrayjk](https://github.com/nrayjk) |
| Vitto Rendi Setiawan | M312B4KY4442   |  Machine Learning  | Machine Learning Engineer |   [vittorends](https://github.com/vittorends) |
| Zhafira Oktaviani | M312B4KX4614  | Machine Learning  | Machine Learning Engineer | [oktaveaz](https://github.com/oktaveaz) |
| Muhamad Ibnu Fadhil  | C200B4KY2617   |   Cloud Computing  |               Cloud Engineer              |  [gelaws-hub](https://github.com/gelaws-hub)         |
| Yosia Aser Camme | C200B4KY4548   |   Cloud Computing  |  Cloud Engineer        | [Shinkai91](https://github.com/Shinkai91) |
| Valentinus Aryo Saputro | A200B4KY4392   | Mobile Development |          Android Mobile Developer          |    [AxelineGit](https://github.com/AxelineGit)   |

## 📖 Learning Path Repository
For more information, check out each learning path to see the individual documentation:
- [Machine Learning](https://github.com/Capstone-FaceFit/ML)
- [Cloud Computing](https://github.com/Capstone-FaceFit/CC)
- [Mobile Development](https://github.com/Capstone-FaceFit/MD)

## 🔧 Tech Stack
1. **Machine Learning 🌐**: TensorFlow and Keras
2. **Mobile Development 📲**: Android (Kotlin)
3. **Cloud Computing 🛠️**: Google Cloud Platform (GCP)

## 🔎 Features
1. **Find Your Face Shape 👀**: FaceFit identifies whether your face is oval, round, square, or heart-shaped using a simple selfie.
2. **Personalized Glasses Recommendations 👗**: Get recommendations for eyeglass frames that perfectly match your face shape, enhancing your look.
3. **Explore Glasses Marketplace 🛒**: Discover ideal frames and access online stores for purchase.

## 🛡️ Endpoints
Here are the endpoints used by FaceFit:

### **Backend-API Endpoints**
#### **User Management**
- **`POST /register`**: Register a new user.
- **`POST /login`**: Authenticate a user and issue a JWT token.  
- **`GET /user`**: Retrieve user details (requires authentication).
- **`PATCH /user`**: Update user details (requires authentication).
- **`DELETE /user`**: Delete user account (requires authentication).

#### **Eyeglass Management**
- **`GET /eyeglass`**: Retrieve all eyeglass products (requires authentication).
- **`POST /eyeglass`**: Create a new eyeglass product (requires authentication).
- **`PATCH /eyeglass/:id`**: Update an existing eyeglass product by ID (requires authentication).
- **`GET /eyeglass/:id`**: Retrieve a specific eyeglass product by ID (requires authentication).

### **Backend-ML Endpoints**
- **`POST /predict`**: Accepts an image file and returns the recommended eyeglass frames based on the face shape.
- **`GET /health-check`**: Provides a health check to ensure the backend ML service is running.

## 🚨 Our Model Performance - Face Shape Detection

### Model Training Performance
![loss](https://github.com/user-attachments/assets/87bffe9e-1e2c-4324-9595-d57dc4f68b3f)
![accuracy](https://github.com/user-attachments/assets/d26709ab-5122-4026-9055-0eae16da9d66)

## 🌐 App Display
<div>
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_171733_com.app.facefit.jpg" alt="Screenshot 1" width="180" />
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_171659_com.app.facefit.jpg" alt="Screenshot 2" width="180" />
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_171702_com.app.facefit.jpg" alt="Screenshot 3" width="180" />
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_171645_com.app.facefit.jpg" alt="Screenshot 4" width="180" />
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_171651_com.app.facefit.jpg" alt="Screenshot 5" width="180" />
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_171909_com.app.facefit.jpg" alt="Screenshot 6" width="180" />
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_171923_com.app.facefit.jpg" alt="Screenshot 7" width="180" />
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_171934_com.app.facefit.jpg" alt="Screenshot 8" width="180" />
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_172449_com.app.facefit.jpg" alt="Screenshot 9" width="180" />
  <img src="https://github.com/Capstone-FaceFit/MD/blob/main/Display/Screenshot_20241211_171750_com.app.facefit.jpg" alt="Screenshot 10" width="180" />
</div>

### 🌐 Download Locally
Setting up the project for local usage.
1. Clone or download this repository:
    ```shell
    git clone https://github.com/Capstone-FaceFit/MD.git
    ```
    If using SSH:
    ```shell
    git clone git@github.com:Capstone-FaceFit/MD.git
    ```
2. Open using Android Studio.
3. Build Gradle, or change it to your preferences (recommended version: 8.x.x).
4. Emulate using an Android phone or emulator.
