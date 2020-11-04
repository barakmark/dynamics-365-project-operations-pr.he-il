---
title: תמחור פרוייקט
description: נושא זו מספק מידע אודות האופן שבו תמחור פועל ב- Dynamics 365 Project Service Automation.
author: rumant
manager: kfend
ms.service: dynamics-365-customerservice
ms.custom:
- dyn365-projectservice
ms.date: 03/11/2019
ms.topic: article
ms.author: rumant
audience: Admin
search.audienceType:
- admin
- customizer
- enduser
search.app:
- D365CE
- D365PS
- ProjectOperations
ms.openlocfilehash: b319f9be9fd72ac99ce6012b6baffde812e3077d
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077505"
---
# <a name="project-pricing"></a><span data-ttu-id="dffc0-103">תמחור פרוייקט</span><span class="sxs-lookup"><span data-stu-id="dffc0-103">Project pricing</span></span> 

[!INCLUDE[cc-applies-to-psa-app-3.x](../includes/cc-applies-to-psa-app-3x.md)]

<span data-ttu-id="dffc0-104">Dynamics 365 Project Service Automation מרחיב את הישות 'מחירון' ב- Dynamics 365 Sales.</span><span class="sxs-lookup"><span data-stu-id="dffc0-104">Dynamics 365 Project Service Automation extends the Price list entity in Dynamics 365 Sales.</span></span> 

## <a name="key-entities"></a><span data-ttu-id="dffc0-105">ישויות עיקריות</span><span class="sxs-lookup"><span data-stu-id="dffc0-105">Key entities</span></span>

<span data-ttu-id="dffc0-106">מחירון כולל מידע המסופק על-ידי ארבע ישויות שונות:</span><span class="sxs-lookup"><span data-stu-id="dffc0-106">A price list includes information that is provided by four different entities:</span></span>

- <span data-ttu-id="dffc0-107">**מחירון** - ישות זו מאחסנת מידע אודות הקשר, מטבע, תוקף של תאריך ויחידת זמן עבור זמן תמחור.</span><span class="sxs-lookup"><span data-stu-id="dffc0-107">**Price List** - This entity stores information about context, currency, date effectivity, and time unit for pricing time.</span></span> <span data-ttu-id="dffc0-108">ההקשר מציג אם המחירון מבטא תעריפי עלות או תעריפי מכירות.</span><span class="sxs-lookup"><span data-stu-id="dffc0-108">Context shows whether the price list is expresses cost rates or sales rates.</span></span> 
- <span data-ttu-id="dffc0-109">**מטבע** - ישות זו מאחסנת את מטבע המחירים במחירון.</span><span class="sxs-lookup"><span data-stu-id="dffc0-109">**Currency** - This entity stores the currency of prices on the price list.</span></span> 
- <span data-ttu-id="dffc0-110">**תאריך** - ישות זו נמצאת בשימוש כאשר המערכת מנסה להזין מחיר ברירת מחדל בעסקה.</span><span class="sxs-lookup"><span data-stu-id="dffc0-110">**Date** - This entity is used when the system tries to enter a default a price on a transaction.</span></span> <span data-ttu-id="dffc0-111">תמחור PSA בוחר את המחירון בעל תוקף של תאריך הכולל את תאריך העסקה.</span><span class="sxs-lookup"><span data-stu-id="dffc0-111">PSA pricing selects the price list that has date effectivity that includes the date of the transaction.</span></span> <span data-ttu-id="dffc0-112">אם תמחור PSA מוצא יותר ממחירון אחד שנמצא בתוקף עבור תאריך העסקה המצורף להצעת המחיר, לחוזה או ליחידה הארגונית הקשורים, אין מחיר שמהווה ברירת מחדל.</span><span class="sxs-lookup"><span data-stu-id="dffc0-112">If PSA pricing finds more than one price list that is effective for the transaction date is attached to the related quote, contract, or organizational unit, then no price is defaulted.</span></span> 
- <span data-ttu-id="dffc0-113">**זמן** - ישות זו מאחסנת את יחידת הזמן שעבורה מבוטאים מחירים, כגון תעריפים יומיים או שעתיים.</span><span class="sxs-lookup"><span data-stu-id="dffc0-113">**Time** - This entity stores the unit of time that prices are expressed for, such as daily or hourly rates.</span></span> 

