---
title: ‏‫קביעת לוח זמנים למשאבי פרויקט
description: כיצד לקבוע לוח זמנים למשאבי פרויקט ב- Project Service
author: JohnPBurrows
manager: kfend
ms.service: dynamics-365-customerservice
ms.custom:
- dyn365-projectservice
ms.date: 8/03/2018
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
ms.openlocfilehash: db69348aac96cbfaaa865228c9230cbda4b1e784
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077514"
---
# <a name="schedule-resources-for-a-project-project-service"></a><span data-ttu-id="4dc57-103">קביעת לוח זמנים למשאבי פרויקט (Project Service)</span><span class="sxs-lookup"><span data-stu-id="4dc57-103">Schedule resources for a project (Project Service)</span></span>

[!INCLUDE[cc-applies-to-psa-app-1x-2x](../includes/cc-applies-to-psa-app-1x-2x.md)]

<span data-ttu-id="4dc57-104">באפשרותך לבדוק זמינות משאבים כדי לקבל תצוגה כוללת על האופן שבו הוזמנו המשאבים שלך, או באפשרותך לסנן את התצוגה לפי כישורים, צוות, מיקום ואפשרויות אחרות.</span><span class="sxs-lookup"><span data-stu-id="4dc57-104">You can check resource availability to get an overall view of how booked your resources are, or you can filter the view by skills, team, location, and other options.</span></span>  
  
<span data-ttu-id="4dc57-105">לוח הזמנים מציג רשימה של משאבים עם הזמינות שלהם.</span><span class="sxs-lookup"><span data-stu-id="4dc57-105">The schedule board shows list of resources and their availability.</span></span> <span data-ttu-id="4dc57-106">בחר מצב תצוגה כדי להציג את הזמינות שלך לפי **שעות** , **יום** , **שבוע** , או **חודש**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-106">Select a view mode to show availability by **Hours** , **Day** , **Week** , or **Month**.</span></span>  
  
