<DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zaka Emballage | لوازم الحلويات</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Cairo', sans-serif;
      background-color: #fff8f5;
      color: #3b2f2f;
    }
    header {
      background-color: #d97d54;
      color: white;
      padding: 25px 20px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: #ffe3c4;
    }
    .hero {
      padding: 60px 20px;
      text-align: center;
      background: url('https://i.imgur.com/pG6UdrT.jpg') center/cover no-repeat;
      color: #fff;
    }
    .hero h1 {
      font-size: 2.8em;
      margin-bottom: 15px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }
    .hero p {
      font-size: 1.2em;
      margin-bottom: 25px;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
    }
    .btn {
      display: inline-block;
      padding: 15px 30px;
      background-color: #f7c28c;
      color: #3b2f2f;
      text-decoration: none;
      font-weight: bold;
      border-radius: 8px;
      transition: 0.3s;
    }
    .btn:hover {
      background-color: #e6b070;
      color: white;
    }
    .section {
      padding: 60px 20px;
    }
    h2 {
      text-align: center;
      font-size: 2em;
      margin-bottom: 40px;
      color: #d97d54;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }
    .card {
      background-color: #fff5f0;
      border-radius: 12px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 12px rgba(0,0,0,0.15);
    }
    .card img {
      max-width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }
    footer {
      background-color: #d97d54;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    form {
      max-width: 500px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, textarea {
      padding: 12px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 1em;
      width: 100%;
    }
    input[type=submit] {
      background-color: #f7c28c;
      color: #3b2f2f;
      border: none;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }
    input[type=submit]:hover {
      background-color: #e6b070;
      color: white;
    }
    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2em;
      }
      .hero p {
        font-size: 1em;
      }
    }
  </style>
</head>
<body><header>
  <h1>Zaka Emballage</h1>
  <p>كل ما تحتاجه للحلويات والتغليف</p>
  <nav>
    <a href="#home">الرئيسية</a>
    <a href="#products">المنتجات</a>
    <a href="#offers">العروض</a>
    <a href="#about">من نحن</a>
    <a href="#contact">تواصل معنا</a>
  </nav>
</header><section class="hero" id="home">
  <h1>مرحبا بكم في Zaka Emballage</h1>
  <p>نوفّر لكم أفضل لوازم الحلويات والتغليف بجودة عالية</p>
  <a class="btn" href="https://wa.me/213776818807">اطلب عبر واتساب</a>
</section><section class="section" id="products">
  <h2>منتجاتنا</h2>
  <div class="grid">
    <div class="card">
      <img src="https://photos.app.goo.gl/AZkRdWWrjcPHVd459.jpg" alt="قوالب حلويات">
      <h3>قوالب حلويات</h3>
      <p>قوالب متنوعة بجودة عالية</p>
      <a class="btn" href="https://wa.me/213776818807">اطلب الآن</a>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/8Q7V5WQ.jpg" alt="مواد أولية">
      <h3>مواد أولية</h3>
      <p>شوكولا، فانيليا، ألوان غذائية</p>
      <a class="btn" href="https://wa.me/213776818807">اطلب الآن</a>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/3F8KJQG.jpg" alt="تغليف">
      <h3>مواد تغليف</h3>
      <p>علب، أكياس، ورق تغليف</p>
      <a class="btn" href="https://wa.me/213776818807">اطلب الآن</a>
    </div>
  </div>
</section><section class="section" id="offers">
  <h2>العروض الخاصة</h2>
  <div class="grid">
    <div class="card">
      <h3>خصم 10% على القوالب</h3>
      <p>استفد من عرضنا المحدود على جميع القوالب.</p>
      <a class="btn" href="https://wa.me/213776818807">اطلب الآن</a>
    </div>
    <div class="card">
      <h3>شحن مجاني فوق 5000 دج</h3>
      <p>اشترِ أي منتج بمبلغ 5000 دج أو أكثر واحصل على الشحن مجاناً.</p>
      <a class="btn" href="https://wa.me/213776818807">اطلب الآن</a>
    </div>
  </div>
</section><section class="section" id="about">
  <h2>من نحن</h2>
  <p style="text-align:center; max-width:600px; margin:0 auto; font-size:1.1em; line-height:1.6;">Zaka Emballage متجر متخصص في تقديم أفضل لوازم الحلويات والتغليف داخل الجزائر. نسعى لتوفير منتجات عالية الجودة وتجربة شراء سهلة وممتعة لكل زبائننا.</p>
</section><section class="section" id="contact">
  <h2>تواصل معنا</h2>
  <form action="https://wa.me/213776818807" method="get">
    <input type="text" name="name" placeholder="الاسم" required>
    <input type="text" name="phone" placeholder="رقم الهاتف" required>
    <input type="text" name="state" placeholder="الولاية" required>
    <input type="text" name="product" placeholder="المنتج" required>
    <input type="number" name="quantity" placeholder="الكمية" required>
    <input type="submit" value="إرسال الطلب عبر واتساب">
  </form>
  <p style="margin-top:20px;">📞 واتساب: 0776818807</p>
</section><footer>
  <p>© 2026 Zaka Emballage - جميع الحقوق محفوظة</p>
</footer></body>
</html>