<span data-ttu-id="dffc0-114">הישות 'מחירון' כוללת שלוש טבלאות קשורות המאחסנות מחירים:</span><span class="sxs-lookup"><span data-stu-id="dffc0-114">The Price list entity has three related tables that store prices:</span></span>

  - <span data-ttu-id="dffc0-115">**מחיר תפקיד** - טבלה זו מאחסנת תעריף עבור שילוב של ערכי תפקיד ויחידה ארגונית ומשמשת כדי להגדיר מחירים מבוססי-תפקיד עבור משאבי אנוש.</span><span class="sxs-lookup"><span data-stu-id="dffc0-115">**Role Price** - This table stores a rate for a combination of role and organizational unit values and is used to set up role-based prices for human resources.</span></span>
  - <span data-ttu-id="dffc0-116">**מחיר קטגוריית עסקה** - טבלה זו מאחסנת מחירים לפי קטגוריית עסקה והיא משמשת כדי להגדיר מחירי קטגוריית הוצאות.</span><span class="sxs-lookup"><span data-stu-id="dffc0-116">**Transaction Category Price** - This table stores prices by transaction category and is used to set up expense category prices.</span></span>
  - <span data-ttu-id="dffc0-117">**פריטי מחירון** - טבלה זו מאחסנת מחירים עבור מוצרי קטלוג.</span><span class="sxs-lookup"><span data-stu-id="dffc0-117">**Price List Items** - This table stores prices for catalog products.</span></span>

> ![קביעת תצורה של מחירים על-ידי שימוש במחירון](media/basic-guide-12.png)
 
<span data-ttu-id="dffc0-119">המחירון הוא כרטיס תעריף.</span><span class="sxs-lookup"><span data-stu-id="dffc0-119">The price list is a rate card.</span></span> <span data-ttu-id="dffc0-120">כרטיס תעריף הוא שילוב של הישות 'מחירון' ושורות קשורות בטבלאות 'מחיר תפקיד', 'מחיר קטגוריית עסקה' ו'פריטי מחירון'.</span><span class="sxs-lookup"><span data-stu-id="dffc0-120">A rate card is a combination of the Price List entity and related rows in the Role Price, Transaction Category Price, and Price List Items tables.</span></span>

## <a name="resource-roles"></a><span data-ttu-id="dffc0-121">תפקידי משאבים</span><span class="sxs-lookup"><span data-stu-id="dffc0-121">Resource roles</span></span>

<span data-ttu-id="dffc0-122">המונח *תפקיד משאב* מתייחס לערכת מיומנויות, יכולות והסמכות שמוכרחה להיות לאדם כדי לבצע ערכת משימות ספציפית בפרוייקט.</span><span class="sxs-lookup"><span data-stu-id="dffc0-122">The term *resource role* refers to a set of skills, competencies, and certifications that a person must have to perform a specific set of tasks on a project.</span></span>

<span data-ttu-id="dffc0-123">זמן משאבי אנוש מופיע בדרך כלל בהצעת מחיר בהתבסס על התפקיד שמשאב ממלא בפרוייקט ספציפי.</span><span class="sxs-lookup"><span data-stu-id="dffc0-123">Human resources time is usually quoted based on the role that a resource fills on a specific project.</span></span> <span data-ttu-id="dffc0-124">עבור זמן משאבי אנוש, PSA תומך בתמחיר ובחיוב המבוססים על תפקיד משאב.</span><span class="sxs-lookup"><span data-stu-id="dffc0-124">For human resource time, PSA supports costing and billing that are based on resource role.</span></span> <span data-ttu-id="dffc0-125">ניתן לתמחר זמן בכל יחידה בקבוצת היחידות **זמן**.</span><span class="sxs-lookup"><span data-stu-id="dffc0-125">Time can be priced in any unit in the **Time** unit group.</span></span>

