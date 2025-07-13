# A.Q Khan Business App

This app allows you to manage stock, customers, and payments. It supports login, bill generation, and is mobile-friendly (PWA).

## 🚀 Features
- Login/Signup (Firebase Auth)
- Stock Management (Add/Edit/Delete)
- Customer Details & Payments (Full/Lease)
- Bill PDF Generation
- Progressive Web App (Mobile Ready)

## 🛠 Setup Instructions

1. Go to [https://console.firebase.google.com](https://console.firebase.google.com)
2. Create a Firebase project
3. Enable **Authentication > Email/Password**
4. Enable **Firestore Database**
5. Copy your Firebase config and paste it into `src/firebase.js`

```
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

6. Run the app:
```bash
npm install
npm run dev
```

7. To deploy:
- Use [https://vercel.com](https://vercel.com)
- Connect your GitHub repo and deploy for free

Enjoy!