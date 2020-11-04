---
title: שימוש במשאב ניתן להזמנה כממד תמחור
description: נושא זה מספק מידע על שימוש במשאב ניתן להזמנה כממד תמחור.
author: Rumant
manager: kfend
ms.custom:
- dyn365-projectservice
ms.date: 10/01/2020
ms.topic: article
ms.service: business-applications
ms.author: rumant
audience: Admin
search.audienceType:
- admin
- customizer
- enduser
search.app:
- D365PS
- ProjectOperations
ms.openlocfilehash: 8a5c643745d8e10887965228da7abd8f56228006
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077407"
---
# <a name="use-bookable-resource-as-a-pricing-dimension"></a><span data-ttu-id="4b3fe-103">שימוש במשאב ניתן להזמנה כממד תמחור</span><span class="sxs-lookup"><span data-stu-id="4b3fe-103">Use bookable resource as a pricing dimension</span></span>
<span data-ttu-id="4b3fe-104">נושא זה מספק מידע על שימוש במשאב ניתן להזמנה כממד תמחור.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-104">This topic provides information about using a bookable resource as a pricing dimension.</span></span> <span data-ttu-id="4b3fe-105">לפני שתתחיל, אם עדיין לא יצרת פתרון של ממד תמחור, תצטרך ליצור פתרון חדש.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-105">Before you begin, if you have not already created a pricing dimension solution, you will need to create a new one.</span></span> <span data-ttu-id="4b3fe-106">אם כבר יש לך פתרון ממד תמחור, תוכל לבצע את השינויים בפתרון זה.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-106">If you already have a pricing dimension solution, then you can make your changes in that solution.</span></span> <span data-ttu-id="4b3fe-107">אם לא יצרת פתרון ממד תמחור חדש עבור הארגון שלך, השלם את ההליכים בנושא [יצירת שדות וישויות מותאמים אישית](create-custom-fields-entities.md).</span><span class="sxs-lookup"><span data-stu-id="4b3fe-107">If you have not created a new pricing dimension solution for your organization, complete the procedures in the [Create custom fields and entities](create-custom-fields-entities.md) topic.</span></span>

## <a name="add-bookable-resource-to-forms-and-views"></a><span data-ttu-id="4b3fe-108">הוספת משאב ניתן להזמנה לטפסים ולתצוגות</span><span class="sxs-lookup"><span data-stu-id="4b3fe-108">Add bookable resource to forms and views</span></span>
<span data-ttu-id="4b3fe-109">כדי להפוך את השדות לגלויים בממשק המשתמש בפתרון ממד התמחור, תצטרך לעבור בין כל הטפסים והתצוגות של הישויות העיקריות של Project Service ולהוסיף שדות אלה לטפסים ולתצוגות של ישויות אלה.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-109">To make the fields visible in the UI in the pricing dimension solution, you will need to walk through all of the forms and views of the key Project Service entities and add these fields to the forms and views of those entities.</span></span>
<span data-ttu-id="4b3fe-110">הטבלה הבאה היא רשימה מקיפה של הטפסים והתצוגות המוכנים לשימוש, מפורטים לפי ישות, שיהיה צורך לעדכן אותם.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-110">The following table is a comprehensive list of the out-of-the box forms and views, listed by entity, that will need to be updated.</span></span> <span data-ttu-id="4b3fe-111">אם יש תצוגות או טפסים נוספים בהתאמות האישיות שלך בישויות אלה, הוסף את השדות החדשים גם להם.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-111">If there are any additional views or forms in your customizations on these entities, add the new fields to those as well.</span></span>
<span data-ttu-id="4b3fe-112">פתח את סייר הפתרונות עבור פתרון ממד התמחור ולאחר מכן לחץ על **פרסם את כל ההתאמות האישיות**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-112">Open Solution Explorer for the pricing dimension solution and then click **Publish All Customizations**.</span></span>


