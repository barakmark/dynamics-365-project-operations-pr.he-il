---
title: הערכה של סעיף חוזה מבוסס פרוייקט - לייט
description: נושא זה מספק מידע על הערכת סעיף חוזה מבוסס פרויקט.
author: rumant
manager: Annbe
ms.date: 03/30/2021
ms.topic: article
ms.service: project-operations
ms.reviewer: kfend
ms.author: rumant
ms.openlocfilehash: bf7941a627375604dca778ab293756bed2536049
ms.sourcegitcommit: 5fd529f2308edfe9322082313e6d50146df56aca
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 04/06/2021
ms.locfileid: "5858078"
---
# <a name="estimate-a-projectbased-contract-line---lite"></a>הערכה של סעיף חוזה מבוסס פרוייקט - לייט

_**חל על**: פריסה בגרסת לייט – מהעסקה ועד להוצאת חשבונית פרופורמה_

ב- Dynamics 365 Project Operations, סעיף חוזה מבוסס פרויקט כולל פרטים המסייעים להעריך את העלות וההכנסות הפוטנציאליות של העבודה הכרוכה במסירת סעיף החוזה.

כדי להעריך סעיף חוזה מבוסס פרויקט, עבור אל הכרטיסיה **פרט סעיף חוזה** ב **סעיף החוזה** מבוסס הפרויקט.  ישנן שתי דרכים ליצור הערכה עבור סעיף חוזה מבוסס פרויקט:

   - יצירת אומדן ישירות על סעיף החוזה על ידי הוספה ידנית של פרטי סעיף חוזה.
   - יצירת פרויקט ותוכנית פרוייקט ולאחר מכן לשייך את הפרויקט והמשימות לסעיף החוזה של הפרויקט. זה מאפשר את התהליך שבאמצעותו ניתן לייבא את ערכת תוכנית הפרוייקט לסעיף החוזה בהתבסס על הרכיבים הכלולים בסעיף החוזה.

## <a name="create-an-estimation-directly-on-a-projectbased-contract-line"></a>יצירת הערכה ישירות בסעיף חוזה מבוסס פרוייקט

ליצירת הערכה ישירות מסעיף חוזה מבוסס פרויקט, בצע את השלבים הבאים:

1. עבור אל סעיף החוזה ובחר את הכרטיסיה **פרט קו חוזה**. השורות שאתה יוצר בכרטיסייה זו מסוכמות ומוצגות כ **כערך שעליו סוכם בחוזה** עבור **סעיף חוזה** זה. 
2. ברשת המשנה **פרטי סעיף חוזה**, בחר **פרט סעיף חוזה חדש**. מחוון ליצירה מהירה נפתח. השדות הבאים זמינים בדף **פרטי סעיף חוזה**.

