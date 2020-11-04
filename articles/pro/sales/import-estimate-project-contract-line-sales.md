---
title: ייבוא הערכה לסעיף חוזה מבוסס פרוייקט
description: נושא זה מספק מידע על ייבוא הערכות פיננסיות מפרויקט לסעיף חוזה.
author: rumant
manager: Annbe
ms.date: 10/19/2020
ms.topic: article
ms.service: dynamics-365-customerservice
ms.reviewer: kfend
ms.author: rumant
ms.openlocfilehash: 9ac367baba4529e86a42d812b7d9b2550812e297
ms.sourcegitcommit: 3a0c18823a7ad23df5aa3de272779313abe56c82
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/20/2020
ms.locfileid: "4077541"
---
# <a name="importing-an-estimate-to-a-project-based-contract-line"></a><span data-ttu-id="f59f3-103">ייבוא הערכה לסעיף חוזה מבוסס פרוייקט</span><span class="sxs-lookup"><span data-stu-id="f59f3-103">Importing an estimate to a project-based contract line</span></span>

<span data-ttu-id="f59f3-104">_**חל על** : פריסה בגרסת לייט – מהעסקה ועד להוצאת חשבונית פרופורמה_</span><span class="sxs-lookup"><span data-stu-id="f59f3-104">_**Applies To:** Lite deployment - deal to proforma invoicing_</span></span>

<span data-ttu-id="f59f3-105">ב-Dynamics 365 Project Operations, ניתן לייבא הערכות מפרויקט לסעיף חוזה מבוסס פרויקט.</span><span class="sxs-lookup"><span data-stu-id="f59f3-105">In Dynamics 365 Project Operations, you can import estimates from a project to a project-based contract line.</span></span>

1. <span data-ttu-id="f59f3-106">ודא שהשדה **פרויקט**  בסעיף חוזה מבוסס פרויקט הושלם.</span><span class="sxs-lookup"><span data-stu-id="f59f3-106">Verify that the **Project** field on the project-based contract line has been filled in.</span></span>
2. <span data-ttu-id="f59f3-107">בכרטיסיה **פרטי שורת הצעת מחיר** , ברשת המשנה, בחר **ייבא מהערכת פרוייקט**.</span><span class="sxs-lookup"><span data-stu-id="f59f3-107">On the **Contract Line Details** tab, on the subgrid, select **Import from Project Estimation**.</span></span> <span data-ttu-id="f59f3-108">דף שיח עם אפשרויות סיכום נפתח.</span><span class="sxs-lookup"><span data-stu-id="f59f3-108">A dialog page with summarization options opens.</span></span> <span data-ttu-id="f59f3-109">אפשרויות הסיכום ה זמינות הן **סיווג עסקה** , **קטגוריה** , **תפקיד** , ו **משימת הפרויקט**.</span><span class="sxs-lookup"><span data-stu-id="f59f3-109">Summarization options available are **Transaction Class** , **Category** , **Role** , and **Project Task**.</span></span>
3. <span data-ttu-id="f59f3-110">על סמך בחירת הסיכום, ההערכה מהפרויקט עבור כל הסיווגים והמשימות של העסקאות הכלולות בסעיף חוזה זה מועתקת.</span><span class="sxs-lookup"><span data-stu-id="f59f3-110">Based on the summary selection, the estimate from the project for all the transaction classes and tasks included on this contract line are copied.</span></span> <span data-ttu-id="f59f3-111">כדי לבדוק אילו סיווגי עסקאות כלולות, בחר בכרטיסיה **כללי** בסעיף החוזה מבוסס הפרויקט, ובדוק את הערכים בשדות **כלול זמן** , **כלול הוצאות** , ו **כלול עמלות**.</span><span class="sxs-lookup"><span data-stu-id="f59f3-111">To check what transaction classes are included, on the **General** tab on the project-based contract line, check the values in the **Include Time** , **Include Expenses** , and **Include Fees** fields.</span></span> 
4. <span data-ttu-id="f59f3-112">כדי לראות אילו משימות כלולות, בחר בכרטיסיה **משימות הניתנות לחיוב** בסעיף החוזה.</span><span class="sxs-lookup"><span data-stu-id="f59f3-112">To see what tasks are included, select the **Chargeable Tasks** tab on the contract line.</span></span> <span data-ttu-id="f59f3-113">בהתבסס על המשימות המשויכות שבהם השדה **סיווגי עסקאות כלולים** מוגדר כ **כן** , כל ההערכות עובר אותם שילובים של סיווגי משימות ועסקאות מיובאים לסעיף החוזה.</span><span class="sxs-lookup"><span data-stu-id="f59f3-113">Based on the associated tasks that have the field **Included Transaction Classes** set to **Yes** , all estimates for those task and transaction class combinations are imported to the contract line.</span></span>

