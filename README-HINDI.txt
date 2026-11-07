MINDGUARD AI ANDROID APP PROJECT

Yeh Android WebView wrapper hai jo aapki live website ko app ke andar kholta hai:
https://mindguard-ai.oneapp.dev/

APK banane ke liye:
1. Is ZIP ko extract karein.
2. GitHub par naya repository banayein.
3. Is folder ke andar ki saari files repository mein upload karein (ZIP ko direct upload nahi).
4. Repository ka naam MindGuardAI rakh sakte hain.
5. GitHub mein Actions tab kholein.
6. Agar workflow prompt aaye to "I understand my workflows, go ahead and enable them" dabayein.
7. "Build MindGuard AI APK" workflow select karke "Run workflow" dabayein.
8. Build complete hone par workflow run ke neeche Artifacts mein MindGuard-AI-debug-APK download karein.
9. ZIP extract karke app-debug.apk ko Android device par install karein.

ZAROORI:
- Yeh debug APK hai, testing/install ke liye. Play Store publish karne ke liye signed release build aur Play Console setup alag chahiye.
- Website online rehni chahiye; app website ko load karta hai, offline app nahi hai.
- Firebase login/mood tracking website ke Firebase setup par depend karte hain.
- WebView mein browser speech recognition har device par supported nahi hoti. Microphone permission handling di gayi hai, lekin voice assistant ko APK mein test karna hoga.
- App icon abhi default Android icon hai; custom icon baad mein add kiya ja sakta hai.
