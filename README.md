# Amar-dokan<!DOCTYPE html><html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>আমার দোকান</title>
  <style>
    body { font-family: 'Arial', sans-serif; margin: 0; padding: 0; background: #f2f2f2; }
    header { background: green; color: white; padding: 20px; text-align: center; }
    nav { background: #333; display: flex; justify-content: center; padding: 10px; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; padding: 20px; }
    .product { background: white; padding: 15px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
    .product img { width: 100%; height: 150px; object-fit: cover; }
    .product h3 { margin: 10px 0; }
    .product button { background: green; color: white; border: none; padding: 10px 15px; border-radius: 5px; cursor: pointer; }
    footer { text-align: center; padding: 20px; background: #222; color: white; margin-top: 40px; }
  </style>
</head>
<body>
  <header>
    <h1>স্বাগতম আমার দোকানে</h1>
    <p>সবজি থেকে শুরু করে সবকিছু পাওয়া যায় এখানে</p>
  </header>
  <nav>
    <a href="#">হোম</a>
    <a href="#">পণ্যসমূহ</a>
    <a href="#">কার্ট</a>
    <a href="#">যোগাযোগ</a>
  </nav>  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/200x150.png?text=পটল" alt="পটল">
      <h3>পটল</h3>
      <p>দাম: ৪০ টাকা/কেজি</p>
      <button>কার্টে যোগ করুন</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x150.png?text=টমেটো" alt="টমেটো">
      <h3>টমেটো</h3>
      <p>দাম: ৩০ টাকা/কেজি</p>
      <button>কার্টে যোগ করুন</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x150.png?text=আপেল" alt="আপেল">
      <h3>আপেল</h3>
      <p>দাম: ১২০ টাকা/কেজি</p>
      <button>কার্টে যোগ করুন</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x150.png?text=শ্যাম্পু" alt="শ্যাম্পু">
      <h3>শ্যাম্পু</h3>
      <p>দাম: ৮০ টাকা</p>
      <button>কার্টে যোগ করুন</button>
    </div>
  </section>  <footer>
    <p>&copy; ২০২৫ আমার দোকান | সব অধিকার সংরক্ষিত</p>
  </footer>
</body>
</html>
