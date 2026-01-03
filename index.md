---
layout: default        # or whatever layout your theme uses, e.g. "page" or "home"
title: "Home"
---

<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 1.5rem; margin-bottom: 2rem;">

  <!-- Profile Photo -->
  <div style="flex: 0 0 150px; max-width: 150px;">
    <img src="/profile.jpg" alt="Profile photo of Lucas Steinberger"
         style="width: 100%; border-radius: 50%; object-fit: cover;">
  </div>

  <!-- Intro Blurb -->
  <div style="flex: 1 1 250px; min-width: 250px;">
  Hello and welcome to my website! I am a first-year master’s student in Harvard University’s Computational
  Science and Engineering program, where I am primarily studying topics in physics, machine learning,
  and materials science. As of spring 2026 I have joined the Materials Intelligence Research group (MIR) under Prof. Boris Kozinsky, where I will be working   on applications of their NequIP model
  for interatomic potentials. You can use this page to find my info and links, some selected projects from my
  coursework and research, and a potpourri of photos from my personal hobbies and interests. Outside of STEM
  work or research, I love camping and outdoor adventure (sometimes of the type II variety), and I am an avid
  bass player who is always looking for new people to make music with!

  <br/><br/>
  <strong>Contact:</strong><br/>
  Email: <a href="mailto:Steinbergerlucas02@gmail.com">Steinbergerlucas02@gmail.com</a><br/>
  LinkedIn: <a href="https://www.linkedin.com/in/lucas-steinberger">lucas-steinberger</a><br/>
  GitHub: <a href="https://github.com/Steinburglar">Steinburglar</a>
  </div>

</div>

---

## Education

- **Harvard University** – Cambridge, MA  
  **M.S. in Computational Science and Engineering**  
  *Sep 2025 – Expected Dec 2026*

- **Tufts University** – Medford, MA  
  **B.S. in Physics, GPA: 4.0**  
  *Aug 2023 – May 2025*

- **Swarthmore College** – Swarthmore, PA  
  **B.A. in Physics, GPA: 4.0**  
  *Aug 2021 – Dec 2022*

---

---

---

## <span style="font-size: 1.8em; font-weight: 700;">Projects</span>

<p style="margin-top: 0.5rem;">
</p>

<div style="border: 1px solid #ddd; border-radius: 8px; padding: 1rem 1.25rem; margin-top: 1rem;">

  <h3 style="margin-top: 0; margin-bottom: 0.5rem;">
    Relaxed Equivariance for Anisotropic Noise
  </h3>

  <p style="margin-top: 0; margin-bottom: 0.5rem; font-style: italic;">
    Final project for AMATH 226, Theory of Neural Computation.
  </p>

  <p style="margin-top: 0; margin-bottom: 0.75rem;">
    <a href="/assets/papers/relaxed_equivariance.pdf">Read the full paper (PDF)</a>
  </p>

  <img src="/assets/img/noised_examples.png"
       alt="Example images from the Relaxed Equivariance for Anisotropic Noise project"
       style="width: 100%; border-radius: 8px; margin: 0.5rem 0 1rem 0;">

  <p style="margin-top: 0;">
    Equivariant neural networks have been shown to be more data-efficient and generalizable than their
    non-equivariant counterparts when the target function is known to be equivariant to some symmetry group.
    Recent work has also shown that for some physical systems with approximate symmetries, approximately
    equivariant models can outperform both normal and strictly equivariant models. In this work, we test the
    effectiveness of relaxed equivariant CNNs on a rotated MNIST classification task with added isotropic and
    anisotropic noise. We find that, contrary to our hypothesis and previous work, the fully equivariant model
    outperforms both the relaxed equivariant and normal CNN models in all noise settings.
  </p>

</div>
---

## Fun Stuff

<p>Some photos from things I enjoy outside of work and research.</p>

<div style="display: flex; flex-wrap: wrap; gap: 1rem;">

  <!-- Photo 1 -->
  <figure style="flex: 1 1 250px; margin: 0;">
    <img src="/assets/alison.jpeg"
         alt="Camping trip"
         style="width: 100%; max-width: 320px; border-radius: 8px;">
    <figcaption style="font-size: 0.9rem; color: #666; margin-top: 0.25rem;">
      Alison Lake, Valdez AK. Picked buckets of blueberries!
    </figcaption>
  </figure>

  <!-- Photo 2 -->
  <figure style="flex: 1 1 250px; margin: 0;">
    <img src="/assets/gus.jpeg"
         alt="Kayaking"
         style="width: 100%; max-width: 320px; border-radius: 8px;">
    <figcaption style="font-size: 0.9rem; color: #666; margin-top: 0.25rem;">
     We found this rooster on Crow island, named him Gus.  
    </figcaption>
  </figure>

  <!-- Photo 3 -->
  <figure style="flex: 1 1 250px; margin: 0;">
    <img src="/assets/album.jpeg"
         alt="Playing bass"
         style="width: 100%; max-width: 320px; border-radius: 8px;">
    <figcaption style="font-size: 0.9rem; color:g #666; margin-top: 0.25rem;">
      Recording an album with my college band.
    </figcaption>
  </figure>

</div>


