---
title: שיטות הקצאת הזמנות ב-Project Service Automation
description: נושא זה מספק מידע אודות הדרכים השונות שבהן באפשרותך להזמין הקצאות.
author: ruhercul
manager: kfend
ms.service: dynamics-365-customerservice
ms.custom:
- dyn365-projectservice
ms.date: 9/26/2019
ms.topic: article
ms.author: ruhercul
audience: Admin
search.audienceType:
- admin
- customizer
- enduser
search.app:
- D365CE
- D365PS
- ProjectOperations
ms.openlocfilehash: 295da428ce15e7775450dfa94e96047f200bdede
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077302"
---
# <a name="booking-allocation-methods-in-project-service-automation"></a><span data-ttu-id="3a9c1-103">שיטות הקצאת הזמנות ב-Project Service Automation</span><span class="sxs-lookup"><span data-stu-id="3a9c1-103">Booking allocation methods in Project Service Automation</span></span>

<span data-ttu-id="3a9c1-104">בין אם אתה מוסיף חבר צוות ישירות לפרויקט בכרטיסיה **צוות** , או מזמין משאב לפרויקט או דרישה מלוח הזמנים, קיימות כמה שיטות שונות להקצאת הזמנה שניתן להשתמש בהן.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-104">Whether you add a team member directly to a project on the **Team** tab, or book a resource to a project or requirement from the Schedule board, there are a few different booking allocation methods you can use.</span></span> <span data-ttu-id="3a9c1-105">נושא זה מסביר כיצד פועלת כל שיטה ואילו שיטות עלול לגרום להזמנת יתר של משאבים.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-105">This topic explains how each method works, and which methods could lead to overbooking resources.</span></span>

## <a name="full-capacity"></a><span data-ttu-id="3a9c1-106">קיבולת מלאה</span><span class="sxs-lookup"><span data-stu-id="3a9c1-106">Full Capacity</span></span> 
<span data-ttu-id="3a9c1-107">השיטה 'קיבולת מלאה' מזמינה קיבולת מלאה של המשאב עבור התאריכים 'מ' ו'עד' שצוינו.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-107">The Full Capacity method books the resource’s full capacity for the specified from and to dates.</span></span> <span data-ttu-id="3a9c1-108">לדוגמה, אם למשאב יש לוח שנה שמוגדר לעבודה שמונה שעות ביום, חמישה ימים בשבוע, הגדרת תאריך התחלה וסיום המכסה חמישה ימי עבודה תזמין את המשאב ל- 40 שעות.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-108">For example, if a resource has a calendar set to work eight hours per day, five days a week, setting a start and end date that covers five working days will book the resource for 40 hours.</span></span> <span data-ttu-id="3a9c1-109">ההזמנה מתבצעת ללא קשר לקיבולת הנותרת של משאב.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-109">The booking is done without regard to the resource's remaining capacity.</span></span> <span data-ttu-id="3a9c1-110">אם משאב מוזמן כבר במהלך תקופה זו לפרוייקטים אחרים, 40 השעות מוזמנות כשעות נוספות, מה שעלול להוביל להזמנות יתר.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-110">If a resource is already booked on other projects during that period, the 40 hours is booked as additional hours, which potentially leads to overbookings.</span></span>

## <a name="remaining-capacity"></a><span data-ttu-id="3a9c1-111">קיבולת שנותרה</span><span class="sxs-lookup"><span data-stu-id="3a9c1-111">Remaining Capacity</span></span>
<span data-ttu-id="3a9c1-112">השיטה 'קיבולת שנותרה' זמינה רק כאשר אתה מזמין ישירות אל פרוייקט באמצעות לוח הזמנים.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-112">The Remaining Capacity method is only available when you book directly to a project using the Schedule board.</span></span> <span data-ttu-id="3a9c1-113">שיטה זו מזמינה את הקיבולת הזמינה של משאב בטווח התאריכים שצוין.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-113">This method books the resource’s available capacity within the specified date range.</span></span> <span data-ttu-id="3a9c1-114">לדוגמה, אם למשאב יש קיבולת של 40 שעות שבועיות, והוא כבר הוזמן ל- 10 שעות, הזמנה עבור אותו שבוע מזמינה את המשאב ל- 30 השעות הנותרות בקיבולת לשבוע זה.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-114">For example, if a resource has a capacity of 40 hours per week and has already been booked 10 hours, booking for the same week results in booking the remaining 30 hours of capacity for that week.</span></span>

