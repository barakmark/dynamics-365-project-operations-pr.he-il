---
title: פרמטרים של ניהול הוצאות
description: הפרמטרים הבאים שולטים באופן הפעולה בניהול הוצאות.
author: KimANelson
manager: AnnBe
ms.date: 01/12/2018
ms.topic: article
ms.prod: ''
ms.service: dynamics-ax-applications
ms.technology: ''
ms.search.form: TrvParameters
audience: Application User
ms.reviewer: roschlom
ms.search.scope: Core, Operations
ms.search.region: Global
ms.author: suvaidya
ms.search.validFrom: 2017-06-30
ms.dyn365.ops.version: July 2017 update
ms.openlocfilehash: af49187a3ad530919376fbfdb5a0fbc288b7c28c
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077352"
---
# <a name="expense-management-parameters"></a><span data-ttu-id="455c8-103">פרמטרים של ניהול הוצאות</span><span class="sxs-lookup"><span data-stu-id="455c8-103">Expense management parameters</span></span>

[!include [banner](../includes/banner.md)]

-----------------------------

<span data-ttu-id="455c8-104">הפרמטרים שולטים באופן הפעולה הכללי בניהול הוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-104">The parameters control the general behavior in Expense management.</span></span>

### <a name="general"></a><span data-ttu-id="455c8-105">כללי</span><span class="sxs-lookup"><span data-stu-id="455c8-105">General</span></span>

