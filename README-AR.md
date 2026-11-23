# Secret Between Us — تحديث قائمة الألعاب

## التعديلات
- الاحتفاظ بلعبة Guess my word كما هي.
- جعل لعبة كلمات سرية — فريقان ظاهرة بعلامة "تحت الصيانة" وتعطيل زر الدخول.
- إضافة روابط ألعاب جاهزة إلى قائمة الألعاب:
  - QuizParty: تفتح نسخة اللعب المستضافة مباشرة.
  - Playhouse: رابط المشروع ومتطلبات تشغيله.
  - GameNight: رابط المشروع ومتطلبات تشغيله.

## ملاحظات تشغيل مهمة
- QuizParty مستضافة على GitHub Pages وتستخدم WebRTC/PeerJS؛ المضيف يحتاج إبقاء الصفحة مفتوحة أثناء المباراة.
- Playhouse مشروع Python/FastAPI + Socket.IO، ولا يعمل بمجرد رفعه إلى GitHub Pages. يحتاج Backend منفصلًا.
- GameNight مشروع Node.js + Socket.IO، ولا يعمل بمجرد رفعه إلى GitHub Pages. يحتاج Backend منفصلًا.
- لم يتم نسخ كود Playhouse إلى هذا المستودع؛ صفحة المشروع لا تعرض ترخيصًا واضحًا لإعادة التوزيع.
- GameNight وQuizParty يعلنان عن ترخيص MIT في مستودعاتهما، لكن هذه الحزمة تضع روابط للمشاريع فقط ولا تدمج ملفات المصدر.
- لم تتم إضافة Cards Against Hackatoa إلى قائمة الموقع لأن محتواه موجّه لجمهور أكبر سنًا.

## الرفع
ارفع محتويات هذا المجلد إلى جذر مستودع GitHub Pages مع استبدال `index.html` فقط. احتفظ بملفي `codenames.html` و`admin.html` كما هما. لا تشغّل أي SQL ولا تحذف أي جدول من Supabase؛ هذه التعديلات تخص واجهة الموقع فقط.

## روابط المصادر
- QuizParty: https://github.com/arvindfroi/quizparty
- Playhouse: https://github.com/sanjinder/MultiplayerGames
- GameNight: https://github.com/abhijatchaturvedi/gamenight