<span data-ttu-id="f59f3-114">כשמייביאם הערכות, המערכת תגדיר תמחור ברירת המחדל בהתבסס על מחירוני הפרויקט המצורפים לחוזה וסוג החיוב שהוגדר בסעיף החוזה.</span><span class="sxs-lookup"><span data-stu-id="f59f3-114">When you import estimates, the system defaults pricing based on the project price lists attached to the contract and billing type setup on the contract line.</span></span> <span data-ttu-id="f59f3-115">אם משימה, תפקיד או קטגוריה מוגדרים בסעיף חוזה מבוסס פרויקט כבלתי ניתנים לחיוב, שורת ההערכה המיובאת תוגדר כבלתי ניתנת לחיוב ולא תתווסף לערך שעליו סוכם בסעיף החוזה.</span><span class="sxs-lookup"><span data-stu-id="f59f3-115">If a task, role, or category is set up on the contract line as non-chargeable, the imported estimate line will be non-chargeable and will not add up to the contracted value of the contract line.</span></span>

<span data-ttu-id="f59f3-116">כאשר קיימים פרטי שורה בסעיף חוזה, השדות **ערך חוזה** ו **מס משוער** בסעיף החוזה מסוכמים ואינם ניתנים לעריכה.</span><span class="sxs-lookup"><span data-stu-id="f59f3-116">When a contract line has line details, the **Contract Value** and **Estimated Tax** fields on the contract line are summarized and can't be edited.</span></span>

<span data-ttu-id="f59f3-117">כאשר נבחרות אפשרויות סיכום מרובות, המערכת מנסה לסכם לפי כל האפשרויות שנבחרו.</span><span class="sxs-lookup"><span data-stu-id="f59f3-117">When multiple summarization options are selected, the system attempts to summarize by all of the selected options.</span></span> <span data-ttu-id="f59f3-118">פלט הסיכום מביאה לסעיפי חוזה מיובאים מרובים יותר מאשר בחירה באפשרות סיכום אחת בלבד.</span><span class="sxs-lookup"><span data-stu-id="f59f3-118">The summarization output results in more imported contract lines than if you select only one summarization option.</span></span>

<span data-ttu-id="f59f3-119">לדוגמה, אם בפרויקט קיימות שורות ההערכה הבאות להוצאות:</span><span class="sxs-lookup"><span data-stu-id="f59f3-119">For example, if the project has the following estimate lines for expenses:</span></span>

