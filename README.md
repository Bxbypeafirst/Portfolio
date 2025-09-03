# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
    }
  </style>
</head>
<body>
  <h1>Hello, GitHub Pages!</h1>
  <p>นี่คือเว็บแรกของฉัน 🚀</p>
  https://Bxbypeafirst.github.io/Bxbypeafirst
  <!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>แฟ้มสะสมผลงาน - ทินภัทร บริรักษ์สาทร</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f6fa;
      color: #333;
      transition: background 0.3s, color 0.3s;
    }
    header {
      text-align: center;
      padding: 30px;
      background: #2c3e50;
      color: white;
    }
    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 15px;
    }
    .container {
      width: 80%;
      margin: 20px auto;
      max-width: 1000px;
    }
    .card {
      background: white;
      padding: 20px;
      margin: 15px 0;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .card:hover {
      transform: translateY(-3px);
    }
    h2 {
      color: #2c3e50;
      margin-top: 0;
    }
    ul {
      padding-left: 20px;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #2c3e50;
      color: white;
      margin-top: 20px;
    }
    /* โหมดมืด */
    .dark-mode {
      background: #1e1e2f;
      color: #f5f5f5;
    }
    .dark-mode .card {
      background: #2b2b3d;
      color: #fff;
    }
    .dark-mode h2 {
      color: #4fc3f7;
    }
    .dark-mode footer {
      background: #111122;
    }
    .dark-toggle {
      margin: 10px;
      padding: 8px 15px;
      border: none;
      border-radius: 8px;
      background: #4fc3f7;
      color: white;
      cursor: pointer;
      font-size: 14px;
    }
    .dark-toggle:hover {
      background: #0288d1;
    }
  </style>
</head>
<body>
  <header>
    <img src="profile.jpg" alt="รูปโปรไฟล์">
    <h1>สวัสดีครับ ผมชื่อ ทินภัทร บริรักษ์สาทร</h1>
    <p><strong>ชื่อเล่น:</strong> Bxbysmurf / BxbyPeafirst</p>
    <p><strong>อายุ:</strong> 20 ปี</p>
    <p><strong>วันเกิด:</strong> 17 มกราคม 2548</p>
    <p><strong>อีเมล:</strong> peafirst.tnpbrt@gmail.com | peafirstvegetable@gmail.com</p>
    <p><strong>โทร:</strong> 092-614-5423</p>
    <button class="dark-toggle" onclick="toggleDarkMode()">🌙 โหมดมืด</button>
  </header>

  <div class="container">
    <div class="card">
      <h2>🎓 การศึกษา</h2>
      <ul>
        <li><strong>อนุบาล:</strong> โรงเรียนอนุบาลเมืองใหม่ชลบุรี</li>
        <li><strong>มัธยมต้น:</strong> โรงเรียนเปรื่องอนุสรณ์</li>
        <li><strong>มัธยมปลาย:</strong> โรงเรียนเปรื่องอนุสรณ์ (สายวิทย์-คณิต)</li>
        <li><strong>วิทยาลัย:</strong> วิทยาลัยเทคนิคบางแสน – สาขาเมคคาทรอนิกส์และหุ่นยนต์</li>
      </ul>
    </div>

    <div class="card">
      <h2>💡 ทักษะ</h2>
      <ul>
        <li>การเขียนโปรแกรม (AI, เว็บ, หุ่นยนต์)</li>
        <li>การสื่อสารภาษาอังกฤษ</li>
        <li>การแก้ปัญหา (คณิตศาสตร์ & ฟิสิกส์)</li>
        <li>การออกแบบด้วยคอมพิวเตอร์ (SolidWorks)</li>
        <li>ระบบอิเล็กทรอนิกส์และระบบอัตโนมัติ</li>
      </ul>
    </div>

    <div class="card">
      <h2>📌 กิจกรรม</h2>
      <ul>
        <li>เล่นและแต่งเพลง</li>
        <li>พัฒนาและดัดแปลงเกม</li>
        <li>ออกแบบและพัฒนาเว็บไซต์</li>
        <li>เขียนโค้ดด้านอิเล็กทรอนิกส์และเมคคาทรอนิกส์</li>
        <li>สอน AI ให้กับเด็กนักเรียน</li>
      </ul>
    </div>

    <div class="card">
      <h2>📜 เกียรติบัตร</h2>
      <ul>
        <li>การเขียนโปรแกรมหุ่นยนต์</li>
        <li>การเขียนโค้ดพัฒนาเว็บไซต์</li>
        <li>การแข่งขันคณิตศาสตร์เร็ว</li>
        <li>การดัดแปลงเกม (Minecraft, PvZ)</li>
        <li>การสอน AI สำหรับเด็ก</li>
        <li>การออกแบบวงจร PLC</li>
      </ul>
    </div>

    <div id="game-projects" class="card">
      <h2>🎮 โปรเจกต์เกม</h2>
      <ul>
        <li>ม็อด Minecraft สำหรับระบบอัตโนมัติในเซิร์ฟเวอร์</li>
        <li>ม็อดด้านอิเล็กทรอนิกส์และวิศวกรรม</li>
        <li>โปรเจกต์เกมธีมเมคคาทรอนิกส์</li>
        <li>ม็อด Plant vs Zombie (เพิ่มความยากของซอมบี้)</li>
        <li>เครื่องมือช่วยสร้างสิ่งปลูกสร้าง Minecraft แบบรวดเร็ว</li>
      </ul>
    </div>

    <div id="gpa" class="card">
      <h2>📊 เกรดเฉลี่ย (GPA)</h2>
      <ul>
        <li><strong>อนุบาล:</strong> 4.00</li>
        <li><strong>มัธยมต้น:</strong> 3.96</li>
        <li><strong>มัธยมปลาย:</strong> 3.37</li>
        <li><strong>วิทยาลัย:</strong> 2.00</li>
      </ul>
    </div>

    <div id="favorite-subjects" class="card">
      <h2>📘 วิชาที่ชื่นชอบ</h2>
      <ul>
        <li>คณิตศาสตร์</li>
        <li>วิทยาศาสตร์</li>
        <li>ฟิสิกส์</li>
        <li>วิทยาการคอมพิวเตอร์</li>
        <li>ภาษาอังกฤษ</li>
        <li>เขียนแบบด้วยคอมพิวเตอร์ (SolidWorks)</li>
        <li>การเขียนโปรแกรม</li>
      </ul>
    </div>
  </div>

  <footer>
    <p>© 2025 ทินภัทร บริรักษ์สาทร | เว็บไซต์แฟ้มสะสมผลงาน</p>
  </footer>

  <script>
    function toggleDarkMode() {
      document.body.classList.toggle('dark-mode');
    }
  </script>
</body>
</html>
</body>
</html>
