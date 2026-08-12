---
title: "⟡ Renewable Energy & Optimization"
subtitle: 'Originally published on <a href="https://sites.google.com/stu.wvusd.org/macrocosm-2026/week-3/cluster-recaps?authuser=0" target="_blank">Macrocosm 2026</a> (Cluster 6).'
intro: "In the summer of 2026, I attended UC Santa Cruz COSMOS, where I studied Smart and Sustainable Power. During the program, I joined the e-newsletter team and wrote about what I learned and experienced throughout the four weeks. I hope you enjoy reading Week 3!"
section: informational
category: "Smart & Sustainable Power"
date: 2026-07-26
---

<p>Monday of week 3 was Professor Zhang’s last day teaching our cluster, and it was an especially interesting lecture. We learned about four different types of renewable energy and how each converts natural resources into electricity.</p>
<figure class="article-figure center">
  <img src="/newspics/hydropower.png" alt="hydropower.">
  <figcaption></figcaption>
</figure>
<p>The first type of renewable energy we studied was hydropower, which generates electricity from flowing water. One of the most important concepts was head, the vertical distance that water falls before reaching a turbine. A greater head creates higher water pressure, allowing more energy to be extracted from the water. Higher pressure also makes it possible to achieve the same flow rate with a smaller turbine, reducing costs since turbine prices are closely related to their physical size.</p>

<figure class="article-figure center">
  <img src="/newspics/waterenergy.jpg" alt="waveenergy">
  <figcaption></figcaption>
</figure>
<p>Next, we learned about harnessing the ocean’s energy through waves and tides. One wave energy converter we discussed was the Oscillating Water Column (OWC), which uses the movement of waves to force air in and out of a chamber. This airflow spins a turbine at the top of the column, generating electricity. We also learned about the two main types of tidal energy: kinetic energy, which is captured from moving tidal currents, and potential energy, which comes from the difference in water levels between high and low tides.</p>

<figure class="article-figure float-left">
  <img src="/newspics/biomass.jpg" alt="bioenergy">
  <figcaption></figcaption>
</figure>
<p>The third renewable energy we explored was bioenergy, which generates electricity by burning organic materials known as biomass. While biomass can be a renewable source, burning it releases carbon dioxide and other pollutants into the atmosphere, making it less environmentally friendly than many other renewable energy sources.</p>

<figure class="article-figure float-left">
  <img src="/newspics/thermal.png" alt="thermal">
  <figcaption></figcaption>
</figure>
<p>Finally, we learned about geothermal energy, which uses heat stored beneath the Earth’s surface to generate electricity. Two common geothermal power plants are dry steam and flash steam plants. Dry steam plants use naturally occurring steam from underground reservoirs to drive turbines directly, while flash steam plants bring hot water to the surface, lower its pressure to produce steam, and then use the steam to generate electricity.</p>

<figure class="article-figure center">
  <img src="/newspics/chenoptimization2.png" alt="optimizationchen">
  <figcaption>Professor Chen explaining the math behind optimization.</figcaption>
</figure>
<p>Cluster 6 dove deeper into the concept of optimization with Professor Chen this week and even used Python to solve complex optimization problems. Professor Chen first introduced several key concepts in linear programming. The first were decision variables, which represent the values we are trying to determine, such as x and y. Next was the objective function, the equation we want to maximize or minimize, followed by the constraints, which are the limitations the solution must satisfy. In class, we worked through an optimization problem involving two types of power plants. Plant A could generate up to 800 MW with a marginal cost of $70/MWh, while Plant B could generate up to 1500 MW with a marginal cost of $25/MWh. Given two different demand periods, we created decision variables representing the electricity produced by each plant, developed an objective function to minimize the total generation cost, and added constraints based on the plants’ maximum capacities and electricity demand. After making the equations, we used scipy.optimize, a Python library used to solve mathematical optimization problems, to find the most cost-effective solution. Through this activity, we learned how optimization can help determine electricity prices, total costs, average costs, and generator profits while ensuring the energy demand is met efficiently.</p>