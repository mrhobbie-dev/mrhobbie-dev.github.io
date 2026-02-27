<link rel="icon" href="/favicon.ico">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
<!-- Lightweight Custom Navigation -->
<nav class="ss1-nav">
  <div class="ss1-nav-inner">
    <div class="ss1-logo">Strata Solutions One</div>
    <div class="ss1-links">
      <a href="#Overview">Overview</a>
      <a href="#Features">Features</a>
      <a href="#Screenshots">Screenshots</a>
      <a href="#Contact">Contact</a>
    </div>
  </div>
</nav>
<div
  class="hero-wrapper"
  style="position: relative; text-align: center; color: white; padding-top: 10px"
>
  <!-- Hero Image -->
  <img
    src="./assets/hero.jpg"
    alt="Condo building"
    style="width: 100%; height: 408px; object-fit: cover; filter: brightness(60%)"
  />

  <!-- Gradient Overlay -->
  <div
    style="
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4));
      z-index: 1;
    "
  ></div>
  <!-- Text + Button Overlay -->
  <div
    style="
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-shadow: 0 0 12px rgba(0, 0, 0, 0.8);
      z-index: 2;
    "
  >
    <div style="font-size: 3rem; font-weight: 700">Strata Solutions One</div>
    <div style="font-size: 1.5rem; margin-top: 10px">
      Resident & Maintenance Tracking for Strata Councils
    </div>
    <div style="margin-top: 20px">
      <a
        href="#Features"
        style="
          background-color: #2c8fdd;
          color: white;
          padding: 12px 24px;
          border-radius: 6px;
          text-decoration: none;
          font-size: 1.1rem;
          font-weight: 600;
        "
      >
        View Features
      </a>
    </div>
  </div>
</div>
<a id="Overview"></a>
<section style="padding: 40px 20px; max-width: 900px; margin: auto">
  <h2 style="text-align: center">Overview</h2>
  <p style="font-size: 1.2rem; line-height: 1.6">
    Strata Solutions One is a modern, modular web application designed for strata councils who want
    a simple, reliable way to manage residents, maintenance requests, activity logs, and essential
    documents. Built for clarity and ease of use, it helps councils stay organized, accountable, and
    efficient.
  </p>
</section>
---

<a id="Features"></a>

<section style="padding: 40px 20px; max-width: 900px; margin: auto">
  <h2 style="text-align: center">Key Features</h2>

  <h3>Why Strata Councils Love It</h3>
  <ul>
    <li>Reduces administrative workload</li>
    <li>Improves communication and accountability</li>
    <li>Keeps all council information in one place</li>
    <li>Easy to learn and simple to maintain</li>
    <li>Built with long-term clarity and reliability in mind</li>
  </ul>

  <h3>Resident Management</h3>
  <ul>
    <li>Maintain accurate records for owners, tenants, and unit details</li>
    <li>Log move‑ins, move‑outs, and contact changes in a structured workflow</li>
    <li>Offer council members a centralized, easy‑to‑navigate resident directory</li>
    <li>Automatically validate form submissions using up‑to‑date owner information</li>
  </ul>

  <h3>Project Tracking</h3>
  <ul>
    <li>Stay informed with clear visibility into major project progress</li>
    <li>Organize and compare vendor quotes for transparent decision‑making</li>
    <li>Track expenses using uploaded invoices and cost documentation</li>
    <li>Centralize related files, including contracts, photos, and project plans</li>
  </ul>

  <h3>Activity & Maintenance Tracking</h3>
  <ul>
    <li>Submit, track, and update maintenance issues</li>
    <li>Assign tasks and monitor progress</li>
    <li>Maintain a full history of completed work</li>
    <li>Track follow-ups and deadlines</li>
    <li>A transparent record for future councils</li>
  </ul>

  <h3>Document Management</h3>
  <ul>
    <li>Store bylaws, meeting minutes, notices, and other key documents</li>
    <li>Organize files by category for quick, intuitive access</li>
    <li>Ensure council members can easily find the information they need</li>
    <li>Configure site pages to always display the latest document version</li>
  </ul>

  <h3>Forms & Workflows</h3>
  <ul>
    <li>Consistent, structured forms for reliable data collection</li>
    <li>Modular workflows that streamline and standardize council processes</li>
    <li>Built for clarity, maintainability, and future growth</li>
    <li>Automatic email confirmations keep everyone informed</li>
    <li>Full audit history for every form submission</li>
  </ul>
</section>
<a id="Screenshots"></a>

