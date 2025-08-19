# ​ بوت همسات تلجرام – Whisper Bot

## طريقة التشغيل على Render

1. أنشئ مستودعًا جديدًا على GitHub وأضف الملفات الثلاثة: `main.py`, `requirements.txt`, `README.md`.
2. سجّل أو سجّل دخولك لحسابك في [Render](https://render.com).
3. اربط حساب GitHub الخاص بك وسِجّل المستودع في Render (أنشئ Web Service جديد).
4. ضمن **Environment Variables**:
   - `BOT_TOKEN` = token البوت الخاص بك من BotFather.
5. في إعدادات الخدمة:
   - **Build command**: `pip install -r requirements.txt`
   - **Start command**: `python main.py`
6. اضغط **Deploy** وسيشتغل البوت ويظل شغال ما دامت الخطة مجانية متاحة (750 ساعة شهريًا).

> ملاحظة مهمة:
>  عدّل قيمة `group_id` في الكود إلى الـID الصحيح للمجموعة التي تريد أن يعمل فيها البوت.
