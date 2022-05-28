---
title: יצירה ואישור של יומני ערכים
description: נושא זה מספק מידע על אופן היצירה והאישור של יומני ערכים ב-Microsoft Dynamics 365 Project Operations.
author: rumant
ms.date: 09/18/2020
ms.topic: article
ms.prod: ''
audience: Application User
ms.reviewer: johnmichalak
ms.search.scope: ''
ms.custom: ''
ms.assetid: ''
ms.author: rumant
ms.dyn365.ops.version: ''
ms.search.validFrom: 2020-10-01
ms.openlocfilehash: 8cb768337bc197895a837670f93b99b132c97437
ms.sourcegitcommit: c0792bd65d92db25e0e8864879a19c4b93efb10c
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 04/14/2022
ms.locfileid: "8584229"
---
# <a name="create-and-confirm-entry-journals"></a>יצירה ואישור של יומני ערכים

_**חל על:** Project Operations לתרחישים מבוססי משאבים/לא מלאי, פריסה קלה - עסקה בחשבונית פרופורמה_

משתמשים ביומני כניסה כדי לתעד נתונים בפועל ישירות ב- Microsoft Dynamics 365 Project Operations . כשמשתמשים ביומני ערכים, אין צורך להזין יומני שימוש בזמן, הוצאות וחומר ב- Project Operations.

יומן ערכים יחיד מאפשר לך ליצור שורות יומן מרובות. לאחר אישור היומן, שורת יומן ערכים מתעדת את הנתון בפועל עבור הפרטים הבאים:

- העלות או ההכנסה, בהתאם לסוג של העסקה שנבחרה.
- מחלקת העסקה שנבחרה. המחלקות הזמינות הם **זמן**, **הוצאה**, **חומר**, **ריטיינר**, **אבן דרך**, ו **מס**.
- משימה ו/או הפרויקט שנבחר בשורת היומן.

בצע את השלבים הבאים כדי ליצור יומן ערכים ב- Project Operations.

