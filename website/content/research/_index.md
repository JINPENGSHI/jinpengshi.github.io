+++
title = "Research"
menu = "main"
weight = 20
+++

<style>

.universal-wrapper h1 {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip-path: inset(50%);
  white-space: nowrap;
  border: 0;
}

.paper-entry {
  margin-bottom: 2rem;
  padding-bottom: 1.5rem;
  border-bottom: 1px solid #b5b5b5;
}

.paper-title {
  margin: 0 0 0.75rem;
  font-size: 1.1rem;
  font-weight: 600;
  line-height: 1.5;
  overflow-wrap: anywhere;
}

/* Paper link on its own line */
.paper-link {
  display: block;
  width: fit-content;
  margin-bottom: 0.75rem;
}

/* Blue, underlined links and Abstract control */
.paper-entry a,
.paper-entry summary {
  color: #2854b8;
  font-size: 1rem;
  text-decoration: underline;
  text-underline-offset: 0.15em;
}

.paper-entry summary {
  display: list-item; /* Keeps the native triangle */
  width: fit-content;
  padding-block: 0.25rem;
  cursor: pointer;
}

/* Abstract appears naturally when details opens */
.abstract-text {
  margin: 0.75rem 0 0;
  line-height: 1.7;
}

.paper-entry a:focus-visible,
.paper-entry summary:focus-visible {
  outline: 3px solid currentColor;
  outline-offset: 3px;
}

body.dark .paper-entry a,
body.dark .paper-entry summary {
  color: #9ecbff;
}
</style>

## Working Papers

<article class="paper-entry" aria-labelledby="paper-1">
  <h3 id="paper-1" class="paper-title">
    When District Attorneys Decide: Election Cycles and Prosecuting Behaviors
  </h3>

   [Read the paper](https://drive.google.com/file/d/1j-PIBRCszIKex6iYdMK10FqkJCKCSoBb/view?usp=sharing)
  

  <details>
    <summary>Abstract</summary>
    <p class="abstract-text">We study how electoral incentives shape the prosecuting behaviors of district attorneys. To do so, we leverage more than 4 million web-scraped criminal case records from the Commonwealth of Virginia spanning over 25 years. Our analysis yields four main findings: (1) Consistent with shifting public attitudes toward crime, effective sentencing has exhibited a long-run decline, but this trend reverses in the most recent election cycle(s). (2) We identify no electoral pressures on district attorneys until the most recent election cycle(s), with point estimates that run into the opposite direction to the existing literature. (3) In the most recent election cycle(s), as elections approach, district attorneys are more lenient on lesser offenses while harsher on server cases, thereby resulting in higher effective sentencing. (4) Finally, case processing times have risen steadily over the past 25 years, and proximity to elections is associated with additional delays. Taken together, our findings provide a comprehensive view of the effect of electoral incentives on district attorneys.</p>
  </details>
</article>


<article class="paper-entry" aria-labelledby="paper-2">
  <h3 id="paper-2" class="paper-title">
    Returns to Skills, Technological Change, and Intergenerational Mobility
  </h3>

  [Read the paper](https://drive.google.com/file/d/1jcb92jgaxq7S2iYNGtJRTbdNkTkG7q80/view?usp=drive_link)
  
  <details>
    <summary>Abstract</summary>
    <p class="abstract-text">How does technological change influence economic opportunities across generations? While existing literature documents that technological change has profound effects on earnings distributions and occupational skill requirements, much less is known about how technological change affects intergenerational income persistence.This paper develops a framework that conceptualizes technological change as a process of skill re-evaluation across cohorts. The model shows how changes in the returns to skills can either strengthen or weaken intergenerational income persistence, providing a mechanism linking technological change to long-run mobility outcomes. We then test the model’s predictions using linked census data and nationally representative surveys spanning several decades. Our preliminary evidence suggests that technological change initially boosts intergenerational mobility by increasing skill demand; however, this effect fades over time as skill supply adjusts to shifts in relative returns. These findings contribute to ongoing policy debates on how to ensure that future technological change generates broadly shared economic gains.</p>
  </details>
</article>


<article class="paper-entry" aria-labelledby="paper-3">
  <h3 id="paper-3" class="paper-title">
    A Theory of Intergenerational Mobility: Heterogeneous Returns and Social Capital
  </h3>

  [Read the paper](https://drive.google.com/file/d/1YqoLWWlARqmkfBU7ODI_0hTUO2_Hesrm/view?usp=drive_link)
  
  <details>
    <summary>Abstract</summary>
    <p class="abstract-text">Recent empirical evidence has documented the importance of social capital in shaping the economic opportunities in the labor market. We build on Becker et al. (2018) to formally theorize the role of social capital by endogenzing return to human capital. We introduce complementarity between family wealth and human capital in earning function. Our model prediction provides empirical relevant estimates of intergenerational elasticity, and is able to sustain high persistence without having to assume convexity between earnings and human capital. Our model highlights how social capital can exacerbate economic inequalities under imperfect labor market, the effect is more pronounced for the bottom of income distribution. We also point out that public intervention programs that overlook the role the social network among the disadvantaged may be insufficient to eradicate economic disparity across generations.</p>
  </details>
</article>


<article class="paper-entry" aria-labelledby="paper-4">
  <h3 id="paper-4" class="paper-title">
    Innovation in Product Iteration
  </h3>

  <details>
    <summary>Abstract</summary>
    <p class="abstract-text">This paper develops a dynamic model to examine firms’ strategic innovation decisions in markets where product quality and brand reputation play a pivotal role. Focusing on a two-period duopoly framework, the model highlights the trade-offs firms face in allocating resources between incremental product updates and riskier breakthrough innovations. Consumers derive utility not only from product quality but also from brand reputation, which is endogenized as a function of past sales. This interplay between quality competition and reputation dynamics is crucial in shaping firms’ profit-maximization strategies. The model extends the work of Goettler and Gordon (2011, 2014) by introducing endogenous brand reputation and differentiating types of innovation investments. Through comparative statics and equilibrium analysis, the findings provide insights into how leading and following firms navigate innovation decisions to maintain or improve their market position.</p>
  </details>
</article>


## Work in Progress

- Intergenerational Mobility Accounting over a Century
- Returns to Skills, Artificial Intelligence, and The Future of Intergenerational Mobility
- Publishing via Networking  
- Children as Risky Assets  
- Learning from Randomness: The Mechanics and Identification of Non-shared Environment 
- On the Monotonicity of Mendelian Randomization 
- Uniformly Fast and Efficient Optimization in Genome-wide Association Studies  

<script>
function toggleAbstract(id) {
  var a = document.getElementById(id);
  if (a.style.display === "block") {
    a.style.display = "none";
  } else {
    a.style.display = "block";
  }
}
</script>