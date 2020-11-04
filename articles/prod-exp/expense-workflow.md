---
title: זרימת עבודה של ניהול הוצאות
description: נושא זה מסביר כיצד אפשר להשתמש במערכת זרימת העבודה ב-Dynamics 365 FinanceMicrosoft ‏‎, להגדרת תהליך סקירת דוחות הוצאות בניהול הוצאות.
author: ShylaThompson
manager: AnnBe
ms.date: 09/13/2017
ms.topic: article
ms.prod: ''
ms.service: dynamics-ax-applications
ms.technology: ''
ms.search.form: WorkflowtableListPageRnr
audience: Application User
ms.reviewer: roschlom
ms.search.scope: Core, Operations
ms.search.region: Global
ms.author: shylaw
ms.search.validFrom: 2016-02-28
ms.dyn365.ops.version: AX 7.0.0
ms.openlocfilehash: 5207be92cb58d8ab2658096b3e0f3fc81d73d91e
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077463"
---
# <a name="expense-management-workflow"></a><span data-ttu-id="09810-103">זרימת עבודה של ניהול הוצאות</span><span class="sxs-lookup"><span data-stu-id="09810-103">Expense management workflow</span></span>

[!include [banner](../includes/banner.md)]

<span data-ttu-id="09810-104">ניתן להשתמש במערכת זרימת העבודה להגדרת תהליך סקירה לדוחות הוצאות בניהול הוצאות.</span><span class="sxs-lookup"><span data-stu-id="09810-104">You can use the workflow system to set up a review process for expense reports in Expense management.</span></span> <span data-ttu-id="09810-105">ניתן להגדיר זרימת עבודה המשתמשת בקריטריונים הבאים כדי לקבוע מי מאשר דוחות הוצאות:</span><span class="sxs-lookup"><span data-stu-id="09810-105">You can set up a workflow that uses the following criteria to determine who approves expense reports:</span></span>

- <span data-ttu-id="09810-106">ההיררכית הדיווח של עובדים ומגבלות האישור שהוגדרו מראש</span><span class="sxs-lookup"><span data-stu-id="09810-106">The employee reporting hierarchy and predefined approval limits</span></span>
- <span data-ttu-id="09810-107">אישור בעל רמות מרובות התומך במאשרי ביניים ובמאשר סופי</span><span class="sxs-lookup"><span data-stu-id="09810-107">Multi-level approval that supports interim approvers and a final approver</span></span>
- <span data-ttu-id="09810-108">ממדים פיננסיים ואחריות פרויקט</span><span class="sxs-lookup"><span data-stu-id="09810-108">Financial dimensions and project responsibility</span></span>
- <span data-ttu-id="09810-109">הקצאה למשתמשים ספציפיים או לקבוצות משתמשים</span><span class="sxs-lookup"><span data-stu-id="09810-109">Assignment to specific users or user groups</span></span>

