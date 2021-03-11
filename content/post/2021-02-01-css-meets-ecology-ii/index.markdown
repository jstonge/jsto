---
title: 'Computational social science meets ecology II'
author: Jonathan St-Onge
date: '2021-01-24'
slug: computational-social-science-meets-ecology-ii
categories: []
tags: []
subtitle: ''
summary: 'Does CSS meets ecology? Why do practitioners should care about CSS'
authors: []
lastmod: '2021-01-24T02:18:10+01:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
bibliography: css_meets_eco_ii.bib
---

## Is ecology into CSS?

As a computational science, CSS is about transforming information overload into opportunities (Lazer et al. 2009; Boyd-Graber, Hu, and Mimno 2017). We have 80 years worth of text data, and we want to make sense out of it. What it is about, how it changed, who are the key players, etc. Techniques such as latent dirichlet allocation and network theory allow us to *explore* and *summarize* large-scale datasets and provide insights on these questions. Call this the *synthetic perspective* of CSS.

To merely describe a large collection of data can prove unsatisfying to some practitioners. Practitioners become domain-experts precisely by doing that, by exploring and summarizing large volumes of information, and they are much better at it than current algorithms. Of course, there are reasons why the synthetic perspective might still be relevant to them. For example, they might want to learn about a lesser-known period of the field or perhaps validate their intuitions about the evolution of particular concepts. That said, I want to make the argument that CSS is more than a descriptive foray into large-scale datasets.

So how exactly can CSS be of use to practitioners? Does CSS meets ecology? In this post, I explain how and why I ended up targeting ecologists for this series, and not economists or neuroscientists, and briefly go over two perspectives from which we can motivate CSS to ecologists; the science of science (scisci) perspective and the narrative perspective.

## Why Ecology

