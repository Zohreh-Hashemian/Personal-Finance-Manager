# Personal Finance Manager | مدیریت مالی شخصی

Personal Finance Manager is a Django-based web application designed to help users manage, track, and organize their personal finances through a simple and intuitive interface.

این پروژه یک برنامه وب مبتنی بر Django برای مدیریت، ثبت و پیگیری امور مالی شخصی است که با هدف فراهم‌کردن ابزاری ساده و کاربردی برای سازمان‌دهی فعالیت‌های مالی طراحی شده است.

---

# 🇬🇧 English

## About the Project

Personal Finance Manager is a Persian-language, right-to-left web application developed with Django for managing and tracking personal finances.

The application allows users to organize their bank cards and cash balances, record income and expenses, transfer money, and review financial reports. It also supports the Jalali calendar for date entry and display.

The project provides a foundation for personal financial management, combining transaction tracking, financial summaries, and visual reports in one application.

## Features

- User authentication
- Individual financial data management for each user
- Bank card and cash wallet management
- Income and expense tracking
- Customizable income and expense categories
- Money transfers between bank cards and cash wallets
- Automatic calculation of bank card balances
- Weekly and monthly financial dashboards
- Income and expense summaries by category
- Recent transaction history and financial charts
- Jalali calendar for date input and display
- Responsive, right-to-left user interface
- Demo data generation for quick testing and evaluation

## Requirements

- Python 3.10 or later
- Git
- Internet connection for installing dependencies

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Zohreh-Hashemian/Personal-Finance-Manager.git
cd Personal-Finance-Manager
```

### 2. Create and Activate a Virtual Environment

**macOS / Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Windows PowerShell:**

```powershell
py -m venv .venv
.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

On macOS or Linux, use `python3` instead of `python` if the latter command is unavailable.

### 4. Apply Database Migrations

```bash
python manage.py migrate
```

### 5. Generate Demo Data

```bash
python manage.py seed_demo
```

### 6. Start the Development Server

```bash
python manage.py runserver
```

Open the following address in your browser:

```text
http://127.0.0.1:8000/
```

Use the following credentials to access the demo account:

**Username:** `demo`

**Password:** `demo1234`

To stop the development server, press `Ctrl+C` in the terminal.

Whenever you want to run the application again, activate your virtual environment and execute the `python manage.py runserver` command.

## Running Tests

To execute the project's tests, run:

```bash
python manage.py test
```

## Notes

- The project uses SQLite as its local database, so installing a separate database server is not necessary.
- The `db.sqlite3` file is generated locally and is excluded from Git version control.
- The Jalali date picker and dashboard charts load browser resources from public CDNs and therefore require an active internet connection.
- The current configuration is intended for local development. Additional security and deployment configurations are required before using it in a production environment.

# 🇮🇷 فارسی

## معرفی پروژه

Personal Finance Manager یک برنامه وب فارسی و راست‌چین است که با فریم‌ورک Django توسعه داده شده و برای مدیریت و پیگیری امور مالی شخصی طراحی شده است.

این برنامه امکان مدیریت کارت‌های بانکی و موجودی نقدی، ثبت درآمد و هزینه، انتقال وجه و بررسی گزارش‌های مالی را فراهم می‌کند. همچنین برای ثبت و نمایش تاریخ‌ها از تقویم شمسی استفاده شده است.

این پروژه مجموعه‌ای از ابزارهای کاربردی مدیریت مالی را در قالب یک برنامه یکپارچه ارائه می‌دهد و امکان مشاهده و بررسی وضعیت مالی را برای کاربران فراهم می‌کند.

## امکانات پروژه

- احراز هویت کاربران و مدیریت ورود و خروج
- تفکیک اطلاعات مالی هر کاربر
- مدیریت کارت‌های بانکی و کیف پول نقدی
- ثبت و پیگیری درآمدها و هزینه‌ها
- ایجاد و مدیریت دسته‌بندی‌های اختصاصی درآمد و هزینه
- انتقال وجه بین کارت‌های بانکی و موجودی نقدی
- محاسبه خودکار موجودی کارت‌های بانکی
- داشبورد مالی با گزارش‌های هفتگی و ماهانه
- ارائه خلاصه درآمد و هزینه بر اساس دسته‌بندی
- نمایش سوابق تراکنش‌های اخیر و نمودارهای مالی
- پشتیبانی از تقویم شمسی برای ورود و نمایش تاریخ
- رابط کاربری راست‌چین و واکنش‌گرا
- تولید اطلاعات نمونه برای آزمایش و بررسی سریع برنامه

## پیش‌نیازها

- Python نسخه 3.10 یا بالاتر
- Git
- دسترسی به اینترنت برای نصب وابستگی‌ها

## نصب و راه‌اندازی

### ۱. دریافت پروژه

```bash
git clone https://github.com/Zohreh-Hashemian/Personal-Finance-Manager.git
cd Personal-Finance-Manager
```

### ۲. ایجاد و فعال‌سازی محیط مجازی

**در macOS و Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

**در Windows PowerShell:**

```powershell
py -m venv .venv
.venv\Scripts\Activate.ps1
```

### ۳. نصب وابستگی‌ها

```bash
python -m pip install -r requirements.txt
```

در سیستم‌عامل‌های macOS و Linux، اگر دستور `python` در دسترس نبود، از `python3` استفاده کنید.

### ۴. ایجاد جداول دیتابیس

```bash
python manage.py migrate
```

### ۵. ساخت اطلاعات آزمایشی

```bash
python manage.py seed_demo
```

### ۶. اجرای برنامه

```bash
python manage.py runserver
```

سپس آدرس زیر را در مرورگر باز کنید:

```text
http://127.0.0.1:8000/
```

برای ورود به حساب آزمایشی از اطلاعات زیر استفاده کنید:

**نام کاربری:** `demo`

**رمز عبور:** `demo1234`

برای متوقف کردن سرور، کلیدهای `Ctrl+C` را در ترمینال فشار دهید.

برای اجرای مجدد برنامه، ابتدا محیط مجازی را فعال کرده و سپس دستور `python manage.py runserver` را اجرا کنید.

## اجرای تست‌ها

برای اجرای تست‌های پروژه، دستور زیر را وارد کنید:

```bash
python manage.py test
```

## نکات تکمیلی

- دیتابیس مورد استفاده در اجرای محلی پروژه SQLite است و نیازی به نصب یا راه‌اندازی یک سرور دیتابیس مجزا ندارد.
- فایل `db.sqlite3` به‌صورت محلی روی سیستم ایجاد می‌شود و در مخزن Git قرار نمی‌گیرد.
- ابزار انتخاب تاریخ شمسی و نمودارهای داشبورد، منابع موردنیاز خود را از CDNهای عمومی دریافت می‌کنند؛ بنابراین برای عملکرد صحیح این قسمت‌ها اتصال اینترنت ضروری است.
- تنظیمات فعلی پروژه با هدف توسعه محلی در نظر گرفته شده است. برای استفاده در محیط عملیاتی (Production)، باید تنظیمات امنیتی و زیرساختی بیشتری اعمال شود.