## <a name="percentage-capacity"></a><span data-ttu-id="3a9c1-115">קיבולת באחוזים</span><span class="sxs-lookup"><span data-stu-id="3a9c1-115">Percentage Capacity</span></span>
<span data-ttu-id="3a9c1-116">השיטה 'קיבולת באחוזים' מזמינה את המשאב לאחוז הקיבולת עבור התאריכים 'מ' ו'עד' שצוינו.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-116">The Percentage Capacity method books the resource for a percentage of capacity for the specified from and to dates.</span></span> <span data-ttu-id="3a9c1-117">לדוגמה, אם למשאב יש לוח שנה שמוגדר לעבודה שמונה שעות ביום, חמישה ימים בשבוע, הגדרת תאריך התחלה וסיום המכסה חמישה ימי עבודה בקיבולת של 50% תזמין את המשאב ל- 20 שעות.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-117">For example, if a resource's calendar is set to work eight hours per day, five days a week, setting a start and end date that covers five working days at 50% capacity would book the resource for 20 hours.</span></span> <span data-ttu-id="3a9c1-118">ההזמנות הנפרדות ליום נפרסות באופן שווה על-פני התקופה, ארבע שעות ביום בדוגמה זו.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-118">The individual bookings per day are spread equally across the period, four hours per day in this example.</span></span> <span data-ttu-id="3a9c1-119">ההזמנה מתבצעת ללא קשר לקיבולת הנותרת של משאב.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-119">The booking is done without regard to the resource’s remaining capacity.</span></span> <span data-ttu-id="3a9c1-120">אם המשאב מוזמן כבר במהלך תקופה זו לפרוייקטים אחרים, 20 השעות מוזמנות כשעות נוספות, מה שעלול להוביל להזמנות יתר.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-120">If the resource is already booked during that period on other projects, the 20 hours is booked as additional hours, which potentially leads to overbookings.</span></span>

## <a name="evenly-distribute-hours"></a><span data-ttu-id="3a9c1-121">הפצת שעות באופן שווה</span><span class="sxs-lookup"><span data-stu-id="3a9c1-121">Evenly Distribute Hours</span></span>
<span data-ttu-id="3a9c1-122">השיטה '‏‫הפצת שעות באופן שווה'‬ מזמינה את המשאב למספר מסוים של שעות, ומפיצה את הזמן באופן שווה בכל יום בטווח התאריכים 'מ'/'עד' שצוינו.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-122">The Evenly Distribute Hours method books the resource for a specified number of hours, distributing the time evenly per day over the specified from and to dates.</span></span> <span data-ttu-id="3a9c1-123">לדוגמה, אם אתה מזמין משאב עבור 20 שעות במשך תקופה של חמישה ימים, שיטה זו תפזר את 20 השעות באופן שווה לארבע שעות ביום.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-123">For example, if you book a resource for 20 hours over a five day period, this method distributes the 20 hours evenly at four hours per day.</span></span> <span data-ttu-id="3a9c1-124">ההזמנה מתבצעת ללא קשר לקיבולת הנותרת של משאב.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-124">The booking is done without regard to the resource's remaining capacity.</span></span> <span data-ttu-id="3a9c1-125">אם המשאב מוזמן כבר במהלך תקופה זו לפרוייקטים אחרים, 20 השעות מוזמנות כשעות נוספות, מה שעלול להוביל להזמנות יתר.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-125">If the resource is already booked during that period on other projects, the 20 hours is booked as additional hours, which potentially leads to overbookings.</span></span>

