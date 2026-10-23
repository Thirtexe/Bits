# BITS

# English Description:

This product was created and is made available to you with the aim of providing a simulated environment for working with logic gates.

## What are logic gates?

Logic gates are among the main components of an electronic circuit. Logic gates cut off and connect the electrical current based on 0 and 1 input signals. (Like a smart water valve)

## Product

Until today, no one had created a product for a normal user to interact with gates. We created a product for a normal user to interact with logic gates so that anyone can work with logic gates, challenge their creativity, learn how to work with gates, and know exactly how they work.
This product works with a terminal environment and is similar to a programming language.

## Installation

In the first step, download the file suitable for your operating system:
Windows (64-bit): `Bits.exe`
Linux (64-bit): `Bits.AppImage`

Windows:
After downloading, right-click on the downloaded file and run it.
And after this, you enter the Windows terminal.
The program opens a terminal for you to execute your commands in it.

Linux:
After downloading, give the file execute permission.
After granting execute permission, open the terminal in the file's path and execute the file with the `./Bits.AppImage` command.
The program opens a terminal for you to execute your commands in it.

Tutorial:
By entering the `help` command, you can view the list of all commands.
From the opened terminal, you can use it to execute commands and write code.
In a way that you write each line of code in the terminal, press Enter to write the next line, and later you can execute all the lines together.
Gates:

- AND
- OR
- NOT
- NAND
- NOR
- XOR
- XNOR
- LOG

Note:
Every line must definitely start with one of the gates.

## Syntax

Each gate takes exactly as many inputs as it has in reality.
Inputs are separated by `,`.
If you give a gate more inputs than it asks for, it only takes the number of inputs it needs, and if you give a gate fewer inputs than it asks for, you will encounter an error.
Example:

AND(1, 1) - Correct
AND(1) - Incorrect

You can provide the execution result of another gate as any one of the inputs.
For example:

AND(AND(1,1), 0)

Each of the inputs of a gate must either be 1 or 0, and the result of all gates is always the same. If you give a gate a number greater than 1, it will always read it as 0.

The `LOG` command:
This command is new and does not exist in reality. This gate takes one input and displays it in the terminal. If you do not use this command, the calculation is performed, but nothing is displayed.

The rest of the gates:

- AND: Takes two inputs and gives an output of 1 only if both inputs are 1
- OR: Takes two inputs and gives an output of 1 even if one of the inputs is 1
- NOT: Takes one input and outputs exactly its opposite
- NAND: Takes two inputs and gives an output of 1 only if both inputs are 0
- NOR: Takes two inputs and gives an output of 1 if only one of the inputs is 0
- XOR: Takes two inputs and gives an output of 1 if the two inputs are not equal to each other
- XNOR: Takes two inputs and gives an output of 1 if the two inputs are equal to each other

# توضیحات فارسی:

این محصول با هدف فراهم کردن یک محیط شبیه‌سازی شده برای کار با گیت‌های منطقی
ساخته شده و در اختیار شما قرار دارد.

## گیت‌های منطقی چه چیزی هستند ؟

گیت‌های منطقی از اجزای اصلی یک مدار الکترونیکی هستند . گیت های منطقی بر اساس سیگنال های ورودی 0 و 1 جریان الکتریکی را قطع و وصل میکنند . (مانند یک شیر آب هوشمند)

## محصول

تا‌‌به امروز هیچ کسی محصولی برای تعامل یک کاربر عادی با گیت‌ها نساخته بود . ما محصولی برای تعامل یک کاربر عادی با گیت های منطقی ‍‍‍‍‍‍‍‍‍‌‍‍‍‍‍‍‍‍‍‍‍ساختیم تا هرکسی بتواند با گیت های منطقی کار کند و خلاقیت خود رو به چالش بکشد و کار با گیت‌هارا یاد بگیرد و بداند که دقیقا آنها چگونه کار میکنند .
این محصول با محیط ترمینالی کار میکند و شبیه یک زبان برنامه‌نویسی است.

## نصب

در مرحله اول فایل مناسب سیستم عامل خود را دانلود کنید:
ویندوز(۶۴‌بیتی): ‍‍`Bits.exe`
لینوکس(۶۴‌بیتی): `Bits.AppImage`

ویندوز:
بعد از دانلود روی فایل دانلود شده کلیک‌راست کنید و فایل را اجرا کنید.
وبعد از این شما وارد ترمینال ویندوز میشوید . 
برنامه برای شما یک ترمینال باز میکند تا در آن دستورات خود را اجرا کنید .

لینوکس:
بعد از دانلود به فایل اجازه اجرا را بدهید . 
بعد از اجازه اجرا در مسیر فایل ترمینال را باز کنید و با دستور `./Bits.AppImage` فایل را اجرا کنید .
برنامه برای شما یک ترمینال باز میکند تا در آن دستورات خود را اجرا کنید .

آموزش:
با وارد کردن دستور `help` میتواند لیست تمامی دستورات را مشاهده کنید.
از ترمینال باز شده میتوانید برای اجرا دستورات و نوشتن کد استفاده کنید . 
جوری که هر خط کد ار در ترمینال مینویسد و با زدن اینتر خط بعدی را مینویسد و بعدا میتوانید همه خط هارا باهم اجرا کنید .
گیت ها:

- AND
- OR
- NOT
- NAND
- NOR
- XOR
- XNOR
- LOG

نکته:
هر خط حتما باید با یکی از گیت‌ها شروع شود .

## سینتکس

هر گیت دقیقا به تعداد ورودی هایش در واقعیت ورودی میگیرد.
ورودی ها با ‍`,` از هم جدا میشوند .
اگر به یک گیت بیشتر از خواسته اش ورودی بدهید او فقط به تعدادی که نیاز دارد ورودی برمیدارد و اگر به یک گیت کمتر از خواسته اش ورودی بدهید به ارور میخورید .
مثال:

AND(1, 1) - درست
AND(1) - غلط
‍‍‍‍
میتوانید بجای هر یک ورودی نتیجه اجرا یک گیت دیگر را بدهید .
مثلا:

AND(AND(1,1), 0)

هرکدام از ورودی های یک گیت یا باید 1 باشند و یا 0 و نتیجه همه گیت ها هم همیشه همین است. اگر به یک گیت عددی بیشتر از 1 بدهید او همیشه آنرا 0 میخواند .

دستور `LOG`:
این دستور جدید است و در واقعیت وجود ندارد . این گیت یک ورودی میگیرد و آنرا در ترمینال نشان میدهد . اگر از این دستور استفاده نکنید محاسبه انجام میشود ولی چیزی نشان داده نمیشود.

بقیه گیت ها :

- AND: دو ورودی میگیرد و تنها اگر هردو ورودی 1 باشند خروجی 1 میدهد
- OR: دو ورودی میگیرد و حتی اگر یکی از ورودی هاهم 1 باشد خروجی 1 میدهد
- NOT: یک ورودی میگیرد و دقیقا برعکس آنرا خروجی میدهد
- NAND: دو ورودی میگیرد و فقط در صورتی که هردو ورودی 0 باشند خروجی 1 میدهد
- NOR: دو ورودی میگیرد و اگر تنها یکی از ورودی ها 0 باشد خروجی 1 میدهد
- XOR: دو ورودی میگیرد و اگر دو ورودی باهم مساوی نباشند خروجی 1 میدهد
- XNOR: دو ورودی میگیرد و اگر دو ورودی باهم مساوی باشند خروجی 1 میدهد


## CONTACT US

Github: @Thirtexe | Telegram: @Thirtexe | Email: Thirtexe@gmail.com
