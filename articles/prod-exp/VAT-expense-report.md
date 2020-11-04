---
title: החזר מע"מ
description: נושא זה מסביר כיצד ניתן לקבל החזרים בגין עסקאות הכוללות מס ערך מוסף (מע"מ).
author: saraschi2
manager: AnnBe
ms.date: 02/26/2018
ms.topic: article
ms.prod: ''
ms.service: dynamics-ax-applications
ms.technology: ''
ms.search.form: TrvPerDiems
audience: Application User
ms.reviewer: roschlom
ms.search.scope: Core, Operations
ms.search.region: Global
ms.author: saraschi
ms.search.validFrom: 2016-02-28
ms.dyn365.ops.version: AX 7.0.0
ms.openlocfilehash: d1be96521cdb486dd5a702cded615d3e1015b364
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077350"
---
# <a name="vat-recovery"></a><span data-ttu-id="f73c3-103">החזר מע"מ</span><span class="sxs-lookup"><span data-stu-id="f73c3-103">VAT recovery</span></span> 

[!include [banner](../includes/banner.md)]

<span data-ttu-id="f73c3-104">כדי לקבל החזרים כספיים בגין עסקאות זכאיות למס ערך מוסף (מע"מ), על החברה או הארגון לזהות, לאסוף, לאמת ולהגיש מידע מדויק.</span><span class="sxs-lookup"><span data-stu-id="f73c3-104">To receive refunds on eligible value-added tax (VAT) transactions, a company or organization must identify, collect, verify, and submit accurate information.</span></span> <span data-ttu-id="f73c3-105">תהליך זה כולל מספר משימות, ובהתאם לגודל החברה, עשוי לכלול מספר עובדים או תפקידים.</span><span class="sxs-lookup"><span data-stu-id="f73c3-105">This process includes multiple tasks and, depending on the size of your company, can include several employees or roles.</span></span>

<span data-ttu-id="f73c3-106">כדי לקבל החזרי מע"מ באמצעות ניהול הוצאות, יש להשלים את ה‏‫דרישות המוקדמות הבאות:</span><span class="sxs-lookup"><span data-stu-id="f73c3-106">To recover VAT by using Expense management, the following prerequisites must be completed:</span></span>

- <span data-ttu-id="f73c3-107">יש ליצור קודי מס עבור מדינות/אזורים בעלי הקצאות לקטגוריות של הוצאות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-107">Tax codes must be created for countries/regions that are allocated to expense categories.</span></span>
- <span data-ttu-id="f73c3-108">יש ליצור קבוצת מע"מ עבור כל קוד מס.</span><span class="sxs-lookup"><span data-stu-id="f73c3-108">A sales tax group must be created for each tax code.</span></span>
- <span data-ttu-id="f73c3-109">יש ליצור קוד מע"מ לפריט עבור כל קבוצת מע"מ.</span><span class="sxs-lookup"><span data-stu-id="f73c3-109">An item sales tax code must be created for each sales tax group.</span></span>

<span data-ttu-id="f73c3-110">לאחר השלמת ‏‫הדרישות המוקדמות, על העובדים לבצע את השלבים הבאים כדי לבקש החזר עבור עסקאות מע"מ.</span><span class="sxs-lookup"><span data-stu-id="f73c3-110">After the prerequisites are completed, employees follow these steps to request refunds for VAT transactions.</span></span>

1. <span data-ttu-id="f73c3-111">בדוח הוצאות, הזן פרטי מס של עסקאות בכרטיס אשראי כדי לזהות זכאויות להחזרי מע"מ.</span><span class="sxs-lookup"><span data-stu-id="f73c3-111">On an expense report, enter tax information about credit card transactions to identify eligible VAT refunds.</span></span>
2. <span data-ttu-id="f73c3-112">יש לוודא שכל פרטי המס מלאים ולאחר מכן לרשום את דוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-112">Make sure that all tax information is complete, and then post the expense report.</span></span>
3. <span data-ttu-id="f73c3-113">בצע עיבוד של הוצאות זכאיות להחזר מע"מ בין מדינות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-113">Process expenses that are eligible for international VAT recovery.</span></span>
4. <span data-ttu-id="f73c3-114">שלח את הנתונים על החזרי מע"מ לספק החיצוני כדי להגיש בקשות להחזרי מע"מ בין מדינות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-114">Send VAT recovery data to the third-party vendor to file international recovery returns.</span></span>
5. <span data-ttu-id="f73c3-115">בצע עיבוד של הוצאות עבור החזר מע"מ מקומי.</span><span class="sxs-lookup"><span data-stu-id="f73c3-115">Process expenses for domestic VAT recovery.</span></span>

<span data-ttu-id="f73c3-116">הסעיפים הבאים כוללים דוגמאות המראות כיצד עובדי Contoso מבצעים כל שלב.</span><span class="sxs-lookup"><span data-stu-id="f73c3-116">The following sections provide examples that show how Contoso employees complete each step.</span></span>

## <a name="on-an-expense-report-enter-tax-information-about-credit-card-transactions-to-identify-eligible-vat-refunds"></a><span data-ttu-id="f73c3-117">בדוח הוצאות, הזן פרטי מס של עסקאות בכרטיס אשראי כדי לזהות זכאויות להחזרי מע"מ</span><span class="sxs-lookup"><span data-stu-id="f73c3-117">On an expense report, enter tax information about credit card transactions to identify eligible VAT refunds</span></span>

<span data-ttu-id="f73c3-118">הגר, נציגת מכירות מחברת Contoso הממוקמת בארצות הברית, חזרה לאחרונה מנסיעת מכירות לבריטניה.</span><span class="sxs-lookup"><span data-stu-id="f73c3-118">Nancy, a Contoso sales representative who is based in the US, recently returned from a sales trip to the United Kingdom.</span></span> <span data-ttu-id="f73c3-119">במהלך הנסיעה היו להגר מספר הוצאות על ארוחות, והיא שילמה באמצעות כרטיס האשראי האישי שלה.</span><span class="sxs-lookup"><span data-stu-id="f73c3-119">During her trip, she incurred some personal credit card expenses for meals.</span></span> <span data-ttu-id="f73c3-120">כעת הגר צריכה להכין דוח הוצאות כדי להסדיר את עניין ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-120">Nancy must now create an expense report to reconcile her expenses.</span></span>

<span data-ttu-id="f73c3-121">הגר מזינה את הפרטים בדוח ההוצאות: היא בוחרת ב **בריטניה** בשדה **מדינה/אזור** שבדף **ערוך דוח הוצאות**.</span><span class="sxs-lookup"><span data-stu-id="f73c3-121">When Nancy enters information on her expense report, she selects **United Kingdom** in the **Country/region** field on the **Edit expense report** page.</span></span> <span data-ttu-id="f73c3-122">לאחר מכן, מתבצע סינון של רשימת קבוצות המע"מ כך שרק הקבוצות הנוגעות לבריטניה מוצגות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-122">The list of sales tax groups is then filtered so that it shows only the groups that apply to the United Kingdom.</span></span> <span data-ttu-id="f73c3-123">הגר בוחרת את קבוצת המע"מ **בריטניה 001** ולאחר מכן בוחרת בפריט **ארוחות** מבין קבוצות המע"מ לפריטים.</span><span class="sxs-lookup"><span data-stu-id="f73c3-123">Nancy selects the **United Kingdom 001** sales tax group and then selects the **Meals** item sales tax group.</span></span> <span data-ttu-id="f73c3-124">לאחר מכן, הגר מוסיפה עסקה של לינה.</span><span class="sxs-lookup"><span data-stu-id="f73c3-124">She then adds a new transaction for her lodging.</span></span> <span data-ttu-id="f73c3-125">מאחר שיש רק קבוצת מע"מ אחת ורק קבוצת מע"מ אחת לפריט עבור לינה בבריטניה, אפשרות זו מוזנת אוטומטית בדוח ההוצאות של הגר.</span><span class="sxs-lookup"><span data-stu-id="f73c3-125">Because there is only one sales tax group and item sales tax group for lodging in the United Kingdom, this information is automatically filled in on Nancy's expense report.</span></span>

<span data-ttu-id="f73c3-126">לפי המדיניות של Contoso, עבור כל הוצאה חייבת להיות קבלה תואמת.</span><span class="sxs-lookup"><span data-stu-id="f73c3-126">Per Contoso policy, all expenses must have a matching receipt.</span></span> <span data-ttu-id="f73c3-127">לכן, כשהגר שומרת את דוח ההוצאות, היא מקבלת הודעה לפיה עליה לצרף קבלה עבור כל עסקה שהיא רשמה בדוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-127">Therefore, when Nancy saves her expense report, she receives a message that states that she must attach a receipt for each transaction that she listed on her expense report.</span></span> <span data-ttu-id="f73c3-128">הגר מוודאת שהיא צירפה לדוח ההוצאות צילום דיגיטלי של הקבלות על כל העסקאות ולאחר מכן מגישה את הדוח לקבלת אישור.</span><span class="sxs-lookup"><span data-stu-id="f73c3-128">Nancy verifies that she has attached a digital image of each transaction receipt to her expense report and then submits her report for approval.</span></span> <span data-ttu-id="f73c3-129">לאחר מכן היא שולחת את העתקי הקבלות המודפסים אל הצוות המטפל בכך במערך האחורי.</span><span class="sxs-lookup"><span data-stu-id="f73c3-129">She then sends the paper receipts to the back-office processing team.</span></span> <span data-ttu-id="f73c3-130">צוות זה ישלח את הנתונים על החזרי מע"מ לספק החיצוני אשר מגיש בקשות להחזרי מע"מ בין מדינות מטעם Contoso.</span><span class="sxs-lookup"><span data-stu-id="f73c3-130">This team will send the VAT recovery data to the third-party vendor that files international VAT recovery returns for Contoso.</span></span>

## <a name="make-sure-that-all-tax-information-is-complete-and-then-post-the-expense-report"></a><span data-ttu-id="f73c3-131">יש לוודא שכל פרטי המס מלאים ולאחר מכן לרשום את דוח ההוצאות</span><span class="sxs-lookup"><span data-stu-id="f73c3-131">Make sure that all tax information is complete, and then post the expense report</span></span>

<span data-ttu-id="f73c3-132">אפרת, מתאמת חשבונות זכאים ב- Contoso, צריכה להזין את פרטי המיסוי שחסרים בדוח ההוצאות לפני שהיא תוכל לשלוח את הדוח.</span><span class="sxs-lookup"><span data-stu-id="f73c3-132">April, the Accounts payable coordinator for Contoso, must enter any tax information that is missing from an expense report before the report can be posted.</span></span> <span data-ttu-id="f73c3-133">היא פותחת את דף **פרטי דוח הוצאות** ורואה את דוח ההוצאות של הגר שעבר אישור.</span><span class="sxs-lookup"><span data-stu-id="f73c3-133">She opens the **Expense report details** page and sees Nancy's approved expense report.</span></span> <span data-ttu-id="f73c3-134">לאחר מכן, אפרת פותחת את דוח ההוצאות כדי לראות את פרטי העסקאות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-134">April then opens the expense report to view the details of the transactions.</span></span> <span data-ttu-id="f73c3-135">היא רואה שהגר לא הזינה קבוצת מע"מ לפריט עבור אחת מהעסקאות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-135">She sees that Nancy didn't enter an item sales tax group for one of the transactions.</span></span> <span data-ttu-id="f73c3-136">מכיוון שמידע זה חסר, אפרת לא יכולה לרשום את דוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-136">Because this information isn't provided, April can't post the expense report.</span></span> <span data-ttu-id="f73c3-137">לכן, אפרת בודקת בדף **תצורות מס** בניהול הוצאות, ומוצאת את קבוצת המע"מ לפריט המתאימה למדינה/אזור ולסוג העסקה.</span><span class="sxs-lookup"><span data-stu-id="f73c3-137">Therefore, April looks on the **Tax configurations** page in Expense management, and finds the appropriate item sales tax group for the country/region and the transaction type.</span></span> <span data-ttu-id="f73c3-138">כעת אפרת יכולה לרשום את דוח ההוצאות בספר החשבונות הראשי.</span><span class="sxs-lookup"><span data-stu-id="f73c3-138">April can now post the expense report to the general ledger.</span></span>

<span data-ttu-id="f73c3-139">במהלך הרישום של דוח ההוצאות, נוצר פריט עבודה של החזר מע"מ.</span><span class="sxs-lookup"><span data-stu-id="f73c3-139">When April posts the expense report, a VAT recoverable work item is created.</span></span> <span data-ttu-id="f73c3-140">פריט עבודה זה מוקצה לחבר בצוות העיבוד במערך האחורי.</span><span class="sxs-lookup"><span data-stu-id="f73c3-140">This work item is assigned to a member of the back-office processing team.</span></span> <span data-ttu-id="f73c3-141">אפרת מקבלת הודעה המאשרת שהרישום התבצע בהצלחה.</span><span class="sxs-lookup"><span data-stu-id="f73c3-141">April receives a message that confirms that posting was successful.</span></span> <span data-ttu-id="f73c3-142">בהודעה זו גם מצוין מספר עסקאות המע"מ שזוהו לצורך החזר.</span><span class="sxs-lookup"><span data-stu-id="f73c3-142">This message also lists the number of VAT transactions that were identified for recovery.</span></span>

## <a name="process-expenses-that-are-eligible-for-international-vat-recovery"></a><span data-ttu-id="f73c3-143">עיבוד של הוצאות זכאיות להחזר מע"מ בין מדינות</span><span class="sxs-lookup"><span data-stu-id="f73c3-143">Process expenses that are eligible for international VAT recovery</span></span>

<span data-ttu-id="f73c3-144">ארנון, חבר בצוות העיבוד במערך האחורי ב- Contoso, אחראי לאשר שכל המידע הנדרש לביצוע החזרי מע"מ נכלל בדוחות ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-144">Arnie, a member of Contoso's back-office processing team, is responsible for confirming that all the required information for VAT recovery is included on expense reports.</span></span> <span data-ttu-id="f73c3-145">הוא פותח את דף **החזר מס על הוצאות** ובוחר את דוח ההוצאות שהגר הגישה.</span><span class="sxs-lookup"><span data-stu-id="f73c3-145">He opens the **Expense tax recovery** page and selects the expense report that Nancy submitted.</span></span> <span data-ttu-id="f73c3-146">ארנון מוודא שכל הקבלות הנדרשות צורפו ושהוזנו הפרטים הנכונים של קבוצת מע"מ וקודי מע"מ לפריט.</span><span class="sxs-lookup"><span data-stu-id="f73c3-146">Arnie verifies that all the required receipts are attached, and that the correct sales tax group and item sales tax codes were entered.</span></span>

<span data-ttu-id="f73c3-147">כאשר ארנון מקבל מהגר את העתקי הקבלות המודפסים, הוא מאמת את קבלות הנייר מול הקבלות הדיגיטליות ולאחר מכן משנה את הסטטוס של דוח ההוצאות ל **מוכן להחזר**.</span><span class="sxs-lookup"><span data-stu-id="f73c3-147">When Arnie receives the paper receipts from Nancy, he verifies the paper receipts against the digital receipts and then changes the status of the expense report to **Ready for recovery**.</span></span>

## <a name="send-vat-recovery-data-to-the-third-party-vendor-to-file-international-recovery-returns"></a><span data-ttu-id="f73c3-148">שלח את הנתונים על החזרי מע"מ לספק החיצוני כדי להגיש בקשות להחזרי מע"מ בין מדינות</span><span class="sxs-lookup"><span data-stu-id="f73c3-148">Send VAT recovery data to the third-party vendor to file international recovery returns</span></span>

<span data-ttu-id="f73c3-149">כאשר ארנון מוכן לשליחת נתוני דוח ההוצאות לספק החיצוני שיגיש את הבקשות להחזרי מע"מ, הוא פותח את דף **החזרי מס על הוצאות**.</span><span class="sxs-lookup"><span data-stu-id="f73c3-149">When Arnie is ready to send the expense report data to the third-party vendor that will file the VAT recovery returns, he opens the **Expense tax recovery** page.</span></span> <span data-ttu-id="f73c3-150">הוא מסנן את הדף כך שיוצגו רק דוחות ההוצאות המסומנים כ **מוכן להחזר**.</span><span class="sxs-lookup"><span data-stu-id="f73c3-150">He filters the page so that it shows only the expense reports that are marked as **Ready for recovery**.</span></span> <span data-ttu-id="f73c3-151">לאחר מכן, ארנון בוחר **קובץ** &gt; **ייצא ל- Excel**.</span><span class="sxs-lookup"><span data-stu-id="f73c3-151">Arnie then selects **File** &gt; **Export to Excel**.</span></span> <span data-ttu-id="f73c3-152">פרטי המע"מ מדוחות ההוצאות מיוצאים לגליון עבודה של Microsoft Excel.</span><span class="sxs-lookup"><span data-stu-id="f73c3-152">The VAT information from the expense reports is exported to a Microsoft Excel worksheet.</span></span> <span data-ttu-id="f73c3-153">ארנון שולח את גליון העבודה לספק החיצוני וכולל הודעה המציינת כי הקבלות המודפסות נשלחו באמצעות שליח.</span><span class="sxs-lookup"><span data-stu-id="f73c3-153">Arnie submits this worksheet to the third-party vendor and includes a message that states that the paper receipts have been sent by courier.</span></span>

## <a name="process-expenses-for-domestic-vat-recovery"></a><span data-ttu-id="f73c3-154">עיבוד הוצאות עבור החזר מע"מ מקומי</span><span class="sxs-lookup"><span data-stu-id="f73c3-154">Process expenses for domestic VAT recovery</span></span>

<span data-ttu-id="f73c3-155">ארנון חייב לוודא שהעסקאות המפורטות בדוח ההוצאות זכאיות להחזר מע"מ, ושהקבלות הדיגיטליות צורפו לדוחות.</span><span class="sxs-lookup"><span data-stu-id="f73c3-155">Arnie must verify that the expense report transactions are eligible for VAT recovery, and that the digital receipts are attached to the reports.</span></span> <span data-ttu-id="f73c3-156">כדי להתחיל לטפל בהוצאות הזכאיות להחזר מקומי, ארנון פותח את הדף **החזר מס על הוצאות** ובוחר את דוח ההוצאות שיש לבדוק ולאמת.</span><span class="sxs-lookup"><span data-stu-id="f73c3-156">To start to process eligible expenses for domestic recovery, Arnie opens the **Expense tax recovery** page and selects the expense report that requires verification.</span></span> <span data-ttu-id="f73c3-157">הוא מוודא כי הקבלות רשומות על שם החברה ולא על שם העובד.</span><span class="sxs-lookup"><span data-stu-id="f73c3-157">He verifies that receipts are in the name of the company instead of the employee.</span></span> <span data-ttu-id="f73c3-158">לצורך החזר מע"מ, הקבלות חייבות להיות על שם החברה.</span><span class="sxs-lookup"><span data-stu-id="f73c3-158">For VAT recovery, receipts must be in the name of the company.</span></span> <span data-ttu-id="f73c3-159">לאחר מכן, ארנון מאשר שהקודים הנכונים של מס מכירה וקבוצת מס מכירה מופיעים.</span><span class="sxs-lookup"><span data-stu-id="f73c3-159">Arnie then confirms that the correct sales tax group and item sales tax codes were applied.</span></span>

<span data-ttu-id="f73c3-160">כאשר ארנון מקבל את הקבלות המודפסות, הוא משנה את הסטטוס של דוח ההוצאות ל **מוכן להחזר**.</span><span class="sxs-lookup"><span data-stu-id="f73c3-160">When Arnie receives the paper receipts, he changes the status of the expense report to **Ready for recovery**.</span></span> <span data-ttu-id="f73c3-161">לאחר מכן הוא יכול להגיש את הבקשה להחזר לרשות המס המתאימה.</span><span class="sxs-lookup"><span data-stu-id="f73c3-161">He can then file the return with the appropriate tax authority.</span></span> <span data-ttu-id="f73c3-162">במקרה זה, רשות המסים המתאימה בארה"ב היא מס הכנסה (IRS).</span><span class="sxs-lookup"><span data-stu-id="f73c3-162">In this case, the appropriate tax authority in the US is the Internal Revenue Service (IRS).</span></span>