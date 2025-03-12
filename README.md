# **איחורית** - מערכת לניהול חריגות נוכחות של תלמידים

### תיאור הפרויקט
איחורית היא מערכת ניהול מתקדמת לניהול חריגות נוכחות של תלמידים בבתי ספר. האתר מאפשר לצוותים חינוכיים לנהל את מצבת התלמידים בכיתה, לעדכן חריגות נוכחות, וליצור דוחות מותאמים אישית בקלות. 

המערכת עוצבה בקפידה תוך דגש על נראות וחווית משתמש, והוטמעה בהצלחה בבית הספר של הלקוח.

  
---

## **טכנולוגיות**

### צד שרת (Server-side):
- ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) - **Node.js**: פלטפורמת צד שרת המאפשרת להריץ JavaScript בצד השרת ולבצע בקשות API במהירות ובאמינות.
- ![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge) - **Express**: פריימוורק מינימליסטי לניהול נתיבים (Routes), ביניים (Middlewares), וניהול הרשאות גישה.
- ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white) - **אבטחת גישה באמצעות JWT**: המערכת משתמשת באסימוני גישה (JWT) לאימות ואבטחת בקשות משתמשים, כדי להבטיח שכל המידע והפעולות מוגנים ברמת אבטחה גבוהה.
- ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) - **MongoDB**: מסד נתונים NoSQL שנועד לאחסן את פרטי התלמידים, הכיתות, חריגות הנוכחות והדוחות שנוצרו.

### צד לקוח (Client-side):
- ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) - **React**: ספרייה לפיתוח ממשק משתמש (UI) יעיל ורספונסיבי עם יכולת ניהול מדינות מתקדמת.
 - **RTK-Query**: מספקת ניהול מדינות מתקדם לביצוע קריאות API ולטיפול במידע המתקבל מהשרת.
 - **PrimeReact**: סט כלים מתקדם לעיצוב קומפוננטים מוכנים מראש המותאמים לצרכים כמו טבלאות, טפסים, וכפתורים בצורה מקצועית ונעימה לעין.
---

## **תכונות עיקריות**
- **ניהול כיתות ותלמידים**: הגדרת כיתות, עדכון פרטי מחנכת כולל מייל, וניהול רשימת תלמידים.
- **ניהול חריגות נוכחות**: אפשרות לעדכן חריגות כגון איחור, איחור מאושר וחיסור.
- **יצירת דוחות מתקדמים בטווח תאריכים**:
  - פירוט חריגות נוכחות של תלמידים לפי כיתה.
  - סכום חריגות מכל סוג לתלמידה, לפי כיתה (עבור תעודות סוף מחצית).
  - מצטיינות שחרגו פחות מX פעמים.
  - אפשרות להדפסה, ייצוא ושליחה בדוא"ל.
- **תהליך פתיחת שנה אוטומטי**:
  - הוספת תלמידות חדשות באמצעות קובץ Excel.
  - העלאה אוטומטית של כיתה.
  - מחיקה מהירה של מחזור כיתות ח'.
## License
This project is proprietary software. All rights are reserved.  
It is permitted to use this software **for learning purposes only** without payment.  
Any other usage, including commercial use, requires purchasing a valid license from the author.  

For inquiries about licensing, please open an [Issue](../../issues).

---
## תמונות מסך


