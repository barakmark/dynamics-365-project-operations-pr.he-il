---
title: מחירוני ברירת מחדל
description: נושא זה מספק מידע על מחירוני ברירת מחדל של מכירות ועלות ב-Project Operations.
author: rumant
manager: Annbe
ms.date: 10/13/2020
ms.topic: article
ms.service: dynamics-365-customerservice
ms.reviewer: kfend
ms.author: rumant
ms.openlocfilehash: 275ef9b9706d212a6da0dc7c060081c3226572f3
ms.sourcegitcommit: 11a61db54119503e82faec5f99c4273e8d1247e5
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077187"
---
# <a name="default-price-lists"></a><span data-ttu-id="2d5d8-103">מחירוני ברירת מחדל</span><span class="sxs-lookup"><span data-stu-id="2d5d8-103">Default price lists</span></span>

<span data-ttu-id="2d5d8-104">_**חל על:** Project Operations לתרחישים מבוססי משאבים/לא מלאי, פריסה קלה - עסקה בחשבונית פרופורמה_</span><span class="sxs-lookup"><span data-stu-id="2d5d8-104">_**Applies To:** Project Operations for resource/non-stocked based scenarios, Lite deployment - deal to proforma invoicing_</span></span>

## <a name="sales-price-lists"></a><span data-ttu-id="2d5d8-105">מחירוני מכירות</span><span class="sxs-lookup"><span data-stu-id="2d5d8-105">Sales price lists</span></span>

<span data-ttu-id="2d5d8-106">כל הצעת מחיר וחוזה בפרויקט Dynamics 365 Project Operations מכיל מחירון ברירת מחדל למכירות.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-106">Every project quote and contract in Dynamics 365 Project Operations contains a default sales price list.</span></span> 

### <a name="price-list-default-on-project-quotes"></a><span data-ttu-id="2d5d8-107">מחירון ברירת מחדל להצעות מחיר לפרויקט</span><span class="sxs-lookup"><span data-stu-id="2d5d8-107">Price list default on project quotes</span></span>
<span data-ttu-id="2d5d8-108">המערכת משלימה את התהליך הבא כדי לקבוע איזה מחירון יהיה מחירון ברירת המחדל של הצעת מחיר לפרויקט:</span><span class="sxs-lookup"><span data-stu-id="2d5d8-108">The system completes the following process to determine which price list to default on a project quote:</span></span>

1. <span data-ttu-id="2d5d8-109">המערכת בוחנת את המחירונים המצורפים למחירוני הפרויקט של תיק הלקוח.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-109">The system looks at the price lists that are attached to the account's project price lists.</span></span> 
2. <span data-ttu-id="2d5d8-110">אם יש מחירוני פרויקט המצורפים לרשומת תיק הלקוח, המערכת בוחנת את מחירוני המכירה המצורפים לפרמטרים של הפרויקט התואמים למטבע של הצעת המחיר להפרויקט.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-110">If there are project price lists attached to the account record, the system looks at the sales price lists attached to the project parameters that match the currency of the project quote.</span></span>
3. <span data-ttu-id="2d5d8-111">לאחר מכן, המערכת בודקת את תוקף התאריכים של המחירונים התואמים את טווח התאריכים של הצעת המחיר.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-111">Next, the system checks the date effectivity of the price lists that match the date range of the project quote.</span></span> <span data-ttu-id="2d5d8-112">באופן ספציפי, התאריך שבו הצעת המחיר נוצרה.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-112">Specifically, the date the quote was created.</span></span>
4. <span data-ttu-id="2d5d8-113">אם ישנם מחירונים מרובים שתקפים לתאריך הצעת המחיר, כל המחירונים יהוו את מחירוני ברירת המחדל של הצעת המחיר.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-113">If there are multiple price lists that are effective for the date of the project quote, all of the price lists default on the project quote.</span></span>
5. <span data-ttu-id="2d5d8-114">אם אין מחירונים בתוקף לתאריך של הצעת המחיר לפרויקט, אין מחירון פרויקט המוגדר כברירת מחדל בהצעת המחיר.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-114">If no price lists in effect for the date of the project quote, there's no default project price list on the project quote.</span></span> <span data-ttu-id="2d5d8-115">הודעת אזהרה תופיע בהצעת המחיר של הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-115">A warning message will occur on the project quote.</span></span> <span data-ttu-id="2d5d8-116">ההודעה מציינת שהנתונים בפועל וההערכות של הפרויקט לא יתומחרו משום שאין מחירוני פרויקט מצורפים.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-116">The message states that actuals and estimates on the project won't be priced because there are no project price lists attached.</span></span>

