# zamin shenasiii
زمین شناسی پروژه فصل ۴
<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت شخصی علیرضا بابائی</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>سایت شخصی علیرضا بابائی</h1>
        <nav>
            <ul>
                <li><a href="#about">درباره من</a></li>
                <li><a href="#project">پروژه فصل ۴</a></li>
                <li><a href="#data-collection">جمع‌آوری اطلاعات</a></li>
                <li><a href="#gallery">گالری</a></li>
                <li><a href="#contact">تماس با من</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>درباره من</h2>
        <p>نام: علیرضا بابائی</p>
        <p>پایه: هشتم کلاس ۱۱</p>
        <p>رشته: ریاضی</p>
        <p>مدرسه: برکت</p>
    </section>

    <section id="project">
        <h2>پروژه فصل ۴ زمین‌شناسی یازدهم</h2>
        <p>در این بخش، پروژه فصل ۴ زمین‌شناسی سال یازدهم ارائه شده است. این پروژه شامل تحلیل پویایی زمین و بررسی فرآیندهای زمین‌شناسی می‌باشد.</p>
        <p>متن کامل پروژه از روی کتاب درسی سال ۱۴۰۴ استخراج شده است.</p>
    </section>

    <section id="data-collection">
        <h2>جمع‌آوری اطلاعات فصل ۴ زمین‌شناسی یازدهم</h2>
        <p>در این بخش، اطلاعات جمع‌آوری شده از فصل ۴ زمین‌شناسی سال یازدهم ارائه می‌شود. این اطلاعات شامل داده‌های مربوط به فرآیندهای زمین‌شناسی و تحلیل‌های مرتبط می‌باشد.</p>
    </section>

    <section id="gallery">
        <h2>گالری تصاویر</h2>
        <div class="gallery">
            <img src="images/sample1.jpg" alt="نمونه ۱">
            <img src="images/sample2.jpg" alt="نمونه ۲">
            <img src="images/sample3.jpg" alt="نمونه ۳">
        </div>
    </section>

    <section id="contact">
        <h2>تماس با من</h2>
        <p>شماره تماس: 09025358273</p>
    </section>

    <footer>
        <p>© 2025 علیرضا بابائی</p>
    </footer>
</body>
</html>
body {
    font-family: 'Tahoma', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #4CAF50;
}

.gallery {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.gallery img {
    width: 30%;
    margin: 10px;
    border-radius: 8px;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
