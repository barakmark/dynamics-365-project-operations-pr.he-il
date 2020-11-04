---
title: מה חדש או שונה במהדורה המעודכנת של Project Service Automation, 23 V3
description: נושא זה מפרט את התכונות החדשות והתיקונים במהדורה 23, עדכון V3 של Project Service Automation.
author: ruhercul
manager: kfend
ms.service: dynamics-365-customerservice
ms.custom: dyn365-projectservice
ms.date: 08/25/2020
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
ms.openlocfilehash: eaae9cc62c449695cb2e999be48c57075aadbb21
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077255"
---
# <a name="project-service-automation-update-release-23-v3"></a><span data-ttu-id="13d6a-103">מהדורה 23, V3 של Project Service Automation</span><span class="sxs-lookup"><span data-stu-id="13d6a-103">Project Service Automation Update Release 23, V3</span></span>

<span data-ttu-id="13d6a-104">אנו שמחים להכריז על העדכון האחרון של אפליקציית Project Service Automation של Dynamics 365.</span><span class="sxs-lookup"><span data-stu-id="13d6a-104">We’re pleased to announce the latest update for the Project Service Automation application for Dynamics 365.</span></span> <span data-ttu-id="13d6a-105">מהדורה זו כוללת כמה שיפורים חשובים באיכות, בביצועים ובשימושיות.</span><span class="sxs-lookup"><span data-stu-id="13d6a-105">This release includes some important improvements to quality, performance, and usability.</span></span> <span data-ttu-id="13d6a-106">מהדורה זו תואמת את Dynamics 365 9.x.</span><span class="sxs-lookup"><span data-stu-id="13d6a-106">This release is compatible with Dynamics 365 9.x.</span></span> <span data-ttu-id="13d6a-107">כדי לעדכן למהדורה זו, בקר במרכז הניהול של Dynamics 365 ועבור לדף הפתרונות כדי להתקין את העדכון.</span><span class="sxs-lookup"><span data-stu-id="13d6a-107">To update to this release, visit the Admin Center for Dynamics 365 online solutions page to install the update.</span></span> <span data-ttu-id="13d6a-108">למידע נוסף: [התקנה, עדכון או הסרה של פתרון מועדף](https://docs.microsoft.com/power-platform/admin/install-remove-preferred-solution).</span><span class="sxs-lookup"><span data-stu-id="13d6a-108">For more information, see [Install, update, or remove a preferred solution](https://docs.microsoft.com/power-platform/admin/install-remove-preferred-solution).</span></span>

<span data-ttu-id="13d6a-109">נושא זה מפרט את התכונות והתיקונים החדשים או ששונו עבור מהדורה 23, עדכון V3 של Project Service Automation.</span><span class="sxs-lookup"><span data-stu-id="13d6a-109">This topic lists the features and fixes that are new or changed for Project Service Automation V3, Update Release 23.</span></span> <span data-ttu-id="13d6a-110">מספר ה- Build של גירסה זו הוא V 3.10.34.30 והיא זמינה דרך עדכון עצמי החל מאוגוסט 2020.</span><span class="sxs-lookup"><span data-stu-id="13d6a-110">This version has a build number of V 3.10.34.30 and is generally available through a self-update in August 2020.</span></span>

## <a name="update-release-23"></a><span data-ttu-id="13d6a-111">הפצת עדכון 23</span><span class="sxs-lookup"><span data-stu-id="13d6a-111">Update Release 23</span></span>

### <a name="bug-fixes"></a><span data-ttu-id="13d6a-112">תיקוני באגים</span><span class="sxs-lookup"><span data-stu-id="13d6a-112">Bug fixes</span></span>

<span data-ttu-id="13d6a-113">**זמן והוצאה**</span><span class="sxs-lookup"><span data-stu-id="13d6a-113">**Time and Expense**</span></span>

<span data-ttu-id="13d6a-114">הבעיות הבאות תוקנו:</span><span class="sxs-lookup"><span data-stu-id="13d6a-114">The following issues have been fixed:</span></span>
- <span data-ttu-id="13d6a-115">טפל במקרי קצה ב **מחיקת חבר צוות פרויקט** כדי לספק חריגה משמעותית.</span><span class="sxs-lookup"><span data-stu-id="13d6a-115">Handle edge case in **Project Team Member Delete** to provide a meaningful exception.</span></span>
- <span data-ttu-id="13d6a-116">ייבוא משימות גורם למסך הסרה ריק.</span><span class="sxs-lookup"><span data-stu-id="13d6a-116">Assignment import results in a blank remove screen.</span></span>

<span data-ttu-id="13d6a-117">**ניהול משאבים**</span><span class="sxs-lookup"><span data-stu-id="13d6a-117">**Resource Management**</span></span>

<span data-ttu-id="13d6a-118">הבעיות הבאות תוקנו:</span><span class="sxs-lookup"><span data-stu-id="13d6a-118">The following issues have been fixed:</span></span>

- <span data-ttu-id="13d6a-119">**כרטיס משאב רשת ניצול משאבים** מציג נתונים שגויים כאשר ציר הזמן הוא יותר מחמישה ימים.</span><span class="sxs-lookup"><span data-stu-id="13d6a-119">The **Resource utilization grid resource card** shows incorrect data when the time scale is more than five days.</span></span>
- <span data-ttu-id="13d6a-120">כאשר לקוחות יוצרים משאב שניתן להזמין, יישום ה-plug-in אינו מצליח להוסיף את המשאב באופן אוטומטי לקבוצה של Microsoft Office 365.</span><span class="sxs-lookup"><span data-stu-id="13d6a-120">When customers create a bookable resource, the plug-in intermittently fails to automatically add the resource to a Microsoft Office 365 group.</span></span>
- <span data-ttu-id="13d6a-121">תצוגת **יישוב‬** מציגה קווי מתאר ידניים בצורה לא נכונה בתצוגה **שבוע** או **חודש**.</span><span class="sxs-lookup"><span data-stu-id="13d6a-121">**Reconciliation** view displays manual contours incorrectly in the **Week** or **Month** view.</span></span>

<span data-ttu-id="13d6a-122">**ניהול פרויקט**</span><span class="sxs-lookup"><span data-stu-id="13d6a-122">**Project Management**</span></span>

<span data-ttu-id="13d6a-123">הבעיות הבאות תוקנו:</span><span class="sxs-lookup"><span data-stu-id="13d6a-123">The following issues have been fixed:</span></span>

- <span data-ttu-id="13d6a-124">מספר מוגזם של ישויות **RetrieveMultiple for usersettings** גורם לביצועים נמוכים של אישורי פרויקט ופעולות אחרות.</span><span class="sxs-lookup"><span data-stu-id="13d6a-124">An excessive number of **RetrieveMultiple for usersettings** entities are causing degraded performance for project approvals and other operations.</span></span>
- <span data-ttu-id="13d6a-125">חיפוש המשאבים ברשת של **תכנון משימות** מוגבל להצגה של עד חמישה חברי צוות בלבד מצוות הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="13d6a-125">The **Task Planning** grid resource lookup is limited to only show up to five team members from the project team.</span></span> 
- <span data-ttu-id="13d6a-126">חיפוש המשאבים ברשת של **תכנון משימות** אינו מסנן משאבים לא פעילים.</span><span class="sxs-lookup"><span data-stu-id="13d6a-126">The **Task Planning** grid resource lookup does not filter inactive resources.</span></span>
- <span data-ttu-id="13d6a-127">מצב ידני אינו פועל כצפוי במבנה פירוט העבודה של תכנון הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="13d6a-127">Manual mode is not working as expected in the project planning work breakdown structure.</span></span>
- <span data-ttu-id="13d6a-128">הרשת **תכנון משימות** מציגה **קטגוריות עסקאות לא פעילות**.</span><span class="sxs-lookup"><span data-stu-id="13d6a-128">The **Task Planning** grid shows **Inactive Transaction Categories**.</span></span>
- <span data-ttu-id="13d6a-129">הרשת **הקצאת משאבים** מעגלת בצורה שגויה כאשר למשימה יש מספר מטלות.</span><span class="sxs-lookup"><span data-stu-id="13d6a-129">The **Resource Assignment** grid rounds incorrectly when a task has multiple assignments.</span></span>
- <span data-ttu-id="13d6a-130">ערכי העיגול שונים בעלות מתוכננת ובעלות בפועל עבור משימה אחת.</span><span class="sxs-lookup"><span data-stu-id="13d6a-130">Rounding values are different between planned cost and actual cost for a single task.</span></span>

<span data-ttu-id="13d6a-131">**Sales**</span><span class="sxs-lookup"><span data-stu-id="13d6a-131">**Sales**</span></span>

<span data-ttu-id="13d6a-132">הבעיות הבאות תוקנו:</span><span class="sxs-lookup"><span data-stu-id="13d6a-132">The following issues have been fixed:</span></span>

- <span data-ttu-id="13d6a-133">**אחזר את כל קטגוריות העסקה** לחיצה כפולה יוצרת מספר שורות.</span><span class="sxs-lookup"><span data-stu-id="13d6a-133">**Fetch All Transaction Categories** double-click creates multiple lines.</span></span>