<span data-ttu-id="dffc0-126">קבוצת היחידות **זמן** נוצרת כאשר PSA מותקן.</span><span class="sxs-lookup"><span data-stu-id="dffc0-126">The **Time** unit group is crated when PSA is installed.</span></span> <span data-ttu-id="dffc0-127">היא בעלת יחידת ברירת מחדל של **שעה**.</span><span class="sxs-lookup"><span data-stu-id="dffc0-127">It has a default unit of **Hour**.</span></span> <span data-ttu-id="dffc0-128">אין באפשרותך למחוק, לשנות את השם או לערוך את התכונות של קבוצת היחידות **זמן** או של היחידה **שעה**.</span><span class="sxs-lookup"><span data-stu-id="dffc0-128">You can't delete, rename, or edit the attributes fo teh **Time** unit group or the **Hour** unit.</span></span> <span data-ttu-id="dffc0-129">עם זאת, באפשרותך להוסיף יחידות אחרות לקבוצת היחידות **זמן**.</span><span class="sxs-lookup"><span data-stu-id="dffc0-129">However, you can add other units to the **Time** unit group.</span></span> <span data-ttu-id="dffc0-130">אם תנסה למחוק את קבוצת היחידות **זמן** או את היחידה **שעה** , ייתכן שתגרום לכשלים בלוגיקה העסקית של PSA.</span><span class="sxs-lookup"><span data-stu-id="dffc0-130">If you try to delete either the **Time** unit group or the **Hour** unit, you might cause failures in the PSA business logic.</span></span>

> ![קביעת התצורה של מחירים לפי תפקיד](media/basic-guide-13.png)
 
## <a name="transaction-categories-and-expense-categories"></a><span data-ttu-id="dffc0-132">קטגוריות עסקה וקטגוריות הוצאה</span><span class="sxs-lookup"><span data-stu-id="dffc0-132">Transaction categories and expense categories</span></span>

<span data-ttu-id="dffc0-133">הלקוח מחויב בדרך כלל עבור נסיעות והוצאות אחרות שיועצי פרוייקט צוברים.</span><span class="sxs-lookup"><span data-stu-id="dffc0-133">Travel and other expenses that project consultants incur are usually billed to the customer.</span></span> <span data-ttu-id="dffc0-134">PSA תומך בתמחור של קטגוריות הוצאות על-ידי שימוש במחירונים.</span><span class="sxs-lookup"><span data-stu-id="dffc0-134">PSA supports pricing of expense categories by using price lists.</span></span> <span data-ttu-id="dffc0-135">טיסות, מלון, והשכרת רכב הם דוגמאות לקטגוריות הוצאות.</span><span class="sxs-lookup"><span data-stu-id="dffc0-135">Airfare, hotel, and car rental are examples fo expense categories.</span></span> <span data-ttu-id="dffc0-136">כל שורת מחירון עבור הוצאות מציינת תמחור עבור קטגוריית הוצאות ספציפית.</span><span class="sxs-lookup"><span data-stu-id="dffc0-136">Each price list line for expenses specifies pricing for a specific expense category.</span></span> <span data-ttu-id="dffc0-137">עבור תמחור של קטגוריות הוצאות, PSA תומך בשלוש שיטות התמחור הבאות:</span><span class="sxs-lookup"><span data-stu-id="dffc0-137">For pricing of expense categories, PSA supports the following three pricing methods:</span></span>

