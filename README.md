# Family Points Hub

A Firebase-powered family request, chore, points, rewards and archive app.

## Files

- `index.html` — full app
- `manifest.json` — lets phone install it as a PWA
- `firebase.rules.txt` — starter Firestore and Storage rules

## Firebase Setup

1. Go to Firebase Console.
2. Create a new project, e.g. `family-points-hub`.
3. Add a Web App.
4. Copy the Firebase config.
5. Open `index.html`.
6. Replace this section:

```js
const firebaseConfig = {
  apiKey: "PASTE_YOUR_API_KEY_HERE",
  authDomain: "PASTE_YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "PASTE_YOUR_PROJECT_ID",
  storageBucket: "PASTE_YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "PASTE_YOUR_SENDER_ID",
  appId: "PASTE_YOUR_APP_ID"
};
```

7. In Firebase, enable Firestore Database.
8. In Firebase, enable Storage.
9. Use the starter rules in `firebase.rules.txt`.

## GitHub Upload

1. Create a new GitHub repository.
2. Name it `family-points-hub`.
3. Upload these files:
   - `index.html`
   - `manifest.json`
   - `firebase.rules.txt`
4. Commit changes.

## Vercel Deployment

1. Go to Vercel.
2. Add New Project.
3. Import the GitHub repository.
4. Framework preset: Other.
5. Build command: leave blank.
6. Output directory: leave blank.
7. Deploy.

## Admin PIN

Default PIN is:

```text
0804
```

Change this line in `index.html`:

```js
const ADMIN_PIN = "0804";
```
