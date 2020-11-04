---
title: הגדרת תעריפי חשבון עבודה
description: נושא זה מספק מידע על הגדרת תעריפי חיוב עבודה ב-Project Operations.
author: rumant
manager: Annbe
ms.date: 10/16/2020
ms.topic: article
ms.service: dynamics-365-customerservice
ms.reviewer: kfend
ms.author: rumant
ms.openlocfilehash: e6294895857442f3a24a9d73ee07d2b90926a4fb
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077370"
---
# <a name="setting-up-bill-rates-for-labor-rate-billing"></a><span data-ttu-id="52e13-103">הגדרת שיעורי חיוב לחיוב עבור עבודה</span><span class="sxs-lookup"><span data-stu-id="52e13-103">Setting up bill rates for labor rate billing</span></span> 

<span data-ttu-id="52e13-104">_**חל על** : פריסה בגרסת לייט – מהעסקה ועד להוצאת חשבונית פרופורמה_</span><span class="sxs-lookup"><span data-stu-id="52e13-104">_**Applies To:** Lite deployment - deal to proforma invoicing_</span></span>

<span data-ttu-id="52e13-105">לכל מחירון יש קבוצה של תעריפים לפי תפקיד, או תעריפים לעבודה, שחלים על ההקשר ותוקף התאריך המופיעים בכותרת המחירון.</span><span class="sxs-lookup"><span data-stu-id="52e13-105">Each price list has a set of role prices, or labor rates, that are effective for the context and date effectivity included on the price list header.</span></span> <span data-ttu-id="52e13-106">ניתן להגדיר שיעורי חיוב עבור זמן ב- Dynamics 365 Project Operations במטבע אחד בלבד, שהוא המטבע בכותרת המחירון.</span><span class="sxs-lookup"><span data-stu-id="52e13-106">Bill rates for time in Dynamics 365 Project Operations can be set up in only one currency, which is the currency on the Price list header.</span></span>