<span data-ttu-id="09810-110">ניתן ליצור אישורי זרימת עבודה עבור דוחות הוצאות, דרישות נסיעות, מקדמות במזומן והחזר מס ערך מוסף (מע"מ).</span><span class="sxs-lookup"><span data-stu-id="09810-110">Workflow approvals can be created for expense reports, travel requisitions, cash advances, and value-added tax (VAT) recovery.</span></span>

<span data-ttu-id="09810-111">**דוגמה**</span><span class="sxs-lookup"><span data-stu-id="09810-111">**Example**</span></span>

<span data-ttu-id="09810-112">התהליך הבא הוא דוגמה לזרימת עבודה של ניהול הוצאות עבור דוח הוצאות.</span><span class="sxs-lookup"><span data-stu-id="09810-112">The following process is an example of the expense management workflow for an expense report.</span></span>

1. <span data-ttu-id="09810-113">עובד יוצר ושומר דוח הוצאות.</span><span class="sxs-lookup"><span data-stu-id="09810-113">An employee creates and saves an expense report.</span></span>
2. <span data-ttu-id="09810-114">העובד מגיש את דוח ההוצאות לאישור.</span><span class="sxs-lookup"><span data-stu-id="09810-114">The employee submits the expense report for approval.</span></span> <span data-ttu-id="09810-115">המאשר מזוהה על פי הכללים שהוגדרו בעת הגדרת זרימת העבודה.</span><span class="sxs-lookup"><span data-stu-id="09810-115">The approver is identified based on the rules that were defined when the workflow was set up.</span></span>
3. <span data-ttu-id="09810-116">המאשר מקבל הודעה שדוח הוצאות מוכן לאישור.</span><span class="sxs-lookup"><span data-stu-id="09810-116">The approver receives a notification that an expense report is ready for approval.</span></span> <span data-ttu-id="09810-117">המאשר בודק את דוח ההוצאות ומוודא שהתנאים הבאים מתקיימים:</span><span class="sxs-lookup"><span data-stu-id="09810-117">The approver reviews the expense report and verifies that the following conditions are met:</span></span>

    - <span data-ttu-id="09810-118">ההוצאות אינן מפרות מדיניות הוצאות כלשהי.</span><span class="sxs-lookup"><span data-stu-id="09810-118">The expenses don't violate any expense policies.</span></span> <span data-ttu-id="09810-119">אם הוצאה מפרה מדיניות, המאשר מוודא שדוח ההוצאות כולל הצדקה עסקית תקפה.</span><span class="sxs-lookup"><span data-stu-id="09810-119">If an expense violates a policy, the approver verifies that the expense report includes a valid business justification.</span></span>
    - <span data-ttu-id="09810-120">קבלות אלקטרוניות מצורפות לדוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="09810-120">Electronic receipts are attached to the expense report.</span></span>

4. <span data-ttu-id="09810-121">המאשר מאשר את דוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="09810-121">The approver approves the expense report.</span></span>
5. <span data-ttu-id="09810-122">דוח ההוצאות מוקצה לרכז חשבונות הזכאים לרישום.</span><span class="sxs-lookup"><span data-stu-id="09810-122">The expense report is assigned to the Accounts payable coordinator for posting.</span></span>
6. <span data-ttu-id="09810-123">אחד השלבים הבאים מתרחש, בהתאם לאם מוגדרת רישום אוטומטי:</span><span class="sxs-lookup"><span data-stu-id="09810-123">One of the following steps occurs, depending on whether automatic posting is configured:</span></span>

    - <span data-ttu-id="09810-124">אם מוגדר רישום אוטומטי, דוח ההוצאות מעובד לתשלום ומצב דוח ההוצאות מעודכן.</span><span class="sxs-lookup"><span data-stu-id="09810-124">If automatic posting is configured, the expense report is processed for payment, and the status of the expense report is updated.</span></span>
    - <span data-ttu-id="09810-125">אם לא הוגדר רישום אוטומטי, רכז החשבונות הזכאים יוודא כי כל הקבלות המקוריות הוגשו, וכי הקבלות מתאימים להוצאות בדוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="09810-125">If automatic posting isn't configured, the Accounts payable coordinator verifies that all original receipts have been submitted, and that the receipts are aligned with the expenses on the expense report.</span></span> <span data-ttu-id="09810-126">יש לוודא את הנכנונות של כל קודי המס המוזנים בדוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="09810-126">All tax codes that are entered on the expense report must also be verified as correct.</span></span>

<span data-ttu-id="09810-127">לאחר אימות דרישות אלה, מתבצע רישום של דוח ההוצאות.</span><span class="sxs-lookup"><span data-stu-id="09810-127">After these requirements are verified, the expense report is posted.</span></span>

<span data-ttu-id="09810-128">לאחר רישום דוח ההוצאות, מאושר התשלום עבור דוח ההוצאות, והעובד מקבל החזר הוצאות.</span><span class="sxs-lookup"><span data-stu-id="09810-128">After the expense report is posted, payment is authorized for the expense report, and the employee is reimbursed.</span></span>