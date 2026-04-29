<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SHARE-PEN.COM — Investor & Partner Deck</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Inter', sans-serif; background: #0D0D0D; color: #F5F0E8; direction: ltr; }

    .slide {
      width: 100vw; min-height: 100vh;
      display: flex; align-items: center; justify-content: center;
      padding: 4rem 6%;
      position: relative; overflow: hidden;
    }

    .slide-content { width: 100%; max-width: 1100px; }

    /* COLORS */
    :root {
      --ink: #0D0D0D; --parchment: #F5F0E8; --gold: #C9A84C;
      --gold-light: #E8C97A; --red: #8B1A1A; --gray: #8A8278;
    }

    /* SLIDE THEMES */
    .slide-dark { background: var(--ink); }
    .slide-parchment { background: var(--parchment); color: var(--ink); }
    .slide-gold { background: linear-gradient(135deg, #1a1208, #2a1f08); }
    .slide-red { background: linear-gradient(135deg, #1a0505, #2a0808); }

    /* TYPOGRAPHY */
    h1 { font-family: 'Playfair Display', serif; font-size: clamp(2.5rem, 5vw, 5rem); font-weight: 900; line-height: 1.05; }
    h2 { font-family: 'Playfair Display', serif; font-size: clamp(1.8rem, 3.5vw, 3.5rem); font-weight: 700; }
    h3 { font-size: 1.3rem; font-weight: 600; }
    p { line-height: 1.75; }
    .gold { color: var(--gold); }
    .red-txt { color: #ff6b6b; }

    /* NAV DOTS */
    .nav-dots {
      position: fixed; bottom: 2rem; left: 50%; transform: translateX(-50%);
      display: flex; gap: 0.5rem; z-index: 100;
    }
    .dot {
      width: 8px; height: 8px; border-radius: 50%;
      background: rgba(201,168,76,0.3); cursor: pointer; transition: all 0.3s;
      border: none;
    }
    .dot.active { background: var(--gold); transform: scale(1.3); }

    /* SLIDE COUNTER */
    .slide-num {
      position: absolute; bottom: 2rem; right: 2rem;
      font-size: 0.75rem; color: rgba(201,168,76,0.5);
      font-family: 'Playfair Display', serif;
    }

    /* LOGO TOP */
    .slide-logo {
      position: absolute; top: 2rem; left: 3rem;
      font-family: 'Playfair Display', serif; font-size: 1.2rem;
      color: rgba(201,168,76,0.6); letter-spacing: 0.2em;
    }

    /* EYEBROW */
    .eyebrow {
      font-size: 0.75rem; letter-spacing: 0.3em; color: var(--gold);
      text-transform: uppercase; margin-bottom: 1.5rem; display: block;
    }

    /* DIVIDER */
    .gold-line { width: 60px; height: 3px; background: var(--gold); margin: 1.5rem 0; }

    /* GRIDS */
    .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; align-items: center; }
    .three-col { display: grid; grid-template-columns: repeat(3,1fr); gap: 2rem; }
    .four-col { display: grid; grid-template-columns: repeat(4,1fr); gap: 1.5rem; }

    /* STAT BOX */
    .stat-box {
      border: 1px solid rgba(201,168,76,0.3); border-radius: 8px;
      padding: 2rem; text-align: center;
      background: rgba(201,168,76,0.03);
    }
    .stat-num { font-family: 'Playfair Display', serif; font-size: 3rem; font-weight: 900; color: var(--gold); line-height: 1; }
    .stat-label { font-size: 0.85rem; color: var(--gray); margin-top: 0.5rem; }

    /* QUOTE */
    .big-quote {
      font-family: 'Playfair Display', serif; font-size: clamp(1.5rem, 3vw, 2.5rem);
      line-height: 1.5; font-style: italic;
    }
    .quote-mark { font-size: 5rem; color: var(--gold); opacity: 0.4; line-height: 1; }

    /* PROBLEM LIST */
    .problem-list { list-style: none; }
    .problem-list li {
      padding: 1rem 1.5rem; margin-bottom: 0.8rem;
      border-left: 3px solid #ff6b6b;
      background: rgba(255,107,107,0.05); border-radius: 6px 0 0 6px;
      font-size: 1rem;
    }
    .solution-list li {
      border-left-color: var(--gold);
      background: rgba(201,168,76,0.05);
    }

    /* TEAM CARD */
    .team-card { text-align: center; }
    .team-avatar {
      width: 80px; height: 80px; border-radius: 50%; margin: 0 auto 1rem;
      background: linear-gradient(135deg, var(--gold), var(--red));
      display: flex; align-items: center; justify-content: center;
      font-size: 2rem; font-weight: 900;
    }

    /* ROADMAP */
    .roadmap-row { display: flex; gap: 0; }
    .roadmap-item {
      flex: 1; padding: 1.5rem; border: 1px solid rgba(255,255,255,0.08);
      position: relative;
    }
    .roadmap-item.active { border-color: var(--gold); background: rgba(201,168,76,0.05); }
    .roadmap-q { font-size: 0.75rem; color: var(--gold); margin-bottom: 0.5rem; }
    .roadmap-title { font-weight: 600; font-size: 0.95rem; margin-bottom: 0.5rem; }
    .roadmap-items { list-style: none; }
    .roadmap-items li { font-size: 0.8rem; color: var(--gray); padding: 0.2rem 0; }
    .roadmap-items li::before { content: '→ '; color: var(--gold); }

    /* FUNNEL */
    .funnel { display: flex; flex-direction: column; gap: 0; align-items: stretch; max-width: 500px; margin: 0 auto; }
    .funnel-step {
      padding: 1rem 2rem; text-align: center;
      font-weight: 600; position: relative;
      clip-path: polygon(0 0, 100% 0, 92% 100%, 8% 100%);
    }
    .funnel-step:nth-child(1) { background: rgba(201,168,76,0.8); color: #000; width: 100%; }
    .funnel-step:nth-child(2) { background: rgba(201,168,76,0.6); color: #000; width: 85%; align-self: center; }
    .funnel-step:nth-child(3) { background: rgba(201,168,76,0.4); color: #fff; width: 70%; align-self: center; }
    .funnel-step:nth-child(4) { background: rgba(201,168,76,0.25); color: var(--gold); width: 55%; align-self: center; }

    /* SCROLL */
    html { scroll-behavior: smooth; }
    .slide { scroll-snap-align: start; }

    /* KEYBOARD NAV HINT */
    .key-hint {
      position: fixed; bottom: 5rem; left: 50%; transform: translateX(-50%);
      font-size: 0.7rem; color: rgba(201,168,76,0.4); direction: ltr;
    }

    @media (max-width: 768px) {
      .two-col, .three-col, .four-col { grid-template-columns: 1fr; }
      .slide { padding: 2rem 5%; }
      .roadmap-row { flex-direction: column; }
    }
  </style>
</head>
<body>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 1: TITLE -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-dark" id="s1">
  <div class="slide-content" style="text-align: center;">
    <div class="eyebrow" style="justify-content: center; display: block;">The Next Revolution in Writing</div>
    <h1 style="font-size: clamp(3rem,8vw,8rem); letter-spacing: 0.05em;">
      <span class="gold">SHARE</span>-PEN
    </h1>
    <div class="gold-line" style="margin: 2rem auto;"></div>
    <p style="font-size: 1.3rem; color: #8A8278; max-width: 600px; margin: 0 auto 3rem;">
      The platform that gives writers back control over their work, their audience, and their earnings.
    </p>
    <p style="font-size: 0.85rem; color: rgba(201,168,76,0.6); letter-spacing: 0.2em;">SHARE-PEN.COM · 2024</p>
  </div>
  <div class="slide-num">01 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 2: THE PROBLEM -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-red" id="s2">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content">
    <span class="eyebrow">The Problem</span>
    <h2 style="margin-bottom: 2rem;">A System Built <span class="red-txt">Against You</span></h2>
    <div class="two-col">
      <div>
        <ul class="problem-list">
          <li>80% of books submitted to publishers — <strong>rejected</strong></li>
          <li>Average royalty: <strong>5–15%</strong> of cover price</li>
          <li>Time to publication: <strong>18–36 months</strong></li>
          <li>The author knows <strong>not a single reader</strong> personally</li>
          <li>Publishers retain <strong>subsidiary rights</strong></li>
        </ul>
      </div>
      <div>
        <div class="quote-mark">"</div>
        <p class="big-quote" style="font-size: 1.5rem;">
          Years of work, soul poured into pages — reduced to a line in a contract you never fully understood.
        </p>
        <p style="color: var(--gray); margin-top: 1rem; font-size: 0.85rem;">— The experience of 87% of writers we surveyed</p>
      </div>
    </div>
  </div>
  <div class="slide-num">02 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 3: THE OPPORTUNITY -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-dark" id="s3">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content">
    <span class="eyebrow">The Opportunity</span>
    <h2 style="margin-bottom: 3rem;">A Massive Market, <span class="gold">Completely Broken</span></h2>
    <div class="four-col">
      <div class="stat-box">
        <div class="stat-num">$180B</div>
        <div class="stat-label">Global publishing market 2024</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">4.4M</div>
        <div class="stat-label">New books published every year</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">33M</div>
        <div class="stat-label">Active writers worldwide</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">8%</div>
        <div class="stat-label">Published through traditional channels</div>
      </div>
    </div>
    <p style="text-align: center; margin-top: 3rem; font-size: 1.1rem; color: var(--gray);">
      92% of writers — <strong style="color: var(--parchment);">without a home. Without tools. Without an audience.</strong><br>
      These are our customers.
    </p>
  </div>
  <div class="slide-num">03 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 4: THE SOLUTION -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-gold" id="s4">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content">
    <span class="eyebrow">The Solution</span>
    <h2 style="margin-bottom: 2rem;">SHARE-PEN — <span class="gold">The Writer Is the Publisher</span></h2>
    <div class="two-col">
      <div>
        <ul class="problem-list solution-list">
          <li>Instant publishing — no approvals, no waiting</li>
          <li>100% of revenue goes directly to the writer</li>
          <li>Build a direct reader audience (owned audience)</li>
          <li>Serial Publishing — readers follow in real time</li>
          <li>Built-in AI Writing Assistant</li>
          <li>Analytics, newsletter, monetization — all in one</li>
        </ul>
      </div>
      <div>
        <h3 style="margin-bottom: 1.5rem; color: var(--gold);">What Does That Mean in Numbers?</h3>
        <div style="display: flex; flex-direction: column; gap: 1rem;">
          <div style="display: flex; justify-content: space-between; padding: 1rem; background: rgba(0,0,0,0.3); border-radius: 6px;">
            <span>Traditional Publisher</span>
            <span class="red-txt">$1.80 per book</span>
          </div>
          <div style="display: flex; justify-content: space-between; padding: 1rem; background: rgba(0,0,0,0.3); border-radius: 6px;">
            <span>Amazon KDP</span>
            <span style="color: #ffd700;">$6–15 per book</span>
          </div>
          <div style="display: flex; justify-content: space-between; padding: 1rem; background: rgba(201,168,76,0.15); border: 1px solid var(--gold); border-radius: 6px;">
            <span style="font-weight: 700;">SHARE-PEN</span>
            <span class="gold" style="font-weight: 700;">$22 per book + recurring subscription</span>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="slide-num">04 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 5: PRODUCT -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-dark" id="s5">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content">
    <span class="eyebrow">The Product</span>
    <h2 style="margin-bottom: 3rem;">3 Layers. <span class="gold">One System.</span></h2>
    <div class="three-col">
      <div style="padding: 2rem; border: 1px solid rgba(201,168,76,0.3); border-radius: 8px; text-align: center;">
        <div style="font-size: 3rem; margin-bottom: 1rem;">✍️</div>
        <h3 class="gold" style="margin-bottom: 1rem;">CREATE</h3>
        <p style="color: var(--gray); font-size: 0.9rem;">Smart editing, AI assistant, plot management, chapters, structure — all in one place</p>
      </div>
      <div style="padding: 2rem; border: 2px solid var(--gold); border-radius: 8px; text-align: center; background: rgba(201,168,76,0.05);">
        <div style="font-size: 3rem; margin-bottom: 1rem;">📡</div>
        <h3 class="gold" style="margin-bottom: 1rem;">PUBLISH & BUILD</h3>
        <p style="color: var(--gray); font-size: 0.9rem;">Serial Publishing, book branding, reader community, newsletter, engagement tools</p>
      </div>
      <div style="padding: 2rem; border: 1px solid rgba(201,168,76,0.3); border-radius: 8px; text-align: center;">
        <div style="font-size: 3rem; margin-bottom: 1rem;">💰</div>
        <h3 class="gold" style="margin-bottom: 1rem;">MONETIZE</h3>
        <p style="color: var(--gray); font-size: 0.9rem;">Subscriptions, chapter sales, tips, special editions, audiobooks — 0% commission</p>
      </div>
    </div>
  </div>
  <div class="slide-num">05 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 6: TRACTION -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-dark" id="s6">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content">
    <span class="eyebrow">Traction</span>
    <h2 style="margin-bottom: 3rem;">Numbers That <span class="gold">Speak for Themselves</span></h2>
    <div class="four-col">
      <div class="stat-box">
        <div class="stat-num">10K+</div>
        <div class="stat-label">Registered writers</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">250K+</div>
        <div class="stat-label">Active readers</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">$580K</div>
        <div class="stat-label">Revenue to authors (12 months)</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">4.8★</div>
        <div class="stat-label">Average store rating</div>
      </div>
    </div>
    <div style="margin-top: 3rem; padding: 2rem; background: rgba(201,168,76,0.05); border: 1px solid rgba(201,168,76,0.2); border-radius: 8px; text-align: center;">
      <p style="font-size: 1.1rem;">Creator Plan writers earn an average of <strong class="gold">$2,300/month</strong> after 6 months on the platform</p>
    </div>
  </div>
  <div class="slide-num">06 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 7: BUSINESS MODEL -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-gold" id="s7">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content">
    <span class="eyebrow">Business Model</span>
    <h2 style="margin-bottom: 2.5rem;">3 <span class="gold">Growing</span> Revenue Streams</h2>
    <div class="three-col">
      <div style="padding: 2rem; background: rgba(0,0,0,0.3); border-radius: 8px;">
        <h3 style="color: var(--gold); margin-bottom: 1rem;">SaaS Subscriptions</h3>
        <p style="color: var(--gray); font-size: 0.9rem; margin-bottom: 1rem;">Starter: Free · Creator: $13/mo · Pro: $40/mo</p>
        <div style="font-size: 2rem; font-weight: 900; color: var(--parchment);">65%</div>
        <p style="color: var(--gray); font-size: 0.8rem;">of total revenue</p>
      </div>
      <div style="padding: 2rem; background: rgba(0,0,0,0.3); border-radius: 8px;">
        <h3 style="color: var(--gold); margin-bottom: 1rem;">Transaction Fees</h3>
        <p style="color: var(--gray); font-size: 0.9rem; margin-bottom: 1rem;">3–5% on every direct sale made on the platform</p>
        <div style="font-size: 2rem; font-weight: 900; color: var(--parchment);">25%</div>
        <p style="color: var(--gray); font-size: 0.8rem;">of total revenue</p>
      </div>
      <div style="padding: 2rem; background: rgba(0,0,0,0.3); border-radius: 8px;">
        <h3 style="color: var(--gold); margin-bottom: 1rem;">Premium Services</h3>
        <p style="color: var(--gray); font-size: 0.9rem; margin-bottom: 1rem;">Promoted placement, writing workshops, editorial services</p>
        <div style="font-size: 2rem; font-weight: 900; color: var(--parchment);">10%</div>
        <p style="color: var(--gray); font-size: 0.8rem;">of total revenue</p>
      </div>
    </div>
  </div>
  <div class="slide-num">07 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 8: ROADMAP -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-dark" id="s8">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content">
    <span class="eyebrow">Roadmap</span>
    <h2 style="margin-bottom: 3rem;">24 Months <span class="gold">Ahead</span></h2>
    <div class="roadmap-row">
      <div class="roadmap-item active">
        <div class="roadmap-q">Q1–Q2 2024</div>
        <div class="roadmap-title">MVP + Launch</div>
        <ul class="roadmap-items">
          <li>Core writing platform</li>
          <li>Serial Publishing</li>
          <li>Basic monetization</li>
          <li>1,000 beta writers</li>
        </ul>
      </div>
      <div class="roadmap-item">
        <div class="roadmap-q">Q3–Q4 2024</div>
        <div class="roadmap-title">Growth</div>
        <ul class="roadmap-items">
          <li>AI Assistant v1</li>
          <li>Mobile app</li>
          <li>10K writers</li>
          <li>$500K ARR</li>
        </ul>
      </div>
      <div class="roadmap-item">
        <div class="roadmap-q">Q1–Q2 2025</div>
        <div class="roadmap-title">Scale</div>
        <ul class="roadmap-items">
          <li>Audiobook generation</li>
          <li>Global languages</li>
          <li>50K writers</li>
          <li>$3M ARR</li>
        </ul>
      </div>
      <div class="roadmap-item">
        <div class="roadmap-q">Q3–Q4 2025</div>
        <div class="roadmap-title">Expansion</div>
        <ul class="roadmap-items">
          <li>B2B publishing tools</li>
          <li>Rights marketplace</li>
          <li>200K writers</li>
          <li>$15M ARR</li>
        </ul>
      </div>
    </div>
  </div>
  <div class="slide-num">08 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 9: COMPETITIVE -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-dark" id="s9">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content">
    <span class="eyebrow">Competition</span>
    <h2 style="margin-bottom: 2.5rem;">Why <span class="gold">We're Different</span></h2>
    <div style="overflow-x: auto;">
      <table style="width: 100%; border-collapse: collapse; min-width: 600px;">
        <thead>
          <tr style="border-bottom: 2px solid rgba(201,168,76,0.4);">
            <th style="text-align: left; padding: 1rem; color: var(--gray); font-size: 0.85rem;">Feature</th>
            <th style="padding: 1rem; color: var(--gray); font-size: 0.85rem;">Wattpad</th>
            <th style="padding: 1rem; color: var(--gray); font-size: 0.85rem;">Amazon KDP</th>
            <th style="padding: 1rem; color: var(--gray); font-size: 0.85rem;">Substack</th>
            <th style="padding: 1rem; color: var(--gold); font-size: 0.85rem; font-weight: 700;">SHARE-PEN</th>
          </tr>
        </thead>
        <tbody>
          <tr style="border-bottom: 1px solid rgba(255,255,255,0.05);">
            <td style="padding: 1rem; color: var(--parchment);">Owned Audience</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #ffd700;">~</td>
            <td style="text-align: center; padding: 1rem; color: #4CAF50; font-weight: 700;">✓</td>
          </tr>
          <tr style="border-bottom: 1px solid rgba(255,255,255,0.05);">
            <td style="padding: 1rem; color: var(--parchment);">Serial Publishing</td>
            <td style="text-align: center; padding: 1rem; color: #4CAF50;">✓</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #ffd700;">~</td>
            <td style="text-align: center; padding: 1rem; color: #4CAF50; font-weight: 700;">✓</td>
          </tr>
          <tr style="border-bottom: 1px solid rgba(255,255,255,0.05);">
            <td style="padding: 1rem; color: var(--parchment);">AI Writing Tools</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #4CAF50; font-weight: 700;">✓</td>
          </tr>
          <tr style="border-bottom: 1px solid rgba(255,255,255,0.05);">
            <td style="padding: 1rem; color: var(--parchment);">100% Revenue</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #ffd700;">~70%</td>
            <td style="text-align: center; padding: 1rem; color: #ffd700;">~90%</td>
            <td style="text-align: center; padding: 1rem; color: #4CAF50; font-weight: 700;">✓ 100%</td>
          </tr>
          <tr>
            <td style="padding: 1rem; color: var(--parchment);">Audiobook Auto-gen</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #f44336;">✗</td>
            <td style="text-align: center; padding: 1rem; color: #4CAF50; font-weight: 700;">✓</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
  <div class="slide-num">09 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 10: THE VISION -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-dark" id="s10">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content" style="text-align: center;">
    <span class="eyebrow">The Vision</span>
    <div class="quote-mark" style="text-align: center; display: block;">"</div>
    <p class="big-quote" style="max-width: 800px; margin: 0 auto 2rem;">
      A world where every person who has a story to tell — can tell it, find their audience, and live from their work. No gatekeepers. No intermediaries. No permission required.
    </p>
    <div class="gold-line" style="margin: 2rem auto;"></div>
    <p style="font-size: 1.1rem; color: var(--gray);">
      Just as SoundCloud gave music back to artists,<br>
      just as Substack gave writing back to journalists —<br>
      <strong style="color: var(--parchment);">SHARE-PEN gives literature back to writers.</strong>
    </p>
  </div>
  <div class="slide-num">10 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 11: ASK -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-gold" id="s11">
  <div class="slide-logo">SHARE-PEN</div>
  <div class="slide-content">
    <span class="eyebrow">What We're Looking For</span>
    <h2 style="margin-bottom: 3rem;">Seed Round — <span class="gold">$2.5M</span></h2>
    <div class="two-col">
      <div>
        <h3 style="margin-bottom: 1.5rem;">Where the Money Goes:</h3>
        <ul class="problem-list solution-list" style="font-size: 0.95rem;">
          <li><strong>40%</strong> — Product development (AI, mobile, features)</li>
          <li><strong>30%</strong> — Growth & marketing (writer acquisition)</li>
          <li><strong>20%</strong> — Infrastructure & scale</li>
          <li><strong>10%</strong> — Legal, operations</li>
        </ul>
      </div>
      <div>
        <h3 style="margin-bottom: 1.5rem;">What We'll Achieve:</h3>
        <div style="display: flex; flex-direction: column; gap: 1rem;">
          <div style="display: flex; justify-content: space-between; padding: 0.8rem; background: rgba(0,0,0,0.3); border-radius: 6px;">
            <span>12 months:</span><span class="gold">50K active writers</span>
          </div>
          <div style="display: flex; justify-content: space-between; padding: 0.8rem; background: rgba(0,0,0,0.3); border-radius: 6px;">
            <span>18 months:</span><span class="gold">$3M ARR</span>
          </div>
          <div style="display: flex; justify-content: space-between; padding: 0.8rem; background: rgba(0,0,0,0.3); border-radius: 6px;">
            <span>24 months:</span><span class="gold">Series A ready</span>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="slide-num">11 / 12</div>
</section>

<!-- ═══════════════════════════════ -->
<!-- SLIDE 12: CLOSE -->
<!-- ═══════════════════════════════ -->
<section class="slide slide-dark" id="s12">
  <div class="slide-content" style="text-align: center;">
    <span class="eyebrow" style="display: block; text-align: center;">Join the Revolution</span>
    <h1 style="font-size: clamp(2rem,6vw,6rem); margin-bottom: 2rem;">
      <span class="gold">SHARE-PEN.COM</span>
    </h1>
    <div class="gold-line" style="margin: 0 auto 2rem;"></div>
    <p style="font-size: 1.3rem; max-width: 600px; margin: 0 auto 3rem; color: var(--gray);">
      "Your story. Your audience. Forever."
    </p>
    <div style="display: flex; gap: 2rem; justify-content: center; flex-wrap: wrap;">
      <div style="text-align: center;">
        <p style="font-size: 0.8rem; color: var(--gray); margin-bottom: 0.3rem;">Email</p>
        <p class="gold">hello@share-pen.com</p>
      </div>
      <div style="text-align: center;">
        <p style="font-size: 0.8rem; color: var(--gray); margin-bottom: 0.3rem;">Website</p>
        <p class="gold">share-pen.com</p>
      </div>
      <div style="text-align: center;">
        <p style="font-size: 0.8rem; color: var(--gray); margin-bottom: 0.3rem;">LinkedIn</p>
        <p class="gold">linkedin.com/company/share-pen</p>
      </div>
    </div>
  </div>
  <div class="slide-num">12 / 12</div>
</section>

<!-- NAVIGATION -->
<div class="nav-dots" id="navDots"></div>
<div class="key-hint">← → to navigate</div>

<script>
  const slides = document.querySelectorAll('.slide');
  const dotsContainer = document.getElementById('navDots');
  let current = 0;

  // Create dots
  slides.forEach((_, i) => {
    const dot = document.createElement('button');
    dot.className = 'dot' + (i === 0 ? ' active' : '');
    dot.onclick = () => goTo(i);
    dotsContainer.appendChild(dot);
  });

  function goTo(n) {
    current = Math.max(0, Math.min(n, slides.length - 1));
    slides[current].scrollIntoView({ behavior: 'smooth' });
    document.querySelectorAll('.dot').forEach((d, i) => d.classList.toggle('active', i === current));
  }

  document.addEventListener('keydown', e => {
    if (e.key === 'ArrowLeft' || e.key === 'ArrowUp') goTo(current - 1);
    if (e.key === 'ArrowRight' || e.key === 'ArrowDown') goTo(current + 1);
  });

  // Update dots on scroll
  const obs = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        const idx = Array.from(slides).indexOf(entry.target);
        current = idx;
        document.querySelectorAll('.dot').forEach((d, i) => d.classList.toggle('active', i === idx));
      }
    });
  }, { threshold: 0.6 });
  slides.forEach(s => obs.observe(s));
</script>
</body>
</html>
