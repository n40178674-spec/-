<!doctype html>

<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>صفحتي الشخصية</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#06b6d4;--muted:#94a3b8;--glass: rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    body{margin:0;font-family:system-ui, -apple-system, 'Segoe UI', Roboto, 'Noto Sans', 'Helvetica Neue', Arial; background:linear-gradient(180deg,#071026 0%, #071822 100%);color:#e6eef6;display:flex;align-items:center;justify-content:center;min-height:100vh;padding:24px}
    .container{width:100%;max-width:980px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:14px;padding:26px;box-shadow:0 8px 30px rgba(2,6,23,0.6);display:grid;grid-template-columns:320px 1fr;gap:22px}
    .profile{background:var(--card);padding:20px;border-radius:12px;text-align:center}
    .avatar{width:220px;height:220px;border-radius:12px;object-fit:cover;border:4px solid rgba(255,255,255,0.05);background:var(--glass);display:block;margin:0 auto}
    h1{margin:12px 0 6px;font-size:22px}
    .role{color:var(--muted);margin:0 0 14px}
    .contacts{display:flex;flex-direction:column;gap:8px;margin-top:10px}
    .btn{display:inline-flex;gap:8px;align-items:center;justify-content:center;padding:10px 12px;border-radius:10px;text-decoration:none;font-weight:600}
    .btn--social{background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.03;color:#eaf6fb}
    .btn svg{width:18px;height:18px;opacity:0.95}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.02));padding:20px;border-radius:12px}
    .section-title{display:flex;align-items:center;justify-content:space-between;margin-bottom:12px}
    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .skill{background:rgba(255,255,255,0.03);padding:8px 10px;border-radius:10px;font-weight:600;color:var(--muted)}
    .info-list{display:grid;gap:8px}
    .info-item{display:flex;justify-content:space-between;padding:10px;border-radius:8px;background:rgba(255,255,255,0.02)}
    .intro{line-height:1.6;color:#d3e9f0}
    footer{grid-column:1/-1;text-align:center;color:var(--muted);margin-top:12px;font-size:13px}
    @media(max-width:820px){.container{grid-template-columns:1fr} .profile{order:2}}
  </style>
</head>
<body>
  <div class="container">
    <div class="profile">
      <!-- ضع اسم الملف الخاص بصورتك في src (مثال: profile.jpg) في نفس المجلد مع هذا الملف -->
      <img class="avatar" src="html nassssr/nasr.png" alt="صورتي الشخصية">
      <h1>نصر الله</h1>
      <p class="role">مصمم · مبرمج · ناشط عالمي</p><div class="contacts">
    <a class="btn btn--social" href="https://www.facebook.com/share/1ZdfzB9DF8/" target="_blank" rel="noopener"> 
      <!-- Facebook SVG -->
      <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.99H7.898v-2.888h2.54V9.845c0-2.507 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.463h-1.26c-1.243 0-1.63.771-1.63 1.562v1.875h2.773l-.443 2.888h-2.33V21.88C18.343 21.128 22 16.99 22 12z"/></svg>
      فيسبوك
    </a>

    <a class="btn btn--social" href="https://instagram.com/twx711" target="_blank" rel="noopener">
      <!-- Instagram SVG -->
      <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5zm5 6.5A4.5 4.5 0 1 0 16.5 13 4.5 4.5 0 0 0 12 8.5zm5.5-3.9a1.1 1.1 0 1 0 1.1 1.1 1.1 1.1 0 0 0-1.1-1.1z"/></svg>
      انستغرام
    </a>

    <a class="btn btn--social" href="tel:+967779101658">📞 الاتصال: 779101658</a>
    <a class="btn btn--social" href="mailto:n40178674@gmail.com">✉️ البريد: n40178674@gmail.com</a>
  </div>
</div>

<div class="card">
  <div class="section-title">
    <h2>نبذة عني</h2>
  </div>
  <p class="intro">أنا مطور ومصمم رقمي شغوف. أعمل على تصميم واجهات مستخدم جذابة وبرمجة حلول ويب متكاملة. أسعى دائماً لتطوير مهاراتي والمشاركة في مشاريع تترك أثرًا على الصعيد العالمي.</p>

  <hr style="margin:18px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">

  <div class="section-title">
    <h3>المهارات</h3>
  </div>
  <div class="skills" aria-hidden="false">
    <span class="skill">مصمم</span>
    <span class="skill">مبرمج</span>
    <span class="skill">ناشط عالمي</span>
    <span class="skill">تصميم واجهات</span>
    <span class="skill">تطوير ويب</span>
  </div>

  <hr style="margin:18px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">

  <div class="section-title">
    <h3>معلوماتي</h3>
  </div>
  <div class="info-list">
    <div class="info-item"><strong>فيسبوك</strong><span><a href="https://www.facebook.com/share/1ZdfzB9DF8/" target="_blank" rel="noopener">رابط فيسبوك</a></span></div>
    <div class="info-item"><strong>انستغرام</strong><span>@twx711</span></div>
    <div class="info-item"><strong>الهاتف</strong><span>+967 779101658</span></div>
    <div class="info-item"><strong>البريد الإلكتروني</strong><span>n40178674@gmail.com</span></div>
  </div>

</div>

<footer>
    
</footer> <code></code></footer>

  </div>
</body>
</html>
