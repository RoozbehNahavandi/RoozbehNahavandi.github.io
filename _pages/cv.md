---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/cv.pdf" download><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i> Download PDF</a></p>

<object class="cv-embed" data="{{ base_path }}/files/cv.pdf" type="application/pdf" aria-label="CV (PDF)">
  <p>Your browser can't display the PDF here. <a href="{{ base_path }}/files/cv.pdf">Open the CV</a> instead.</p>
</object>

<style>
  .cv-embed { width: 100%; height: 85vh; border: 1px solid var(--global-border-color, #ccc); border-radius: 4px; }
  /* Embedded PDFs rarely render on phones and tablets: show only the download link there. */
  @media (max-width: 640px), (hover: none) and (pointer: coarse) { .cv-embed { display: none; } }
</style>