- <span data-ttu-id="dffc0-138">**לפי עלות** - הלקוח מחויב בעלות ההוצאות ולא מוחל ייקור.</span><span class="sxs-lookup"><span data-stu-id="dffc0-138">**At cost** - The expense cost is billed to the customer, and no markup is applied.</span></span>
- <span data-ttu-id="dffc0-139">**אחוזי ייקור** - הלקוח מחויב באחוזים מעל העלות בפועל.</span><span class="sxs-lookup"><span data-stu-id="dffc0-139">**Markup percentage** - The percentage over the actual cost is billed to the customer.</span></span> 
- <span data-ttu-id="dffc0-140">**מחיר ליחידה** - מחיר חיוב מוגדר עבור כל יחידה בקטגוריית ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="dffc0-140">**Price per unit** - A billing price is set for each unit of the expense category.</span></span> <span data-ttu-id="dffc0-141">הסכום שבו מחויב הלקוח מחושב בהתבסס על מספר יחידות ההוצאה שהיועץ מדווח עליו.</span><span class="sxs-lookup"><span data-stu-id="dffc0-141">The amount that is billed ot the customer is calculated based on the number of expense units that the consultant reports.</span></span> <span data-ttu-id="dffc0-142">מרחק משתמש בשיטת התמחור של מחיר ליחידה.</span><span class="sxs-lookup"><span data-stu-id="dffc0-142">Mileage uses the price-per-unit pricing method.</span></span> <span data-ttu-id="dffc0-143">לדוגמה, ניתן לקבוע את תצורת קטגוריית ההוצאות של מרחק ל- 30 דולר אמריקני (USD) ליום או ל- ‎2 USD לק"מ.</span><span class="sxs-lookup"><span data-stu-id="dffc0-143">For example, the mileage expense category can be configured for 30 US dollars (USD) per day or 2 USD per mile.</span></span> <span data-ttu-id="dffc0-144">כאשר יועץ מדווח על מרחק בפרוייקט, הסכום לחיוב מחושב בהתבסס על מספר הקילומטרים שהיועץ דיווח עליהם.</span><span class="sxs-lookup"><span data-stu-id="dffc0-144">When a consultant reports mileage on a project, the amount to bill is calculated based on the number of miles that the consultant reported.</span></span>

> ![קביעת תצורה של תמחור עבור קטגוריות הוצאות](media/basic-guide-14.png)
 
## <a name="project-sales-pricing-and-overrides"></a><span data-ttu-id="dffc0-146">תמחור ועקיפות של מכירות פרוייקט</span><span class="sxs-lookup"><span data-stu-id="dffc0-146">Project sales pricing and overrides</span></span>

<span data-ttu-id="dffc0-147">עבור הצעות מחיר וחוזים של פרוייקט, למחירון פרוייקט יש תבנית עקיפת מחיר שונה מאשר מחירון מוצר.</span><span class="sxs-lookup"><span data-stu-id="dffc0-147">For project quotes and contracts, a project price list has a different price override pattern than a product price list.</span></span> <span data-ttu-id="dffc0-148">בשורה בהצעת מחיר המבוססת על קטלוג מוצרים, באפשרותך לעקוף את המחיר לתפקידים ולקטגוריות ישירות בשורה בהצעת המחיר, משום שכל שורה בהצעת מחיר מצביעה על פריט קטלוג אחד בדיוק.</span><span class="sxs-lookup"><span data-stu-id="dffc0-148">On a product catalog–based quote line, you can override the price to roles and categories directly on the quote line, because each quote line points to exactly one catalog item.</span></span> <span data-ttu-id="dffc0-149">עם זאת, בשורה בהצעת מחיר המבוססת על פרוייקט, אין באפשרותך לעקוף את המחיר לתפקידים ולקטגוריות ישירות בשורה בהצעת המחיר.</span><span class="sxs-lookup"><span data-stu-id="dffc0-149">However, on a project-based quote line, you can't override the price to roles and categories directly on the quote line.</span></span> <span data-ttu-id="dffc0-150">כדי לתמוך בשתי תבניות העקיפה הנפרדות, PSA הציג שיוך חדש של מחירון, מחירון הפרוייקט.</span><span class="sxs-lookup"><span data-stu-id="dffc0-150">To support the two distinct override patterns, PSA has introduced a new price list association, the project price list.</span></span>

