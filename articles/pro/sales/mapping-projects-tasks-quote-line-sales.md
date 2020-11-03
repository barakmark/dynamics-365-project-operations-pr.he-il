---
title: מיפוי פרויקטים ומשימות בשורות הצעת מחיר מבוססת פרויקט
description: נושא זה מספק מידע על אופן מיפוי פרויקטים ומשימות בשורת משימות מבוססת פרויקט.
author: rumant
manager: Annbe
ms.date: 10/05/2020
ms.topic: article
ms.service: dynamics-365-customerservice
ms.reviewer: kfend
ms.author: rumant
ms.openlocfilehash: d726ab09da0e502da99191f7e7469c47f79b6e7c
ms.sourcegitcommit: 6b396ccf5e76230a42a2f933a3aaa5b8149790bb
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/06/2020
ms.locfileid: "3964908"
---
# <a name="map-projects-and-tasks-to-a-project-based-quote-line"></a>מיפוי פרויקטים ומשימות בשורות הצעת מחיר מבוססת פרויקט

_**חל על:** Project Operations לתרחישים מבוססי משאבים/לא מלאי, פריסה קלה - עסקה בחשבונית פרופורמה_

בשורות הצעות מחיר מבוססות פרויקט, אפשר למפות את המשימות הספציפיות של פרויקט שכבר משויך לשורת הצעת מחיר.

כשממפים משימות לשורת הצעת מחיר, רק עליהם יכולו הפריטים הבאים, שהגדרת בשורת הצעת המחיר:

- שיטת חיוב
- אפשרויות של יכולת חיוב
- מגבלות 'אין לחרוג'
- לקוחות

לדוגמה, ייתכן שיהיה לך פרויקט שבו שלב אחד הוא במחיר קבוע וכל שאר השלבים הם לפי זמן וחומרים. במקרה זה, ניתן לשייך את השלב הראשון ואת כל המשימות הבנות שלו לשורת הצעת המחיר של אותו שלב עם שיטת חיוב במחיר קבוע. לאחר מכן, ניתן לשייך את כל השלבים האחרים לשורת הצעת המחיר מבוססת זמן וחומרים.

## <a name="associate-tasks-to-project-based-quote-lines"></a>שיוך משימות להצעות מחיר מבוססות פרויקט

ניתן לשייך משימות לשורות הצעות מחיר מהמיקומים הבאים:

- מהדף **פרויקט** > לשונית **חיוב משימות** (אופטימלי)
- מהדף **שורת הצעת מחיר** > כרטיסיה **משימות הניתנות לחיוב** 

### <a name="from-the-project-page"></a>מדך הפרוייקט

הדף **פרויקט** מספק את החוויה האופטימלית עבור שיוך משימות לשורות הצעת מחיר. אפשר להשתמש בדף זה כדי לבחור מספר משימות ולשייך את כולן, בתוספת המשימות הבנות שלהן, לשורת הצעת המחיר שנבחרה.

1. בכרטיסיה **כללי** של שורת הצעת מחיר מבוססת פרויקט, אמת שהשדה **פרויקט** מלא.
2. בשדה **משימות כלולות**, בחר **משימות נבחרות בלבד**.
3. שמור את שורות הצעת המחיר מבוססות הפרויקט. לאחר ריענון הטופס, תוצג הכרטיסיה **משימות הניתנות לחיוב**.
4. בכרטיסיה **כללי**, בחר את הקישור לפרויקט מתוך השדה **פרויקט**.
5. בדף **פרוייקט**, בחר בכרטיסיה **חיוב משימות**.
6. ברשת השנייה, שחלה על הגדרת חיוב ספציפי למשימה, בחר משימה אחת או יותר ואז בחר **שורות הצעות מחיר משויכות**.
7. בדף הדו-שיח שמופיע, בחר שורת הצעת מחיר המציגה שורות הצעת מחיר מבוססות פרויקט על הצעת המחיר.
8. בשדה **סוג החיוב**, ציין אם אלה משימות הניתנות לחיוב או משימות שאינן ניתנות לחיוב.
9. בחר בתיבת הסימון כדי לציין אם השיוך צריך לכלול את המשימות הבנות של המשימות שנבחרו. סימון תיבת הסימון ישייך את המשימות הבנות של המשימות שנבחרו לשורת הצעת המחיר.
10. בחר **אישור** כדי לסגור את הדו-שיח.

