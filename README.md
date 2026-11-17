# DESHISHA

# حزمة Private CRM – Google AI Studio

هذه حزمة تحويل هندسي ومواصفات وتعليمات لـ Google AI Studio Build mode، وليست شفرة تطبيق مكتملة أو دليلاً على تنفيذ أو اختبار النظام.

## الاستخدام
1. افتح https://aistudio.google.com/ واختر Build.
2. أرسل `01_AI_STUDIO_PROMPTS/AI_STUDIO_SYSTEM_INSTRUCTIONS.md` كتعليمات أساسية.
3. أرسل `AI_STUDIO_MASTER_PROMPT.md`.
4. ابدأ بالمرحلة 0 فقط باستخدام Prompt المرحلة 0.
5. راجع الأدلة والملفات والاختبارات ثم اعتمد المرحلة صراحة قبل التالية.
6. بعد كل مرحلة صدّر ZIP أو اربط مستودع GitHub خاصاً واحتفظ بنسخة محلية.

## التقنية المعتمدة
React + TypeScript + Tailwind؛ Node.js + TypeScript server؛ REST API؛ PostgreSQL؛ Prisma؛ Docker Compose؛ Nginx؛ Gemini API من الخادم فقط واختياري.

## تنبيهات
- المراحل 0–16 خارطة مستهدفة وليست مراحل منفذة أو معتمدة.
- AI Studio preview لا يثبت نجاح PostgreSQL أو اختبارات الأمان أو النشر الفعلي.
- لا تعتمد على Cloud Run كاستضافة نهائية؛ الهدف تشغيل ذاتي على Dell R930 بعد فحصه.
- لا تستخدم Firestore كقاعدة CRM رئيسية.
- لا تضع أسراراً في Git أو كود المتصفح.
- لا تفتح PostgreSQL أو Docker API للإنترنت.
- لا تمسح أو تهيئ أقراص السيرفر ضمن هذا المشروع.
