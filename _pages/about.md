---
layout: about
permalink: /
# Rimuovendo 'title: about' qui, eliminiamo il duplicato generato dal tema
profile:
  align: right
  image: mario_auh.jpg
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

  /* 5. Layout pubblicazioni fisso orizzontale */
  .pub-row {
    display: flex !important;
    flex-direction: row !important;
    align-items: center !important;
    flex-wrap: nowrap !important;
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
### Publications

<div class="publications">
  
  <div class="row pub-row" style="margin-bottom: 25px; border: 1px solid #ddd; padding: 20px; border-radius: 8px;">
    <div class="col-sm-3" style="flex: 0 0 25%; max-width: 25%; text-align: center;">
      <img src="assets/img/publication_preview/2025_ral_thumbnail.png" style="width: 100%; max-width: 180px; border-radius: 4px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);" alt="thumbnail">
    </div>
    <div class="col-sm-9" style="flex: 0 0 75%; max-width: 75%; padding-left: 20px;">
      <div style="font-weight: bold; font-size: 1.1em;">MineInsight: A Multi-Sensor Dataset for Humanitarian Demining Robotics in Off-Road Environments (2025)</div>
      <div style="font-style: italic;"><strong>Mario Malizia</strong>, Charles Hamesse, Ken Hasselmann, Geert De Cubber, Nikolaos Tsiogkas, Eric Demeester, and Rob Haelterman</div>
      <div style="margin-top: 5px;">
        <span class="badge" style="background-color: #34a853; color: white; padding: 5px 10px;">IEEE RA-L</span>
        <!-- <span class="badge" style="background-color: #757575; color: white; padding: 5px 10px;">Journal</span> -->
      </div>
      <div style="margin-top: 10px;">
        <a href="https://ieeexplore.ieee.org/document/11297788" class="btn btn-sm z-depth-0" role="button" style="border: 1px solid #4285f4; color: #4285f4; margin-right: 5px;">Paper</a>
        <a href="https://github.com/mariomlz99/MineInsight" class="btn btn-sm z-depth-0" role="button" style="border: 1px solid #333; color: #333;">GitHub</a>
      </div>
    </div>
  </div>

  <div class="row pub-row" style="margin-bottom: 25px; border: 1px solid #ddd; padding: 20px; border-radius: 8px;">
    <div class="col-sm-3" style="flex: 0 0 25%; max-width: 25%; text-align: center;">
      <img src="assets/img/publication_preview/2025_iccas_thumbnail.png" style="width: 100%; max-width: 180px; border-radius: 4px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);" alt="thumbnail">
    </div>
    <div class="col-sm-9" style="flex: 0 0 75%; max-width: 75%; padding-left: 20px;">
      <div style="font-weight: bold; font-size: 1.1em;">PFM-1 Landmine Detection in Vegetation Using Thermal Imaging with Limited Training Data (2025)</div>
      <div style="font-style: italic;"><strong>Mario Malizia</strong>, Ken Hasselmann, Alessandra Miuccio, Rob Haelterman, Nikolaos Tsiogkas, and Eric Demeester</div>
      <div style="margin-top: 5px;">
        <span class="badge" style="background-color: #4285f4; color: white; padding: 5px 10px;">ICCAS</span>
        <span class="badge" style="background-color: #ff9800; color: white; padding: 5px 10px;">Oral</span>
      </div>
      <div style="margin-top: 10px;">
        <a href="https://ieeexplore.ieee.org/document/11301116/" class="btn btn-sm z-depth-0" role="button" style="border: 1px solid #4285f4; color: #4285f4;">Paper</a>
      </div>
    </div>
  </div>

  <div class="row pub-row" style="margin-bottom: 25px; border: 1px solid #ddd; padding: 20px; border-radius: 8px;">
    <div class="col-sm-3" style="flex: 0 0 25%; max-width: 25%; text-align: center;">
      <img src="assets/img/publication_preview/2024_roman_thumbnail.jpg" style="width: 100%; max-width: 180px; border-radius: 4px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);" alt="thumbnail">
    </div>
    <div class="col-sm-9" style="flex: 0 0 75%; max-width: 75%; padding-left: 20px;">
      <div style="font-weight: bold; font-size: 1.2em;">HADRON: Human-friendly Control and Artificial Intelligence for Military Drone Operations (2024)</div>
      <div style="font-style: italic;">Ana M. Casado Faulí, <strong>Mario Malizia</strong>, Ken Hasselmann, Emile Le Flécher, Geert De Cubber, and Ben Lauwens</div>
      <div style="margin-top: 5px;">
        <span class="badge" style="background-color: #4285f4; color: white; padding: 5px 10px;">RO-MAN Workshop on Variable Autonomy for Human-Robot Teaming</span>
      </div>
      <div style="margin-top: 10px;">
        <a href="https://arxiv.org/abs/2408.07063" class="btn btn-sm z-depth-0" role="button" style="border: 1px solid #4285f4; color: #4285f4;">Paper</a>
      </div>
    </div>
  </div>

  <div class="row pub-row" style="margin-bottom: 25px; border: 1px solid #ddd; padding: 20px; border-radius: 8px;">
    <div class="col-sm-3" style="flex: 0 0 25%; max-width: 25%; text-align: center;">
      <img src="assets/img/publication_preview/2024_icra_thumbnail.png" style="width: 100%; max-width: 180px; border-radius: 4px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);" alt="thumbnail">
    </div>
    <div class="col-sm-9" style="flex: 0 0 75%; max-width: 75%; padding-left: 20px;">
      <div style="font-weight: bold; font-size: 1.2em;">A multi-robot system for the detection of explosive devices (2024)</div>
      <div style="font-style: italic;">Ken Hasselmann, <strong>Mario Malizia</strong>, Rafael Caballero, Fabio Polisano, Shashank Govindaraj, Jakob Stigler, Oleksii Ilchenko, Milan Bajic, and Geert De Cubber</div>
      <div style="margin-top: 5px;">
        <span class="badge" style="background-color: #4285f4; color: white; padding: 5px 10px;">ICRA Workshop on Field Robotics</span>
      </div>
      <div style="margin-top: 10px;">
        <a href="https://arxiv.org/pdf/2404.14167" class="btn btn-sm z-depth-0" role="button" style="border: 1px solid #4285f4; color: #4285f4;">Paper</a>
      </div>
    </div>
  </div>

</div>