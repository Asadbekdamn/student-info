
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>O‘qish joyidan ma’lumotnoma</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background: #f7f9fc;
      margin: 0;
      padding: 20px;
      display: flex;
      justify-content: center;
    }

    .doc {
      background: #fff;
      padding: 30px 25px;
      border-radius: 10px;
      max-width: 620px;
      width: 100%;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      border: 1px solid #e2e8f0;
    }

    h2 {
      text-align: center;
      margin-bottom: 5px;
      color: #333;
    }

    .meta {
      text-align: center;
      font-size: 0.95rem;
      color: #555;
      margin-bottom: 20px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      font-size: 0.95rem;
    }

    th, td {
      border: 1px solid #e0e0e0;
      padding: 8px 10px;
      text-align: left;
      vertical-align: top;
    }

    th {
      background: #f2f4f7;
      font-weight: 600;
      width: 45%;
    }

    .qr {
      text-align: center;
      margin-top: 25px;
    }

    .qr img {
      width: 160px;
      height: 160px;
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 6px;
      background: #fff;
    }

    footer {
      text-align: center;
      font-size: 0.85rem;
      color: #777;
      margin-top: 20px;
    }

    .note {
      margin-top: 20px;
      text-align: center;
      font-weight: 600;
      color: #444;
    }
  </style>
</head>
<body>
  <div class="doc">
    <h2>Yaponiya raqamli universiteti</h2>
    <div class="meta">
      № 498221100087/1<br>
      Hujjat yaratilgan sana: 10.28.2025
    </div>

    <h3 style="text-align:center;">O‘QISH JOYIDAN MA’LUMOTNOMA<br><small>СПРАВКА С МЕСТА УЧЁБЫ</small></h3>

    <table>
      <tr>
        <th>F.I.SH. / Ф.И.О.:</th>
        <td>RIZAYEV ASADBEK TURSUNPO‘LOT O‘G‘LI</td>
      </tr>
      <tr>
        <th>Tug‘ilgan sana / Дата рождения:</th>
        <td>05.07.2004</td>
      </tr>
      <tr>
        <th>Fuqaroligi / Гражданство:</th>
        <td>O‘zbekiston Respublikasi fuqarosi </td>
      </tr>
      <tr>
        <th>Ta’lim turi / Вид образования:</th>
        <td>Bakalavr </td>
      </tr>
      <tr>
        <th>Ta’lim shakli / Форма обучения:</th>
        <td>Kunduzgi </td>
      </tr>
      <tr>
        <th>Qabul turi / Тип приёма:</th>
        <td>To‘lov-shartnoma </td>
      </tr>
      <tr>
        <th>O‘qishni boshlagan yil :</th>
        <td>2022</td>
      </tr>
      <tr>
        <th>Fakultet / Факультет:</th>
        <td>Axborot texnologiyalari menejmenti </td>
      </tr>
      <tr>
        <th>Yo‘nalish / Направление:</th>
        <td>Dasturiy injiniring </td>
      </tr>
      <tr>
        <th>O‘quv kursi / Курс обучения:</th>
        <td>4-kurs </td>
      </tr>
      <tr>
        <th>Oliy ta’lim muassasasi / Высшее учебное заведение:</th>
        <td>Yaponiya raqamli universiteti </td>
      </tr>
    </table>

    <div class="note">
      Ma’lumot so‘ralgan joyga taqdim etish uchun berildi.<br>
      Справка выдана для представления по месту требования.
    </div>


    <footer>© 2025 Yaponiya raqamli universiteti</footer>
  </div>

  <script>
    const pageUrl = window.location.href;
    const qr = document.getElementById('qrImage');
    qr.src = "https://chart.googleapis.com/chart?cht=qr&chs=300x300&chl=" + encodeURIComponent(pageUrl);
  </script>
</body>
</html>
