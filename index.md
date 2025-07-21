---
layout: default
title: Home
description: We build civic tech projects to make our city better for everyone.
---

<section id="mission" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Our Mission</h2>
    <p class="lead text-center">
      We connect developers, designers, and engaged citizens to collaborate on open-source civic tech projects
      that address local issues, improve public services, and promote transparency and participation in {{ site.location | default: "your city" }}.
    </p>
  </div>
</section>

<section id="projects" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Current Projects</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Open Transit</h5>
            <p class="card-text">Making transit data accessible and visual for riders and city planners.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Neighbourhood Finder</h5>
            <p class="card-text">Helping residents discover community services and supports nearby through smart maps and filters.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">311 Tracker</h5>
            <p class="card-text">Tracking and visualizing 311 service requests to improve city response and accountability.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="join" class="py-5">
  <div class="container text-center">
    <h2 class="mb-4">Join the Movement</h2>
    <p class="lead mb-4">
      Developers, designers, researchers, and residents — we need your skills and your voice to make a difference in {{ site.location | default: "our community" }}.
    </p>
    <a href="#" class="btn btn-primary btn-lg">Join Our Discord</a>
  </div>
</section>
