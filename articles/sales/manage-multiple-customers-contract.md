---
title: ניהול לקוחות מרובים בחוזים של פרוייקט
description: נושא זה מספק מידע על הדרך לנהל לקוחות מרובים בחוזה פרויקט.
author: rumant
manager: Annbe
ms.date: 11/18/2020
ms.topic: article
ms.service: project-operations
ms.reviewer: kfend
ms.author: rumant
ms.openlocfilehash: 5554cb062710c3587d81b1a29771a7af84d2d05f
ms.sourcegitcommit: 573be7e36604ace82b35e439cfa748aa7c587415
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 11/25/2020
ms.locfileid: "4643173"
---
# <a name="manage-multiple-customers-on-project-contracts"></a><span data-ttu-id="420fb-103">ניהול לקוחות מרובים בחוזים של פרוייקט</span><span class="sxs-lookup"><span data-stu-id="420fb-103">Manage multiple customers on project contracts</span></span>

<span data-ttu-id="420fb-104">נושא זה מספק מידע על הדרך לנהל לקוחות מרובים בחוזה פרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-104">This topic provides information about how to manage multiple customers on a project contract.</span></span> <span data-ttu-id="420fb-105">אתה יכול להשתמש בחוזה פרויקט כאשר יש צורך בהסכם חוזי למספר לקוחות למימון עסקה.</span><span class="sxs-lookup"><span data-stu-id="420fb-105">You can use a project contract when a contractual agreement for multiple customers is needed for funding a deal.</span></span> <span data-ttu-id="420fb-106">בדף **חוזה פרויקט**, הכרטיסיה **סיכום** כוללת מידע על הלקוח העיקרי בעסקה.</span><span class="sxs-lookup"><span data-stu-id="420fb-106">On the **Project Contract** page, the **Summary** tab includes information about the primary customer for a deal.</span></span> <span data-ttu-id="420fb-107">ניתן להוסיף לקוחות אחרים שמשתתפים בעסקה בכרטיסיה **לקוחות**.</span><span class="sxs-lookup"><span data-stu-id="420fb-107">Other customers that participate in the deal can be added to the **Customers** tab.</span></span>

<span data-ttu-id="420fb-108">כל לקוחות החוזה בכרטיסיה **לקוחות** של הפרויקט משמשים, כברירת מחדל, כלקוחות סעיף חוזה בכל סעיף חוזה חדש שמבוסס על הפרויקט ונוצר עבור חוזה הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-108">All contract customers on the **Customers** tab of the project contract default as contract line customers on any new project-based contract lines created for the project contract.</span></span> <span data-ttu-id="420fb-109">כל סעיפי החוזה הקיימים המבוססים על הפרויקט אינם יורשים רשומות חדשות של לקוחות חוזה שנוצרות מאוחר יותר.</span><span class="sxs-lookup"><span data-stu-id="420fb-109">Any existing project-based contract lines don't inherit new contract customers records that are created at a later time.</span></span>

<span data-ttu-id="420fb-110">ניתן להוסיף, לעדכן או למחוק לקוחות חוזה ולקוחות סעיף חוזה בכל עת לפני הזכייה בחוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-110">You can add, update, or delete contract and contract line customers anytime before the contract is won.</span></span> <span data-ttu-id="420fb-111">לקוח בחוזה הפרויקט חייב להיות מוגדר כלקוח בחברה או בישות המשפטית שבבעלותו בדף **לקוחות**.</span><span class="sxs-lookup"><span data-stu-id="420fb-111">A customer on the project contract must be set up as a customer in the owning company or legal entity on the **Customers** page.</span></span> <span data-ttu-id="420fb-112">ישויות משפטיות מוקמות במודול **ניהול פרויקטים וחשבונאות** של Dynamics 365 Project Operations והן זמינות כחברות במודולים **מכירות פרויקטים** ו **מסירה** של Project Operations.</span><span class="sxs-lookup"><span data-stu-id="420fb-112">Legal entities are set up in the **Project management and accounting** module of Dynamics 365 Project Operations and are available as companies in the **Project Sales** and **Delivery** modules of Project Operations.</span></span>

## <a name="primary-customers"></a><span data-ttu-id="420fb-113">לקוחות ראשיים</span><span class="sxs-lookup"><span data-stu-id="420fb-113">Primary customers</span></span>

