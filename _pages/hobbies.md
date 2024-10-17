---
layout: archive
title: "Hobbies"
permalink: /hobbies/
author_profile: true
---

{% include base_path %}

<style>
.image-row {
  display: flex;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); /* Responsive grid */
  gap: 10px; /* Space between images */
  margin-bottom: 20px; /* Margin to prevent overlap with the next section */
  flex-wrap: wrap; /* Allow wrapping to next line if there are too many images */
}

.image-container {
  position: relative;
  height: 250px; /* Set the height for the container */
  flex-grow: 0;
  flex-shrink: 0;
  overflow: hidden; /* Hide overflow for uniformity */
}

.tooltip {
    height: 100%;
    display: flex;
}

.tooltip img {
  display: flex;
  width: auto;
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

Here are some of the overtly non-scientific things I love to do and am always happy to talk about!

Cooking
======
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
======
I love making cakes for special occasions- and sometimes regular occasions.

<div class="image-row">
	<div class="image-container">
		<div class="tooltip">
			<img src="../images/black_forest.jpg" alt="A cake I made for a friend's birthday!">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Black Forest Cake"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">A birthday cake for a friend. Chocolate sponge, cherry liqueur syrup, whipped cream, chocolate bark, pitted cherries and chocolate shavings.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/christmas_cake.jpg" alt="Cake with a festive spirit.">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Peppermint Pizzazz"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">Chocolate espresso sponge, peppermint buttercream, dark chocolate ganache, candy cane brittle and white chocolate peppermint bark.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/hazelnut_symphony.jpg" alt="I made this because of my never-ending love of Nutella.">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Hazelnut Symphony"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">No special occasion unless a love of Nutella counts as a special occasion. Chocolate sponge, hazelnut & almond streusel, hazelnut mousse, dark chocolate ganache, dark chocolate & Nutella shards, pecan shavings, Ferrero Rocher.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/oreo_domes.jpg" alt="Again, no special occasion, just a quirky dessert.">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Oreo Domes"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">Cookies & cream mousse hemispheres, Oreos (whole cookies and crumble), brownie round, vanilla mirror glaze, caramel syrup, lemon shavings, decorative Pirouette chocolate fudge wafer.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/reeses_cake.jpg" alt="Celebrating Halloween 2021!">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Ode to Reese's"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">Even though I stopped trick-or-treating over a decade ago, I still like to put out candy for everyone else. One year I had enough leftover peanut butter cups to make a cake- chocolate sponge, peanut buttercream, milk chocolate ganache, decorative Reese's cups.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/yule_log.jpg" alt="Celebrating Christmas 2021!">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Yuletide on the Forest Floor"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">Chocolate genoise sponge, chocolate chestnut whipped cream, dark chocolate ganache, meringue mushrooms, cranberry, decorative rosemary, sugar and simple syrup.</div>
				</div>
			</div>
		</div>
	</div>
</div>

Running
====== 
No better way to clear your head and relax than with constant searing lung pain! Just kidding, kind of. 
I'm on <a href="https://www.strava.com/athletes/83649431">Strava!</a>

<div class="image-row">
	<div class="image-container">
		<div class="tooltip">
			<img src="../images/cambridgeside_half.jpg" alt="First half marathon in 2023- 1:55:40">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Black Forest Cake"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">My first major running milestone was the Cambridgeside half marathon, completed in 1:55:40.</div>
				</div>
			</div>
		</div>
	</div>
</div>

 
Magic: The Gathering
====== 
The best tabletop game there is. A summary of my current EDH decks and favorite parts of the Multiverse.

<div class="image-row">
	<div class="image-container">
		<div class="tooltip">
			<img src="../images/Xenagos.jpg" alt="My oldest deck that I play regularly.">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Xenagos"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">The deck's pretty straightforward and fun. Play a bunch of big timmy creatures, give them haste and 2x their power with Xenagos, donk someone for 10+ in one turn.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/Xyris.jpg" alt="The deck I'm proudest of.">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Snakes on a Plane (Xyris)"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">The deck that I'm proudest of building from both a strength & fun factor. There are multiple different avenues to victory, the deck can create a degenerate number of snakes consistently and often creates some pretty wild turns for everyone at the table because of the group hug core.</div>
				</div>
			</div>
		</div>
	</div>

	<div class="image-container">
		<div class="tooltip">
			<img src="../images/Dragonhawk.jpg" alt="Burn baby, burn.">
			<div class="overlay">
				<div class="tooltiptext">
					<div class="tooltip-header">"Feathered Firestorm (Dragonhawk)"</div>
					<div class="tooltip-separator"></div>
					<div class="tooltip-description">My newest deck that I'm currently piloting, designed to hopefully be a thematic dragon tribal deck with treasures, burn damage and of course, dragons!</div>
				</div>
			</div>
		</div>
	</div>
</div>


Video Games
======
Currently, my top five video games of all time, in order: 
<ol>
  <li>The Elder Scrolls V: Skyrim</li>
  <li>Elden Ring</li>
  <li>Pokemon Mystery Dungeon: Explorers of Sky</li>
  <li>World of Warcraft</li>
  <li>Call of Duty: Black Ops 3</li>
</ol>

Media (not the biological kind!)
======
Some of my favorite movies (not in order, this is too hard):
* Interstellar
* Ratatouille (unironically inspired me to learn to cook!)
* The Dark Knight
* Good Will Hunting
* Hereditary
* Pirates of the Caribbean: The Curse of the Black Pearl
* The Holdovers

And shows:
* Jeopardy!
* Succession
* Full Metal Alchemist: Brotherhood
* 

Books:
* The Great Gatsby
* 
* 
* 

Music:
* Panic! At the Disco  


