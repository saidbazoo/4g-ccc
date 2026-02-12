
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الصفحة الرئيسية</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            color: #fff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            text-align: center;
            padding: 30px;
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 20px;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        header {
            margin-bottom: 40px;
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 15px;
            color: #ffd700;
            text-shadow: 0 3px 6px rgba(0, 0, 0, 0.5);
        }
        
        .subtitle {
            font-size: 1.2rem;
            color: #ddd;
            max-width: 700px;
            margin: 0 auto 30px;
            line-height: 1.6;
        }
        
        .links-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
        }
        
        .link-card {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 30px;
            width: 100%;
            max-width: 350px;
            text-align: center;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.2);
            position: relative;
            overflow: hidden;
        }
        
        .link-card:hover {
            transform: translateY(-10px);
            background: rgba(255, 255, 255, 0.15);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
        }
        
        .link-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, #ff416c, #ff4b2b);
        }
        
        .link-card:nth-child(2)::before {
            background: linear-gradient(90deg, #2193b0, #6dd5ed);
        }
        
        .icon {
            font-size: 3.5rem;
            margin-bottom: 20px;
            color: #ffd700;
        }
        
        .link-card:nth-child(2) .icon {
            color: #6dd5ed;
        }
        
        .link-title {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #fff;
        }
        
        .link-desc {
            color: #ccc;
            font-size: 1rem;
            margin-bottom: 25px;
            line-height: 1.5;
        }
        
        .btn {
            display: inline-block;
            background: linear-gradient(45deg, #ff416c, #ff4b2b);
            color: white;
            padding: 12px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(255, 75, 43, 0.4);
        }
        
        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 20px rgba(255, 75, 43, 0.6);
        }
        
        .btn.secondary {
            background: linear-gradient(45deg, #2193b0, #6dd5ed);
            box-shadow: 0 4px 15px rgba(33, 147, 176, 0.4);
        }
        
        .btn.secondary:hover {
            box-shadow: 0 6px 20px rgba(33, 147, 176, 0.6);
        }
        
        footer {
            margin-top: 50px;
            text-align: center;
            color: rgba(255, 255, 255, 0.7);
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            .link-card {
                max-width: 100%;
            }
            
            .links-container {
                gap: 20px;
            }
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>مرحباً بكم </h1>
            <p class="subtitle">  الصفحه الرئيسية</p>
        </header>
        
        <div class="links-container">
            <div class="link-card">
                <div class="icon">
                    <i class="fas fa-file-alt"></i>
                </div>
                <h2 class="link-title">   coverage Dimensioning </h2>
                
                <a href="https://ahman71q-cmyk.github.io/caverage-planning-toll/" class="btn pulse"> اضغط هنا </a>
            </div>
            
            <div class="link-card">
                <div class="icon">
                    <i class="fas fa-file-contract"></i>
                </div>
                <h2 class="link-title"> capacity Dimensioning <h2>
              
                  <a href="https://saidbazoo.github.io/4G/" class="btn pulse">اضغط هنا</a>

            </div>
        </div>
        
        <footer>
            <p>جميع الحقوق محفوظة &copy; 2026 | تم إنشاء هذا الموقع بواسطة tiger & A7K</p>
        </footer>
    </div>

    <script>
        // إضافة تفاعل إضافي للأزرار
        document.querySelectorAll('.btn').forEach(button => {
            button.addEventListener('click', function(e) {
                // يمكنك هنا تغيير الرابط الفعلي
                const pageNumber = this.textContent.includes("الأولى") ? "الأولى" : "الثانية";
                alert(`ستتم إعادة توجيهك إلى الصفحة ${pageNumber} (في التطبيق الفعلي، سيتم إعادة التوجيه إلى الرابط الحقيقي)`);
                
                // في التطبيق الحقيقي، يمكنك إلغاء التعليق عن السطر التالي وتعديل الرابط
                // window.location.href = "page1.html"; أو "page2.html"
            });
        });
        
        // إضافة تأثير عند تحميل الصفحة
        document.addEventListener('DOMContentLoaded', function() {
            const cards = document.querySelectorAll('.link-card');
            cards.forEach((card, index) => {
                card.style.opacity = '0';
                card.style.transform = 'translateY(20px)';
                
                setTimeout(() => {
                    card.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
                    card.style.opacity = '1';
                    card.style.transform = 'translateY(0)';
                }, index * 200);
            });
        });
    </script>
</body>
</html>