| <span data-ttu-id="455c8-106">**שדה**</span><span class="sxs-lookup"><span data-stu-id="455c8-106">**Field**</span></span>                                                | <span data-ttu-id="455c8-107">**תיאור**</span><span class="sxs-lookup"><span data-stu-id="455c8-107">**Description**</span></span>                                                 |
|----------------------------------------------------------|---------------------------------------------------------------------|
| <span data-ttu-id="455c8-108">**תעריף רגיל עבור מרחק**</span><span class="sxs-lookup"><span data-stu-id="455c8-108">**Standard rate of mileage**</span></span>                             | <span data-ttu-id="455c8-109">הזן את שיעור ההחזר עבור הוצאות מרחק.</span><span class="sxs-lookup"><span data-stu-id="455c8-109">Enter the reimbursement rate for mileage expenses.</span></span> <span data-ttu-id="455c8-110">התעריף יוכפל במרחק שהוזן עבור ההוצאה לצורך חישוב הסכום המוחזר עבור הוצאות הנסיעה.</span><span class="sxs-lookup"><span data-stu-id="455c8-110">The rate will be multiplied by the mileage entered on the expense to calculate the amount reimbursed for the travel expense.</span></span>                       |
|<span data-ttu-id="455c8-111">**הוצאות אישיות משולמות על ידי**</span><span class="sxs-lookup"><span data-stu-id="455c8-111">**Personal expenses paid by**</span></span>                             | <span data-ttu-id="455c8-112">בחר באדם האחראי לתשלום סכומי עסקאות בכרטיס אשראי המסווגים כאישיים.</span><span class="sxs-lookup"><span data-stu-id="455c8-112">Select who is responsible for paying any credit card transaction amounts categorized as personal.</span></span>                                                                                                     |
|<span data-ttu-id="455c8-113">**הצגת דוח הוצאות שלם להסתעפות לאחור**</span><span class="sxs-lookup"><span data-stu-id="455c8-113">**Display entire expense report on drillback**</span></span>               | <span data-ttu-id="455c8-114">בחר באפשרות זו כדי להציג את כל ההוצאות עבור דוח הוצאות כאשר מוצגים פרטי המסמך המקורי עבור שובר ספציפי שנוצר בעת רישום דוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-114">Select this option to display all expenses for an expense report when viewing the details of the original document for a specific voucher that was generated when the expense report was posted.</span></span>              |
|<span data-ttu-id="455c8-115">**מתן הרשאה מראש לנסיעה הוא חובה**</span><span class="sxs-lookup"><span data-stu-id="455c8-115">**Pre-authorization of travel is mandatory**</span></span>                 | <span data-ttu-id="455c8-116">בחר באפשרות זו כדי לדרוש כי דרישת נסיעה תוגש ותאושר לפני שעובד יכול להגיש דוח הוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-116">Select this option to require that a travel requisition be submitted and approved before an employee can submit an expense report.</span></span>                                                                    |
|<span data-ttu-id="455c8-117">**אפשר עריכה של הפצות לפני הרישום**</span><span class="sxs-lookup"><span data-stu-id="455c8-117">**Allow editing of distributions before posting**</span></span>            | <span data-ttu-id="455c8-118">בחר האם ניתן יהיה לערוך את ההפצות של דוח הוצאות לפני רישומו.</span><span class="sxs-lookup"><span data-stu-id="455c8-118">Select whether the distributions of an expense report can be edited prior to posting.</span></span>                                                                                                                 |
|<span data-ttu-id="455c8-119">**הערך את מדיניות ניהול ההוצאות**</span><span class="sxs-lookup"><span data-stu-id="455c8-119">**Evaluate expense management policies**</span></span>                     | <span data-ttu-id="455c8-120">בחר מתי יש לבצע הערכה להוצאות כדי לקבוע אם מדיניות הוצאות הופרה.</span><span class="sxs-lookup"><span data-stu-id="455c8-120">Select when expenses are evaluated to determine if an expense policy has been violated.</span></span> <span data-ttu-id="455c8-121">ניתן לבדוק הוצאות בגין הפרות כאשר ערך ההוצאה מוזנת ונשמרת, או כאשר ההוצאה מוגשת לאישור.</span><span class="sxs-lookup"><span data-stu-id="455c8-121">Expenses can be checked for violations when the expense entry is entered and saved or when the expense is submitted for approval.</span></span> <span data-ttu-id="455c8-122">כללי המדיניות לקבלות הנדרשות יבדקו לאחר שמירת שורת ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-122">The policy rules for receipts required will be checked when the expense line is saved.</span></span>                   |
|<span data-ttu-id="455c8-123">**אפשר שורות הוצאות בין-חברתיות**</span><span class="sxs-lookup"><span data-stu-id="455c8-123">**Allow intercompany expense lines**</span></span>                         | <span data-ttu-id="455c8-124">בחר אם לאפשר הזנת הוצאות עבור ישויות משפטיות אחרות בדוח הוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-124">Select whether to allow entry of expenses for other legal entities within an expense report.</span></span>                                                                                                          |
|<span data-ttu-id="455c8-125">**אפשר עריכת שער החליפין של הוצאות כרטיסי אשראי**</span><span class="sxs-lookup"><span data-stu-id="455c8-125">**Allow editing the exchange rate for credit card expenses**</span></span> | <span data-ttu-id="455c8-126">בחר באפשרות זו כדי לאפשר למשתמש לערוך את שער החליפין עבור הוצאות בכרטיסי אשראי שיובאו.</span><span class="sxs-lookup"><span data-stu-id="455c8-126">Select this option to allow the user to edit the exchange rate for imported credit card expenses.</span></span>                                                                        |
|<span data-ttu-id="455c8-127">**שדות היררכיה מרובי רמות להצגה**</span><span class="sxs-lookup"><span data-stu-id="455c8-127">**Multi-level hierarchy fields to display**</span></span>                  | <span data-ttu-id="455c8-128">בחר אלו שדות של מאשר יוצגו כאשר סוג הקצאת זרימת העבודה של דוח ההוצאות מוגדר כהיררכיה, והבחירה היררכיה מוגדרת להשתמש בהיררכיית אישור מרובה רמות להוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-128">Select which approver fields to display when the expense report workflow assignment type is set to be hierarchy and the hierarchy selection is set to use the Expense multi-level approval hierarchy.</span></span> <span data-ttu-id="455c8-129">כאשר נעשה שימוש בהיררכיית אישור מרובת רמות עבור זרימת עבודה, השדות שנבחרו יוצגו בדוח ההוצאות וניתן יהיה לערוך אותם.</span><span class="sxs-lookup"><span data-stu-id="455c8-129">When the multi-level approval hierarchy is used for workflow, the selected fields will be displayed and editable in the Expense report.</span></span> |
|<span data-ttu-id="455c8-130">**הזן מספר כרטיס אשראי של העובד (עדכון יולי 2017)**</span><span class="sxs-lookup"><span data-stu-id="455c8-130">**Enter employee credit card number (July 2017 update)**</span></span>     | <span data-ttu-id="455c8-131">בחר אם ניתן יהיה להזין ולשמור מספר בן 15 או 16 תווים בשדה **מזהה כרטיס** בדף **כרטיסי אשראי** עובר עובד.</span><span class="sxs-lookup"><span data-stu-id="455c8-131">Select whether a 15-or 16-character number can be entered and saved in the **Card ID** field in the **Credit cards** page for an employee.</span></span>                                                                          |