<section style="padding: 50px 20px; max-width: 900px; margin: auto">
  <h2 style="text-align: center">Interactive Previews</h2>
  <p style="text-align: center; font-size: 1.1rem; color: #555; margin-bottom: 30px">
    Expand a section to see a rotating preview of the interface.
  </p>
  <!-- Accordion Container -->
  <div class="ss1-accordion">
    <!-- Accordion Item 1 -->
    <div class="ss1-accordion-item">
      <button class="ss1-accordion-header" data-section="residents">
        Owner & Resident Information
      </button>
      <div class="ss1-accordion-content">
        <div class="screenshot-grid">
          <img src="./assets/screenshots/residents1.png" class="thumb" onclick="openModal(this.src)" />
          <img src="./assets/screenshots/residents2.png" class="thumb" onclick="openModal(this.src)" />
          <img src="./assets/screenshots/residents3.png" class="thumb" onclick="openModal(this.src)" />
          <!--<img src="img/residents4.jpg" class="thumb" onclick="openModal(this.src)" />-->
        </div>
      </div>
    </div>
    <!-- Accordion Item 2 -->
<div class="ss1-accordion-item">
  <button class="ss1-accordion-header" data-section="projects">
    Project Tracking
  </button>

  <div class="ss1-accordion-content">
    <div class="screenshot-grid">
      <img src="./assets/screenshots/projects1.png" class="thumb" onclick="openModal(this.src)">
      <img src="./assets/screenshots/projects2.png" class="thumb" onclick="openModal(this.src)">
      <!--<img src="img/projects3.jpg" class="thumb" onclick="openModal(this.src)">
      <img src="img/projects4.jpg" class="thumb" onclick="openModal(this.src)">-->
    </div>
  </div>
</div>
    <!-- Accordion Item 3 -->
    <div class="ss1-accordion-item">
      <button class="ss1-accordion-header" data-section="activity">
        Activity & Maintenance Tracking
      </button>
      <div class="ss1-accordion-content">
        <div class="ss1-gallery" id="activity-gallery" data-gallery="activity">
          <!-- This placeholder will be replaced by buildGallery() -->
        </div>
      </div>
    </div>
    <!-- Accordion Item 4 -->
    <div class="ss1-accordion-item">
      <button class="ss1-accordion-header" data-section="documents">Document Management</button>
      <div class="ss1-accordion-content">
        <div class="ss1-gallery" id="documents-gallery" data-gallery="documents">
          <!-- This placeholder will be replaced by buildGallery() -->
        </div>
      </div>
    </div>
    <!-- Accordion Item 5 -->
    <div class="ss1-accordion-item">
      <button class="ss1-accordion-header" data-section="forms">Forms & Workflows</button>
      <div class="ss1-accordion-content">
        <div class="ss1-gallery" id="forms-gallery" data-gallery="forms">
          <!-- This placeholder will be replaced by buildGallery() -->
        </div>
      </div>
    </div>
  </div>
</section>
<a id="Contact"></a>
<section id="contact" class="contact-section">
  <h2>Contact</h2>
  <p>
    If you’d like to find out more about Strata Solutions One, request a demo, or connect about
    development work, I’d be happy to hear from you.
  </p>

  <p class="contact-email">
    <strong>Email:</strong>
    <a href="mailto:info@stratasolutions.one">info@stratasolutions.one</a>
  </p>
</section>

<footer style="text-align: center; padding: 20px; margin-top: 40px; color: #666">
  © <span id="year"></span> Strata Solutions One — Built for Strata Councils
</footer>
<div id="lightbox" class="lightbox" onclick="closeModal()">
  <img id="lightbox-img">
</div>
<script>
  document.getElementById("year").textContent = new Date().getFullYear();
</script>
<script>
  document.querySelectorAll(".ss1-accordion-header").forEach((header) => {
    header.addEventListener("click", () => {
      const content = header.nextElementSibling;

      // Close others
      document.querySelectorAll(".ss1-accordion-content").forEach((c) => {
        if (c !== content) {
          c.style.maxHeight = null;
          c.classList.remove("open");
        }
      });

      // Toggle this one
      if (content.style.maxHeight) {
        content.style.maxHeight = null;
        content.classList.remove("open");
      } else {
        content.style.maxHeight = content.scrollHeight + "px";
        content.classList.add("open");
      }
    });
  });
</script>
<script>
function openModal(src) {
  document.getElementById('lightbox-img').src = src;
  document.getElementById('lightbox').style.display = 'flex';
}

function closeModal() {
  document.getElementById('lightbox').style.display = 'none';
}
</script>
