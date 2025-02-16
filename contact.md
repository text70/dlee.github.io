---
layout: default
title: "Contact"
---

<section class="container fade-in">
  <h1>Contact Neon Hearts & Minds</h1>
  <p>
    Have questions, ideas, or feedback?
    We’d love to hear from you. Share your thoughts and 
    help us keep shining bright.
  </p>

  <!-- Simple Contact Form (client-side only) -->
  <form 
    method="post" 
    action="https://formspree.io/f/your_form_endpoint" 
    style="max-width: 600px; margin: 2rem auto;"
  >
    <div style="margin-bottom: 1rem;">
      <label for="name" style="display: block; margin-bottom: 0.5rem;">
        Your Name
      </label>
      <input 
        type="text" 
        id="name" 
        name="name" 
        required 
        style="width: 100%; padding: 0.6rem; border: 1px solid #fe3dda;"
      >
    </div>

    <div style="margin-bottom: 1rem;">
      <label for="email" style="display: block; margin-bottom: 0.5rem;">
        Your Email
      </label>
      <input 
        type="email" 
        id="email" 
        name="email" 
        required 
        style="width: 100%; padding: 0.6rem; border: 1px solid #fe3dda;"
      >
    </div>

    <div style="margin-bottom: 1rem;">
      <label for="message" style="display: block; margin-bottom: 0.5rem;">
        Your Message
      </label>
      <textarea 
        id="message" 
        name="message" 
        rows="5" 
        required 
        style="width: 100%; padding: 0.6rem; border: 1px solid #fe3dda;"
      ></textarea>
    </div>

    <button 
      class="btn" 
      type="submit" 
      style="width: 100%; font-size: 1rem;"
    >
      Send Message
    </button>
  </form>
</section>