| <span data-ttu-id="f59f3-120">משימה</span><span class="sxs-lookup"><span data-stu-id="f59f3-120">Task</span></span> | <span data-ttu-id="f59f3-121">קטגוריה</span><span class="sxs-lookup"><span data-stu-id="f59f3-121">Category</span></span> | <span data-ttu-id="f59f3-122">תאריך</span><span class="sxs-lookup"><span data-stu-id="f59f3-122">Date</span></span> | <span data-ttu-id="f59f3-123">כמות</span><span class="sxs-lookup"><span data-stu-id="f59f3-123">Quantity</span></span> | <span data-ttu-id="f59f3-124">מחיר יחידה</span><span class="sxs-lookup"><span data-stu-id="f59f3-124">Unit price</span></span> | <span data-ttu-id="f59f3-125">סכום</span><span class="sxs-lookup"><span data-stu-id="f59f3-125">Amount</span></span> |
| --- | --- | --- | --- | --- | --- |
| <span data-ttu-id="f59f3-126">משימה א'</span><span class="sxs-lookup"><span data-stu-id="f59f3-126">Task A</span></span> | <span data-ttu-id="f59f3-127">טיסות</span><span class="sxs-lookup"><span data-stu-id="f59f3-127">Airfare</span></span> | <span data-ttu-id="f59f3-128">1/10/2020</span><span class="sxs-lookup"><span data-stu-id="f59f3-128">10/1/2020</span></span> | <span data-ttu-id="f59f3-129">4</span><span class="sxs-lookup"><span data-stu-id="f59f3-129">4</span></span> | <span data-ttu-id="f59f3-130">400</span><span class="sxs-lookup"><span data-stu-id="f59f3-130">400</span></span> | <span data-ttu-id="f59f3-131">1600</span><span class="sxs-lookup"><span data-stu-id="f59f3-131">1600</span></span> |
| <span data-ttu-id="f59f3-132">משימה ב'</span><span class="sxs-lookup"><span data-stu-id="f59f3-132">Task B</span></span> | <span data-ttu-id="f59f3-133">בתי מלון</span><span class="sxs-lookup"><span data-stu-id="f59f3-133">Hotel</span></span> | <span data-ttu-id="f59f3-134">1/10/2020</span><span class="sxs-lookup"><span data-stu-id="f59f3-134">10/1/2020</span></span> | <span data-ttu-id="f59f3-135">4</span><span class="sxs-lookup"><span data-stu-id="f59f3-135">4</span></span> | <span data-ttu-id="f59f3-136">200</span><span class="sxs-lookup"><span data-stu-id="f59f3-136">200</span></span> | <span data-ttu-id="f59f3-137">800</span><span class="sxs-lookup"><span data-stu-id="f59f3-137">800</span></span> |
| <span data-ttu-id="f59f3-138">משימה ג'</span><span class="sxs-lookup"><span data-stu-id="f59f3-138">Task C</span></span> | <span data-ttu-id="f59f3-139">בתי מלון</span><span class="sxs-lookup"><span data-stu-id="f59f3-139">Hotel</span></span> | <span data-ttu-id="f59f3-140">1/11/2020</span><span class="sxs-lookup"><span data-stu-id="f59f3-140">11/1/2020</span></span> | <span data-ttu-id="f59f3-141">2</span><span class="sxs-lookup"><span data-stu-id="f59f3-141">2</span></span> | <span data-ttu-id="f59f3-142">200</span><span class="sxs-lookup"><span data-stu-id="f59f3-142">200</span></span> | <span data-ttu-id="f59f3-143">400</span><span class="sxs-lookup"><span data-stu-id="f59f3-143">400</span></span> |

<span data-ttu-id="f59f3-144">כאשר המשתמש בוחר לסכם לפי **סיווג עסקה** , המידע הבא ייובא.</span><span class="sxs-lookup"><span data-stu-id="f59f3-144">When the user selects to summarize by **Transaction Class** , the following information will be imported:</span></span>

| <span data-ttu-id="f59f3-145">משימה</span><span class="sxs-lookup"><span data-stu-id="f59f3-145">Task</span></span> | <span data-ttu-id="f59f3-146">קטגוריה</span><span class="sxs-lookup"><span data-stu-id="f59f3-146">Category</span></span> | <span data-ttu-id="f59f3-147">תאריך</span><span class="sxs-lookup"><span data-stu-id="f59f3-147">Date</span></span> | <span data-ttu-id="f59f3-148">כמות</span><span class="sxs-lookup"><span data-stu-id="f59f3-148">Quantity</span></span> | <span data-ttu-id="f59f3-149">מחיר יחידה</span><span class="sxs-lookup"><span data-stu-id="f59f3-149">Unit price</span></span> | <span data-ttu-id="f59f3-150">סכום</span><span class="sxs-lookup"><span data-stu-id="f59f3-150">Amount</span></span> |
| --- | --- | --- | --- | --- | --- |
| &nbsp; | &nbsp; | <span data-ttu-id="f59f3-151">1/10/2020</span><span class="sxs-lookup"><span data-stu-id="f59f3-151">10/1/2020</span></span> | <span data-ttu-id="f59f3-152">3.34</span><span class="sxs-lookup"><span data-stu-id="f59f3-152">3.34</span></span> | <span data-ttu-id="f59f3-153">840</span><span class="sxs-lookup"><span data-stu-id="f59f3-153">840</span></span> | <span data-ttu-id="f59f3-154">2800</span><span class="sxs-lookup"><span data-stu-id="f59f3-154">2800</span></span> |