1. עבור אל **מכירות** \> **עסקאות** \> **יומנים**.
2. בדף הרשימה **יומני ערכים**, בחלונית הפעולה, בחר **חדש** כדי ליצור יומן.
3. בדף **יומן חדש**, בשדה **תיאור**, הזן תיאור של היומן.
4. ודא כי השדה **סוג יומן** מוגדר ל **ערכים**, ולאחר מכן בחר **שמור**. לאחר שמירת יומן הערכים החדש, הכרטיסיה **שורות יומן** אמורה להופיע בדף היומן.
5. בכרטיסייה **שורות יומן**, בסרגל הכלים מעל הרשת, בחר **חדש** כדי ליצור שורת יומן ערכים.
6. בתיבת הדו-שיח **יצירה מהירה** ליצירת שורת יומן ערכים, הגדר את השדות כמתואר בטבלה הבאה.

    | שדה | Description | השפעה פונקציונלית |
    | --- | --- | --- |
    | מחלקת עסקאות | ניתן לסווג את שורת היומן לאחת מששת מחלקות העסקאות: **זמן**, **הוצאה**, **חומר**, **ריטיינר**, **אבן דרך** או **מס**. | מחלקת העסקאות **מס** הוצאה משימוש ב- Project Operations. <br> אם אתה יוצר מחלקת עסקאות **מס**, היא לא תעובד באמצעות חשבונית או בחישובי עלות או הכנסה. **אבן דרך** הוא מחלקת עסקאות של הכנסה בלבד. <br>מחלקט העסקאות **ריטיינר** מייצגת מקדמה שהתקבלה מלקוח. יש ליצור אותו תמיד כזוג שורות יומן מכירות שחויבו ומחירות שלא חויבו. |
    | סוג עסקה | סוגי העסקאות **עלות**, **מכירות בין ארגוניות**, ו **עלות יחידת הקצאת משאבים** צריכים לשמש לתיעוד עלויות.<br> סוגי העסקאות **מכירות שלא חויבו** ו **מכירות שחיובו** צריכים לשמש לתיעוד הכנסות. | מחלקת העסקאות **ריטיינר** עובדת רק עם סוגי העסוקאות **מכירות שלא חויבו** ו **מכירות שחויבו**.<br> מחקת העסקאות **אבן דרך** עובדת רק עם סוג העסקאות **מכירות שחויבו**. <br>סוגי העסקאות **מכירות בין אירגוניות** ו **עלות יחידת הקצאת משאבים** רלוונטים רק למחלקת העסקאות **זמן** ואלה זמינות רק ביומני ערכים בתרחיש הפריסה הקלה ולא בעת פריסת Project Operations בתרחישים של משאב/ללא מלאי. |
    | בחר מוצר | כאשר מחלקת העסקאות **חומר** נבחרת, שדה זה מאפשר לך לציין אם עסקת החומר שעבורה אתה יוצר את שורת היומן היא מוצר קיים או מוצר שאינו מופיע ברשימה. | אם תבחר **מוצר שאינו מופיע ברישמה**, תוכל להזין שם למוצר. |
    | מוצר | הפניה למוצר מהקטלוג. | |
    | Description | תיאור של שורת היומן כדי להקל על הזיהוי. | עבור שורות יומן של מכירות שלא חויבו, הערך ישמש כתיאור בעת יצירת פרטי שורת החשבונית. |
    | תיאור חיצוני | תיאור של שורת היומן שניתן להשתמש בה לשיתוף עם בעלי עניין חיצוניים. | עבור שורות יומן של מכירות שלא חויבו, הערך ישמש כתיאור החיצוני בעת יצירת פרטי שורת החשבונית. הוא יכול להופיע גם בחשבונית הנשלחת ללקוח. |
    | סוג חיוב | ערך המציין אם שורת היומן תיספר כרכיב שניתן לחיוב, ללא תשלום או שלא ניתן לחיוב בפרויקט. | בתזרים טיפוסי, סוג החיוב נגזר מהתנאים המוסכמים שנקבעים בחוזה. עם זאת, כאשר אתה רושם שורת יומן, ניתן להזין ערך בשדה זה. |
    | תאריך מסמך | השתמש בתאריך שבו התרחשה העסקה. | |
    | תאריך התחלה | השתמש בתאריך שבו התרחשה העסקה. | שדה זה משמש להשוואה עם תאריך יצירת החשבונית עבור עסקאות מסוג **מכירות שלא חויבו**. השוואה זו תעזור לך להחליט אם תאריך העסקה היא בעתיד או בעבר. לחשבונית יתווספו רק עסקאות שהתאריך שלהן בעבר. |
    | תאריך סיום | השתמש בתאריך שבו התרחשה העסקה. | |
    | תאריך חשבונאות | השתמש בתאריך שבו תירשם ההשפעה החשבונאית. | |
    | לקוח סעיף חוזה | כברירת מחדל, אם לסעיף החוזה יש רק לקוח אחד, שדה זה מוגדר ללקוח בסעיף החוזה כאשר שורת היומן נשמרת. אם לסעיף החוזה יש מספר לקוחות, בחר את הלקוח הנכון בסעיף החוזה. | אם המערכת לא יכולה לקבוע את לקוח סעיף החוזה בשורת היומן, והוא ריק בנתון בפועל של העסקה מסוג **מכירות שלא חויבו** שנוצר משורת היומן, לא תופק חשבונית עבור הנתון בפועל. |
    | פרויקט | בחר את הפרויקט שבו יש לתעד את הנתון בפועל. | בהתבסס על הפרויקט, מחלקת העסקה והמשימה שנבחרו, המערכת תנסה לקבוע את החוזה, סעיף החוזה ולקוח סעיף החוזה. |
    | משימה | בחר את המשימה שבה יש לתעד את הנתון בפועל. | אם שייכת משימות לסיעיפי חוזה במהלך הגדרת החוזה, המערכת תשתמש במשימה שנבחרה, יחד עם פרויקט ומחלקת עסקאות, כדי לקבוע את החוזה, סעיף החוזה ולקוח סעיף החוזה. |
    | קטגוריית עסקה | בחר את קטגוריית העסקה שבה יש לתעד את הנתון בפועל. | עבור הוצאות, קטגוריית העסקה שנבחרה קובעת את מחיר ברירת המחדל שיוזן בשורת היומן בעת שמירתו. |
    | תפקיד | שדה זה רלוונטי לשורות יומן זמן. בחר את התפקיד של המשאב שהשקיע זמן בפרויקט ו/או במשימה. | עבור שורות יומן זמן, אם אתה משתמש בתצורה שמגיעה עם המוצר להזנת עלויות משאבים ושיעורי חיוב שהגדרו כברירת מחדל, התפקיד הנבחר ישמש יחד עם יחידת הקצאת המשאבים כדי לקבוע את מחיר ברירת המחדל שיוזן בשורת היומן בעת שמירתה. אם אתה משתמש בתצורה מותאמת אישית להזנת מחירי ברירת המחדל, עליך לבדוק את התצורה הזו כדי לקבוע אם השדה **תפקיד** משמש להזנת ערכי ברירת מחדל של מחיר. |
    | חוזה משנה | אם שורת היומן מייצגת קיבולת בקבלנות משנה, או הוצאות או חומרים בקבלנות משנה, בחר את חוזה המשנה הרלוונטי. | כאשר נרשמות שורות יומן עלות, חוזה המשנה הנבחר יקבע את המחירון המשמש להזנת עלות היחידה שהוגדרה כברירת מחדל. |
    | סעיף חוזה משנה | אם שורת היומן מייצגת קיבולת בקבלנות משנה, או הוצאות או חומרים בקבלנות משנה, בחר את סעיף חוזה המשנה הרלוונטי. | כאשר נרשמות שורות של יומן עלות, סעיף חוזה המשנה שנבחר יבטיח שחישובי הקיבולת הזמינה בסעיף חוזה המשנה מחושבים כהלכה. |
    | שיטת סכום | כברירת מחדל, שדה זה מוגדר כ **‏‫הכפלת כמות במחיר‬**. כאשר נעשה שימוש בשיטה זו, הסכום יחושב כ *כמות* × *מחיר*. השיטה הנתמכת השניה היא **מחיר קבוע**. כאשר נעשה שימוש בשיטה זו, המחיר יוגדר לסכום, והכמות לא תשמש בחישוב. | |
    | לוח זמנים של יחידה ויחידה | יחד, לוח הזמנים של היחידה והיחידה מזהים את יחידת הכמות. | השילוב של היחידה וקטגוריית העסקה משמש להזנת מחירי ברירת מחדל להוצאות. בתצורת ברירת המחדל של Project Operations, השילוב של היחידה, התפקיד ויחידת הקצאת המשאבים משמש להזנת מחירי ברירת מחדל עבור זמן. אם יש לך תצורה מותאמת אישית להזנת מחירי ברירת מחדל, היא תשמש יחד עם היחידה. השילוב של המוצר והיחידה משמש להזנת מחירי ברירת מחדל לחומרים. |
    | כמות | הזן את הכמות. | |
    | מחיר | אם המחיר נותר ריק בעת יצירת שורת היומן, הערכים הרלוונטיים ישמשו להזנת מחירי ברירת המחדל, בהתאם למחלקת העסקה. אם יוזן מחיר בעת יצירת שורת היומן, המחיר ישמש. | |
    | סה"כ מס | הזן כל סכום מס. | בהתאם לסכום המס שיוזן, הסכום המורחב יחושב כ *כמות* + *מס*. |

