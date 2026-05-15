# 4.1P_SIT305_2026

This Android App, developed in Android Studio, allows users to manage personal events, appointments and trips through a simple and structured interface. 
This app was developed based on provided assessment guidelines and focuses on implementing CRUD operations, Room databases, Navigation and Android UI practices.

Developed for SIT305 assessment by Thilini Fonseka

## Personal Event Planner App
This application is designed to help users organise and track upcoming events efficiently on Android devices.
Users can create, view, edit and delete events while ensuring that all event information is stored locally using Room Persistence Library.
The application also uses Fragments and Android Navigation components to provide a smooth and modern navigation between screens.

### Technology used
1. Java
2. Android Studio
3. XML
4. Room Persistence Library

### App Features
1. Add new events with title, category, location and data/time
2. View all upcoming events sorted by date
3. Edit existing events details
4. Delete events no longer required

### Data Persistence
1. Stored all event data locally using Room Database
2. Data remains saved after app closure or device restart

### Validationg and Error Handling
1. Prevents empty Title and Date fields
2. Prevents users from selecting past dates
3. Displays Toasts

## How to run app
1. Clone the repository
   https://github.com/ThiliniPF/4.1P_SIT305_2026.git
2. Open the project in Android Studio
3. Allow Gradle to sync
4. Run the app using an emulator or a physical Android device
