---
layout: home
top_image: "/assets/images/van.png"
jump:
  text: Find out more
  target: about
image: "/assets/images/og-preview.png"
blocks:
- template: block
  type: heading
  half: true
  heading: About
  heading_background: false
  text: "{{ site.description }}"
  buttons:
  - target: "/about"
    text: Read more
  image: ''
- template: block
  type: map
  half: true
  text: |-
    # Map

    A map of the route the freedom tour will take.
  buttons:
  - text: Full map
    target: "/map"
  image: ''
  heading: ''
  heading_background: false

---