## <a name="confirm-an-entry-journal"></a>אשר יומן ערכים

לאחר שהזנת את כל שורות היומן ביומן ערכים, תוכל לאשר את היומן. תהליך זה ירשום כל שורת יומן כנתונים בפועל בפרויקטים המתאימים.

לאחר אישור יומן, לא תוכל עוד לערוך אותו או את השורות שלו.

## <a name="actuals-created-by-entry-journal-confirmation"></a>נתונים בפועל שנוצרו על ידי אישור יומן ערכים

ישנם כמה הבדלים חשובים בין נתונים בפועל שנוצרו על ידי אישור יומן ערכים לבין נתונים בפועל שנוצרו במהלך אישור יומני שימוש של זמן, הוצאות וחומרים ואישור חשבונית ב- Project Operations:

- יומני ערכים אינם משתמשים בחיבורי עסקאות כדי לקשר את נתון העלות בפועל לנתון המכירות שלא חויבו בפועל. הנתונים בפועל שנוצרים לאחר אישור יומני השימוש בזמן, הוצאות וחומר, תמיד משתמשים בחיבורי עסקאות כדי לקשר את הנתונים בפועל של עלות ומכירות שלא חויבו.
- יומני ערכים אינם משתמשים במקורות של עסקאות כדי לקשר את הנתון בפועל של העלות לנתון בפועל של מכירות שלא חויבו לרשומה מקורית כלשהי. הנתונים בפועל שנוצרים לאחר אישור יומני השימוש בזמן, הוצאות וחומר, תמיד משתמשים בחיבורי מקורות של עסקאות כדי לקשר את הנתונים בפועל של עלות ומכירות שלא חויבו לערך הזמן המקורי.
- כאשר נוצרת חשבונית עבור נתונים בפועל של מכירות שלא חויבו על ידי אישור יומן ערכים, הנתונים בפועל של המכירות שחויבו שנוצרו במהלך אישור החשבונית מקושרים לנתונים בפועל של המכירות שלא חויבו, באופן דומה לנתונים בפועל של המכירות שלא חויבו שנוצרות לאחר אישור יומני השימוש בזמן, הוצאות וחומרים.
- שורות יומן ערכים שנוצרות עבור זמן המוזן על ידי משאבים בין ארגוניים לא גורמות ליצירה אוטומטת של הנתונים בפועל מהסוגים **עלות יחידת הקצאת משאבים** ו **מכירות בין אירגוניות**. יש ליצור את הנתונים בפועל האלה באופן ידני. אופן פועלה זה שונה מאופן הפועלה עבור ערכי זמן המתועדים על ידי משאבים בין ארגוניים. במקרה זה, לאחר אישור הזמן, האפליקציה יוצרת אוטומטית נתונים בפועל מהסוג **עלות** בפרויקט ונתונים בפועל מהסוגים **עלות יחידת הקצאת משאבים** ו **מכירות בין ארגוניות** בחטיבת הבעלים של העובד. לאחר מכן, היא משתמשת בחיבורי עסקאות כדי לקשר את הנתונים בפועל האלה יחד ובמקורות עסקאות כדי לקשר אותם לערך זמן המקור.
- לאחר אישור יומני ערכים, הם יוצרים נתונים בפועל. עם זאת, לא ניתן להשתמש ביומני תיקון כדי לתקן נתונים בפועל אלה. אופן פעולה זה שונה מאופן הפועלה של נתונים בפועל שנוצרים לאחר האישור של יומני שימוש בזמן, הוצאות וחומר. במקרה זה, האפליקציה מאפשרת לך להשתמש ביומני תיקון לתיקון הנתונים בפועל כדי לתקן שגיאות כלשהן, בתנאי שעדיין לא נוצרה חשבונית עבור הנתונים בפועל המדוברים. אם הם כבר נוצרה עבורם חשבונית, עדיין פאשר לתקן נתון בפועל אם יבוצע ללקוח זיכוי מלא של אותו נתון בפועל.

> [!NOTE]
> יומני ערכים אינם אוכפים כללי ברירת מחדל קפדניים. לכן, השתמש ביומני ערכים אלה כמה שפחות, ופעל בזהירות כדי להבטיח שלא תיצור נתונים פיננסיים פגומים במערכת שלך. מתי שאפשר, השתמש ביומני שימוש בזמן, הוצאות וחומר, בהגדרת אבן הדרך וריטיינר בחוזי פרויקטים, ובתהליך אישור חשבונית הפרויקט במקום ביומני ערכים כדי ליצור נתונים בפועל.

[!INCLUDE[footer-include](../includes/footer-banner.md)]