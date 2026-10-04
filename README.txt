ভিন্নতা টেলিকম প্লাস - PWA Trial Package

GitHub Pages setup:
1. এই ZIP extract করুন।
2. ভিতরের সব ফাইল GitHub repository-এর root folder-এ upload করুন।
3. GitHub Settings > Pages থেকে branch/folder publish করুন।
4. HTTPS URL খুলুন। Chrome/Edge-এ Install App অপশন আসবে।

মূল ফাইল:
- index.html : মূল সফটওয়্যার
- manifest.webmanifest : PWA app metadata
- sw.js : service worker / app shell cache
- icons/ : Android/PWA icons

নোট:
Firebase Authentication ও Firestore চালাতে internet connection প্রয়োজন। PWA shell cached হলেও Firebase backend offline অবস্থায় কাজ করার নিশ্চয়তা এই package দেয় না।

ভবিষ্যতে Android APK/AAB বানানোর জন্য এই একই PWA-কে Capacitor বা Trusted Web Activity ভিত্তিক Android wrapper-এ ব্যবহার করা যাবে।
