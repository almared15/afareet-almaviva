# afareet-almavivabody 
{font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: #f2f2f2;
  margin: 0;
  padding: 0;
  direction: rtl;
}
.container {
  max-width: 600px;
  margin: 40px auto;
  background: #fff;
  padding: 30px;
  border-radius: 12px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
h1 {
  color: #cc9900;
  text-align: center;
}
input, textarea {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
  border: 1px solid #ccc;
  border-radius: 6px;
}
button {
  width: 100%;
  padding: 10px;
  background-color: #cc9900;
  color: white;
  border: none;
  border-radius: 6px;
  font-size: 16px;
  cursor: pointer;
}
button:hover {
  background-color: #a77f00;
}
.en {
  margin-top: 40px;
  direction: ltr;
  text-align: left;
}


<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>عفاريت المافيفا</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>عفاريت المافيفا - اشتراك البوت</h1>
    <p>اشترك الآن في أقوى بوت لحجز المواعيد تلقائيًا.</p>

    <form action="https://formspree.io/f/xvgryvzo" method="POST">
      <input type="text" name="name" placeholder="الاسم" required>
      <input type="email" name="email" placeholder="البريد الإلكتروني" required>
      <input type="text" name="phone" placeholder="رقم الهاتف" required>
      <textarea name="message" placeholder="أخبرنا ماذا تريد..." required></textarea>
      <button type="submit">اشترك الآن</button>
    </form>

    <p class="en">
      <strong>Afareet Al-Maviva - Bot Subscription</strong><br>
      Subscribe now to the most powerful auto-booking bot.<br><br>
      <form action="https://formspree.io/f/xvgryvzo" method="POST">
        <input type="text" name="name" placeholder="Name" required>
        <input type="email" name="email" placeholder="Email" required>
        <input type="text" name="phone" placeholder="Phone Number" required>
        <textarea name="message" placeholder="Write your request..." required></textarea>
        <button type="submit">Subscribe Now</button>
      </form>
    </p>
  </div>
</body>
</html>


