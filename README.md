# Photo Sharing App

PhotoConnect is a mobile application where users can share photos, log in using email, and manage their posts. Users can upload images, add descriptions, and view the posts of other users. User authentication, data storage, and image uploading processes are handled using Firebase infrastructure.

## Features
- **User Login and Registration:** Users can sign up and log in using their email.

- **Photo Sharing:** Users can upload photos and add descriptions for each photo.
- **Post Listing:** Shared photos, descriptions, and user email addresses are displayed in a list.
- **Firebase Integration:** User authentication is handled with Firebase Authentication, and photo uploads are managed with Firebase Storage.
- **Picasso Usage:** The Picasso library is used for fast and efficient image loading.
  
  
## Technologies and Libraries Used
  - **Firebase Authentication:** Used for user sign-up, login, and authentication.
    
  - **Firebase Firestore:** Used for storing and retrieving posts from the cloud.
  - **Firebase Storage:** Used for storing images uploaded by users.
  - **Picasso:** A library for downloading and displaying images in an efficient manner.
  - **Navigation Component:** : Used for navigating between fragments.

## Usage
### 1. **Sign Up and Login**
- **Sign Up**: Allows users to create a new account using their email and password. After successful registration, users are redirected to the main page.
- **Login**: Allows existing users to log in using their email and password. After successful login, users are redirected to the main page.

### 2. **Photo Sharing**
- Users can upload photos and add descriptions to each photo.
- Uploaded photos are stored in Firebase Storage, and their URLs are saved in the Firestore database.

### 3. **Viewing Shared Posts**
- Users can view all shared photos, descriptions, and user email addresses in a list, fetched from Firebase Firestore.