1. <span data-ttu-id="52e13-107">כדי להגדיר תעריפים לחיוב על עבודה עבור מחירון מכירות, צור מחירון על בסיס כותרת המחירון.</span><span class="sxs-lookup"><span data-stu-id="52e13-107">To set up labor bill rates for a sales price list, create a price list based on the price list header.</span></span> 
2. <span data-ttu-id="52e13-108">בכרטיסיה **מחירי תפקידים** , ברשת המשנה, בחר **+ מחיר תפקיד חדש**.</span><span class="sxs-lookup"><span data-stu-id="52e13-108">On the **Role Prices** tab, in the subgrid, select **+ New Role Price**.</span></span> 
3. <span data-ttu-id="52e13-109">בחלונית **יצירה מהירה** , הזן את שילוב התפקיד ויחידת הארגון שעבורו אתה צריך להגדיר את התעריף לחיוב.</span><span class="sxs-lookup"><span data-stu-id="52e13-109">On the **Quick Create** pane, enter the role and organization unit combination for which you need to set up the bill rate.</span></span>

  <span data-ttu-id="52e13-110">הטבלה הבאה כוללת את השדות בכרטיסיה **כללי** ובדף **יצירה מהירה** בשורת מחיר התפקיד שכדאי לקחת בחשבון בעת יצירת מחירי תפקידים במחירון המכירות.</span><span class="sxs-lookup"><span data-stu-id="52e13-110">The following table includes the fields on the **General** tab and the **Quick Create** pane of a role price line that you need keep in mind as you create role prices on a sales price list:</span></span>

  | <span data-ttu-id="52e13-111">שדה</span><span class="sxs-lookup"><span data-stu-id="52e13-111">Field</span></span> | <span data-ttu-id="52e13-112">מיקום</span><span class="sxs-lookup"><span data-stu-id="52e13-112">Location</span></span> | <span data-ttu-id="52e13-113">רלוונטיות, מטרה והכוונה</span><span class="sxs-lookup"><span data-stu-id="52e13-113">Relevance, purpose, and guidance</span></span> | <span data-ttu-id="52e13-114">השפעה במורד הזרם</span><span class="sxs-lookup"><span data-stu-id="52e13-114">Downstream impact</span></span> |
  | --- | --- | --- | --- |
  | <span data-ttu-id="52e13-115">תפקיד</span><span class="sxs-lookup"><span data-stu-id="52e13-115">Role</span></span> | <span data-ttu-id="52e13-116">הכרטיסיה **כללי** וחלונית **יצירה מהירה**</span><span class="sxs-lookup"><span data-stu-id="52e13-116">**General** tab and **Quick Create** pane</span></span> | <span data-ttu-id="52e13-117">בחר את התפקיד שעבורו אתה מגדיר את התעריף לחיוב.</span><span class="sxs-lookup"><span data-stu-id="52e13-117">Select the role that you are setting the bill rate for.</span></span> | <span data-ttu-id="52e13-118">תפקיד בהערכה או בנתון בפועל הנכנסים יותאם לשורה זו כדי להגדיר כברירת מחדל את התעריף לחיוב עבור התפקיד.</span><span class="sxs-lookup"><span data-stu-id="52e13-118">Role on the incoming estimate or actual will be matched against this line to default bill rate of the role.</span></span> |
  | <span data-ttu-id="52e13-119">יחידת הקצאת משאבים</span><span class="sxs-lookup"><span data-stu-id="52e13-119">Resourcing Unit</span></span> | <span data-ttu-id="52e13-120">הכרטיסיה **כללי** וחלונית **יצירה מהירה**</span><span class="sxs-lookup"><span data-stu-id="52e13-120">**General** tab and **Quick Create** pane</span></span> | <span data-ttu-id="52e13-121">בחר את היחידה הארגונית או את החטיבה בחברה שאליה שייך תפקיד זה.</span><span class="sxs-lookup"><span data-stu-id="52e13-121">Select the organizational unit or division of the company that the role is from.</span></span> <span data-ttu-id="52e13-122">לדוגמה, מפתח מחטיבת הרובוטיקה של Fabrikam בהודו או מפתח מחטיבת התוכנה של Fabrikam בארה"ב.</span><span class="sxs-lookup"><span data-stu-id="52e13-122">For example, a developer from the Robotics division of Fabrikam India or a developer from the Software division of Fabrikam USA.</span></span> | <span data-ttu-id="52e13-123">היחידה של הקצאת המשאבים בהערכה או בנתון בפועל הנכנסים תותאם לשורה זו כדי להגדיר כברירת מחדל את תעריף החיוב של התפקיד.</span><span class="sxs-lookup"><span data-stu-id="52e13-123">The resourcing unit on the incoming estimate or actual will be matched against this line to default the bill rate of the role.</span></span> |
  | <span data-ttu-id="52e13-124">מחיר</span><span class="sxs-lookup"><span data-stu-id="52e13-124">Price</span></span> | <span data-ttu-id="52e13-125">הכרטיסיה **כללי** וחלונית **יצירה מהירה**</span><span class="sxs-lookup"><span data-stu-id="52e13-125">**General** tab and **Quick Create** pane</span></span> | <span data-ttu-id="52e13-126">הגדר את השילוב בין התעריף לחיוב עבור התפקיד, החברה של הקצאת המשאבים ויחידת הקצאת המשאבים.</span><span class="sxs-lookup"><span data-stu-id="52e13-126">Set up the bill rate for the role resourcing company and resourcing unit combination.</span></span> <span data-ttu-id="52e13-127">לדוגמה, מפתח מ- Fabrikam הודו הוא בעל תעריף חיוב של 100 דולר או למפתח מ- Fabrikam ארה"ב יש תעריף של 150 דולר.</span><span class="sxs-lookup"><span data-stu-id="52e13-127">For example, a developer from Fabrikam India has a bill rate of 100 USD or a developer from Fabrikam USA has a bill rate of 150 USD.</span></span> | <span data-ttu-id="52e13-128">מחיר זה הוא תעריף החיוב המוגדר כברירת מחדל לכל מחיר ליחידה של שורת ההערכה או הנתון בפועל הנכנסים עבור סיווג העסקה זמן.</span><span class="sxs-lookup"><span data-stu-id="52e13-128">This price is the default bill rate on the per unit price of the incoming estimate or actual line for Time transaction class.</span></span> |
  | <span data-ttu-id="52e13-129">מטבע</span><span class="sxs-lookup"><span data-stu-id="52e13-129">Currency</span></span> | <span data-ttu-id="52e13-130">הכרטיסיה **כללי** וחלונית **יצירה מהירה**</span><span class="sxs-lookup"><span data-stu-id="52e13-130">**General** tab and **Quick Create** pane</span></span>| <span data-ttu-id="52e13-131">כברירת מחדל, ערך המטבע מגיע מהשדה מטבע שבכותרת מחירון המכירות.</span><span class="sxs-lookup"><span data-stu-id="52e13-131">By default, the currency value comes from the currency on the sales price list header.</span></span> <span data-ttu-id="52e13-132">במחירון מכירות לא ניתן לבטל את המטבע.</span><span class="sxs-lookup"><span data-stu-id="52e13-132">On a sales price list, the currency can't be overridden.</span></span> | <span data-ttu-id="52e13-133">מטבע זה מוגדר כברירת מחדל של המחיר ליחידה של שורת מכירות בפועל נכנסת עבור סיווג זמן העסקה.</span><span class="sxs-lookup"><span data-stu-id="52e13-133">This currency is the default currency on the per unit price of the incoming actual sales line for Time transaction class.</span></span> |
  | <span data-ttu-id="52e13-134">לוח זמני יחידה</span><span class="sxs-lookup"><span data-stu-id="52e13-134">Unit Schedule</span></span> | <span data-ttu-id="52e13-135">הכרטיסיה **כללי** וחלונית **יצירה מהירה**</span><span class="sxs-lookup"><span data-stu-id="52e13-135">**General** tab and **Quick Create** pane</span></span> | <span data-ttu-id="52e13-136">לוח הזמנים של היחידות מוגדר כברירת מחדל כ'זמן' ולא ניתן לשנותו בישות המחיר 'תפקיד' מכיוון שהוא משתמש בתעריפי אקספרס לפי יחידות זמן.</span><span class="sxs-lookup"><span data-stu-id="52e13-136">This unit schedule defaults to Time and can't be changed on the Role price entity because it's used to express rates by units of time.</span></span> | <span data-ttu-id="52e13-137">לשדה זה אין השפעה במורד הזרם.</span><span class="sxs-lookup"><span data-stu-id="52e13-137">There is no downstream impact for this field.</span></span> |
  | <span data-ttu-id="52e13-138">יחידה</span><span class="sxs-lookup"><span data-stu-id="52e13-138">Unit</span></span> | <span data-ttu-id="52e13-139">הכרטיסיה **כללי** וחלונית **יצירה מהירה**</span><span class="sxs-lookup"><span data-stu-id="52e13-139">**General** tab and **Quick Create** pane</span></span> | <span data-ttu-id="52e13-140">ערך היחידה מגיע מהשדה **יחידת זמן** שבכותרת של מחירון המכירות.</span><span class="sxs-lookup"><span data-stu-id="52e13-140">The unit value comes from the **Time Unit** field on the sales price list header.</span></span> <span data-ttu-id="52e13-141">אך ניתן לעקוף את הערך.</span><span class="sxs-lookup"><span data-stu-id="52e13-141">But the value can be overridden.</span></span> <span data-ttu-id="52e13-142">לדוגמה, למפתח מ- Fabrikam בהודו יש תעריף חיוב של 1,000 דולר (USD) לכל **יום הודו**.</span><span class="sxs-lookup"><span data-stu-id="52e13-142">For example, a developer from Fabrikam India has bill rate of 1000 USD per **India Day**.</span></span> <span data-ttu-id="52e13-143">למפתח מ- Fabrikam ארה"ב יש תעריף חיוב של 1500 USD לכל **יום ארה"ב**.</span><span class="sxs-lookup"><span data-stu-id="52e13-143">A developer from Fabrikam USA has a bill rate of 1500 USD per **US Day**.</span></span> | <span data-ttu-id="52e13-144">המערכת משתמשת במערכת היחידות וההמרה ביחידות בסיס כדי לחשב עלות ליחידה כאשר ברירת המחדל של המחיר ליחידה היא בשורת ההערכה או הנתון בפועל הנכנסים.</span><span class="sxs-lookup"><span data-stu-id="52e13-144">When the per unit price defaults on an incoming estimate or actual line, the system uses the system of units and conversion in base units to calculate a per unit price.</span></span> <span data-ttu-id="52e13-145">לדוגמה, ההערכה היא שווי עבודה של 10 **ימי הודו** למפתח מהודו, והיחידה 'יום הודו' מוגדרת כ- 10 שעות.</span><span class="sxs-lookup"><span data-stu-id="52e13-145">For example, the estimate is for 10 **India Days** worth of work for a Developer from India, and the unit India Day is defined as 10 hours.</span></span> <span data-ttu-id="52e13-146">כאשר מתמחרים את שורת האומדן, היישום מחשב את מחיר היחידה באומדן כ-‎ 1000 USD / 10 hours = 100 USD לשעה.</span><span class="sxs-lookup"><span data-stu-id="52e13-146">When pricing that estimate line, the application calculates the unit price on the estimate as 1000 USD/10 hours = 100 USD per hour.</span></span> |


