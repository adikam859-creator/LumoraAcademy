<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Lumora Academy — ruang belajar online yang seru, sederhana, dan mudah diakses.">
  <title>Lumora Academy | Belajar Jadi Lebih Mudah</title>
  <style>
    :root{--navy:#172554;--blue:#4f46e5;--purple:#7c3aed;--mint:#d1fae5;--ink:#1f2937;--muted:#64748b;--paper:#f8fafc;--white:#fff}
    *{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;color:var(--ink);background:var(--paper);line-height:1.6}
    a{color:inherit;text-decoration:none}.wrap{width:min(1120px,92%);margin:auto}
    header{position:sticky;top:0;background:rgba(255,255,255,.94);backdrop-filter:blur(12px);z-index:10;border-bottom:1px solid #e8edf5}
    nav{display:flex;align-items:center;justify-content:space-between;gap:18px;padding:14px 0}.brand{display:flex;align-items:center;gap:10px;font-weight:850;font-size:1.12rem;color:var(--navy)}
    .logo{display:grid;place-items:center;width:40px;height:40px;border-radius:14px;background:linear-gradient(135deg,var(--blue),var(--purple));color:white;font-weight:900}
    .navlinks{display:flex;gap:22px;align-items:center;font-size:.94rem;color:#475569}.navlinks a:hover{color:var(--blue)}
    .btn{display:inline-flex;justify-content:center;align-items:center;padding:12px 18px;border-radius:13px;background:var(--blue);color:white;font-weight:750;border:0;cursor:pointer;transition:.2s}
    .btn:hover{transform:translateY(-2px);filter:brightness(1.06)}.btn.light{background:white;color:var(--blue);border:1px solid #e0e7ff}
    .hero{overflow:hidden;padding:76px 0 66px;background:radial-gradient(circle at 85% 20%,#ddd6fe 0,transparent 27%),linear-gradient(135deg,#eef2ff,#f8fafc 60%,#ecfdf5)}
    .hero-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:42px;align-items:center}.eyebrow{display:inline-block;padding:7px 12px;border-radius:99px;background:#e0e7ff;color:#4338ca;font-weight:800;font-size:.82rem}
    h1{font-size:clamp(2.5rem,5vw,4.4rem);line-height:1.08;letter-spacing:-.045em;color:var(--navy);margin:18px 0}.gradient{color:var(--purple)}
    .hero p{font-size:1.08rem;color:#526078;max-width:560px}.actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:25px}
    .visual{position:relative;min-height:330px;display:grid;place-items:center}.orb{width:min(340px,80vw);aspect-ratio:1;border-radius:42% 58% 61% 39%/42% 42% 58% 58%;background:linear-gradient(145deg,#818cf8,#a78bfa 55%,#6ee7b7);display:grid;place-items:center;box-shadow:0 25px 65px #6366f133;transform:rotate(-5deg)}
    .book{width:190px;height:220px;border-radius:18px;background:white;box-shadow:0 18px 35px #312e811f;transform:rotate(5deg);padding:22px;display:flex;flex-direction:column;justify-content:space-between}
    .book .mini-logo{width:42px;height:42px;border-radius:13px;background:#4f46e5;color:white;display:grid;place-items:center;font-size:1.3rem;font-weight:900}
    .book strong{font-size:1.3rem;line-height:1.2;color:var(--navy)}.book small{color:var(--muted)}
    .float{position:absolute;background:white;padding:12px 16px;border-radius:15px;box-shadow:0 12px 35px #0f172a12;font-weight:750}.float.one{top:24px;right:0}.float.two{bottom:25px;left:0}
    section{padding:66px 0}.section-head{text-align:center;max-width:650px;margin:0 auto 32px}.section-head h2{font-size:clamp(1.8rem,3vw,2.5rem);line-height:1.2;color:var(--navy);margin:0 0 10px}.section-head p{color:var(--muted);margin:0}
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}.feature,.course,.about-card{background:white;border:1px solid #e8edf5;border-radius:22px;padding:24px;box-shadow:0 8px 25px #0f172a05}
    .icon{width:48px;height:48px;display:grid;place-items:center;border-radius:15px;background:#eef2ff;font-size:1.4rem;margin-bottom:15px}.feature h3,.course h3{margin:0 0 7px;color:var(--navy)}.feature p,.course p{color:var(--muted);margin:0}
    .courses{background:#f1f5f9}.course-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}.course-top{height:125px;border-radius:16px;display:grid;place-items:center;font-size:2.6rem;margin-bottom:17px}.c1{background:#e0e7ff}.c2{background:#d1fae5}.c3{background:#fef3c7}.tag{display:inline-block;margin:0 0 10px;padding:4px 9px;background:#f1f5f9;border-radius:99px;font-size:.76rem;font-weight:800;color:#475569}
    .course .btn{margin-top:18px;width:100%;padding:10px}.notice{font-size:.84rem;color:#64748b;margin-top:15px;text-align:center}
    .about-grid{display:grid;grid-template-columns:1fr 1fr;gap:30px;align-items:center}.about-grid h2{font-size:2.2rem;line-height:1.2;color:var(--navy)}.about-grid p{color:var(--muted)}
    .checklist{list-style:none;padding:0}.checklist li{margin:10px 0}.checklist li:before{content:"✓";display:inline-grid;place-items:center;background:#d1fae5;color:#047857;width:24px;height:24px;border-radius:50%;font-weight:900;margin-right:9px}
    .cta{background:linear-gradient(135deg,#312e81,#4f46e5);color:white;border-radius:28px;padding:40px;text-align:center}.cta h2{font-size:2rem;margin:0 0 8px}.cta p{color:#e0e7ff;margin:0 0 22px}.cta .btn{background:white;color:#4338ca}
    footer{padding:25px 0;border-top:1px solid #e2e8f0;color:var(--muted);font-size:.9rem}.footer-row{display:flex;justify-content:space-between;gap:15px;flex-wrap:wrap}
    .modal{display:none;position:fixed;inset:0;background:#0f172acc;z-index:20;align-items:center;justify-content:center;padding:20px}.modal.show{display:flex}.modal-box{width:min(460px,100%);background:white;border-radius:22px;padding:28px;position:relative}.close{position:absolute;right:16px;top:12px;border:0;background:#f1f5f9;border-radius:9px;padding:7px 11px;cursor:pointer}.modal-box h2{color:var(--navy);margin-top:0}.modal-box p{color:var(--muted)}.lesson-list{padding-left:20px}.lesson-list li{margin:9px 0}
    @media(max-width:800px){.hero-grid,.about-grid{grid-template-columns:1fr}.hero{padding-top:52px}.visual{min-height:290px}.features,.course-grid{grid-template-columns:1fr 1fr}.navlinks{gap:12px}.navlinks a:not(.btn){display:none}}
    @media(max-width:520px){.features,.course-grid{grid-template-columns:1fr}.float.one{right:0}.float.two{left:0}.cta{padding:30px 20px}section{padding:50px 0}}
  </style>
</head>
<body>
<header>
  <div class="wrap"><nav aria-label="Navigasi utama">
    <a class="brand" href="#beranda"><span class="logo">L</span><span>Lumora Academy</span></a>
    <div class="navlinks"><a href="#fitur">Keunggulan</a><a href="#kelas">Kelas</a><a href="#tentang">Tentang</a><a class="btn" href="#kelas">Mulai Belajar</a></div>
  </nav></div>
</header>
<main>
  <section class="hero" id="beranda"><div class="wrap hero-grid">
    <div><span class="eyebrow">✦ Belajar • Bertumbuh • Berkarya</span>
      <h1>Langkah kecil hari ini, <span class="gradient">masa depan cerah.</span></h1>
      <p>Selamat datang di Lumora Academy, ruang belajar online untuk menemukan ilmu baru, mengasah keterampilan, dan berkembang dengan cara yang menyenangkan.</p>
      <div class="actions"><a class="btn" href="#kelas">Jelajahi Kelas <span aria-hidden="true">&nbsp;→</span></a><a class="btn light" href="#tentang">Kenali Lumora</a></div>
    </div>
    <div class="visual" aria-label="Ilustrasi buku belajar"><div class="orb"><div class="book"><span class="mini-logo">L</span><strong>Belajar hal baru, setiap hari.</strong><small>LUMORA ACADEMY</small></div></div><div class="float one">💡 Ide jadi karya</div><div class="float two">📚 Belajar sesuai ritme</div></div>
  </div></section>
  <section id="fitur"><div class="wrap"><div class="section-head"><h2>Belajar lebih nyaman, mulai dari sini</h2><p>Tempat belajar yang dirancang agar kamu bisa memulai dari dasar dan berkembang selangkah demi selangkah.</p></div>
    <div class="features">
      <article class="feature"><div class="icon">🎯</div><h3>Materi terarah</h3><p>Mulai dari pengenalan konsep hingga latihan sederhana yang mudah diikuti.</p></article>
      <article class="feature"><div class="icon">⏰</div><h3>Belajar fleksibel</h3><p>Atur waktu belajarmu sendiri dan ulangi materi kapan pun kamu perlu.</p></article>
      <article class="feature"><div class="icon">🌱</div><h3>Tumbuh bersama</h3><p>Bangun kebiasaan belajar, berani mencoba, dan rayakan setiap kemajuan.</p></article>
    </div>
  </div></section>
  <section class="courses" id="kelas"><div class="wrap"><div class="section-head"><h2>Pilih kelas pertamamu</h2><p>Jelajahi kelas pengantar berikut. Tekan tombol untuk melihat gambaran materi belajar.</p></div>
    <div class="course-grid">
      <article class="course"><div class="course-top c1">💻</div><span class="tag">PEMULA</span><h3>Dasar Pemrograman</h3><p>Kenali logika pemrograman dan mulai menulis kode Python pertamamu.</p><button class="btn open-lesson" data-course="python">Lihat Materi</button></article>
      <article class="course"><div class="course-top c2">🌐</div><span class="tag">KREATIF</span><h3>Web Development</h3><p>Pelajari peran HTML, CSS, dan JavaScript dalam membuat website.</p><button class="btn open-lesson" data-course="web">Lihat Materi</button></article>
      <article class="course"><div class="course-top c3">🧠</div><span class="tag">PENGEMBANGAN DIRI</span><h3>Strategi Belajar</h3><p>Latih fokus, atur waktu, dan buat rencana belajar yang realistis.</p><button class="btn open-lesson" data-course="belajar">Lihat Materi</button></article>
    </div><p class="notice">Materi di halaman ini adalah contoh awal dan dapat dikembangkan sesuai kebutuhan belajar.</p>
  </div></section>
  <section id="tentang"><div class="wrap about-grid">
    <div><span class="eyebrow">TENTANG KAMI</span><h2>Setiap orang bisa terus belajar.</h2><p>Lumora Academy hadir dengan semangat bahwa pendidikan seharusnya terasa ramah, mudah dijangkau, dan memberi ruang untuk mencoba. Tidak harus langsung ahli—yang penting berani memulai.</p><ul class="checklist"><li>Bahasa yang mudah dipahami</li><li>Cocok untuk langkah awal</li><li>Berfokus pada proses dan kemajuan</li></ul></div>
    <div class="about-card"><div class="icon">✨</div><h3>Misi Lumora</h3><p>Membantu pelajar menemukan rasa percaya diri untuk mengeksplorasi pengetahuan dan mengubah rasa ingin tahu menjadi keterampilan nyata.</p><hr style="border:0;border-top:1px solid #e8edf5;margin:22px 0"><strong style="color:#4338ca">“Terus bertumbuh, satu pelajaran setiap hari.”</strong></div>
  </div></section>
  <section><div class="wrap"><div class="cta"><h2>Siap memulai perjalanan belajarmu?</h2><p>Pilih topik yang menarik perhatianmu dan mulai dari satu langkah sederhana.</p><a class="btn" href="#kelas">Mulai dari Kelas</a></div></div></section>
</main>
<footer><div class="wrap footer-row"><span><strong style="color:#172554">Lumora Academy</strong> — Belajar jadi lebih mudah.</span><span>© <span id="year"></span> Lumora Academy</span></div></footer>
<div class="modal" id="lessonModal" role="dialog" aria-modal="true" aria-labelledby="modalTitle"><div class="modal-box"><button class="close" id="closeModal" aria-label="Tutup">✕</button><h2 id="modalTitle">Materi kelas</h2><p id="modalIntro"></p><ol class="lesson-list" id="lessonList"></ol><button class="btn" id="doneButton">Siap Belajar</button></div></div>
<script>
  document.getElementById('year').textContent = new Date().getFullYear();
  const lessons = {
    python:{title:'Dasar Pemrograman',intro:'Gambaran materi pengantar Python:',items:['Apa itu pemrograman dan Python','Variabel, tipe data, dan input/output','Percabangan if/else','Latihan: menghitung luas persegi panjang']},
    web:{title:'Web Development',intro:'Gambaran materi pengantar pembuatan website:',items:['Struktur halaman dengan HTML','Mengatur tampilan menggunakan CSS','Membuat tombol interaktif dengan JavaScript','Latihan: membuat halaman profil sederhana']},
    belajar:{title:'Strategi Belajar',intro:'Gambaran materi membangun kebiasaan belajar:',items:['Menentukan tujuan belajar yang jelas','Membagi tugas menjadi langkah kecil','Teknik fokus dan jeda istirahat','Mengevaluasi kemajuan setiap minggu']}
  };
  const modal=document.getElementById('lessonModal');
  document.querySelectorAll('.open-lesson').forEach(button=>button.addEventListener('click',()=>{
    const lesson=lessons[button.dataset.course];
    document.getElementById('modalTitle').textContent=lesson.title;
    document.getElementById('modalIntro').textContent=lesson.intro;
    const list=document.getElementById('lessonList');list.innerHTML='';
    lesson.items.forEach(item=>{const li=document.createElement('li');li.textContent=item;list.appendChild(li)});
    modal.classList.add('show');document.getElementById('closeModal').focus();
  }));
  function closeModal(){modal.classList.remove('show')}
  document.getElementById('closeModal').addEventListener('click',closeModal);
  document.getElementById('doneButton').addEventListener('click',closeModal);
  modal.addEventListener('click',e=>{if(e.target===modal)closeModal()});
  document.addEventListener('keydown',e=>{if(e.key==='Escape')closeModal()});
</script>
</body>
</html>
