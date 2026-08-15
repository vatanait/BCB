
<html lang="km">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>ធនាគារ​ ប៊ី ស៊ី ប៊ី | BCB Bank</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Segoe UI", Arial, sans-serif;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            background: #f5f7fb;
            color: #1f2937;
            line-height: 1.7;
        }

        /* ================= HEADER ================= */

        header {
            background: #063b2b;
            color: white;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 3px 15px rgba(0,0,0,.15);
        }

        .navbar {
            max-width: 1200px;
            margin: auto;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 15px 20px;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .logo-icon {
            width: 48px;
            height: 48px;
            border-radius: 50%;
            background: #d6a84f;
            color: #063b2b;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 25px;
            font-weight: bold;
        }

        .logo h1 {
            font-size: 20px;
        }

        .logo small {
            color: #d9e7df;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 15px;
            transition: .3s;
        }

        nav a:hover {
            color: #d6a84f;
        }

        .login-btn {
            background: #d6a84f;
            color: #063b2b;
            padding: 10px 18px;
            border-radius: 7px;
            text-decoration: none;
            font-weight: bold;
        }

        /* ================= HERO ================= */

        .hero {
            background:
                linear-gradient(135deg, rgba(6,59,43,.95), rgba(11,92,67,.88));
            color: white;
            min-height: 570px;
            display: flex;
            align-items: center;
        }

        .hero-container {
            max-width: 1200px;
            margin: auto;
            padding: 60px 20px;
            display: grid;
            grid-template-columns: 1.2fr .8fr;
            gap: 50px;
            align-items: center;
        }

        .hero h2 {
            font-size: 48px;
            line-height: 1.25;
            margin-bottom: 20px;
        }

        .hero h2 span {
            color: #d6a84f;
        }

        .hero p {
            color: #e1eee9;
            font-size: 18px;
            max-width: 650px;
            margin-bottom: 30px;
        }

        .hero-buttons {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }

        .btn-primary,
        .btn-secondary {
            padding: 13px 25px;
            border-radius: 7px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
        }

        .btn-primary {
            background: #d6a84f;
            color: #063b2b;
        }

        .btn-secondary {
            border: 1px solid white;
            color: white;
        }

        .bank-card {
            background: linear-gradient(135deg, #d6a84f, #f0d38b);
            color: #063b2b;
            border-radius: 20px;
            padding: 30px;
            min-height: 280px;
            box-shadow: 0 20px 50px rgba(0,0,0,.25);
            transform: rotate(2deg);
        }

        .bank-card h3 {
            font-size: 25px;
            margin-bottom: 50px;
        }

        .card-number {
            font-size: 21px;
            letter-spacing: 3px;
            margin-bottom: 25px;
        }

        .card-bottom {
            display: flex;
            justify-content: space-between;
        }

        /* ================= GENERAL ================= */

        .section {
            max-width: 1200px;
            margin: auto;
            padding: 75px 20px;
        }

        .section-title {
            text-align: center;
            margin-bottom: 45px;
        }

        .section-title h2 {
            font-size: 32px;
            color: #063b2b;
        }

        .section-title p {
            color: #6b7280;
            margin-top: 8px;
        }

        /* ================= SERVICES ================= */

        .services {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
        }

        .service-card {
            background: white;
            padding: 30px 22px;
            border-radius: 12px;
            text-align: center;
            box-shadow: 0 5px 20px rgba(0,0,0,.07);
            transition: .3s;
        }

        .service-card:hover {
            transform: translateY(-7px);
            box-shadow: 0 12px 30px rgba(0,0,0,.12);
        }

        .service-icon {
            width: 65px;
            height: 65px;
            margin: auto auto 18px;
            border-radius: 50%;
            background: #e8f3ee;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
        }

        .service-card h3 {
            color: #063b2b;
            margin-bottom: 8px;
        }

        .service-card p {
            color: #6b7280;
            font-size: 14px;
        }

        /* ================= ACCOUNTS ================= */

        .accounts {
            background: #ffffff;
        }

        .account-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .account-card {
            border: 1px solid #e5e7eb;
            border-radius: 12px;
            padding: 30px;
            background: white;
        }

        .account-card h3 {
            color: #063b2b;
            font-size: 22px;
            margin-bottom: 12px;
        }

        .account-card .rate {
            font-size: 30px;
            color: #b48526;
            font-weight: bold;
            margin: 15px 0;
        }

        .account-card ul {
            list-style: none;
            margin: 15px 0;
        }

        .account-card li {
            margin: 8px 0;
        }

        .account-card li::before {
            content: "✓";
            color: #087a56;
            font-weight: bold;
            margin-right: 8px;
        }

        .account-btn {
            display: block;
            text-align: center;
            background: #063b2b;
            color: white;
            padding: 11px;
            text-decoration: none;
            border-radius: 6px;
            margin-top: 20px;
        }

        /* ================= DIGITAL BANKING ================= */

        .digital {
            background: #063b2b;
            color: white;
        }

        .digital-container {
            max-width: 1200px;
            margin: auto;
            padding: 70px 20px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }

        .digital h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .digital p {
            color: #d9e7df;
            margin-bottom: 25px;
        }

        .digital-features {
            list-style: none;
        }

        .digital-features li {
            margin: 14px 0;
        }

        .digital-features li::before {
            content: "✓";
            background: #d6a84f;
            color: #063b2b;
            border-radius: 50%;
            padding: 2px 7px;
            margin-right: 10px;
            font-weight: bold;
        }

        .phone {
            width: 270px;
            height: 500px;
            background: #111827;
            border: 8px solid #374151;
            border-radius: 35px;
            margin: auto;
            padding: 25px 15px;
            box-shadow: 0 20px 50px rgba(0,0,0,.3);
        }

        .phone-screen {
            background: #f5f7fb;
            height: 100%;
            border-radius: 22px;
            padding: 20px;
            color: #063b2b;
        }

        .phone-header {
            background: #063b2b;
            color: white;
            padding: 15px;
            border-radius: 12px;
            margin-bottom: 15px;
        }

        .balance {
            font-size: 22px;
            font-weight: bold;
        }

        .phone-menu {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
            margin-top: 20px;
        }

        .phone-menu div {
            background: white;
            padding: 15px 5px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,.08);
        }

        /* ================= EXCHANGE ================= */

        .exchange {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }

        .exchange-box {
            background: white;
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 5px 20px rgba(0,0,0,.06);
        }

        .exchange-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        .exchange-table th,
        .exchange-table td {
            padding: 13px;
            text-align: center;
            border-bottom: 1px solid #eee;
        }

        .exchange-table th {
            background: #063b2b;
            color: white;
        }

        /* ================= NEWS ================= */

        .news {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .news-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(0,0,0,.07);
        }

        .news-image {
            height: 160px;
            background: linear-gradient(135deg,#063b2b,#15916b);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 50px;
        }

        .news-content {
            padding: 22px;
        }

        .news-content h3 {
            color: #063b2b;
            margin-bottom: 8px;
        }

        .news-content p {
            color: #6b7280;
            font-size: 14px;
        }

        /* ================= CONTACT ================= */

        .contact {
            background: white;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
        }

        .contact-info div {
            margin: 20px 0;
        }

        .contact-info strong {
            display: block;
            color: #063b2b;
            font-size: 17px;
        }

        .contact-form {
            background: #f5f7fb;
            padding: 30px;
            border-radius: 12px;
        }

        .form-group {
            margin-bottom: 18px;
        }

        .form-group label {
            display: block;
            margin-bottom: 7px;
            font-weight: bold;
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #d1d5db;
            border-radius: 7px;
            outline: none;
        }

        .form-group textarea {
            min-height: 120px;
            resize: vertical;
        }

        .submit-btn {
            border: none;
            background: #063b2b;
            color: white;
            padding: 13px 25px;
            border-radius: 7px;
            cursor: pointer;
            font-weight: bold;
        }

        /* ================= FOOTER ================= */

        footer {
            background: #04291e;
            color: white;
            padding-top: 55px;
        }

        .footer-container {
            max-width: 1200px;
            margin: auto;
            padding: 0 20px 40px;
            display: grid;
            grid-template-columns: 2fr 1fr 1fr 1fr;
            gap: 35px;
        }

        footer h3 {
            margin-bottom: 18px;
            color: #d6a84f;
        }

        footer p,
        footer li {
            color: #cbd5d1;
            font-size: 14px;
        }

        footer ul {
            list-style: none;
        }

        footer li {
            margin: 9px 0;
        }

        footer a {
            color: #cbd5d1;
            text-decoration: none;
        }

        footer a:hover {
            color: #d6a84f;
        }

        .copyright {
            border-top: 1px solid #315247;
            text-align: center;
            padding: 20px;
            color: #9fb2aa;
            font-size: 13px;
        }

        /* ================= LOGIN MODAL ================= */

        .modal {
            display: none;
            position: fixed;
            inset: 0;
            background: rgba(0,0,0,.65);
            z-index: 2000;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .modal-content {
            background: white;
            width: 100%;
            max-width: 430px;
            padding: 35px;
            border-radius: 15px;
            position: relative;
        }

        .modal-content h2 {
            color: #063b2b;
            margin-bottom: 20px;
            text-align: center;
        }

        .close {
            position: absolute;
            right: 20px;
            top: 12px;
            font-size: 28px;
            cursor: pointer;
        }

        .login-submit {
            width: 100%;
            padding: 13px;
            border: none;
            border-radius: 7px;
            background: #063b2b;
            color: white;
            font-weight: bold;
            cursor: pointer;
        }

        /* ================= RESPONSIVE ================= */

        @media(max-width: 900px) {

            nav ul {
                display: none;
            }

            .hero-container,
            .digital-container,
            .contact-grid,
            .exchange {
                grid-template-columns: 1fr;
            }

            .services {
                grid-template-columns: repeat(2, 1fr);
            }

            .account-grid,
            .news {
                grid-template-columns: 1fr;
            }

            .footer-container {
                grid-template-columns: 1fr 1fr;
            }

            .hero h2 {
                font-size: 38px;
            }
        }

        @media(max-width: 600px) {

            .navbar {
                padding: 12px 15px;
            }

            .logo h1 {
                font-size: 16px;
            }

            .logo-icon {
                width: 40px;
                height: 40px;
            }

            .login-btn {
                padding: 8px 12px;
                font-size: 13px;
            }

            .services {
                grid-template-columns: 1fr;
            }

            .footer-container {
                grid-template-columns: 1fr;
            }

            .hero {
                min-height: auto;
            }

            .hero h2 {
                font-size: 32px;
            }

            .hero p {
                font-size: 15px;
            }

            .bank-card {
                min-height: 230px;
            }

            .section {
                padding: 55px 15px;
            }
        }
    </style>
</head>

<body>

<!-- ================= HEADER ================= -->

<header>
    <div class="navbar">

        <div class="logo">
            <div class="logo-icon">L</div>

            <div>
                <h1>ធនាគារលោកឈា</h1>
                <small>Lok Chhea Bank</small>
            </div>
        </div>

        <nav>
            <ul>
                <li><a href="#home">ទំព័រដើម</a></li>
                <li><a href="#services">សេវាកម្ម</a></li>
                <li><a href="#accounts">គណនី</a></li>
                <li><a href="#digital">Digital Banking</a></li>
                <li><a href="#news">ព័ត៌មាន</a></li>
                <li><a href="#contact">ទំនាក់ទំនង</a></li>
            </ul>
        </nav>

        <a href="#" class="login-btn" onclick="openLogin()">
            🔐 ចូលប្រើប្រាស់
        </a>

    </div>
</header>


<!-- ================= HERO ================= -->

<section class="hero" id="home">

    <div class="hero-container">

        <div>

            <h2>
                ដៃគូហិរញ្ញវត្ថុ
                <span>សម្រាប់អនាគតរបស់អ្នក</span>
            </h2>

            <p>
                ស្វាគមន៍មកកាន់ ធនាគារលោកឈា
                ផ្តល់ជូនសេវាធនាគារទំនើប
                មានសុវត្ថិភាព ងាយស្រួល និងជឿទុកចិត្តបាន
                សម្រាប់បុគ្គល និងអាជីវកម្ម។
            </p>

            <div class="hero-buttons">

                <a href="#accounts" class="btn-primary">
                    បើកគណនី
                </a>

                <a href="#services" class="btn-secondary">
                    ស្វែងយល់បន្ថែម
                </a>

            </div>

        </div>


        <div class="bank-card">

            <h3>LOK CHHEA BANK</h3>

            <div class="card-number">
                5321  ****  ****  8899
            </div>

            <div class="card-bottom">
                <span>LOK CHHEA</span>
                <strong>VISA</strong>
            </div>

        </div>

    </div>

</section>


<!-- ================= SERVICES ================= -->

<section class="section" id="services">

    <div class="section-title">

        <h2>សេវាកម្មរបស់យើង</h2>

        <p>
            ដំណោះស្រាយហិរញ្ញវត្ថុសម្រាប់តម្រូវការរបស់អ្នក
        </p>

    </div>


    <div class="services">

        <div class="service-card">
            <div class="service-icon">💰</div>
            <h3>គណនីសន្សំ</h3>
            <p>
                សន្សំប្រាក់ប្រកបដោយសុវត្ថិភាព
                និងទទួលបានអត្ថប្រយោជន៍ពីការប្រាក់។
            </p>
        </div>


        <div class="service-card">
            <div class="service-icon">💳</div>
            <h3>កាតធនាគារ</h3>
            <p>
                ប្រើប្រាស់ Debit Card និង Credit Card
                សម្រាប់ការទូទាត់ប្រចាំថ្ងៃ។
            </p>
        </div>


        <div class="service-card">
            <div class="service-icon">🏠</div>
            <h3>ឥណទាន</h3>
            <p>
                ដំណោះស្រាយឥណទានសម្រាប់ផ្ទះ
                អាជីវកម្ម និងតម្រូវការផ្ទាល់ខ្លួន។
            </p>
        </div>


        <div class="service-card">
            <div class="service-icon">📱</div>
            <h3>Mobile Banking</h3>
            <p>
                គ្រប់គ្រងគណនី និងធ្វើប្រតិបត្តិការតាមទូរស័ព្ទ។
            </p>
        </div>

    </div>

</section>


<!-- ================= ACCOUNTS ================= -->

<section class="accounts" id="accounts">

    <div class="section">

        <div class="section-title">

            <h2>ប្រភេទគណនី</h2>

            <p>
                ជ្រើសរើសគណនីដែលសមស្របសម្រាប់អ្នក
            </p>

        </div>


        <div class="account-grid">

            <div class="account-card">

                <h3>គណនីសន្សំ</h3>

                <p>
                    សម្រាប់ការសន្សំប្រាក់ប្រចាំថ្ងៃ។
                </p>

                <div class="rate">
                    3.50%
                </div>

                <small>អត្រាការប្រាក់ប្រចាំឆ្នាំ*</small>

                <ul>
                    <li>បើកគណនីងាយស្រួល</li>
                    <li>គ្រប់គ្រងតាម Mobile Banking</li>
                    <li>មានសុវត្ថិភាព</li>
                </ul>

                <a href="#" class="account-btn">
                    ស្វែងយល់បន្ថែម
                </a>

            </div>


            <div class="account-card">

                <h3>គណនីចរន្ត</h3>

                <p>
                    សម្រាប់បុគ្គល និងអាជីវកម្ម។
                </p>

                <div class="rate">
                    2.00%
                </div>

                <small>អត្រាការប្រាក់ប្រចាំឆ្នាំ*</small>

                <ul>
                    <li>ប្រតិបត្តិការប្រចាំថ្ងៃ</li>
                    <li>ការទូទាត់ងាយស្រួល</li>
                    <li>សាកសមសម្រាប់អាជីវកម្ម</li>
                </ul>

                <a href="#" class="account-btn">
                    ស្វែងយល់បន្ថែម
                </a>

            </div>


            <div class="account-card">

                <h3>គណនីមានកាលកំណត់</h3>

                <p>
                    សម្រាប់អ្នកចង់សន្សំរយៈពេលវែង។
                </p>

                <div class="rate">
                    5.25%
                </div>

                <small>អត្រាការប្រាក់ប្រចាំឆ្នាំ*</small>

                <ul>
                    <li>អត្រាការប្រាក់ប្រកួតប្រជែង</li>
                    <li>រយៈពេលច្រើនជម្រើស</li>
                    <li>សុវត្ថិភាពខ្ពស់</li>
                </ul>

                <a href="#" class="account-btn">
                    ស្វែងយល់បន្ថែម
                </a>

            </div>

        </div>

    </div>

</section>


<!-- ================= DIGITAL BANKING ================= -->

<section class="digital" id="digital">

    <div class="digital-container">

        <div>

            <h2>
                ធនាគារឌីជីថល
            </h2>

            <p>
                ធ្វើប្រតិបត្តិការធនាគារគ្រប់ពេល
                គ្រប់ទីកន្លែង តាមរយៈ Mobile Banking
                របស់ធនាគារលោកឈា។
            </p>

            <ul class="digital-features">

                <li>ពិនិត្យសមតុល្យគណនី</li>
                <li>ផ្ទេរប្រាក់</li>
                <li>បង់វិក្កយបត្រ</li>
                <li>បង់ប្រាក់តាម QR</li>
                <li>ពិនិត្យប្រវត្តិប្រតិបត្តិការ</li>

            </ul>

        </div>


        <div class="phone">

            <div class="phone-screen">

                <div class="phone-header">

                    <small>សមតុល្យគណនី</small>

                    <div class="balance">
                        $12,580.00
                    </div>

                </div>


                <div class="phone-menu">

                    <div>💸<br>ផ្ទេរប្រាក់</div>

                    <div>📷<br>Scan QR</div>

                    <div>💡<br>បង់វិក្កយបត្រ</div>

                    <div>📊<br>ប្រវត្តិ</div>

                </div>

            </div>

        </div>

    </div>

</section>


<!-- ================= EXCHANGE ================= -->

<section class="section">

    <div class="section-title">

        <h2>អត្រាប្តូរប្រាក់</h2>

        <p>
            អត្រាគំរូសម្រាប់ Website Template
        </p>

    </div>


    <div class="exchange">

        <div class="exchange-box">

            <h3>អត្រាប្តូរប្រាក់</h3>

            <table class="exchange-table">

                <tr>
                    <th>រូបិយប័ណ្ណ</th>
                    <th>ទិញ</th>
                    <th>លក់</th>
                </tr>

                <tr>
                    <td>USD</td>
                    <td>4,050</td>
                    <td>4,080</td>
                </tr>

                <tr>
                    <td>THB</td>
                    <td>118</td>
                    <td>121</td>
                </tr>

                <tr>
                    <td>EUR</td>
                    <td>4,650</td>
                    <td>4,750</td>
                </tr>

            </table>

        </div>


        <div class="exchange-box">

            <h3>ព័ត៌មានសុវត្ថិភាព</h3>

            <p>
                🔐 កុំចែករំលែក Password ឬ OTP
                ជាមួយអ្នកដទៃ។
            </p>

            <br>

            <p>
                🛡️ ធនាគារនឹងមិនស្នើសុំ Password
                តាមរយៈ Email ឬ Phone ទេ។
            </p>

            <br>

            <p>
                📞 ប្រសិនបើមានបញ្ហា
                សូមទាក់ទង Customer Service។
            </p>

        </div>

    </div>

</section>


<!-- ================= NEWS ================= -->

<section class="section" id="news">

    <div class="section-title">

        <h2>ព័ត៌មាន និងប្រូម៉ូសិន</h2>

        <p>
            ព័ត៌មានថ្មីៗពីធនាគារលោកឈា
        </p>

    </div>


    <div class="news">

        <div class="news-card">

            <div class="news-image">
                🎁
            </div>

            <div class="news-content">

                <h3>
                    ប្រូម៉ូសិនបើកគណនីថ្មី
                </h3>

                <p>
                    បើកគណនីថ្មី និងទទួលបានអត្ថប្រយោជន៍ពិសេស
                    សម្រាប់អតិថិជនថ្មី។
                </p>

            </div>

        </div>


        <div class="news-card">

            <div class="news-image">
                📱
            </div>

            <div class="news-content">

                <h3>
                    Digital Banking ថ្មី
                </h3>

                <p>
                    ប្រើប្រាស់សេវាធនាគារឌីជីថល
                    ដើម្បីគ្រប់គ្រងហិរញ្ញវត្ថុរបស់អ្នក។
                </p>

            </div>

        </div>


        <div class="news-card">

            <div class="news-image">
                💳
            </div>

            <div class="news-content">

                <h3>
                    កាតថ្មី
                </h3>

                <p>
                    ស្វែងយល់ពីកាតធនាគារថ្មី
                    និងអត្ថប្រយោជន៍សម្រាប់ការទូទាត់។
                </p>

            </div>

        </div>

    </div>

</section>


<!-- ================= CONTACT ================= -->

<section class="contact" id="contact">

    <div class="section">

        <div class="section-title">

            <h2>ទំនាក់ទំនង</h2>

            <p>
                យើងរីករាយក្នុងការជួយអ្នក
            </p>

        </div>


        <div class="contact-grid">

            <div class="contact-info">

                <div>
                    <strong>📍 អាសយដ្ឋាន</strong>
                    <p>
                        Phnom Penh, Cambodia
                    </p>
                </div>

                <div>
                    <strong>📞 Customer Service</strong>
                    <p>
                        1800 888 999
                    </p>
                </div>

                <div>
                    <strong>✉️ Email</strong>
                    <p>
                        info@lokchheabank.com
                    </p>
                </div>

                <div>
                    <strong>🕘 ម៉ោងធ្វើការ</strong>
                    <p>
                        ច័ន្ទ - សុក្រ : 8:00 AM - 5:00 PM
                    </p>
                </div>

            </div>


            <form class="contact-form"
                  onsubmit="sendMessage(event)">

                <div class="form-group">

                    <label>ឈ្មោះ</label>

                    <input
                        type="text"
                        placeholder="បញ្ចូលឈ្មោះ"
                        required
                    >

                </div>


                <div class="form-group">

                    <label>Email</label>

                    <input
                        type="email"
                        placeholder="example@email.com"
                        required
                    >

                </div>


                <div class="form-group">

                    <label>សារ</label>

                    <textarea
                        placeholder="សរសេរសាររបស់អ្នក..."
                        required
                    ></textarea>

                </div>


                <button class="submit-btn">
                    ផ្ញើសារ
                </button>

            </form>

        </div>

    </div>

</section>


<!-- ================= FOOTER ================= -->

<footer>

    <div class="footer-container">

        <div>

            <h3>ធនាគារលោកឈា</h3>

            <p>
                ដៃគូហិរញ្ញវត្ថុដែលអ្នកអាចទុកចិត្តបាន។
                យើងផ្តល់ជូនសេវាធនាគារទំនើប
                សម្រាប់បុគ្គល និងអាជីវកម្ម។
            </p>

        </div>


        <div>

            <h3>សេវាកម្ម</h3>

            <ul>
                <li><a href="#">គណនីសន្សំ</a></li>
                <li><a href="#">កាតធនាគារ</a></li>
                <li><a href="#">ឥណទាន</a></li>
                <li><a href="#">Mobile Banking</a></li>
            </ul>

        </div>


        <div>

            <h3>ជំនួយ</h3>

            <ul>
                <li><a href="#">សំណួរដែលសួរញឹកញាប់</a></li>
                <li><a href="#">សុវត្ថិភាព</a></li>
                <li><a href="#">លក្ខខណ្ឌ</a></li>
                <li><a href="#">គោលការណ៍ឯកជនភាព</a></li>
            </ul>

        </div>


        <div>

            <h3>តាមដានយើង</h3>

            <ul>
                <li><a href="#">Facebook</a></li>
                <li><a href="#">Telegram</a></li>
                <li><a href="#">YouTube</a></li>
                <li><a href="#">LinkedIn</a></li>
            </ul>

        </div>

    </div>


    <div class="copyright">

        © 2026 ធនាគារលោកឈា | Lok Chhea Bank.
        All Rights Reserved.

    </div>

</footer>


<!-- ================= LOGIN MODAL ================= -->

<div class="modal" id="loginModal">

    <div class="modal-content">

        <span class="close" onclick="closeLogin()">
            &times;
        </span>

        <h2>
            🔐 Internet Banking
        </h2>


        <form onsubmit="loginDemo(event)">

            <div class="form-group">

                <label>User ID</label>

                <input
                    type="text"
                    placeholder="បញ្ចូល User ID"
                    required
                >

            </div>


            <div class="form-group">

                <label>Password</label>

                <input
                    type="password"
                    placeholder="បញ្ចូល Password"
                    required
                >

            </div>


            <button class="login-submit">
                ចូលប្រើប្រាស់
            </button>

        </form>

        <p style="text-align:center;margin-top:15px;font-size:12px;color:#777;">
            Demo Website — មិនមែនប្រព័ន្ធធនាគារពិតទេ
        </p>

    </div>

</div>


<!-- ================= JAVASCRIPT ================= -->

<script>

    function openLogin() {
        document.getElementById("loginModal").style.display = "flex";
    }

    function closeLogin() {
        document.getElementById("loginModal").style.display = "none";
    }

    window.onclick = function(event) {

        const modal = document.getElementById("loginModal");

        if (event.target === modal) {
            modal.style.display = "none";
        }

    };


    function loginDemo(event) {

        event.preventDefault();

        alert(
            "នេះគឺជា Demo Website។\n\n" +
            "ប្រព័ន្ធ Login ពិតប្រាកដមិនទាន់បានភ្ជាប់ជាមួយ Database ទេ។"
        );

    }


    function sendMessage(event) {

        event.preventDefault();

        alert(
            "អរគុណសម្រាប់ការទាក់ទងមកកាន់\n" +
            "ធនាគារលោកឈា!"
        );

    }

</script>

</body>
</html>