### <a name="from-the-quote-line-page"></a>מדף שורת הצעת מחיר

ניתן לשייך משימות פרויקט לשורות הצעות מחיר מהכרטיסיה **משימות הניתנות לחיוב** בדף **שורת הצעות מחיר**.

>[!NOTE]
>המקום האופטימלי לשיוך משימות פרויקט לשורות הצעת מחיר הוא בחרטיסיה **חיוב משימות** שבדף **פרויקט**. אם אתה משייך משימות מהכרטיסיה **משימות הניתנות לחיוב** שבדף **שורת הצעת מחיר**, עליך לשייך ידנית כל פרויקט.

1. בכרטיסיה **כללי** של שורת הצעת מחיר מבוססת פרויקט, אמת שנבחרה פרויקט בשדה **פרויקט**.
2. בשדה **משימות כלולות**, בחר **משימות נבחרות בלבד**.
3. שמור את שורות הצעת המחיר מבוססות הפרויקט. לאחר ריענון הטופס, תוצג הכרטיסיה **משימות הניתנות לחיוב**.
4. בכרטיסיה **משימות הניתנות לחיוב**, בחר **הוסף משימה של שורת הצעת מחיר**.
5. בדף **שורת הצעת מחיר** , בשדה **משימות**, בחר את המשימה ובשדה **סוג החיוב** בחר **שמור**. 
6. סגור את הדף. המשימה שנבחרה משויכת כעת לשורת הצעת המחיר.

## <a name="disassociate-tasks-from-projectbased-quote-lines"></a>ביטול השיוך של משימות להצעות מחיר מבוססות פרויקט

### <a name="from-the-project-page"></a>מדך הפרוייקט

שיטה זו מספק תאת החוויה האופטימלית ביותר עבור ביטול השיוך של משימות לשורות הצעת מחיר. אפשר לבחור משימות מרובות ולבטל את השיוך של כולן, ושל המשימות הבנות שלהן, לשורת הצעת המחיר שנבחרה.

1. בכרטיסיה **כללי** של שורת הצעת מחיר מבוססת פרויקט, בשדה **פרויקט** בחר את קישור הפרויקט.
2. בדף **פרוייקט**, בחר בכרטיסיה **חיוב משימות**.
3. ברשת השנייה, שחלה על הגדרה של חיוב ספציפי למשימה, בחר משימה אחת או יותר ואז בחר **בטל את השיוך של שורות הצעות מחיר**.
4. בדף הדו-שיח שמוצג, בחר בשורת הצעת מחיר.
5. בחר בתיבת הסימון כדי לציין אם יש להסיר את השיוך גם מהמשימות הבנות של המשימות שנבחרו. סימון תיבת הסימון יבטל גם את השיוך של המשימות הבנות של המשימות שנבחרו לשורת הצעת המחיר.
6. בחר **אישור**. הודעת אזהרה מודיעה לך שאם תסיר שיוך זה, רישום של נתונים בפועל שנרשמו בעבר במשימה עשוי להתבטל. 
7. בחר **אישור** כדי להמשיך ולהסיר את השיוק שבין המשימה לשורת הצעת המחיר מבוססת הפרויקט.

### <a name="from-the-quote-line-page"></a>מדף שורת הצעת מחיר

ניתן גם לבטל את השיוך של משימות פרויקט לשורות הצעות מחיר מהכרטיסיה **משימות הניתנות לחיוב** בדף **שורת הצעת מחיר**.

1. בכרטיסיה **משימות הניתנות לחיוב**, בחר **מחק משימה של שורת הצעת מחיר**.
2. בחר **אישור**. הודעת אזהרה מודיעה לך שאם תסיר שיוך זה, רישום של נתונים בפועל שנרשמו בעבר במשימה עשוי להתבטל. 
3. בחר **אישור** כדי להמשיך ולהסיר את השיוק שבין המשימה לשורת הצעת המחיר מבוססת הפרויקט.

>[!NOTE]
> הליך זה אינו מוחק את המשימה מהפרויקט. אלא רק מסיר את שיוך המשימות משורת הצעת המחיר מבוססת הפרויקט.