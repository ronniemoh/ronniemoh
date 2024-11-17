<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بكج يوم الميلاد</title>
    <style>
        /* إعدادات الصفحة */
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            max-width: 700px;
            width: 90%;
            padding: 40px 30px;
            text-align: center;
        }

        .header {
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 20px;
            color: #444;
        }

        .divider {
            width: 50px;
            height: 3px;
            background: linear-gradient(90deg, #ff7eb3, #ff758c);
            margin: 10px auto 30px;
        }

        .info-list {
            list-style: none;
            padding: 0;
            margin: 0;
            text-align: right;
        }

        .info-list li {
            margin: 15px 0;
            padding: 15px 20px;
            background: #f9f9f9;
            border-radius: 10px;
            display: flex;
            align-items: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .info-list li:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
        }

        .info-list li i {
            font-size: 20px;
            color: #ff758c;
            margin-left: 10px;
        }

        .note {
            font-size: 14px;
            margin-top: 20px;
            color: #555;
            background: #fffbf3;
            padding: 10px;
            border-radius: 8px;
            border: 1px solid #ffd3b6;
        }

        .price {
            font-size: 24px;
            font-weight: bold;
            background: #ff758c;
            color: #fff;
            padding: 15px 30px;
            border-radius: 50px;
            display: inline-block;
            margin-top: 25px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease;
        }

        .price:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
        }

        /* روابط التواصل الاجتماعي */
        .social-links {
            margin-top: 30px;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .social-links a {
            font-size: 20px;
            color: #fff;
            background: #ff758c;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            display: flex;
            justify-content: center;
            align-items: center;
            transition: all 0.3s ease;
            text-decoration: none;
        }

        .social-links a:hover {
            background: #ff7eb3;
            transform: scale(1.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">بكج يوم الميلاد</div>
        <div class="divider"></div>
        <ul class="info-list">
            <li><i>📸</i>يشمل 20 صورة معدلة</li>
            <li><i>🎂</i>عدد الثيمات 2 يشمل كيكة الميلاد</li>
            <li><i>🖼️</i>15 صورة ورقية مطبوعة</li>
            <li><i>🎁</i>بوكس لحفظ الصور</li>
            <li><i>💾</i>فلاش تُرفق فيه جميع صور الجلسة</li>
        </ul>
        <p class="note">لا يشمل اليوم، بالإمكان إضافة اليوم بسعر إضافي</p>
        <div class="price">1200 ريال</div>
        <div class="social-links">
            <a href="https://www.instagram.com" target="_blank" title="Instagram">📸</a>
            <a href="https://www.tiktok.com" target="_blank" title="TikTok">🎵</a>
            <a href="https://wa.me/000000000" target="_blank" title="WhatsApp">💬</a>
        </div>
    </div>
</body>
</html>
