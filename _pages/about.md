---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This page is a window into both my professional and personal life- feel free to reach out via any of the contact links; I'm happy to chat about anything!

<!-- Include CSS and JS directly in the Markdown file -->
<style>
.image-row {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); /* Responsive grid */
  gap: 10px; /* Space between images */
  margin-bottom: 20px; /* Margin to prevent overlap with the next section */
  flex-wrap: wrap; /* Allow wrapping to next line if there are too many images */
}

.image-container {
  position: relative;
  height: 300px; /* Set the height for the container */
  flex-grow: 1; /* Allow width to vary */
  display: flex;
  align-items: center; /* Center image vertically */
  justify-content: center; /* Center image horizontally */
  overflow: hidden; /* Hide overflow for uniformity */
}

.tooltip img {
  display: block;
  width: auto; /* Ensure the image takes the full width of the container */
  height: 100%; /* Set the image height to 100% of the container */
  object-fit: contain; /* Maintain aspect ratio and cover the container */
  transition: 0.3s ease; /* Smooth transition for darkening effect */
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.6); /* Dark overlay */
  color: #fff; /* Text color */
  opacity: 0; /* Hidden by default */
  transition: 0.3s ease; /* Smooth transition */
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  border-radius: 10px; /* Match the border radius of the image */
}

.tooltip:hover img {
  filter: brightness(0.5); /* Darken the image when hovering */
}

.tooltip:hover .overlay {
  opacity: 1; /* Show the overlay when hovering */
}

.tooltiptext {
  padding: 20px;
  font-size: 16px;
}

.tooltip-header {
  font-weight: bold;
  margin-bottom: 10px;
}

.tooltip-separator {
  height: 1px;
  background-color: #ccc;
  margin-bottom: 10px;
}

.tooltip-description {
  font-size: 14px;
}
</style>

Biology
======
I am a molecular biologist studying the spatiotemporal characteristics of cells at the [Whitehead Institute](https://wi.mit.edu/) & [MIT](https://be.mit.edu/), with a focus on predicting the characteristics and consequences of interacting molecular components.

Computation
======
I develop analytical computational platforms (see the [Spateo package](https://github.com/aristoteleo/spateo-release)). I am also a hobby programmer always eager to learn more about what we can do with machines. I have recently ventured into developing atomistic protein modeling tools and language modeling (see the Portfolio page for examples!)


  


