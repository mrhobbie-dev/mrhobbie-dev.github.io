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
<div class="hero-wrapper" style="position: relative; text-align: center; color: white; padding-top: 10px;">
  <!-- Hero Image -->
  <img src="./assets/hero.jpg" alt="Condo building" style="width:100%; height: 408px; object-fit: cover; filter: brightness(60%);">

  <!-- Gradient Overlay -->
  <div style="
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(
      rgba(0, 0, 0, 0.4),
      rgba(0, 0, 0, 0.4)
    );
    z-index: 1;
  "></div>
  <!-- Text + Button Overlay -->
  <div style="
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-shadow: 0 0 12px rgba(0,0,0,0.8);
    z-index: 2;
  ">
    <div style="font-size: 3rem; font-weight: 700;">
      Strata Solutions One
    </div>
    <div style="font-size: 1.5rem; margin-top: 10px;">
      Resident & Maintenance Tracking for Strata Councils
    </div>
    <div style="margin-top: 20px;">
      <a href="#Features" style="
        background-color: #2c8fdd;
        color: white;
        padding: 12px 24px;
        border-radius: 6px;
        text-decoration: none;
        font-size: 1.1rem;
        font-weight: 600;
      ">
        View Features
      </a>
    </div>
  </div>
</div>
<a id="Overview"></a>
<section style="padding: 40px 20px; max-width: 900px; margin: auto;">
  <h2 style="text-align:center;">Overview</h2>
  <p style="font-size: 1.2rem; line-height: 1.6;">
    Strata Solutions One is a modern, modular web application designed for strata councils
    who want a simple, reliable way to manage residents, maintenance requests, activity logs,
    and essential documents. Built for clarity and ease of use, it helps councils stay organized,
    accountable, and efficient.
  </p>
</section>
---

<a id="Features"></a>

<section style="padding: 40px 20px; max-width: 900px; margin: auto;">
  <h2 style="text-align:center;">Key Features</h2>

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
<section style="padding: 50px 20px; max-width: 900px; margin: auto;">
  <h2 style="text-align:center;">Interactive Previews</h2>
  <p style="text-align:center; font-size: 1.1rem; color:#555; margin-bottom: 30px;">
    Expand a section to see a rotating preview of the interface.
  </p>
  <!-- Accordion Container -->
  <div class="ss1-accordion">
      <!-- Accordion Item 1 -->
      <div class="ss1-accordion-item">
        <button class="ss1-accordion-header" data-section="residents">
          Resident Management
        </button>
        <div class="ss1-accordion-content">
          <div class="ss1-gallery" id="residents-gallery" data-gallery="residents">
            <!-- This placeholder will be replaced by buildGallery() -->
          </div>
        </div>
      </div>
      <!-- Accordion Item 2 -->
      <div class="ss1-accordion-item">
        <button class="ss1-accordion-header" data-section="projects">
          Project Tracking
        </button>
        <div class="ss1-accordion-content">
          <div class="ss1-gallery" id="projects-gallery" data-gallery="projects">
            <!-- This placeholder will be replaced by buildGallery() -->
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
        <button class="ss1-accordion-header" data-section="documents">
          Document Management
        </button>
        <div class="ss1-accordion-content">
          <div class="ss1-gallery" id="documents-gallery" data-gallery="documents">
            <!-- This placeholder will be replaced by buildGallery() -->
          </div>
        </div>
      </div>
      <!-- Accordion Item 5 -->
      <div class="ss1-accordion-item">
        <button class="ss1-accordion-header" data-section="forms">
          Forms & Workflows
        </button>
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
  <p>If you’d like to find out more about Strata Solutions One, request a demo, or connect about development work, I’d be happy to hear from you.</p>

  <p class="contact-email">
    <strong>Email:</strong>
    <a href="mailto:info@stratasolutions.one">info@stratasolutions.one</a>
  </p>
</section>

<footer style="text-align:center; padding: 20px; margin-top: 40px; color:#666;">
  © <span id="year"></span> Strata Solutions One — Built for Strata Councils
</footer>

<script>
  document.getElementById("year").textContent = new Date().getFullYear();
</script>
<script
      src="https://code.jquery.com/jquery-4.0.0.min.js"
      integrity="sha256-OaVG6prZf4v69dPg6PhVattBXkcOWQB62pdZ3ORyrao="
      crossorigin="anonymous"
    ></script>
<script>
      // Gallery image hover
      $(".img-wrapper").hover(
        function () {
          $(this).find(".img-overlay").animate({ opacity: 1 }, 600);
        },
        function () {
          $(this).find(".img-overlay").animate({ opacity: 0 }, 600);
        },
      );

      // Lightbox
      var $overlay = $('<div id="overlay"></div>');
      var $image = $("<img>");
      var $prevButton = $(
        '<div id="prevButton"><i class="fa fa-chevron-left"></i></div>',
      );
      var $nextButton = $(
        '<div id="nextButton"><i class="fa fa-chevron-right"></i></div>',
      );
      var $exitButton = $(
        '<div id="exitButton"><i class="fa fa-times"></i></div>',
      );

      // Add overlay
      $overlay
        .append($image)
        .prepend($prevButton)
        .append($nextButton)
        .append($exitButton);
      $("#gallery").append($overlay);

      // Hide overlay on default
      $overlay.hide();

      // When an image is clicked
      $(".img-overlay").click(function (event) {
        // Prevents default behavior
        event.preventDefault();
        // Adds href attribute to variable
        var imageLocation = $(this).prev().attr("href");
        // Add the image src to $image
        $image.attr("src", imageLocation);
        // Fade in the overlay
        $overlay.fadeIn("slow");
      });

      // When the overlay is clicked
      $overlay.click(function () {
        // Fade out the overlay
        $(this).fadeOut("slow");
      });

      // When next button is clicked
      $nextButton.click(function (event) {
        // Hide the current image
        $("#overlay img").hide();
        // Overlay image location
        var $currentImgSrc = $("#overlay img").attr("src");
        // Image with matching location of the overlay image
        var $currentImg = $('#image-gallery img[src="' + $currentImgSrc + '"]');
        // Finds the next image
        var $nextImg = $($currentImg.closest(".image").next().find("img"));
        // All of the images in the gallery
        var $images = $("#image-gallery img");
        // If there is a next image
        if ($nextImg.length > 0) {
          // Fade in the next image
          $("#overlay img").attr("src", $nextImg.attr("src")).fadeIn(800);
        } else {
          // Otherwise fade in the first image
          $("#overlay img").attr("src", $($images[0]).attr("src")).fadeIn(800);
        }
        // Prevents overlay from being hidden
        event.stopPropagation();
      });

      // When previous button is clicked
      $prevButton.click(function (event) {
        // Hide the current image
        $("#overlay img").hide();
        // Overlay image location
        var $currentImgSrc = $("#overlay img").attr("src");
        // Image with matching location of the overlay image
        var $currentImg = $('#image-gallery img[src="' + $currentImgSrc + '"]');
        // Finds the next image
        var $nextImg = $($currentImg.closest(".image").prev().find("img"));
        // Fade in the next image
        $("#overlay img").attr("src", $nextImg.attr("src")).fadeIn(800);
        // Prevents overlay from being hidden
        event.stopPropagation();
      });

      // When the exit button is clicked
      $exitButton.click(function () {
        // Fade out the overlay
        $("#overlay").fadeOut("slow");
      });
    </script>
<link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB"
      crossorigin="anonymous"
    />
<link
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css"
      rel="stylesheet"
    />
<script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI"
      crossorigin="anonymous"
    ></script>
