---
title: פתרון מחירי עלות להערכות ולנתונים בפועל
description: נושא זה מספק מידע אודות אופן פתרון מחירי העלות של הערכות ונתונים ופועלים.
author: rumant
manager: Annbe
ms.date: 10/13/2020
ms.topic: article
ms.service: dynamics-365-customerservice
ms.reviewer: kfend
ms.author: rumant
ms.openlocfilehash: bad8f4b95ac5803d3f334e1b306d2a9d27a6645d
ms.sourcegitcommit: 11a61db54119503e82faec5f99c4273e8d1247e5
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077218"
---
# <a name="resolving-cost-prices-on-estimates-and-actuals"></a><span data-ttu-id="21b85-103">פתרון מחירי עלות להערכות ולנתונים בפועל</span><span class="sxs-lookup"><span data-stu-id="21b85-103">Resolving cost prices on estimates and actuals</span></span>

<span data-ttu-id="21b85-104">_**חל על** : פריסה בגרסת לייט – מהעסקה ועד להוצאת חשבונית פרופורמה_</span><span class="sxs-lookup"><span data-stu-id="21b85-104">_**Applies To:** Lite deployment - deal to proforma invoicing_</span></span>

<span data-ttu-id="21b85-105">כדי לפתור מחירי עלות ומחירון העלויות להערכות ולנתונים בפועל, המערכת משתמשת במידע שמופיע בשדות **תאריך** , **מטבע** , ו **יחידת החוזה** של הפרויקט הקשור.</span><span class="sxs-lookup"><span data-stu-id="21b85-105">To resolve cost prices and the cost price list for estimates and actuals, the system uses the information in the **Date** , **Currency** , and **Contracting Unit** fields of the related project.</span></span> <span data-ttu-id="21b85-106">לאחר פתרון מחירון העלות, היישום פותר את תעריף העלות.</span><span class="sxs-lookup"><span data-stu-id="21b85-106">After the cost price list is resolved, the application resolves the cost rate.</span></span>

## <a name="resolving-cost-rates-on-actual-and-estimate-lines-for-time"></a><span data-ttu-id="21b85-107">פתרון תעריפי עלות בנתונים בפועל והערכת עבור 'זמן'</span><span class="sxs-lookup"><span data-stu-id="21b85-107">Resolving cost rates on actual and estimate lines for Time</span></span>

<span data-ttu-id="21b85-108">שורות הערכה ל'זמן' מתייחסים לפרטי הצעת המחיר וסעיף החוזה להקצאת זמן ומשאבים בפרויקט.</span><span class="sxs-lookup"><span data-stu-id="21b85-108">Estimate lines for Time refer to the quote and contract line details for time and resource assignments on a project.</span></span>

<span data-ttu-id="21b85-109">לאחר פתרון מחירון עלות, המערכת משתמשת בשדות **תפקיד** ו **יחידת הקצאת משאבים** שבשורת ההערכה של 'זמן' להתאמה מול שורות מחירי התפקידים במחירון.</span><span class="sxs-lookup"><span data-stu-id="21b85-109">After a cost price list is resolved, the system uses the **Role** and **Resourcing Unit** fields on the estimate line for Time to match against the role price lines in the price list.</span></span> <span data-ttu-id="21b85-110">הנחת היסוד של פעולת התאמה זו היא שאתה משתמש בממדי תמחור מוכנים לשימוש עובר עלות העבודה.</span><span class="sxs-lookup"><span data-stu-id="21b85-110">This match assumes that you are using out-of-the-box pricing dimensions for labor cost.</span></span> <span data-ttu-id="21b85-111">אם הגדרת את המערכת כך שתתאים שדות במקום, או בנוסף לשדות **תפקיד** ו **יחידת הקצאת משאבים** , שילוב אחר ישימש כדי לאחזר שורת מחיר תפקיד תואם.</span><span class="sxs-lookup"><span data-stu-id="21b85-111">If you configured the system to match fields instead of, or in addition to **Role** and **Resourcing Unit** , then a different combination will be used to retrieve a matching role price line.</span></span> <span data-ttu-id="21b85-112">אם היישום מוצא שורת מחיר תפקיד שיש לה תעריף עלות עבור השילוב בין **תפקיד** ו **יחידת הקצאת משאבים** , זהו תעריף ברירת המחדל של עלות.</span><span class="sxs-lookup"><span data-stu-id="21b85-112">If the application finds a role price line that has a cost rate for the **Role** and **Resourcing Unit** combination, that is the default cost rate.</span></span> <span data-ttu-id="21b85-113">אם היישום אינו יכול להתאים את הערכים של **תפקיד** ו **יחידת הקצאת משאבים** , הוא מאחזר שורות מחיר תפקיד עם תפקיד תואם, אך עם ערכי Null עבור **יחידת הקצאת משאבים**.</span><span class="sxs-lookup"><span data-stu-id="21b85-113">If the application can't match the **Role** and **Resourcing Unit** values, then it retrieves role price lines with a matching role, but null values of the **Resourcing Unit**.</span></span> <span data-ttu-id="21b85-114">לאחר שמצא רשומת מחיר תפקיד תואם, ברירת המחדל של תעריף העלות נקבעת מאותה רשומה.</span><span class="sxs-lookup"><span data-stu-id="21b85-114">After it has a matching role price record, the cost rate defaults from that record.</span></span> 