<span data-ttu-id="4dc57-107"> קביעת תצורה של לוח הזמנים (Field Service or Project Service Automation)</span><span class="sxs-lookup"><span data-stu-id="4dc57-107">Before you use the schedule board, it’s important to set it up.</span></span> <span data-ttu-id="4dc57-108">למידע נוסף, ראה [קביעת תצורה ללוח הזמנים (Field Service או Project Service Automation)](https://docs.microsoft.com/dynamics365/field-service/configure-schedule-board).</span><span class="sxs-lookup"><span data-stu-id="4dc57-108">For more information, see [Configure the schedule board (Field Service or Project Service Automation)](https://docs.microsoft.com/dynamics365/field-service/configure-schedule-board).</span></span>
  
<span data-ttu-id="4dc57-109">אם אתה משתמש בגרסה ישנה יותר, כדי לצפות בזמינות המשאבים היכנס ל[הצגת זמינות משאבים](../psa/view-resource-availability.md).</span><span class="sxs-lookup"><span data-stu-id="4dc57-109">If you are using an older version, for resource availability, see [View resource availability](../psa/view-resource-availability.md).</span></span>  

> [!IMPORTANT]
>  <span data-ttu-id="4dc57-110">כדי להשתמש בפונקציונליות של הזמנת לוח זמנים, קודים גיאוגרפיים‬ ושירותי מיקום, תצטרך להפעיל את המפות.</span><span class="sxs-lookup"><span data-stu-id="4dc57-110">To use the schedule board booking functionality, geocoding, and location services, you need to turn on maps.</span></span>  
> 
> 1. <span data-ttu-id="4dc57-111">מתוך התפריט הראשי בחר **תזמון משאבים** > **ניהול**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-111">On the main menu, select **Resource Scheduling** > **Administration**.</span></span>  
> 2. <span data-ttu-id="4dc57-112">לחץ על **פרמטרים של תזמון**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-112">Click **Scheduling parameters**.</span></span>  
> 3. <span data-ttu-id="4dc57-113">פתח את הרשומה וגלול למטה למקטע **Resource Scheduling Optimization**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-113">Open record and scroll down to the **Resource Scheduling Optimization** section.</span></span>  
> 4. <span data-ttu-id="4dc57-114">בשדה **התחבר למפות** , בחר **כן**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-114">On the **Connect to Maps** field, choose **Yes**.</span></span>  
> 5. <span data-ttu-id="4dc57-115">קבל את התנאים ושמור את הרשומה.</span><span class="sxs-lookup"><span data-stu-id="4dc57-115">Accept terms and save the record.</span></span>  
> 6. <span data-ttu-id="4dc57-116">מתוך התפריט הראשי בחר **Project Service** > **לוח זמנים**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-116">On the main menu, select **Project Service** > **Schedule board**.</span></span> <span data-ttu-id="4dc57-117">מכאן, קיימות כמה דרכים לתזמון ידני של דרישת הזמנה.</span><span class="sxs-lookup"><span data-stu-id="4dc57-117">From here, there are several ways to manually schedule a booking requirement.</span></span> <span data-ttu-id="4dc57-118">בחר את השיטה המתאימה עבורך.</span><span class="sxs-lookup"><span data-stu-id="4dc57-118">Choose the method that works for you.</span></span>
  
## <a name="find-available-resources"></a><span data-ttu-id="4dc57-119">מציאת משאבים זמינים‬</span><span class="sxs-lookup"><span data-stu-id="4dc57-119">Find available resources</span></span>

1.  <span data-ttu-id="4dc57-120">מתוך הרשימה **דרישת ההזמנה** , לחץ לחיצה ימנית על הזמנת משאב מתוכננת ובחר אחת מהאפשרויות הבאות:</span><span class="sxs-lookup"><span data-stu-id="4dc57-120">From the **Booking Requirement** list, right-click an unscheduled booking and choose one of the following:</span></span>  
  
- <span data-ttu-id="4dc57-121">בחר **חיפוש זמינות - משאבים נוכחיים** כדי לאתר משאב זמין מתוך הרשימה בלוח הזמנים.</span><span class="sxs-lookup"><span data-stu-id="4dc57-121">Choose **Find availability - Current Resources** to find an available resource from the list on the schedule board.</span></span>  
- <span data-ttu-id="4dc57-122">בחר **חיפוש זמינות - כל המשאבים** , כדי לאתר משאבים זמינים ממשאבי המערכת</span><span class="sxs-lookup"><span data-stu-id="4dc57-122">Choose **Find availability - All Resources** , to find an available resource from resources in the system</span></span>  
   > [!NOTE]
   >  <span data-ttu-id="4dc57-123">לאחר שתבצע זאת, המסננים יציגו אפשרויות עבור דרישת ההזמנה שנבחרה.</span><span class="sxs-lookup"><span data-stu-id="4dc57-123">When you do this, the filters will show options for the selected booking requirement.</span></span>  
  
2. <span data-ttu-id="4dc57-124">כאשר תראה משבצת זמינה, לחץ קליק-ימני על משבצת הזמן בלוח הזמנים ובחר **הזמן כאן**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-124">When you see an available slot, right-click the time slot on the schedule board and choose **Book Here**.</span></span> <span data-ttu-id="4dc57-125">לחלופין, גרור ושחרר את דרישת ההזמנה למשבצת הזמן.</span><span class="sxs-lookup"><span data-stu-id="4dc57-125">Or, drag and drop the booking requirement to the available time slot.</span></span>  
  

## <a name="book-a-resource-using-the-daily-view-and-find-whos-under-booked"></a><span data-ttu-id="4dc57-126">הזמנת משאב באמצעות תצוגה יומית וזיהוי האנשים שלא הוזמנו</span><span class="sxs-lookup"><span data-stu-id="4dc57-126">Book a resource using the daily view and find who’s under-booked</span></span>
  
1.  <span data-ttu-id="4dc57-127">בלוח הזמנים, לחץ על **מצב תצוגה** ובחר **ימים**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-127">On the schedule board, select **View Mode** and select **Days**.</span></span>  
  
    <span data-ttu-id="4dc57-128">תופיע תצוגת רשת של מספר השעות שבהן משאב מוזמן בכל יום ובאילו ימים הוא פנוי.</span><span class="sxs-lookup"><span data-stu-id="4dc57-128">This shows a grid view of how many hours a resource is booked per day and which days they are free.</span></span>  
  
2.  <span data-ttu-id="4dc57-129">לחץ על שם המשאב שברצונך להזמין ולאחר מכן לחץ על **הזמן**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-129">Click the name of the resource you want to book, and then select **Book**.</span></span>  
  
3.  <span data-ttu-id="4dc57-130">בתיבת הדו-שיח **הזמנת משאבים (יצירה)** , בחר את הפרויקט שעבורו ברצונך להזמין את המשאב, כמו גם את שיטת הזמנת המשאב ומועדי ההתחלה והסיום.</span><span class="sxs-lookup"><span data-stu-id="4dc57-130">On the **Resource booking (create)** dialog box, choose the project that you want to book the resource for along with booking method and start and end times.</span></span>  
  
4.  <span data-ttu-id="4dc57-131">לאחר שסיימת, בחר **הזמן**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-131">When you’re done, select **Book**.</span></span>  
  
## <a name="view-to-the-schedule-board"></a><span data-ttu-id="4dc57-132">הצגת לוח הזמנים</span><span class="sxs-lookup"><span data-stu-id="4dc57-132">View to the schedule board</span></span>
  
1.  <span data-ttu-id="4dc57-133">בחר דרישת הזמנה לא מתוזמנת‬ מתוך הרשימה למטה.</span><span class="sxs-lookup"><span data-stu-id="4dc57-133">Select an unscheduled booking requirement from the list at the bottom.</span></span>  
  
2.  <span data-ttu-id="4dc57-134">גרור את דרישת ההזמנה למשבצת זמן/משאב זמינים בלוח הזמנים.</span><span class="sxs-lookup"><span data-stu-id="4dc57-134">Drag the booking requirement to an available resource/time slot on the schedule board.</span></span>  
  
3.  <span data-ttu-id="4dc57-135">לאחר שסיימת, בחר **הזמן**.</span><span class="sxs-lookup"><span data-stu-id="4dc57-135">When you're done, select **Book**.</span></span>  
  
### <a name="additional-resources"></a><span data-ttu-id="4dc57-136">משאבים נוספים</span><span class="sxs-lookup"><span data-stu-id="4dc57-136">Additional resources</span></span>  
 [<span data-ttu-id="4dc57-137">מדריך למנהל משאבים</span><span class="sxs-lookup"><span data-stu-id="4dc57-137">Resource manager guide</span></span>](../psa/resource-manager-guide.md)