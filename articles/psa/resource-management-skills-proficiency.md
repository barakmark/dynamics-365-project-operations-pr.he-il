---
title: כישורים ומודלים של מיומנות
description: נושא זה מספק מידע על אופן השימוש בכישורים ובמודלים של מיומנות.
author: ruhercul
manager: kfend
ms.service: dynamics-365-customerservice
ms.custom:
- dyn365-projectservice
ms.date: 03/13/2019
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
ms.openlocfilehash: cd243544df062e5801bbfa0a3bd75c4d9a116a6f
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077528"
---
# <a name="skills-and-proficiency-models"></a><span data-ttu-id="7cf84-103">כישורים ומודלים של מיומנות</span><span class="sxs-lookup"><span data-stu-id="7cf84-103">Skills and proficiency models</span></span>

[!INCLUDE[cc-applies-to-psa-app-3.x](../includes/cc-applies-to-psa-app-3x.md)]

<span data-ttu-id="7cf84-104">כישורים הם מאפייני משאב המשותפים בין Dynamics 365 Project Service Automation ובמידה והוא קיים, Dynamics 365 Field Service.</span><span class="sxs-lookup"><span data-stu-id="7cf84-104">Skills are resource characteristics that are shared between Dynamics 365 Project Service Automation and if present, Dynamics 365 Field Service.</span></span> 

<span data-ttu-id="7cf84-105">כדי לשמור על מאגר הכישורים ב- Project Service Automation, עבור אל **משאבים** \> **כישורי משאבים**.</span><span class="sxs-lookup"><span data-stu-id="7cf84-105">To maintain the repository of skills in Project Service Automation, go to **Resources** \> **Resource Skills**.</span></span> 

> ![כישורי משאבים](media/Resource-Management-image84.png)

## <a name="use-proficiency-models-to-rate-resources"></a><span data-ttu-id="7cf84-107">שימוש במודלים של מיומנות כדי לדרג משאבים</span><span class="sxs-lookup"><span data-stu-id="7cf84-107">Use proficiency models to rate resources</span></span>

<span data-ttu-id="7cf84-108">כישורים עבור משאבים מדורגים לפי מודלים של מיומנות.</span><span class="sxs-lookup"><span data-stu-id="7cf84-108">Skills for resources are rated by proficiency models.</span></span> <span data-ttu-id="7cf84-109">הדירוגים הבודדים נמצאים במודל מיומנות.</span><span class="sxs-lookup"><span data-stu-id="7cf84-109">The individual ratings are in a proficiency model.</span></span> 

1. <span data-ttu-id="7cf84-110">כדי ליצור מודל מיומנות, עבור אל **משאבים** \> **מודלים של מיומנות** ולאחר מכן בחר **חדש**.</span><span class="sxs-lookup"><span data-stu-id="7cf84-110">To create a proficiency model, go to **Resources** \> **Proficiency Models** , and then select **New**.</span></span>
2. <span data-ttu-id="7cf84-111">במודל הדירוג החדש, ציין את ערך הדירוג המינימלי, את ערך הדירוג המרבי ואת הישות המדורגת.</span><span class="sxs-lookup"><span data-stu-id="7cf84-111">In the new rating model, specify the minimum rating value, the maximum rating value, and the entity that is being rated.</span></span>
3. <span data-ttu-id="7cf84-112">ברשת המשנה **ערכי דירוג** , ניתן להגדיר את ערכי הדירוג השונים, מהערך המינימלי לערך המרבי.</span><span class="sxs-lookup"><span data-stu-id="7cf84-112">In the **Rating Values** sub-grid, you can define the different rating values, from the minimum to the maximum.</span></span>

> ![דירוגים מינימליים ומרביים הוגדרו](media/Resource-Management-image85.png)

<span data-ttu-id="7cf84-114">ערכי דירוג אלה מוצגים במסננים **דרישות משאב** , **לוח זמנים** ו **מסייע לוח הזמנים**.</span><span class="sxs-lookup"><span data-stu-id="7cf84-114">These rating values are shown on the **Resource Requirements** , **Schedule Board** , and **Schedule Assistant** filters.</span></span>