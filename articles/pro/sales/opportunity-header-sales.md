---
title: כותרת הזדמנות
description: נושא זה מספק מידע על המידע הכולל אודות עסקאות מבוססות פרויקט שורות הזדמנות מבוססיות פרויקט.
author: rumant
manager: Annbe
ms.date: 10/01/2020
ms.topic: article
ms.service: dynamics-365-customerservice
ms.reviewer: kfend
ms.author: rumant
ms.openlocfilehash: 2f08de54767f49c308d0ccc7f2e1c6ef880b7f99
ms.sourcegitcommit: a0f80d024a5d3112a39781815bd31d0c05ddaf6f
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 09/30/2020
ms.locfileid: "3906183"
---
# <a name="opportunity-header"></a>כותרת הזדמנות

_**חל על**: פריסה בגרסת לייט – מהעסקה ועד להוצאת חשבונית פרופורמה_

כותרת ההזדמנות כוללת את המידע הכולל אודות עסקה מבוססת פרויקט החלה על כל השורות בהזדמנות מבוססת הפרויקט.

הזדמנויות מבוססות-פרוייקט ב-Dynamics 365 Project Operations הן הרחבות של הזדמנויות Dynamics 365 Sales. הרחבות אלה מספקות פונקציונליות נוספת ספציפית להזדמנויות מבוססות פרויקט הנדרשת להן. הרחבות אלה יכולות לכלול שדות חדשים ופעולות סרט הזמינות בהזדמנויות מבוססות פרויקט. יתכן שתמצא שכמה שדות, פונקציונליות ולוגיקת ברירת מחדל הזמינה Sales אינה זמינה ב-Project Operations.

הטבלה הבאה כוללת את השדות בהזדמנות מבוססת פרויקט שהם ייחודיים ל-Project Operations או שהם כוללים שיוניים חשובים באופן הפעולה מ'הזדמנויות' שב-Sales.

| **שדה** | **מיקום** | **רלוונטיות, מטרה והכוונה** | **השפעה במורד הזרם** |
| --- | --- | --- | --- |
| סוג | כרטיסיה כללית (מוסתרת) | שדה קבוצת אפשרויות מכיל את האפשרויות הבאות:</br>- מבוססת עבודה (זמין רק כאשר Project Operations מותקן)</br>- מבוססת פריט (זמין רק Project Operations ו-Sales מותקנים)</br>- מבוססת תחזוקת שירות (זמין רק כאשר Field Service מותקן) | כאשר אתה משתמש ביישום Project Operations, הערך של שדה זה מוגדר אוטומטית ל**מבוססת עבודה** שמסווג את הזדמנות להזדמנות מבוססת פרויקט. על ההזדמנות להיות מבוססת פרויקט כדי לאפשר את כל ההרחבות והפונקציונליות הספציפיות לפרויקט בתהליך המכירה במורד הזרם עבור עסקה זו. |
| איש קשר | הכרטיסיה 'כללי' | הפניה לאיש הקשר העיקרי של הלקוח לעסקה זו. | |
| חשבון | הכרטיסיה 'כללי' | הפניה לחברת הלקוח או לרשומת תיק הלקוח. | |
| מנהל תיק לקוח | הכרטיסיה 'כללי' | השם של מנהל תיק הלקוח עבור הזדמנות מבוססת פרויקט זו. | מנהל תיק הלקוח אחראי על ניהול הקשר עם הלקוח במהלך השלמת פרויקט זה. יחידת החוזה נוצרת כברירת מחדל, בהתבסס על רשומת להצעת המחיר הקשורה למנהל תיק הלקוח. |
| יחידת החוזה | הכרטיסיה 'כללי' | יחידת הארגון האחראית להגשת הפרויקט או הפרויקטים הקשורים לעסקה זו. | יחידת החוזה היא החטיבה בחברה שתשלים את הפרויקטים לאחר סגירת העסקה. לכל יחידת חוזה יש מטבע, מטבע זה משמש לדיווח על עלויות משוערות ועלויות בפועל שנגרמו במהלך הפרויקט. |

לכל שאר השדות והמקטעים בכרטיסיה **סיכום** של ההזדמנות, ראה [צור או ערוך הזדמנויות (מרכז המכירות ומכירות)](https://docs.microsoft.com/dynamics365/sales-enterprise/create-edit-opportunity-sales)