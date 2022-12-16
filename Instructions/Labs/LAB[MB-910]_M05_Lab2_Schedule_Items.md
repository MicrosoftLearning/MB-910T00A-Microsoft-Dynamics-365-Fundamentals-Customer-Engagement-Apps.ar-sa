---
lab:
  title: 'النشاط المعملي 4.2: جدولة العناصر في Dynamics 365 Field Service'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
ms.openlocfilehash: ca0728e865cf16478ab84f160cf34538e521c91e
ms.sourcegitcommit: 6065e6a662bd0407d37fcc565c1b2da1c916255d
ms.translationtype: HT
ms.contentlocale: ar-SA
ms.lasthandoff: 04/29/2022
ms.locfileid: "144404906"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>الوحدة 4: تعلم أساسيات Dynamics 365 Field Service
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>معمل التدريب 4.2 - جدولة العناصر في Dynamics 365 Field Service

## <a name="lab-setup"></a>إعداد النشاط المعملي

  - **الزمن المقدر**: 20 دقيقة

  **ملاحظة:** لا يمكن فتح جزء متطلبات الحجز في مستعرض Internet Explorer. يُرجى استخدام مستعرض Microsoft Edge أو Google Chrome لإكمال هذا التمرين.
  
## <a name="instructions"></a>الإرشادات

1.  إذا لم يكن مفتوحًا بالفعل، فافتح تطبيق **Dynamics 365 Field Service**.  

2.  باستخدام التنقل على اليسار، حدد **أوامر العمل**.

3.  في **شريط الأوامر**، حدد زر **جديد** لإنشاء أمر عمل جديد.

4.  أكمل تفاصيل أمر العمل على النحو التالي:
    - حساب الخدمة: ADatum Corporation
    - Primary Incident Type: MRI Scanner down
    - Taxable: No
    
5.  حدد **حفظ وإغلاق** لحفظ التغييرات والخروج من أمر العمل الجديد.

6.  في **شريط الأوامر** الخاص **بأمر العمل**، حدد زر **حجز**.  سيؤدي هذا إلى فتح **Schedule Assistant**.  

7.  ينبغي أن تظهر لك خيارات لجدولة العنصر.  حدد سجل **ريان بريم**.

8.  في النافذة **Create Resource Booking**، اضبط **Start Time** على **Top of the next hour**.

9.  اضبط **وقت الانتهاء** على 2.5 ساعة بعد ذلك.  

10. حدد الزر **Book & Exit** لحجز العنصر وترك نافذة الجدولة.  

11. بمجرد العودة إلى أمر العمل، انقر فوق الزر **Save and Close** من **Command Bar**.  

12. باستخدام التنقل الأيسر، حدد **لوحة الجدولة**.

13. في الجزء السفلي من الشاشة في لوحة المتطلبات، حدد **أوامر العمل غير المجدولة**.

14. حدد أمر عمل **Adventure Works** الذي أنشأته مسبقًا باستخدام رقم أمر العمل الذي كتبته. من الخيارات التي تظهر، حدد **البحث عن التوفر**.  

15. سيؤدي هذا إلى فتح **Schedule Assistant**.  

16. ينبغي أن تظهر لك خيارات لجدولة العنصر.  حدد سجل بوب كوزاك.

17. في النافذة **Create Resource Booking**، اضبط **Start Time** على **Top of the next hour**.

18. اضبط **وقت الانتهاء** على 2.5 ساعة بعد ذلك.
  
19. حدد الزر **Book & Exit** لحجز العنصر وترك نافذة الجدولة. 

20. في بعض الأحيان، قد تحتاج إلى إعادة جدولة أمر عمل بناءً على تعارضات الفني أو عناصر أخرى.  يمكن القيام بذلك بسهولة عن طريق استفادة المرسلين من لوحة الجدولة.  

21. انقر في مربع موارد البحث في لوحة الجدولة (الموجودة أعلى عمود اسم المورد مباشرةً)، وأدخِل ريان وحدد موقع أمر العمل المجدول لريان في وقتٍ لاحق اليوم.  

22. انقر بزر الماوس الأيمن فوق أمر العمل، ومن القائمة التي تظهر، حدد **Substitute Resource**، وحدد الزر **Find Substitution**.

