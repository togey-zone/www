---
layout: home
title: TOGEY Zone · Main Portal
---

<section class="tg-hero" aria-labelledby="hero-title">
  <div class="tg-kicker">TOGEY ZONE · 桃吉主站</div>
  <h1 id="hero-title">把独处做成一种有秩序的生活方式。</h1>
  <p class="tg-lead">
    TOGEY LIMITED is shaping a compact brand system for cross-border commerce,
    digital products, and everyday tools — designed in Hong Kong, built for people
    who prefer clarity, independence, and long-term value.
  </p>
  <p class="tg-lead tg-lead-zh">
    桃吉有限公司正在整理一套更清楚的品牌主站：把跨境经营、数字产品与日常工具收束到同一张地图里，
    让外部伙伴、用户和团队都能一眼看懂我们在做什么、下一步去哪。
  </p>
  <div class="tg-actions" aria-label="Primary actions">
    <a class="tg-button tg-button-primary" href="mailto:contact@togey.com">Start a conversation</a>
    <a class="tg-button" href="#roadmap">View rebuild roadmap</a>
  </div>
</section>

<section class="tg-section tg-snapshot" aria-labelledby="snapshot-title">
  <div>
    <p class="tg-eyebrow">Current position · 当前定位</p>
    <h2 id="snapshot-title">A calmer front door for the TOGEY ecosystem.</h2>
  </div>
  <div class="tg-copy">
    <p>
      This page is the public foyer for TOGEY: not a temporary name card, but a
      lightweight map that explains the company, the domain matrix, and the near-term
      direction before the full product sites are separated and launched.
    </p>
    <p>
      主站先承担“门面 + 总导航 + 路线说明”的职责：不要堆概念，也不急着把所有项目一次讲完；
      先把可信度、气质和入口整理好，再逐步把各条业务线独立成站。
    </p>
  </div>
</section>

<section class="tg-section" aria-labelledby="principles-title">
  <p class="tg-eyebrow">Operating principles · 做事原则</p>
  <h2 id="principles-title">Less noise, more useful structure.</h2>
  <div class="tg-principles">
    <article>
      <span>01</span>
      <h3>Clear identity</h3>
      <p>Keep TOGEY as the holding identity and use subdomains or sister domains for products, labs, and regional operations.</p>
    </article>
    <article>
      <span>02</span>
      <h3>Practical commerce</h3>
      <p>Focus on cross-border product selection, brand operations, and service flows that can be measured and repeated.</p>
    </article>
    <article>
      <span>03</span>
      <h3>Small useful tools</h3>
      <p>Ship digital products that reduce friction in daily life rather than chasing loud, short-lived launches.</p>
    </article>
  </div>
</section>

<section class="tg-section" aria-labelledby="matrix-title">
  <p class="tg-eyebrow">Domain matrix · 品牌矩阵</p>
  <h2 id="matrix-title">One company, several purposeful doors.</h2>
  <div class="domain-grid">
    {% include domain-card.html title_en=site.data.domains.core_operations.title_en title_zh=site.data.domains.core_operations.title_zh domains=site.data.domains.core_operations.domains %}
    {% include domain-card.html title_en=site.data.domains.digital_products.title_en title_zh=site.data.domains.digital_products.title_zh domains=site.data.domains.digital_products.domains %}
    {% include domain-card.html title_en=site.data.domains.innovation_labs.title_en title_zh=site.data.domains.innovation_labs.title_zh domains=site.data.domains.innovation_labs.domains %}
  </div>
</section>

<section class="tg-section tg-roadmap" id="roadmap" aria-labelledby="roadmap-title">
  <p class="tg-eyebrow">Rebuild roadmap · 主站改造规划</p>
  <h2 id="roadmap-title">From “temporary facade” to a site that can meet people.</h2>
  <div class="tg-roadmap-grid">
    <article>
      <strong>Phase 1 · Now</strong>
      <h3>Make the doorway credible</h3>
      <p>Refresh tone, information hierarchy, domain map, and contact path so the site no longer feels like a placeholder.</p>
    </article>
    <article>
      <strong>Phase 2 · Content system</strong>
      <h3>Separate story from navigation</h3>
      <p>Add concise pages for company profile, product lines, operating regions, and collaboration notes.</p>
    </article>
    <article>
      <strong>Phase 3 · Product surfaces</strong>
      <h3>Launch focused sub-sites</h3>
      <p>Move each serious project into its own domain or subdomain, with the main portal acting as the verified index.</p>
    </article>
  </div>
</section>

<section class="tg-section tg-contact" aria-labelledby="contact-title">
  <p class="tg-eyebrow">Contact · 联系方式</p>
  <h2 id="contact-title">For partnerships, product conversations, and quiet useful things.</h2>
  <p><strong>TOGEY LIMITED</strong> · 桃吉有限公司</p>
  <p><a href="mailto:contact@togey.com">contact@togey.com</a> · Hong Kong SAR</p>
</section>