## <a name="transfer-pricing-or-set-up-bill-rates-for-resources-from-other-organizational-units-or-divisions"></a><span data-ttu-id="52e13-147">העבר את התמחור או הגדר תעריפים לחיוב עבור משאבים מיחידות או חטיבות ארגוניות אחרות</span><span class="sxs-lookup"><span data-stu-id="52e13-147">Transfer pricing or set up bill rates for resources from other organizational units or divisions</span></span> 

<span data-ttu-id="52e13-148">חברות מבוססות פרויקטים משתמשות בעובדים ממחלקות או מחטיבות שונות בחברה לעבודה על פרויקטים.</span><span class="sxs-lookup"><span data-stu-id="52e13-148">Project-based companies to use employees from different divisions of the company to work on projects.</span></span> <span data-ttu-id="52e13-149">ניתן לבצע פרויקטים מחטיבה אחת בעוד העובדים או היועצים מגיעים מחטיבה אחרת של החברה.</span><span class="sxs-lookup"><span data-stu-id="52e13-149">Projects can be executed from one division while the employees or consultants come from the same a different division of the company.</span></span> <span data-ttu-id="52e13-150">הפרויקט יכול להיות מורכב גם משילוב של אנשים מחטיבות שונות.</span><span class="sxs-lookup"><span data-stu-id="52e13-150">The project could also be made up of a combination of people from different divisions.</span></span> <span data-ttu-id="52e13-151">ב- Project Operations, החברה שאחראית על מסירת הפרויקט נקראת **יחידת החוזה**.</span><span class="sxs-lookup"><span data-stu-id="52e13-151">In Project Operations, the company that owns the delivery of the project is called the **Contracting Unit**.</span></span> <span data-ttu-id="52e13-152">כל שאר החטיבות המספקות משאבים נקראות **יחידות מיקור**.</span><span class="sxs-lookup"><span data-stu-id="52e13-152">All the other divisions that provide resources are called the **Resourcing Units**.</span></span> <span data-ttu-id="52e13-153">בגלל ההבדלים בעלויות העבודה בין אזורים שונים ובשווקי העבודה ברחבי העולם, תעריפי החיוב עבור עבודה נקבעים גם באופן שונה באזורים גיאוגרפיים שונים.</span><span class="sxs-lookup"><span data-stu-id="52e13-153">Because of the differences in labor costs across various geographies and labor markets across the world, bill rates for labor are also set up differently for different geographies.</span></span>

