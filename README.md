**Kaushalya-Karnataka**

**Project File** https://drive.google.com/drive/folders/1TywArcHbwDOKGTRVPiMP9cdZGXLar0zj?usp=sharing

Connecting Skilled Professionals with Local Opportunities

📝 **Project Overview**

Kaushalya-Karnataka is a mobile marketplace designed to bridge the gap between local skilled laborers (electricians, plumbers, painters) and residents in Karnataka. The app provides a seamless interface for workers to showcase their service cards and portfolios while allowing users to discover and contact verified professionals via WhatsApp integration


🚀 **Key Features**

**Role-Based Access Control:** Separate, secure dashboards for "Users" and "Workers" managed via Firebase Firestore.  
**Professional Service Cards:** Workers can create, update, and manage their service pricing cards in real-time.  
**Local Portfolio Management:** Implementation of Scoped Storage to save and display high-resolution work images directly from the device's internal memory.  
**Direct Communication:** Instant "Contact on WhatsApp" feature with pre-filled messaging for efficient hiring.  
**Dynamic Discovery:** Service categories (Electrician, Plumber, etc.) with real-time filtration of available professionals. 


🛠 **Tech Stack**

**Frontend:** Jetpack Compose (Kotlin)  
**Backend/Database:** Firebase Firestore & Firebase Authentication   
**Image Loading:** Coil Library (for local scoped storage rendering)   
**State Management:** Compose State (mutableStateOf/remember)


📁 **Project Structure**

app/src/main/java/com/example/kaushalyakarnataka/
<br>├── MainActivity.kt        # Main Navigation logic and Auth Check
<br>├── ui/                    # UI Components 
<br>│   ├── Screens.kt         # Registration, Dashboards, and Lists 
<br>│   └── components/        # Reusable Cards and Buttons 
<br>├── data/                    # Data Models 
<br>│   └── ServiceItem.kt     # Worker service card definitions 
<br>└── utils/                    # Helpers 
    <br>└── ImageUtils.kt        # Scoped Storage / Local Save logic 


⚙️ Setup and Installation

**Clone the repository:**  
git clone [INSERT_YOUR_REPOSITORY_LINK_HERE]

**Add Firebase Configuration:** Place your google-services.json in the app/ directory.  
**Dependencies:** Ensure the Coil, Firebase-Auth, and Firestore dependencies are synced via build.gradle.  
**Run:** Connect an Android device with USB Debugging enabled and click Run in Android Studio. 

<img width="261" height="494" alt="image" src="https://github.com/user-attachments/assets/ba0a5469-01f1-4284-861b-d13ae9210441" />  

**UsersDashboard**

<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/4b7d4a17-3630-44c6-8f16-1944a833d35b" />
<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/1b5b4344-f38a-4bf2-982f-8e444144a18c" />
<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/d1fc1e39-bdf7-48f0-9878-eed5aa9e36fa" />
<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/a5773adb-7445-4d39-8936-e110e1a781f8" />
<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/e79d1b38-603b-4da2-b917-b0d5a3fdcb8e" />



**Workers Dashboard**

<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/e806e376-302d-4b6c-a18b-31327def426c" />
<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/d82a4413-beb6-4cd4-8928-7c066cd0cdde" />
<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/daa562fc-1b7b-4816-a029-c465c3fc15fc" />
<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/bb447e61-6764-4279-a81d-2ae8308119fb" />
<img width="320" height="751" alt="image" src="https://github.com/user-attachments/assets/fb626229-f62d-42c9-97d0-8b504612878e" />












