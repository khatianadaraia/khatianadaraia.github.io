---
layout: archive
title: "Statistical Visualisations"
permalink: /stats-visuals/
author_profile: true
---


A collection of geometric and visual explanations of statistical concepts designed for undergraduate sociology students. While teaching a methods course to social science students, I have realised that the most effective approach is to frame statistical concepts through geometry. This allows students to grasp the underlying logic more easily; the visual representations are tangible mental models that stay with them long after abstract definitions fade.

I am currently working to compile these insights into a free e-book. I believe in making these visual methods accessible to everyone, so I'll be sharing updates and excerpts here periodically.
 
---


### Why Sociologists Care About Interactions

Interaction effects reveal **conditional relationships**—the answer to "it depends" questions:
- Does education affect income the same way for men and women?
- Does parental SES matter more or less depending on the country's level of inequality?


An interaction effect means the effect of one variable on the outcome *depends on* the level of another variable.

### Example: Education, Experience, and Income

The regression model: **Income = β₀ + β₁(Education) + β₂(Experience) + β₃(Education × Experience)**

That last term (Education × Experience) is the **interaction term**. It creates a "twist" in the relationship.

![Interaction Effects Visualization](/images/interaction_effects.png)

**Left panel (3D surface):** Shows how income changes across both education and experience simultaneously.Here, both education and experience increase income; the interaction term simply makes the slope steeper when both are high.

**Right panel (2D lines):**  Each line shows how education affects income *at different levels of experience*:
- Lower lines: With fewer years of experience, more education increases income gradually
- Upper lines: With more years of experience, more education increases income *much more steeply*

**The key:** The lines are **not parallel**. If there were no interaction, all three lines would be parallel (education would have the same effect regardless of experience). The fact that they fan out shows that education "pays off" more for people with more experience.





*A saddle analogy works for interactions where one effect is positive and another is negative—for example, a treatment that helps young people but hurts older people, or a policy that benefits one group while disadvantaging another.*

![True Saddle Interaction](/images/saddle_interaction.png)

The saddle surface above illustrates this: the same treatment produces **opposite effects** depending on age. Young people (blue lines) benefit from higher doses, while older people (red lines) are harmed. At age 45, the effect is zero. If you enjoy imagining world in shapes read more about saddle surface on this link: https://en.wikipedia.org/wiki/Saddle_point

---

## Covariance: The Concentration Ellipse

**The key insight:** Covariance measures how two variables "move together." The concentration ellipse gives us the big picture at a glance.

![Covariance Ellipse Visualization](/images/covariance_ellipse.png)

### Reading the Ellipse

**The Tilt** shows the *direction* of the relationship:
- Tilted right (↗) = positive covariance: when X goes up, Y tends to go up
- Tilted left (↖) = negative covariance: when X goes up, Y tends to go down

**The Stretch** shows the *strength* of the relationship:
- Long, thin "cigar" = strong covariance (tight relationship)
- Round "egg" = weak covariance
- Perfect circle = zero covariance (no relationship)

### The Symmetry of the Cloud

Here's something important: **Cov(X, Y) = Cov(Y, X)**

Geometrically, this makes sense. The "shape" of the relationship doesn't care which axis you label as X and which as Y. If you swap the axes (reflect the graph over a 45° diagonal line), a circular cloud stays circular. An elongated ellipse stays elongated at the same angle.

**The sociological implication:** If we find a high covariance between "Education" and "Income," the geometry alone cannot tell us whether education leads to higher income, or whether high-income families purchase more education. The stretch of the data is a *mutual property* of both variables.

### When the Circle is a Warning Sign

Look at the bottom-right panel: a perfect circle.

In a cigar-shaped ellipse, you can see a "corridor"—a trend, a path through the data.

In a circle, **there is no corridor**. There is no direction. There is only noise.

This is the visual proof of independence. The variables are not "traveling together" through the graph. Knowing someone's X tells you *nothing* about their Y.

### What Covariance Cannot Tell Us

Covariance is just a measure of **co-occurrence**. It tells us that two variables are "hanging out" in the same part of the graph. But it cannot tell us *who followed whom to get there*.

The ellipse shows association, not causation. Two variables can have a beautiful, tight, cigar-shaped relationship—and still have no causal connection whatsoever (think: ice cream sales and drowning deaths both rise in summer).

---

*More visualisations coming soon...*