> [!NOTE]
> <span data-ttu-id="dffc0-151">מומלץ שיהיה לך מחירון נפרד עבור משאבי הפרוייקט שלך ועבור פריטי הקטלוג, בשל ההבדלים באופן הפעולה בין השניים כאשר אתה עוקף תמחור.</span><span class="sxs-lookup"><span data-stu-id="dffc0-151">We recommend that you have a separate price list for your project resources and your catalog items, because of the behavior differences between the two when you override pricing.</span></span>

<span data-ttu-id="dffc0-152">לכל אחת מהיישויות הבאות יכול להיות מחירון מכירות משויך אחד או יותר עבור תמחור פרויקט:</span><span class="sxs-lookup"><span data-stu-id="dffc0-152">Each of the following entities can have one or more associated sales price lists for project pricing:</span></span>

- <span data-ttu-id="dffc0-153">לקוח (תיק לקוח)</span><span class="sxs-lookup"><span data-stu-id="dffc0-153">Customer (account)</span></span> 
- <span data-ttu-id="dffc0-154">הזדמנות</span><span class="sxs-lookup"><span data-stu-id="dffc0-154">Opportunity</span></span> 
- <span data-ttu-id="dffc0-155">הצעת מחיר</span><span class="sxs-lookup"><span data-stu-id="dffc0-155">Quote</span></span> 
- <span data-ttu-id="dffc0-156">חוזה הפרויקט</span><span class="sxs-lookup"><span data-stu-id="dffc0-156">Project Contract</span></span>

<span data-ttu-id="dffc0-157">השיוך של ישויות אלה למחירון מצוין על-ידי המחירונים של הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="dffc0-157">The association of these entities with a price list is indicated by the project price lists.</span></span> <span data-ttu-id="dffc0-158">באפשרותך לשייך מחירון אחד או יותר לישויות המכירות 'לקוח', 'הזדמנות', 'הצעת מחיר' ו'חוזה פרויקט'.</span><span class="sxs-lookup"><span data-stu-id="dffc0-158">You can associate one or more price lists with the Customer, Opportunity, Quote, and Project Contract sales entities.</span></span>

<span data-ttu-id="dffc0-159">מחירון פרויקט המהווה ברירת מחדל אינו מוזן באופן אוטומטי ברשומת לקוח.</span><span class="sxs-lookup"><span data-stu-id="dffc0-159">A default project price list isn't automatically entered on a customer record.</span></span> <span data-ttu-id="dffc0-160">עם זאת, באפשרותך לצרף באופן ידני מחירון פרויקט לרשומת הלקוח.</span><span class="sxs-lookup"><span data-stu-id="dffc0-160">However, you can manually attach a project price list to the customer record.</span></span> <span data-ttu-id="dffc0-161">עם זאת, עליך לצרף באופן ידני מחירון פרוייקט רק כאשר יש לך הסכם תמחור מותאם אישית עם הלקוח.</span><span class="sxs-lookup"><span data-stu-id="dffc0-161">Nevertheless, you should manually attach a project price list only when you have a custom pricing agreement with the customer.</span></span> 

<span data-ttu-id="dffc0-162">כאשר מחירון פרוייקט מצורף לישות מכירות, PSA מאמת את המידע הבא:</span><span class="sxs-lookup"><span data-stu-id="dffc0-162">When a project price list is attached to a sales entity, PSA validates the following information:</span></span>

- <span data-ttu-id="dffc0-163">המחירון מהווה הקשר של **מכירות**.</span><span class="sxs-lookup"><span data-stu-id="dffc0-163">The price list las a context of **Sales**.</span></span> 
- <span data-ttu-id="dffc0-164">מטבע המחירון מתאים למטבע הלקוח.</span><span class="sxs-lookup"><span data-stu-id="dffc0-164">The price list currency matches the customer currency.</span></span> 

