# n8n Installer

یک اسکریپت ساده و تمام‌خودکار برای نصب یا حذف `n8n` بر روی سرور لینوکسی شما با پشتیبانی از Docker، Docker Compose و دامنه با SSL رایگان (Let's Encrypt) از طریق Traefik.

## ویژگی‌ها

- نصب خودکار Docker و Docker Compose (در صورت نیاز)
- پشتیبانی کامل از دامنه + SSL (Let's Encrypt)
- رابط تعاملی ساده برای نصب یا حذف n8n
- قابلیت اجرا روی IP یا دامنه

## نصب سریع

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/Ptechgithub/n8n-installer/main/n8n.sh)
```

## پیش‌نیازها

- سیستم عامل Ubuntu و سایر توزیع ها 
- دسترسی به `root` یا `sudo`
- دامنه معتبر (اختیاری، برای SSL 

## آدرس دسترسی

- اگر دامنه وارد کرده باشید:
  ```
  https://your-domain.com
  ```

- اگر دامنه وارد نکرده باشید:
  ```
  http://your-server-ip:5678
  ```

## حذف کامل n8n

برای حذف کامل، اسکریپت را دوباره اجرا کرده و گزینه ۲ را انتخاب کنید. این عملیات شامل:

- توقف و حذف کانتینرهای n8n
- حذف کامل دایرکتوری نصب n8n (`n8n-docker/`)

## سورس کد n8n

GitHub: [https://github.com/n8n-io/n8n](https://github.com/n8n-io/n8n)
