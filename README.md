# Social App Project

## Overview

This is my final project for the Android course, built using Android Studio with Java. The app showcases essential features like logging in, posting pictures, and managing user profiles.

## Features

- **Login**: Register and log in with email or Google sign-in.
- **Post Pictures**: Upload and share pictures.
- **Like Pictures**: Like the pictures posted by others.
- **Save Pictures**: Save posts for later viewing.
- **Profile Management**: Edit your name and profile picture.

## Technologies Used

- **Android Studio (Java)**: Main development platform.
- **Firebase**:
  - **Authentication**: For user login and registration.
  - **Firestore**: Keeps track of posts and users. For each post, it stores the caption, image URL, like count, post ID, user ID, and timestamp. For users, it tracks email, name, profile picture URL, and user ID.
  - **Storage**: Saves uploaded pictures.
