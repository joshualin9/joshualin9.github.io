<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Save the Date | 18 August 2026</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
  <style>
    :root {
      --ivory: #f8f6f1;
      --soft-green: #c9d6c3;
      --light-yellow: #f2e7b6;
      --text-dark: #3b3b3b;
      --accent: #9fb39a;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: var(--ivory);
      color: var(--text-dark);
    }

    .container { max-width: 820px; margin: 0 auto; padding: 48px 24px 72px; }

    .card {
      background: #ffffff;
      border-radius: 24px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.06);
      padding: 56px 40px;
      position: relative;
      overflow: hidden;
    }

    .card::before {
      content: "";
      position: absolute;
      inset: 0;
      background:
        radial-gradient(circle at top left, var(--soft-green), transparent 55%),
        radial-gradient(circle at bottom right, var(--light-yellow), transparent 55%);
      opacity: 0.2;
      pointer-events: none;
    }

    .content { position: relative; z-index: 1; }
    h1 { font-family: 'Playfair Display', serif; font-weight: 500; text-align: center; margin: 0 0 12px; font-size: 40px; }
    .names { font-family: 'Playfair Display', serif; text-align: center; font-size: 34px; margin: 12px 0 20px; }
    .date { text-align: center; font-size: 18px; letter-spacing: 0.2em; text-transform: uppercase; margin-bottom: 36px; color: #5b5b5b; }
    .divider { width: 80px; height: 2px; background: var(--accent); margin: 32px auto; border-radius: 2px; }
    .section { margin-bottom: 36px; }
    .section h2 { font-family: 'Playfair Display', serif; font-weight: 500; font-size: 22px; margin-bottom: 12px; }
    .section p { margin: 0; line-height: 1.7; font-size: 16px; }
    .highlight { background: rgba(201, 214, 195, 0.25); padding: 16px 20px; border-radius: 14px; margin-top: 16px; }
    .rsvp { margin-top: 24px; padding: 24px; border-radius: 18px; background: #f8f6f1; border: 1px solid rgba(0, 0, 0, 0.05); }
    .rsvp p { margin-bottom: 16px; }
    .rsvp-button { display: block; width: 100%; text-align: center; margin-top: 20px; padding: 16px 0; border-radius: 12px; background: #c9d6c3; color: var(--text-dark); text-decoration: none; font-size: 16px; font-weight: 500; transition: transform 0.2s ease, box-shadow 0.2s ease; }
    .rsvp-button:hover { transform: translateY(-2px); box-shadow: 0 8px 24px rgba(0,0,0,0.15); }
    .subtle-note { margin-top: 8px; font-size: 14px; color: #5b5b5b; text-align: center; }
    footer { text-align: center; margin-top: 48px; font-size: 14px; color: #6b6b6b; }
    @media (max-width: 600px) { h1 { font-size: 34px; } .names { font-size: 28px; } .card { padding: 40px 24px; } }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="content">
        <h1>Save the Date</h1>
        <div class="names">Joshua Lin &amp; Sem Yih Lum</div>
        <div class="date">Tuesday · 18 August 2026</div>

        <div class="divider"></div>

        <div class="section">
          <p style="text-align:center; font-size:17px;">
            We would love for you to join us as we celebrate our wedding.
          </p>
        </div>

        <div class="section">
          <h2>Ceremony</h2>
          <p>
            Our ceremony will take place on the same day in the <strong>afternoon</strong>.
            <br />
            <strong>Location:</strong> To be confirmed
          </p>
          <div class="highlight">
            <p>
              As this is a weekday, we completely understand that not everyone may be able to attend the ceremony.
              Please let us know if you are able to join us.
            </p>
          </div>
        </div>

        <div class="section">
          <h2>Reception</h2>
          <p>
            <strong>Bossley Bar &amp; Restaurant</strong><br />
            Private Dining Room<br />
            Evening reception to follow the ceremony
          </p>
        </div>

        <div class="section">
          <h2>RSVP</h2>
          <div class="rsvp">
            <p>Please let us know your availability:</p>
            <p style="margin-top:8px;">
              Your response will help us plan our day and is greatly appreciated. Kindly complete your RSVP by <strong>31 January 2026</strong>.
            </p>
            <a href="https://docs.google.com/forms/d/1SK_pXhkDc_DgpcS5Dg5k2RR2XWlEI1mTNbHcVIWfB4k/viewform" target="_blank" class="rsvp-button">Kindly Respond</a>
            <div class="subtle-note">Please respond at your convenience</div>
          </div>
        </div>

        <footer>
          Once your RSVP is received, a formal web invitation will gracefully follow, carrying our joy and anticipation to you.
        </footer>
      </div>
    </div>
  </div>
</body>
</html>