| שדה | מיקום | תיאור | השפעה במורד הזרם |
| --- | --- | --- | --- |
| **תיאור** | **יצירה מהירה** | תיאור של ההערכה הספיצפית. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **מחלקת עסקאות** | **יצירה מהירה** | זוהי רשימה של סיווגי עסקאות הכלולה בכרטיסיה **כללי** של סעיף החוזה מבוסס הפרויקט. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **בחר מוצר** | **יצירה מהירה** | חלה כאשר סיווג העסקה הוא **חומר**. ניתן לציין אם שורת הערכה זו היא עבור מוצר (קטלוג) **קיים** או מוצר ש **‏‫לא מופיע ברשימה‬**. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **מוצר** | **יצירה מהירה** | מזהה המוצר מקטלוג המוצרים. שדה זה מופעל רק בעת בחירה באפשרות **מוצר קיים** בשדה **בחר מוצר**. המזהה משמש לאחזור מחיר המכירה ממחירון הפרויקט בחוזה. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **מוצר שאינו מופיע ברשימה** | **יצירה מהירה** | שדה טקסט להזנת שם המוצר. שדה זה מופעל רק בעת בחירה באפשרות **לא מופיע ברשימה** בשדה **בחר מוצר**.| ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **תפקיד** | **יצירה מהירה** | תפקיד האדם שמבצע עבודה זו או צובר הוצאה זו. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית.|
| **קטגוריה** | **יצירה מהירה** | קטגוריית ההוצאה או העלות. |ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית.|
| **תאריך התחלה** | **יצירה מהירה** | תאריך ההתחלה של העבודה. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **תאריך סיום** | **יצירה מהירה** | תאריך הסיום של העבודה. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **יחידת הקצאת משאבים** | **יצירה מהירה** | היחידה להקצאת המשאבים שנושאת בעלות זו ומספקת את המשאב שיעבוד עליה. |ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית ומשמש לאחזור מחיר העלות. |
| **לוח זמני יחידה** | **יצירה מהירה** | קבוצת היחידות של עבודה, מוצר או הוצאה. יחידות שייכות ללוח זמנים של יחידה או לקבוצת יחידות. לדוגמה, *מיילים* ו *קילומטרים (ק"מ)* הן יחידות השייכות לקבוצת יחידות המתארות מרחק. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **יחידה** | **יצירה מהירה** | היחידה של עבודה, מוצר או הוצאה. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **כמות** | **יצירה מהירה** | כמות של עבודה, מוצר או הוצאה. | ערך זה הוא כברירת מחדל פרט סעיף החוזה הקשור לעלות שנוצרת אוטומטית. |
| **מחיר יחידה** | **יצירה מהירה** | תעריף החיוב של התפקיד שמבצע את העבודה, מחיר היחידה או מחיר המכירה של קטגוריית המוצר או ההוצאה. ברירת המחדל של שדה זה עבור **זמן** מבוססת על השילוב של ערכי ממד התמחור בשורת מחיר התפקידים במחירון הפרויקט שתקף לתאריך ההתחלה. עבור **הוצאות**, ברירת המחדל של שדה זה היא מהגדרת המחירים עבור קטגוריית העסקאות במחירון הפרויקט שתקף לתאריך ההתחלה. אם שיטת התמחור עבור קטגוריית העסקה אינה **מחיר ליחידה**, אין ברירת מחדל ושדה זה נותר ריק. עבור מוצרים, ברירת המחדל של שדה זה מבוססת על השורה **פריט מחירון** במחירון הפרויקט שתקף לתאריך ההתחלה.| תעריף העלות של התפקיד שמבצע את העבודה, או העלות ליחידה בקטגוריית ההוצאות או עלות היחידה של המוצר. ברירת המחדל של שדה זה עבור **זמן** מבוססת על השילוב של ערכי ממד התמחור בשורת מחיר התפקידים במחירון העלות שמצורף ליחידת חוזה שתקפה לתאריך ההתחלה. עבור הוצאות, ברירת המחדל של שדה זה מבוססת על שורת המחיר של הקטגוריה במחירון העלות המצורף ליחידת החוזה שתקף לתאריך ההתחלה. אם שיטת התמחור עבור קטגוריית העסקה אינה מחיר ליחידה, אין ברירת מחדל ושדה זה נותר ריק. עבור מוצרים, ברירת המחדל לשדה זה מבוססת על **פריט מחירון** במחירון העלות שמצורף ליחידת חוזה שתקפה לתאריך ההתחלה.|
| **מס משוער** | **יצירה מהירה** | המס המשוער עבור עבודה או הוצאה זו. | המס המשוער עבור עבודה או הוצאה זו. |
| **סכום** | **יצירה מהירה** | ניתן להוסיף את הערך בשדה זה אם השדות **כמות** ו **מחיר** נותרים ריקים. אם השדות **כמות** ו **מחיר** מולאו, השדה **סכום‬** הוא לקריאה בלבד ומחושב כ: **(כמות \* מחיר יחידה) + מס**. | &nbsp; |

## <a name="update-prices-on-contract-line-details"></a>עדכן מחירים בפרטי סעיף החוזה

אם משנים את המחירים במחירון הפרויקט המצורף לחוזה או במחירון העלות של היחידת החוזה, אפשר לרענן את המחירים בפרטי שורת החוזה הבודדים כדי לשקף את השינוי. בדף **חוזה**, בחר **חישוב מחדש**. מופיעה אזהרה המודיעה לך כי המחירים עבור כל סעיפי החוזה בחוזה זה מתאפסים. בחר **כן** כדי לרענן מחירים הן לפרטי המכירות בסעיף החוזה והן לפרטי העלות של סעיף החוזה.

## <a name="access-contract-line-details-for-cost"></a>גישה לפרטי סעיף חוזה עבור עלות

בכרטיסיה **פרטי סעיף חוזה** בחר בשורה ברשת כדי להציג פעולות בסרגל הכלים של רשת המשנה. הפעולה הראשונה בסרגל הכלים של רשת המשנה היא **פתח פרט עלות**. כדי לראות את תעריף העלות והסכום הקשורים לפרט זה של קו חוזה, בחר **פתח פרט עלות**. 

> [!NOTE]
> שינוי חברת הקצאת המשאבים, יחידת הקצאת המשאבים, הכמות, התאריכים, התפקיד או ערכי הקטגוריות בפרט סעיף החוזה עבור **עלות** משנה גם את הערכים התואמים בפרט סעיף החוזה עבור **מכירות**.

## <a name="currency-on-contract-line-details-for-cost-and-sales"></a>מטבע בפרטי קו חוזה לעלויות ומכירות

פרט סעיף החוזה עבור **מכירות** מגדיר את מטבע ברירת המחדל ממחירון הפרויקט שתקף לתאריך ההתחלה של פרט סעיף החוזה.

פרט סעיף החוזה עבור **עלות** מגדיר את מטבע ברירת המחדל מהמחירון של יחידת הקצאת המשאבים של החוזה שתקף לתאריך ההתחלה של פרט סעיף החוזה עבור **עלות**.

חישובי רווחיות ממירים את הסכומים עבור פרטי קו החוזה עבור **עלות** ו **מכירות** למטבע הבסיס של הסביבה כדי לדווח על השוליים בפועל והשוליים המשוערים בחוזה.

> [!NOTE]
> טעויות עיגול מטבע ושוליים שהשתנו עלולים להתרחש בגלל היעדר שערי חליפין תקפים לתאריך. השתמש בחישובים אלה רק בחוזי פרויקט, שכן מדובר בהערכות והם אינם דיווח סטטוטורי בפועל או דיווח אחר הדורש דיוק גבוה יותר של עיגול ומודעות לתוקף התאריכים לשערי החליפין.


[!INCLUDE[footer-include](../../includes/footer-banner.md)]