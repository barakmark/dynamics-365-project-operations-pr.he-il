---
title: מה חדש ומה השתנה ב- Project Operations, יולי 2021 עבור תרחישים של מלאי/מבוססי ייצור
description: נושא זה מספק מידע על עדכוני האיכות הזמינים במהדורת יולי 2021 של Project Operations עבור תרחישים של מלאי/מבוססי ייצור.
author: andchoi
ms.date: 07/01/2021
ms.topic: article
ms.prod: ''
ms.reviewer: kfend
ms.author: andchoi
ms.openlocfilehash: fb1814330b5e474ccbda0ab85dd67758a6f270a9
ms.sourcegitcommit: be5beba71ee9770c0083b4fe5cc89e7ec6b741b8
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 07/02/2021
ms.locfileid: "6334546"
---
# <a name="whats-new-or-changed-in-project-operations-july-2021-for-stockedproduction-based-scenarios"></a>מה חדש ומה השתנה ב- Project Operations, יולי 2021 עבור תרחישים של מלאי/מבוססי ייצור

_חל על:**‏ Project Operations** לתרחישים מבוססי ייצור/עם מלאי_

נושא זה חל על הרכיבים והגירסאות הבאים של Dynamics 365 Project Operations:

- ניהול פרויקטים וחשבונאות בסביבת Dynamics 365 Finance גרסה 10.0.20
 
### <a name="quality-updates"></a>עדכוני איכות
                                                                                                                                                                                  