<span data-ttu-id="f59f3-155">כאשר המשתמש בוחר לסכם לפי **סיווג עסקה** ו **קטגוריה** , המידע הבא ייובא:</span><span class="sxs-lookup"><span data-stu-id="f59f3-155">When the user selects to summarize by **Transaction Class** and **Category** , the following information will be imported:</span></span>

| <span data-ttu-id="f59f3-156">משימה</span><span class="sxs-lookup"><span data-stu-id="f59f3-156">Task</span></span> | <span data-ttu-id="f59f3-157">קטגוריה</span><span class="sxs-lookup"><span data-stu-id="f59f3-157">Category</span></span> | <span data-ttu-id="f59f3-158">תאריך</span><span class="sxs-lookup"><span data-stu-id="f59f3-158">Date</span></span> | <span data-ttu-id="f59f3-159">כמות</span><span class="sxs-lookup"><span data-stu-id="f59f3-159">Quantity</span></span> | <span data-ttu-id="f59f3-160">מחיר יחידה</span><span class="sxs-lookup"><span data-stu-id="f59f3-160">Unit price</span></span> | <span data-ttu-id="f59f3-161">סכום</span><span class="sxs-lookup"><span data-stu-id="f59f3-161">Amount</span></span> |
| --- | --- | --- | --- | --- | --- |
| <span data-ttu-id="f59f3-162">משימה א'</span><span class="sxs-lookup"><span data-stu-id="f59f3-162">Task A</span></span> | <span data-ttu-id="f59f3-163">טיסות</span><span class="sxs-lookup"><span data-stu-id="f59f3-163">Airfare</span></span> | <span data-ttu-id="f59f3-164">1/10/2020</span><span class="sxs-lookup"><span data-stu-id="f59f3-164">10/1/2020</span></span> | <span data-ttu-id="f59f3-165">4</span><span class="sxs-lookup"><span data-stu-id="f59f3-165">4</span></span> | <span data-ttu-id="f59f3-166">400</span><span class="sxs-lookup"><span data-stu-id="f59f3-166">400</span></span> | <span data-ttu-id="f59f3-167">1600</span><span class="sxs-lookup"><span data-stu-id="f59f3-167">1600</span></span> |
| &nbsp;| <span data-ttu-id="f59f3-168">בתי מלון</span><span class="sxs-lookup"><span data-stu-id="f59f3-168">Hotel</span></span> | <span data-ttu-id="f59f3-169">1/10/2020</span><span class="sxs-lookup"><span data-stu-id="f59f3-169">10/1/2020</span></span> | <span data-ttu-id="f59f3-170">6</span><span class="sxs-lookup"><span data-stu-id="f59f3-170">6</span></span> | <span data-ttu-id="f59f3-171">200</span><span class="sxs-lookup"><span data-stu-id="f59f3-171">200</span></span> | <span data-ttu-id="f59f3-172">1200</span><span class="sxs-lookup"><span data-stu-id="f59f3-172">1200</span></span> |