|   <span data-ttu-id="4b3fe-113">ישות</span><span class="sxs-lookup"><span data-stu-id="4b3fe-113">Entity</span></span>        | <span data-ttu-id="4b3fe-114">טפסים</span><span class="sxs-lookup"><span data-stu-id="4b3fe-114">Forms</span></span>   |<span data-ttu-id="4b3fe-115">תצוגות</span><span class="sxs-lookup"><span data-stu-id="4b3fe-115">Views</span></span>        |
| ------------------------------|---------------------------------|----------------------------------|
|  <span data-ttu-id="4b3fe-116">מחיר תפקיד</span><span class="sxs-lookup"><span data-stu-id="4b3fe-116">Role Price</span></span>|<span data-ttu-id="4b3fe-117">• מידע</span><span class="sxs-lookup"><span data-stu-id="4b3fe-117">• Information</span></span> |<span data-ttu-id="4b3fe-118">• מחירי קטגוריות משאבים פעילים</span><span class="sxs-lookup"><span data-stu-id="4b3fe-118">• Active Resource Category Prices</span></span><br> <span data-ttu-id="4b3fe-119">• תצוגה משויכת של מחיר קטגוריות משאבים</span><span class="sxs-lookup"><span data-stu-id="4b3fe-119">• Resource Category Price Associated View</span></span>|
|  <span data-ttu-id="4b3fe-120">ייקור מחיר תפקיד</span><span class="sxs-lookup"><span data-stu-id="4b3fe-120">Role Price Markup</span></span>|<span data-ttu-id="4b3fe-121">• מידע</span><span class="sxs-lookup"><span data-stu-id="4b3fe-121">• Information</span></span>|<span data-ttu-id="4b3fe-122">• ייקור מחיר התפקיד הפעיל</span><span class="sxs-lookup"><span data-stu-id="4b3fe-122">• Active Role Price Markup</span></span><br><span data-ttu-id="4b3fe-123">• תצוגה משויכת של ייקור מחיר התפקיד</span><span class="sxs-lookup"><span data-stu-id="4b3fe-123">• Role Price Markup Associated View</span></span>|
|  <span data-ttu-id="4b3fe-124">פרטים בשורת הצעת מחיר</span><span class="sxs-lookup"><span data-stu-id="4b3fe-124">Quote line detail</span></span>|<span data-ttu-id="4b3fe-125">• פרטי פרויקט</span><span class="sxs-lookup"><span data-stu-id="4b3fe-125">• Project Information</span></span><br><span data-ttu-id="4b3fe-126">• יצירה מהירה של פרויקט</span><span class="sxs-lookup"><span data-stu-id="4b3fe-126">• Project Quick Create</span></span>|<span data-ttu-id="4b3fe-127">• פרטים בשורת הצעת מחיר פעילה</span><span class="sxs-lookup"><span data-stu-id="4b3fe-127">• Active Quote Line Detail</span></span><br><span data-ttu-id="4b3fe-128">• פרטי שורה של הצעת מחיר משולבת</span><span class="sxs-lookup"><span data-stu-id="4b3fe-128">• Combined Quote Line Details</span></span><br><span data-ttu-id="4b3fe-129">• תצוגה משויכת של פרטי שורה בהצעת מחיר</span><span class="sxs-lookup"><span data-stu-id="4b3fe-129">• Quote Line Detail associated view</span></span>|
|  <span data-ttu-id="4b3fe-130">פרט סעיף חוזה של פרויקט</span><span class="sxs-lookup"><span data-stu-id="4b3fe-130">Project Contract line detail</span></span>|<span data-ttu-id="4b3fe-131">• פרטי פרוייקט</span><span class="sxs-lookup"><span data-stu-id="4b3fe-131">• Project Information</span></span><br><span data-ttu-id="4b3fe-132">• יצירה מהירה של פרוייקט</span><span class="sxs-lookup"><span data-stu-id="4b3fe-132">• Project Quick Create</span></span>|<span data-ttu-id="4b3fe-133">• פרטי סעיף חוזה משולב</span><span class="sxs-lookup"><span data-stu-id="4b3fe-133">• Combined Contract line Details</span></span><br><span data-ttu-id="4b3fe-134">• פרטי סעיף חוזה פעיל</span><span class="sxs-lookup"><span data-stu-id="4b3fe-134">• Active Contract Line Details</span></span><br><span data-ttu-id="4b3fe-135">• תצוגה משויכת של פרטי סעיף חוזה</span><span class="sxs-lookup"><span data-stu-id="4b3fe-135">• Contract Line Detail associated view</span></span>|
|  <span data-ttu-id="4b3fe-136">משימת פרויקט</span><span class="sxs-lookup"><span data-stu-id="4b3fe-136">Project Task</span></span>|<span data-ttu-id="4b3fe-137">• מידע</span><span class="sxs-lookup"><span data-stu-id="4b3fe-137">• Information</span></span><br><span data-ttu-id="4b3fe-138">• טופס חדש</span><span class="sxs-lookup"><span data-stu-id="4b3fe-138">• New Form</span></span>||
|  <span data-ttu-id="4b3fe-139">חבר צוות פרוייקט</span><span class="sxs-lookup"><span data-stu-id="4b3fe-139">Project Team Member</span></span>|<span data-ttu-id="4b3fe-140">• מידע</span><span class="sxs-lookup"><span data-stu-id="4b3fe-140">• Information</span></span><br><span data-ttu-id="4b3fe-141">• טופס חדש</span><span class="sxs-lookup"><span data-stu-id="4b3fe-141">• New Form</span></span>|<span data-ttu-id="4b3fe-142">• חברי צוות פרויקט פעיל</span><span class="sxs-lookup"><span data-stu-id="4b3fe-142">• Active Project Team Members</span></span><br><span data-ttu-id="4b3fe-143">• חברי צוות פרויקט</span><span class="sxs-lookup"><span data-stu-id="4b3fe-143">• Project Team Members</span></span><br><span data-ttu-id="4b3fe-144">• תצוגה משויכת של חברי צוות פרויקט</span><span class="sxs-lookup"><span data-stu-id="4b3fe-144">• Project Team members associated View</span></span>|
|  <span data-ttu-id="4b3fe-145">ערך זמן</span><span class="sxs-lookup"><span data-stu-id="4b3fe-145">Time Entry</span></span>|<span data-ttu-id="4b3fe-146">• מידע</span><span class="sxs-lookup"><span data-stu-id="4b3fe-146">• Information</span></span><br><span data-ttu-id="4b3fe-147">• יצירת ערך זמן</span><span class="sxs-lookup"><span data-stu-id="4b3fe-147">• Create Time Entry</span></span>|<span data-ttu-id="4b3fe-148">• ערכי הזמן שלי לפי תאריך</span><span class="sxs-lookup"><span data-stu-id="4b3fe-148">• My Time Entries By Date</span></span><br><span data-ttu-id="4b3fe-149">• ערכי הזמן שלי לשבוע זה</span><span class="sxs-lookup"><span data-stu-id="4b3fe-149">• My time Entries for this week</span></span><br><span data-ttu-id="4b3fe-150">• ערכי זמן לאישור</span><span class="sxs-lookup"><span data-stu-id="4b3fe-150">• Time entries for approval</span></span>|
|  <span data-ttu-id="4b3fe-151">שורת יומן</span><span class="sxs-lookup"><span data-stu-id="4b3fe-151">Journal Line</span></span>|<span data-ttu-id="4b3fe-152">• מידע</span><span class="sxs-lookup"><span data-stu-id="4b3fe-152">• Information</span></span><br><span data-ttu-id="4b3fe-153">• יצירה מהירה</span><span class="sxs-lookup"><span data-stu-id="4b3fe-153">• Quick create</span></span>|<span data-ttu-id="4b3fe-154">• שורות יומן פעיל</span><span class="sxs-lookup"><span data-stu-id="4b3fe-154">• Active journal lines</span></span><br><span data-ttu-id="4b3fe-155">• תצוגה משויכת של שורת יומן</span><span class="sxs-lookup"><span data-stu-id="4b3fe-155">• Journal Line associated view</span></span>|
|  <span data-ttu-id="4b3fe-156">פרט בשורת חשבונית</span><span class="sxs-lookup"><span data-stu-id="4b3fe-156">Invoice Line Detail</span></span>|<span data-ttu-id="4b3fe-157">• מידע</span><span class="sxs-lookup"><span data-stu-id="4b3fe-157">• Information</span></span><br><span data-ttu-id="4b3fe-158">• יצירה מהירה</span><span class="sxs-lookup"><span data-stu-id="4b3fe-158">• Quick create</span></span>|<span data-ttu-id="4b3fe-159">• פרטי שורה בחשבונית פעילה</span><span class="sxs-lookup"><span data-stu-id="4b3fe-159">• Active Invoice Line Details</span></span><br><span data-ttu-id="4b3fe-160">• עסקאות חשבונית לחיוב</span><span class="sxs-lookup"><span data-stu-id="4b3fe-160">• Chargeable Invoice Transactions</span></span><br><span data-ttu-id="4b3fe-161">• עסקאות חשבונית ללא תשלום</span><span class="sxs-lookup"><span data-stu-id="4b3fe-161">• Complimentary Invoice Transactions</span></span><br><span data-ttu-id="4b3fe-162">• תצוגה משויכת של פרטי שורה בחשבונית</span><span class="sxs-lookup"><span data-stu-id="4b3fe-162">• Invoice Line Detail associated view</span></span><br><span data-ttu-id="4b3fe-163">• עסקאות חשבונית שאינן ניתנות לחיוב</span><span class="sxs-lookup"><span data-stu-id="4b3fe-163">• Non-Chargeable Invoice Transactions</span></span>|
|  <span data-ttu-id="4b3fe-164">בפועל</span><span class="sxs-lookup"><span data-stu-id="4b3fe-164">Actual</span></span>|<span data-ttu-id="4b3fe-165">• מידע</span><span class="sxs-lookup"><span data-stu-id="4b3fe-165">• Information</span></span><br><span data-ttu-id="4b3fe-166">• נתונים בפועל פעילים</span><span class="sxs-lookup"><span data-stu-id="4b3fe-166">• Active Actuals</span></span>|<span data-ttu-id="4b3fe-167">• תצוגה משויכת של נתונים בפועל</span><span class="sxs-lookup"><span data-stu-id="4b3fe-167">• Actual Associated view</span></span>|

