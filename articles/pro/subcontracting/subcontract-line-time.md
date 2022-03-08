---
title: סעיפי חוזה משנה עבור זמן
description: נושא זה מסביר כיצד לתעד סעיפי חוזה משנה עבור זמן ולתעד את רכישת הזמן מספקים.
author: rumant
ms.date: 08/05/2021
ms.topic: article
ms.reviewer: kfend
ms.author: rumant
ms.openlocfilehash: 10ebe0fcc86b4652ac01e28108361df1f768b61d
ms.sourcegitcommit: 80aa1e8070f0cb4992ac408fc05bdffe47cee931
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 08/13/2021
ms.locfileid: "7323867"
---
# <a name="subcontract-lines-for-time"></a>סעיפי חוזה משנה עבור זמן

[!include [banner](../../includes/dataverse-preview.md)]

_**חל על**: פריסה בגרסת לייט – מהעסקה ועד להוצאת חשבונית פרופורמה_

לחוזה משנה ב- Dynamics 365 Project Operations יכול להיות סעיף חוזה משנה עבור זמן. סעיפי חוזה משנה עבור זמן מאפשרים למנהל פרוייקט לקנות זמן משאב ספק כדי לאייש משימות פרוייקט ודרישות משאבים.

כדי ליצור סעיף חוזה משנה עבור זמן ב- Project Operations, בצע את השלבים הבאים.

1. בחלונית הניווט, בחר **חוזי משנה** ופתח חוזה משנה.
2. בכרטיסיה **סעיפי חוזה משנה**, בחר **חדש** כדי ליצור סעיף חוזה משנה חדש.
3. בדף **יצירה מהירה**, בשדה **סוג עסקה**, בחר **זמן**.
4. הזן את מידע השדה שנותר ובחר **שמור**.

  הטבלה הבאה מספקת מידע אודות השדות בדף **סעיף חוזה משנה** ובדף **יצירה מהירה**.

| **שדה** | **תיאור** |
| --- | --- |
| שם | השם של סעיף חוזה המשנה. |
| תיאור | תיאור קצר של שירותים הנרכשים בסעיף חוזה המשנה. | 
| סוג סעיף | שדה זה הוא ערך ברירת מחדל.  |
| שיטת חיוב | בחר את שיטת החיוב. בהתבסס על שיטת החיוב של סעיף חוזה המשנה שיש הפניה אליו, לוח זמנים לחשבוניות מבוסס-אבני דרך הופך לזמין עבור שיטת החיוב במחיר קבוע. |
| מחלקת עסקאות | שדה זה הוא ערך ברירת מחדל המציין אם נעשה שימוש בסעיף חוזה המשנה כדי לתעד רכישה או זמן של קבלן משנה. |
| תפקיד | התפקיד של משאבי חוזה המשנה שהזמן שלהם נרכש. התפקיד המוקצה למשאבי חוזה המשנה קובע את עלות הרכישה. |
| התחלה מבוקשת | התאריך שבו נדרשים משאבי קבלן המשנה כדי להתחיל בעבודה. ההתחלה המבוקשת משמשת לבחירת מחירון פרוייקט ממחירוני הפרוייקטים המצורפים לחוזה המשנה. עלות התפקיד בסעיף חוזה המשנה נקבעת כברירת מחדל ממחירון זה. |
| סיום מבוקש | התאריך שבו מסתיימת הקצאת המשאבים של קבלן המשנה. תאריך זה משמש להצגת אזהרות כאשר מנהל פרוייקט שואב מקיבולת זו עבור דרישות משאב המופיעות לאחר תאריך זה. |
| כמות שהוזמנה | מספר שעות התפקיד שנרכשות מהספק. ערך זה משמש להצגת אזהרות כאשר מנהל פרוייקט שואב יתר על המידה מקיבולת זו עבור דרישות משאב המופיעות לאחר תאריך זה. |
| קבוצת יחידות | ערך שדה זה מוגדר כברירת מחדל כקבוצת היחידות 'זמן' ולא ניתן לשינוי.  |
| יחידה | שדה זה מוגדר כברירת מחדל כיחידת הבסיס של שעות מקבוצת היחידות 'זמן'. באפשרותך לשנות ערך זה כדי לרכוש כל יחידה מקבוצת היחידות' זמן', כגון יום או שבוע. השילוב של 'תפקיד' ו'יחידה' משמש כדי לחשב את מחיר היחידה עבור סעיף חוזה המשנה. |
| מחיר יחידה | מחיר היחידה נקבע כברירת מחדל משילוב 'תפקיד' ו'יחידה' מתוך מחירון הפרוייקט החל על תאריך ההתחלה המבוקש של סעיף חוזה המשנה. כאשר המחירון של הפרוייקט הרלוונטי כולל את המחיר אשר מוגדר ביחידה שונה מהיחידה בסעיף חוזה המשנה, המערכת משתמשת בהמרת היחידה כדי לחשב את המחיר ליחידה. |
| סכום ביניים | זהו שדה לקריאה בלבד המחושב באופן אוטומטי כ **כמות x מחיר יחידה** אם הוזנו ערכי כמות ומחיר יחידה. אם כמות, מחיר יחידה או שניהם ריקים, באפשרותך להזין ערך בשדה. |
| מס מכירות |  הזן את סכום מס המכירות. |
| סכום כולל | הסכום הכולל של סעיף חוזה המשנה לאחר מסים כלול. |


[!INCLUDE[footer-include](../../includes/footer-banner.md)]