<span data-ttu-id="420fb-114">הלקוח הפוטנציאלי בכרטיסיה **סיכום** של חוזה הפרויקט הוא הלקוח העיקרי של החוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-114">The potential customer on the **Summary** tab of the project contract is the primary customer of the contract.</span></span> <span data-ttu-id="420fb-115">לא ניתן לעדכן את הלקוח הראשי מרשימת לקוחות החוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-115">You cannot update the primary customer from the contract customer's list.</span></span> <span data-ttu-id="420fb-116">אם מנסים למחוק את הלקוח הראשי מרשימת הלקוחות בחוזה, תתקבל הודעת שגיאה שלא ניתן למחוק רשומת לקוח ראשי בחוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-116">If you try to delete the primary customer from a customer list on contract, an error will occur that says a primary customer record on a contract can't be deleted.</span></span> <span data-ttu-id="420fb-117">במקום זאת, יש לשנות את הלקוח בשדה **לקוח פוטנציאלי** בכרטיסיה **סיכום** של חוזה הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-117">Instead, change the customer in the **Potential Customer** field on the **Summary** tab of the project contract.</span></span> <span data-ttu-id="420fb-118">כאשר מעדכנים את השדה, הלקוח שבוחרים נוסף כלקוח חוזה חדש והדגל **עיקרי** מוגדר **כן**.</span><span class="sxs-lookup"><span data-stu-id="420fb-118">When you update this field, the newly selected customer is added as a new contract customer with the **Primary** flag set to **Yes**.</span></span> <span data-ttu-id="420fb-119">הלקוח הראשי הקודם הוא עדיין לקוח בחוזה, אולם הם כבר אינם הלקוחות הראשיים.</span><span class="sxs-lookup"><span data-stu-id="420fb-119">The previous primary customer is still a customer on the contract, however they are no longer the primary customer.</span></span>

## <a name="create-update-or-delete-a-contract-customer-record"></a><span data-ttu-id="420fb-120">יצירה, עדכון או מחיקה של רשומת לקוח חוזה</span><span class="sxs-lookup"><span data-stu-id="420fb-120">Create, update, or delete a contract customer record</span></span>

<span data-ttu-id="420fb-121">ניתן ליצור, לעדכן או למחוק לקוח חוזה מהכרטיסיה **לקוחות בחוזה** בדף **חוזה**.</span><span class="sxs-lookup"><span data-stu-id="420fb-121">You can create, update, or delete a contract customer from the **Contract Customers** tab on the **Contract** page.</span></span> <span data-ttu-id="420fb-122">השדות הבאים כלולים ברשומת לקוח החוזה של חוזה פרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-122">The following fields are included on the contract customer record of a project contract.</span></span>

