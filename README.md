# Anjoman-biganeh-
<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>انجمن ادیتوران بیگانه</title>
    <style>
        /* ریست پایه */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #0d0d0d, #2c003e, #4b0082);
            color: #ffffff;
            text-align: center;
            padding: 20px;
        }

        .container {
            background: rgba(255, 255, 255, 0.05);
            padding: 40px 30px;
            border-radius: 20px;
            box-shadow: 0 8px 30px rgba(0,0,0,0.7);
            max-width: 800px;
            backdrop-filter: blur(10px);
            animation: fadeIn 2s ease-in-out;
        }

        h1 {
            font-size: 2rem;
            color: #e0c3fc;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #f0f0f0;
        }

        @keyframes fadeIn {
            0% {opacity: 0; transform: translateY(-20px);}
            100% {opacity: 1; transform: translateY(0);}
        }

        /* دکمه آزمایشی (اختیاری) */
        .btn {
            margin-top: 25px;
            padding: 12px 25px;
            border: none;
            border-radius: 50px;
            background: #8a2be2;
            color: #fff;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .btn:hover {
            background: #9b30ff;
            transform: scale(1.05);
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 1.5rem;
            }
            p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>انجمن ادیتوران بیگانه</h1>
        <p>بزرگ‌ترین انجمن ادیتوران در روبیکا، مرجع رسمی طراحان و ادیتورهای حرفه‌ای برای همکاری، انتشار آثار و ارتقای مهارت‌های طراحی و ادیت در محیطی سازمان‌یافته و رسمی</p>
        <!-- دکمه اختیاری -->
        <!-- <button class="btn">عضویت در انجمن</button> -->
    </div>
</body>
</html>
