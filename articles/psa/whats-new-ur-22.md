---
title: מה חדש או שונה במהדורה המעודכנת של Project Service Automation, 22 V3
description: נושא זה מפרט את התכונות החדשות והתיקונים במהדורה 22, עדכון V3 של Project Service Automation.
author: ruhercul
manager: kfend
ms.service: dynamics-365-customerservice
ms.custom: dyn365-projectservice
ms.date: 07/28/2020
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
ms.openlocfilehash: badd87a276d68d9959e9cca4220daf61ed570638
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077256"
---
# <a name="project-service-automation-update-release-22-v3"></a><span data-ttu-id="31368-103">מהדורה 22, V3 של Project Service Automation</span><span class="sxs-lookup"><span data-stu-id="31368-103">Project Service Automation Update Release 22, V3</span></span>

<span data-ttu-id="31368-104">אנו שמחים להכריז על העדכון האחרון של אפליקציית Project Service Automation של Dynamics 365.</span><span class="sxs-lookup"><span data-stu-id="31368-104">We’re pleased to announce the latest update for the Project Service Automation application for Dynamics 365.</span></span> <span data-ttu-id="31368-105">מהדורה זו כוללת כמה שיפורים חשובים באיכות, בביצועים ובשימושיות.</span><span class="sxs-lookup"><span data-stu-id="31368-105">This release includes some important improvements to quality, performance, and usability.</span></span> <span data-ttu-id="31368-106">מהדורה זו תואמת את Dynamics 365 9.x.</span><span class="sxs-lookup"><span data-stu-id="31368-106">This release is compatible with Dynamics 365 9.x.</span></span> <span data-ttu-id="31368-107">כדי לעדכן למהדורה זו, בקר במרכז הניהול של Dynamics 365 ועבור לדף הפתרונות כדי להתקין את העדכון.</span><span class="sxs-lookup"><span data-stu-id="31368-107">To update to this release, visit the Admin Center for Dynamics 365 online solutions page to install the update.</span></span> <span data-ttu-id="31368-108">למידע נוסף: [התקנה, עדכון או הסרה של פתרון מועדף](https://docs.microsoft.com/power-platform/admin/install-remove-preferred-solution).</span><span class="sxs-lookup"><span data-stu-id="31368-108">For more information, see [Install, update, or remove a preferred solution](https://docs.microsoft.com/power-platform/admin/install-remove-preferred-solution).</span></span>

<span data-ttu-id="31368-109">נושא זה מפרט את התכונות והתיקונים החדשים או ששונו עבור מהדורה 22, עדכון V3 של Project Service Automation.</span><span class="sxs-lookup"><span data-stu-id="31368-109">This topic lists the features and fixes that are new or changed for Project Service Automation V3, Update Release 22.</span></span> <span data-ttu-id="31368-110">גירסה זו כוללת מספר build של V 3.10.33.48 ובדרך כלל היא זמינה דרך עדכון עצמי ביוני 2020.</span><span class="sxs-lookup"><span data-stu-id="31368-110">This version has a build number of V 3.10.33.48 and is generally available through a self-update in June 2020.</span></span>

## <a name="update-release-22"></a><span data-ttu-id="31368-111">הפצת עדכון 22</span><span class="sxs-lookup"><span data-stu-id="31368-111">Update Release 22</span></span>

### <a name="bug-fixes"></a><span data-ttu-id="31368-112">תיקוני באגים</span><span class="sxs-lookup"><span data-stu-id="31368-112">Bug fixes</span></span>



<span data-ttu-id="31368-113">**זמן והוצאה**</span><span class="sxs-lookup"><span data-stu-id="31368-113">**Time and Expense**</span></span>

<span data-ttu-id="31368-114">הבעיות הבאות תוקנו:</span><span class="sxs-lookup"><span data-stu-id="31368-114">The following issues have been fixed:</span></span>

- <span data-ttu-id="31368-115">**ערכי זמן** אינם מתווספים אוטומטית בלוח הזמנים לאחר הייבוא.</span><span class="sxs-lookup"><span data-stu-id="31368-115">**Time entries** are not automatically added in the Time entries schedule after import.</span></span>
- <span data-ttu-id="31368-116">בורר תאריכי הרשת של **ערכי זמן** אינו מזהה את ההגדרות האזוריות של המשתמש.</span><span class="sxs-lookup"><span data-stu-id="31368-116">The **Time Entry** grid date picker does not recognize a user's regional settings.</span></span>

<span data-ttu-id="31368-117">**ניהול משאבים**</span><span class="sxs-lookup"><span data-stu-id="31368-117">**Resource Management**</span></span>

<span data-ttu-id="31368-118">הבעיות הבאות תוקנו:</span><span class="sxs-lookup"><span data-stu-id="31368-118">The following issues have been fixed:</span></span>

- <span data-ttu-id="31368-119">במצב ידני, שינויים בקווי מתאר של **הקצאת משאבים** אינם מוכרים בעת היצירה של **דרישות משאבים**.</span><span class="sxs-lookup"><span data-stu-id="31368-119">In manual mode, changes to **Resource Assignment** contours are not recognized when generating **Resource Requirements**.</span></span>
- <span data-ttu-id="31368-120">**בקשות משאבים** אינן תומכות בסטטוסים של בקשות מותאמות אישית.</span><span class="sxs-lookup"><span data-stu-id="31368-120">**Resource Requests** do not support custom request statuses.</span></span>

<span data-ttu-id="31368-121">**ניהול פרויקט**</span><span class="sxs-lookup"><span data-stu-id="31368-121">**Project Management**</span></span>

<span data-ttu-id="31368-122">הבעיות הבאות תוקנו:</span><span class="sxs-lookup"><span data-stu-id="31368-122">The following issues have been fixed:</span></span>

- <span data-ttu-id="31368-123">שימוש בלחיצה כפולה על EstimateGridControl לא ינתח כראוי מספרי פורמט הולנדי.</span><span class="sxs-lookup"><span data-stu-id="31368-123">Using double-click on EstimateGridControl will not correctly parse Dutch format numbers.</span></span>
- <span data-ttu-id="31368-124">שעות שהוקצו אינן מתעדכנות כראוי בעת שינוי הקצאות באמצעות התוסף לקוח שולחן העבודה של Microsoft Project.</span><span class="sxs-lookup"><span data-stu-id="31368-124">Assigned hours do not update correctly when assignments are changed using the Microsoft Project desktop client add-in.</span></span>
- <span data-ttu-id="31368-125">מעקב אחר פרויקטים ורשתות הערכה מציגים קוד מטבע מכירות שגוי כאשר מטבע החוזה שונה ממטבע הלקוח והארגון מוגדר להצגת קודי מטבע במקום סמלי מטבעות.</span><span class="sxs-lookup"><span data-stu-id="31368-125">Project Tracking and Estimates grids display incorrect sales currency code when contract currency is different than customer currency and organization is configured to display currency codes instead of currency symbols.</span></span>
- <span data-ttu-id="31368-126">תאריך הסיום של חבר צוות יוסיף יום אחד אם לוח הזמנים של שעות העבודה הוא 24 שעות ביממה.</span><span class="sxs-lookup"><span data-stu-id="31368-126">A Team member's finish date will add one day if the work hour schedule is 24-hours per day.</span></span>
- <span data-ttu-id="31368-127">בלוח הזמנים של הפרויקט, הוספת קטגוריית עסקאות למשימה אינה מפעילה שמירה אוטומטית.</span><span class="sxs-lookup"><span data-stu-id="31368-127">On the Project Schedule, adding a Transaction Category to a task does not trigger auto save.</span></span>
- <span data-ttu-id="31368-128">השגיאה הבאה מוצגת בעת הוספת חבר צוות לתבנית הפרויקט: "לא ניתן לשייך דרישות משאבים לתבניות פרויקט".</span><span class="sxs-lookup"><span data-stu-id="31368-128">The following error is displayed when adding a team member to the Project Template: "Resource requirements cannot be associated with project templates".</span></span> 
- <span data-ttu-id="31368-129">סקריפט רצועת הכלים "msdyn.Approval.CanApproveOrReject" מציג שגיאת פסק זמן.</span><span class="sxs-lookup"><span data-stu-id="31368-129">Ribbon rule script "msdyn.Approval.CanApproveOrReject" displays a timeout error.</span></span>

<span data-ttu-id="31368-130">**Sales**</span><span class="sxs-lookup"><span data-stu-id="31368-130">**Sales**</span></span>

<span data-ttu-id="31368-131">הבעיות הבאות תוקנו:</span><span class="sxs-lookup"><span data-stu-id="31368-131">The following issues have been fixed:</span></span>

- <span data-ttu-id="31368-132">הודעת שגיאת אימות לא מוצגת כאשר נבחר מחירון עלות ברשימת מחירים בטופס/ישות של 'מחירון פרויקט חדש'.</span><span class="sxs-lookup"><span data-stu-id="31368-132">Validation error message not displayed when a Cost Price List is selected in Price List lookup on 'New Quote Project Price List' form/entity.</span></span>
- <span data-ttu-id="31368-133">סגירת הצעת המחיר כזוכה לא מנווטת לחוזה שנוצר אם BPF המצורף להצעת המחיר נמצא בשלב הסופי.</span><span class="sxs-lookup"><span data-stu-id="31368-133">Closing the quote as won does not navigate to the created contract if a BPF attached to the quote is in the final stage.</span></span>
- <span data-ttu-id="31368-134">הפיכה של **מכירות שלא הושלמו** מקושרת לעלות המקורית כאשר מחזירים ערך זמן.</span><span class="sxs-lookup"><span data-stu-id="31368-134">Reversing **Unbilled Sales** is linked to original cost when a time entry is recalled.</span></span>
- <span data-ttu-id="31368-135">לאחר בחירה בלחצן **אישור** , סטטוס החשבונית לא משתנה ל- **אושר** אלא אם כן נעשה רענון של החשבונית.</span><span class="sxs-lookup"><span data-stu-id="31368-135">After selecting the **Confirm** button, the invoice status doesn't change to **Confirmed** unless the invoice is refreshed.</span></span>