| <span data-ttu-id="420fb-123">**שדה**</span><span class="sxs-lookup"><span data-stu-id="420fb-123">**Field**</span></span> | <span data-ttu-id="420fb-124">**מיקום**</span><span class="sxs-lookup"><span data-stu-id="420fb-124">**Location**</span></span> | <span data-ttu-id="420fb-125">**תיאור**</span><span class="sxs-lookup"><span data-stu-id="420fb-125">**Description**</span></span> | 
| --- | --- | --- | 
| <span data-ttu-id="420fb-126">חשבון</span><span class="sxs-lookup"><span data-stu-id="420fb-126">Account</span></span> | <span data-ttu-id="420fb-127">רשת הניתנת לעריכה בכרטיסיה **לקוחות חוזה** ובדפים ליצירה וליצירה מהירה של לקוח חוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-127">Editable grid on the **Contract Customers** tab and the main and quick create pages for a contract customer.</span></span> | <span data-ttu-id="420fb-128">מכיל את כל תיקי הלקוח הפעילים.</span><span class="sxs-lookup"><span data-stu-id="420fb-128">Lists all the active accounts.</span></span> <span data-ttu-id="420fb-129">שדה זה ננעל לאחר יצירת הרשומה.</span><span class="sxs-lookup"><span data-stu-id="420fb-129">This field is locked after the record is created.</span></span> <span data-ttu-id="420fb-130">כדי לעדכן את הרשומה, עליך למחוק את הרשומה וליצור אותה מחדש.</span><span class="sxs-lookup"><span data-stu-id="420fb-130">To update the record, you have to delete it and then re-create it.</span></span> <span data-ttu-id="420fb-131">אם תיעדת נתונים בפועל כלשהם, או אם רשומת לקוח החוזה היא לקוח ראשי, לא ניתן למחוק את הרשומה.</span><span class="sxs-lookup"><span data-stu-id="420fb-131">If you have recorded any actuals, or if the contract customer record is a primary customer, you can't delete the record.</span></span> <span data-ttu-id="420fb-132">כאשר יוצרים סעיף חוזה, לקוחות חוזה מועתקים כלקוחות סעיף חוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-132">When a contract line is created, contract customers are copied as contract line customers.</span></span> |
| <span data-ttu-id="420fb-133">אחוז פיצול חיוב</span><span class="sxs-lookup"><span data-stu-id="420fb-133">Billing Split Percent</span></span> | <span data-ttu-id="420fb-134">רשת הניתנת לעריכה בכרטיסיה **לקוחות חוזה** ובדפים ליצירה וליצירה מהירה של לקוח חוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-134">Editable grid on the **Contract Customers** tab and the main and quick create pages for a contract customer.</span></span> | <span data-ttu-id="420fb-135">מייצג את האחוז מכל עסקת מכירה שלא חויב שייזקף לחובת לקוח חוזה זה.</span><span class="sxs-lookup"><span data-stu-id="420fb-135">Represents the percentage of each unbilled sales transaction attributed to the contract customer.</span></span> <span data-ttu-id="420fb-136">כאשר נוצרים סעיפי חוזה חדשים של פרויקט, אחוז הפיצול לחיוב מועתק לכל סעיפי החוזה החדשים שנוצרו וללקוחות של סעיף החוזה בפרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-136">When new project contract lines are created, the billing split percent is copied to new any contract lines created and to project contract line customers.</span></span> |
| <span data-ttu-id="420fb-137">שם איש קשר לחיוב</span><span class="sxs-lookup"><span data-stu-id="420fb-137">Bill to Contact Name</span></span> | <span data-ttu-id="420fb-138">רשת הניתנת לעריכה בכרטיסיה **לקוחות חוזה** ובדפים ליצירה וליצירה מהירה של לקוח חוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-138">Editable grid on the **Contract Customers** tab and the main and quick create pages for a contract customer.</span></span> | <span data-ttu-id="420fb-139">יש להשתמש בשדה טקסט זה לזיהוי איש הקשר של החשבונית עבור הלקוח.</span><span class="sxs-lookup"><span data-stu-id="420fb-139">This text field should be used to identify the invoice contact person for the customer.</span></span> <span data-ttu-id="420fb-140">הערך שמוגדר כברירת המחדל מרשומת תיק הלקוח הקשור.</span><span class="sxs-lookup"><span data-stu-id="420fb-140">The default value comes from the related account record.</span></span> <span data-ttu-id="420fb-141">שם החוזה מועתק אל **חיוב לשם חוזה** בחשבונית שנוצרת עבור לקוח זה.</span><span class="sxs-lookup"><span data-stu-id="420fb-141">The contact name is copied to **Bill to Contract Name** on the invoice generated for the customer.</span></span> |
| <span data-ttu-id="420fb-142">שם לחיוב</span><span class="sxs-lookup"><span data-stu-id="420fb-142">Bill To Name</span></span> | <span data-ttu-id="420fb-143">רשת הניתנת לעריכה בכרטיסיה **לקוחות חוזה** ובדפים ליצירה וליצירה מהירה של לקוח חוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-143">Editable grid on the **Contract Customers** tab and the main and quick create pages for a contract customer.</span></span> | <span data-ttu-id="420fb-144">יש להשתמש בשדה זה לזיהוי איש הקשר של החשבונית עבור הלקוח.</span><span class="sxs-lookup"><span data-stu-id="420fb-144">Use this field to identify the invoice contact person for the customer.</span></span> <span data-ttu-id="420fb-145">הערך שמוגדר כברירת המחדל מרשומת תיק הלקוח הקשור.</span><span class="sxs-lookup"><span data-stu-id="420fb-145">The default value comes from the related account record.</span></span> <span data-ttu-id="420fb-146">השם מועתק לשדה **חיוב לשם חוזה** בחשבונית שנוצרת עבור הלקוח.</span><span class="sxs-lookup"><span data-stu-id="420fb-146">The name is copied to the **Bill to Contract Name** field on the invoice generated for the customer.</span></span> |
| <span data-ttu-id="420fb-147">‏‫תנאי תשלום‬</span><span class="sxs-lookup"><span data-stu-id="420fb-147">Payment Terms</span></span> | <span data-ttu-id="420fb-148">רשת הניתנת לעריכה בכרטיסיה **לקוחות חוזה** ובדפים ליצירה וליצירה מהירה של לקוח חוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-148">Editable grid on the **Contract Customers** tab and main and quick create pages for a contract customer.</span></span> | <span data-ttu-id="420fb-149">הערך שמוגדר כברירת המחדל מרשומת תיק הלקוח הקשור.</span><span class="sxs-lookup"><span data-stu-id="420fb-149">The default value comes from the related account record.</span></span> <span data-ttu-id="420fb-150">התנאים מועתקים אל **חיוב לשם חוזה** בחשבונית שנוצרת עבור לקוח זה.</span><span class="sxs-lookup"><span data-stu-id="420fb-150">The terms are copied over to **Bill to Contract Name** on the invoice generated for the customer.</span></span> |
| <span data-ttu-id="420fb-151">החברה המהווה בעלים</span><span class="sxs-lookup"><span data-stu-id="420fb-151">Owning Company</span></span> | <span data-ttu-id="420fb-152">רשת הניתנת לעריכה בכרטיסיה **לקוחות חוזה בפרויקט** ובדפים ליצירה וליצירה מהירה של לקוח חוזה בפרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-152">Editable grid on the **Project Contract Customers** tab and the main and quick create pages for a project contract customer.</span></span> | <span data-ttu-id="420fb-153">הישות המשפטית שבה מוגדר הלקוח במודול **ניהול פרויקטים וחשבונאות**.</span><span class="sxs-lookup"><span data-stu-id="420fb-153">The legal entity in which the customer is set up in the **Project management and accounting** module.</span></span> <span data-ttu-id="420fb-154">שדה זה מוגדר לקריאה בלבד ומוגדר לחברה המהווה בעלים של חוזה הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-154">This field is read-only and set to the owning company of the project contract.</span></span></br><span data-ttu-id="420fb-155">רשימת הלקוחות להוספה בשדה **תיק לקוח** כבר מסונן לרשימה מחברת הבעלות במודול **ניהול פרויקטים וחשבונאות** של Project Operations.</span><span class="sxs-lookup"><span data-stu-id="420fb-155">The list of customers to add in the **Account** field is already filtered to the list from the owning company in the **Project management and accounting** module of Project Operations.</span></span> <span data-ttu-id="420fb-156">החברה המחזיקה שווה ליישות המשפטית במודול **ניהול פרויקטים וחשבונאות** של Project Operations.</span><span class="sxs-lookup"><span data-stu-id="420fb-156">The owning company is equal to the legal entity in the **Project management and accounting** module of Project Operations.</span></span> <span data-ttu-id="420fb-157">כל העלויות וההכנסות הנובעות מהפרויקט מתועדות בספר החשבונות הראשי של החברה המהווה בעלים.</span><span class="sxs-lookup"><span data-stu-id="420fb-157">All costs and revenue accruing from the project are accounted for in the general ledger of the owning company.</span></span> |
| <span data-ttu-id="420fb-158">הוא עיגול</span><span class="sxs-lookup"><span data-stu-id="420fb-158">Is Rounding</span></span> | <span data-ttu-id="420fb-159">רשת הניתנת לעריכה בכרטיסיה **לקוחות חוזה** ובדפים ליצירה וליצירה מהירה של לקוח חוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-159">Editable grid on the **Contract Customers** tab and the main and quick create pages for a contract customer.</span></span> | <span data-ttu-id="420fb-160">מציין אם הלקוח הוא לקוח עיגול ברירת מחדל לעסקה.</span><span class="sxs-lookup"><span data-stu-id="420fb-160">Indicates if the customer is a default rounding customer for the deal.</span></span> <span data-ttu-id="420fb-161">יכול להיות שיש רק לקוח עיגול אחד בחוזה פרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-161">There can only be one rounding customer on a project contract.</span></span> <span data-ttu-id="420fb-162">כאשר העלות והמכירות שלא חויבו מפוצלות לפי כמות מובילות להפרש בעיגול, הפרש זה מוחל על הנתון בפועל הממפה ללקוח.</span><span class="sxs-lookup"><span data-stu-id="420fb-162">When cost and unbilled sales split on quantity and lead to a rounding difference, that difference is applied to the actual that maps to the customer.</span></span> |
| <span data-ttu-id="420fb-163">מגבלת 'אין לחרוג'</span><span class="sxs-lookup"><span data-stu-id="420fb-163">Not-to-exceed Limit</span></span> | <span data-ttu-id="420fb-164">רשת הניתנת לעריכה בכרטיסיה **לקוחות חוזה** ובדפים ליצירה וליצירה מהירה של לקוח חוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-164">Editable grid on the **Contract Customers** tab and the main and quick create pages for a contract customer.</span></span> | <span data-ttu-id="420fb-165">מציין אם הוסכם על מגבלה או תקרת לסכום הכולל שבו יחויב לקוח זה עבור המעורבות.</span><span class="sxs-lookup"><span data-stu-id="420fb-165">Indicates if there is a negotiated limit or cap to the overall amount that will be invoiced to the customer for the engagement.</span></span> <span data-ttu-id="420fb-166">ההערכה של מגבלת החריגה שהוגדרה ברמת לקוח החוזה מבוססת על נתונים בפועל של מכירות שלא חיובו שמפנות ללקוח החוזה.</span><span class="sxs-lookup"><span data-stu-id="420fb-166">The not-to-exceed limit set up at the contract customer level is evaluated based on unbilled sales actuals that reference the contract customer.</span></span> |

