# محول النص إلى صوت

أهلاً بك في تطبيق محول النص إلى صوت!
يتيح لك هذا التطبيق تحويل النصوص الموجودة في قاعدة بيانات SQLite إلى ملفات صوتية
بالاعتماد على مكتبة gTTS (Google Text-to-Speech).

## الخطوات لاستخدام التطبيق:
1. اختر ملف قاعدة البيانات.
2. اختر الجدول والعمود الذي يحتوي على النص.
3. اختر الجدول والعمود الذي سيتم تخزين الصوت فيه.
4. اضغط على زر 'تحويل النص إلى صوت' للبدء في التحويل.

## المتطلبات:
- Python 3
- مكتبة gTTS
- مكتبة tkinter
- مكتبة sqlite3

## كيفية التثبيت:
```sh
pip install gtts