### <a name="financial"></a><span data-ttu-id="455c8-132">בנקאות ושירותים פיננסיים</span><span class="sxs-lookup"><span data-stu-id="455c8-132">Financial</span></span>

| <span data-ttu-id="455c8-133">**שדה**</span><span class="sxs-lookup"><span data-stu-id="455c8-133">**Field**</span></span>                                                            | <span data-ttu-id="455c8-134">**תיאור**</span><span class="sxs-lookup"><span data-stu-id="455c8-134">**Description**</span></span>     |
|----------------------------------------------------------------------|------------------------------------|
|<span data-ttu-id="455c8-135">**שם היומן היומי של הספר הראשי**</span><span class="sxs-lookup"><span data-stu-id="455c8-135">**Ledger daily journal name**</span></span>                                         | <span data-ttu-id="455c8-136">בחר את שם יומן הספר הראשי שבו נרשמים דוחות הוצאות שאושרו.</span><span class="sxs-lookup"><span data-stu-id="455c8-136">Select the name of the ledger journal that approved expense reports are posted to.</span></span>            |
|<span data-ttu-id="455c8-137">**אפשר החזר מס מהוצאות**</span><span class="sxs-lookup"><span data-stu-id="455c8-137">**Enable tax recovery from expenses**</span></span>                                  | <span data-ttu-id="455c8-138">בחר באפשרות זו כדי לאפשר החזר מס על הוצאות בגין הוצאות זכאיות.</span><span class="sxs-lookup"><span data-stu-id="455c8-138">Select this option to enable expense tax recovery for eligible expenses.</span></span> <span data-ttu-id="455c8-139">לא ניתן להפוך אפשרות זו לזמינה אם מופעלים כללי מס המכירות והשימוש של ארה"ב.</span><span class="sxs-lookup"><span data-stu-id="455c8-139">This option cannot be enabled if US sales tax and use tax rules are enabled.</span></span>      |
|<span data-ttu-id="455c8-140">**רישום מקדמות במזומן באופן מיידי**</span><span class="sxs-lookup"><span data-stu-id="455c8-140">**Post cash advances immediately**</span></span>                                     | <span data-ttu-id="455c8-141">בחר באפשרות זו כדי לרשום מקדמה במזומן שאושרה לאחר השלמת תהליך התשלום וההעברה.</span><span class="sxs-lookup"><span data-stu-id="455c8-141">Select this option to post an approved cash advance when the process to Pay and transfer is completed.</span></span> <span data-ttu-id="455c8-142">אם אפשרות זו לא נבחרה, תהליך התשלום וההעברה יוצר יומן כללי שלא נרשם.</span><span class="sxs-lookup"><span data-stu-id="455c8-142">If this option is not selected, the Pay and transfer process will generate an unposted general journal.</span></span> |
|<span data-ttu-id="455c8-143">**תאריך חשבונאות נכון במהלך הרישום**</span><span class="sxs-lookup"><span data-stu-id="455c8-143">**Correct accounting date during posting**</span></span>                             | <span data-ttu-id="455c8-144">בחר באפשרות זו כדי לעדכן את תאריך החשבונאות שבו נרשמות הוצאות, אם התקופה הנוכחית בהמתנה או סגורה.</span><span class="sxs-lookup"><span data-stu-id="455c8-144">Select this option to update the accounting date when posting expenses if the current period is on hold or closed.</span></span> <span data-ttu-id="455c8-145">תאריך החשבונאות ייקבע לתקופה הפתוחה הבאה.</span><span class="sxs-lookup"><span data-stu-id="455c8-145">The accounting date will be set to the next open period.</span></span>   |
|<span data-ttu-id="455c8-146">**אפשר קיבוץ עסקאות על בסיס חשבון קיזוז שצוין בשיטת התשלום**</span><span class="sxs-lookup"><span data-stu-id="455c8-146">**Allow grouping of transactions based on offset account specified in payment method**</span></span>      | <span data-ttu-id="455c8-147">בחר באפשרות זו כדי לסכם את עסקאות ההוצאות עבור דוח הוצאות, בהתבסס על חשבון הקיזוז שצוין בשיטת התשלום עבור ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-147">Select this option to summarize the expense transactions for an expense report, based on the offset account specified in the payment method for the expenses.</span></span>   
|<span data-ttu-id="455c8-148">**מס כלול**</span><span class="sxs-lookup"><span data-stu-id="455c8-148">**Tax included**</span></span>                                                   | <span data-ttu-id="455c8-149">בחר באפשרות זו כדי לכלול מס מכירה בסכום ההוצאות כברירת מחדל.</span><span class="sxs-lookup"><span data-stu-id="455c8-149">Select this option to include sales tax in the expense amount by default.</span></span>             |
|<span data-ttu-id="455c8-150">**שחרר התחייבויות בסגירת דרישות נסיעה**</span><span class="sxs-lookup"><span data-stu-id="455c8-150">**Release encumbrances on closing travel requisitions**</span></span>            | <span data-ttu-id="455c8-151">בחר באפשרות זו כדי לשחרר כספים משועבדים בעת סגירת דרישת הנסיעות שאושרה.</span><span class="sxs-lookup"><span data-stu-id="455c8-151">Select this option to release encumbered funds when an approved travel requisition is closed.</span></span>                                                                                   |
|<span data-ttu-id="455c8-152">**אפשר הגשת דרישת נסיעות בחריגה מהתקציב לפנקס התקציב ותקציב הפרויקט**</span><span class="sxs-lookup"><span data-stu-id="455c8-152">**Allow travel requisition submit on budget overrun for budget register and project budget**</span></span> | <span data-ttu-id="455c8-153">בחר באפשרות זו כדי לאפשר לעובדים להגיש בקשות נסיעה לאישור, שחורגים מהתקציב המותר שנקבע בפנקס התקציבים או מהתקציב שהותר לפרויקט.</span><span class="sxs-lookup"><span data-stu-id="455c8-153">Select this option to allow employees to submit travel requisitions for approval that exceed either the allowed budget that is set in the budget register or the allowed budget for a project.</span></span>            |
|<span data-ttu-id="455c8-154">**אפשר הגשת דרישת נסיעות בחריגה מהתקציב עבור פנקס התקציבים ותקציב הפרויקט**</span><span class="sxs-lookup"><span data-stu-id="455c8-154">**Allow expense report submit on budget overrun for budget register and project budget**</span></span>    | <span data-ttu-id="455c8-155">בחר באפשרות זו כדי לאפשר לעובדים להגיש דוחות הוצאות לאישור, שחורגים מהתקציב המותר שנקבע בפנקס התקציבים או מהתקציב שהותר לפרויקט.</span><span class="sxs-lookup"><span data-stu-id="455c8-155">Select this option to allow employees to submit expense reports for approval that exceed either the allowed budget that is set in the budget register or the allowed budget for a project.</span></span>                |
|<span data-ttu-id="455c8-156">**אפשר אישור דוח הוצאות בחריגה מהתקציב עבור פנקס התקציבים בלבד**</span><span class="sxs-lookup"><span data-stu-id="455c8-156">**Allow expense report approval on budget overrun for budget register only**</span></span>                | <span data-ttu-id="455c8-157">בחר באפשרות זו כדי לאפשר למאשרים לאשר דוחות הוצאות החורגים מהתקציב המותר שנקבע בפנקס התקציבים.</span><span class="sxs-lookup"><span data-stu-id="455c8-157">Select this option to allow approvers to approve expense reports that exceed the allowed budget that is set in the budget register.</span></span>                                                                       |