| אזור תכונות                      | מספר אסמכתא| עדכון איכות                                                                                                                                                                          |
|-----------------------------------|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ניהול פרוייקטים וחשבונאות | [485394](https://fix.lcs.dynamics.com/Issue/Details/?bugId=485394) | רישומים של התחייבות עלות מדרישת רכישה מנוקים ברגע שהזמנת הרכש מופצת מדרישת הרכש.                                                                           |
| ניהול פרוייקטים וחשבונאות | [529602](https://fix.lcs.dynamics.com/Issue/Details/?bugId=529602) | אימות תקציב מתרחש פעמיים בדרישת רכש. המשמעות של כפילות זו היא שלא ניתן לסגור את הדרישה ולא ניתן ליצור את הזמנת הרכש המתאימה.                                                                                                                        |
| ניהול פרוייקטים וחשבונאות | [539439](https://fix.lcs.dynamics.com/Issue/Details/?bugId=539439) | לא ניתן היה להשלים את כלל החיוב **אחוז לחיוב** בגלל בעיית עיגול.                                                                              |
| ניהול פרוייקטים וחשבונאות | [540023](https://fix.lcs.dynamics.com/Issue/Details/?bugId=540023) | בעת התאמת העסקה, אם האחוז הוא מספר עשרוני, העלות ומחיר המכירה אינם מותאמים כהלכה.                                      |
| ניהול פרוייקטים וחשבונאות | [540927](https://fix.lcs.dynamics.com/Issue/Details/?bugId=540927) | מקור החשבונאות מציג שעות עבור שורה בלוח זמנים יחיד עבור מספר רב של שורות בגיליון זמנים עם פעילויות שונות.                                      |
| ניהול פרוייקטים וחשבונאות | [541471](https://fix.lcs.dynamics.com/Issue/Details/?bugId=541471) | תצוגות שמורות והתאמה אישית של פרטי שורות בגיליון זמן גורמות למערכת לפתוח תמיד את הפרטים עבור גיליון הזמנים הראשון ברשימה כאשר היא מנסה לפתוח גיליון זמנים.  |
| ניהול פרוייקטים וחשבונאות | [548677](https://fix.lcs.dynamics.com/Issue/Details/?bugId=548677) | צומת הבסיס של הפרויקט נעלמת והרשומות של מבנה התפלגות העבודה נמחקות לאחר הייבוא.                                                                                             |
| ניהול פרוייקטים וחשבונאות | [548999](https://fix.lcs.dynamics.com/Issue/Details/?bugId=548999) | כאשר פריטים מתקבלים ומונפקים חלקית מדרישת הפריטים, המערכת מעדכנת את יתרת הצריכה התקציבית הלא נכונה. |
| ניהול פרוייקטים וחשבונאות | [550959](https://fix.lcs.dynamics.com/Issue/Details/?bugId=550959) | הזמנות רכש של שימור פרויקטים לא מציגות את הסכומים כהלכה בחלונית **סך הכל** או ברשת **חשבונית בהמתנה**.                                                                  |
| ניהול פרוייקטים וחשבונאות | [554593](https://fix.lcs.dynamics.com/Issue/Details/?bugId=554593) | בעת סגירת מלאי, התאמות של עלויות פריט בפרויקט מוצגות לחשבון היתרה במקום חשבון הרווח וההפסד.                                                            |
| ניהול פרוייקטים וחשבונאות | [557394](https://fix.lcs.dynamics.com/Issue/Details/?bugId=557394) | שובר עסקאות שפורסם בפרויקט ושובר האומדן משתמשים בדולר ארה"ב כמטבע החשבונאי, אך הסכום מראה מה יהיה הערך המקביל ל- CAD.              |
| ניהול פרוייקטים וחשבונאות | [560140](https://fix.lcs.dynamics.com/Issue/Details/?bugId=560140) | עלויות מחויבות עם דרישת פריט והזמנת רכש שגויות בתהליך חשבונית הזמנת הרכש עם קבלת מוצר חלקי וחשבונית חלקית.       |
| ניהול פרוייקטים וחשבונאות | [560567](https://fix.lcs.dynamics.com/Issue/Details/?bugId=560567) | התאמת הפרויקט לא מעדכנת נכון את סכום המכירות עם עלויות עקיפות.                                                                                    |
| ניהול פרוייקטים וחשבונאות | [561137](https://fix.lcs.dynamics.com/Issue/Details/?bugId=561137) | בטבלה **לוח זמנים** חסר קשר מוגדר עם תצוגת **עובד/משאב**.                                                                                   |
| ניהול פרוייקטים וחשבונאות | [563330](https://fix.lcs.dynamics.com/Issue/Details/?bugId=563330) | לא ניתן לאכלס את השדה **מספר פעילות** אם בוחרים אותו מהתפריט הנפתח עבור לוח זמנים בין חברות.                                                                 |
| ניהול פרוייקטים וחשבונאות | [563840](https://fix.lcs.dynamics.com/Issue/Details/?bugId=563840) | אי אפשר להוסיף שדה **מטרה** או **תיאור הפעילות** מותאממים אישית בדפים הבאים: **עסקה שפורסמה בפרויקט**, **יצירת הצעת חשבונית**, או **הצעת חשבונית**.  |
| ניהול פרוייקטים וחשבונאות | [566348](https://fix.lcs.dynamics.com/Issue/Details/?bugId=566348) | מופיע פקד לא נכון של תאריך המסירה בעת יצירת דרישות פריט באמצעות ניהול נתונים (**ProjSalesItemRequirementEntity**).                                              |
| ניהול פרוייקטים וחשבונאות | [566544](https://fix.lcs.dynamics.com/Issue/Details/?bugId=566544) | כאשר אתה בוחר מזהה חוזה פרוייקט ב- Finance, הסביבה המשולבת של Project Operations פותחת את הדף ליצירת רשומה חדשה במקום לפתיחת חוזה הפרויקט הקיים.                                                                                                                 |
| ניהול פרוייקטים וחשבונאות | [567300](https://fix.lcs.dynamics.com/Issue/Details/?bugId=567300) |  התווית, "@SYS4083080" ("לא ניתן למצוא רשומת עובד ייחודית שמתאימה לערכים שהוזנו") אינה מתורגמת לדנית.                                |
| ניהול פרוייקטים וחשבונאות | [569901](https://fix.lcs.dynamics.com/Issue/Details/?bugId=569901) | השדה **קבוצת מס מכירה על פריטים** אינו ניתן לעריכה בהצעת חשבונית.                                                                               |
| ניהול פרוייקטים וחשבונאות | [557049](https://fix.lcs.dynamics.com/Issue/Details/?bugId=557049) | העלות המחויבת מוגזמת בסכומי מס שאינם ניתנים לניכוי.                                                                                                    |
| ניהול פרוייקטים וחשבונאות | [565080](https://fix.lcs.dynamics.com/Issue/Details/?bugId=565080) | פרסום לוח זמנים בין חברות עם מספר פרויקטים וממדים פיננסיים שונים מייצר ערכים בלתי צפויים בספר החשבונות הכללי.                             |
| ניהול פרוייקטים וחשבונאות | [567962](https://fix.lcs.dynamics.com/Issue/Details/?bugId=567962) | שורות הצעת חשבונית משוכפלות בגלל מספר מקרים של תהליך תקופתי, **ייבוא מאחסון זמני** פועל במקביל.                                      |
| ניהול פרוייקטים וחשבונאות | [571339](https://fix.lcs.dynamics.com/Issue/Details/?bugId=571339) | יש שגיאה בפרסום הצעת החשבונית של פתק האשראי, כך שהעסקאות בשובר לא מתאזנות.    |
| ניהול פרוייקטים וחשבונאות | [573567](https://fix.lcs.dynamics.com/Issue/Details/?bugId=573567) | עלויות שמחויבות לפרויקט הופכות להיות שגויות לאחר פרסום חשבוניות בהמתנה.                                                                             |
| ניהול פרוייקטים וחשבונאות | [573886](https://fix.lcs.dynamics.com/Issue/Details/?bugId=573886) | אי אפשר ליצור אשראי להזמנת מכירה בפרוייקט כאשר המס הוא במטבע שונה מזה של מטבע החברה.                                      |
| ניהול פרוייקטים וחשבונאות | [582329](https://fix.lcs.dynamics.com/Issue/Details/?bugId=582329) | מחיקת חוזה גורמת גם למחיקת הכתובת המשויכת ללקוח.                                                                                     |
| ניהול פרוייקטים וחשבונאות | [585811](https://fix.lcs.dynamics.com/Issue/Details/?bugId=585811) | לא ניתן לפרסם הצעת חשבונית הנובעת מתיקון עסקה שלילי בזמן.                                                                    |
| נסיעות והוצאה                  | [532075](https://fix.lcs.dynamics.com/Issue/Details/?bugId=532075) | המס מחושב באופן שונה בדוחות ההוצאות.                                                                                                                  |
| נסיעות והוצאה                  | [546450](https://fix.lcs.dynamics.com/Issue/Details/?bugId=546450) | עדכון המהדורה **DB72_Expense.updateTrvExpTransProjTransId()**   לא מאפשר ל- **trvExpTrans.ReferenceDataAreaId** ליצור רצף מספרים חדש.                    |
| נסיעות והוצאה                  | [568805](https://fix.lcs.dynamics.com/Issue/Details/?bugId=568805) | הסכום שהוגש אינו מופיע בשדה החובה.                                                                                                             |
| נסיעות והוצאה                  | [568831](https://fix.lcs.dynamics.com/Issue/Details/?bugId=568831) | שיפורים בביצועים של הצמדת הוצאה לדוח ההוצאות באמצעות ממשק המשתמש Expense Reimagined.                                                            |
| נסיעות והוצאה                  | [570790](https://fix.lcs.dynamics.com/Issue/Details/?bugId=570790) | אפשר למחוק דוחות הוצאות שפורסמו.                                                                                           |
| נסיעות והוצאה                  | [571317](https://fix.lcs.dynamics.com/Issue/Details/?bugId=571317) | הודעת מדיניות ההוצאות מוצגת כמה פעמים.                                                                                                       |
| נסיעות והוצאה                  | [573969](https://fix.lcs.dynamics.com/Issue/Details/?bugId=573969) | השדה  **אמצעי תשלום** נכלל בחלונית **הוצאה חדשה**.                                                                                                      |
| נסיעות והוצאה                  | [523557](https://fix.lcs.dynamics.com/Issue/Details/?bugId=523557) | הכלי **אפס את מצב מסמך ההוצאות** צריך לאפס את דוח ההוצאות למצב **טיוטה** אם זרימת העבודה לא נמצאה. 

### <a name="regulatory-updates"></a>עדכוני רגולציה
למידע על עדכונים רגולטוריים עבור יישומי Finance and Operations, ראה [עדכוני רגולציה](/dynamics365/finance/localizations/regulatory-updates). ניתן גם להיכנס ל- Lifecycle Services ‏(LCS) ולהציג את עדכוני הרגולציה המתוכננים באמצעות הכלי לחיפוש בעיות. חיפוש בעיות מאפשר לך לחפש לפי מדינה, סוג תכונה והפצה.


[!INCLUDE[footer-include](../../includes/footer-banner.md)]