Long story short, I became interested in ecology for its role in the evolution of modeling in science. Ever since the 50s and 60s, ecology positioned itself has a pioneering field in the study of complex systems using models, i.e. a simplified (some [people](https://en.wikipedia.org/wiki/All_models_are_wrong) might even say *wrong*) but useful representations of phenomena in the world. This step, to see models as a valid means to study complex systems, is a major leap in science. Before that, models weren’t seen as an end in themselves but as a temporary step towards developing physic-like theories (Morrison and Morgan 1999, ch.3). In *Primer of Ecological Theory*, Joan Roughgarden discusses this necessary change of mind in ecological modeling as she describes the necessary trade-off between simplicity and precision:

> If you’re a physicist, talks about kinds of models, and negotiations between simplicity and detail, seems strange indeed. One doesn’t negotiate about *F = ma* or the laws of thermodynamics. So ecology is different and it’s a good idea to accept this now. For the most part, mathematical models in ecology are not foundational, they are supplemental, and judged by their utility. (Roughgarden 1998)

I feel that something has changed with the ecological modeling. While this change of mind may not be exclusive to ecology, I think ecology has gone a long way in making science more comfortable with the idea that an approximate representation of the world might be good enough. Echoing philosopher William C. Wimsatt, ecologists were among the first to methodologically embrace the fact that we are limited beings in a very complex world, and that models might be our best shot at representing reality (see Wimsatt 2007 for more on how we are limited beings).

Anyway, this is how ecology became my whipping boy for talking about models. Being an optimist, I hope to meet ecologists on this ground when talking about CSS.

## Scisci: taking our destiny into our own hands

If you knew that major discoveries necessarily arrive early in scientific careers, would you do anything differently? How did you select your first scientific problem to work on? Was it your own doing, or was it inherited from your advisor. Was the problem a promising one? One that you can solve given the amount of time and tools you had at that time? Let’s say you want to make a career in academia, should you prefer, as an early career researcher, a larger team over a smaller one? Or perhaps, as a recent controversial [paper](https://www.nature.com/articles/s41467-020-19723-8) suggested it, you should go for a team led by a male advisor?

Speaking as a first-gen social scientist, most of the above questions let me clueless when I first thought about it. I didn’t think much about my choices early on. I’ve essentially worked on what I thought was interesting.

Although the above questions used to be exclusive to the realm of philosophy and sociology of science, they are now being investigated from the emerging field of scisci. Scisci is about the study of the structure and evolution of *science itself* through networks and other tools from complex science. They define science as a complex, self-organizing, and evolving network and evolving network of *scholars*, *projects*, *papers*, and *ideas* (Fortunato et al. 2018). As a branch of CSS, scisci is interested in the social processes underlying scientific inquiries, using large-scale datasets. With respect to the above questions, evidence from scisci suggest that major discoveries can happen at any point in scientific careers, but that researchers tend to be more productive early on (Sinatra et al. 2016), that some discoveries might be more predictable than others (Clauset, Larremore, and Sinatra 2017), that team sizes impact the types of discoveries with smaller teams being more disruptive, but larger teams are more cited anyway (Wu, Wang, and Evans 2019).

CSS can be motivated from a scisci perspective. At its core, scisci makes the following assumption:

> The value proposition of SciSci is that with a deeper understanding of the factors that drive successful science, we can more effectively address environmental, societal, and technological problems (Fortunato et al. 2018).

In our case, the idea is that a better understanding of the drivers of ecology would allow for a better organization of the field as a whole, both individually and collectively. From this perspective, CSS is relevant for practitioners because it can help identify the factors that make science successful, which could then lead to well-designed interventions.

Of course, this perspective assumes that it is desirable to try to steer the boat that is ecology in ways that we think more effective. Needless to say, we should be very careful in doing so. It is not because we find that female scientists with male advisors are more “productive” than those with female advisors that we should conclude that women ought to prefer male advisors over female ones. Given what we know about the history of science, it’s best to level the playing field before making a strong statement about it, if at all.

The scisci perspective motivates CSS in the grand scheme, but what about in the day-to-day lives of practitioners?

## The narrative perspective: reading, modeling & coding with purpose

<figure>
<img src="tasks.png" style="width:25.0%" alt="https://xkcd.com/1425/" /><figcaption aria-hidden="true">https://xkcd.com/1425/</figcaption>
</figure>

A question I often come across is the following: is it really necessary for people with particular domain expertise to learn coding and vice versa? Why not just collaborate? Of course we can collaborate, but I see two main reasons why collaboration is hard.

The first is perfectly illustrated by the XKCD comic above; coding is a very peculiar set of problem-solving skills in which it is hard to explain to uninitiated individuals the difficulty of a particular task. In other words, uninitiated individuals often fail to formulate, or simulate, their problems in a computer-friendly way, or one that takes advantage of the current state of computer science. This creates friction between the two camps.

A second barrier to collaboration comes from the other end, that is, *coding with purpose is hard*. As it is the case with reading or modeling, coding with purpose means seeing why a problem is a problem, and perhaps more importantly, why it needs to be addressed. This is a *stance*, as when we set out to read a text with a question in mind. Some problems are easier to grasp than others. Some problems take a PhD to understand why they are seen as problematic. Sometimes, to make someone see a problem, or worse, to make that person invests efforts before seeing it, is impractical. Arguably, this creates a challenge for domain experts to collaborate effectively with “formally trained” computer scientists.

I think this is where CSS comes in to meet ecology. CSS applied to ecology is a lubricant to facilitate collaboration between computer science and ecology, while being informed by yet another theoretical framework in the social sciences.

Coming back to our original question, coding with purpose also means that CSS will meet ecology when it answers questions ecologists care about. This might be a disappointing answer, but I think this is the big challenge. The weird thing about it is that this position requires prior knowledge about ecology without being an ecologist. Like the good old analogy of a map being too close from reality to be useful, computational social scientists must understand the insider view without becoming themselves ecologists. To do so, one must read what ecologists read or even better, work with them. If no one is close at hand, there are still plenty of blogs out there where you can learn the kinds of questions or beliefs ecologists have about ecology.[^1]

### If coding with purpose is hard, why not let ecologists do it?

If ecologists start investigating ecological investigations, are they still doing ecology? This is a trick question as old as Western philosophy itself. As soon as ecologists get into the practices of using large-scale datasets to understand their own field, they become CSS practitioners but with a background in ecology. The same way I come in to study ecology with a background from philosophy of science, [embodied cognition](https://en.wikipedia.org/wiki/Embodied_cognition), and [cultural evolution theory](https://plato.stanford.edu/entries/evolution-cultural/#CulEvoWitMem). The only thing I want to mention here is that if this is the case, it is important to recognize that ecology is, like any other science, a social process. To transfer knowledge from ecology onto ecology itself one needs to mind the gap between biological and cultural systems. For instance, we might want to use the idea of *niche* to describe the cultural environments scientists inherited when entering in particular communities. To some extent, this is an idea under consideration by cultural evolutionists and one that I would like to examine in more depth later on in this series.

Also, putting on my anthropologist hat for a second, I think there is value in having outsiders studying each other’s field. Ecologists, like any other culture, are less surprised when they encounter their own shared, patterned practices. This prior expectation is a double-edged sword when it comes to data analysis. It is much easier to know what we are looking for when we have strong priors than when it is an outsider who come in. Of course, the outsider sometimes needs the insider to collaborate or to know if the observed phenomenon is of interest. So, from an anthropological perspective, this make sense to collaborate with CSS people.

## Ultimate goal

The ultimate goal of this blog series is *to map the network of scholars, papers, and ideas to better understand the coevolution of modeling practices and social structure in ecology*. I will explore how the ecological socio-technical environment influenced modeling and, in turn, how modeling practices influenced the social structure of ecology. In honor of a [book](https://press.uchicago.edu/ucp/books/book/chicago/M/bo4343149.html) I like, we might summarize this project as understanding the social evolution of (mathematical) models.

Although this might not be controversial today, assuming that modeling practices, social communities and institutions are intermingled would have been radical to statisticians such as Ronald Fisher. For the [frequentist](https://en.wikipedia.org/wiki/Frequentist_probability) school of statistics, statistics is all about decoupling scientific activities from statistical modeling. This is how statistics allow us to be objective. My assumption here is that this view is wrong. To be clear, I do not say that frequentism is wrong. I claim that the idea that statistical modeling as independent from its social context, from people who created it, is wrong.

Starting from the fact that social structures and modeling are intermingled, I put forth the hypothesis that we can identify networks of interactions between the aforementioned layers. I think this will be of interest to ecologists because this is essentially the same basic assumption they take when using network approaches to ecological questions (for instance see Delmas et al. 2019). After having identified the social structure and the informational structure of ecological networks, the key contribution of this project is to put them together by finding social structures that stand in for particular models (a bit like flowers that contain information about their pollinators), and vice versa.

More precisely, the plan is to use network approaches to investigate ecological questions. That is, we will use the network approach to examine ecological questions themselves instead of ecological questions (yes, I know, this is confusing. Feel free to reread the sentence if necessary). This means to identify the “species” interaction networks (discrete groups of modeling practices and scientific communities), how they interact, their different roles, and so on.

Now, I reiterate the fact that I hope this problem statement will be relevant to ecologists in that it will allow them to better navigate the complex, multi-layered network that is ecology. Each component of the problem itself will be quantified using computational tools from CSS and reveal particular insights into the determinants of ecological investigations To give you a glimpse of where we are going, here is the current plan of the series (preliminary):

-   [x] Computational social science meets ecology I : Prelude
-   [x] Computational social science meets ecology II : is ecology into CSS?
-   [ ] Data interlude: show me what you got
-   [ ] Social structure I : mapping collaboration networks within journals
-   [ ] Social structure II : mapping collaboration networks across journals
-   [ ] Informational structure I : abstract dynamics
-   [ ] Informational structure II : mandatory topic modeling
-   [ ] Informational structure IV : models phylogeny
-   [ ] Sociosemantic structure : putting the two together

In this blog post we’ve seen that CSS might be of use to ecologists to identify the underlying social factors that drive ecological investigations. This can be useful for organizing the field as a whole, but also for understanding how models and the ecological socio-technical environment have co-evolved over the years. What gives my coding purpose is will be the later perspective, namely, showing how social structures and modeling are intertwined in ecology.

Now, all of this will require some data, which we give a brief overview in the next blog post.

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-boyd-graber_applications_2017" class="csl-entry">

Boyd-Graber, Jordan, Yuening Hu, and David Mimno. 2017. *Applications of Topic Models*.

</div>

<div id="ref-clauset_data-driven_2017" class="csl-entry">

Clauset, Aaron, Daniel B. Larremore, and Roberta Sinatra. 2017. “Data-Driven Predictions in the Science of Science.” *Science* 355 (6324): 477–80. <https://doi.org/10.1126/science.aal4217>.

</div>

<div id="ref-delmas_analysing_2019" class="csl-entry">

Delmas, Eva, Mathilde Besson, Marie-Hélène Brice, Laura A. Burkle, Giulio V. Dalla Riva, Marie-Josée Fortin, Dominique Gravel, et al. 2019. “Analysing Ecological Networks of Species Interactions.” *Biological Reviews* 94 (1): 16–36. <https://doi.org/10.1111/brv.12433>.

</div>

<div id="ref-fortunato_science_2018" class="csl-entry">

Fortunato, Santo, Carl T. Bergstrom, Katy Börner, James A. Evans, Dirk Helbing, Staša Milojević, Alexander M. Petersen, et al. 2018. “Science of Science.” *Science* 359 (6379): eaao0185. <https://doi.org/10.1126/science.aao0185>.

</div>

<div id="ref-lazer_social_2009" class="csl-entry">

Lazer, D., A. Pentland, L. Adamic, S. Aral, A.-L. Barabasi, D. Brewer, N. Christakis, et al. 2009. “SOCIAL SCIENCE: Computational Social Science.” *Science* 323 (5915): 721–23. <https://doi.org/10.1126/science.1167742>.

</div>

<div id="ref-morgan_models_1999" class="csl-entry">

Morrison, Margaret, and Mary S. Morgan. 1999. “Models as Mediating Instruments.” In *Models as Mediators*, edited by Mary S. Morgan and Margaret Morrison, 10–37. Cambridge: Cambridge University Press. <https://doi.org/10.1017/CBO9780511660108.003>.

</div>

<div id="ref-roughgarden_primer_1998" class="csl-entry">

Roughgarden, Jonathan. 1998. *Primer of Ecological Theory*. Prentice Hall.

</div>

<div id="ref-sinatra_quantifying_2016" class="csl-entry">

Sinatra, R., D. Wang, P. Deville, C. Song, and A.-L. Barabasi. 2016. “Quantifying the Evolution of Individual Scientific Impact.” *Science* 354 (6312): aaf5239–39. <https://doi.org/10.1126/science.aaf5239>.

</div>

<div id="ref-wimsatt_re-engineering_2007" class="csl-entry">

Wimsatt, William C. 2007. *Re-Engineering Philosophy for Limited Beings: Piecewise Approximations to Reality*. Cambridge, Mass: Harvard University Press.

</div>

<div id="ref-wu_large_2019" class="csl-entry">

Wu, Lingfei, Dashun Wang, and James A. Evans. 2019. “Large Teams Develop and Small Teams Disrupt Science and Technology.” *Nature* 566 (7744): 378–82. <https://doi.org/10.1038/s41586-019-0941-9>.

</div>

</div>

[^1]: For example, blogs from [Eco-Evo Evo-Eco](https://ecoevoevoeco.blogspot.com/) or [Dynamic Ecology](https://dynamicecology.wordpress.com/)
