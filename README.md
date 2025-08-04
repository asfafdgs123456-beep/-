<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>مكتبة الجواد - قرطاسية مدرسية</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>📚 مكتبة الجواد</h1>
    <nav>
      <ul>
        <li><a href="#">الرئيسية</a></li>
        <li><a href="#">من نحن</a></li>
        <li><a href="#">المنتجات</a></li>
        <li><a href="#">تواصل معنا</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>كل ما تحتاجه لمدرستك في مكان واحد!</h2>
    <p>أدوات مكتبية، قرطاسية، دفاتر، أقلام، حقائب والمزيد...</p>
    <a href="#" class="btn">تصفح المنتجات</a>
  </section>

  <section class="features">
    <div class="box">
      <h3>أسعار مناسبة</h3>
      <p>نضمن لك أفضل سعر في السوق.</p>
    </div>
    <div class="box">
      <h3>منتجات أصلية</h3>
      <p>نوفر لك ماركات مضمونة وجودة عالية.</p>
    </div>
    <div class="box">
      <h3>خدمة توصيل</h3>
      <p>توصيل سريع داخل المدينة.</p>
    </div>
  </section>

  <footer>
    <p>جميع الحقوق محفوظة © مكتبة الجواد 2025</p>
  </footer>
</body>
</html>
body {
  font-family: 'Arial', sans-serif;
  background-color: #f9f9f9;
  margin: 0;
  padding: 0;
  direction: rtl;
}

header {
  background-color: #004080;
  color: white;
  padding: 20px;
  text-align: center;
}

header h1 {
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  margin-top: 10px;
}

nav li {
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  background-color: #dceeff;
  padding: 50px 20px;
  text-align: center;
}

.hero h2 {
  font-size: 28px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 20px;
}

.btn {
  background-color: #004080;
  color: white;
  padding: 12px 20px;
  text-decoration: none;
  border-radius: 5px;
}

.features {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  padding: 30px 10px;
  background-color: #fff;
}

.features .box {
  width: 30%;
  min-width: 250px;
  background-color: #e6f0ff;
  padding: 20px;
  margin: 10px;
  border-radius: 8px;
  text-align: center;
}

footer {
  background-color: #004080;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 30px;
}
