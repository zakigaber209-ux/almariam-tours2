<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>المريم تورز للسياحة - Luxury Edition</title>
    <style>
        :root {
            --bg-color: #ffffff;
            --main-black: #1a1a1a;
            --soft-gray: #f9f9f9;
            --border-color: #dddddd;
            --text-dark: #111111;
            --text-light: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--text-dark);
            line-height: 1.6;
        }

        /* الهيدر */
        header {
            background: var(--main-black);
            color: var(--text-light);
            padding: 60px 20px;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .header-logo {
            width: 450px;
            height: auto;
            margin-bottom: 20px;
        }

        header h1 { margin: 0; font-size: 2.8em; border-bottom: 3px solid white; display: inline-block; padding-bottom: 10px; }
        header p { opacity: 0.9; margin-top: 15px; letter-spacing: 2px; font-size: 1.2em; }

        .container { max-width: 1100px; margin: 20px auto; padding: 20px; }

        /* الجاليري */
        .hero-gallery {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 15px;
            margin-bottom: 50px;
        }
        .hero-gallery img {
            width: 100%;
            height: 400px;
            object-fit: cover;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .side-images { display: flex; flex-direction: column; gap: 15px; }
        .side-images img { height: 192.5px; }

        .section-title {
            text-align: center;
            border-bottom: 2px solid var(--main-black);
            margin: 40px 0;
            padding-bottom: 10px;
            color: var(--main-black);
            font-size: 2em;
        }

        /* برامج العمرة */
        .programs-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 10px;
            margin-bottom: 30px;
        }
        .program-card {
            background: var(--main-black);
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 0.95em;
        }

        /* قسم الوزن (تعديل لتنسيق الأسود والأبيض) */
        .weight-info-box {
            background: var(--main-black);
            color: white;
            padding: 30px;
            border-radius: 10px;
            margin: 40px 0;
            text-align: center;
            border: 2px solid #333;
        }
        .weight-info-box h3 { margin-top: 0; color: #fff; border-bottom: 1px solid #444; padding-bottom: 10px; display: inline-block; }

        /* الفنادق */
        .hotel-item {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-bottom: 40px;
            align-items: center;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 30px;
        }
        .hotel-images img { width: 100%; height: 300px; object-fit: cover; border-radius: 8px; }
        .distance-tag { display: inline-block; background: var(--soft-gray); padding: 5px 15px; font-size: 0.9em; margin-bottom: 15px; border-radius: 20px; border: 1px solid var(--border-color); }

        /* قسم احجز مكانك (قبل التواصل) */
        .booking-promo {
            background: #ffffff;
            padding: 40px;
            text-align: center;
            border-radius: 15px;
            border: 3px solid var(--main-black);
            margin: 50px 0 20px 0;
        }
        .form-btn {
            display: inline-block;
            background: var(--main-black);
            color: white;
            padding: 18px 40px;
            text-decoration: none;
            font-size: 1.4em;
            font-weight: bold;
            border-radius: 5px;
            transition: 0.3s;
        }
        .form-btn:hover { opacity: 0.8; transform: scale(1.02); }

        /* قسم التواصل الشامل */
        .contact-section {
            background: var(--main-black);
            color: white;
            padding: 50px 20px;
            text-align: center;
            border-radius: 15px;
        }
        .contact-grid {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin-top: 25px;
        }
        .contact-link {
            text-decoration: none;
            color: white;
            padding: 12px 25px;
            border-radius: 5px;
            font-weight: bold;
            min-width: 180px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            transition: 0.3s;
        }
        .wa { background: #25D366; }
        .fb { background: #1877F2; }
        .ig { background: #E4405F; }

        footer { background: var(--soft-gray); text-align: center; padding: 40px; border-top: 1px solid var(--border-color); }
        .footer-logo { width: 250px; opacity: 0.8; }

        @media (max-width: 768px) {
            .hero-gallery, .hotel-item { grid-template-columns: 1fr; }
            .header-logo { width: 300px; }
        }
    </style>
</head>
<body>

<header>
    <img src="WhatsApp Image 2026-04-15 at 7.30.55 PM.jpeg" alt="لوجو المريم" class="header-logo">
    <h1>شركة المريم تورز</h1>
    <p>تميز . مصداقية . راحة</p>
</header>

<div class="container">
    
    <div class="hero-gallery">
        <img src="https://www.arabicmagazine.net/Images/Articles/202461112242888.jpg" alt="الكعبة">
        <div class="side-images">
            <img src="https://tripawayjo.com/wp-content/uploads/2023/11/4-61.jpg" alt="مكة">
            <img src="https://cnn-arabic-images.cnn.io/cloudinary/image/upload/w_1920,c_scale,q_auto/cnnarabic/2020/07/12/images/159630.jpg" alt="المدينة">
        </div>
    </div>

    <h2 class="section-title">برامج رحلاتنا</h2>
    <div class="programs-grid">
        <div class="program-card">عمرة المولد النبوي</div>
        <div class="program-card">رحلات شهر رجب</div>
        <div class="program-card">عمرة شعبان</div>
        <div class="program-card">عمرة 50 يوم</div>
        <div class="program-card">عمرة رمضان</div>
        <div class="program-card">شعبان/عودة شوال</div>
    </div>

    <div class="weight-info-box">
        <h3>🧳 تفاصيل الأمتعة والوزن</h3>
        <p>يسمح لكل معتمر بوزن إجمالي: 46 كيلو (موزعة على شنطتين) + 7 كيلو شنطة يد للشحن الداخلي.</p>
        <p>نقدم هدايا قيمة (شنطة ظهر - حذاء - مصلية) لكل معتمر من المريم تورز.</p>
    </div>

    <h2 class="section-title">إقامتكم في مكة والمدينة</h2>
    <div class="hotel-item">
        <div class="hotel-info">
            <span class="distance-tag">📍 محبس الجن - مكة</span>
            <h3>بيوت الجزيرة / أركان بكه</h3>
            <p>خدمة توصيل مجانية للحرم على مدار الساعة باصات كادي المتطورة.</p>
        </div>
        <div class="hotel-images">
            <img src="https://cf.bstatic.com/xdata/images/hotel/max1024x768/440139812.jpg?k=a8c876a33058ee363c5ca321d3ae2feb19bb1a26736e42a857ef80cf04833798&o=" alt="فندق مكة">
        </div>
    </div>

    <div class="hotel-item">
        <div class="hotel-info">
            <span class="distance-tag">📍 المدينة المنورة - خطوات من الحرم</span>
            <h3>مجموعة الزهراء الفندقية</h3>
            <p>إقامة فاخرة بالقرب من باب السلام والروضة الشريفة.</p>
        </div>
        <div class="hotel-images">
            <img src="https://pix10.agoda.net/hotelImages/663/6631130/6631130_19030415240072705406.jpg?ca=7&ce=1&s=1024x768" alt="فندق المدينة">
        </div>
    </div>

    <div class="booking-promo">
        <h2 style="margin-top:0;">جاهز لرحلة العمر؟ ✨</h2>
        <p>اترك بياناتك وسيقوم موظف خدمة العملاء بالتواصل معك فوراً.</p>
        <a href="order.html" class="form-btn">اضغط هنا واحجز مكانك الآن 📝</a>
    </div>

    <div class="contact-section">
        <h3>تواصل معنا مباشرة عبر</h3>
        <div class="contact-grid">
            <a href="https://wa.me/201023472864" class="contact-link wa">واتساب 1 📞</a>
            <a href="https://wa.me/201061875815" class="contact-link wa">واتساب 2 📞</a>
            <a href="https://www.facebook.com/share/1CFnZBnvmG/?mibextid=wwXIfr" class="contact-link fb">فيسبوك 🔵</a>
            <a href="https://www.instagram.com/almariamtours?igsh=MXV0YXBucXU1MHZyaQ%3D%3D&utm_source=qr" class="contact-link ig">إنستجرام 📸</a>
        </div>
    </div>

</div>

<footer>
    <img src="WhatsApp Image 2026-04-15 at 7.30.55 PM.jpeg" alt="Logo" class="footer-logo">
    <p>جميع الحقوق محفوظة &copy; 2024 - شركة المريم تورز للسياحة</p>
    <p style="font-size: 0.8em; opacity: 0.6;">المنصورة - محافظة الدقهلية</p>
</footer>

</body>
</html>
