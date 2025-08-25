# 🐦 Mock Microblogging Platform  

A **mock Chirper microblogging platform** built with **Laravel**, **Inertia.js**, and **Vue 3**, enabling users to post short messages (“Chirps”) with secure authentication and engagement features.  

## ✨ Features  

- **User Authentication**:  
  - Managed via **Laravel Breeze**  
  - Only authenticated users can create, edit, or delete Chirps  

- **Chirp Management**:  
  - Post, edit, and delete short messages (“Chirps”)  
  - Only authors can modify their own Chirps  

- **Secure Data Handling**:  
  - Displays only Chirp text, author name, and relative date (via **Day.js**)  
  - Sensitive details are hidden  
  - Authorization enforced at every action  

- **Engagement Features**:  
  - Email notifications for newly created Chirps  
  - Implemented via **Laravel Event Listeners**  

- **Frontend Design**:  
  - Built with **Vue 3** components through **Inertia.js**  
  - Reactive and dynamic user interface  

## 🛠️ Tech Stack  

- **Backend Framework**: Laravel  
- **Frontend**: Vue 3 + Inertia.js  
- **Language**: PHP, JavaScript  
- **Authentication**: Laravel Breeze  
- **Utilities**: Day.js for relative timestamps  
- **Notifications**: Laravel Event Listeners  