### <a name="price-list-default-on-project-contracts"></a><span data-ttu-id="2d5d8-117">מחירון ברירת מחדל בחוזי פרויקט</span><span class="sxs-lookup"><span data-stu-id="2d5d8-117">Price list default on project contracts</span></span> 
<span data-ttu-id="2d5d8-118">המערכת משלימה את התהליך הבא כדי לקבוע איזה מחירון יהיה מחירון ברירת המחדל של חוזה פרויקט:</span><span class="sxs-lookup"><span data-stu-id="2d5d8-118">The system completes the following process to determine which price list to default on a project contract:</span></span>

1. <span data-ttu-id="2d5d8-119">אם החוזה נוצר מהצעת מחיר, מחירוני הפרויקט בהצעת המחיר מועתקים בנפרד ומצורפים לחוזה הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-119">If the contract is created from a quote, the project price lists on the quote are copied over separately and attached to the project contract.</span></span>
2. <span data-ttu-id="2d5d8-120">אם החוזה נוצר מאפס, המערכת בוחנת את המחירונים המצורפים למחירוני הפרויקט של תיק הלקוח.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-120">If the contract is created from scratch, the system looks at the price lists that are attached to the project price lists of the account.</span></span> <span data-ttu-id="2d5d8-121">אם אין מחירוני פרויקט המצורפים לרשומת תיק הלקוח, המערכת מחפשת מחירוני המכירה המצורפים לפרמטרים של הפרויקט, שתואמים למטבע של חוזה הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-121">If there aren't project price lists attached to the account record, the system looks for sales price lists attached to the project parameters that match the currency of the project contract.</span></span>
4. <span data-ttu-id="2d5d8-122">לאחר מכן, המערכת בודקת את תוקף התאריכים של המחירונים התואמים את טווח התאריכים של חוזה הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-122">Next, the system checks the date effectivity of the price lists that match the date range of the project contract.</span></span> <span data-ttu-id="2d5d8-123">באופן ספציפי, התאריך שבו החוזה נוצר.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-123">Specifically, the date the contract was created.</span></span>
5. <span data-ttu-id="2d5d8-124">אם ישנם מחירונים מרובים שתקפים לתאריך החוזה, כל המחירונים יהוו את מחירוני ברירת המחדל של החוזה.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-124">If there are multiple price lists that are effective for the date of the contract, all of the price lists default on the contract.</span></span>
6. <span data-ttu-id="2d5d8-125">אם אין מחירונים בתוקף לתאריך של חוזה הפרויקט, לא יוגדרו מחירוני פרויקט כברירת מחדל בחוזה.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-125">If there are no price lists in effect for the date of the contract, no project price lists default to the contract.</span></span> <span data-ttu-id="2d5d8-126">הודעת אזהרה תופיע בחוזה הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-126">A warning message will occur on the project contract.</span></span> <span data-ttu-id="2d5d8-127">ההודעה מציינת שהנתונים בפועל וההערכות של הפרויקט לא יתומחרו משום שאין מחירוני פרויקט מצורפים.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-127">The message states that actuals and estimates on the project won't be priced because there are no project price lists attached.</span></span>

## <a name="cost-price-lists"></a><span data-ttu-id="2d5d8-128">מחירוני עלות</span><span class="sxs-lookup"><span data-stu-id="2d5d8-128">Cost price lists</span></span>

