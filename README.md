# افزونه نمایش دوربین‌های مداربسته در وردپرس 📹  
![CCTV Plugin Banner](https://lh3.googleusercontent.com/d/10VGC-frQq5P-R7q9wbA_1ErrWLNVvNPN)

## فهرست
- [✨ کاربردهای افزونه](#-کاربردهای-افزونه)
- [🚀 امکانات کلیدی](#-امکانات-کلیدی)
- [📦 نحوه نصب](#-نحوه-نصب)
- [⚡ شروع سریع](#-شروع-سریع)
- [🌐 English Version](#-english-version)

---

## ✨ کاربردهای افزونه
این افزونه برای نمایش **دوربین‌های مداربسته در سایت وردپرس** شما طراحی شده است:
- 🏢 نمایش دوربین‌های ساختمان اداری/مسکونی  
- 🏢 نظارت بر محیط کارگاه‌ها و سایت‌های پروژه‌ای  
- 🛍️ نمایش زنده فروشگاه‌ها و مراکز تجاری  
- 👨‍👩‍👧‍👦 نظارت والدین بر محیط منزل از راه دور  
- 🎥 ایجاد تایم‌لیپس (تصاویر متوالی) از محیط  

> 📚 راهنمای جامع نصب و تنظیم:  
> [راهنمای افزونه نمایش دوربین مداربسته در وبسایت](https://intellsoft.ir/guide-to-the-cctv-camera-display-plugin-on-the-website/)

---

## 🚀 امکانات کلیدی
| ویژگی | توضیح |  
|-------|-------|  
| **🔒 امنیت بالا** | رمزنگاری AES-256 اطلاعات دوربین‌ها |  
| **🌐 پشتیبانی از برندها** | هایک‌ویژن، داهوا، یونی‌ویو |  
| **📆 محدوده زمانی** | تعیین تاریخ شروع/پایان نمایش دوربین |  
| **🔄 به‌روزرسانی خودکار** | سیستم کرون جاب برای دریافت تصاویر |  
| **📱 ریسپانسیو** | نمایش مناسب در موبایل و تبلت |  
| **📸 کش تصاویر** | ذخیره تصاویر در سرور برای دسترسی سریع |  
| **🧩 شورت‌کد حرفه‌ای** | نمایش تکی/گروهی دوربین‌ها |  
| **⏱️ تنظیم بازه زمانی** | تعیین فاصله تازه‌سازی (5 تا 3600 ثانیه) |  

---

## 📦 نحوه نصب
1. دانلود فایل زیپ از [صفحه انتشار در گیت‌هاب](https://github.com/intellsoft/wordpress-cctv-timelapse-recorder)  
2. آپلود در مسیر: `پنل وردپرس > افزونه‌ها > افزودن > آپلود`  
3. فعال‌سازی افزونه  
4. تنظیمات در مسیر: `پنل مدیریت > نمایش دوربین‌ها`  

---

## ⚡ شروع سریع
1. افزودن دوربین جدید:  
   ```php
   [secure_cctv id="cam_65a3b1c"]
   ```
2. نمایش تمام دوربین‌های فعال:  
   ```php
   [secure_cctv_all]
   ```
3. تنظیم بازه زمانی:  
   ```php
   /* 30 ثانیه در کد جاوااسکریپت */
   data-refresh-interval="30000"
   ```

```mermaid
graph TD
    A[افزونه CCTV] --> B[مدیریت در پنل وردپرس]
    A --> C[نمایش در سایت]
    B --> D[تنظیمات دوربین]
    B --> E[مدیریت تصاویر]
    C --> F[شورت‌کد تکی]
    C --> G[شورت‌کد گروهی]
    D --> H[اطلاعات اتصال]
    D --> I[تنظیمات زمانی]
    E --> J[ذخیره‌سازی]
    E --> K[حذف خودکار]


📘 راهنمای حرفه‌ای:  
[آموزش کامل تنظیم دوربین‌های هایک‌ویژن و داهوا](https://intellsoft.ir/guide-to-the-cctv-camera-display-plugin-on-the-website/)

---

## 🌐 English Version

# WordPress CCTV Camera Plugin 📹  

## Table of Contents
- [✨ Use Cases](#-use-cases)
- [🚀 Key Features](#-key-features)
- [📦 Installation](#-installation)
- [⚡ Quick Start](#-quick-start)

---

## ✨ Use Cases
Ideal for displaying security cameras on WordPress sites:
- 🏢 Office/residential building surveillance  
- 🏗️ Monitoring construction sites  
- 🛍️ Live view of stores/commercial centers  
- 👨‍👩‍👧‍👦 Remote home monitoring  
- 🎥 Creating timelapse sequences  

> 📚 Full Setup Guide:  
> [Comprehensive CCTV Plugin Documentation](https://intellsoft.ir/guide-to-the-cctv-camera-display-plugin-on-the-website/)

---

## 🚀 Key Features
| Feature | Description |  
|---------|-------------|  
| **🔒 Military-grade Security** | AES-256 data encryption |  
| **🌐 Brand Support** | Hikvision, Dahua, Uniview |  
| **📆 Date Range Control** | Set active period for cameras |  
| **🔄 Auto Refresh** | Cron-based image updates |  
| **📱 Responsive Design** | Mobile & tablet compatible |  
| **📸 Image Caching** | Local storage for fast loading |  
| **🧩 Smart Shortcodes** | Single/group camera display |  
| **⏱️ Custom Intervals** | Refresh rate (5-3600 seconds) |  

---

## 📦 Installation
1. Download ZIP from [GitHub Releases](https://github.com/intellsoft/wordpress-cctv-timelapse-recorder)  
2. Upload via: `WP Admin > Plugins > Add New > Upload`  
3. Activate plugin  
4. Configure at: `Dashboard > CCTV Cameras`  

---

## ⚡ Quick Start
1. Add single camera:  
   ```php
   [secure_cctv id="cam_65a3b1c"]
   ```
2. Display all active cameras:  
   ```php
   [secure_cctv_all]
   ```
3. Set custom refresh interval:  
   ```php
   /* 30 seconds in JavaScript */
   data-refresh-interval="30000"
   ```

📘 Professional Guide:  
[Complete Setup for Hikvision & Dahua Cameras](https://intellsoft.ir/guide-to-the-cctv-camera-display-plugin-on-the-website/)
