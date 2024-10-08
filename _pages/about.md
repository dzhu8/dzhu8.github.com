---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

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

Hobbies
======
Here are some of the overtly non-scientific things I love to do and am always happy to talk about!

Cooking
------ 
To me, the ultimate form of artistic expression because you get to eat the art afterwards, and if you're lucky, it's as good as it looks!

<div class="image-row">
	<div class="image-container">
		<div class="tooltip">
			<img src="../images/chinese_new_year.jpg" alt="A dish for Lunar New Year 2022.">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Xīnnián Kuàilè"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">A celebration of the Lunar New Year. Egg fried rice, pork potstickers, sweet potato puree, radish, pea shoots, pork char siu, panda-styled red bean bun, fried sesame balls with ube jam.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/soil_sea_and_sky.jpg" alt="A taste of terrestrial, marine and aerial.">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Soil, Sea and Sky"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">A dish that represents each of the highest-level ecological zones: terrestrial, marine and aerial! Honey garlic salmon, orzo, sirloin steak, broccolini, pea puree, king oyster mushroom, duck, toasted sesame, tomato pearls and a teriyaki sauce & parsley tree.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/fancy_thanksgiving.jpg" alt="A dish for Thanksgiving 2021!">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Elevated Thanksgiving"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">An elevated take on Thanksgiving dinner. Turkey roulade, mashed potatoes, potato pave, cranberry gel, assorted vegetables.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/mediterranean.jpg" alt="A Mediterranean medley">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Mediterranean Medley"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">A miscellaneous Mediterranean mashup! Falafel, pita crisps, tzatziki, yogurt, harissa tahini, pomegranate, mango chutney, cucumber slaw, and basmati rice.</div>
				</div>
			</div>
		</div>
	</div>
	
	<div class="image-container">
		<div class="tooltip">
			<img src="../images/kbbq.jpg" alt="KBBQ plate">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"KBBQ Plate"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">Galbi (Korean BBQ short rib), nasi goreng w/ fried egg, Chinese cabbage slaw with sweet & sour homemade Asian dressing.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/deconstructed_big_mac_meal.jpg" alt="Fancy Big Mac meal">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Deconstructed Big Mac Meal"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">NY strip steak, toasted sesame buns, butter lettuce, pickle, onion, "special sauce", pommes puree, ketchup, Sprite in a wine glass (not pictured).</div>
				</div>
			</div>
		</div>
	</div>
</div>


Baking
------ 
I love making cakes for special occasions!

Running
------ 
No better way to clear your head and relax than with constant searing lung pain! Just kidding, kind of. 
 
Magic: The Gathering
------ 
The greatest tabletop game ever created. A summary of my current EDH decks and favorite parts of the Multiverse.

Video Games
------
Currently, my top five video games of all time, in order: 


  


