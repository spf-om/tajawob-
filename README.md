# لوحة المؤشرات التنفيذية - منصة تجاوب

لوحة مؤشرات شهرية بصفحة HTML واحدة (RTL)، تعتمد على Chart.js وSheetJS وخط Cairo عبر الإنترنت.

## التشغيل
افتح `index.html` في المتصفح مباشرة، أو انشرها عبر GitHub Pages.

## النشر على GitHub Pages
1. Settings ← Pages
2. Source: Deploy from a branch
3. Branch: `main` / المجلد: `/ (root)`
4. الرابط: `https://USERNAME.github.io/REPO_NAME/`

## تحديث البيانات شهريًا
عدّل `index.html` ثم نفّذ:
```
git add index.html
git commit -m "تحديث بيانات الشهر"
git push
```

## تنبيه
لا ترفع هذا المستودع كعام إذا كانت البيانات داخلية.
