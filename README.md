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
### 4.ثبت شناسه حساب برای نود شبکه:
پس از نصب نود از شما یک شناسه حساب (Account ID) و پین کد(رمزعبور) دریافت میکند :

<img src="https://github.com/user-attachments/assets/c24b3ad2-6993-4886-a572-d8679b638df0" alt="multiper" width="300">

 از طریق لینک روبرو میتونید شناسه حساب رو مشاهده و ثبت کنید: 
 [دریافت Account ID](https://www.app.multiple.cc/#/setup)
 
<img src="https://github.com/user-attachments/assets/5ba03df1-03c7-4408-8e86-b95445b033d4" alt="image" width="300">




### 4. بررسی لاگ‌ها:
```bash
cd ~/multipleforlinux && ./multiple-cli status
```

### 5. پایان!
حالا وضعیت اتصال را در [داشبورد](https://www.app.multiple.cc/#/dataPanel) بررسی کنید. اگر وضعیت **Connected** بود، کار تمام است. 🎉  
موفق باشید!
