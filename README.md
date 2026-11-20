# Image Text Extraction with PaddleOCR | استخراج متن تصویر با PaddleOCR

**Proposed GitHub repository name:** `paddleocr-image-text`

## Purpose | هدف
Run PaddleOCR on a local image and save recognized text to a text file.

استخراج متن تصویر با PaddleOCR: این مخزن یک نمونهٔ مستقل مبتنی بر یک سلول کد استخراج‌شده است؛ برای شرح کوتاه فارسی، هدف پروژه را در عنوان بالا ببینید.

## Prerequisites | پیش‌نیازها
Python 3.9+; paddleocr; compatible PaddlePaddle build; image backend.

## Install | نصب
Use Python 3 and Jupyter. Install the packages listed in `requirements.txt` with:

```bash
python -m pip install -r requirements.txt
```

پایتون و Jupyter را نصب کنید؛ سپس وابستگی‌های `requirements.txt` را با دستور بالا نصب کنید. برخی وابستگی‌ها اختیاری یا وابسته به سیستم‌عامل/سخت‌افزار هستند.

## Run | اجرا
Open notebook.ipynb in Jupyter; place image at image_path, then run the cell.

فایل `notebook.ipynb` را در Jupyter باز کنید و یک سلول کد آن را اجرا کنید. ورودی‌ها و مسیرهای لازم در بخش محدودیت‌ها آمده‌اند.

## Limitations and input assets | محدودیت‌ها و ورودی‌ها
Requires test2.jpg or adjusting image_path to an image you own. OCR accuracy and installation compatibility vary by platform.

این نمونه‌ها صرفاً آموزشی‌اند و اجرای انتها‌به‌انتها در این بسته تضمین یا تأیید نشده است. ورودی/دادهٔ تخصصی یا سخت‌افزار در صورت نیاز باید جداگانه فراهم شود.
