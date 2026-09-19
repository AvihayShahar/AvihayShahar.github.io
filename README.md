# יומן דרך - הבלוג של אביחי לקבלה לרפואה

אתר בלוג סטטי מודרני מותאם לעברית (RTL), מעוצב עם Tailwind CSS וכולל רכיבים אינטראקטיביים (ציר זמן, כרטיסיית פליפ, סרגל קריאה).

---

## 🖥️ איך לצפות באתר מקומית במחשב שלך עכשיו

פשוט פתח את הקובץ `index.html` בדפדפן, או הרץ מהטרמינל בתיקייה זו:
```bash
open index.html
```

---

## 🚀 איך להעלות ל-GitHub Pages (מדריך מהיר)

### שלב 1: יצירת Repository ב-GitHub
1. היכנס לחשבון ה-GitHub שלך.
2. צור Repository חדש (למשל בשם `med-journey` או `avihay.github.io` אם תרצה שזה יהיה האתר הראשי שלך).
3. ודא שה-Repo מוגדר כ-**Public**.

### שלב 2: העלאת הקבצים מהמחשב
הרם טרמינל בתיקייה הזו (`/Users/avihay/.gemini/antigravity/scratch/med-journey-blog`):

```bash
git init
git add .
git commit -m "Initial commit: יומן דרך טיוטה ראשונה"
git branch -M main
git remote add origin https://github.com/<השם-משתמש-שלך>/<שם-הריפו>.git
git push -u origin main
```

*(לחלופין, אם מותקן אצלך ה-GitHub CLI `gh`:)*
```bash
gh repo create med-journey --public --source=. --push
```

### שלב 3: הפעלת GitHub Pages
1. בתוך ה-Repository ב-GitHub, לחץ על **Settings** (למעלה).
2. בתפריט הצדדי בחר **Pages** (תחת "Code and automation").
3. תחת **Build and deployment** -> **Source**, בחר **Deploy from a branch**.
4. תחת **Branch**, בחר ב-`main` ובתיקייה `/ (root)`, ולחץ **Save**.
5. תוך דקה האתר שלך יהיה באוויר בכתובת:
   `https://<השם-משתמש-שלך>.github.io/<שם-הריפו>/`