> [!NOTE]
> <span data-ttu-id="21b85-115">אם מגדירים עדיפות שונה ל **תפקיד** ול **יחידת הקצאת משאבים** , או אם יש לך ממדים אחרים בעלי עדיפות גבוהה יותר, אופן פעולה זה ישתנה בהתאם.</span><span class="sxs-lookup"><span data-stu-id="21b85-115">If you configure a different prioritization of **Role** and **Resourcing Unit** , or if you have other dimensions that have higher priority, this behavior will change accordingly.</span></span> <span data-ttu-id="21b85-116">המערכת מאחזרת רשומות של מחירי תפקידים עם ערכים התואמים לכל אחד מערכי ממדי התמחור לפי סדר העדיפות עם שורות בעלות ערכי Null עבור אותם ממדים בעלי העדיפות הנמוכה ביותר.</span><span class="sxs-lookup"><span data-stu-id="21b85-116">The system retrieves role price records with values that match each of the pricing dimension values in order of priority with rows that have null values for those dimensions coming last.</span></span>

## <a name="resolving-cost-rates-on-actual-and-estimate-lines-for-expense"></a><span data-ttu-id="21b85-117">פתרון תעריפי עלות בשורות של נתונים בפועל ושל הערכת עבור 'הוצאה'</span><span class="sxs-lookup"><span data-stu-id="21b85-117">Resolving cost rates on actual and estimate lines for Expense</span></span>

<span data-ttu-id="21b85-118">שורות הערכה ל'הוצאה' מתייחסות לפרטי ההוצאת של הצעת המחיר וסעיף החוזה ולשורות הערכת ההוצאות בפרויקט.</span><span class="sxs-lookup"><span data-stu-id="21b85-118">Estimate lines for Expense refer to the quote and contract line details for expenses and the expense estimate lines on a project.</span></span>

<span data-ttu-id="21b85-119">לאחר פתרון מחירון עלות, המערכת משתמשת בשילוב של השדות **קטגוריה** , ו **יחידה** שבשורת ההערכה של 'הוצאה' להתאמה מול שורות **מחירי הקטגוריות** שבמחירון שנפתר.</span><span class="sxs-lookup"><span data-stu-id="21b85-119">After a cost price list is resolved, the system uses a combination of the **Category** and **Unit** fields on the estimate line for an expense to match against the **Category Price** lines on the resolved price list.</span></span> <span data-ttu-id="21b85-120">אם היישום מוצא שורת מחיר של קטגורה שיש לה תעריף עלות עבור השילוב בין השדות **קטגוריה** ו **יחידה** , זהו תעריף ברירת המחדל של עלות.</span><span class="sxs-lookup"><span data-stu-id="21b85-120">If the system finds a category price line that has a cost rate for the **Category** and **Unit** field combination, the cost rate is defaulted.</span></span> <span data-ttu-id="21b85-121">אם המערכת לא יכולה להתאים בין הערכים של **קטגוריה** ו **יחידה** , או אם היא מוצאת שורת מחיר תואמת של קטגוריה אך שיטת התמחור אינה **מחיר ליחידה** , תעריף העלות תהיה אפס (0) כברירת מחדל.</span><span class="sxs-lookup"><span data-stu-id="21b85-121">If the system can't match the **Category** and **Unit** values, or if it is able to find a matching category price line but the pricing method is not **Price Per Unit** , the cost rate is defaulted to zero(0).</span></span>