88ACADEMY — קבצי הפרויקט

איך מעלים לאתר
1. מעלים את כל הקבצים כמו שהם, כולם באותה תיקייה, לאחסון אתרים רגיל
   (למשל Netlify, Cloudflare Pages, GitHub Pages, או public_html באחסון של cPanel).
2. כתובת האתר פותחת את index.html, והוא מעביר למסך הכניסה (Login.dc.html).

חשוב לדעת
- צריך לפתוח את האתר דרך שרת. בפתיחה בלחיצה כפולה מהמחשב חלק מהמסכים נפתחים,
  אבל מסכים שמציגים בתוכם מסך אחר (אזור המשקיף ומסכי הסטודנט הנפרדים) נשארים ריקים.
- לצפייה במחשב בלי להעלות: בתיקייה הזאת מריצים
  python3 -m http.server 8000
  ופותחים בדפדפן http://localhost:8000
- support.js הוא המנוע שמציג את המסכים. הוא חייב להישאר באותה תיקייה עם קבצי ה־.dc.html.
- זה אב־טיפוס שרץ כולו בדפדפן: הכניסה והסיסמאות לדוגמה הן להדגמה בלבד, בלי שרת ובלי אבטחה,
  והשינויים (ארנק, פרסים, הגדרות ניקוד) נשמרים רק בדפדפן של מי שמשתמש בו.
- canvas.json הוא מפת הקנבס (שמות, גדלים ומיקומים של המסכים). האתר לא צריך אותו.

חשבונות לדוגמה (מופיעים גם במסך הכניסה)
  מנהל     yehuda   / admin123
  משקיף    ahazan   / observer123
  סטודנט   babafab  / student123

המסכים
Login.dc.html                כניסה
Main.dc.html                 סקירה — לוח בקרה
Students.dc.html             סטודנטים
StudentDetail.dc.html        כרטיס סטודנט
Units.dc.html                יחידות
Leadership.dc.html           מנהיגות
Curriculum.dc.html           תוכנית לימודים
SkillEdit.dc.html            עריכת מיומנות
Rewards.dc.html              פרסים
RewardEdit.dc.html           עריכת פרס
AIChecks.dc.html             בדיקות AI
Activity.dc.html             יומן פעילות
PointsSettings.dc.html       הגדרות ניקוד
StudentApp.dc.html           סטודנט — לוח מחוונים
StudentSkill.dc.html         סטודנט — מיומנות
StudentPathGraph.dc.html     סטודנט — הנתיב שלי (גרף)
StudentPathPhone.dc.html     סטודנט — הנתיב שלי (גרף, טלפון)
StudentPathList.dc.html      סטודנט — הנתיב שלי (רשימה)
StudentChallenges.dc.html    סטודנט — אתגרים
StudentFlights.dc.html       סטודנט — הטיסות שלי
StudentRewards.dc.html       סטודנט — פרסים
StudentPoints.dc.html        סטודנט — המטבעות שלי
StudentGuide.dc.html         סטודנט — איך צוברים מטבעות
StudentLevelUp.dc.html       סטודנט — עלייה בדרגה
Observer.dc.html             משקיף — הקבוצה שלי
