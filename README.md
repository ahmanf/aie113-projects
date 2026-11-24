تجهيز المشروع: ثبتنا مكتبات Python وجهزنا النموذج والبيانات.



تشغيل API: استخدمنا FastAPI لتقديم خدمة كشف الاحتيال، واختبرناها عبر Swagger.



تجهيز Docker: أنشأنا صورة للتطبيق حتى يعمل داخل حاوية مستقلة.



تحسين الأمان:
- استخدمنا Multi-stage Build لتقليل حجم الصورة.
- شغّلنا التطبيق بمستخدم غير المدير appuser بدل root.
- منعنا إدراج الملفات غير الضرورية والأسرار باستخدام .dockerignore.



Docker Compose: شغّلنا خدمتين معًا:
- fraud-api: خدمة كشف الاحتيال.
- feature-cache: قاعدة Redis للتخزين المؤقت.



فحص التشغيل: تأكدنا أن الخدمتين بحالة healthy.



رفع المشروع: نسخنا ملفات المشروع إلى tracks/fraud داخل مستودع aie113-projects وجهزنا Git لرفعها.
العاملين على المشروع
git hub users ( bdra9197, abadii22, ahmanf)
Badr alqarni
abdullah alhamadi
ahmed alnafea
SDAIA Acadimi
