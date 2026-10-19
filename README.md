<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shehwar Sajid | Senior Content Strategist, Writer & AI Operations Specialist</title>
  <meta name="description" content="6+ years of experience in B2B e-commerce, SEO content strategy, editorial leadership, regulatory legal tracking, and AI workflow engineering.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=Space+Grotesk:wght@600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-page: #F8FAFC;
      --bg-surface: #FFFFFF;
      --border-light: #E2E8F0;
      --border-accent: #C7D2FE;
      --text-heading: #0F172A;
      --text-body: #334155;
      --text-muted: #64748B;
      --primary: #4338CA;
      --primary-hover: #3730A3;
      --primary-light: #EEF2FF;
      --accent-green: #059669;
      --font-heading: 'Space Grotesk', sans-serif;
      --font-body: 'Plus Jakarta Sans', sans-serif;
    }

    * { margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth; }

    body {
      background-color: var(--bg-page);
      color: var(--text-body);
      font-family: var(--font-body);
      line-height: 1.6;
      -webkit-font-smoothing: antialiased;
    }

    .container { max-width: 1140px; margin: 0 auto; padding: 0 24px; }

    header {
      background: rgba(255, 255, 255, 0.95);
      backdrop-filter: blur(10px);
      border-bottom: 1px solid var(--border-light);
      position: sticky;
      top: 0;
      z-index: 100;
      padding: 18px 0;
    }

    .nav-wrapper { display: flex; justify-content: space-between; align-items: center; }

    .logo {
      font-family: var(--font-heading);
      font-size: 1.35rem;
      font-weight: 700;
      color: var(--text-heading);
      text-decoration: none;
    }

    .logo span { color: var(--primary); }

    nav { display: flex; gap: 28px; }

    nav a {
      color: var(--text-muted);
      text-decoration: none;
      font-weight: 600;
      font-size: 0.95rem;
      transition: color 0.2s;
    }

    nav a:hover { color: var(--primary); }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 12px 24px;
      border-radius: 8px;
      font-weight: 700;
      font-size: 0.95rem;
      text-decoration: none;
      transition: all 0.2s ease;
      cursor: pointer;
      border: none;
    }

    .btn-primary {
      background-color: var(--primary);
      color: #FFFFFF;
      box-shadow: 0 4px 12px rgba(67, 56, 202, 0.2);
    }

    .btn-primary:hover {
      background-color: var(--primary-hover);
      transform: translateY(-1px);
    }

    .btn-outline {
      background-color: var(--bg-surface);
      color: var(--text-heading);
      border: 1px solid var(--border-light);
    }

    .btn-outline:hover {
      border-color: var(--primary);
      color: var(--primary);
      background-color: var(--primary-light);
    }

    .hero { padding: 70px 0 50px; }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 6px 14px;
      background: #ECFDF5;
      border: 1px solid #A7F3D0;
      color: var(--accent-green);
      border-radius: 20px;
      font-size: 0.85rem;
      font-weight: 700;
      margin-bottom: 24px;
    }

    .badge-dot {
      width: 8px;
      height: 8px;
      background-color: var(--accent-green);
      border-radius: 50%;
    }

    .hero h1 {
      font-family: var(--font-heading);
      font-size: 3.1rem;
      line-height: 1.2;
      color: var(--text-heading);
      margin-bottom: 20px;
      letter-spacing: -0.02em;
    }

    .hero h1 span { color: var(--primary); }

    .hero-subtitle {
      font-size: 1.15rem;
      color: var(--text-body);
      max-width: 780px;
      margin-bottom: 32px;
    }

    .hero-cta { display: flex; gap: 16px; flex-wrap: wrap; }

    .metrics-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 48px;
    }

    .metric-card {
      background: var(--bg-surface);
      border: 1px solid var(--border-light);
      padding: 24px;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.02);
    }

    .metric-card h3 {
      font-family: var(--font-heading);
      font-size: 2.2rem;
      color: var(--primary);
      margin-bottom: 4px;
    }

    .metric-card p {
      color: var(--text-muted);
      font-size: 0.88rem;
      font-weight: 600;
      line-height: 1.4;
    }

    section { padding: 64px 0; border-top: 1px solid var(--border-light); }

    .section-header { margin-bottom: 36px; }

    .section-title {
      font-family: var(--font-heading);
      font-size: 2.1rem;
      color: var(--text-heading);
      margin-bottom: 8px;
    }

    .section-desc { color: var(--text-muted); font-size: 1.05rem; }

    .about-card {
      background: var(--bg-surface);
      border: 1px solid var(--border-light);
      border-radius: 16px;
      padding: 36px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.02);
    }

    .about-card p { margin-bottom: 16px; font-size: 1.05rem; line-height: 1.7; }

    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 24px;
    }

    .service-card {
      background: var(--bg-surface);
      border: 1px solid var(--border-light);
      border-radius: 12px;
      padding: 32px;
      transition: all 0.2s ease;
    }

    .service-card:hover {
      border-color: var(--primary);
      box-shadow: 0 8px 24px rgba(67, 56, 202, 0.08);
      transform: translateY(-2px);
    }

    .service-icon {
      font-size: 2rem;
      margin-bottom: 16px;
    }

    .service-card h3 {
      font-family: var(--font-heading);
      font-size: 1.25rem;
      color: var(--text-heading);
      margin-bottom: 12px;
    }

    .project-block {
      background: var(--bg-surface);
      border: 1px solid var(--border-light);
      border-radius: 16px;
      padding: 32px;
      margin-bottom: 32px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.02);
    }

    .project-badge {
      display: inline-block;
      font-size: 0.75rem;
      font-weight: 800;
      text-transform: uppercase;
      letter-spacing: 0.05em;
      color: var(--primary);
      background: var(--primary-light);
      padding: 4px 12px;
      border-radius: 20px;
      margin-bottom: 12px;
    }

    .project-header h3 {
      font-family: var(--font-heading);
      font-size: 1.5rem;
      color: var(--text-heading);
      margin-bottom: 6px;
    }

    .project-header p {
      color: var(--text-muted);
      font-size: 0.95rem;
      margin-bottom: 24px;
    }

    .deliverables-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 20px;
    }

    .deliverable-card {
      background: var(--bg-page);
      border: 1px solid var(--border-light);
      border-radius: 10px;
      padding: 20px;
    }

    .deliverable-card h4 {
      font-family: var(--font-heading);
      font-size: 0.98rem;
      color: var(--text-heading);
      margin-bottom: 12px;
      border-bottom: 2px solid var(--border-accent);
      padding-bottom: 6px;
    }

    .deliverable-card ul {
      list-style: none;
      padding: 0;
    }

    .deliverable-card li {
      font-size: 0.88rem;
      color: var(--text-body);
      margin-bottom: 10px;
      line-height: 1.4;
      display: flex;
      align-items: flex-start;
      gap: 6px;
    }

    .deliverable-card li::before {
      content: "•";
      color: var(--primary);
      font-weight: bold;
    }

    .deliverable-card a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 600;
    }

    .deliverable-card a:hover { text-decoration: underline; }

    .ai-box {
      background: var(--primary-light);
      border: 1px solid var(--border-accent);
      border-radius: 16px;
      padding: 36px;
    }

    .ai-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 24px;
    }

    .ai-item {
      background: var(--bg-surface);
      border: 1px solid var(--border-light);
      padding: 24px;
      border-radius: 12px;
    }

    .ai-item h4 {
      font-family: var(--font-heading);
      color: var(--text-heading);
      margin-bottom: 8px;
      font-size: 1.1rem;
    }

    footer {
      padding: 40px 0;
      text-align: center;
      color: var(--text-muted);
      font-size: 0.9rem;
      border-top: 1px solid var(--border-light);
    }

    .toast {
      position: fixed;
      bottom: 24px;
      right: 24px;
      background: var(--text-heading);
      color: #FFFFFF;
      padding: 12px 24px;
      border-radius: 8px;
      font-weight: 700;
      display: none;
      z-index: 1000;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    }

    @media (max-width: 768px) {
      .hero h1 { font-size: 2.25rem; }
      nav { display: none; }
      .deliverables-grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

  <header>
    <div class="container nav-wrapper">
      <a href="#" class="logo">Shehwar<span>.</span>Sajid</a>
      <nav>
        <a href="#about">About</a>
        <a href="#capabilities">Capabilities</a>
        <a href="#portfolio">Projects</a>
        <a href="#ai-operations">AI Operations</a>
      </nav>
      <a href="mailto:shehwarsajid81@gmail.com" class="btn btn-outline">Let's Connect</a>
    </div>
  </header>

  <main class="container">

    <!-- Hero Section -->
    <section class="hero" style="border-top: none;">
      <div class="badge">
        <span class="badge-dot"></span>
        Available for Strategic Roles & Content Operations
      </div>
      <h1>Senior Content Strategist, Writer & <span>AI Operations</span> Specialist</h1>
      <p class="hero-subtitle">
        6+ years of experience turning complex topics into search-authoritative content engines. Bridging search intent (E-E-A-T) with custom LLM prompt architectures to accelerate editorial operations across B2B, RegTech, and E-Commerce.
      </p>
      <div class="hero-cta">
        <a href="#portfolio" class="btn btn-primary">Explore Featured Projects ↗</a>
        <button onclick="copyEmail()" class="btn btn-outline">📋 Copy Email Address</button>
      </div>

      <!-- Verified Metric Highlights -->
      <div class="metrics-grid">
        <div class="metric-card">
          <h3>6+ Years</h3>
          <p>Editorial Leadership & Content Strategy</p>
        </div>
        <div class="metric-card">
          <h3>3,500+</h3>
          <p>Catalog Descriptions Across 150+ Niches</p>
        </div>
        <div class="metric-card">
          <h3>70% Faster</h3>
          <p>Production Efficiency via Trained AI Agents</p>
        </div>
        <div class="metric-card">
          <h3>200+</h3>
          <p>Trainee Articles Governed & Mentored</p>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about">
      <div class="section-header">
        <h2 class="section-title">Strategic Approach</h2>
        <p class="section-desc">Connecting search intent, editorial governance, and modern AI automation.</p>
      </div>
      <div class="about-card">
        <p>
          I specialize in building sustainable organic search visibility across B2B marketplaces, supply chain logistics, e-commerce platforms, and regulatory compliance sectors. High-performing content isn't just about keyword output—it is about answering target user intent while fulfilling strict Google E-E-A-T standards.
        </p>
        <p>
          By pairing manual editorial standards (style guides, grading policies) with trained ChatGPT and Claude prompt workflows, I help brand teams scale publication output without losing human nuances or factual integrity.
        </p>
      </div>
    </section>

    <!-- Capabilities Section -->
    <section id="capabilities">
      <div class="section-header">
        <h2 class="section-title">Core Capabilities</h2>
        <p class="section-desc">End-to-end editorial management, technical writing, and automated workflows.</p>
      </div>

      <div class="services-grid">
        <div class="service-card">
          <div class="service-icon">🔍</div>
          <h3>Content Strategy & SEO</h3>
          <p>Topical authority maps, keyword clustering, competitor gap analysis, and search intent alignment built to drive domain rank.</p>
        </div>

        <div class="service-card">
          <div class="service-icon">🤖</div>
          <h3>AI Workflow Operations</h3>
          <p>Engineering customized prompt frameworks for ChatGPT & Claude to automate metadata, product descriptions, and first-pass editing.</p>
        </div>

        <div class="service-card">
          <div class="service-icon">✍️</div>
          <h3>B2B & Technical Writing</h3>
          <p>In-depth technical guides across wholesale e-commerce, inventory logistics, US regulatory legal tracking, and software PRDs.</p>
        </div>
      </div>
    </section>

    <!-- Brand-by-Brand Portfolio Section -->
    <section id="portfolio">
      <div class="section-header">
        <h2 class="section-title">Featured Projects & Deliverables</h2>
        <p class="section-desc">A brand-by-brand showcase of content strategy, SEO writing, E-commerce copywriting, and technical documentation.</p>
      </div>

      <!-- Project 1: SeeBiz Marketplace -->
      <div class="project-block">
        <div class="project-header">
          <span class="project-badge">B2B & Wholesale E-Commerce</span>
          <h3>SeeBiz Marketplace</h3>
          <p>End-to-end editorial writing, category architecture across 11 industries & 150+ niches, vendor profile creation, and social strategy.</p>
        </div>

        <div class="deliverables-grid">
          <div class="deliverable-card">
            <h4>Onsite SEO Blogs</h4>
            <ul>
              <li><a href="https://www.seebiz.com/blog/why-do-wholesalers-need-an-automated-inventory-system/" target="_blank">Why Do Wholesalers Need an Automated Inventory System? ↗</a></li>
              <li><a href="https://www.seebiz.com/blog/distributors/" target="_blank">What Are Distributors and Their Role in the Supply Chain ↗</a></li>
              <li><a href="https://www.seebiz.com/blog/wholesale-inventory-management-everything-that-you-should-know/" target="_blank">Wholesale Inventory Management: Complete Guide ↗</a></li>
              <li><a href="https://www.seebiz.com/blog/procurement-and-supply-chain-management/" target="_blank">How Procurement and Supply Chain Management Are Related ↗</a></li>
            </ul>
          </div>

          <div class="deliverable-card">
            <h4>Vendor Profiles</h4>
            <ul>
              <li>Don John by Victoria Charles</li>
              <li>Herbal Connections</li>
              <li>Closeoutsareus</li>
              <li>JHP-Collection</li>
            </ul>
          </div>

          <div class="deliverable-card">
            <h4>Category Copywriting</h4>
            <ul>
              <li>Halloween Costumes</li>
              <li>Kids' Clothing</li>
              <li>Corsets Collection</li>
              <li>Purses & Handbags</li>
            </ul>
          </div>

          <div class="deliverable-card">
            <h4>Social Media Strategy</h4>
            <ul>
              <li>LinkedIn: SeeBiz Inc.</li>
              <li>Instagram: SeeBiz US</li>
              <li>X (Twitter): SeeBiz</li>
              <li>Facebook: SeeBiz Inc.</li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Project 2: Klarity Kratom -->
      <div class="project-block">
        <div class="project-header">
          <span class="project-badge">Regulatory & Botanical E-Commerce</span>
          <h3>Klarity Kratom</h3>
          <p>Technical writing, homepage messaging, educational learning hub creation, and US state-by-state regulatory legal tracking.</p>
        </div>

        <div class="deliverables-grid">
          <div class="deliverable-card">
            <h4>Web Copy & Hubs</h4>
            <ul>
              <li>Homepage Copywriting & Brand Messaging</li>
              <li>Kratom Educational Learning Centre Guide</li>
            </ul>
          </div>

          <div class="deliverable-card">
            <h4>In-Depth Technical Blogs</h4>
            <ul>
              <li><a href="https://klaritykratom.com/blog/kratom-strains/understanding-kratom-batches/" target="_blank">Why Do Batches Vary? Alkaloids & Natural Variation ↗</a></li>
              <li><a href="https://klaritykratom.com/blog/kratom-news/current-state-of-kratom-legality-in-us/" target="_blank">State of Kratom Legality in US: Regulatory Guide ↗</a></li>
              <li>A Day in the Life of Klarity Kratom — From Website to Door</li>
              <li>Kratom Usage Statistics & Industry Data</li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Project 3: Turnfeat AI -->
      <div class="project-block">
        <div class="project-header">
          <span class="project-badge">AI & Software Documentation</span>
          <h3>Turnfeat AI</h3>
          <p>Technical product requirements documentation and software framework guides.</p>
        </div>

        <div class="deliverables-grid">
          <div class="deliverable-card">
            <h4>Technical Documentation</h4>
            <ul>
              <li>Product Requirements Document (PRD): A Guide with Turnfeat</li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Project 4: Amazon & E-Commerce -->
      <div class="project-block">
        <div class="project-header">
          <span class="project-badge">Amazon Listing Copywriting</span>
          <h3>Herviva (Herbal Supplements)</h3>
          <p>SEO-optimized product titles, feature bullet points, and catalog descriptions.</p>
        </div>

        <div class="deliverables-grid">
          <div class="deliverable-card">
            <h4>Amazon Listings</h4>
            <ul>
              <li>Multiple Herbal Supplement Amazon Product Listings</li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Project 5: Qalam IT -->
      <div class="project-block">
        <div class="project-header">
          <span class="project-badge">EdTech & Social Strategy</span>
          <h3>Qalam IT</h3>
          <p>Multi-channel social campaigns and educational content strategy.</p>
        </div>

        <div class="deliverables-grid">
          <div class="deliverable-card">
            <h4>Social Media Channels</h4>
            <ul>
              <li>LinkedIn: Qalam IT</li>
              <li>Instagram: Qalam IT</li>
              <li>Facebook: Qalam Training Programs</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- AI Operations Section -->
    <section id="ai-operations">
      <div class="ai-box">
        <div class="section-header" style="margin-bottom: 20px;">
          <h2 class="section-title">🤖 AI Operations & Prompt Engineering</h2>
          <p class="section-desc">Automating content workflows without sacrificing human tone or editorial quality.</p>
        </div>

        <div class="ai-grid">
          <div class="ai-item">
            <h4>⚡ 1,100-Word Product Description Engines</h4>
            <p>Trained prompt structures for ChatGPT agents covering every product aspect, cutting total drafting time by 70%.</p>
          </div>
          <div class="ai-item">
            <h4>🔍 Automated Metadata & Outline Pipelines</h4>
            <p>Built system prompts configured to auto-generate SEO meta descriptions, titles, and comprehensive blog outlines at scale.</p>
          </div>
          <div class="ai-item">
            <h4>✍️ First-Pass Editorial Models</h4>
            <p>Configured system prompts enforcing style guides, readability rules, and brand consistency for rapid first-pass copy editing.</p>
          </div>
        </div>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <p>© 2026 Shehwar Sajid. Built with GitHub Pages.</p>
    </div>
  </footer>

  <div id="toast" class="toast">Email address copied to clipboard!</div>

  <script>
    function copyEmail() {
      navigator.clipboard.writeText('shehwarsajid81@gmail.com');
      const toast = document.getElementById('toast');
      toast.style.display = 'block';
      setTimeout(() => { toast.style.display = 'none'; }, 2500);
    }
  </script>
</body>
</html>
