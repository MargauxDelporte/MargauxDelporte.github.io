---
layout: page
title: "CV"
---
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-P52QC73R53"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-P52QC73R53');
</script>

<p style="margin-bottom: 1.5em;" class="more">
  <a href="{{ '/CV2.pdf?v=20260926' | relative_url }}" target="_blank">Open / Download CV (PDF)</a>
</p>

<div class="pdf-container">
  <iframe
    src="{{ '/CV2.pdf?v=20260926' | relative_url }}"
    title="Curriculum vitae"
    loading="eager">
  </iframe>
</div>

<style>
  .pdf-container {
    width: 100%;
    height: min(85vh, 1000px);
    min-height: 640px;
    border: 1px solid #ddd;
    overflow: hidden;
    margin-bottom: 2em;
  }

  .pdf-container iframe {
    display: block;
    width: 100%;
    height: 100%;
    border: 0;
  }

  @media (max-width: 700px) {
    .pdf-container {
      height: 75vh;
      min-height: 520px;
    }
  }

  .cv-web-view {
    margin-top: 2em;
    padding-top: 1em;
    border-top: 1px solid #eee;
  }
  .cv-web-view h2 {
    font-size: 1.25em;
    margin-top: 1.5em;
    border-bottom: 1px solid #ddd;
    padding-bottom: 0.2em;
  }
  .cv-web-view h3 {
    font-size: 1.05em;
    margin-top: 1em;
  }
  .cv-entry-header {
    display: flex;
    justify-content: space-between;
    font-weight: bold;
  }
  .cv-entry-sub {
    font-style: italic;
    color: #555;
  }
</style>


