# JokerLudo — social room chat

Friends ka group chat. Ludo room code yahin paste hota hai, doosra player copy karke join karta hai.

Isme paise nahi hain. Koi wallet, deposit, withdrawal, stake, pot, ya commission nahi. Firebase sirf real-time chat aur room-code cards ke liye hai.

Project: `jokerludo-bf60f`

## Pehle Firebase console

1. [Firestore](https://console.firebase.google.com/project/jokerludo-bf60f/firestore) kholo aur database banao (production mode theek hai).
2. Rules tab me `firestore.rules` ka content paste karke Publish karo.
3. API key ko Google Cloud me HTTP referrer se restrict karo. Yeh web config chat me share ho chuka hai.

## Chalana

`index.html` kahin bhi host karo (GitHub Pages, Firebase Hosting, ya seedha file). Jo log same link kholenge, wahi group me real-time join honge.

Local:

```bash
npx --yes serve .
