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

<div class="cv-web-view">
  <h2>Education</h2>
  <div class="cv-entry">
    <div class="cv-entry-header">
      <span>PhD in Biostatistics (50%) &ndash; KU Leuven, Belgium</span>
      <span>2019&ndash;2024</span>
    </div>
    <ul>
      <li>Thesis: <em>A joint model for longitudinal outcomes and longitudinal covariates</em></li>
      <li>Supervisors: Drs. Geert Verbeke and Geert Molenberghs</li>
    </ul>
  </div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span>Master of Science in Statistics &ndash; KU Leuven, Belgium</span>
      <span>2017&ndash;2019</span>
    </div>
    <ul>
      <li>Thesis: <em>Learning Dashboard Activity as a &ldquo;Learning Trace&rdquo;</em></li>
      <li>Supervisor: Dr. Tinne De Laet</li>
    </ul>
  </div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span>Bachelor of Science in Psychology &ndash; KU Leuven, Belgium</span>
      <span>2014&ndash;2017</span>
    </div>
  </div>

  <h2>Experience</h2>
  <div class="cv-entry">
    <div class="cv-entry-header">
      <span>TT Assistant Professor in Biostatistics &ndash; University of Rhode Island, RI</span>
      <span>2026&ndash;Present</span>
    </div>
    <ul>
      <li>Department of Public Health, College of Health Sciences</li>
    </ul>
  </div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span>Postdoctoral Researcher &ndash; Weill Cornell Medicine, New York, NY</span>
      <span>2024&ndash;2026</span>
    </div>
    <ul>
      <li>Dep. Population Health Sciences, Div. Biostatistics (50%) &amp; Div. Epidemiology (50%)</li>
      <li>False discovery rate control in high-dimensional data (Dr. Yushu Shi)</li>
      <li>Cancer prevention and risk prediction in breast cancer (Dr. Rulla Tamimi)</li>
    </ul>
  </div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span>Teaching Assistant (50%) &ndash; KU Leuven, Belgium</span>
      <span>2019&ndash;2024</span>
    </div>
    <ul>
      <li>Taught six undergraduate and graduate courses in biostatistics for 400+ students</li>
      <li>Supervised two graduate students in Statistics</li>
      <li>Delivered statistical consulting to medical researchers</li>
    </ul>
  </div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span>Data Science Intern &ndash; De Persgroep-Medialaan, Brussels, Belgium</span>
      <span>2019</span>
    </div>
    <ul>
      <li>Personalized the newsfeed using machine learning techniques</li>
    </ul>
  </div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span>Junior Statistician &ndash; Leuven Statistics Research Centre, KU Leuven</span>
      <span>2018&ndash;2019</span>
    </div>
    <ul>
      <li>Provided consultancy and taught short courses for researchers</li>
    </ul>
  </div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span>Data Science Intern &ndash; Vente-Exclusive, Brussels, Belgium</span>
      <span>2018</span>
    </div>
    <ul>
      <li>Created an automatically updating dashboard with metrics to track flash sales</li>
    </ul>
  </div>

  <h2>Skills</h2>
  <p><strong>Statistics:</strong> Longitudinal data, multivariate data, high-dimensional data, survival analysis, HPC<br>
  <strong>Software:</strong> R, SAS, Python, SPSS, Stata, SQL, GitHub<br>
  <strong>Languages:</strong> Dutch (native), English (fluent), French (intermediate)</p>
</div>
