
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>ESHWARI TIMES — Breaking: Idli Scandal</title>

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville:wght@400;700;900&family=Source+Sans+3:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    :root{
      --paper-bg: #e9ebec;          /* outer page grey */
      --page: #f8f7f5;              /* inner white-off */
      --text: #111111;
      --muted: #6b6b6b;
      --rule: #d6d4d1;
      --accent: #b91c1c;            /* deep red */
      --funky: #0fb6a1;             /* muted teal for a modern twist */
      --maxw: 920px;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:"Source Sans 3", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background:var(--paper-bg);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:34px 18px;
      display:flex;
      justify-content:center;
    }

    .shell{
      width:100%;
      max-width:var(--maxw);
      background:linear-gradient(0deg, rgba(255,255,255,0.95), rgba(255,255,255,0.95));
      border:1px solid var(--rule);
      padding:44px 46px;
      box-shadow: 0 18px 50px rgba(6,8,10,0.06);
      background-color:var(--page);
    }

    header.mast{
      text-align:center;
      border-bottom:1px solid var(--rule);
      padding-bottom:10px;
      margin-bottom:18px;
    }
    .mast-title{
      font-family:"Libre Baskerville", Georgia, serif;
      font-size:54px;
      margin:0;
      letter-spacing:0.25px;
      color:var(--text);
      font-weight:700;
    }
    .mast-sub{
      font-size:12px;
      color:var(--muted);
      margin-top:6px;
      text-transform:uppercase;
      letter-spacing:1px;
    }

    .headline{
      font-family:"Libre Baskerville", serif;
      font-size:34px;
      line-height:1.08;
      margin:22px 0 8px;
      text-align:left;
      color:var(--text);
      font-weight:700;
    }
    .sub{
      color:var(--muted);
      margin-bottom:18px;
      font-style:italic;
    }

    .grid{
      display:grid;
      grid-template-columns: 1fr 320px;
      gap:28px;
      align-items:start;
    }

    article.story{
      font-size:18px;
      line-height:1.68;
      font-family: "Source Sans 3", Arial, sans-serif;
      color:var(--text);
      text-align:justify;
      column-count:2;
      column-gap:44px;
      column-rule:1px solid #e8e7e5;
    }
    article p{margin:0 0 1.25em 0;}

    .hero{
      margin-bottom:18px;
      border:1px solid var(--rule);
      padding:6px;
      background:linear-gradient(0deg, rgba(0,0,0,0.03), rgba(255,255,255,0.015));
      display:block;
    }
    .hero img{
      width:100%;
      height:auto;
      display:block;
      filter:grayscale(85%) contrast(1.04) brightness(0.98);
      object-fit:cover;
    }

    aside.side{
      font-size:15px;
      color:var(--text);
      padding-left:12px;
      border-left:1px solid var(--rule);
      font-family: "Source Sans 3", Arial, sans-serif;
    }
    .box{
      background:#fff;
      border:1px solid #efeeec;
      padding:14px;
      margin-bottom:12px;
      box-shadow: 0 6px 12px rgba(12,14,15,0.03);
    }
    .proof-title{
      font-family:"Libre Baskerville", serif;
      font-size:16px;
      margin:0 0 6px 0;
      color:var(--text);
    }
    .proof-item{
      font-weight:700;
      margin-top:6px;
      color:var(--funky);
    }

    .qr{
      display:block;
      width:100%;
      text-align:center;
      margin-top:10px;
    }
    .qr img{width:140px;height:140px;border:1px solid #eee;padding:6px;background:#fff}

    .rum{
      margin:18px 0;
      padding:12px 14px;
      background:#fbfbfa;
      border-left:4px solid var(--accent);
      color:var(--muted);
      font-style:italic;
    }

    .cta{
      margin-top:26px;
      border-top:1px solid var(--rule);
      padding-top:18px;
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:12px;
      flex-wrap:wrap;
    }
    .cta .txt{
      font-family:"Libre Baskerville",serif;
      font-size:18px;
    }
    .buttons{display:flex;gap:12px;flex-wrap:wrap}
    .btn{
      display:inline-block;
      padding:10px 14px;
      border-radius:3px;
      text-decoration:none;
      font-weight:700;
      font-size:14px;
    }
    .btn-primary{background:var(--funky);color:#fff}
    .btn-outline{border:1px solid #ddd;color:var(--text);background:transparent}

    footer{
      margin-top:18px;
      color:var(--muted);
      font-size:13px;
      border-top:1px dashed #eee;
      padding-top:12px;
      display:flex;
      justify-content:space-between;
      gap:12px;
      flex-wrap:wrap;
    }

    @media (max-width:920px){
      .mast-title{font-size:42px}
      .grid{grid-template-columns:1fr}
      article.story{column-count:1}
      .headline{font-size:28px}
      .hero img{max-height:360px;object-fit:cover}
      .side{border-left:none;padding-left:0;padding-top:14px;border-top:1px solid var(--rule)}
    }
   @media (max-width: 768px) {
  body {
    background: var(--page);
    padding: 0;
  }

  .container {
    max-width: 100%;
    margin: 0;
    border: none;
    box-shadow: none;
    padding: 30px 20px;
  }

  header h1 {
    font-size: 40px;
    letter-spacing: 0.2px;
  }

  .headline {
    font-size: 26px;
    line-height: 1.3;
    padding: 0 10px;
  }

  .subhead {
    font-size: 16px;
    padding: 0 12px;
  }

  .hero img {
    max-width: 100%;
    border-radius: 2px;
    border: 1px solid #ccc;
  }

  article {
    font-size: 16px;
    line-height: 1.7;
    padding: 0 10px;
  }

  .cta p {
    font-size: 18px;
    margin-bottom: 12px;
  }

  footer {
    font-size: 12px;
    line-height: 1.5;
  }
}
  </style>
</head>

<body>
  <div class="shell" role="main" aria-labelledby="masthead">
    <header class="mast" id="masthead">
      <div class="mast-title">ESHWARI TIMES</div>
      <div class="mast-sub">Serving the freshest scoop from the tiffin world — #DramaAtEshwari</div>
    </header>

    <h1 class="headline">BREAKING: IDLI CAUGHT CHEATING ON SAMBAR WITH CHICKEN CURRY</h1>
    <div class="sub">A spicy new pairing rocks the batter community — eyewitness accounts and a leaked menu confirm the scandal.</div>

    <div class="grid">
      <!-- left column -->
      <div>
        <div class="hero" aria-hidden="true">
          <img src="0EEA155E-F57A-4523-9420-749CD46357B3.jpg" alt="Cartoon: Idli caught cheating on Sambar with Chicken Curry">
        </div>

        <article class="story" aria-label="Main article">
          <p>For decades, <strong>Idli</strong> and <strong>Sambar</strong> have been the most comfortable pairing on the breakfast table — unassuming, reliable and beloved by the city. But this past Sunday, eyewitnesses at <em>Eshwari Canteen</em> reported seeing Idli spending time with <strong>Chicken Curry</strong> near the steam counter.</p>

          <p>“I saw them together,” said Dosa, who described the scene as “oddly aromatic.” Sources claim the chemistry between the two was immediate, spicy and unmistakable. Within hours, the canteen quietly added a new pairing to the menu: <strong>Idli + Chicken Curry</strong>.</p>

          <p>Reactions split between outrage and curiosity. Longtime Sambar devotees expressed shock — while adventurous diners queued to try the forbidden combo. Sambar has not given an official statement, though close friends say she is taking time to simmer.</p>

          <div class="rum">🗣️ <strong>Rumour Mill:</strong> Dosa seen flirting with Chukka Curry — Poori reportedly not amused.</div>

          <p>The Eshwari Times will continue to follow the story and publish any fallout. For those tempted, the pairing is now available at the canteen.</p>
        </article>
      </div>

      <!-- right column / sidebar -->
      <aside class="side" aria-label="Sidebar">
        <div class="box">
          <div class="proof-title">PROOF</div>
          <div class="proof-item">Leaked Menu Item — <strong>Idli + Chicken Curry</strong></div>
          <div style="margin-top:10px;">
            <a class="btn btn-outline" id="view-menu" href="#">View full menu →</a>
          </div>
        </div>

        <div class="box">
          <div style="font-weight:700;margin-bottom:8px">WHERE</div>
          <div><a id="visitMap" href="#">Eshwari Canteen — Google Maps</a></div>

          <div class="qr" aria-hidden="true">
            <img id="qrImg" src="qr-placeholder.png" alt="QR code to read more">
            <div style="font-size:13px;color:var(--muted);margin-top:8px">Scan to read on your phone</div>
          </div>
        </div>

        <div class="box">
          <div style="font-weight:700;margin-bottom:8px">RUMOUR</div>
          <div>Sources say the batter community is buzzing. Subscribe to stay ahead of the drama.</div>
        </div>
      </aside>
    </div>

    <div class="cta" role="region" aria-label="Call to action">
      <div class="txt">Taste the scandal — only at <strong>Eshwari Canteen</strong></div>
      <div class="buttons">
        <a class="btn btn-primary" id="orderNow" href="#">Order Online</a>
        <a class="btn btn-outline" id="visitNow" href="#">Visit Us</a>
      </div>
    </div>

    <footer>
      <div>© 2025 Eshwari Canteen · #DramaAtEshwari</div>
      <div>Follow @eshwaricanteen · <a href="#" id="subscribeLink">Subscribe</a></div>
    </footer>
  </div>

  <script>
    // Replace these with your actual live links
    const visitLink = "https://maps.google.com/?q=Eshwari+Canteen";
    const orderLink = "https://share.google/bGszEUYZD6aq"; // ✅ updated Swiggy link
    const menuLink = "https://example.com/menu"; // update if needed

    document.getElementById('visitNow').href = visitLink;
    document.getElementById('visitMap').href = visitLink;
    document.getElementById('orderNow').href = orderLink;
    document.getElementById('view-menu').href = menuLink;
    document.getElementById('subscribeLink').href = "#"; 
  </script>
</body>
</html>
