---
title: סוגים של שלבי פרויקט
description: נושא זו מספק מידע על שלבי פרויקט.
author: ruhercul
manager: kfend
ms.service: dynamics-365-customerservice
ms.custom:
- dyn365-projectservice
ms.date: 06/19/2020
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
ms.openlocfilehash: 521bf4b3090473a603626a99fded53906b644a7a
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077359"
---
# <a name="project-stage-types"></a><span data-ttu-id="46f9d-103">סוגים של שלבי פרויקט</span><span class="sxs-lookup"><span data-stu-id="46f9d-103">Project stage types</span></span> 

[!INCLUDE[cc-applies-to-psa-app-3.x](../includes/cc-applies-to-psa-app-3x.md)]

<span data-ttu-id="46f9d-104">שלבי פרויקט מיועדים לשקף את מצב הפרויקט במהלך התקדמותו.</span><span class="sxs-lookup"><span data-stu-id="46f9d-104">Project stages are designed to reflect the state of the project as it progresses.</span></span> <span data-ttu-id="46f9d-105">ניתן להשתמש בהתאמות אישיות כדי לעדכן אוטומטית את השלבים בזרימת תהליכים עסקיים, Power Automate, או תוספים של יישום plug-in.</span><span class="sxs-lookup"><span data-stu-id="46f9d-105">Customizations can be used to automatically update the stages with business process flows, Power Automate, or plug-in extensions.</span></span>

<span data-ttu-id="46f9d-106">השלבים הבאים מוגדרים ב- BPF המוגדר כברירת מחדל:</span><span class="sxs-lookup"><span data-stu-id="46f9d-106">The following stages are defined in the default BPF:</span></span>

- <span data-ttu-id="46f9d-107">משתמשים חדשים</span><span class="sxs-lookup"><span data-stu-id="46f9d-107">New</span></span>
- <span data-ttu-id="46f9d-108">הצעת מחיר</span><span class="sxs-lookup"><span data-stu-id="46f9d-108">Quote</span></span>
- <span data-ttu-id="46f9d-109">תוכנית</span><span class="sxs-lookup"><span data-stu-id="46f9d-109">Plan</span></span>
- <span data-ttu-id="46f9d-110">מסירה</span><span class="sxs-lookup"><span data-stu-id="46f9d-110">Deliver</span></span>
- <span data-ttu-id="46f9d-111">הושלם</span><span class="sxs-lookup"><span data-stu-id="46f9d-111">Complete</span></span>
- <span data-ttu-id="46f9d-112">סגור</span><span class="sxs-lookup"><span data-stu-id="46f9d-112">Close</span></span> 

## <a name="new"></a><span data-ttu-id="46f9d-113">חדש</span><span class="sxs-lookup"><span data-stu-id="46f9d-113">New</span></span>

<span data-ttu-id="46f9d-114">בעת יצירת פרויקט, השלב בפרויקט מוגדר בתור **חדש**.</span><span class="sxs-lookup"><span data-stu-id="46f9d-114">When you create a project, the project stage is set to **New**.</span></span> <span data-ttu-id="46f9d-115">אם הפרויקט נוצר מתבנית, ייתכן שהוא כוללנתונים של לוח זמנים, הערכה וצוות.</span><span class="sxs-lookup"><span data-stu-id="46f9d-115">If the project was created from a template, it might have schedule, estimate, and team data.</span></span> <span data-ttu-id="46f9d-116">אחרת, זהו רק מיתאר של הפרויקט ויש להזין את הרכיבים הנותרים.</span><span class="sxs-lookup"><span data-stu-id="46f9d-116">Otherwise, it's just an outline of the project, and the remaining components must be entered.</span></span>

## <a name="quote"></a><span data-ttu-id="46f9d-117">הצעת מחיר</span><span class="sxs-lookup"><span data-stu-id="46f9d-117">Quote</span></span>

