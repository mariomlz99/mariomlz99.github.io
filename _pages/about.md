---
layout: about
permalink: /
# Rimuovendo 'title: about' qui, eliminiamo il duplicato generato dal tema
profile:
  align: right
  image: mario_face.png
  image_circular: true 
social: false
---

<style>
  /* 1. Nasconde la navbar (linea superiore e menu) */
  nav.navbar { 
    display: none !important; 
  }

  /* 2. Nasconde il titolo automatico generato dal tema (il duplicato) */
  header.post-header h1.post-title {
    display: none !important;
  }

  /* 3. Riduce lo spazio superiore per far iniziare il sito dall'alto */
  body { 
    padding-top: 10px !important; 
  }
  .post {
    padding-top: 0 !important;
  }

  /* 4. Stile icone social colorate */
  .header-social-icons a {
    margin-left: 12px;
    font-size: 0.7em;
    vertical-align: middle;
    transition: opacity 0.3s;
  }
  .header-social-icons a:hover { opacity: 0.7; }

  /* Classi per i colori originali */
  .social-email { color: #444 !important; }
  .social-linkedin { color: #0077b5 !important; }
  .social-scholar { color: #4285f4 !important; }
  .social-rg { color: #00ccbb !important; }
  .social-github { color: #333 !important; }
  .social-orcid { color: #a6ce39 !important; }

  /* Shared layout for publications and workshop papers. */
  .research-list {
    display: grid;
    gap: 24px;
    margin-top: 20px;
    clear: both;
  }
  .research-card {
    display: grid;
    grid-template-columns: minmax(0, 180px) minmax(0, 1fr);
    align-items: center;
    gap: 24px;
    padding: 20px;
    border: 1px solid var(--global-divider-color, #ddd);
    border-radius: 8px;
  }
  .research-preview {
    text-align: center;
  }
  .research-preview img {
    width: 100%;
    max-width: 180px;
    max-height: 160px;
    height: auto;
    object-fit: contain;
    border-radius: 4px;
  }
  .research-content {
    min-width: 0;
    overflow-wrap: anywhere;
  }
  .research-title {
    margin: 0 0 6px;
    font-size: 1.1rem;
    font-weight: 700;
    line-height: 1.4;
  }
  .research-year {
    white-space: nowrap;
  }
  .research-authors {
    margin: 0 0 8px;
    font-style: italic;
    line-height: 1.5;
  }
  .research-venue {
    margin: 0 0 8px;
    line-height: 1.5;
  }
  .research-badges,
  .research-links {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 6px;
  }
  .research-badge {
    padding: 4px 9px;
    border-radius: 4px;
    font-size: 0.75rem;
    font-weight: 600;
    line-height: 1.4;
  }
  .research-badge--conference { background: #eaf2ff; color: #2459a6; }
  .research-badge--journal { background: #e7f5eb; color: #256d3b; }
  .research-badge--workshop { background: #f1edff; color: #6745a5; }
  .research-badge--presentation { background: #fff0d8; color: #754800; }
  .research-badge--status { background: #f0f0f0; color: #555; }
  .research-links {
    margin-top: 12px;
    gap: 8px;
  }
  .research-link {
    display: inline-flex;
    align-items: center;
    padding: 6px 12px;
    border: 1px solid currentColor;
    border-radius: 4px;
    font-size: 0.8rem;
    font-weight: 500;
    line-height: 1.5;
  }
  .research-link--paper { color: var(--global-theme-color, #2459a6); }
  .research-link--repository { color: var(--global-text-color, #333); }
  .research-link--pending {
    color: var(--global-text-color-light, #666);
    border-style: dashed;
  }
  a.research-link:hover { text-decoration: underline; }
  a.research-link:focus-visible {
    outline: 2px solid var(--global-theme-color, #2459a6);
    outline-offset: 3px;
  }
  @media (max-width: 575px) {
    .research-card {
      grid-template-columns: minmax(0, 1fr);
      gap: 16px;
      padding: 16px;
    }
  }
</style>

# Mario Malizia <span class="header-social-icons" style="display: inline-flex; align-items: center;"> <a href="mailto:mario.malizia@mil.be" title="Email" class="social-email"><i class="fas fa-envelope"></i></a> <a href="https://www.linkedin.com/in/mario-malizia" target="_blank" title="LinkedIn" class="social-linkedin"><i class="fab fa-linkedin"></i></a> <a href="https://scholar.google.com/citations?user=3fDazuEAAAAJ" target="_blank" title="Google Scholar" class="social-scholar"><i class="ai ai-google-scholar"></i></a> <a href="https://www.researchgate.net/profile/Mario-Malizia" target="_blank" title="ResearchGate" class="social-rg"><i class="ai ai-researchgate"></i></a> <a href="https://github.com/mariomlz99" target="_blank" title="GitHub" class="social-github"><i class="fab fa-github"></i></a> <a href="https://orcid.org/0009-0008-6618-5059" target="_blank" title="ORCID" class="social-orcid"><i class="ai ai-orcid"></i></a></span>

* I grew up in **Cosenza**, Italy, a beautiful city in the sunny South of Italy.
* I later moved to **Milan** where I pursued my BSc and MSc studies in **Automation and Control Engineering** at [Politecnico di Milano](https://www.polimi.it/en).
* After my MSc, I worked as a **Research Assistant** at the Politecnico di Milano [mOve Group](https://move.deib.polimi.it/), focusing on simulations and perception for autonomous driving applications in on-road and off-road environments.
* I am currently a **Research Engineer** at the [Royal Military Academy](https://www.rma.ac.be/en) (RMA) of Belgium, focusing on autonomous robotics applications within the [Robotics and Autonomous Systems Group](https://mecatron.rma.ac.be/).
* In parallel, I have started a **joint PhD** with the [KU Leuven](https://www.kuleuven.be/english/) [ACRO](https://iiw.kuleuven.be/onderzoek/acro) research group, supervised by Prof. Eric Demeester and Prof. Nikolaos Tsiogkas on the KUL side and Prof. Rob Haelterman and Dr. Ken Hasselmann on the RMA side.

---

### Research Interests

<div class="projects" style="line-height: 2.5em; margin-top: 20px;">
  <span class="badge grey" style="border: 1px solid #ddd; padding: 8px 12px; background-color: #f5f5f5; border-radius: 5px;">Autonomous Robotics</span>
  <span class="badge grey" style="border: 1px solid #ddd; padding: 8px 12px; background-color: #f5f5f5; border-radius: 5px;">Field Robotics</span>
  <span class="badge grey" style="border: 1px solid #ddd; padding: 8px 12px; background-color: #f5f5f5; border-radius: 5px;">Off-road Perception</span>
  <br>
  <span class="badge grey" style="border: 1px solid #ddd; padding: 8px 12px; background-color: #f5f5f5; border-radius: 5px;">Landmine Detection</span>
  <span class="badge grey" style="border: 1px solid #ddd; padding: 8px 12px; background-color: #f5f5f5; border-radius: 5px;">Occluded Object Detection</span>
  <span class="badge grey" style="border: 1px solid #ddd; padding: 8px 12px; background-color: #f5f5f5; border-radius: 5px;">Synthetic Data</span>
</div>

---
### Publications & Workshops

<div class="research-list">
{% for entry in site.data.research %}
  {% include research-card.liquid entry=entry %}
{% endfor %}
</div>
