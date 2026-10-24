<div align="center">
  
# ⚡ BITS 
**A Simulated Environment for Logic Gates / یک محیط شبیه‌سازی شده برای گیت‌های منطقی**

[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue.svg)]()
[![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

</div>

---

## 🇬🇧 English Description

This product was created and is made available to you with the aim of providing a simulated environment for working with logic gates.

### 🔍 What are logic gates?
Logic gates are among the main components of an electronic circuit. Logic gates cut off and connect the electrical current based on 0 and 1 input signals. (Like a smart water valve).

### 💡 The Product
Until today, no one had created a product for a normal user to interact with gates. We created a product for a normal user to interact with logic gates so that anyone can work with logic gates, challenge their creativity, learn how to work with gates, and know exactly how they work.
This product works with a terminal environment and is similar to a programming language.

> **Why the number 3 in our logo?** 
> The "3" represents the three fundamental terminals of a transistor (Base, Collector, Emitter) which are the building blocks of all logic gates. It also proudly nods to the creator, **Thirtexe** (derived from "Thirteen").

### ⚙️ Installation

First, download the file suitable for your operating system:
*   **Windows (64-bit):** `Bits.exe`
*   **Linux (64-bit):** `Bits.AppImage`

**Windows:**
After downloading, right-click on the downloaded file and run it. You will enter the Windows terminal. The program opens a terminal for you to execute your commands in it.

**Linux:**
After downloading, grant execute permission to the file:
```bash
chmod +x Bits.AppImage
```
Then, open the terminal in the file's path and execute it:
```bash
./Bits.AppImage
```

### 📖 Tutorial
By entering the `help` command, you can view the list of all commands.
From the opened terminal, you can execute commands and write code. You write each line of code in the terminal, press Enter to write the next line, and later you can execute all the lines together.

**Available Gates:**
`AND` | `OR` | `NOT` | `NAND` | `NOR` | `XOR` | `XNOR` | `LOG`

> **Note:** Every line must definitely start with one of the gates.

### 📝 Syntax
Each gate takes exactly as many inputs as it has in reality. Inputs are separated by `,`.
*   If you give a gate more inputs than it asks for, it only takes the number of inputs it needs.
*   If you give a gate fewer inputs than it asks for, you will encounter an error.

**Example:**
```text
AND(1, 1)  ✅ Correct
AND(1)     ❌ Incorrect
```

You can provide the execution result of another gate as any one of the inputs:
```text
AND(AND(1,1), 0)
```

Each of the inputs of a gate must either be `1` or `0`, and the result of all gates is always the same. If you give a gate a number greater than `1`, it will always read it as `0`.

**The `LOG` Command:**
This command is new and does not exist in reality. This gate takes one input and displays it in the terminal. If you do not use this command, the calculation is performed, but nothing is displayed.

**Gate Details:**
- **AND:** Takes two inputs and gives an output of 1 only if both inputs are 1.
- **OR:** Takes two inputs and gives an output of 1 even if one of the inputs is 1.
- **NOT:** Takes one input and outputs exactly its opposite.
- **NAND:** Takes two inputs and gives an output of 1 only if both inputs are 0.
- **NOR:** Takes two inputs and gives an output of 1 if only one of the inputs is 0.
- **XOR:** Takes two inputs and gives an output of 1 if the two inputs are not equal to each other.
- **XNOR:** Takes two inputs and gives an output of 1 if the two inputs are equal to each other.

<br>

---

## 🇮🇷 توضیحات فارسی

این محصول با هدف فراهم کردن یک محیط شبیه‌سازی شده برای کار با گیت‌های منطقی ساخته شده و در اختیار شما قرار دارد.

### 🔍 گیت‌های منطقی چه چیزی هستند؟
گیت‌های منطقی از اجزای اصلی یک مدار الکترونیکی هستند. گیت‌های منطقی بر اساس سیگنال‌های ورودی 0 و 1 جریان الکتریکی را قطع و وصل می‌کنند. (مانند یک شیر آب هوشمند)

### 💡 محصول
تا به امروز هیچ کسی محصولی برای تعامل یک کاربر عادی با گیت‌ها نساخته بود. ما محصولی برای تعامل یک کاربر عادی با گیت‌های منطقی ساختیم تا هرکسی بتواند با گیت‌های منطقی کار کند، خلاقیت خود را به چالش بکشد، کار با گیت‌ها را یاد بگیرد و بداند که دقیقا آنها چگونه کار می‌کنند.
این محصول با محیط ترمینالی کار می‌کند و شبیه یک زبان برنامه‌نویسی است.

> **چرا عدد ۳ در لوگوی ما؟**
> عدد "۳" نماد سه پایه اساسی یک ترانزیستور (Base, Collector, Emitter) است که پایه‌ی سازنده‌ی تمام گیت‌های منطقی هستند. این عدد همچنین اشاره‌ای افتخارآمیز به سازنده، یعنی **Thirtexe** (برگرفته از Thirteen) دارد.

### ⚙️ نصب

در مرحله اول فایل مناسب سیستم‌عامل خود را دانلود کنید:
*   **ویندوز (۶۴بیتی):** `Bits.exe`
*   **لینوکس (۶۴بیتی):** `Bits.AppImage`

**ویندوز:**
بعد از دانلود روی فایل دانلود شده کلیک‌راست کنید و فایل را اجرا کنید. بعد از این شما وارد ترمینال ویندوز می‌شوید. برنامه برای شما یک ترمینال باز می‌کند تا در آن دستورات خود را اجرا کنید.

**لینوکس:**
بعد از دانلود به فایل اجازه اجرا را بدهید:
```bash
chmod +x Bits.AppImage
```
بعد از اجازه اجرا، در مسیر فایل ترمینال را باز کنید و با دستور زیر فایل را اجرا کنید:
```bash
./Bits.AppImage
```

### 📖 آموزش
با وارد کردن دستور `help` می‌توانید لیست تمامی دستورات را مشاهده کنید.
از ترمینال باز شده می‌توانید برای اجرای دستورات و نوشتن کد استفاده کنید. به این صورت که هر خط کد را در ترمینال می‌نویسید و با زدن اینتر به خط بعدی می‌روید و بعدا می‌توانید همه خط‌ها را با هم اجرا کنید.

**گیت‌ها:**
`AND` | `OR` | `NOT` | `NAND` | `NOR` | `XOR` | `XNOR` | `LOG`

> **نکته:** هر خط حتما باید با یکی از گیت‌ها شروع شود.

### 📝 سینتکس
هر گیت دقیقا به تعداد ورودی‌هایش در واقعیت ورودی می‌گیرد. ورودی‌ها با `,` از هم جدا می‌شوند.
*   اگر به یک گیت بیشتر از خواسته‌اش ورودی بدهید، او فقط به تعدادی که نیاز دارد ورودی برمی‌دارد.
*   اگر به یک گیت کمتر از خواسته‌اش ورودی بدهید، به ارور می‌خورید.

**مثال:**
```text
AND(1, 1)  ✅ درست
AND(1)     ❌ غلط
```

می‌توانید به جای هر یک ورودی، نتیجه اجرای یک گیت دیگر را بدهید:
```text
AND(AND(1,1), 0)
```

هرکدام از ورودی‌های یک گیت یا باید `1` باشند و یا `0` و نتیجه همه گیت‌ها هم همیشه همین است. اگر به یک گیت عددی بیشتر از `1` بدهید، او همیشه آن را `0` می‌خواند.

**دستور `LOG`:**
این دستور جدید است و در واقعیت وجود ندارد. این گیت یک ورودی می‌گیرد و آن را در ترمینال نشان می‌دهد. اگر از این دستور استفاده نکنید، محاسبه انجام می‌شود ولی چیزی نشان داده نمی‌شود.

**جزئیات گیت‌ها:**
- **AND:** دو ورودی می‌گیرد و تنها اگر هر دو ورودی 1 باشند خروجی 1 می‌دهد.
- **OR:** دو ورودی می‌گیرد و حتی اگر یکی از ورودی‌ها هم 1 باشد خروجی 1 می‌دهد.
- **NOT:** یک ورودی می‌گیرد و دقیقا برعکس آن را خروجی می‌دهد.
- **NAND:** دو ورودی می‌گیرد و فقط در صورتی که هر دو ورودی 0 باشند خروجی 1 می‌دهد.
- **NOR:** دو ورودی می‌گیرد و اگر تنها یکی از ورودی‌ها 0 باشد خروجی 1 می‌دهد.
- **XOR:** دو ورودی می‌گیرد و اگر دو ورودی با هم مساوی نباشند خروجی 1 می‌دهد.
- **XNOR:** دو ورودی می‌گیرد و اگر دو ورودی با هم مساوی باشند خروجی 1 می‌دهد.

<br>

---

<div align="center">

## 📬 CONTACT US | ارتباط با ما

[![GitHub](https://img.shields.io/badge/GitHub-Thirtexe-black?style=flat-square&logo=github)](https://github.com/Thirtexe)
[![Telegram](https://img.shields.io/badge/Telegram-Thirtexe-blue?style=flat-square&logo=telegram)](https://t.me/Thirtexe)
[![Email](https://img.shields.io/badge/Email-Thirtexe@gmail.com-red?style=flat-square&logo=gmail)](mailto:Thirtexe@gmail.com)

</div>