<span data-ttu-id="dffc0-165">בחוזה של פרוייקט, PSA משתמש בסדר העדיפויות הבא כדי להגדיר באופן אוטומטי מחירונים קשורים של פרוייקט:</span><span class="sxs-lookup"><span data-stu-id="dffc0-165">On a project contract, PSA uses the following order of precedence to automatically set related project price lists:</span></span>

1. <span data-ttu-id="dffc0-166">הצעת מחיר</span><span class="sxs-lookup"><span data-stu-id="dffc0-166">Quote</span></span>
2. <span data-ttu-id="dffc0-167">הזדמנות</span><span class="sxs-lookup"><span data-stu-id="dffc0-167">Opportunity</span></span>
3. <span data-ttu-id="dffc0-168">לקוח</span><span class="sxs-lookup"><span data-stu-id="dffc0-168">Customer</span></span> 
4. <span data-ttu-id="dffc0-169">הגדרות כלליות עבור PSA</span><span class="sxs-lookup"><span data-stu-id="dffc0-169">Global settings for PSA</span></span>

<span data-ttu-id="dffc0-170">כאשר מחירון של פרוייקט מוזן כברירת מחדל, PSA מאמת שהמטבע תואם למטבע הלקוח ושהמחירונים המהווים ברירת מחדל שהוזנו הם בעלי הקשר של **מכירות**.</span><span class="sxs-lookup"><span data-stu-id="dffc0-170">When a project price list is entered by default, PSA validates that the currency matches the customer’s currency, and that the default price lists that have been entered have a context of **Sales**.</span></span>

<span data-ttu-id="dffc0-171">באפשרותך לשייך מחירוני פרויקט מרובים לישויות 'לקוח', 'הזדמנות', 'הצעת מחיר' ו'חוזה פרויקט'.</span><span class="sxs-lookup"><span data-stu-id="dffc0-171">You can associate multiple project price lists with the Customer, Opportunity, Quote, and Project Contract entities.</span></span> <span data-ttu-id="dffc0-172">יכולת זו תומכת במחירי ברירת מחדל ספציפיים לתאריך עבור חוזה פרויקט לטווח הארוך, שבו אתה עשוי לדרוש יותר ממחירון אחד עבור עדכוני מחירים המתרחשים כתוצאה מאינפלציה.</span><span class="sxs-lookup"><span data-stu-id="dffc0-172">This capability supports date-specific default prices for a long-running project contract, where you might require more than one price list to account for price updates that occur because of inflation.</span></span> <span data-ttu-id="dffc0-173">עם זאת, אם המחירונים שאתה משייך לישות 'לקוח', 'הזדמנות', 'הצעת מחיר' או 'חוזה פרויקט' הם בעלי תוקף של תאריך חופף, מחירי ברירת המחדל עשויים להיות שגויים.</span><span class="sxs-lookup"><span data-stu-id="dffc0-173">However, if the price lists that you associate with the Customer, Opportunity, Quote, or Project Contract entity have overlapping date effectivity, the default prices might be incorrect.</span></span> <span data-ttu-id="dffc0-174">לכן, עליך לוודא שמחירוני הפרוייקט בעלי תוקף של תאריך חופף אינם משויכים לישויות אלה.</span><span class="sxs-lookup"><span data-stu-id="dffc0-174">Therefore, you should make sure that project price lists that have overlapping date effectivity aren't associated with those entities.</span></span>

### <a name="deal-specific-price-overrides"></a><span data-ttu-id="dffc0-175">עקיפות מחירים ספציפיות לעסקה</span><span class="sxs-lookup"><span data-stu-id="dffc0-175">Deal-specific price overrides</span></span>