## <a name="edit-billing-split-percentages"></a><span data-ttu-id="420fb-167">עריכת אחוזי פיצול חיוב</span><span class="sxs-lookup"><span data-stu-id="420fb-167">Edit billing split percentages</span></span>

<span data-ttu-id="420fb-168">ניתן לערוך את אחוזי פיצול החיובים על ידי עריכת הרשת.</span><span class="sxs-lookup"><span data-stu-id="420fb-168">You can edit billing split percentages by editing in the grid.</span></span> <span data-ttu-id="420fb-169">כאשר אחוזי פיצול החיוב אינם מסתכמים כ-100 אחוז, זוהי שגיאה.</span><span class="sxs-lookup"><span data-stu-id="420fb-169">When billing split percentages don't total 100 percent, an error occurs.</span></span> <span data-ttu-id="420fb-170">לאחר עריכת אחוז הפיצול לחיוב, יש לרענן את הדף **חוזה פרויקט** כדי להסיר את השגיאה.</span><span class="sxs-lookup"><span data-stu-id="420fb-170">After you edit a billing split percentage, refresh the **Project Contract** page to remove the error.</span></span>

<span data-ttu-id="420fb-171">ניתן גם לבחור **חלק באופן שווה** ברשת-המשנה של לקוחות חוזה בפרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-171">You can also select **Evenly Distribute** on the project contract customers subgrid.</span></span> <span data-ttu-id="420fb-172">פיצול החיוב מבוצע בצורה שווה בין כל הלקוחות בחוזה הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="420fb-172">Billing splits are evenly allocated to all of the customers on the project contract.</span></span> <span data-ttu-id="420fb-173">אם יש גורם עיגול כלשהו, הוא יתווסף ללקוח העיגול.</span><span class="sxs-lookup"><span data-stu-id="420fb-173">If there is any rounding factor, the factor will be added to the rounding customer.</span></span> <span data-ttu-id="420fb-174">לאחד מלקוחות החוזה הדגל **עיגול** תמיד מוגדר **כן**.</span><span class="sxs-lookup"><span data-stu-id="420fb-174">One of the contract customers always has the **Rounding** flag set to **Yes**.</span></span> <span data-ttu-id="420fb-175">אותו לקוח הוא הלקוח המעוגל.</span><span class="sxs-lookup"><span data-stu-id="420fb-175">That customer is the rounding customer.</span></span> <span data-ttu-id="420fb-176">בדרך כלל, לקוח העיגול הוא גם הלקוח העיקרי של החוזה, אך זה לא נדרש.</span><span class="sxs-lookup"><span data-stu-id="420fb-176">Typically, the rounding customer is also the primary customer of the contract, but that isn't required.</span></span>