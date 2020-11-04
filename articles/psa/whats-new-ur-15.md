---
title: מה חדש או שונה במהדורה המעודכנת של Project Service Automation, 15 V3
description: נושא זה מספק מידע על מה חדש בעדכון המהדורה 15, V3 של Project Service Automation.
author: ruhercul
manager: kfend
ms.service: dynamics-365-customerservice
ms.custom: dyn365-projectservice
ms.date: 01/27/2020
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
ms.openlocfilehash: 6112e4874025e528a2bb583cf215fd9eff681534
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077265"
---
# <a name="project-service-automation-update-release-15-v3"></a><span data-ttu-id="fb070-103">מהדורה 15, V3 של Project Service Automation</span><span class="sxs-lookup"><span data-stu-id="fb070-103">Project Service Automation Update Release 15, V3</span></span>

<span data-ttu-id="fb070-104">אנו שמחים להכריז על העדכון האחרון עבור יישום Dynamics 365 Project Service Automation‏ (PSA).</span><span class="sxs-lookup"><span data-stu-id="fb070-104">We’re pleased to announce the latest update for the Dynamics 365 Project Service Automation (PSA) application.</span></span> <span data-ttu-id="fb070-105">מהדורה זו כוללת כמה שיפורים חשובים באיכות, בביצועים ובשימושיות.</span><span class="sxs-lookup"><span data-stu-id="fb070-105">This release includes some important improvements to quality, performance, and usability.</span></span> <span data-ttu-id="fb070-106">מהדורה זו תואמת את Dynamics 365 9.x.</span><span class="sxs-lookup"><span data-stu-id="fb070-106">This release is compatible with Dynamics 365 9.x.</span></span> <span data-ttu-id="fb070-107">כדי לעדכן למהדורה זו, בקר במרכז הניהול של Dynamics 365 ועבור לדף הפתרונות כדי להתקין את העדכון.</span><span class="sxs-lookup"><span data-stu-id="fb070-107">To update to this release, visit the Admin Center for Dynamics 365 online, and go to the solutions page to install the update.</span></span> <span data-ttu-id="fb070-108">למידע נוסף: [התקנה, עדכון או הסרה של פתרון מועדף](https://docs.microsoft.com/power-platform/admin/install-remove-preferred-solution).</span><span class="sxs-lookup"><span data-stu-id="fb070-108">For more information, see [Install, update, or remove a preferred solution](https://docs.microsoft.com/power-platform/admin/install-remove-preferred-solution).</span></span>

<span data-ttu-id="fb070-109">נושא זה מפרט את התכונות והתיקונים החדשים או ששונו עבור מהדורה 15, עדכון V3 של PSA.</span><span class="sxs-lookup"><span data-stu-id="fb070-109">This topic lists the features and fixes that are new or changed for PSA V3, Update Release 15.</span></span> <span data-ttu-id="fb070-110">מספר ה-build של גירסה זו הוא V3.10.5.28 והיא זמינה דרך עדכון עצמי החל מינואר 2020.</span><span class="sxs-lookup"><span data-stu-id="fb070-110">This version has a build number of V3.10.5.28 and is generally available through a self-update in January 2020.</span></span>

## <a name="update-release-15"></a><span data-ttu-id="fb070-111">הפצת עדכון 15</span><span class="sxs-lookup"><span data-stu-id="fb070-111">Update Release 15</span></span> 

### <a name="enhancements"></a><span data-ttu-id="fb070-112">שיפורים</span><span class="sxs-lookup"><span data-stu-id="fb070-112">Enhancements</span></span>

- <span data-ttu-id="fb070-113">ניהול פרויקט</span><span class="sxs-lookup"><span data-stu-id="fb070-113">Project Management</span></span>

### <a name="bug-fixes"></a><span data-ttu-id="fb070-114">תיקוני באגים</span><span class="sxs-lookup"><span data-stu-id="fb070-114">Bug fixes</span></span>

- <span data-ttu-id="fb070-115">זמן והוצאה</span><span class="sxs-lookup"><span data-stu-id="fb070-115">Time and Expense</span></span>

  - <span data-ttu-id="fb070-116">תוקן: נוסף טיפול בשגיאות בעומס בתצוגת ההתאמה.</span><span class="sxs-lookup"><span data-stu-id="fb070-116">Fixed: Add on-load error handling in the reconciliation view.</span></span>
  - <span data-ttu-id="fb070-117">תוקן: מרכז משאבי הפרויקט: שינוי שם **כמות** כדי להפחית את העמימות.</span><span class="sxs-lookup"><span data-stu-id="fb070-117">Fixed: Project Resource Hub: Rename **Amount** to reduce ambiguity.</span></span>
  - <span data-ttu-id="fb070-118">תוקן: התאמת התצוגה **העתקת עמודות של ערכי זמן** כדי לכלול את הסוג.</span><span class="sxs-lookup"><span data-stu-id="fb070-118">Fixed: Adjust the view **Copy Time Entry Columns** to include the type.</span></span>
  - <span data-ttu-id="fb070-119">תוקן: עריכת משך הזנת זמן בתצוגת הרשת באמצעות מספרים עשרוניים מביאה לשגיאה לא ידועה עבור מספרים מסוימים.</span><span class="sxs-lookup"><span data-stu-id="fb070-119">Fixed: Editing time entry duration in the grid view using decimal numbers results in unknown error for some numbers.</span></span>

- <span data-ttu-id="fb070-120">ניהול פרויקט</span><span class="sxs-lookup"><span data-stu-id="fb070-120">Project Management</span></span>

  - <span data-ttu-id="fb070-121">תוקן: התפריט הנפתח עבור **השתמש בתצוגת מעקב** כעת מתרחב על סמך רוחב האפשרויות.</span><span class="sxs-lookup"><span data-stu-id="fb070-121">Fixed: The drop-down menu for **Use in Tracking View** now expands based on the width of the options.</span></span>
  - <span data-ttu-id="fb070-122">תוקן: בעת ניהול פרויקטים באזור הזמן +13, חישובי משימות יכולים להציג תוצאות לא מדויקות.</span><span class="sxs-lookup"><span data-stu-id="fb070-122">Fixed: When managing projects in the +13 time zone, tasks calculations can display inaccurate results.</span></span>
  - <span data-ttu-id="fb070-123">תוקן: **זמן סיום של חבר צוות** תוקן בעת שימוש בלוח השנה הפתוח 24 שעות ביממה.</span><span class="sxs-lookup"><span data-stu-id="fb070-123">Fixed: **Team Member End Time** has been corrected when using a 24-hour calendar.</span></span>
  - <span data-ttu-id="fb070-124">תוקן: הפעלה מחדש של **BPF** בטופס הראשי **msdyn_project**.</span><span class="sxs-lookup"><span data-stu-id="fb070-124">Fixed: Re-activated the **BPF** in **msdyn_project** main form.</span></span>
  - <span data-ttu-id="fb070-125">תוקן: חישוב המשימות כבר לא מתעלם מיום אחד.</span><span class="sxs-lookup"><span data-stu-id="fb070-125">Fixed: Assignments calculation no longer ignores one day.</span></span>
  - <span data-ttu-id="fb070-126">תוקן: באנר התראות חדש נוסף לטופס הפרויקט כאשר אזור הזמן של המשתמש שונה מזה של הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="fb070-126">Fixed: A new notification banner has been added to the project form when the time zone differs between user and project.</span></span>

- <span data-ttu-id="fb070-127">Sales</span><span class="sxs-lookup"><span data-stu-id="fb070-127">Sales</span></span>

  - <span data-ttu-id="fb070-128">תוקן: ניתן להשתמש בחיפוש קטגוריות לאומדן הוצאות לצורך סינון כפילויות.</span><span class="sxs-lookup"><span data-stu-id="fb070-128">Fixed: Expense estimate category lookup can be used to filter duplicates.</span></span>
  - <span data-ttu-id="fb070-129">תוקן: הקוד ב- **PluginDomain.ExecuteInTryCatchBlock (..)** כבר לא מסתיר את מקור החריגה.</span><span class="sxs-lookup"><span data-stu-id="fb070-129">Fixed: Code in **PluginDomain.ExecuteInTryCatchBlock(..)** no longer hides the origin of the exception.</span></span>
  - <span data-ttu-id="fb070-130">תוקן: כבר לא מקבלים הודעת שגיאה בזמן **חיפוש פרויקט** בטופס **שורת הצעת מחיר** כשיש יותר מ- 1000 פרויקטים.</span><span class="sxs-lookup"><span data-stu-id="fb070-130">Fixed: No longer get an error message in **Project lookup** in the **Quote Line** form when there are more than 1000 projects.</span></span>
  - <span data-ttu-id="fb070-131">תוקן: רשת **הערכות** לאומדני עבודה ואומדני הוצאות מציגה כעת את סמל המטבע הנכון.</span><span class="sxs-lookup"><span data-stu-id="fb070-131">Fixed: **Estimates** grid for labor estimates and expense estimates now displays the correct currency symbol.</span></span>
  - <span data-ttu-id="fb070-132">תוקן: לאחר שארגון מעדכן את PSA מעדכון מהדורה 14 לעדכון מהדורה 15, הכרטיסיה **לוח זמנים** כבר לא מופיעה ריקה בטופס **פרויקט**.</span><span class="sxs-lookup"><span data-stu-id="fb070-132">Fixed: After an organization updates PSA from Update Release 14 to Update Release 15, the **Schedule** tab no longer appears as blank on the **Project** form.</span></span>