<span data-ttu-id="46f9d-118">כאשר אתה משייך פרויקט להצעת מחיר או יוצר אותו מתוך הצעת מחיר, שלב הפרויקט מוגדר **הצעת מחיר** , וההערכות של תאריכי ההתחלה והסיום יעודכנו.</span><span class="sxs-lookup"><span data-stu-id="46f9d-118">When you associate a project with a quote, or when you create a project from a quote, the project stage is set to **Quote** , and the estimated start and end dates are updated.</span></span> <span data-ttu-id="46f9d-119">בזמן שהפרויקט נמצא בשלב **הצעת מחיר** , הכרטיסיה **מכירות** בדף **ישות פרויקט** מציגה פרטים לל הצעת המחיר.</span><span class="sxs-lookup"><span data-stu-id="46f9d-119">While the project is in the **Quote** stage, the **Sales** tab on the **Project Entity** page shows details of the quote.</span></span>

## <a name="plan"></a><span data-ttu-id="46f9d-120">תוכנית</span><span class="sxs-lookup"><span data-stu-id="46f9d-120">Plan</span></span>

<span data-ttu-id="46f9d-121">כאשר תזכה בהצעת מחיר המשויכת לפרויקט והוא יתקדם לשלב **חוזה** , שלב הפרויקט מתעדכן ל **תוכנית**.</span><span class="sxs-lookup"><span data-stu-id="46f9d-121">When you win a quote that is associated with a project, and the project is moved to the **Contract** phase, the project stage is updated to **Plan**.</span></span> <span data-ttu-id="46f9d-122">בזמן שהפרויקט נמצא בשלב **תוכנית** , הדף **ישות פרויקט** מציגה פרטים על החוזה.</span><span class="sxs-lookup"><span data-stu-id="46f9d-122">While the project is in the **Plan** stage, the **Project Entity** page shows details of the contract.</span></span>

## <a name="deliver"></a><span data-ttu-id="46f9d-123">מסירה</span><span class="sxs-lookup"><span data-stu-id="46f9d-123">Deliver</span></span>

<span data-ttu-id="46f9d-124">כאשר תוכנית הפרויקט תושלם ותהיה מוכן להתחיל את הפרויקט, מנהל הפרויקט צריך לעדכן את השלב ל **מסירה** כדי להראות שהפרויקט התחיל.</span><span class="sxs-lookup"><span data-stu-id="46f9d-124">When the project plan is completed, and you're ready to start the project, the project manager should update the project stage to **Deliver** to show that the project has started.</span></span>

## <a name="complete"></a><span data-ttu-id="46f9d-125">הושלם</span><span class="sxs-lookup"><span data-stu-id="46f9d-125">Complete</span></span> 

<span data-ttu-id="46f9d-126">כאשר העבודה עבור הפרויקט מסתיימת, מנהל הפרויקט יכול לעדכן את השלב ל **הושלם**.</span><span class="sxs-lookup"><span data-stu-id="46f9d-126">When the work for the project is completed, the project manager can update the stage to **Complete**.</span></span> <span data-ttu-id="46f9d-127">על-ידי עדכון שלב הפרויקט ל **הושלם** , מנהל הפרויקט מציין שהעבודה הושלמה ב-100 אחוזים, אבל הפרויקט נשאר פתוח כדי שניתן יהיה לתעד ערכי שעות או הוצאות שנמצאים בהמתנה.</span><span class="sxs-lookup"><span data-stu-id="46f9d-127">By updating the project stage to **Complete** , the project manager indicates that the work is 100-percent completed, but that the project is being kept open so that any pending time or expense entries can be recorded.</span></span>

## <a name="close"></a><span data-ttu-id="46f9d-128">סגור</span><span class="sxs-lookup"><span data-stu-id="46f9d-128">Close</span></span>

<span data-ttu-id="46f9d-129">כאשר כל התנועות תועדו עבור הפרויקט, מנהל הפרויקט יכול לעדכן את השלב ל **סגור**.</span><span class="sxs-lookup"><span data-stu-id="46f9d-129">When all transactions are recorded for the project, the project manager can update the stage to **Close**.</span></span> <span data-ttu-id="46f9d-130">בשלב זה, לא ניתן לתעד תנועות והפרויקט מוגדר לקריאה בלבד.</span><span class="sxs-lookup"><span data-stu-id="46f9d-130">At that point, no transactions can be recorded, and the project is set to read-only.</span></span>