<DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zaka Emballage | لوازم الحلويات</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
<style>
body { margin:0; font-family: 'Cairo', sans-serif; background-color:#fff8f5; color:#3b2f2f; }
header { background-color:#d97d54; color:white; padding:20px; text-align:center; }
nav a { color:white; margin:0 10px; text-decoration:none; font-weight:bold; }
nav a:hover { color:#ffe3c4; }
.section { padding:40px 20px; }
h2 { text-align:center; color:#d97d54; margin-bottom:30px; }
.grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px; }
.card { background-color:#fff5f0; padding:20px; border-radius:12px; text-align:center; box-shadow:0 4px 6px rgba(0,0,0,0.1); }
.card img { width:200px; border-radius:10px; margin-bottom:15px; }
.btn { display:inline-block; padding:10px 20px; background-color:#f7c28c; color:#3b2f2f; text-decoration:none; border-radius:8px; font-weight:bold; margin-top:10px; }
.btn:hover { background-color:#e6b070; color:white; }
input[type=number] { padding:8px; width:60px; text-align:center; margin-top:5px; }
select { padding:8px; margin-top:5px; width:150px; }
footer { background-color:#d97d54; color:white; text-align:center; padding:20px; margin-top:20px; }
</style>
</head>
<body><header>
  <h1>Zaka Emballage</h1>
  <p>كل ما تحتاجه للحلويات والتغليف</p>
  <nav>
    <a href="#products">المنتجات</a>
    <a href="#about">من نحن</a>
    <a href="#contact">تواصل معنا</a>
  </nav>
</header><section class="section" id="products">
  <h2>منتجاتنا</h2>
  <div class="grid"><!-- قوالب حلويات -->
<div class="card">
  <h3>قوالب حلويات</h3>
  <select id="moldType" onchange="updateMold()">
    <option value="سيليكون">قالب سيليكون</option>
    <option value="فلورين">قالب فلورين</option>
    <option value="كب كيك">قالب كب كيك</option>
  </select>
  <img id="moldImage" src="https://images.pexels.com/photos/3756521/pexels-photo-3756521.jpeg?auto=compress&cs=tinysrgb&w=600" alt="قالب سيليكون">
  <label for="quantity">الكمية:</label>
  <input type="number" id="quantity" value="1" min="1">
  <a id="whatsappBtn" class="btn" href="https://wa.me/213776818807?text=أريد+شراء+قالب+سيليكون+بكمية+1" target="_blank">اطلب الآن عبر واتساب</a>
</div>

<!-- مواد أولية -->
<div class="card">
  <h3>مواد أولية</h3>
  <select id="materialType" onchange="updateMaterial()">
    <option value="شوكولا">شوكولا</option>
    <option value="فانيليا">فانيليا</option>
    <option value="ألوان غذائية">ألوان غذائية</option>
  </select>
  <img id="materialImage" src="https://cdn.pixabay.com/photo/2016/11/18/15/33/chocolate-1835437_640.jpg" alt="شوكولا">
  <label for="materialQuantity">الكمية:</label>
  <input type="number" id="materialQuantity" value="1" min="1">
  <a id="whatsappMaterialBtn" class="btn" href="https://wa.me/213776818807?text=أريد+شراء+شوكولا+بكمية+1" target="_blank">اطلب الآن عبر واتساب</a>
</div>

<!-- تغليف -->
<div class="card">
  <h3>مواد تغليف</h3>
  <select id="packagingType" onchange="updatePackaging()">
    <option value="علب">علب</option>
    <option value="أكياس">أكياس</option>
    <option value="ورق تغليف">ورق تغليف</option>
  </select>
  <img id="packagingImage" src="https://cdn.pixabay.com/photo/2017/07/16/10/43/cupcake-2501070_640.jpg" alt="علب">
  <label for="packQuantity">الكمية:</label>
  <input type="number" id="packQuantity" value="1" min="1">
  <a id="whatsappPackagingBtn" class="btn" href="https://wa.me/213776818807?text=أريد+شراء+علب+بكمية+1" target="_blank">اطلب الآن عبر واتساب</a>
</div>

  </div>
</section><section class="section" id="about">
  <h2>من نحن</h2>
  <p style="text-align:center; max-width:600px; margin:0 auto; font-size:1.1em; line-height:1.6;">
    Zaka Emballage متجر متخصص في تقديم أفضل لوازم الحلويات والتغليف داخل الجزائر. نسعى لتوفير منتجات عالية الجودة وتجربة شراء سهلة وممتعة لكل زبائننا.
  </p>
</section><section class="section" id="contact">
  <h2>تواصل معنا</h2>
  <p style="text-align:center;">📞 واتساب: 0776818807</p>
</section><footer>
  <p>© 2026 Zaka Emballage - جميع الحقوق محفوظة</p>
</footer><script>
function updateMold() {
  var type = document.getElementById('moldType').value;
  var quantity = document.getElementById('quantity').value;
  var image = document.getElementById('moldImage');
  var btn = document.getElementById('whatsappBtn');
  if(type==="سيليكون") image.src="https://images.pexels.com/photos/3756521/pexels-photo-3756521.jpeg?auto=compress&cs=tinysrgb&w=600";
  else if(type==="فلورين") image.src="https://cdn.pixabay.com/photo/2014/08/10/21/17/baking-molds-pans-copper-old-419245_640.jpg";
  else image.src="https://cdn.pixabay.com/photo/2017/06/02/18/24/cupcake-2361854_640.jpg";
  btn.href="https://wa.me/213776818807?text=أريد+شراء+"+type+"+بكمية+"+quantity;
}
document.getElementById('quantity').addEventListener('input', updateMold);

function updateMaterial() {
  var type = document.getElementById('materialType').value;
  var quantity = document.getElementById('materialQuantity').value;
  var image = document.getElementById('materialImage');
  var btn = document.getElementById('whatsappMaterialBtn');
  if(type==="شوكولا") image.src="https://cdn.pixabay.com/photo/2016/11/18/15/33/chocolate-1835437_640.jpg";
  else if(type==="فانيليا") image.src="https://cdn.pixabay.com/photo/2017/08/30/13/10/vanilla-2697682_640.jpg";
  else image.src="https://cdn.pixabay.com/photo/2017/02/01/10/17/food-2030334_640.jpg";
  btn.href="https://wa.me/213776818807?text=أريد+شراء+"+type+"+بكمية+"+quantity;
}
document.getElementById('materialQuantity').addEventListener('input', updateMaterial);

function updatePackaging() {
  var type = document.getElementById('packagingType').value;
  var quantity = document.getElementById('packQuantity').value;
  var image = document.getElementById('packagingImage');
  var btn = document.getElementById('whatsappPackagingBtn');
  if(type==="علب") image.src="https://cdn.pixabay.com/photo/2017/07/16/10/43/cupcake-2501070_640.jpg";
  else if(type==="أكياس") image.src="https://cdn.pixabay.com/photo/2016/02/11/18/26/bag-1197256_640.jpg";
  else image.src="https://cdn.pixabay.com/photo/2016/10/17/19/28/wrapping-paper-1749936_640.jpg";
  btn.href="https://wa.me/213776818807?text=أريد+شراء+"+type+"+بكمية+"+quantity;
}
document.getElementById('packQuantity').addEventListener('input', updatePackaging);
</script></body>
</html>