<span data-ttu-id="f59f3-173">כאשר המשתמש בוחר לסכם לפי **סיווג עסקה** , **קטגוריה** ו **משימת צומת עלה** , המידע הבא ייובא.</span><span class="sxs-lookup"><span data-stu-id="f59f3-173">When the user selects to summarize by **Transaction Class** , **Category** , and **Leaf Node Task** , the following will be imported.</span></span> <span data-ttu-id="f59f3-174">שימו לב שתוצאה זו זהה למה שהיה בפרויקט:</span><span class="sxs-lookup"><span data-stu-id="f59f3-174">Notice that this result is the same as what is on the project:</span></span>

| <span data-ttu-id="f59f3-175">משימה</span><span class="sxs-lookup"><span data-stu-id="f59f3-175">Task</span></span> | <span data-ttu-id="f59f3-176">קטגוריה</span><span class="sxs-lookup"><span data-stu-id="f59f3-176">Category</span></span> | <span data-ttu-id="f59f3-177">תאריך</span><span class="sxs-lookup"><span data-stu-id="f59f3-177">Date</span></span> | <span data-ttu-id="f59f3-178">כמות</span><span class="sxs-lookup"><span data-stu-id="f59f3-178">Quantity</span></span> | <span data-ttu-id="f59f3-179">מחיר יחידה</span><span class="sxs-lookup"><span data-stu-id="f59f3-179">Unit price</span></span> | <span data-ttu-id="f59f3-180">סכום</span><span class="sxs-lookup"><span data-stu-id="f59f3-180">Amount</span></span> |
| --- | --- | --- | --- | --- | --- |
| <span data-ttu-id="f59f3-181">משימה א'</span><span class="sxs-lookup"><span data-stu-id="f59f3-181">Task A</span></span> | <span data-ttu-id="f59f3-182">טיסות</span><span class="sxs-lookup"><span data-stu-id="f59f3-182">Airfare</span></span> | <span data-ttu-id="f59f3-183">1/10/2020</span><span class="sxs-lookup"><span data-stu-id="f59f3-183">10/1/2020</span></span> | <span data-ttu-id="f59f3-184">4</span><span class="sxs-lookup"><span data-stu-id="f59f3-184">4</span></span> | <span data-ttu-id="f59f3-185">400</span><span class="sxs-lookup"><span data-stu-id="f59f3-185">400</span></span> | <span data-ttu-id="f59f3-186">1600</span><span class="sxs-lookup"><span data-stu-id="f59f3-186">1600</span></span> |
| <span data-ttu-id="f59f3-187">משימה ב'</span><span class="sxs-lookup"><span data-stu-id="f59f3-187">Task B</span></span> | <span data-ttu-id="f59f3-188">בתי מלון</span><span class="sxs-lookup"><span data-stu-id="f59f3-188">Hotel</span></span> | <span data-ttu-id="f59f3-189">1/10/2020</span><span class="sxs-lookup"><span data-stu-id="f59f3-189">10/1/2020</span></span> | <span data-ttu-id="f59f3-190">4</span><span class="sxs-lookup"><span data-stu-id="f59f3-190">4</span></span> | <span data-ttu-id="f59f3-191">200</span><span class="sxs-lookup"><span data-stu-id="f59f3-191">200</span></span> | <span data-ttu-id="f59f3-192">800</span><span class="sxs-lookup"><span data-stu-id="f59f3-192">800</span></span> |
| <span data-ttu-id="f59f3-193">משימה ג'</span><span class="sxs-lookup"><span data-stu-id="f59f3-193">Task C</span></span> | <span data-ttu-id="f59f3-194">בתי מלון</span><span class="sxs-lookup"><span data-stu-id="f59f3-194">Hotel</span></span> | <span data-ttu-id="f59f3-195">1/11/2020</span><span class="sxs-lookup"><span data-stu-id="f59f3-195">11/1/2020</span></span> | <span data-ttu-id="f59f3-196">2</span><span class="sxs-lookup"><span data-stu-id="f59f3-196">2</span></span> | <span data-ttu-id="f59f3-197">200</span><span class="sxs-lookup"><span data-stu-id="f59f3-197">200</span></span> | <span data-ttu-id="f59f3-198">400</span><span class="sxs-lookup"><span data-stu-id="f59f3-198">400</span></span> |