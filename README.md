# نصب و راه‌اندازی نود شبکه Multiple

## الزامات سخت‌افزاری:
> - **RAM**: 1-2 GB  
> - **CPU**: 1-2 vCPU  
> - **Storage**: 200MB Disk Space  
> - **Network**: 100 Mbps Internet Connection  


## مراحل نصب

### 1. ثبت نام در سایت (ترجیحاً با کیف پول فرعی):  
[سایت Multiple](https://www.app.multiple.cc/#/signup?inviteCode=V0Vuqcr9)

### 2. ایمیل اختیاری:
می‌توانید اضافه کردن ایمیل را فعلاً رد کنید.  

### 3. اجرای نصب خودکار:
```bash
wget -O multiplenode.sh https://raw.githubusercontent.com/0xs3nat0r/multiple-network/refs/heads/main/utils/multiplenode.sh && chmod +x multiplenode.sh && ./multiplenode.sh
```

از طریق لینک زیر میتونید شناسه حسابتون رو هم مشاهده و ذخیره کنید:  
[لینک مشاهده حساب](https://www.app.multiple.cc/#/setup)

### 4. بررسی لاگ‌ها:
```bash
cd ~/multipleforlinux && ./multiple-cli status
```

### 5. پایان!
حالا وضعیت اتصال را در داشبورد بررسی کنید. اگر وضعیت **Connected** بود، کار تمام است. 🎉  
موفق باشید!
