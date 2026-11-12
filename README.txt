EMOTION CONNECT - FASA 1
1. Create Firebase project at https://console.firebase.google.com
2. Register Web App and copy firebaseConfig into index.html (replace PASTE_... values).
3. Enable Authentication > Sign-in method > Email/Password.
4. Create Cloud Firestore and paste firestore.rules into Firestore > Rules; publish.
5. Authentication > Settings > Authorized domains: add your GitHub Pages hostname (username.github.io). localhost may also need adding for local tests.
6. To test locally, use a local HTTP server (e.g. python -m http.server 8000) and open http://localhost:8000. Do not use file://.
7. For GitHub Pages, upload index.html to repository root, set Settings > Pages > Deploy from branch > main / root.
8. The app is a prototype. Do not enter real child data without appropriate privacy notices, consent, retention/deletion processes and security review.
9. One guardian account per student profile. Firebase config is public client configuration; never put service-account credentials in this file.
