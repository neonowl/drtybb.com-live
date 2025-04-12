---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: DRTYBB LLC
      text: Product Management. Creative Development. Digital Design.
      primary_action:
        text: Contact Us
        url: /#contact
        icon: rocket-launch
      secondary_action:
        text: About Us
        url: /#about
      announcement:
        text: "Powered by"
        link:
          text: "HugoBlox"
          url: "https://hugoblox.com/?utm_campaign=poweredby"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: testimonials
    content:
      title: "The DRTYBB LLC Story"
      text: "Jeremy Chandler Van Doren, the owner/operator and general manager of DRTYBB LLC, was inspired by a seemingly innocuous passage from one of his favorite non-fiction books on adult ADHD. The rest is history (or will be in good time)!"
      items:
        - name: "Dr. Tamara Rosier PhD"
          role: "Your Brain's Not Broken"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-book.jpg"
          text: “You want to know how I see my ADHD?” Melanie said. “It’s a dirty baby.” ... Since being diagnosed, Melanie said, “My life is starting to make sense now.” That part of herself that she couldn’t entirely trust, the dirty baby, was ADHD. “No matter how many times I wash him, he’s always messy.” I giggled at her metaphor and then stopped at her serious look. “I really hate how the dirty baby makes me feel overwhelmed and angry. Some days, I just end up hating myself.” Melanie was beginning to understand how menacing the emotional dysregulation associated with ADHD feels.
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
---
