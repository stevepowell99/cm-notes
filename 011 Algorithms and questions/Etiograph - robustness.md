
> From [Powell, Copestake, et al. (2023)]()

Figure 3. An illustrative example of a very simple causal map.


Even with a simple example like this, we can answer many questions by visually examining the paths. But analysis of larger data sets might be simplified by selecting only all the paths between a selected cause and consequence to produce what Bougon et al (1977) called an ‘etiograph’. Eden et al. (1992) go so far as to collapse some causal paths into individual links, simply removing intervening factors.

Our causal map software uses the ‘maximum flow/minimum cut’ algorithm (Erickson, 2019), which quantifies the robustness of longer paths from C to E by calculating the minimum number of causal claims, which would have to be invalidated or lost to remove any possible causal pathway between them. This is simply the idea that the strength of an argument is dependent on the strength of its weakest link, extended to apply to an interconnected network rather than a single chain. In other words, we can express a path through a causal map as a possible argument: An argument can be constructed that C causally influences D, and then E. This also provides ways to formally address questions such as ‘how robust is the evidence for the influence of C on E, compared to evidence for the influence of B on E?’. As our causal evidence will often be of varying quality and reliability, we are advised to also construct and compare paths that consist only of evidence from the most reliable sources.