### <a name="per-diem"></a><span data-ttu-id="455c8-158">אש"ל</span><span class="sxs-lookup"><span data-stu-id="455c8-158">Per diem</span></span>

| <span data-ttu-id="455c8-159">**שדה**</span><span class="sxs-lookup"><span data-stu-id="455c8-159">**Field**</span></span>                             | <span data-ttu-id="455c8-160">**תיאור**</span><span class="sxs-lookup"><span data-stu-id="455c8-160">**Description**</span></span>             |
|---------------------------------------|--------------------------------------------------------------------------------------|
|<span data-ttu-id="455c8-161">**שעות מינימום לאש"ל**</span><span class="sxs-lookup"><span data-stu-id="455c8-161">**Minimum hours for per diem**</span></span>           | <span data-ttu-id="455c8-162">הזן את מספר השעות המינימלי המוגדר כברירת מחדל שעובד חייב לעבוד ביום כדי להיות זכאי לקבלת דמי אש"ל עבור הוצאות הקשורות לנסיעה.</span><span class="sxs-lookup"><span data-stu-id="455c8-162">Enter the default minimum number of hours that an employee must work in a day to be eligible to receive a per diem for travel-related expenses.</span></span>  <span data-ttu-id="455c8-163">ערך זה משמש כערך ברירת מחדל רק עבור השדה שעות מינימום ברמות של תעריפי אש"ל.</span><span class="sxs-lookup"><span data-stu-id="455c8-163">This value is only used as a default value for the Minimum hours field on per diem rate tiers.</span></span>                                                                                      |
|<span data-ttu-id="455c8-164">**אחוז ארוחות**</span><span class="sxs-lookup"><span data-stu-id="455c8-164">**Meal percent**</span></span>                          | <span data-ttu-id="455c8-165">הזן את אחוז ברירת המחדל של דמי האש"ל עבור ארוחות, המשמש ליום הראשון והאחרון של הוצאה הקשורה לנסיעה, כאשר השדה **חישוב הפחתת הארוחה לפי** מוגדר ל **סוג הארוחה ליום** אוֹ ל **מספר הארוחות ביום**.</span><span class="sxs-lookup"><span data-stu-id="455c8-165">Enter the default percentage of the per diem for meals that is used on the first and last days of the travel-related expense when the **Calculate meal reduction by** field is set to either **Meal type per day** or **Number of meals per day**.</span></span> <span data-ttu-id="455c8-166">יום העבודה ביום הראשון והאחרון עשוי להיות קצר יותר מיום העבודה הרגיל.</span><span class="sxs-lookup"><span data-stu-id="455c8-166">The work day on the first and last days may be shorter than a standard work day.</span></span> <span data-ttu-id="455c8-167">לפיכך, סכום האש"ל בימים אלו עשוי להיות שונה מהסכום הרגיל.</span><span class="sxs-lookup"><span data-stu-id="455c8-167">Therefore, the amount of the per diem on these days may differ from the standard amount.</span></span> <span data-ttu-id="455c8-168">אם האחוז מוגדר ל-0 (אפס), הניכויים ליום הראשון והאחרון יהיו 0.00.</span><span class="sxs-lookup"><span data-stu-id="455c8-168">If the percent is set to 0, then the first and last day deductions will be 0.00.</span></span> |
|<span data-ttu-id="455c8-169">**אחוז המלונות**</span><span class="sxs-lookup"><span data-stu-id="455c8-169">**Hotel percent**</span></span>                        | <span data-ttu-id="455c8-170">הזן את אחוז ברירת המחדל של האש"ל המשמש למלונות ביום הראשון והאחרון מההוצאה הקשורה לנסיעה.</span><span class="sxs-lookup"><span data-stu-id="455c8-170">Enter the default percentage of the per diem for hotels that is used on the first and last days of the travel-related expense.</span></span> <span data-ttu-id="455c8-171">יום העבודה ביום הראשון והאחרון עשוי להיות קצר יותר מיום העבודה הרגיל.</span><span class="sxs-lookup"><span data-stu-id="455c8-171">The work day on the first and last days may be shorter than a standard work day.</span></span> <span data-ttu-id="455c8-172">לפיכך, סכום האש"ל בימים אלו עשוי להיות שונה מהסכום הרגיל.</span><span class="sxs-lookup"><span data-stu-id="455c8-172">Therefore, the amount of the per diem on these days may differ from the standard amount.</span></span> <span data-ttu-id="455c8-173">אם האחוז מוגדר ל-0 (אפס), הניכויים ליום הראשון והאחרון יהיו 0.00.</span><span class="sxs-lookup"><span data-stu-id="455c8-173">If the percent is set to 0, then the first and last day deductions will be 0.00.</span></span>                                              |
|<span data-ttu-id="455c8-174">**אחוזים אחרים**</span><span class="sxs-lookup"><span data-stu-id="455c8-174">**Other percent**</span></span>                        | <span data-ttu-id="455c8-175">הזן את אחוז ברירת המחדל של האש"ל המשמש להוצאות שונות ביום הראשון והאחרון מההוצאה הקשורה לנסיעה.</span><span class="sxs-lookup"><span data-stu-id="455c8-175">Enter the default percentage of the per diem for miscellaneous expenses that is used on the first and last days of the travel-related expense.</span></span> <span data-ttu-id="455c8-176">יום העבודה ביום הראשון והאחרון עשוי להיות קצר יותר מיום העבודה הרגיל.</span><span class="sxs-lookup"><span data-stu-id="455c8-176">The work day on the first and last days may be shorter than a standard work day.</span></span> <span data-ttu-id="455c8-177">לפיכך, סכום האש"ל בימים אלו עשוי להיות שונה מהסכום הרגיל.</span><span class="sxs-lookup"><span data-stu-id="455c8-177">Therefore, the amount of the per diem on these days may differ from the standard amount.</span></span> <span data-ttu-id="455c8-178">אם האחוז מוגדר ל-0 (אפס), הניכויים ליום הראשון והאחרון יהיו 0.00.</span><span class="sxs-lookup"><span data-stu-id="455c8-178">If the percent is set to 0, then the first and last day deductions will be 0.00.</span></span>                                                                                                     |
|<span data-ttu-id="455c8-179">**הפחתת אחוזים לארוחת הבוקר**</span><span class="sxs-lookup"><span data-stu-id="455c8-179">**Reduction in percentage for breakfast**</span></span> | <span data-ttu-id="455c8-180">הזן את הסכום הפחתה מהאש"ל לארוחת הבוקר.</span><span class="sxs-lookup"><span data-stu-id="455c8-180">Enter the amount that the per diem is reduced for breakfast.</span></span> <span data-ttu-id="455c8-181">לדוגמה, אם עובד מקבל ארוחת בוקר בחינם, יתכן שתרצה להפחית את סכום האש"ל ב-10 אחוזים.</span><span class="sxs-lookup"><span data-stu-id="455c8-181">For example, if an employee receives a complimentary breakfast, you may want to reduce the amount of the per diem by 10 percent.</span></span>                               |
|<span data-ttu-id="455c8-182">**הפחתת אחוזים לארוחת צהריים**</span><span class="sxs-lookup"><span data-stu-id="455c8-182">**Reduction in percentage for lunch**</span></span>    | <span data-ttu-id="455c8-183">הזן את הסכום הפחתה מהאש"ל לארוחת צהריים.</span><span class="sxs-lookup"><span data-stu-id="455c8-183">Enter the amount that the per diem is reduced for lunch.</span></span> <span data-ttu-id="455c8-184">לדוגמה, אם עובד מקבל ארוחת צהריים בחינם, יתכן שתרצה להפחית את סכום האש"ל ב-15 אחוזים.</span><span class="sxs-lookup"><span data-stu-id="455c8-184">For example, if an employee receives a complimentary lunch, you may want to reduce the amount of the per diem by 15 percent.</span></span>                                       |
|<span data-ttu-id="455c8-185">**הפחתת אחוזים לארוחת ערב**</span><span class="sxs-lookup"><span data-stu-id="455c8-185">**Reduction in percentage for dinner**</span></span>   | <span data-ttu-id="455c8-186">הזן את הסכום הפחתה מהאש"ל לארוחת ערב.</span><span class="sxs-lookup"><span data-stu-id="455c8-186">Enter the amount that the per diem is reduced for dinner.</span></span> <span data-ttu-id="455c8-187">לדוגמה, אם עובד מקבל ארוחת ערב בחינם, יתכן שתרצה להפחית את סכום האש"ל ב-25 אחוזים.</span><span class="sxs-lookup"><span data-stu-id="455c8-187">For example, if an employee receives a complimentary dinner, you may want to reduce the amount of the per diem by 25 percent.</span></span>                                     |
|<span data-ttu-id="455c8-188">**חישוב הפחתת הארוחה לפי**</span><span class="sxs-lookup"><span data-stu-id="455c8-188">**Calculate meal reduction by**</span></span>         | <span data-ttu-id="455c8-189">בחר כיצד על המערכת לחשב את ההפחה מהארוחות באש"ל, על-ידי בחירה אם ההפחתה תתבסס על סוג הארוחה לנסיעה או ליום, או אם ההפחתה מתבססת על מספר הארוחות המותרות ליום.</span><span class="sxs-lookup"><span data-stu-id="455c8-189">Select how the system should calculate the per diem meal reduction by selecting if the reduction is based on the meal type per trip or per day, or if the reduction is based on the number of meals allowed per day.</span></span>|
|<span data-ttu-id="455c8-190">**עיגול דמי אש"ל**</span><span class="sxs-lookup"><span data-stu-id="455c8-190">**Per diem rounding**</span></span>                  | <span data-ttu-id="455c8-191">בחר את סוג העיגול המשמש להוצאות אש"ל.</span><span class="sxs-lookup"><span data-stu-id="455c8-191">Select the type of rounding that is used for per diem expenses.</span></span> <span data-ttu-id="455c8-192">אם בוחרים בעיגול רגיל, כל הוצאת אש"ל עם סכום של 0.50 מעוגלת ל-1.00, וכל הוצאה לכל יום עם סכום הנמוך מ-0.50 מעוגלת כלפי מטה ל-0.00.</span><span class="sxs-lookup"><span data-stu-id="455c8-192">If you select normal rounding, any per diem expense that has an amount of 0.50 is rounded up to 1.00, and any per diem expense that has an amount that is less than 0.50 is rounded down to 0.00.</span></span>                                                                                              |
|<span data-ttu-id="455c8-193">**בסס את חישוב האש"ל על**</span><span class="sxs-lookup"><span data-stu-id="455c8-193">**Base per diem calculation on**</span></span>         | <span data-ttu-id="455c8-194">בחר אם סכום אש"ל מבוסס על יום קלנדרי או על תקופה של 24 שעות.</span><span class="sxs-lookup"><span data-stu-id="455c8-194">Select whether a per diem amount is based on a calendar day or a 24-hour period.</span></span>       |

