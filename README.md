# TWApp

**TWApp** is a sophisticated, role-based Android application engineered to enhance communication, streamline administrative workflows, and centralize resource management within a university environment, with a particular focus on National Service Scheme (NSS) related activities. This public repository serves as a visual showcase of the application's robust capabilities through a curated collection of interface screenshots.

> 📌 **Important Note**: This repository is dedicated solely to demonstrating the application's user interface and functional scope. The full application codebase is actively under development and maintained in a private repository to protect proprietary information and intellectual property. TWApp is currently in its development phase.

---

## 🚀 Key Functional Modules & User Experience

TWApp is meticulously designed to provide a seamless and efficient experience for various user roles, primarily students and administrators (Admin1, Admin2).

### 🔹 Unified Dashboard
The central hub for all users, dynamically tailored to display relevant information:
-   **Personalized Greetings**: Custom messages and quick access based on user identity.
-   **Announcements & Updates**: Timely dissemination of information from administrators.
-   **Role-Based UI Rendering**: Distinct interfaces and feature access depending on the logged-in user's role (Student, Admin1, Admin2), ensuring a clear separation of functionalities.
-   **Instruction-Based Chatbot**: An integrated chatbot provides instant responses and guidance on common queries, improving user support efficiency.


### 💬 Real-Time Communication
Facilitating effective and immediate interaction across the university community:
-   **Group Messaging**: Supports collaborative discussions within NSS groups, courses, or specific project teams.
-   **Direct Messaging**: Enables private, one-on-one conversations between individuals.
-   **File Sharing**: Users can share images, pdfs and audio files within chat.

### 🗓️ Smart Calendar & Event Management
A versatile calendar system for organizing and tracking academic and NSS-related events:
-   **Dual Tab View**:
    -   **Teaching Calendar**: Dedicated to managing class schedules and tracking leave applications, which is crucial for NSS program coordination.
    -   **Events Calendar**: Comprehensive tracking for university-wide events, NSS camps, workshops, and general meetings.
      
-   **Comprehensive Date Display**: The calendar grid consistently displays all dates for every month.
  
-   **Interactive Date Selection**: Users can tap on specific dates to view detailed event information, create new events, or manage leave applications (permission-based).
  
-   **Leave Application Status Indicators**: Clearly tags dates with pending, approved, or rejected leave applications, providing immediate visual cues for teaching staff and administrators.

### 🧰 Admin Toolkit
Empowering administrators with essential management capabilities:
-   **Role-Restricted Access**: Administrative tools, including the **Schedule Manager** and **Interview Portal**, are exclusively accessible to designated Admin1 and Admin2 roles, ensuring data integrity and operational control.
-   **Content & User Management**: Admins possess capabilities for creating groups, managing user visibility, and posting critical updates.
-   **Attendance Manager**: Facilitates efficient recording and management of NSS attendance, a core function of the application.

### 📚 Profile & Resource Library
A centralized personal space and access point for essential resources:
-   **User Information Card**: Displays key user details, course affiliations, and assigned roles.
-   **Integrated Resource Viewer**: Provides seamless access to a digital library of documents and images relevant to courses or NSS activities.
---


## ⚙️ Core Technology Stack

TWApp is built upon a robust and scalable architecture, leveraging leading Android development frameworks and cloud services:

-   **Kotlin**: Utilized for its conciseness, safety, and interoperability, forming the backbone of the application logic.
  
-   **Firebase Suite**: A comprehensive backend-as-a-service (BaaS) solution providing:
    -   **Firebase Authentication**: Secure user identity management.
    -   **Cloud Firestore**: A flexible, NoSQL cloud database for data storage and synchronization.
    -   **Firebase Realtime Database**: For immediate data synchronization in real-time communication features.
    -   **Firebase Cloud Messaging (FCM)**: Enables push notifications for timely alerts.
    -   **Firebase Storage**: Securely stores user-generated content, including chat images.
      
-   **Android Jetpack Components**: Enhancing developer productivity and app quality:
    -   **MVVM (Model-View-ViewModel)**: Architectural pattern for separation of concerns and testability.
    -   **LiveData**: Observable data holders for lifecycle-aware UI updates.
    -   **Navigation Component**: Simplifies in-app navigation and streamlines user flows.
      
-   **Google Drive API**: Facilitates integration with cloud storage services for resource management.
  
-   **Glide & PhotoView**: Essential libraries for efficient image loading, caching, and enabling interactive features like pinch-to-zoom for images.
  
-   **CameraX & Google Play Services Location**: Integrated for advanced functionalities such as attendance tracking, potentially incorporating facial recognition (currently in-progress) and precise location services.