<span data-ttu-id="2d5d8-129">מחירוני עלות אינם מוגדרים כברירת מחדל של אף ישות ב-Project Operations.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-129">Cost price lists don't default to any entity in Project Operations.</span></span> <span data-ttu-id="2d5d8-130">קביעת מחירון העלות לשימוש עבור עלויות הפרויקט נעשית תמיד באותו הרגע.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-130">Determining the cost price list to use for project costs is always done in the moment.</span></span> <span data-ttu-id="2d5d8-131">המערכת משלימה את התהליך הבא כדי לקבוע איזה מחירון ישמש לעלויות פרויקט:</span><span class="sxs-lookup"><span data-stu-id="2d5d8-131">The system completes the following process to determine which price list to use for project costs:</span></span>

1. <span data-ttu-id="2d5d8-132">המערכת בוחנת תחילה את המחירונים המצורפים ליחידת החוזה הארגונית של הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-132">The system first looks at the price lists that are attached to the contracting organization unit of the project.</span></span>
2. <span data-ttu-id="2d5d8-133">לאחר מכן המערכת בוחנת את תוקף התאריכים של המחירונים שתואמים לתאריך של שורת ההערכה הנכנסת או הנתונים בפועל.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-133">The system then looks at the date effectivity of the price lists that match the date of the incoming estimate or actual line.</span></span> <span data-ttu-id="2d5d8-134">במצב הזה, *שורת הערכה* מתייחסת לשלושת ההקשרים הערכה ב-Project Operations:</span><span class="sxs-lookup"><span data-stu-id="2d5d8-134">In this situation, *estimate line* refers to all three contexts of estimation in Project Operations:</span></span>

    - <span data-ttu-id="2d5d8-135">שורת הערכת פרוייקט</span><span class="sxs-lookup"><span data-stu-id="2d5d8-135">Project estimate line</span></span>
    - <span data-ttu-id="2d5d8-136">פרטים בשורת הצעת מחיר</span><span class="sxs-lookup"><span data-stu-id="2d5d8-136">Quote line detail</span></span>
    - <span data-ttu-id="2d5d8-137">פריט סעיף חוזה</span><span class="sxs-lookup"><span data-stu-id="2d5d8-137">Contract line detail</span></span>
  
3. <span data-ttu-id="2d5d8-138">אם ישנם מחירונים מרובים בתוקף בתאריך של ההערכה או הנתון בפועל הנכנס, נבחר המחירון שנוצר לאחרונה.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-138">If there are multiple price lists that are effective for the date on the incoming estimate or actual, the price list created most recently is selected.</span></span>
4. <span data-ttu-id="2d5d8-139">אם אין מחירוני מצורפים ליחידה החוזה הארגונית של הפרויקט, המערכת בוחנת את מחירוני העלות המצורפים לפרמטרים של הפרויקט, שתואמים למטבע של הפרויקט.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-139">If there no price lists attached to the contracting organization unit of the project, the system looks at cost price lists attached to project parameters that match the currency of the project.</span></span>
5. <span data-ttu-id="2d5d8-140">לאחר מכן המערכת בוחנת את תוקף התאריכים של המחירונים שתואמים לתאריך של שורת ההערכה או הנתון בפועל הנכנסים.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-140">Next the system looks at the date effectivity of the price lists that match the date of the incoming estimate or actual line.</span></span> 
6. <span data-ttu-id="2d5d8-141">אם ישנם מחירונים מרובים בתוקף בתאריך של ההערכה או הנתון בפועל הנכנס, נבחר המחירון שנוצר לאחרונה.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-141">If there are multiple price lists that are effective for the date on the incoming estimate or actual, the price list created most recently is selected.</span></span>
7. <span data-ttu-id="2d5d8-142">אם אין מחירוני עלות המצורפים לפרמטרים של הפרויקט התואמים למטבע ולתאריך התוקף, המערכת מגדירה את תעריף העלות כאפס (0) בשורת ההערכה או הנתון בפועל הנכנסים.</span><span class="sxs-lookup"><span data-stu-id="2d5d8-142">If there are no cost price lists attached to the project parameters that match the currency and effective date, the system defaults the cost rate to zero (0) on the incoming estimate or actual line.</span></span>