<span data-ttu-id="dffc0-176">ב- PSA, באפשרותך ליצור עקיפות ספציפיות לעסקה עבור מחירים נבחרים במחירוני פרוייקט שהוזנו כברירת מחדל בהצעת מחיר או בחוזה פרוייקט.</span><span class="sxs-lookup"><span data-stu-id="dffc0-176">In PSA, you can create deal-specific overrides for selected prices on project price lists that are entered by default on a quote or project contract.</span></span>

<span data-ttu-id="dffc0-177">כברירת מחדל, חוזה פרויקט מקבל תמיד עותק של מחירון המכירות הראשי במקום קישור ישיר אליו.</span><span class="sxs-lookup"><span data-stu-id="dffc0-177">By default, a project contract always gets a copy of the master sales price list instead of a direct link to it.</span></span> <span data-ttu-id="dffc0-178">אופן פעולה זה מסייע להבטיח שההסכמים על מחירים שנוצרו עם לקוח עבור מסמך עבודה (SOW) אינם משתנים אם המחירון הראשי משתנה.</span><span class="sxs-lookup"><span data-stu-id="dffc0-178">This behavior helps guarantee that price agreements that are made iwth a customer for a statement of work (SOW) don't change if the master price list is changed.</span></span>

<span data-ttu-id="dffc0-179">עם זאת, בהצעת מחיר, באפשרותך להשתמש במחירון ראשי.</span><span class="sxs-lookup"><span data-stu-id="dffc0-179">However, on a quote, you can use a master price list.</span></span> <span data-ttu-id="dffc0-180">לחלופין, באפשרותך להעתיק מחירון ראשי ולערוך אותו כדי ליצור מחירון מותאם אישית שיחול רק על הצעת מחיר זו.</span><span class="sxs-lookup"><span data-stu-id="dffc0-180">Alternatively, you can copy a master price list and edit it to create a custom price list that applies only to that quote.</span></span> <span data-ttu-id="dffc0-181">כדי ליצור מחירון חדש הספציפי להצעת מחיר, בדף **הצעת מחיר** , בחר **יצירת תמחור מותאם אישית**.</span><span class="sxs-lookup"><span data-stu-id="dffc0-181">To create a new price list that is specific to a quote, on the **Quote** page, select **Create custom pricing**.</span></span> <span data-ttu-id="dffc0-182">באפשרותך לגשת למחירון הפרויקט הספציפי לעסקה רק מהצעת המחיר.</span><span class="sxs-lookup"><span data-stu-id="dffc0-182">You can access the deal-specific project price list only from the quote.</span></span> 

<span data-ttu-id="dffc0-183">בעת יצירת מחירון פרויקט מותאם אישית, רק רכיבי הפרויקט של המחירון יועתקו.</span><span class="sxs-lookup"><span data-stu-id="dffc0-183">When you create a custom project price list, only the project components of the price list are copied.</span></span> <span data-ttu-id="dffc0-184">במילים אחרות, מחירון חדש נוצר כעותק של מחירון הפרוייקט הקיים המצורף בהצעת המחיר, ולמחירון חדש זה יש רק מחירי תפקידים ומחירי קטגוריית עסקה קשורים.</span><span class="sxs-lookup"><span data-stu-id="dffc0-184">In other words, a new price list created as a copy of the existing project price list that is attached on the quote, and this new price list has only related role prices and transaction category prices.</span></span>

> ![הצגה וקביעת תצורה של תמחור מותאם אישית עבור חוזה פרוייקט](media/basic-guide-15.png)
  
## <a name="tracking-costs"></a><span data-ttu-id="dffc0-186">מעקב אחר עלויות</span><span class="sxs-lookup"><span data-stu-id="dffc0-186">Tracking costs</span></span>

