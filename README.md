# IELTS Master (Android APK) – সম্পূর্ণ সংস্করণ (সংশোধিত)

এই জিপই সম্পূর্ণ প্রজেক্ট। পর্ব ১ এর সব কিছু এতে আছে, সাথে ১০০টি Collocation এর বাংলা অনুবাদও যোগ হয়েছে।

## একটাই APK বানানোর নিয়ম
### যদি পর্ব ১ আগেই GitHub-এ তুলে থাকেন
1. আপনার repository খুলুন → `www` ফোল্ডার → `index.html` ফাইলে ক্লিক করুন।
2. ডানে উপরে পেনসিল (Edit) নয়, তিন ডট (⋯) → Delete file → Commit।
3. Add file → Upload files → এই জিপের `www/index.html` আপলোড করুন (www ফোল্ডারসহ) → Commit।
4. `.github/workflows/build-apk.yml` আগের মতোই থাকবে, বদলাতে হবে না।

### যদি নতুন repository বানান
1. নতুন repository বানান।
2. জিপের `www` আর `.github` ফোল্ডার আপলোড করুন (Add file → Upload files)।
   - `.github` না উঠলে: Add file → Create new file → নাম `.github/workflows/build-apk.yml` → build-apk.yml এর লেখা পেস্ট করুন।

## APK ডাউনলোড
1. Commit করলেই Actions ট্যাবে "Build APK" নিজে চালু হবে (না হলে Run workflow চাপুন)। ৫–১০ মিনিট লাগবে।
2. সবুজ টিক এলে সেই run এ ঢুকুন → নিচে Artifacts → **IELTS-Master-APK** ডাউনলোড করুন।
3. জিপ খুলে `app-debug.apk` ফোনে ইনস্টল করুন (Unknown sources অনুমতি দিন)।

## প্রথমবার অ্যাপে
- নোটিফিকেশন ও অ্যালার্মের অনুমতি দিন → ৩০ দিনের অ্যালার্ম সেট হবে।
- সেটিংস → Gemini API Key বসান → "টেস্ট করুন"।
- ফোনের Battery সেটিংসে IELTS Master কে "Unrestricted" করুন; ফোনের টাইমজোন Dhaka রাখুন।
