
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>لفة | خذ لك لفة</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.rtl.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #0d0d0d;
      color: white;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      scroll-behavior: smooth;
    }
    nav {
      background-color: #1a1a1a;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background: linear-gradient(to bottom, #0d0d0d, #1a1a1a);
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      color: #00fff7;
    }
    .hero p {
      font-size: 1.25rem;
      color: #ccc;
    }
    .cta-btn {
      margin-top: 20px;
      padding: 12px 30px;
      background-color: #00fff7;
      color: #000;
      font-weight: bold;
      border: none;
      border-radius: 50px;
    }
    .section {
      padding: 80px 20px;
    }
    .service-icon {
      font-size: 2rem;
      color: #00fff7;
      margin-bottom: 10px;
    }
    .service-box {
      background-color: #1a1a1a;
      padding: 30px;
      border-radius: 15px;
      transition: transform 0.3s ease;
    }
    .service-box:hover {
      transform: translateY(-10px);
    }
    .portfolio-item img {
      width: 100%;
      border-radius: 12px;
      transition: transform 0.3s ease;
    }
    .portfolio-item img:hover {
      transform: scale(1.05);
    }
    .features-box {
      background-color: #1a1a1a;
      padding: 30px;
      border-radius: 15px;
    }
    .contact-form input,
    .contact-form textarea {
      background-color: #0d0d0d;
      color: white;
      border: 1px solid #555;
    }
    .contact-form button {
      background-color: #00fff7;
      color: black;
      border: none;
      padding: 10px 25px;
      border-radius: 30px;
      font-weight: bold;
    }
    footer {
      background-color: #1a1a1a;
      padding: 40px 20px;
      text-align: center;
      color: #ccc;
      font-size: 0.9rem;
    }
    footer a {
      color: #00fff7;
      text-decoration: none;
      margin: 0 10px;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg sticky-top">
    <div class="container">
      <a class="navbar-brand text-white fw-bold" href="#">لفة</a>
      <div>
        <a href="#services">الخدمات</a>
        <a href="#portfolio">الأعمال</a>
        <a href="#about">من نحن</a>
        <a href="#contact">تواصل</a>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <h1>مش عارف تبدأ؟</h1>
    <p>🌀 خذ لك لفة.</p>
    <a href="#services" class="cta-btn">ابدأ الآن</a>
  </section>

  <!-- Services Section -->
  <section id="services" class="section container">
    <div class="row text-center">
      <h2 class="mb-5">خدماتنا</h2>
      <div class="col-md-3">
        <div class="service-box">
          <div class="service-icon">🎙️</div>
          <h5>التعليق الصوتي</h5>
          <p>نصمم الصوت المناسب لهوية مشروعك، بإحساس احترافي.</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="service-box">
          <div class="service-icon">🎬</div>
          <h5>المونتاج والإخراج</h5>
          <p>نحرك فكرتك بصريًا ونعطيها الحياة بإبداع.</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="service-box">
          <div class="service-icon">📝</div>
          <h5>كتابة المحتوى</h5>
          <p>نكتبها بأسلوب يلفت الانتباه، ويقنع جمهورك.</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="service-box">
          <div class="service-icon">📊</div>
          <h5>التسويق الرقمي</h5>
          <p>نستهدف عملاءك بالذكاء والتحليل… ونلفهم نحوك.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about" class="section container text-center">
    <h2 class="mb-4">من نحن؟</h2>
    <p class="lead">"لفة" شركة تسويق وإنتاج ذكية، تربط كل حاجة حوالين فكرتك: من التصميم للمحتوى للصوت للتسويق. نخدمك بخطوات متسلسلة، كل خطوة تخدم اللي بعدها، لحد ما مشروعك يلف… ويلفت.</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="section container">
    <h2 class="text-center mb-5">معرض الأعمال</h2>
    <div class="row g-4">
      <div class="col-md-4 portfolio-item">
        <img src="https://via.placeholder.com/600x400?text=مشروع+1" alt="مشروع 1">
      </div>
      <div class="col-md-4 portfolio-item">
        <img src="https://via.placeholder.com/600x400?text=مشروع+2" alt="مشروع 2">
      </div>
      <div class="col-md-4 portfolio-item">
        <img src="https://via.placeholder.com/600x400?text=مشروع+3" alt="مشروع 3">
      </div>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features" class="section container text-center">
    <h2 class="mb-5">ليش تختار لفة؟</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="features-box">
          <h5>إبداع مو متكرر</h5>
          <p>كل فكرة نصممها بأسلوب مختلف، لا تشبه غيرها.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="features-box">
          <h5>تسلسل ذكي</h5>
          <p>من أول فكرة… لآخر حملة. كل خطوة محسوبة.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="features-box">
          <h5>واقعية وإحساس</h5>
          <p>نحكيها بصوت وصورة… زي ما تحسها، مو بس تشوفها.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials" class="section container text-center">
    <h2 class="mb-5">ماذا قالوا عنا؟</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="p-4 bg-dark rounded">
          <p>"أفضل تجربة تعاملت معها! شغل احترافي وتعاون رائع من فريق لفة."</p>
          <strong>— أحمد الغامدي</strong>
        </div>
      </div>
      <div class="col-md-4">
        <div class="p-4 bg-dark rounded">
          <p>"سوّولي إعلان خرافي لفكرة بسيطة… والله ما توقعت النتيجة تكون كذا!"</p>
          <strong>— سارة المطيري</strong>
        </div>
      </div>
      <div class="col-md-4">
        <div class="p-4 bg-dark rounded">
          <p>"لفة غيرت طريقة عرض مشروعي بالكامل. إبداعهم ما يتكرر."</p>
          <strong>— يوسف الحربي</strong>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section container">
    <h2 class="text-center mb-4">تواصل معنا</h2>
    <p class="text-center mb-4">للتواصل المباشر: <strong>+966 53 889 9006</strong> | <a href="https://wa.me/966538899006" target="_blank" style="color:#00fff7; text-decoration:underline;">راسلنا على واتساب</a></p>
    <form class="contact-form row g-3">
      <div class="col-md-6">
        <input type="text" class="form-control" placeholder="الاسم الكامل" required>
      </div>
      <div class="col-md-6">
        <input type="email" class="form-control" placeholder="البريد الإلكتروني" required>
      </div>
      <div class="col-12">
        <textarea class="form-control" rows="5" placeholder="رسالتك" required></textarea>
      </div>
      <div class="col-12 text-center">
        <button type="submit">أرسل الآن</button>
      </div>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 جميع الحقوق محفوظة لشركة لفة.</p>
    <p>
      <a href="#">إنستغرام</a> |
      <a href="#">تويتر</a> |
      <a href="#">لينكدإن</a>
    </p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