## <a name="front-load-hours"></a><span data-ttu-id="3a9c1-126">שעות עומס חזיתי</span><span class="sxs-lookup"><span data-stu-id="3a9c1-126">Front Load Hours</span></span>
<span data-ttu-id="3a9c1-127">השיטה 'שעות עומס חזיתי' מזמינה את המשאב למספר מסוים של שעות, ומחלקת את השעות ביום לפי עומס חזיתי בטווח התאריכים 'מ' ו'עד' שצוינו.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-127">The Front Load Hours method books the resource for a specified number of hours, front-loading the per-day hours over the specified from and to dates.</span></span> <span data-ttu-id="3a9c1-128">חלוקה לפי עומס חזיתי צורכת את הקיבולת זמינה של משאב בסדר "ראשון-בראשון-שנצרך".</span><span class="sxs-lookup"><span data-stu-id="3a9c1-128">Front-loading consumes the resource's available capacity in a “first-in-first-consumed” order.</span></span> <span data-ttu-id="3a9c1-129">לדוגמה, אם זמני העבודה של משאב הם שמונה שעות ביום, חמישה ימים בשבוע, ואין לו הזמנות נוכחיות, הזמנת המשאב ל- 20 שעות לאורך תקופה של חמישה ימי עבודה תביא לדפוס ההזמנה היומי הבא:</span><span class="sxs-lookup"><span data-stu-id="3a9c1-129">For example, if a resource’s work schedule is eight hours per day, five days per week, and they have no current bookings, booking the resource for 20 hours over a five working day period results in the following daily booking pattern:</span></span> 

|         <span data-ttu-id="3a9c1-130">הזמנות</span><span class="sxs-lookup"><span data-stu-id="3a9c1-130">Bookings</span></span>          |    <span data-ttu-id="3a9c1-131">יום 1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-131">Day 1</span></span>    |    <span data-ttu-id="3a9c1-132">יום 2</span><span class="sxs-lookup"><span data-stu-id="3a9c1-132">Day 2</span></span>    |    <span data-ttu-id="3a9c1-133">יום 3</span><span class="sxs-lookup"><span data-stu-id="3a9c1-133">Day 3</span></span>    |    <span data-ttu-id="3a9c1-134">יום 4</span><span class="sxs-lookup"><span data-stu-id="3a9c1-134">Day 4</span></span>    |    <span data-ttu-id="3a9c1-135">יום 5</span><span class="sxs-lookup"><span data-stu-id="3a9c1-135">Day 5</span></span>    |    <span data-ttu-id="3a9c1-136">סה''כ</span><span class="sxs-lookup"><span data-stu-id="3a9c1-136">Total</span></span>    |
|---------------------------|-------------|-------------|-------------|-------------|-------------|-------------|
|    <span data-ttu-id="3a9c1-137">הזמנות קיימות</span><span class="sxs-lookup"><span data-stu-id="3a9c1-137">Existing   bookings</span></span>    |    <span data-ttu-id="3a9c1-138">1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-138">0</span></span>        |    <span data-ttu-id="3a9c1-139">1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-139">0</span></span>        |    <span data-ttu-id="3a9c1-140">1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-140">0</span></span>        |    <span data-ttu-id="3a9c1-141">1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-141">0</span></span>        |    <span data-ttu-id="3a9c1-142">1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-142">0</span></span>        |    <span data-ttu-id="3a9c1-143">1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-143">0</span></span>        |
|    <span data-ttu-id="3a9c1-144">הזמנה חדשה</span><span class="sxs-lookup"><span data-stu-id="3a9c1-144">New   booking</span></span>          |    <span data-ttu-id="3a9c1-145">8</span><span class="sxs-lookup"><span data-stu-id="3a9c1-145">8</span></span>        |    <span data-ttu-id="3a9c1-146">8</span><span class="sxs-lookup"><span data-stu-id="3a9c1-146">8</span></span>        |    <span data-ttu-id="3a9c1-147">4</span><span class="sxs-lookup"><span data-stu-id="3a9c1-147">4</span></span>        |    <span data-ttu-id="3a9c1-148">0</span><span class="sxs-lookup"><span data-stu-id="3a9c1-148">0</span></span>        |    <span data-ttu-id="3a9c1-149">0</span><span class="sxs-lookup"><span data-stu-id="3a9c1-149">0</span></span>        |    <span data-ttu-id="3a9c1-150">20</span><span class="sxs-lookup"><span data-stu-id="3a9c1-150">20</span></span>       |