<span data-ttu-id="dffc0-187">PSA עוקב אחר עלויות עבור השימוש בזמן משאבי אנוש בפרוייקט.</span><span class="sxs-lookup"><span data-stu-id="dffc0-187">PSA tracks costs for the use of human resource time on projects.</span></span> <span data-ttu-id="dffc0-188">הוא עוקב גם אחר עלויות עבור הוצאות אחרות שמצטברות במהלך הפרוייקט, כגון הוצאות נסיעות.</span><span class="sxs-lookup"><span data-stu-id="dffc0-188">It also tracks costs for other expenses that are incurrred during hte project, such as travel expenses.</span></span>

<span data-ttu-id="dffc0-189">בדומה לתעריפי חיוב, תעריפי עלות עבור משאבי אנוש מוגדרים גם באמצעות מחירונים.</span><span class="sxs-lookup"><span data-stu-id="dffc0-189">Like bill rates, cost rates for human resources are also set up using price lists.</span></span> <span data-ttu-id="dffc0-190">להלן ההבדלים העיקריים באופן הפעולה של מחירון העלות ומחירון המכירות:</span><span class="sxs-lookup"><span data-stu-id="dffc0-190">Here are the main differences in the behavior of the cost price list and sales price list:</span></span>

- <span data-ttu-id="dffc0-191">לא ניתן לעקוף את תעריף העלות של משאב בפרויקט, חוזה או הצעת מחיר ספציפיים.</span><span class="sxs-lookup"><span data-stu-id="dffc0-191">The cost rate of a resource can’t be overridden on a specific project, contract, or quote.</span></span> <span data-ttu-id="dffc0-192">עם זאת, ניתן לעקוף תעריפי חיוב על בסיס לפי עסקה אם מתבצעים שינויים הספציפיים לאופי העסקה.</span><span class="sxs-lookup"><span data-stu-id="dffc0-192">However, bill rates can be overridden on a per-deal basis if changes are made that are specific to the nature of the deal.</span></span> 

- <span data-ttu-id="dffc0-193">הסדר הבא משמש כדי לפענח מחירון עלות:</span><span class="sxs-lookup"><span data-stu-id="dffc0-193">The following order is used to resolve a cost price list:</span></span>

    1. <span data-ttu-id="dffc0-194">מחירון העלות המצורף ליחידה הארגונית.</span><span class="sxs-lookup"><span data-stu-id="dffc0-194">The cost price list that is attached to the organizational unit.</span></span>
    2. <span data-ttu-id="dffc0-195">מחירון העלות המצורף לפרמטרים של Project Service.</span><span class="sxs-lookup"><span data-stu-id="dffc0-195">The cost price list that is attached to the project service parameters.</span></span> <span data-ttu-id="dffc0-196">מכיוון שניתן לצרף מחירוני עלות במטבעות רבים ושונים לפרמטרים של Project Service‏, PSA יוצר התאמת מטבעות בין המטבע של היחידה הארגונית של החוזה של הפרוייקט, החוזה או הצעת המחיר, לבין מטבע מחירון העלות.</span><span class="sxs-lookup"><span data-stu-id="dffc0-196">Because cost price lists in many different currencies can be attached to project service parameters, PSA does a currency match between the currency of the contracting organizational unit of the project, contract, or quote, and the currency of the cost price list.</span></span>
    3. <span data-ttu-id="dffc0-197">עבור הוצאות, שיטות התמחור לפי עלות וייקור מעל לעלות אינן חלות על מחירוני עלות.</span><span class="sxs-lookup"><span data-stu-id="dffc0-197">For expenses, the at-cost and markup-over-cost pricing methods don’t apply to cost price lists.</span></span> <span data-ttu-id="dffc0-198">גם אם שיטות תמחור אלה משמשות בשורות מחירוני עלות כדי להגדיר עלויות קטגוריית עסקה, המערכת מתעלמת מהן ולא מוזן מחיר עלות של ברירת מחדל.</span><span class="sxs-lookup"><span data-stu-id="dffc0-198">Even if these pricing methods are used on cost price list lines to set up transaction category costs, the system ignores them, and no default cost price is entered.</span></span>