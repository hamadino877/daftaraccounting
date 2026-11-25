# دفتر الحسابات (Supabase + Vercel)

## 1) Supabase
1. أنشئ مشروع جديد على https://supabase.com
2. SQL Editor ← الصق محتوى `supabase.sql` ← Run
3. Project Settings ← API: انسخ **Project URL** و **anon public key** والصقهم في `config.js`
4. (اختياري) Authentication ← Providers ← Email: عطّل Confirm email لو عايز الدخول فوراً

## 2) GitHub
```
git init && git add . && git commit -m "ledger app"
git branch -M main
git remote add origin https://github.com/USERNAME/ledger-app.git
git push -u origin main
```

## 3) Vercel
Add New Project ← اختر الريبو ← Framework: Other ← Deploy (موقع static بدون build).
بعد النشر: Supabase ← Authentication ← URL Configuration ← ضع رابط Vercel في Site URL.