## <a name="set-up-bookable-resource-as-a-pricing-dimension"></a><span data-ttu-id="4b3fe-168">הגדרת משאב ניתן להזמנה כממד תמחור</span><span class="sxs-lookup"><span data-stu-id="4b3fe-168">Set up bookable resource as a pricing dimension</span></span>

1. <span data-ttu-id="4b3fe-169">בממשק האינטרנט, עבור אל **Project Service** > **הגדרות** > **פרמטרים**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-169">In the web interface, go to **Project Service** > **Settings** > **Parameters**.</span></span> <span data-ttu-id="4b3fe-170">בדף **פרמטר** , בכרטיסיה ‏‫ **ממדי תמחור מבוססי-כמות** , שים לב שהרשת בכרטיסיה מציגה את הרשומות בישות ממדי התמחור.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-170">On the **Parameter** page, on the **Amount-Based Pricing Dimensions** tab, notice that the grid on the tab shows the records in the pricing dimensions entity.</span></span> 
2. <span data-ttu-id="4b3fe-171">הוסף **משאב הניתן להזמנה** לרשימה זו של ממדי תמחור כ- **msdyn_bookableresource**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-171">Add **Bookable Resource** to this list of pricing dimensions as **msdyn_bookableresource**.</span></span> 
3. <span data-ttu-id="4b3fe-172">ציין את ההקשר שבו המשאב הניתן הזמנה פועל כממד תמחור והגדר את הערכים **חל על עלות** ו **חל על מכירות**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-172">Indicate the context in which the bookable resource works as a pricing dimension and set the **Applicable to cost** and **Applicable to sales** values.</span></span>
4. <span data-ttu-id="4b3fe-173">בשדה **סוג ממד** , בחר **מבוסס-סכום**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-173">In the **Dimension Type** field, select **Amount-based**.</span></span> 
5. <span data-ttu-id="4b3fe-174">בחר את עדיפות העלות והמכירות עבור המשאב הניתן להזמנה.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-174">Select the cost and sales priority for the bookable resource.</span></span> <span data-ttu-id="4b3fe-175">בדרך כלל, כאשר הוא כלול כממד תמחור, למשאב ניתן להזמנה יש את העדיפות הגבוהה ביותר כך שהגדרת הערך כ- **1** (או **0** בהתאם לאופן ספירת העדיפות) תבטיח אופן פעולה זה.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-175">Typically, when included as a pricing dimension, a bookable resource has the highest priority so setting this to **1** (or **0** depending on how you count the priority) would ensure that behavior.</span></span>

