لغز Tower Of Hanoi الشهير
===============

إذا افترضنا أن لدينا ثلاثة أعمدة أ , ب , ج

على العمود أ يوجد ثلاثة أقراص مرتبة حسب أحجامها الأصغر في الأعلى دائما
والمطلوب نقل جميع الأقراص إلى عمود آخر بنفس الترتيب مع مراعات عدم وضع أي قرص كبير فوق قرص أصغر منه
 

![Image Alt](https://github.com/Mohamed-okasha/iterative_tower_of_hanoi/raw/master/Tower_of_Hanoi.gif)


لحل اللغز بالطريقة التكرارية اتبع الخطوات التالية
======================

* إذا كان عدد الأقراص في العمود أ زوجي انقل قرص من أ إلى ب أما إذا كان فردي انقل قرص من أ إلى ج

* إذا كان عدد الأقراص في العمود ب زوجي انقل قرص من ب إلى أ أما إذا كان فردي انقل قرص من ب إلى ج

* إذا كان عدد الأقرص في العمود ج زوجي انقل قرص من ج إلى أما أإذا كان فردي انقل قرص من ج إلى ب

* لا تقم بنقل أي قرص أكثر من مرتين متتاليتين ،وحافظ على شرط اللغز

فكرة الحل استنتجها الصديق علي الشريف  ، لكن الحل بهذه الطريقة معروف و مشهور أيضا .