<span data-ttu-id="3a9c1-151">שיטת העומס הקדמי מתחשבת בהזמנות קיימות ובקיבולת זמינה.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-151">The front load method takes into consideration existing bookings and available capacity.</span></span> <span data-ttu-id="3a9c1-152">לדוגמה, אם לאותו משאב יש כבר 20 שעות של הזמנות בשבוע העבודה, ההזמנות החדשות צורכות את הקיבולת הנותרת כדלקמן:</span><span class="sxs-lookup"><span data-stu-id="3a9c1-152">For example, if the same resource already has 20 hours of bookings in the work week, the new bookings consume the remaining capacity as follows:</span></span>

|   <span data-ttu-id="3a9c1-153">הזמנות</span><span class="sxs-lookup"><span data-stu-id="3a9c1-153">Bookings</span></span>          | <span data-ttu-id="3a9c1-154">יום 1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-154">Day 1</span></span> | <span data-ttu-id="3a9c1-155">יום 2</span><span class="sxs-lookup"><span data-stu-id="3a9c1-155">Day 2</span></span> | <span data-ttu-id="3a9c1-156">יום 3</span><span class="sxs-lookup"><span data-stu-id="3a9c1-156">Day 3</span></span> | <span data-ttu-id="3a9c1-157">יום 4</span><span class="sxs-lookup"><span data-stu-id="3a9c1-157">Day 4</span></span> | <span data-ttu-id="3a9c1-158">יום 5</span><span class="sxs-lookup"><span data-stu-id="3a9c1-158">Day 5</span></span> | <span data-ttu-id="3a9c1-159">סה''כ</span><span class="sxs-lookup"><span data-stu-id="3a9c1-159">Total</span></span> |
|---------------------|-------|-------|-------|-------|-------|-------|
| <span data-ttu-id="3a9c1-160">הזמנות קיימות</span><span class="sxs-lookup"><span data-stu-id="3a9c1-160">Existing   bookings</span></span> | <span data-ttu-id="3a9c1-161">8</span><span class="sxs-lookup"><span data-stu-id="3a9c1-161">8</span></span>     | <span data-ttu-id="3a9c1-162">8</span><span class="sxs-lookup"><span data-stu-id="3a9c1-162">8</span></span>     | <span data-ttu-id="3a9c1-163">4</span><span class="sxs-lookup"><span data-stu-id="3a9c1-163">4</span></span>     | <span data-ttu-id="3a9c1-164">1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-164">0</span></span>     | <span data-ttu-id="3a9c1-165">1</span><span class="sxs-lookup"><span data-stu-id="3a9c1-165">0</span></span>     | <span data-ttu-id="3a9c1-166">20</span><span class="sxs-lookup"><span data-stu-id="3a9c1-166">20</span></span>    |
| <span data-ttu-id="3a9c1-167">הזמנה חדשה</span><span class="sxs-lookup"><span data-stu-id="3a9c1-167">New   booking</span></span>       | <span data-ttu-id="3a9c1-168">0</span><span class="sxs-lookup"><span data-stu-id="3a9c1-168">0</span></span>     | <span data-ttu-id="3a9c1-169">0</span><span class="sxs-lookup"><span data-stu-id="3a9c1-169">0</span></span>     | <span data-ttu-id="3a9c1-170">4</span><span class="sxs-lookup"><span data-stu-id="3a9c1-170">4</span></span>     | <span data-ttu-id="3a9c1-171">8</span><span class="sxs-lookup"><span data-stu-id="3a9c1-171">8</span></span>     | <span data-ttu-id="3a9c1-172">8</span><span class="sxs-lookup"><span data-stu-id="3a9c1-172">8</span></span>     | <span data-ttu-id="3a9c1-173">20</span><span class="sxs-lookup"><span data-stu-id="3a9c1-173">20</span></span>    |

<span data-ttu-id="3a9c1-174">מאחר שהשיטה מתחשבת בקיבולת זמינה, ייתכן שתקבל הודעת שגיאה אם למשאב אין קיבולת נותרת שניתן לספוג בהזמנה.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-174">Because available capacity is considered, you may get an error message if the resource has no remaining capacity that can be absorbed by the booking.</span></span> <span data-ttu-id="3a9c1-175">בשיטה זו לא ניתן ליצור הזמנת יתר.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-175">With this method, you can’t overbook.</span></span>

