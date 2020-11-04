---
title: התקנת נתונים לדוגמה
description: נושא זה מספק מידע על התקנת נתוני דוגמה ב-Project Service Automation.
ms.custom: dyn365-projectservice
ms.date: 11/08/2018
ms.service: dynamics-365-customerservice
ms.reviewer: kfend
ms.suite: ''
applies_to: Dynamics 365 Project Service Automation
author: ruhercul
ms.author: ruhercul
search.audienceType: IT Pro, Developer
search.app: ''
ms.openlocfilehash: 46dbd8d125396baa97537ea5d11c47864558c113
ms.sourcegitcommit: 5c4c9bf3ba018562d6cb3443c01d550489c415fa
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 10/16/2020
ms.locfileid: "4077373"
---
# <a name="sample-data-installation-for-the-project-service-application"></a><span data-ttu-id="ec720-103">התקנת הנתונים לדוגמה עבור Project Service</span><span class="sxs-lookup"><span data-stu-id="ec720-103">Sample data installation for the Project Service application</span></span>

<span data-ttu-id="ec720-104">כדי לעזור לך לבנות סביבות הדגמה משלך, Microsoft מספקת חבילות נתונים לדוגמה שניתן להוריד, שמציגות את היכולות של היישומים שלך.</span><span class="sxs-lookup"><span data-stu-id="ec720-104">To help you build your own demo environments, Microsoft provides downloadable sample data packages that showcase the capabilities of your apps.</span></span> <span data-ttu-id="ec720-105">קיימים שני סוגים של חבילות נתונים לדוגמה:</span><span class="sxs-lookup"><span data-stu-id="ec720-105">There are two types of sample data packages:</span></span>
- <span data-ttu-id="ec720-106">נתוני הפניה/הגדרה</span><span class="sxs-lookup"><span data-stu-id="ec720-106">reference/setup data</span></span>
- <span data-ttu-id="ec720-107">נתוני הדגמה (הפניה/הגדרה ונתוני טרנזקציות, כגון הזמנות עבודה ופרוייקטים)</span><span class="sxs-lookup"><span data-stu-id="ec720-107">demo data (reference/setup and transactional data such as work orders and projects)</span></span>

<span data-ttu-id="ec720-108">חבילות נתוני **הפניה** לדוגמה ניתנות להורדה בשלוש חבילות נפרדות, כך שבאפשרותך להתקין נתונים רק עבור Project Service או רק עבור Field Service, או להתקין את הנתונים לדוגמה עבור שני היישומים בו-זמנית.</span><span class="sxs-lookup"><span data-stu-id="ec720-108">The sample **reference** data packages are downloadable in three different packages, so you can install data only for Project Service, or only for Field Service, or you can install sample data for both applications at once.</span></span>

<span data-ttu-id="ec720-109">חבילות נתוני הגדרה/הפניה לדוגמה הן:</span><span class="sxs-lookup"><span data-stu-id="ec720-109">The sample setup/reference data packages are:</span></span>