## <a name="set-up-pricing-dimension-field-names"></a><span data-ttu-id="4b3fe-176">הגדרת שמות שדה של ממד תמחור</span><span class="sxs-lookup"><span data-stu-id="4b3fe-176">Set up pricing dimension field names</span></span>

<span data-ttu-id="4b3fe-177">כאשר שם השדה של ממד התמחור בטבלה **מחיר תפקיד** שונה משם השדה שלו בכל ישות אחרת שבה ברירות מחדל של מחירים צריכות לפעול, צריך ליידע את רשומת ממד התמחור לגבי השמות השונים.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-177">When the field name of a pricing dimension in the **Role Price** table is different from its field name in any of the other entities where price defaulting needs to work, the pricing dimension record must be made aware of the different names.</span></span>    
<span data-ttu-id="4b3fe-178">עבור משאב ניתן להזמנה, לישות **חברי צוות של פרוייקט** יש שם שדה מעט שונה ( **msdyn_bookableresourceid** ) משמה בישות **מחיר תפקיד** ( **msdyn_bookableresource** ).</span><span class="sxs-lookup"><span data-stu-id="4b3fe-178">For bookable resource, the **Project Team Members** entity has a slightly different field name ( **msdyn_bookableresourceid** ) from what it is called on the **Role price** entity ( **msdyn_bookableresource** ).</span></span> <span data-ttu-id="4b3fe-179">רשומת ממד התמחור עבור **msydn_bookableresource** חייבת להיות מודעת לכך.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-179">The pricing dimension record for **msydn_bookableresource** must be made aware of this.</span></span> 
1. <span data-ttu-id="4b3fe-180">לשם כך, לחץ לחיצה כפולה על השורה ברשת **ממדי תמחור** כדי לפתוח את דף הממד של **msdyn_bookableresource**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-180">To do this, double-click the row in the **Pricing Dimensions** grid to open the dimension page of **msdyn_bookableresource**.</span></span>
2. <span data-ttu-id="4b3fe-181">בדף הממד, בכרטיסיה **קשור** , לחץ על **שמות של שדות ממדי התמחור**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-181">On dimension page, on the **Related** tab, click **Pricing Dimension Field Names**.</span></span>

 ![כרטיסיית שמות של שדה ממד תמחור](media/PD-fieldname.png)

4. <span data-ttu-id="4b3fe-183">בתצוגה המשויכת שנפתחת, לחץ על **הוסף שם שדה של ממד תמחור חדש**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-183">On the associated view that opens, click **Add New Pricing Dimension Field Name**.</span></span>

 ![הוספת שמות שדות של ממד תמחור חדש](media/Add-NewPD-fieldname.png)


<span data-ttu-id="4b3fe-185">פעולה זו פותחת את הדף **שם שדה של ממד תמחור חדש** עבור **msdyn_bookableresource**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-185">This opens the **New Pricing dimension field name** page for **msdyn_bookableresource**.</span></span> 

5. <span data-ttu-id="4b3fe-186">הוסף את **msdyn_projectteam** לשדה **שם לוגי של ישות** ואת **msdyn_bookableresourceid** לשדה **שם שדה**.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-186">Add **msdyn_projectteam** to the **Entity Locigal Name** field and **msdyn_bookableresourceid** to the **Field Name** field.</span></span> <span data-ttu-id="4b3fe-187">שמור את הרשומה.</span><span class="sxs-lookup"><span data-stu-id="4b3fe-187">Save the record.</span></span>

 ![טופס שם שדה של ממד תמחור חדש](media/PD-fieldname-Added.png)