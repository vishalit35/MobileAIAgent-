# 🤖 AI Phone Copilot (Autonomous Android Mobile Agent)

Yeh ek fully functional Android App hai jo aapke mobile screen ko read karke aapke liye tasks automatically execute karti hai (WhatsApp messages bhejna, Job applications me Easy Apply par click karna, form bharna, apps navigate karna).

---

## 🌟 App Kaise Kaam Karti Hai?

1. **Floating Bubble Service:** Ek chhota sa AI button screen par hamesha rehta hai (kisi bhi app ke upar).
2. **Accessibility Service:** Screen par maujood har button, text field aur links ko bina screenshot ke lightweight text tree me extract karti hai.
3. **Gemini 2.0 Flash:** Screen elements ko analyze karke exact button par tap, type ya scroll karne ka decision leti hai.

---

## 📦 APK Kaise Banayein (2 Asaan Raste)?

### Rasta 1: GitHub se Free Cloud Build (Bina PC me Android Studio install kiye - RECOMMENDED)
Agar aapke computer me Java ya Android Studio nahi hai:
1. Ek naya **Free GitHub Repository** banayein (Private ya Public).
2. Is `MobileAIAgent` folder ki saari files ko us repository me push kar dein.
3. GitHub me **Actions** tab me jayein -> `Build Android APK` automatically run hoga.
4. 2 se 3 minute me **Artifacts** me `AI-Phone-Copilot-Debug-APK` tayar milega.
5. use apne mobile me download karke install kar lein!

### Rasta 2: Android Studio se (Agar aapke paas Android Studio hai)
1. **Android Studio** open karein.
2. `Open Project` -> `C:\Users\wewin\.gemini\antigravity\scratch\MobileAIAgent` select karein.
3. Gradle Sync hone dein.
4. Top menu se **Build > Build Bundle(s) / APK(s) > Build APK(s)** par click karein.
5. Generate hui `app-debug.apk` ko phone me copy karke install kar lein.

---

## 🚀 Phone me Install karne ke baad Setup

1. **Overlay Permission:** App open karke "Display Over Other Apps" ko `Allow` karein.
2. **Accessibility Permission:** Settings me jakar `AI Phone Copilot` Accessibility Service ko `On` karein.
3. **Gemini API Key:** [Google AI Studio](https://aistudio.google.com/) se free API key generate karein aur app me paste karke Save karein.
4. **Start Agent:** "Start AI Floating Assistant" dabayein.

---

## 🎯 Use Case Examples:
* **WhatsApp:** Floating icon dabao aur likho: *"Open WhatsApp, search Rahul and send: Meeting scheduled for 4 PM"*
* **LinkedIn/Job Portals:** Job page kholo, floating icon dabao: *"Click Easy Apply and proceed with next steps"*