## <a name="none"></a><span data-ttu-id="3a9c1-176">ללא</span><span class="sxs-lookup"><span data-stu-id="3a9c1-176">None</span></span>
<span data-ttu-id="3a9c1-177">השיטה 'ללא' זמינה רק בעת הזמנה מהכרטיסיה **צוות** בפרויקט.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-177">The None method is only available when you book from the **Team** tab within a project.</span></span> <span data-ttu-id="3a9c1-178">שיטה זו מוסיפה את המשאב בתור חבר בצוות הפרויקט, אך אינה יוצרת הזמנות כלשהן אשר סופגות את קיבולת המשאב.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-178">This method adds the resource as a team member on the project, but doesn’t create any bookings that absorb the resource's capacity.</span></span> <span data-ttu-id="3a9c1-179">שיטה זו משמשת כאשר חבר צוות המשמש כמנהל פרויקט בברירת המחדל מתווסף בעת יצירת פרויקט.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-179">This method is used when the default project manager team member is added when a project is created.</span></span> <span data-ttu-id="3a9c1-180">משתמש שהוא מנהל הפרויקט שיצר את הפרויקט מתווסף כברירת מחדל לפרויקט, כך שלרשומת ישות של הפרויקט יש בעלים וקיים מאשר אחד בפרויקט.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-180">The project manager user who created the project is added by default to the project, so that the project entity record has an owner and there is one approver on the project.</span></span> <span data-ttu-id="3a9c1-181">מאחר שלמשתמש זה אין הזמנות כלשהן, אם ברצונך להזמין את המשאב, באפשרותך למחוק ולהוסיף אותו מחדש באמצעות שיטת הקצאה אחרת, או להוסיף את המשאב למשימות ולאחר מכן להשתמש ב **הזמנות מורחבות** בכרטיסיה **פיוס** ליצירת הזמנות עבור ההקצאות.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-181">Because this user doesn't have any bookings, if you do want to book the resource, you can either delete and then re-add them using a different allocation method, or add the resource to tasks and then use **Extend Bookings** on the **Reconciliation** tab to create bookings for the assignments.</span></span>

## <a name="allocation-methods-that-lead-to-overbooking"></a><span data-ttu-id="3a9c1-182">שיטות הקצאה שמובילות להזמנת יתר</span><span class="sxs-lookup"><span data-stu-id="3a9c1-182">Allocation methods that lead to overbooking</span></span>
<span data-ttu-id="3a9c1-183">לסיכום, שיטות ההקצאה הבאות מובילות להזמנת יתר אם המשאב כבר מחויב בפרויקטים אחרים (או עבור הזמנות עבודה אחרות או ישויות אחרות הניתנות לתזמון):</span><span class="sxs-lookup"><span data-stu-id="3a9c1-183">To summarize, the following allocation methods lead to overbooking if the resource is already committed in other projects (or for other work orders or schedulable entities):</span></span>

- <span data-ttu-id="3a9c1-184">קיבולת מלאה</span><span class="sxs-lookup"><span data-stu-id="3a9c1-184">Full Capacity</span></span>
- <span data-ttu-id="3a9c1-185">קיבולת באחוזים</span><span class="sxs-lookup"><span data-stu-id="3a9c1-185">Percentage Capacity</span></span>
- <span data-ttu-id="3a9c1-186">הפצת שעות באופן שווה</span><span class="sxs-lookup"><span data-stu-id="3a9c1-186">Evenly Distribute Hours</span></span>

<span data-ttu-id="3a9c1-187">בעת שימוש באחת משלוש שיטות ההקצאה הללו, לא תקבל הודעה בעת הזמנת יתר של משאב.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-187">When using one of these three allocation methods, you won’t be notified that the resource is overbooked.</span></span> <span data-ttu-id="3a9c1-188">כדי לתקן את הזמנת היתר, יהיה עליך להשתמש בלוח הזמנים.</span><span class="sxs-lookup"><span data-stu-id="3a9c1-188">To correct the overbooking, you’ll need to use the Schedule board.</span></span>