<span data-ttu-id="52e13-154">לדוגמה, מפתח מ- Fabrikam הודו שעובד על פרויקט אמריקאי מחויב בשיעור של 100 USD לשעה.</span><span class="sxs-lookup"><span data-stu-id="52e13-154">For example, a developer from Fabrikam India working on a US project is billed at the rate of 100 USD per hour.</span></span> <span data-ttu-id="52e13-155">מפתח מ- Fabrikam ארה"ב שעובד על פרויקט בארה"ב מחויב בסכום של 150 USD לשעה.</span><span class="sxs-lookup"><span data-stu-id="52e13-155">A developer from Fabrikam US working on US Project is billed at 150 USD per hour.</span></span>

### <a name="example-set-up-a-bill-rate"></a><span data-ttu-id="52e13-156">דוגמה: הגדר תעריף חיוב</span><span class="sxs-lookup"><span data-stu-id="52e13-156">Example: Set up a bill rate</span></span>

1. <span data-ttu-id="52e13-157">צור מחירון מכירות שנקרא *שיעורי החיוב של Fabrikam בארה"ב* , וקבע את תאריך התוקף.</span><span class="sxs-lookup"><span data-stu-id="52e13-157">Create a sales price list called *Fabrikam US Bill Rates* , and set the date effectivity.</span></span>
2. <span data-ttu-id="52e13-158">במחירון המכירות הזן את נתוני התעריפים הבאים:</span><span class="sxs-lookup"><span data-stu-id="52e13-158">In the sales price list, enter the following rate information:</span></span>

    | <span data-ttu-id="52e13-159">תפקיד</span><span class="sxs-lookup"><span data-stu-id="52e13-159">Role</span></span> | <span data-ttu-id="52e13-160">יחידה ארגונית</span><span class="sxs-lookup"><span data-stu-id="52e13-160">Organizational unit</span></span> | <span data-ttu-id="52e13-161">תעריף חיוב</span><span class="sxs-lookup"><span data-stu-id="52e13-161">Bill rate</span></span> |
    | --- | --- | --- |
    | <span data-ttu-id="52e13-162">מפתחים</span><span class="sxs-lookup"><span data-stu-id="52e13-162">Developer</span></span> | <span data-ttu-id="52e13-163">Fabrikam בהודו</span><span class="sxs-lookup"><span data-stu-id="52e13-163">Fabrikam India</span></span> | <span data-ttu-id="52e13-164">$100</span><span class="sxs-lookup"><span data-stu-id="52e13-164">$100</span></span> |
    | <span data-ttu-id="52e13-165">מפתחים</span><span class="sxs-lookup"><span data-stu-id="52e13-165">Developer</span></span> | <span data-ttu-id="52e13-166">Fabrikam בפיליפינים</span><span class="sxs-lookup"><span data-stu-id="52e13-166">Fabrikam Philippines</span></span> | <span data-ttu-id="52e13-167">$90</span><span class="sxs-lookup"><span data-stu-id="52e13-167">$90</span></span> |
    | <span data-ttu-id="52e13-168">מפתחים</span><span class="sxs-lookup"><span data-stu-id="52e13-168">Developer</span></span> | <span data-ttu-id="52e13-169">Fabrikam בארה"ב</span><span class="sxs-lookup"><span data-stu-id="52e13-169">Fabrikam US</span></span> | <span data-ttu-id="52e13-170">$150</span><span class="sxs-lookup"><span data-stu-id="52e13-170">$150</span></span> |

3. <span data-ttu-id="52e13-171">צרף את מחירון המכירות, **שיעורי החיוב של Fabrikam בארה"ב** למחירון הפרויקט של חוזה הפרויקט או לתיק לקוח מסוים.</span><span class="sxs-lookup"><span data-stu-id="52e13-171">Attach the sales price list, **Fabrikam US Bill Rates** to the project price list of the project contract or to a certain account.</span></span>