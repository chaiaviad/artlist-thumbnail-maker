# Artlist Tools — קונבנציית הוספת כלי

מערכת מסודרת לפי מספור **AL-0X**. כל כלי מקבל מספר רץ, וממשיכים ברצף.

## מספור קיים
- **AL-04** — Thumbnail & Banner Maker  (מקור: `D:\AL-04 May Thumbnail`)
- **AL-05** — Collab Maker             (מקור: `D:\AL-05_Collab_Maker`)

הכלי הבא = **AL-06**, אחר כך AL-07 וכו'.

## איך מוסיפים כלי חדש (התהליך שאני מבצע אוטומטית)
1. **מספר**: לקחת את ה-AL הבא ברצף.
2. **תיקיית מקור** (נשארת אצל המשתמש, לא נדרסת): `D:\AL-0X <שם הכלי>`.
3. **תיקייה ב-repo**: `Artlist_Tools/<Clean_Name>/index.html` — שם נקי ל-URL (בלי `&` או רווחים; להעדיף `_`).
4. **רישום ב-hub**: להוסיף אובייקט אחד למערך `TOOLS` שב-`index.html` (al, folder, title, desc, tags). הסדר מתעדכן אוטומטית לפי `al`.
5. **commit** (המשתמש דוחף ל-GitHub).

## כתובות (GitHub Pages, repo בשם `Artlist_Tools` תחת chaiaviad)
- Hub:               `https://chaiaviad.github.io/Artlist_Tools/`
- כל כלי:            `https://chaiaviad.github.io/Artlist_Tools/<Clean_Name>/`

> שם התיקייה הנקי הוא ה-URL. שם התצוגה (`title`) יכול לכלול `&` ורווחים — הוא לא משפיע על הכתובת.