---
## 📸 UI Showcase

This section offers a comprehensive visual tour of TWApp's key interfaces and functionalities, demonstrating the application's design and user experience.

*For comparative analysis, the Left Android Mobile illustrates the Admin Interface, while the Right Android Mobile showcases the Student Interface.*

---

### Login Interface
These screenshots present the secure and intuitive entry points for users to access the application based on their designated roles.<br>
![Screenshot 2025-07-02 014533](https://github.com/user-attachments/assets/b7f6add4-8d80-4ecd-9a60-0408d76799e9)
![Screenshot 2025-07-02 014541](https://github.com/user-attachments/assets/af67f269-3d1a-4d10-9750-3fbe076627b8)

### Dashboard
Observe the personalized main screen, dynamically adapting to display relevant information and quick access modules tailored to each user's role (Admin or Student).<br>
![Screenshot 2025-07-02 011700](https://github.com/user-attachments/assets/1fb37683-a148-4656-a54e-c35a7c6dba29)


### Attendance Manager
A dedicated interface for administrators to efficiently record, view, and manage NSS attendance data.<br>
![Screenshot 2025-06-08 070758](https://github.com/user-attachments/assets/fc1ca1c2-5f06-4df8-b856-01d8ba8f9b91)
![Screenshot 2025-06-08 072523](https://github.com/user-attachments/assets/4d8bdcac-6e31-4dad-a898-c7e5265d79f7)

### Updates Section of Dashboard
This view highlights how administrators can disseminate important announcements and updates directly to users via the dashboard.<br>
![Screenshot 2025-06-08 070901](https://github.com/user-attachments/assets/450a8afd-542a-4e8b-91ea-151cece6b3cf)

### Instruction Based Chatbot
Experience the interactive chatbot, designed to provide immediate, instruction-based assistance and information to users.<br>
![Screenshot 2025-06-08 070846](https://github.com/user-attachments/assets/6305196d-9168-4007-b696-11d7d87c332e)

### Chat Feature
These images showcase the real-time messaging capabilities, including both group and direct chat interfaces, along with integrated image sharing.<br>
![Screenshot 2025-07-02 011729](https://github.com/user-attachments/assets/31dad9ee-ad85-45bf-ade6-21924bc029b8)
![Screenshot 2025-06-08 071000](https://github.com/user-attachments/assets/0f27893d-61c1-4209-98ce-df37bc23d7f9)
![Screenshot 2025-06-08 071823](https://github.com/user-attachments/assets/b7d385cb-ffd0-4452-ad36-fc78a304d455)

### Calendar
A visual representation of the robust calendar system, illustrating both teaching schedules and general university events with clear date and event indicators.<br>
![Screenshot 2025-06-08 071933](https://github.com/user-attachments/assets/183c1f9b-19e0-4099-85cb-f342fac78b37)
![Screenshot 2025-06-08 071910](https://github.com/user-attachments/assets/9c06207a-e54f-4929-b01c-648b27ba1b07)

### Schedule Manager
This administrative tool provides a dedicated interface for managing and organizing various schedules within the institution.<br>
![Screenshot 2025-07-02 011748](https://github.com/user-attachments/assets/e90d17ab-48a4-411c-9260-d6ed7d329a9d)
![Screenshot 2025-07-02 011800](https://github.com/user-attachments/assets/9144e583-8c67-43a2-a4a7-3c39e60e8d81)


### Interview Manager
An exclusive administrative module designed for the streamlined management of interview processes.<br>
![Screenshot 2025-06-08 071956](https://github.com/user-attachments/assets/2323855a-6141-4c73-9379-9f071c3d772a)

### Profile
Explore the personal profile section, where users can view their information, course codes, and assigned roles.<br>
![Screenshot 2025-07-02 014402](https://github.com/user-attachments/assets/162d6408-6415-4562-9db4-cdf10f945e8b)

### Resource Library
A centralized hub for accessing various educational and NSS-related resources, including documents and images.<br>
![Screenshot 2025-07-02 011819](https://github.com/user-attachments/assets/7387b9dd-1169-4648-be12-e71cd4056869)

---

**Core Contributors:**
-   [Aditya Onam](https://github.com/AdityaOnam)
-   [Aditya Gupta](https://github.com/code-epic-adi)
-   [Eshan Bhaskar](https://github.com/EshanBhaskar)
-   [Ankesh Kumar](https://github.com/arbitcoper)

---

Thank you for exploring the **TWApp Showcase**! We welcome technical inquiries and collaboration interests. Feel free to connect via GitHub or professional networking platforms.