<footer class="tg-footer">
  <p>© 2026 TOGEY LIMITED. All rights reserved.</p>
  <nav aria-label="Footer links">
    <a href="https://togey.com">togey.com</a>
    <a href="https://togey.org">togey.org</a>
    <a href="https://togey.link">togey.link</a>
  </nav>
</footer>

<style>
:root {
  --tg-ink: #101313;
  --tg-muted: #66706f;
  --tg-line: #dde4df;
  --tg-paper: #fbfaf6;
  --tg-card: #ffffff;
  --tg-moss: #16423c;
  --tg-gold: #d88b18;
}

body {
  background:
    radial-gradient(circle at top left, rgba(216, 139, 24, 0.12), transparent 30rem),
    linear-gradient(180deg, #fffdf8 0%, #f7f8f3 100%);
  color: var(--tg-ink);
  font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  line-height: 1.7;
}

.post-header { display: none; }
.post-content { margin-bottom: 0; }
.wrapper { max-width: 1120px; }

h1, h2, h3, h4, p { margin-top: 0; }
h1, h2, h3, h4 { letter-spacing: -0.04em; line-height: 1.08; }
a { color: var(--tg-moss); text-decoration-thickness: 1px; text-underline-offset: 0.2em; }
a:hover { color: var(--tg-gold); }

.tg-hero {
  min-height: 62vh;
  display: grid;
  align-content: center;
  padding: 7rem 0 5rem;
  border-bottom: 1px solid var(--tg-line);
}

.tg-kicker, .tg-eyebrow {
  color: var(--tg-gold);
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.16em;
  text-transform: uppercase;
}

.tg-hero h1 {
  max-width: 920px;
  margin: 1.1rem 0 1.5rem;
  font-size: clamp(3rem, 9vw, 6.8rem);
}

.tg-lead {
  max-width: 800px;
  color: var(--tg-muted);
  font-size: clamp(1.05rem, 2vw, 1.35rem);
}

.tg-lead-zh { max-width: 760px; }
.tg-actions { display: flex; flex-wrap: wrap; gap: 0.9rem; margin-top: 2rem; }
.tg-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 2.9rem;
  padding: 0 1.2rem;
  border: 1px solid var(--tg-line);
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.72);
  color: var(--tg-ink);
  font-weight: 700;
  text-decoration: none;
}
.tg-button-primary { background: var(--tg-moss); border-color: var(--tg-moss); color: #fff; }
.tg-button-primary:hover { color: #fff; background: #0f312c; }

.tg-section { padding: 5rem 0; border-bottom: 1px solid var(--tg-line); }
.tg-section h2 { max-width: 780px; margin: 0.7rem 0 1.8rem; font-size: clamp(2rem, 5vw, 4rem); }
.tg-snapshot { display: grid; grid-template-columns: minmax(0, 0.9fr) minmax(18rem, 1fr); gap: 3rem; }
.tg-copy { color: var(--tg-muted); font-size: 1.05rem; }

.tg-principles, .domain-grid, .tg-roadmap-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}

.tg-principles article, .domain-card, .tg-roadmap article {
  min-height: 14rem;
  padding: 1.35rem;
  border: 1px solid rgba(22, 66, 60, 0.14);
  border-radius: 1.4rem;
  background: rgba(255, 255, 255, 0.68);
  box-shadow: 0 1.2rem 3rem rgba(16, 19, 19, 0.04);
}

.tg-principles span, .tg-roadmap strong {
  color: var(--tg-gold);
  font-size: 0.78rem;
  font-weight: 800;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.tg-principles h3, .tg-roadmap h3, .domain-card h4 { margin: 1rem 0 0.7rem; font-size: 1.35rem; }
.tg-principles p, .tg-roadmap p, .domain-card p, .domain-list { color: var(--tg-muted); }

.domain-list { list-style: none; margin: 1rem 0 0; padding: 0; }
.domain-item {
  display: grid;
  gap: 0.15rem;
  padding: 0.75rem 0;
  border-top: 1px solid rgba(22, 66, 60, 0.1);
}
.domain-url { color: var(--tg-ink); font-weight: 800; }
.domain-desc { font-size: 0.92rem; }
.domain-development .domain-url::after, .domain-planned .domain-url::after {
  margin-left: 0.5rem;
  color: var(--tg-gold);
  font-size: 0.72rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}
.domain-development .domain-url::after { content: "Building"; }
.domain-planned .domain-url::after { content: "Planned"; }

.tg-contact {
  text-align: center;
  border-bottom: 0;
}
.tg-contact h2 { margin-left: auto; margin-right: auto; }
.tg-footer {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
  padding: 2rem 0 3rem;
  color: var(--tg-muted);
  font-size: 0.92rem;
}
.tg-footer nav { display: flex; flex-wrap: wrap; gap: 1rem; }

@media (max-width: 820px) {
  .tg-hero { min-height: auto; padding: 4rem 0; }
  .tg-snapshot, .tg-principles, .domain-grid, .tg-roadmap-grid { grid-template-columns: 1fr; }
  .tg-section { padding: 3.5rem 0; }
  .tg-principles article, .domain-card, .tg-roadmap article { min-height: auto; }
}
</style>
