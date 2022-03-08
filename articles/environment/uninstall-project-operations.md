---
title: הסרת ההתקנה של Dynamics 365 Project Operations
description: נושא זו מספק מידע על הסרת התקנה של Dynamics 365 Project Operations.
author: stsporen
ms.date: 11/09/2021
ms.topic: article
ms.reviewer: kfend
ms.author: sigitac
ms.openlocfilehash: b87c9324b1c95c10ef1e18b0fbf4572bdbe76827
ms.sourcegitcommit: b8b7a59eee7d93638446e93726d270316e45ab3d
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 11/10/2021
ms.locfileid: "7783644"
---
# <a name="uninstall-dynamics-365-project-operations"></a>הסרת ההתקנה של Dynamics 365 Project Operations 

_**חל על:** ‏Project Operations לתרחישים מבוססי משאבים/ללא מלאי_

כדי להסיר את ההתקנה של Dynamics 365 Project Operations, יש להקצות לך את התפקיד של מנהל מערכת.

1. עבור אל **הגדרות** > **פתרונות**.

    ![דף הגדרות.](./media/uninstall-proj-ops-solutions.png)
  
2. הסר את הפתרונות בסדר המדויק שהם מופיעים בטבלה הבאה. 

    | שלב | שם הפתרון                                    | הערה                                                                                         |
    |------|----------------------------------------------------|----------------------------------------------------------------------------------------------|
    | 1 | msdyn_ProjectServiceUpgrade_managed.cab            | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 2 | ProjectOperations_Anchor                           | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 3 | Dynamics365ProjectOperationsDualWriteEntityMaps    | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 4 | Dynamics365ProjectOperationsDualWrite              | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 5 | ProjectService                                     | אין הערות נוספות.                                                                         |
    | 6 | ProjectServiceCore_Patch                           | אין הערות נוספות.                                                                         |
    | 7 | ProjectServiceCore                                 | אין הערות נוספות.                                                                         |
    | 8 | ProjectServiceDeprecatedComponents                 | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 9 | FieldServiceCommon                                 | נדרש עבור כתיבה כפולה עם Dynamics 365 Finance או Dynamics 365 Supply Chain Management.   |
    | 10 | msdyn_AssetCommon                                  | נדרש עבור כתיבה כפולה עם Dynamics 365 Finance או Dynamics 365 Supply Chain Management.   |
    | 11 | msdyn_TESA_Anchor                                  | שדה נדרש עבור Dynamics 365 Field Service.                                                     |
    | 12 | msdyn_TESA_Patch                                   | שדה נדרש עבור Dynamics 365 Field Service.                                                     |
    | 13 | msdyn_TESA                                         | שדה נדרש עבור Dynamics 365 Field Service.                                                     |
    | 14 | ResourceSchedulingControls                         | שדה נדרש עבור Dynamics 365 Field Service.                                                     |
    | 15 | MicrosoftDynamicsScheduling3_CumulativePatch       | שדה נדרש עבור Dynamics 365 Field Service.                                                     |
    | 16 | MicrosoftDynamicsScheduling_Patch_xx               | שדה נדרש עבור Dynamics 365 Field Service.                                                     |
    | 17 | MicrosoftDynamicsScheduling                        | שדה נדרש עבור Dynamics 365 Field Service.                                                     |
    | 18 | Dynamics365FinanceAndOperationsAnchor              | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 19 | Dynamics365Notes                                   | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 20 | Dynamics365FinanceAndOperationsDualWriteEntityMaps | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 21 | DualWriteCore                                      | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 22 | Dynamics365AssetManagementApp                      | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 23 | Dynamics365AssetManagement                         | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 24 | Dynamics365SupplyChainExtended                     | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 25 | Dynamics365FinanceExtended                         | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 26 | HCMCommon                                          | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 27 | Dynamics365FinanceAndOperationsCommon              | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 28 | צד                                              | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 29 | Dynamics365Company                                 | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 30 | CurrencyExchangeRates                              | אם לא נמצא, דלג על פתרון זה.                                                            |
    | 31 | AssetCommon                                        | אם לא נמצא, דלג על פתרון זה.                                                            |