### <a name="fax-cover-pages"></a><span data-ttu-id="455c8-195">עמודי שער של פקס</span><span class="sxs-lookup"><span data-stu-id="455c8-195">Fax cover pages</span></span>

| <span data-ttu-id="455c8-196">**שדה**</span><span class="sxs-lookup"><span data-stu-id="455c8-196">**Field**</span></span>                      | <span data-ttu-id="455c8-197">**תיאור**</span><span class="sxs-lookup"><span data-stu-id="455c8-197">**Description**</span></span>            |
|--------------------------------|-----------------------------------------------------------------------------|
| <span data-ttu-id="455c8-198">**הוראות**</span><span class="sxs-lookup"><span data-stu-id="455c8-198">**Instructions**</span></span>                   | <span data-ttu-id="455c8-199">הזן את ההוראות שעל העובדים לבצע כאשר הם יוצרים עמוד שער של פקס המשמש למשלוח קבלות שקשורות לדוח הוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-199">Enter the instructions that employees must follow when they create a cover page for a fax that is used to send receipts that are related to an expense report.</span></span> <span data-ttu-id="455c8-200">לחץ על הלחצן **תרגומים** להזנת טקסט ספציפי לשפה שיוצג בהתבסס על שפת המשתמש.</span><span class="sxs-lookup"><span data-stu-id="455c8-200">Click the **Translations** button to enter language-specific text that will be displayed based on the user language.</span></span> |
|<span data-ttu-id="455c8-201">**מזהה משתמש (פרטי ברקוד)**</span><span class="sxs-lookup"><span data-stu-id="455c8-201">**User ID (Bar code information)**</span></span> | <span data-ttu-id="455c8-202">בחר באפשרות זו כדי לאחסן את המזהה הייחודי של העובד בברקוד המופיע בעמוד השער של הפקס.</span><span class="sxs-lookup"><span data-stu-id="455c8-202">Select this option to store an employee’s unique identifier in the bar code that is used on the cover page of the fax.</span></span>                 |
|<span data-ttu-id="455c8-203">**ברקוד**</span><span class="sxs-lookup"><span data-stu-id="455c8-203">**Bar code**</span></span>                      | <span data-ttu-id="455c8-204">בחר את הברקוד המשמש בעמוד השער של הפקס.</span><span class="sxs-lookup"><span data-stu-id="455c8-204">Select the bar code that is used on the cover page of the fax.</span></span> <span data-ttu-id="455c8-205">ברקודים 39 ו-128 נתמכים עם ניהול הוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-205">Bar codes 39 and 128 are supported with Expense management.</span></span>               |

