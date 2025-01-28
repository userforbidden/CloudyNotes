# App Name: CloudyNotes
## Description
A simple note-taking app that allows users to save and sync their notes across devices using SSO for authentication.

## Features
Add, edit, and delete simple text notes.
Use SSO (Google or Apple) to log in and sync notes.

## Valid Reason for SSO
SSO simplifies user management and enables cross-device syncing by linking notes to a user’s account (Google or Apple).

# Development Steps

## 1. Setup the Project
- Create a new project in Android Studio (for Android) or Xcode (for iOS).
- Use Firebase or a local SQLite database for storing notes.

## 2. Login Screen
- Add a “Sign in with Google” button using Firebase Authentication or OAuth.
- Once the user logs in, redirect them to the notes screen.

### Example Login UI:

- A button: "Sign in with Google."
- A background message: “Log in to sync your notes.”

## 3. Notes Screen
- A simple interface to display a list of notes.
- A floating action button (FAB) to add new notes.

## 4. Add Note Screen
- Allow users to write and save a note.
- Save the note locally or sync it to Firebase after login.

## 5. SSO Integration
- Google SSO: Use Firebase Authentication to set up Google Sign-In.
- Apple SSO (for iOS): Implement Apple Sign-In API.
- After successful login, retrieve the user ID and link notes to their account.

## 6. Testing
- Ensure smooth navigation between screens.
- Test login/logout flows and note-sync functionality.
