---
title: Zenith
type: docs
prev: docs/
next: docs/zenith/bom/
---

![zenith.jpg](/img/placeholder/placeholder2.jpg)
{{< badge content="GitHub" link="https://github.com/typewatch/zenith" icon="github" >}}
{{< badge content="YouTube" link="https://www.youtube.com/watch?v=dQw4w9WgXcQ" icon="youtube" >}}

uhh imagine the stuff below is placeholder text and not real zenith writeup stuff

Zenith is a product development exercise and jab at the premade/semi-DIY air purifier market. The aforementioned market is full of great products that do their job remarkably well---however---multiple of them unfortunately boast intentional kinks and pointless features that turn an excellent device into an underperforming, expensive, unrepairable paperweight. This air purifier aims to perform one thing and one thing only: air purification. No more, no less. By avoiding scope creep and pointless overengineering, Zenith ends up as a relatively cheap, stylish, and efficient air purifier.

Several versions have been released, all based on the same core device, with varying levels of bells and whistles that add a little bit extra to the user experience. All parts & upgrades are modular and can be added, removed and replaced with nothing more than a screwdriver, and a little bit of time.

So I've been researching air quality and purification for a little while by now and, among the many interesting bits of info I've picked up along the way, I have also found that "real" (consumer-oriented brand-made) air purifiers are really expensive, laughably inefficient (see "filters" section for explanation) and blatant exemplars of the razor and blades business model. Just straight up awful. 

To combat this and price-hikes during covid, corsi-rosenthal boxes popped up. CRboxes are great little cost-effective doohickeys that have helped many people stay safe and breathe clean air for years, although they introduce some uncertainty to the ease-of-use brand air purifiers provide, and require some DIYing, which may put away some people from getting an air purifier. Noticing this issue, prebuilt crboxes came to existance. I have a grudge with most prebuilt crbox manufacturers because not only are these air purifiers incredibly expensive (at or above the pricepoint of brand air purifiers), they also look really bad and have a lot of really unnecessary bloat that just bumps the price up even higher. 

Zenith aims to perform one thing and one thing only: air purification. No more, no less. By avoiding scope creep and pointless overengineering, I reckon a decently-performing, decently-looking premade crbox can be achieved. 

I will begin development shortly, but I'm afraid a prototype might take a little time before happening due to budget constraints. I'll link up zenith's github soon™ 

## Filters

I forgot to explain the inefficient part, and kind of ran out of space to do it properly, so here's a half-assed version: Air purifiers are really simple machines; they slurp up air, sift it through a filter and push it out. The more air volume your purifier filters in a given time, the better it is at purifying air. Most brand purifiers tend to use filters labeled as HEPA filters, which are rated to clean up to 99.97% of 0.3µm particles. That sounds good...right? Well, yes—and no. As I mentioned earlier, a good air purifier is one that can clean a big volume of air quickly, meaning it will most often than not go through the same air multiple times. A HEPA filter will clean practically everything with the first pass, but will also heavily restrict airflow, making your air purifier worse compared to one using a run-of-the-mill MERV 13 filter rated for 50% of 0.3µm particles, which will go through x volume of air multiple more times and clean what it didn't get on the first pass fairly quickly. 