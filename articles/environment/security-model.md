---
title: מודל האבטחה
description: נושא זה מספק מידע על מודל האבטחה ב- Dynamics 365 Project Operations.
author: stsporen
manager: Annbe
ms.date: 10/01/2020
ms.topic: article
ms.service: dynamics-365-customerservice
ms.reviewer: kfend
ms.author: stsporen
ms.openlocfilehash: ffcfa8a9c8e31c5665acd3c3919fa90d36a3f3ca
ms.sourcegitcommit: a2c3cd49a3b667b8b5edaa31788b4b9b1f728d78
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 09/28/2020
ms.locfileid: "3896732"
---
# <a name="security-model"></a>מודל האבטחה

_**חל על:** Project Operations לתרחישים מבוססי משאבים/לא מלאי, פריסה קלה - עסקה בחשבונית פרופורמה_

Microsoft Dynamics 365 Project Operations מכיל מודל אבטחה ייחודי המאפשר מודל אבטחה עסקי מבוסס תפקיד המשתף פעולה עם Microsoft Office Groups. 


## <a name="security-roles"></a>תפקידי אבטחה
יכולות החזית של Project Operations כוללות את התפקידים הבאים:

| תפקיד                          | תיאור                                                                                                                                                                 | Scope |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|
| מנהל שיטות עבודה              | תומך בדיווח חוצה פרויקט.                                                                                                            | יחידה עסקית              |
| מאשר הפרויקט              | מאשר שעות והוצאות כנגד פרויקט.                                                                                                                              | יחידה עסקית |
| מנהל חיוב פרויקט | יוצר את הצעת החשבונית.                                                                                                                                                 | יחידה עסקית |
| מנהל פרוייקט               | יוצר את תוכנית הפרויקט ומבקש משאבים.                                                                                                                              | יחידה עסקית |
| משאב פרויקט              | חברי צוות שניתן להזמין אותם והם יכולים לדווח על שעות.                                                                                                          | יחידה עסקית|
| מנהל משאבים              | כל פונקציות ניהול המשאבים, כגון מילוי בקשות והזמנות של משאבים, מופרדות לתמיכה בתצורה היברידית של מנהל פרויקט + מנהל משאבים ובתפקיד מנהל משאבים יחיד ומרכזי. | יחידה עסקית |


Microsoft Project באינטרנט כולל את התפקידים הבאים:
| תפקיד                          | תיאור                                                                                                          | Scope |                                                       
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|
| משתמש בפרויקט | משתמש משותף של Project המסוגל ליצור פרויקטים משלו ולהציג את כל הפרויקטים המשותפים איתו.| משתמש|
| מערכת פרויקט | תפקיד המשמש להקשר יישום. לקוחות לא אמורים להשתמש בתפקיד מערכת זה. | כללי|

## <a name="security-enforcement"></a>אכיפת אבטחה
פעולות המתבצעות ברמת הפרויקט מבוצעות בהקשר של המשתמש המחובר. המשמעות היא שכדי ליצור, לפתוח או למחוק פרויקט, למשתמש נדרשת גישה ל- CDS. ניתן להעניק גישה ל- CDS באמצעות כל אחד מהמנגנונים האפשריים הכלולים בפלטפורמה. לדוגמה, משתמש עם טווח גדול יותר רשאי לגשת לפרויקט או אם בוצעה פעולה מפורשת לשיתוף פרויקט המעניקה למשתמש גישה.

חשוב להביא את זה בחשבון בעת יצירת פרויקטים ב- Project Operations.

## <a name="modern-group-collaboration-with-project-operations"></a>שיתוף פעולה מודרני בין קבוצות עם Project Operations
Project באינטרנט ו- Project Operations תומכים בקבוצות מודרניות לשיתוף פעולה. משתמשים שנוספו לפרויקט באמצעות קבוצה יכולים לערוך את תוכנית הפרויקט.

Project באינטרנט מוסיף משתמשים לקבוצה באופן אוטומטי עם ההקצאה.

הקבוצות מאפשרות לעבוד בשיתוף פעולה על ההרשאות לפרויקט ועל תוצרים נתמכים של שיתוף הפעולה. התרשים הבא מתאר את האירועים ומציין שינויים שקורים במהלך תהליך הקצאת הקבוצה.

Project Operations לא יוצר קבוצה באמצעות פעולה משתמעת ועושה זאת רק באמצעות פעולה מפורשת של קבוצות הדורשות זאת.

חיפוש חבר קבוצה בדו-שיח **ניהול קבוצה** מוגבל לאלה המוגדרים כחלק מקבוצת האבטחה של הסביבה. למידע נוסף, ראה [בקרה על גישת משתמשים לסביבות: קבוצות אבטחה ורשיונות](https://docs.microsoft.com/power-platform/admin/control-user-access).

1. הפרויקט נוצר על-ידי המשתמש היוצר והוא בבעלותו.
2. הבעלים של הפרויקט מעודכן בצוות.
3. צוות הבעלים ממופה לקבוצת Office שצוינה או שנוצרה.
4. הבעלים המקורי של הפרויקט מתווסף לקבוצת Office.

## <a name="deployment-recommendation"></a>המלצת פריסה
ככל שמודל שיתוף הפעולה של קבוצת Office יתפתח, תתווסף פונקציונליות כדי לספק בקרה מפורטת יותר לאורך זמן. לקוחות הפורשים Project Operations היום מוזמנים להתמקד במודל האבטחה המסורתי של Microsoft Dynamics 365.

לקבלת מידע נוסף, ראה [אבטחה ב- Common Data Service](https://docs.microsoft.com/power-platform/admin/wp-security).

## <a name="project-operations-and-microsoft-dynamics-365-finance-security"></a>אבטחת Project Operations ו- Microsoft Dynamics 365 Finance
Project Operations כולל את התפקידים הבאים:

- מנהל פרוייקט
- רואה חשבון של פרויקט

למידע נוסף על אבטחה ב- Finance, ראה [אבטחה מבוססת תפקידים](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/sysadmin/role-based-security).

