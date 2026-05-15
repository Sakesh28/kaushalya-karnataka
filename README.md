<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/e3748712-d03d-43a8-9779-a3b171295788" />**Kaushalya-Karnataka**

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

