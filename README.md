# Omar's Projects Hub

مركز واحد يجمع كل مشاريع **Omar** في رابط واحد. صفحة هبوط سريعة ومتجاوبة تعمل كمنيو رئيسي يوصلك لأي مشروع بضغطة واحدة.

**الموقع المباشر:** [zomariq.github.io/omar-projects-hub](https://zomariq.github.io/omar-projects-hub/)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](#)
[![Dependencies](https://img.shields.io/badge/dependencies-0-4DA3FF?style=flat-square)](#)
[![License](https://img.shields.io/badge/license-MIT-9B8CFF?style=flat-square)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-E9B44C?style=flat-square&logo=github&logoColor=white)](https://zomariq.github.io/omar-projects-hub/)

---

## نظرة عامة

المشروع عبارة عن **ملف واحد** (`index.html`) يحتوي على كل شيء: البنية، التنسيق، الأيقونات، والأكواد التفاعلية.

- **صفر اعتماديات** — لا يوجد `npm install`، ولا إطار عمل، ولا خطوة بناء (build step).
- **الأيقونات مدمجة** — أيقونات Lucide مرسومة كـ SVG داخل الملف نفسه، بدون CDN خارجي.
- **الخطوط من Google Fonts** — عائلة `Reem Kufi` للعناوين و`IBM Plex Sans Arabic` للنصوص.
- **واجهة عربية RTL** بالكامل مع تصميم Dark Mode ومؤثرات تفاعلية.

الملف الوحيد الجاهز للنشر هو `index.html`، وتنشره GitHub Pages كما هو.

---

## المشاريع المربوطة

| # | المشروع | النوع | الوصف | الرابط |
|:-:|---------|-------|-------|--------|
| 1 | **فحص القبول الجامعي** | نظام استرشادي | التحقق من أهلية القبول في أقسام كلية الشرق الأوسط الجامعة وفق الحدود الدنيا للعام الدراسي 2026/2027 | [فتح](https://meuc.omar962012.workers.dev/) |
| 2 | **Valid Worker** | أداة مطوّرين | أداة خدمية على Cloudflare Workers مخصّصة للتحقّق والمعالجة السريعة | [فتح](https://valid.omar962012.workers.dev/) |
| 3 | **بطاقة التخرج التفاعلية** | تصميم تفاعلي | تصميم ويب احتفالي لبطاقة تخرّج مع تأثيرات بصرية وحركة مخصّصة | [فتح](https://graduation-card1.vercel.app/) |

> جميع الروابط تُفتح في تبويب جديد (`target="_blank"` مع `rel="noopener noreferrer"`).

---

## المميزات

- **تصميم متجاوب بالكامل** — يعمل من شاشات 320px (الجوال) حتى الشاشات الكبيرة.
- **بطاقات تفاعلية** — كل بطاقة كاملة قابلة للنقر، مع ارتفاع خفيف عند المرور بالماوس.
- **مؤثر ضوئي يتبع المؤشر** — إضاءة دائرية داخل البطاقة بلون المشروع نفسه.
- **شريط لوني (Rail)** على حافة كل بطاقة يرسم نفسه عند تحميل الصفحة.
- **لون مميّز لكل مشروع** — أزرق للقبول، بنفسجي لأداة المطوّرين، ذهبي لبطاقة التخرج.
- **شعار دائري ثلاثي الألوان** — يمثّل المشاريع الثلاثة مجتمعة في شعار واحد.
- **احترام تفضيلات المستخدم** — يتوقف الأنيميشن تلقائياً عند تفعيل `prefers-reduced-motion`.
- **إمكانية وصول عالية** — تنقل كامل بلوحة المفاتيح، تباين ألوان مطابق لمعايير AA، وأسماء وصفية للروابط.

---

## هيكل الملفات

```
landing-page/
├── index.html      ← الصفحة كاملة (HTML + CSS + JS + الأيقونات)
├── README.md       ← هذا الملف
├── LICENSE         ← رخصة MIT
└── .gitignore      ← ملفات مستثناة من Git
```

لا تحتاج أي ملفات أخرى. الصفحة تعمل بفتح `index.html` مباشرة في المتصفح.

---

## التشغيل محلياً

### الطريقة الأسهل
افتح ملف `index.html` بالنقر المزدوج عليه. سيعمل مباشرة في المتصفح.

### الطريقة الاحترافية (خادم محلي)
بعض المتصفحات تقيّد بعض المميزات عند الفتح عبر `file://`، لذا يُفضّل تشغيل خادم محلي:

```bash
# باستخدام Node.js
npx serve .

# أو باستخدام Python
python -m http.server 8000
```

ثم افتح المتصفح على `http://localhost:8000` (أو المنفذ الذي يظهر لك في الطرفية).

---

## النشر على GitHub Pages

### 1) أنشئ المستودع على GitHub
ادخل إلى [github.com/new](https://github.com/new) وأنشئ مستودعاً باسم:

```
omar-projects-hub
```

اجعله **Public** (مطلوب لتفعيل GitHub Pages مجاناً)، ولا تُضف `README` أو `.gitignore` لأن الملفات موجودة لديك بالفعل.

### 2) ارفع الملفات
اتبع أوامر Git في القسم التالي.

### 3) فعّل Pages
1. ادخل إلى المستودع على GitHub.
2. اذهب إلى **Settings** ← **Pages**.
3. تحت **Build and deployment** ← **Source**، اختر: **Deploy from a branch**.
4. تحت **Branch**، اختر: **`main`** و **`/ (root)`**.
5. اضغط **Save** وانتظر دقيقة تقريباً.

### 4) رابط الموقع
بعد اكتمال النشر سيصبح رابطك:

```
https://zomariq.github.io/omar-projects-hub/
```

> **ملاحظة:** هذا الرابط مُعدّ لحساب `zOmarIQ`. إذا نسخت المشروع لحساب آخر، استبدل `zOmarIQ` باسم المستخدم الجديد في `index.html` وفي هذا الملف.

---

## التخصيص

### تغيير روابط المشاريع
ابحث في `index.html` عن الدومين واستبدله. كل رابط يظهر مرتين: مرة في البطاقة ومرة في التذييل.

```
meuc.omar962012.workers.dev
valid.omar962012.workers.dev
graduation-card1.vercel.app
```

### تغيير رابط المستودع
ابحث عن `zOmarIQ` واستبدله باسم المستخدم الجديد في الموضعين (الهيدر والتذييل).

### تغيير ألوان المشاريع
كل بطاقة تحمل متغيّر `--accent` الخاص بها داخل وسم البطاقة:

```html
<a class="card" style="--accent:#4DA3FF" href="...">
```

عدّل قيمة اللون، وستتغير معها الأيقونة والشريط الجانبي والإضاءة وزر الإجراء تلقائياً.

### تغيير ألوان الواجهة العامة
كل الألوان الأساسية معرّفة في بداية قسم `<style>` داخل `:root`:

```css
:root{
  --bg:          #070A12;   /* خلفية الصفحة */
  --panel:       #0F1524;   /* خلفية البطاقات */
  --paper:       #EAEDF6;   /* لون النص الأساسي */
  --paper-dim:   #98A1BA;   /* النص الثانوي */
  --azure:       #4DA3FF;
  --iris:        #9B8CFF;
  --brass:       #E9B44C;
}
```

### تغيير الخطوط
عدّل رابط Google Fonts في `<head>`، ثم حدّث `font-family` في `body` وفي `.hero__title`.

### تغيير الأيقونات
الأيقونات معرّفة كـ `<symbol>` داخل وسم `<svg class="sprite">` في بداية `<body>`.
لإضافة أيقونة جديدة: انسخ مسارها من [lucide.dev](https://lucide.dev) والصقه كـ `<symbol>`، ثم استدعها بـ:

```html
<svg><use href="#i-اسم-الأيقونة"></use></svg>
```

---

## إضافة مشروع رابع

انسخ أي بطاقة كاملة (`<a class="card">...</a>`) والصقها في قسم `.projects`، ثم:

1. غيّر `--accent` إلى لون جديد.
2. غيّر `href` إلى رابط المشروع.
3. حدّث العنوان والوصف والأيقونة.
4. أضف رابطاً في التذييل.

التنسيق يتم بشكل تلقائي — لا حاجة لتعديل أي CSS.

---

## التقنيات

| التقنية | الاستخدام |
|---------|-----------|
| HTML5 | البنية الدلالية (`header`, `main`, `footer`, `nav`) |
| CSS3 | متغيرات CSS، Grid، Flexbox، `color-mix()`، طبقات الخلفية |
| Vanilla JavaScript | مؤثر الإضاءة التابعة للمؤشر، وتحديث سنة التذييل |
| SVG | أيقونات Lucide وشعار الصفحة والأيقونة المفضّلة (favicon) |
| Google Fonts | `Reem Kufi` + `IBM Plex Sans Arabic` |

### المتصفحات المدعومة
يعمل على كل المتصفحات الحديثة. يعتمد التصميم على `color-mix()` المتوفر في:

- Chrome / Edge 111+
- Safari 16.2+
- Firefox 113+

على المتصفحات الأقدم تعمل الصفحة بشكل كامل، لكن بدون الإضاءة الملوّنة داخل البطاقات (تدرّج آمن).

---

## الرخصة

هذا المشروع مرخّص تحت رخصة **MIT** — راجع ملف [LICENSE](LICENSE) للتفاصيل.

---

## تواصل

صُنع بواسطة **Omar**.

- المستودع: [github.com/zOmarIQ/omar-projects-hub](https://github.com/zOmarIQ/omar-projects-hub)
- الموقع: [zomariq.github.io/omar-projects-hub](https://zomariq.github.io/omar-projects-hub/)