### <a name="anti-corruption"></a><span data-ttu-id="455c8-206">נגד שחיתות</span><span class="sxs-lookup"><span data-stu-id="455c8-206">Anti-corruption</span></span>

|                 <span data-ttu-id="455c8-207"><strong>שדה</strong></span><span class="sxs-lookup"><span data-stu-id="455c8-207"><strong>Field</strong></span></span>                 |                                                                                                                                                                                            <span data-ttu-id="455c8-208"><strong>תיאור</strong></span><span class="sxs-lookup"><span data-stu-id="455c8-208"><strong>Description</strong></span></span>                                                                                                                                                                                             |
|--------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  <span data-ttu-id="455c8-209"><strong>הצגת ההצהרה נגד שחיתות</strong></span><span class="sxs-lookup"><span data-stu-id="455c8-209"><strong>Display anti-corruption attestation</strong></span></span>  | <span data-ttu-id="455c8-210">בחר באפשרות זו כדי להציג את הטקסט נגד שחיתות בעת יצירת דוח הוצאות חדש.</span><span class="sxs-lookup"><span data-stu-id="455c8-210">Select this option to display the anti-corruption text when creating a new expense report.</span></span> <span data-ttu-id="455c8-211">ניתן להפוך לזמינות קטגוריות ספציפיות של הוצאות, שידרשו לבחור את ההצהרה נגד שחיתות בדוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="455c8-211">Specific expense categories can then be enabled that will require the anti-corruption attestation to be selected on the expense report.</span></span> <span data-ttu-id="455c8-212">לדוגמה, קטגוריית מתנות שקשורה להוצאה של פקיד ממשלתי עשויה לדרוש שהעובד יאשר כי ההוצאה עומדת במדיניות החברה שקשורה לפקידי ממשלתיים.</span><span class="sxs-lookup"><span data-stu-id="455c8-212">For example, a gift category related to a government official expense may require the employee to confirm that the expense meets company policy related to government officials.</span></span> |
| <span data-ttu-id="455c8-213"><strong>הודעה נגד שחיתות למגיש</strong></span><span class="sxs-lookup"><span data-stu-id="455c8-213"><strong>Anti-corruption message for submitter</strong></span></span> |                                                                                             <span data-ttu-id="455c8-214">הזן את הטקסט שיוצג לעובד בעת יצירת דוח הוצאות חדש.</span><span class="sxs-lookup"><span data-stu-id="455c8-214">Enter the text that will be displayed to the employee when creating a new expense report.</span></span> <span data-ttu-id="455c8-215">לחץ על הלחצן <strong>תרגומים</strong> להזנת טקסט ספציפי לשפה שיוצג בהתבסס על שפת המשתמש.</span><span class="sxs-lookup"><span data-stu-id="455c8-215">Click the <strong>Translations</strong> button to enter language specific text that will be displayed based on the user language.</span></span>                                                                                             |
| <span data-ttu-id="455c8-216"><strong>הודעה נגד שחיתות למאשר</strong></span><span class="sxs-lookup"><span data-stu-id="455c8-216"><strong>Anti-corruption message for approver</strong></span></span>  |                                                                                             <span data-ttu-id="455c8-217">הזן את הטקסט שיוצג למאשר בעת יצירת דוח הוצאות חדש.</span><span class="sxs-lookup"><span data-stu-id="455c8-217">Enter the text that will be displayed to the approver when creating a new expense report.</span></span> <span data-ttu-id="455c8-218">לחץ על הלחצן <strong>תרגומים</strong> להזנת טקסט ספציפי לשפה שיוצג בהתבסס על שפת המשתמש.</span><span class="sxs-lookup"><span data-stu-id="455c8-218">Click the <strong>Translations</strong> button to enter language specific text that will be displayed based on the user language.</span></span>                                                                                             |
