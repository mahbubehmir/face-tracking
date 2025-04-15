
# 🎯 پروژه‌ی ردیابی چهره با OpenCV

🎯 پروژه‌ی ردیابی چهره با OpenCV

این پروژه یک سیستم ساده و کاربردی برای تشخیص و ردیابی چهره به‌صورت زنده با استفاده از دوربین است. با استفاده از کتابخانه‌ی OpenCV، چهره‌ها شناسایی شده و در هر فریم به‌صورت خودکار دنبال می‌شوند. سیستم به گونه‌ای طراحی شده که با حرکت سر یا صورت، به‌طور دقیق و سریع، تغییر موقعیت چهره در تصویر ردیابی می‌شود.

ویژگی‌های پروژه:

تشخیص و ردیابی زنده چهره: سیستم قادر است چهره‌های موجود در تصویر را شناسایی کرده و آن‌ها را در فریم‌های بعدی دنبال کند.

حرکت سر موس: این پروژه به گونه‌ای توسعه داده شده که با حرکت سر یا صورت، به‌طور دقیق و با کمترین تأخیر، موقعیت چهره در تصویر ردیابی می‌شود. در این حالت، حرکت صورت کاربر مشابه حرکت نشانگر موس در صفحه است، یعنی با حرکت سر یا صورت، نشانگر موس نیز در صفحه تغییر موقعیت می‌دهد. این ویژگی باعث ایجاد یک تجربه تعاملی و جالب برای کاربران می‌شود.

استفاده از Haar Cascades: برای شناسایی چهره‌ها، از مدل‌های پیش‌آماده‌ی Haar Cascade استفاده شده است که یکی از روش‌های محبوب و سریع برای تشخیص چهره در تصاویر و ویدیوها است.

کاربردهای متنوع: این پروژه می‌تواند در زمینه‌های مختلفی از جمله امنیت، بازی‌های تعاملی، یا حتی به‌عنوان ابزار دسترسی برای افراد با محدودیت‌های فیزیکی کاربرد داشته باشد.

نحوه عملکرد:

ابتدا، از دوربین برای دریافت ویدیو استفاده می‌شود.

در هر فریم ویدیو، سیستم به طور خودکار چهره‌ها را شناسایی می‌کند.

پس از شناسایی چهره، سیستم به‌طور مداوم موقعیت چهره را در فریم‌های بعدی ردیابی می‌کند و این ردیابی باعث حرکت نرم و بدون تأخیر نشانگر موس (یا هر عنصر دیگر) بر اساس حرکت صورت کاربر می‌شود.


## 🧠 ابزارهای استفاده شده

- Python 3.8+
- OpenCV 4.x
- NumPy

---

## 💡 ویژگی‌ها

- تشخیص چهره در ویدئو به‌صورت زنده
- ردیابی پیوسته‌ی چهره با جعبه‌ی اطراف آن (bounding box)
- مناسب برای استفاده در پروژه‌های ساده‌ی نظارتی، آموزشی یا ترکیب با سیستم‌های دیگر

---

## ⚙️ نصب و اجرا

### 1. کلون کردن پروژه:

```bash
git clone https://github.com/YOUR_USERNAME/face-tracking.git
cd face-tracking
```

### 2. نصب پیش‌نیازها:

```bash
pip install -r requirements.txt
```

### 3. اجرای پروژه:

- اگر فایل `.py` داری:

```bash
python face_tracking.py
```

- یا اگر با Jupyter Notebook کار می‌کنی:

```bash
jupyter notebook j1_10_project_face_tracking.ipynb
```

---

## 📁 ساختار پروژه

```
📦 face-tracking
 ┣ 📜 j1_10_project_face_tracking.ipynb
 ┣ 📜 requirements.txt
 ┣ 📜 README.md
 ┗ 📁 assets/         ← اختیاری: شامل ویدیو یا تصویر اجرای پروژه
```

---

## 🛠 ایده برای گسترش پروژه

- شناسایی چند چهره همزمان
- ترکیب با تشخیص احساسات چهره
- تبدیل به اپلیکیشن وب یا موبایل (با Flask یا Streamlit)
- ذخیره چهره‌ها برای حضور و غیاب یا سیستم امنیتی

---

## 🙋‍♀️ درباره من

من محبوبه هستم، متخصص هوش مصنوعی و علاقمند به بینایی ماشین و پروژه‌های هوشمند.  
📫 تماس: niayeshmirshekar92@gmail.com  
🔗 لینکدین: [linkedin.com/in/mahboubeh](#) 

---

## ⭐ اگه این پروژه برات مفید بود خوشحال می‌شم یه ستاره بدی 🌟
