

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>My GitHub Page</title>
  <meta name="description" content="A simple HTML template for a GitHub repository." />
  <style>
    :root{--bg:#0f1724;--card:#111827;--muted:#9ca3af;--accent:#60a5fa}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;background:linear-gradient(180deg,var(--bg),#071028);color:#e6eef8;line-height:1.5}
    .wrap{max-width:900px;margin:48px auto;padding:24px}
    header{display:flex;justify-content:space-between;align-items:center}
    .logo{font-weight:700;letter-spacing:0.4px}
    nav a{color:var(--muted);text-decoration:none;margin-left:16px}
    .hero{background:rgba(255,255,255,0.03);padding:28px;border-radius:12px;margin-top:20px}
    h1{margin:0 0 8px;font-size:28px}
    p.lead{margin:0;color:var(--muted)}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:20px}
    .card{background:rgba(255,255,255,0.02);padding:18px;border-radius:10px}
    footer{margin-top:28px;color:var(--muted);font-size:13px}
    .btn{display:inline-block;padding:8px 12px;border-radius:8px;background:var(--accent);color:#04203a;text-decoration:none;font-weight:600}
    @media (max-width:520px){h1{font-size:22px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">MyRepo</div>
      <nav>
        <a href="#">Home</a>
        <a href="#features">Features</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

  </div>
</body>
</html>
