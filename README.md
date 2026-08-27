<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>eider.cc</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: #0f172a;
      color: #f8fafc;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1.5rem;
    }
    .card {
      max-width: 480px;
      width: 100%;
      background-color: #1e293b;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.3);
      border: 1px solid #334155;
    }
    .hero-image {
      width: 100%;
      height: 260px;
      object-fit: cover;
      display: block;
    }
    .content {
      padding: 2rem;
    }
    .tag {
      display: inline-block;
      background: #38bdf820;
      color: #38bdf8;
      padding: 0.25rem 0.75rem;
      border-radius: 9999px;
      font-size: 0.875rem;
      font-weight: 500;
      margin-bottom: 1rem;
    }
    h1 {
      font-size: 1.75rem;
      font-weight: 700;
      letter-spacing: -0.025em;
      margin-bottom: 0.5rem;
      color: #ffffff;
    }
    p {
      color: #94a3b8;
      font-size: 0.95rem;
      line-height: 1.5;
      margin-bottom: 1.5rem;
    }
    .contact-btn {
      display: inline-block;
      width: 100%;
      text-align: center;
      background-color: #0284c7;
      color: #ffffff;
      padding: 0.75rem 1.25rem;
      border-radius: 6px;
      font-weight: 600;
      text-decoration: none;
      transition: background-color 0.2s;
    }
    .contact-btn:hover {
      background-color: #0369a1;
    }
  </style>
</head>
<body>
  <div class="card">
    <img 
      src="https://images.unsplash.com/photo-1611689342806-0863700ce1e4?auto=format&fit=crop&w=800&q=80" 
      alt="Peregrine Falcon" 
      class="hero-image"
    >
    <div class="content">
      <span class="tag">eider.cc</span>
      <h1>Peregrine Falcon</h1>
      <p>Welcome to eider.cc. This site is currently under development.</p>
      <a href="mailto:contact@eider.cc" class="contact-btn">Get in Touch</a>
    </div>
  </div>
</body>
</html>