- [<span data-ttu-id="ec720-110">**V902PSMasterData** - Project Service גירסה 3.x בלבד</span><span class="sxs-lookup"><span data-stu-id="ec720-110">**V902PSMasterData** - Project Service version 3.x only</span></span>](https://go.microsoft.com/fwlink/?linkid=2026540&clcid=0x409)

- [<span data-ttu-id="ec720-111">**V902FSMasterData** - Field Service גירסה 8.x בלבד</span><span class="sxs-lookup"><span data-stu-id="ec720-111">**V902FSMasterData** - Field Service version 8.x only</span></span>](https://go.microsoft.com/fwlink/?linkid=2026536&clcid=0x409)

- [<span data-ttu-id="ec720-112">**V902FPSMasterData** - Field Service 8.x ו- Project Service 3.x</span><span class="sxs-lookup"><span data-stu-id="ec720-112">**V902FPSMasterData** - Field Service 8.x and Project Service 3.x</span></span>](https://go.microsoft.com/fwlink/?linkid=2026041&clcid=0x409)

<span data-ttu-id="ec720-113">חבילת נתוני **הדגמה** האחרונה היא:</span><span class="sxs-lookup"><span data-stu-id="ec720-113">The latest **demo** data package is:</span></span>

 - [<span data-ttu-id="ec720-114">**FPSDemoData** - Field Service 8.x ו- Project Service 3.x</span><span class="sxs-lookup"><span data-stu-id="ec720-114">**FPSDemoData** - Field Service 8.x and Project Service 3.x</span></span>](https://aka.ms/fpsdemodatapackage)

   <span data-ttu-id="ec720-115">הוראות התקנה משתנות מעט במקטע 'משתמשים ליצירה ולהגדרה' אך היתר זהה ל [**לפרסום הבלוג**](https://aka.ms/fpsdemodatablog) הקודם.</span><span class="sxs-lookup"><span data-stu-id="ec720-115">Installation instructions differ slightly in the users to create and configure section but the rest is the same as in the previous [**blog post**](https://aka.ms/fpsdemodatablog).</span></span> <span data-ttu-id="ec720-116">חבילה זו כוללת קבוצת נתוני הדגמה מופחתת והתקנתה אורכת כ- 3 שעות.</span><span class="sxs-lookup"><span data-stu-id="ec720-116">This package features a reduced demo data set and takes approximately 3 hours to install.</span></span>

<span data-ttu-id="ec720-117">חבילות אלו של נתונים לדוגמה זמינות באנגלית בלבד.</span><span class="sxs-lookup"><span data-stu-id="ec720-117">These sample data packages are available in English only.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="ec720-118">**אין דרך להסיר את התקנת הנתונים לדוגמה.**</span><span class="sxs-lookup"><span data-stu-id="ec720-118">**There is no way to uninstall the sample data.**</span></span> <span data-ttu-id="ec720-119">עליך להתקין חבילות אלו רק במערכות הדגמה, הערכה, הדרכה או בדיקה.</span><span class="sxs-lookup"><span data-stu-id="ec720-119">You should only install these packages on demonstration, evaluation, training, or test systems.</span></span> <span data-ttu-id="ec720-120">בנוסף, שים לב שאין תמיכה בהתקנת חבילה יחידה ולאחר מכן התקנה של חבילה יחידה אחרת.</span><span class="sxs-lookup"><span data-stu-id="ec720-120">Also note that installing an individual package, and then installing the other individual package, is not supported.</span></span> <span data-ttu-id="ec720-121">(במילים אחרות, אין באפשרותך להתקין את **FSMasterData** ואחריו **PSMasterData** , או להפך.) אם לדעתך אתה צריך נתונים לדוגמה עבור שני יישומים בשלב כלשהו בעתיד, עליך להתקין חבילת **v902FPSMasterData**.</span><span class="sxs-lookup"><span data-stu-id="ec720-121">(In other words, you can't install **FSMasterData** followed by **PSMasterData** , or vice versa.) If you see yourself needing sample data for both applications at any point in the future, you should install the **v902FPSMasterData** package.</span></span>

<span data-ttu-id="ec720-122">כאשר אתה מתקין אחת מחבילות הנתונים לדוגמה, תהליך ההתקנה יבצע את הפעולות הבאות:</span><span class="sxs-lookup"><span data-stu-id="ec720-122">When you install any of the sample data packages, the installation process performs the following actions:</span></span>

- <span data-ttu-id="ec720-123">יצירה או הגדרה של ברירת מחדל לפרמטרים לצורך שימוש ב-Project Service, ב-Field Service או בשני היישומים (אם ישים).</span><span class="sxs-lookup"><span data-stu-id="ec720-123">Creates or sets default parameters for using Project Service, Field Service, or both applications (if applicable).</span></span>

- <span data-ttu-id="ec720-124">ייבוא נתונים לדוגמה עבור היישומים, כגון משאבים שניתנים להזמנה, תפקידים ספציפיים ליישום, רשימות של מכירות ומחירונים, יחידות ארגוניות, רשומות של תהליכי מכירה וישויות אחרות כדי להדגים יכולות מרכזיות.</span><span class="sxs-lookup"><span data-stu-id="ec720-124">Imports sample data for the applications, such as bookable resources, application-specific roles, sales and cost price lists, organizational units, sales process records, and other entities to demonstrate key capabilities.</span></span>  

<span data-ttu-id="ec720-125">עם חבילת **נתונים לדוגמה** , תקבל את הנתונים לעיל ונתוני טרנזקציות נוספים, כגון הזמנות עבודה ופרוייקטים.</span><span class="sxs-lookup"><span data-stu-id="ec720-125">With the **demo data** package, you get the above and additional transactional data such as work orders and projects.</span></span>

<span data-ttu-id="ec720-126">האם אתה תוהה אילו יכולות באפשרותך להדגים עם הנתונים לדוגמה?</span><span class="sxs-lookup"><span data-stu-id="ec720-126">Wondering what capabilities you can demo with the sample data?</span></span> <span data-ttu-id="ec720-127">עיין בתרחיש הבדוי Fabrikam Robotics ב[‏‫הערות טכניות‬](#technical-notes).</span><span class="sxs-lookup"><span data-stu-id="ec720-127">See the Fabrikam Robotics fictitious scenario in [Technical notes](#technical-notes).</span></span>

<span data-ttu-id="ec720-128">אם יש לך שאלות לגבי התקנת חבילות אלה של נתונים לדוגמה, [שלח לנו הודעת דואר אלקטרוני אל fpsdemodata@microsoft.com](mailto:fpsdemodata@microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="ec720-128">If you have questions about installing these sample data packages, [send us an email at fpsdemodata@microsoft.com](mailto:fpsdemodata@microsoft.com).</span></span>

## <a name="requirements"></a><span data-ttu-id="ec720-129">דרישות</span><span class="sxs-lookup"><span data-stu-id="ec720-129">Requirements</span></span>

<span data-ttu-id="ec720-130">פרוטוקול ההתקנה מניח כמה הנחות לגבי מופע היעד שלך (הארגוני):</span><span class="sxs-lookup"><span data-stu-id="ec720-130">The installation protocol assumes the following about your target instance (org):</span></span>

- <span data-ttu-id="ec720-131">שפת הבסיס היא אנגלית, ומטבע הבסיס הוא דולר אמריקני (USD, $).</span><span class="sxs-lookup"><span data-stu-id="ec720-131">Base language is English and base currency is US dollar (USD,$).</span></span>

- <span data-ttu-id="ec720-132">לארגון עדיין אין נתונים של Project Service או של Field Service, או שיש לו רק נתוני ברירת מחדל גולמיים המגיעים עם כל ארגון חדש.</span><span class="sxs-lookup"><span data-stu-id="ec720-132">The org has no Project Service or Field Service data already, or only has barebones default data that comes with any new org.</span></span>

- <span data-ttu-id="ec720-133">כבר הותקנה הגירסה הנכונה של יישומים עסקיים:</span><span class="sxs-lookup"><span data-stu-id="ec720-133">The correct version of the business application is already installed:</span></span>
       
    - <span data-ttu-id="ec720-134">**עבור FPSDemoData או v902FPSMasterData:** בארגון מותקנות גירסה Field Service 8.x ו- Project Service 3. x.</span><span class="sxs-lookup"><span data-stu-id="ec720-134">**For FPSDemoData or v902FPSMasterData:** The org has Field Service version 8.x and Project Service version 3.x installed.</span></span>

    - <span data-ttu-id="ec720-135">**עבור v902PSMasterData:** בארגון מותקנת גירסה 3. x של Project Service.</span><span class="sxs-lookup"><span data-stu-id="ec720-135">**For v902PSMasterData:** The org has Project Service version 3.x installed.</span></span>

    - <span data-ttu-id="ec720-136">**עבור v902FSMasterData:** בארגון מותקנת גירסה ‎ 8.xשל Field Service.</span><span class="sxs-lookup"><span data-stu-id="ec720-136">**For v902FSMasterData:** The org has Field Service version 8.x installed.</span></span>

> [!NOTE]
> <span data-ttu-id="ec720-137">אם עליך להתקין את הנתונים לדוגמה מעל גירסת ניסיון קיימת של Field Service ו-Project Service או סביבת הדגמה שכבר יש בה נתונים (לא מומלץ), יהיה עליך להפסיק את בדיקות הבטיחות המבוצעות על-ידי תוכנית ההתקנה.</span><span class="sxs-lookup"><span data-stu-id="ec720-137">If you need to install the sample data on top of an existing Project Service and Field Service trial or demo environment that already has data (not recommended), you'll need to suspend the safety prechecks performed by the installer.</span></span> <span data-ttu-id="ec720-138">לקבלת מידע נוסף, עיין בהערות הטכניות שבהמשך.</span><span class="sxs-lookup"><span data-stu-id="ec720-138">For more information, see the technical notes below.</span></span>

## <a name="prepare-for-installation"></a><span data-ttu-id="ec720-139">התכונן להתקנה</span><span class="sxs-lookup"><span data-stu-id="ec720-139">Prepare for installation</span></span>

<span data-ttu-id="ec720-140">עליך להפעיל את תוכנית ההתקנה במחשב עם גירסה עדכנית של Windows‏ (Windows 10 מועדף).</span><span class="sxs-lookup"><span data-stu-id="ec720-140">You need to run the installer on a computer with a recent version of Windows (Windows 10 preferred).</span></span>

<span data-ttu-id="ec720-141">עליך לתכנן כך שהמחשב יישאר מחובר לרשת, ושההתקנה תפעל במשך פרק זמן של עד **שעה** עבור **נתוני הגדרה/הפניה**.</span><span class="sxs-lookup"><span data-stu-id="ec720-141">You should plan for the computer to remain connected to a network, and for the installation to run for up to **1 hour** for **setup/reference data**.</span></span> <span data-ttu-id="ec720-142">(בדרך כלל ההתקנה אורכת בסביבות 30 דקות עבור **FPSMasterData** , שכולל נתונים לדוגמה עבור שני היישומים.) עבור **FPSDemoData** , ההתקנה תימשך סביב **3 שעות**.</span><span class="sxs-lookup"><span data-stu-id="ec720-142">(Normally the installation takes around 30 minutes for **FPSMasterData** , which includes sample data for both applications.) For the **FPSDemoData** , the installation will take around **3 hours**.</span></span>

<span data-ttu-id="ec720-143">הפונקציה של שומר מסך במחשב צריכה להיות כבויה.</span><span class="sxs-lookup"><span data-stu-id="ec720-143">The computer should have the screen saver function turned off.</span></span> <span data-ttu-id="ec720-144">אחרת, אישורי ההפעלה של ההתקנה יאבדו כאשר שומר המסך פעיל (אלא אם תשמור את ההפעלה פעילה).</span><span class="sxs-lookup"><span data-stu-id="ec720-144">Otherwise, session credentials for the installation may be lost when the screen saver engages (unless you keep your session active throughout).</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="ec720-145">![צילום מסך של הגדרות שומר מסך, עם שומר מסך כבוי](media/sample-data-1.png)</span><span class="sxs-lookup"><span data-stu-id="ec720-145">![Screenshot of screen saver settings, with screen saver turned off](media/sample-data-1.png)</span></span>

## <a name="download-and-unpack"></a><span data-ttu-id="ec720-146">הורד וחלץ</span><span class="sxs-lookup"><span data-stu-id="ec720-146">Download and unpack</span></span>

<span data-ttu-id="ec720-147">מתקין הנתונים לדוגמה של Project Service ושל Field Service מופץ בצורה של קובץ הפעלה בחילוץ עצמי.</span><span class="sxs-lookup"><span data-stu-id="ec720-147">The Project Service and Field Service sample data installer is distributed as a self-extracting executable.</span></span> <span data-ttu-id="ec720-148">שמות הקבצים עשויים להשתנות בהתאם לחבילת הנתונים לדוגמה, אך בכל מקרה השלבים זהים כך שלא משנה איזו חבילה התקנת.</span><span class="sxs-lookup"><span data-stu-id="ec720-148">The file names may vary depending on the sample data package, but otherwise the steps are the same no matter which package you install.</span></span>

<span data-ttu-id="ec720-149">לאחר הורדת החבילה, הרץ את קובץ ה-.exe, ולאחר מכן קבל את התנאים כדי לפרוס את קובץ ה-zip הדחוס.</span><span class="sxs-lookup"><span data-stu-id="ec720-149">After downloading a package, run the .exe file, and then accept terms and conditions to unpack the compressed zip file.</span></span> <span data-ttu-id="ec720-150">לאחר מכן עליך לחלץ את תוכן הקובץ לתיקיה במחשב שלך.</span><span class="sxs-lookup"><span data-stu-id="ec720-150">You then need to extract contents of that file to a folder on the computer.</span></span>

<span data-ttu-id="ec720-151">בהתאם למערכת ההפעלה ולהגדרות האבטחה, ייתכן שיהיה עליך לבצע את הפעולות הבאות לאחר פתיחת קובץ ה-zip:</span><span class="sxs-lookup"><span data-stu-id="ec720-151">Depending on the operating system and security settings, you may need to perform the following steps after unpacking the zip file:</span></span>

1. <span data-ttu-id="ec720-152">חפש ולחץ באמצעות לחצן העכבר הימני על קובץ **FPSDemoData.dll** בתיקיה **v902FPSMasterData** / **PackageDeployer_FPSDemoData**.</span><span class="sxs-lookup"><span data-stu-id="ec720-152">Find and right-click the **FPSDemoData.dll** file in the **v902FPSMasterData** / **PackageDeployer_FPSDemoData** folder.</span></span>

2. <span data-ttu-id="ec720-153">בחר **ביטול חסימה**.</span><span class="sxs-lookup"><span data-stu-id="ec720-153">Choose **Unblock**.</span></span>

3. <span data-ttu-id="ec720-154">בחר **החל**.</span><span class="sxs-lookup"><span data-stu-id="ec720-154">Select **Apply**.</span></span>

4. <span data-ttu-id="ec720-155">בחר **אישור**.</span><span class="sxs-lookup"><span data-stu-id="ec720-155">Select **OK**.</span></span>


## <a name="create-or-configure-users"></a><span data-ttu-id="ec720-156">יצירה או קביעת תצורה של משתמשים</span><span class="sxs-lookup"><span data-stu-id="ec720-156">Create or configure users</span></span>

<span data-ttu-id="ec720-157">החבילה **FPSDemoData** דורשת שישה משתמשים, בעוד שחבילות **FPSMasterData** דורשות משתמש אחד.</span><span class="sxs-lookup"><span data-stu-id="ec720-157">The **FPSDemoData** package requires six users while **FPSMasterData** packages require one user.</span></span> <span data-ttu-id="ec720-158">התייחס לחבילה הנכונה עבור חבילת הנתונים לדוגמה שלך.</span><span class="sxs-lookup"><span data-stu-id="ec720-158">Refer to the correct one for your sample data package.</span></span>

## <a name="create-or-configure-users---setupreference-data-packages"></a><span data-ttu-id="ec720-159">יצירה או הגדרה של משתמשים - חבילות נתוני הגדרה/הפניה</span><span class="sxs-lookup"><span data-stu-id="ec720-159">Create or configure users - setup/reference data packages</span></span>

<span data-ttu-id="ec720-160">החבילה **FPSMasterData** מיועדת להתקנה עם משתמש אחד בשם Spencer Low עם ההגדרות המתוארות כאן.</span><span class="sxs-lookup"><span data-stu-id="ec720-160">The **FPSMasterData** package is designed to install with one user named Spencer Low with the settings described here.</span></span> <span data-ttu-id="ec720-161">כדי להתקין את החבילה כראוי, תצטרך ליצור משתמשים (או לשנות להם שם באופן זמני) בסביבה שלך כדי להתאים לתצורת הנתונים לדוגמה.</span><span class="sxs-lookup"><span data-stu-id="ec720-161">To install the package correctly, you need to create (or temporarily rename) users in your environment to match the incoming sample data configuration.</span></span>

<span data-ttu-id="ec720-162">כדי ליצור משתמשים או לקבוע תצורה של משתמשים, עבור אל **הגדרות** > **אבטחה** > **משתמשים** , ובצע את הפעולות הבאות:</span><span class="sxs-lookup"><span data-stu-id="ec720-162">To create or configure users, go to **Settings** > **Security** > **Users** , and do the following:</span></span>

1. <span data-ttu-id="ec720-163">הגדר UserFullname = "Spencer Low" עם שם המשתמש "spencerl" ( **אותיות קטנות** ) לתפקידים של מנהל הפרוייקט ומנהל התרגול.</span><span class="sxs-lookup"><span data-stu-id="ec720-163">Set UserFullname="Spencer Low" with username "spencerl" ( **lowercase** ) to the Project Manager and Practice Manager roles.</span></span>

2. <span data-ttu-id="ec720-164">בחר את המשתמש **Spencer Low** ולאחר מכן בחר ‏‫ **ניהול תפקידים‬**.</span><span class="sxs-lookup"><span data-stu-id="ec720-164">Select the **Spencer Low** user, and then select **Manage Roles**.</span></span> <span data-ttu-id="ec720-165">חפש ובחר את התפקיד **מנהל המערכת** , ולאחר מכן בחר **אישור** כדי להעניק הרשאות ניהול מלאות ל-Spencer Low.</span><span class="sxs-lookup"><span data-stu-id="ec720-165">Find and select the **System Administrator** role, and then select **OK** to grant full admin rights to Spencer Low.</span></span> <span data-ttu-id="ec720-166">שלב זה הוא הכרחי כדי להבטיח שרשומות לדוגמה נוצרות עם הבעלות הנכונה של משתמש ולאכלס תצוגות כראוי.</span><span class="sxs-lookup"><span data-stu-id="ec720-166">This step is necessary to ensure that sample records are created with the correct user ownership and therefore populate views correctly.</span></span>

3. <span data-ttu-id="ec720-167">מתוך החבילת שהורדת, עליך לעדכן את קובץ מיפוי הנתונים עם כתובות דואר אלקטרוני של הקשר המשתמש המהווה ברירת מחדל.</span><span class="sxs-lookup"><span data-stu-id="ec720-167">From the downloaded package, you need to update a data mapping file with email addresses of the default user context.</span></span> <span data-ttu-id="ec720-168">כדי לעשות זאת, פתח את **PkgFolder** , ולאחר מכן חפש ופתח את הקובץ **ImportUserMapFile.xml** ב-Notepad (או ב- Visual Studio או בעורך XML אחר).</span><span class="sxs-lookup"><span data-stu-id="ec720-168">To do this, open **PkgFolder** , and then find and open the **ImportUserMapFile.xml** file in Notepad (or Visual Studio or another XML editor).</span></span> <span data-ttu-id="ec720-169">הגדר את השדה **DefaultUserToMapTo =** לכתובת הדואר האלקטרוני של המשתמש Spencer Low.</span><span class="sxs-lookup"><span data-stu-id="ec720-169">Set the **DefaultUserToMapTo=** field to the email address of the Spencer Low user.</span></span>

4. <span data-ttu-id="ec720-170">אם אינך משתמש ב-Spencer Low עם שם משתמש **spencerl** , עליך לעדכן קובץ נוסף.</span><span class="sxs-lookup"><span data-stu-id="ec720-170">If you aren't using Spencer Low with username **spencerl** , you need to update an additional file.</span></span> <span data-ttu-id="ec720-171">פתח את הקובץ **DemoDataPreImportConfig.xml** , ולאחר מכן חפש את התג **userstocreateandconfigure**.</span><span class="sxs-lookup"><span data-stu-id="ec720-171">Open the **DemoDataPreImportConfig.xml** file, and then find the **userstocreateandconfigure** tag.</span></span> <span data-ttu-id="ec720-172">עדכן את התג **\<login\>** עם שם המשתמש של המשתמש שלך.</span><span class="sxs-lookup"><span data-stu-id="ec720-172">Update the **\<login\>** tag with the username of your Spencer Low user.</span></span> <span data-ttu-id="ec720-173">לקבלת פרטים נוספים, ראה [הערות טכניות](#technical-notes).</span><span class="sxs-lookup"><span data-stu-id="ec720-173">For additional details, see [Technical notes](#technical-notes).</span></span>

## <a name="create-or-configure-users---demo-data-package"></a><span data-ttu-id="ec720-174">יצירה או הגדרה של משתמשים - חבילת נתוני הדגמה</span><span class="sxs-lookup"><span data-stu-id="ec720-174">Create or configure users - demo data package</span></span>

<span data-ttu-id="ec720-175">חבילת נתוני הדגמה דורשת שישה משתמשים.</span><span class="sxs-lookup"><span data-stu-id="ec720-175">The demo data package requires six users.</span></span> <span data-ttu-id="ec720-176">כדי שהחבילה תותקן כראוי, בצע את הפעולות הבאות:</span><span class="sxs-lookup"><span data-stu-id="ec720-176">For the package to install correctly, do the following:</span></span>

 1. <span data-ttu-id="ec720-177">צור או שנה באופן זמני את שם המשתמשים הקיימים כך שיתאימו לתצורת הנתונים לדוגמה הנכנסים על-ידי מעבר אל **הגדרות** > **אבטחה** > **משתמשים**.</span><span class="sxs-lookup"><span data-stu-id="ec720-177">Create or temporarily rename existing users to match incoming sample data configuration by going to **Settings** > **Security** > **Users**.</span></span>
 
    <span data-ttu-id="ec720-178">תפקידים אלה נחוצים רק עבור הדגמות המבוססות על אדם כלשהו.</span><span class="sxs-lookup"><span data-stu-id="ec720-178">These roles are only needed for persona-based demos.</span></span>  
    - <span data-ttu-id="ec720-179">שם מלא של משתמש="David So" כטכנאי Field Service</span><span class="sxs-lookup"><span data-stu-id="ec720-179">User Fullname="David So" as Field Service Technician</span></span>   
    - <span data-ttu-id="ec720-180">שם מלא של משתמש="Jamie Reding" כמשגר Customer Service ו- Field Service</span><span class="sxs-lookup"><span data-stu-id="ec720-180">User Fullname="Jamie Reding" as Customer Service & Field Service Dispatcher</span></span>   
    - <span data-ttu-id="ec720-181">שם מלא של משתמש="Molly Clark" כמנהל תיקי לקוחות</span><span class="sxs-lookup"><span data-stu-id="ec720-181">User Fullname="Molly Clark" as Account Manager</span></span>   
    - <span data-ttu-id="ec720-182">שם מלא של משתמש="Spencer Low" כמנהל פרויקט ושיטת עבודה</span><span class="sxs-lookup"><span data-stu-id="ec720-182">User Fullname="Spencer Low" as Practice and Project Manager</span></span>  
    - <span data-ttu-id="ec720-183">שם מלא של משתמש="Veronica Quek" כחבר צוות</span><span class="sxs-lookup"><span data-stu-id="ec720-183">User Fullname="Veronica Quek" as Team Member</span></span>   
    - <span data-ttu-id="ec720-184">שם מלא של משתמש="William Contoso"</span><span class="sxs-lookup"><span data-stu-id="ec720-184">User Fullname="William Contoso"</span></span>
  
2. <span data-ttu-id="ec720-185">למטרות ייבוא נתוני הדגמה, הקצה לששת המשתמשים שלעיל את תפקיד מנהל המערכת כדי לייבא רשומות לדוגמה כהלכה.</span><span class="sxs-lookup"><span data-stu-id="ec720-185">For the purposes of demo data import, assign the six users above the Administrator role so sample records import correctly.</span></span> 

3. <span data-ttu-id="ec720-186">פתח את **PkgFolder** ולאחר מכן חפש ופתח את **ImportUserMapFile.xml**.</span><span class="sxs-lookup"><span data-stu-id="ec720-186">Open **PkgFolder** and then find and open **ImportUserMapFile.xml**.</span></span> <span data-ttu-id="ec720-187">עדכן את השדות **חדש =** בכתובות דואר אלקטרוני של המשתמשים המתאימים במערכת שלך.</span><span class="sxs-lookup"><span data-stu-id="ec720-187">Update the **New=** fields to the email addresses of corresponding Users in your system.</span></span>

   > [!div class="mx-imgBorder"]
   > <span data-ttu-id="ec720-188">![צילום מסך של UserMapFile](media/sample-data-7.png)</span><span class="sxs-lookup"><span data-stu-id="ec720-188">![Screen shot of UserMapFile](media/sample-data-7.png)</span></span>

4. <span data-ttu-id="ec720-189">אם לשם מלא של משתמש "Spencer Low" יש מזהה משתמש השונה מ- **"spencerl"** , עליך לעדכן קובץ נוסף.</span><span class="sxs-lookup"><span data-stu-id="ec720-189">If your "Spencer Low" full name user has a different user ID than **"spencerl"** , then you need to update an additional file.</span></span> <span data-ttu-id="ec720-190">פתח את **DemoDataPreImportConfig.xml** וחפש את התג **userstocreateandconfigure**.</span><span class="sxs-lookup"><span data-stu-id="ec720-190">Open **DemoDataPreImportConfig.xml** and find the **userstocreateandconfigure** tag.</span></span> <span data-ttu-id="ec720-191">עדכן את התג **\<login\>** ב- loginId (תלוי רישיות).</span><span class="sxs-lookup"><span data-stu-id="ec720-191">Update the **\<login\>** tag with the loginId (case-sensitive).</span></span> 

5. <span data-ttu-id="ec720-192">לוח השנה של המשתמש הראשון (בתג **userstocreateandconfigure** ) משמש לאכלוס שעות העבודה עבור כל המשאבים הניתנים להזמנה בעת ייבוא נתוני הדגמה.</span><span class="sxs-lookup"><span data-stu-id="ec720-192">The first user's calendar (in the **userstocreateandconfigure** tag) is used to populate the work hours for all bookable resources on import of demo data.</span></span> <span data-ttu-id="ec720-193">נווט אל **הגדרות** > **אבטחה** > **משתמשים** , חפש את המשתמש "Spencer Low" ופתח את האפשרות "שעות עבודה".</span><span class="sxs-lookup"><span data-stu-id="ec720-193">Navigate to **Settings** > **Security** > **Users** , find your "Spencer Low" user, and open the "Work Hours" option.</span></span> <span data-ttu-id="ec720-194">ערוך את שעות העבודה הקיימות, תוך בחירת האפשרות **‏‫לוח הזמנים השבועי המחזורי בשלמותו, מן ההתחלה ועד הסיום‬**.</span><span class="sxs-lookup"><span data-stu-id="ec720-194">Edit the existing work hours, selecting the **Entire recurring weekly schedule from start to end** option.</span></span> <span data-ttu-id="ec720-195">ודא כי **שעות העבודה מוגדרות ל- 8 בבוקר עד 5 בערב (9 שעות), בימים שני עד שישי, ואזור הזמן מוגדר לשעון החוף המערבי (ארה"ב וקנדה)**.</span><span class="sxs-lookup"><span data-stu-id="ec720-195">Ensure the **Work hours are set to 8 AM - 5 PM (9 Hours), Monday to Friday and with the Timezone set to Pacific Time (US & Canada)**.</span></span> <span data-ttu-id="ec720-196">הדבר נדרש כדי לוודא כי לוח הפרוייקט ולוח הזמנים מוצגים כצפוי.</span><span class="sxs-lookup"><span data-stu-id="ec720-196">This is needed to ensure that the Project and Schedule board show as expected.</span></span>

<span data-ttu-id="ec720-197">**המלצה:** שקול ליצור גיבוי של הארגון שלך כעת, למקרה שיהיה עליך לחזור לנקודת ההתחלה אם משהו משתבש במהלך התקנת הנתונים לדוגמה.</span><span class="sxs-lookup"><span data-stu-id="ec720-197">**Recommendation:** Consider creating a backup of your org now, in case you need to revert to your starting point if something goes wrong during the sample data installation.</span></span> <span data-ttu-id="ec720-198">לקבלת מידע נוסף, ראה [מופעי גיבוי ושחזור](https://docs.microsoft.com/dynamics365/customer-engagement/admin/backup-restore-instances).</span><span class="sxs-lookup"><span data-stu-id="ec720-198">For more information, see [Backup and restore instances](https://docs.microsoft.com/dynamics365/customer-engagement/admin/backup-restore-instances).</span></span>

## <a name="run-the-package-deployer"></a><span data-ttu-id="ec720-199">הפעל את Package Deployer</span><span class="sxs-lookup"><span data-stu-id="ec720-199">Run the Package Deployer</span></span>

1. <span data-ttu-id="ec720-200">חפש והפעל את **PackageDeployer.exe** בתיקיה **v902FPSMasterData** או **PackageDeployer_FPSDemoData**.</span><span class="sxs-lookup"><span data-stu-id="ec720-200">Find and run **PackageDeployer.exe** in the **v902FPSMasterData** OR **PackageDeployer_FPSDemoData** folder.</span></span>

2. <span data-ttu-id="ec720-201">קבל את התנאים וההתניות.</span><span class="sxs-lookup"><span data-stu-id="ec720-201">Accept the terms and conditions.</span></span>

3. <span data-ttu-id="ec720-202">בחלון הבא:</span><span class="sxs-lookup"><span data-stu-id="ec720-202">On the next window:</span></span>

   <span data-ttu-id="ec720-203">א.</span><span class="sxs-lookup"><span data-stu-id="ec720-203">a.</span></span> <span data-ttu-id="ec720-204">בחר סוג פריסה **Office 365**.</span><span class="sxs-lookup"><span data-stu-id="ec720-204">Select deployment type **Office 365**.</span></span>

   <span data-ttu-id="ec720-205">ב.</span><span class="sxs-lookup"><span data-stu-id="ec720-205">b.</span></span> <span data-ttu-id="ec720-206">השתמש במשתמש ובסיסמה של מנהל המערכת שהוגדר ב"צור או קבע תצורה של משתמשים" ("Spencer Low" עם שם המשתמש "spencerl").</span><span class="sxs-lookup"><span data-stu-id="ec720-206">Use the user and password of the system administrator user configured in "Create or configure users" ("Spencer Low" with "spencerl" username).</span></span>

   <span data-ttu-id="ec720-207">ג.‎</span><span class="sxs-lookup"><span data-stu-id="ec720-207">c.</span></span> <span data-ttu-id="ec720-208">ודא שהאפשרות **הצג רשימה של ארגונים זמינים** נבחרה.</span><span class="sxs-lookup"><span data-stu-id="ec720-208">Make sure **Display list of available organizations** is selected.</span></span>

      > [!div class="mx-imgBorder"]
      > <span data-ttu-id="ec720-209">![צילום מסך של חלון Package Deployer עם סימון של "הצג רשימת ארגונים זמינה"](media/sample-data-2.png)</span><span class="sxs-lookup"><span data-stu-id="ec720-209">![Screenshot of Package Deployer window with "Display list of available organizations" selected](media/sample-data-2.png)</span></span>

4. <span data-ttu-id="ec720-210">בחר את הארגון שבו ברצונך להתקין את הנתונים לדוגמה.</span><span class="sxs-lookup"><span data-stu-id="ec720-210">Select the organization where you want to install the sample data.</span></span>

5. <span data-ttu-id="ec720-211">בחר **הבא** עד שתראה את הדו-שיח **הגדרת נתוני הדגמה**.</span><span class="sxs-lookup"><span data-stu-id="ec720-211">Select **Next** until you see the **Demo Data Setup** dialog.</span></span>

   > [!div class="mx-imgBorder"]
   > <span data-ttu-id="ec720-212">![צילום מסך של חלון מצב המתקין של נתוני הדגמה](media/sample-data-3.png)</span><span class="sxs-lookup"><span data-stu-id="ec720-212">![Screenshot of the demo data installer status window](media/sample-data-3.png)</span></span>

6. <span data-ttu-id="ec720-213">לפני שתמשיך, שים לב שהתקנת הנתונים לדוגמה עלולה להימשך עד שעה (בדרך כלל ~ 10 דקות).</span><span class="sxs-lookup"><span data-stu-id="ec720-213">Before proceeding, note that installing sample data could take up to one hour (normally ~10 minutes).</span></span> <span data-ttu-id="ec720-214">יהיה עליך לוודא כי המחשב נשאר מחובר לרשת במהלך ההתקנה וההפעלה שלך נשארת פעילה.</span><span class="sxs-lookup"><span data-stu-id="ec720-214">You'll need to make sure the computer remains on and connected to a network throughout the installation process, and that your session remains active.</span></span>   

7. <span data-ttu-id="ec720-215">כאשר תהיה מוכן, לחץ על **הבא** כדי להתחיל את תהליך ההתקנה של נתונים לדוגמה.</span><span class="sxs-lookup"><span data-stu-id="ec720-215">When you're ready, click **Next** to start the sample data installation process.</span></span> <span data-ttu-id="ec720-216">לאחר טעינת הנתונים לדוגמה, לחץ על **סיום**.</span><span class="sxs-lookup"><span data-stu-id="ec720-216">After the sample data is loaded, click **Finish**.</span></span>

## <a name="verify-the-sample-data-installation"></a><span data-ttu-id="ec720-217">ודא שהתקנת הנתונים לדוגמה הושלמה</span><span class="sxs-lookup"><span data-stu-id="ec720-217">Verify the sample data installation</span></span>

<span data-ttu-id="ec720-218">לצורך הבדיקה, ודא כי מספר הרשומות וסוגי הישויות מופיעים בתרחיש הפיקטיבי Fabrikam Robotics והם נראים כצפוי.</span><span class="sxs-lookup"><span data-stu-id="ec720-218">For a sanity check, verify that the number of records and types of entities listed in Fabrikam Robotics fictitious scenario appear as expected.</span></span>

<span data-ttu-id="ec720-219">לאחר שהנתונים לדוגמה הועלו, היכנס כמשתמש Spencer Low ואשר את הנקודות הבאות:</span><span class="sxs-lookup"><span data-stu-id="ec720-219">After the sample data completely loads, sign in as the Spencer Low user and confirm the following:</span></span>

- <span data-ttu-id="ec720-220">אם Project Service מותקן, עבור אל **Project Service** > **הגדרות** > **מחירונים**.</span><span class="sxs-lookup"><span data-stu-id="ec720-220">If the Project Service application is installed, go to **Project Service** > **Settings** > **Price Lists**.</span></span> <span data-ttu-id="ec720-221">בדוק כי שיעורי החיוב והעלויות קיימים, עם המטבע המתאים, לכל מדינה/אזור בערכת הנתונים.</span><span class="sxs-lookup"><span data-stu-id="ec720-221">Confirm that bill rates and costs rates exist with the appropriate currency for each country/region in the data set.</span></span>

- <span data-ttu-id="ec720-222">אם היישום Project Service מותקן, עבור אל **Universal Resource Scheduling** > **הגדרות** > **יחידות ארגוניות**.</span><span class="sxs-lookup"><span data-stu-id="ec720-222">If the Project Service application is installed, go to **Universal Resource Scheduling** > **Settings** > **Organizational Units**.</span></span> <span data-ttu-id="ec720-223">אשר כי מחירון עם המטבע המתאים שויך לכל יחידה ארגונית (למעט ערכי עיר).</span><span class="sxs-lookup"><span data-stu-id="ec720-223">Confirm that a cost price list with the appropriate currency has been associated with each org unit (excluding city entries).</span></span> <span data-ttu-id="ec720-224">אם הם חסרים, חפש ושייך את המחירון הנכון.</span><span class="sxs-lookup"><span data-stu-id="ec720-224">If any are missing, find and associate the correct cost price list.</span></span>

- <span data-ttu-id="ec720-225">אם Field Service מותקן, עבור אל **Project Service** > **הגדרות** > **מחירונים**.</span><span class="sxs-lookup"><span data-stu-id="ec720-225">If the Field Service application is installed, go to **Project Service** > **Settings** > **Price Lists**.</span></span> <span data-ttu-id="ec720-226">אשר שתעריפי החיוב והעלויות קיימים.</span><span class="sxs-lookup"><span data-stu-id="ec720-226">Confirm that bill rates and costs rates exist.</span></span> <span data-ttu-id="ec720-227">עבור אל **Field Service** > **הגדרות** > **מחירונים** ובדוק כי שיעורי החיוב והעלויות קיימים, עם המטבע המתאים, לכל מדינה/אזור בערכת הנתונים.</span><span class="sxs-lookup"><span data-stu-id="ec720-227">Go to **Field Service** > **Settings** > **Price Lists** and check that bill rates and costs rates exist, with the appropriate currency, for each country/region in the data set.</span></span>

  > [!div class="mx-imgBorder"]
  > <span data-ttu-id="ec720-228">![צילום מסך של מחירונים פעילים](media/sample-data-4.png)</span><span class="sxs-lookup"><span data-stu-id="ec720-228">![Screenshot of active price lists](media/sample-data-4.png)</span></span>

  > [!div class="mx-imgBorder"]
  > <span data-ttu-id="ec720-229">![צילום מסך של יחידות ארגוניות פעילות](media/sample-data-5.png)</span><span class="sxs-lookup"><span data-stu-id="ec720-229">![Screenshot of active organizational units](media/sample-data-5.png)</span></span>

## <a name="technical-notes"></a><span data-ttu-id="ec720-230">הערות טכניות</span><span class="sxs-lookup"><span data-stu-id="ec720-230">Technical notes</span></span>

<span data-ttu-id="ec720-231">ראה בהמשך פרטים טכניים נוספים לגבי ההתקנה של נתונים אלה.</span><span class="sxs-lookup"><span data-stu-id="ec720-231">See below for more technical details on the installation of this data.</span></span>

### <a name="installing-sample-data-on-top-of-existing-data-not-recommended"></a><span data-ttu-id="ec720-232">התקנת הנתונים לדוגמה על גבי נתונים קיימים (לא מומלץ)</span><span class="sxs-lookup"><span data-stu-id="ec720-232">Installing sample data on top of existing data (not recommended)</span></span>

<span data-ttu-id="ec720-233">הערה: אם עליך להתקין את הנתונים לדוגמה מעל גירסת ניסיון קיימת של Field Service או Project Service או סביבת הדגמה שכבר יש בה נתונים (לא מומלץ), יהיה עליך להפסיק את בדיקות הבטיחות המבוצעות על-ידי תוכנית ההתקנה.</span><span class="sxs-lookup"><span data-stu-id="ec720-233">If you need to install sample data on top of an existing Field Service or Project Service trial or demo environment that already has data, you'll need to suspend the safety prechecks performed by the installer.</span></span>

<span data-ttu-id="ec720-234">כדי לעשות זאת, עבור אל תיקיה **PkgFolder** כדי לחפש ולפתוח את הקובץ **DemoDataPreImportConfig.xml** עם 'פנקס רשימות' (או עורך XML אחר).</span><span class="sxs-lookup"><span data-stu-id="ec720-234">To do this, go to the **PkgFolder** folder to find and open the **DemoDataPreImportConfig.xml** file with Notepad (or another XML editor).</span></span>

<span data-ttu-id="ec720-235">חפש את הערך הבא, ולאחר מכן שנה את ההגדרה true ל-false:</span><span class="sxs-lookup"><span data-stu-id="ec720-235">Find the following value, and then change the setting from true to false:</span></span>

```alias
<TerminateOnPreCheckFailure>true</TerminateOnPreCheckFailure>
```

<span data-ttu-id="ec720-236">שינוי זה גורם למתקין לעקוף כמה בדיקות בטיחות חשובות, כולל:</span><span class="sxs-lookup"><span data-stu-id="ec720-236">This change causes the installer to bypass some important safety checks, including:</span></span>

- <span data-ttu-id="ec720-237">אישור כי אין יותר מפרופיל אחד פעיל של **יחידה ארגונית** ולאחר מכן שינוי השם ל- **Fabrikam US**.</span><span class="sxs-lookup"><span data-stu-id="ec720-237">Confirming that there is no more than one active **Organizational Unit** record, and then renaming it to **Fabrikam US**.</span></span>

- <span data-ttu-id="ec720-238">אישור כי אין יותר מפרופיל אחד פעיל של רשומת **תבנית עבודה**.</span><span class="sxs-lookup"><span data-stu-id="ec720-238">Confirming that there is no more than one active **Work Template** record.</span></span>

- <span data-ttu-id="ec720-239">אישור כי אין יותר מפרופיל אחד פעיל של **פרמטרים בפרויקט** ולאחר מכן שינוי השם של הערך ל- **Parameters**.</span><span class="sxs-lookup"><span data-stu-id="ec720-239">Confirming that there is no more than one active **Project Parameter** record, and then renaming that entry to **Parameters**.</span></span>

### <a name="configuration-components"></a><span data-ttu-id="ec720-240">תצורת רכיבים</span><span class="sxs-lookup"><span data-stu-id="ec720-240">Configuration components</span></span>

<span data-ttu-id="ec720-241">קיימים מספר רכיבי תצורה אחרים בקובץ זה שעבר ייבוא.</span><span class="sxs-lookup"><span data-stu-id="ec720-241">There are a number of other configuration components in this pre-import configuration file.</span></span> <span data-ttu-id="ec720-242">עבור משתמשים טכניים, חלק משינויים אלה כוללים:</span><span class="sxs-lookup"><span data-stu-id="ec720-242">For technical users, some of these include:</span></span>

- <span data-ttu-id="ec720-243">**\<RequiredSolutions\>** מציין התקנות פתרון שהן דרישה מוקדמת ואת מספרי הגירסה שלהם.</span><span class="sxs-lookup"><span data-stu-id="ec720-243">**\<RequiredSolutions\>** specifies prerequisite solution installations and their version numbers.</span></span>

- <span data-ttu-id="ec720-244">**\<InstallSampleData\>** קובע אם יותקנו דוגמאות מוכנות לשימוש עבור היישומים.</span><span class="sxs-lookup"><span data-stu-id="ec720-244">**\<InstallSampleData\>** controls whether out-of-the-box sample data for the apps is installed.</span></span>

    - <span data-ttu-id="ec720-245">False - מדלג על התקנה של נתונים מוכללים אלה (שניתן להסיר)</span><span class="sxs-lookup"><span data-stu-id="ec720-245">false - skips installation of this built-in data (which is removable)</span></span>

    - <span data-ttu-id="ec720-246">True - מתקין את הנתונים המוכללים במקביל להתקנה של הנתונים לדוגמה FS ו- PSA</span><span class="sxs-lookup"><span data-stu-id="ec720-246">true - installs the built-in data concurrent with installation of the FS and PSA sample data</span></span>

- <span data-ttu-id="ec720-247">**\<PreImportDataCollection\>** מציין מפות נתונים בצורת קובץ שטוח ואת הרשומות המשויכות לייבוא לפני ההתקנה הראשית של הנתונים לדוגמה.</span><span class="sxs-lookup"><span data-stu-id="ec720-247">**\<PreImportDataCollection\>** specifies flat-file Data Maps and associated Records to be imported ahead of the main sample data installation.</span></span>

- <span data-ttu-id="ec720-248">**\<EntitiesToEnableScheduling\>** מציין אילו ישויות צריכות להיות מופעלות עבור הזמנה ב- Microsoft Dynamics Scheduling (נקרא גם Universal Resource Scheduling).</span><span class="sxs-lookup"><span data-stu-id="ec720-248">**\<EntitiesToEnableScheduling\>** specifies which entities should be enabled for Booking in Microsoft Dynamics Scheduling (aka Universal Resource Scheduling).</span></span>

- <span data-ttu-id="ec720-249">**\<UsersToCreateAndConfigure\>** מציין משאבים שניתנים להזמנה שיווצרו (אם הם עדיין לא קיימים) לפני ייבוא הנתונים לדוגמה.</span><span class="sxs-lookup"><span data-stu-id="ec720-249">**\<UsersToCreateAndConfigure\>** specifies Bookable Resources that will be created (if they don't exist already) before the sample data import executes.</span></span> <span data-ttu-id="ec720-250">שים לב כי משאב הניתן להזמנה של מקור הנתונים לדוגמה תואם לרשומות המשאב הניתן להזמנה של מערכת היעד וב-FullName ובכניסה של כל משאב.</span><span class="sxs-lookup"><span data-stu-id="ec720-250">Note that the source system sample data Bookable Resource match with the target system Bookable Resource records on the FullName and login of each resource.</span></span> <span data-ttu-id="ec720-251">לפיכך, אין אפשרות לשנות את השמות בקובץ זה של קביעת תצורה מראש, אלא אם ראשית ביצעת ייבוא של הנתונים לדוגמה לתוך מערכת היעד באמצעות שמות אלה ולאחר מכן שינית את שמות המשאבים הניתנים להזמנה לשם הרצוי יחד עם רשומות המשתמשים הזמינים, ולאחר מכן ביצעת ייצוא של הנתונים כדי שתוכל לייבא אותם לתוך מערכת היעד הסופית שוב (מעדכן את הערכים הישנים והחדשים של **ImportUserMapFile.xml** בהתאם).</span><span class="sxs-lookup"><span data-stu-id="ec720-251">Therefore, it is NOT possible to change the names in this preconfiguration file unless you first import sample data into a target system using these names, then rename the Bookable Resources to your desired name set along with the Enabled User records, and then export the data again for import into your final destination system (updating the **ImportUserMapFile.xml** Old and New entries accordingly).</span></span>

- <span data-ttu-id="ec720-252">**\<PluginsToDisable\>** מציין פריטי שורה נפרדים של יישומי plug-in שצריכים להיות זמינים במהלך ייבוא הנתונים לדוגמה ולאחר מכן יש להפעילם.</span><span class="sxs-lookup"><span data-stu-id="ec720-252">**\<PluginsToDisable\>** specifies very discrete line-item plug-ins that must be disabled during the sample data import and then reenabled afterwards.</span></span>

### <a name="fabrikam-robotics-fictitious-scenario"></a><span data-ttu-id="ec720-253">התרחיש הפיקטיבי Fabrikam Robotics</span><span class="sxs-lookup"><span data-stu-id="ec720-253">Fabrikam Robotics fictitious scenario</span></span>

<span data-ttu-id="ec720-254">חבילות נתוני ההפניה לדוגמה של Field Service ו-Project Service מתקינות את הפתרון **Fabrikam Manufacturing Master Data (v3.0.0.0)‎** , יחד עם כ-4,000 רשומות וכ-40 ישויות שונות.</span><span class="sxs-lookup"><span data-stu-id="ec720-254">The Field Service and Project Service sample reference data packages install the **Fabrikam Manufacturing Master Data (v3.0.0.0) solution** , along with approximately 4,000 records and approximately 40 different entities.</span></span> <span data-ttu-id="ec720-255">חבילות הנתונים לדוגמה הנפרדות של Field Service או Project Service מכילות קבוצת משנה של הנתונים לדוגמה **v902FPSMasterData** עבור יישום זה.</span><span class="sxs-lookup"><span data-stu-id="ec720-255">The separate sample data packages for Field Service or Project Service contain a subset of the **v902FPSMasterData** sample data for that application.</span></span> <span data-ttu-id="ec720-256">חבילת **נתוני ההדגמה** מתקינה את **הפתרון Fabrikam Manufacturing Demo Data (v3.0.0.7)** עם כ- 22,000 רשומות ב- 148 ישויות.</span><span class="sxs-lookup"><span data-stu-id="ec720-256">The **Demo Data** package installs the **Fabrikam Manufacturing Demo Data (v3.0.0.7) solution** with approximately 22,000 records across 148 entities.</span></span>

<span data-ttu-id="ec720-257">החברה הבדויה, Fabrikam Robotics, היא יצרנית של רובוטים בקו הרכבה של מכשירים אלקטרוניים, והיא ידועה באיכות המוצר, חדשנות ושירות לקוחות מוצלח, כולל שירותי התקנה, תכנון, יישום ותחזוקה שוטפת.</span><span class="sxs-lookup"><span data-stu-id="ec720-257">The fictional company, Fabrikam Robotics, is a manufacturer of electronic device assembly line robots and is known for their product quality, innovation, and solid customer service, including installation planning, implementation, and ongoing maintenance services.</span></span> <span data-ttu-id="ec720-258">המשרדים הראשיים של Fabrikam נמצאים בארצות הברית (Fabrikam US), ויש לחברה פעילות שירות המבוססת על פרויקטים בצרפת, בהודו, בבריטניה ובשוויץ.</span><span class="sxs-lookup"><span data-stu-id="ec720-258">Fabrikam is headquartered in the United States (Fabrikam US), and has project-based service operations in France, India, the United Kingdom, and Switzerland.</span></span>

<span data-ttu-id="ec720-259">הפעולות של Field Service מתרכזות בעיקר בארה"ב, באזור סיאטל.</span><span class="sxs-lookup"><span data-stu-id="ec720-259">Field service operations are centered in the United States, mostly in the greater Seattle area.</span></span> <span data-ttu-id="ec720-260">החברה מתמקדת במינוף קישוריות של אינטרנט של הדברים (IoT) כדי לפקח על הביצועים של נכסי הלקוחות ולספק שירותים מקדימים יותר ויותר באתר הלקוח.</span><span class="sxs-lookup"><span data-stu-id="ec720-260">The company is focused on leveraging Internet of Things (IoT) connectivity to monitor customer asset performance and deliver increasingly proactive onsite services.</span></span>

<span data-ttu-id="ec720-261">מבט כולל ברמה גבוהה על הנתונים לדוגמה:</span><span class="sxs-lookup"><span data-stu-id="ec720-261">A high-level overview of the sample data is as follows:</span></span>

- <span data-ttu-id="ec720-262">רכיבים רגילים של נתונים לדוגמה (כלול עבור שני יישומים)</span><span class="sxs-lookup"><span data-stu-id="ec720-262">Common sample data elements (included for both applications)</span></span>

    - <span data-ttu-id="ec720-263">משתמש 1</span><span class="sxs-lookup"><span data-stu-id="ec720-263">1 user</span></span>

    - <span data-ttu-id="ec720-264">71 תיקי לקוחות</span><span class="sxs-lookup"><span data-stu-id="ec720-264">71 accounts</span></span>

    - <span data-ttu-id="ec720-265">137 אנשי קשר</span><span class="sxs-lookup"><span data-stu-id="ec720-265">137 contacts</span></span>

    - <span data-ttu-id="ec720-266">סוגי תנועות וקטגוריות שונות</span><span class="sxs-lookup"><span data-stu-id="ec720-266">Various transaction types and categories</span></span>

    - <span data-ttu-id="ec720-267">50 מוצרים במחירון אחד</span><span class="sxs-lookup"><span data-stu-id="ec720-267">50 products with 1 product price list</span></span>

    - <span data-ttu-id="ec720-268">14 מחירונים/רשימות עלות</span><span class="sxs-lookup"><span data-stu-id="ec720-268">14 price/cost lists</span></span>

    - <span data-ttu-id="ec720-269">31 מאפיינים (כישורי משאבים) ב-2 מודלים לדירוג עם 3 רמות (דירוג ערכים)</span><span class="sxs-lookup"><span data-stu-id="ec720-269">31 characteristics (resource skills) in 2 rating models with 3 levels (rating values)</span></span>

- <span data-ttu-id="ec720-270">Project Service</span><span class="sxs-lookup"><span data-stu-id="ec720-270">Project Service</span></span>

    - <span data-ttu-id="ec720-271">8 יחידות ארגוניות</span><span class="sxs-lookup"><span data-stu-id="ec720-271">8 organizational units</span></span>

    - <span data-ttu-id="ec720-272">6 רמות ניצול ספציפיות לתפקיד</span><span class="sxs-lookup"><span data-stu-id="ec720-272">6 role-specific utilization levels</span></span>

    - <span data-ttu-id="ec720-273">מעל 2.8 אלף מפרטים של מחיר-תפקיד</span><span class="sxs-lookup"><span data-stu-id="ec720-273">2.8k+ role-price specifications</span></span>

- <span data-ttu-id="ec720-274">Field Service</span><span class="sxs-lookup"><span data-stu-id="ec720-274">Field Service</span></span>

    - <span data-ttu-id="ec720-275">4 אזורים</span><span class="sxs-lookup"><span data-stu-id="ec720-275">4 territories</span></span>

    - <span data-ttu-id="ec720-276">5 סוגי הזמנת עבודה</span><span class="sxs-lookup"><span data-stu-id="ec720-276">5 work order types</span></span>

    - <span data-ttu-id="ec720-277">22 נכסי לקוחות</span><span class="sxs-lookup"><span data-stu-id="ec720-277">22 customer assets</span></span>

    - <span data-ttu-id="ec720-278">9 סוגי אירועים עם מגוון של מאפייני משאבים משויכים (9), שירותים (13) ומשימות שירות (13)</span><span class="sxs-lookup"><span data-stu-id="ec720-278">9 incident types with a range of associated resource characteristics (9), services (13) and service tasks (13)</span></span>
   
<span data-ttu-id="ec720-279">חבילת **נתוני ההדגמה** מתקינה כ- 179 הזמנות עבודה, 12 פרוייקטים ונתוני טרנזקציות קשורים.</span><span class="sxs-lookup"><span data-stu-id="ec720-279">The **Demo Data** package installs approximately 179 work orders, 12 projects, and associated transactional data.</span></span> 

### <a name="change-the-work-hours-for-sample-resources"></a><span data-ttu-id="ec720-280">שנה את שעות העבודה עבור משאבים לדוגמה</span><span class="sxs-lookup"><span data-stu-id="ec720-280">Change the work hours for sample resources</span></span>

<span data-ttu-id="ec720-281">כברירת מחדל, לכל המשאבים הניתנים להזמנה יש לוח שנה עם 24 שעות עבודה.</span><span class="sxs-lookup"><span data-stu-id="ec720-281">By default, all bookable resources have a 24 work hours calendar.</span></span>

<span data-ttu-id="ec720-282">אם עליך לשנות את שעות העבודה עבור משאבים לדוגמה שניתנים להזמנה, עבור אל **Universal Resource Scheduling** > **תזמון** > **משאבים**.</span><span class="sxs-lookup"><span data-stu-id="ec720-282">If you need to change the work hours for sample bookable resources, go to **Universal Resource Scheduling** > **Scheduling** > **Resources**.</span></span>

<span data-ttu-id="ec720-283">בחר משתמש (לדוגמה, Spencer Low) ושנה את שעות עבודה שלו לשעות שברצונך להחיל על משתמשים מרובים.</span><span class="sxs-lookup"><span data-stu-id="ec720-283">Select a user (for example, Spencer Low) and change Spencer's work hours to the hours you want to apply to multiple users.</span></span> <span data-ttu-id="ec720-284">עבור אל **Universal Resource Scheduling** > **הגדרות** > **תבניות שעות עבודה** וערוך את הרשומה **תבנית עבודה המהווה ברירת מחדל**.</span><span class="sxs-lookup"><span data-stu-id="ec720-284">Go to **Universal Resource Scheduling** > **Settings** > **Work Hour Templates** and edit the **Default Work Template** record.</span></span> <span data-ttu-id="ec720-285">בשדה **משאב תבנית** , בחר משתמש עם שעות עבודה שברצונך להחיל על משאבים אחרים.</span><span class="sxs-lookup"><span data-stu-id="ec720-285">In the **Template Resource** field, select a user with work hours that you want to apply to other resources.</span></span> <span data-ttu-id="ec720-286">עבור אל **Universal Resource Scheduling** > **תזמון** > **משאבים** > **משאבים פעילים הניתנים להזמנה**.</span><span class="sxs-lookup"><span data-stu-id="ec720-286">Go to **Universal Resource Scheduling** > **Scheduling** > **Resources** > **Active Bookable Resources**.</span></span> <span data-ttu-id="ec720-287">בחר את המשאבים שברצונך לשנות ולאחר מכן בחר **הגדר לוח שנה**.</span><span class="sxs-lookup"><span data-stu-id="ec720-287">Select the resources you want to change, and then select **Set Calendar**.</span></span> <span data-ttu-id="ec720-288">ברשימה הנפתחת **תבנית עבודה** , בחר את התבנית **שעות העבודה המהוות ברירת מחדל** או תבנית אחרת עם המשאב הנכון ליצירת תבנית.</span><span class="sxs-lookup"><span data-stu-id="ec720-288">On the **Work Template** drop-down list, select the **Default Work Hour** template or another template with the correct templating resource.</span></span> <span data-ttu-id="ec720-289">כאשר אתה עובר ללוח הזמנים, אתה אמור לראות שהמשאבים כעת עדכנו את שעות העבודה.</span><span class="sxs-lookup"><span data-stu-id="ec720-289">When you go to the schedule board, you should see that the resources now have updated work hours.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="ec720-290">![צילום מסך של משאבים פעילים הניתנים להזמנה](media/sample-data-6.png)</span><span class="sxs-lookup"><span data-stu-id="ec720-290">![Screenshot of active bookable resources](media/sample-data-6.png)</span></span>