---
title: 'Using Social Ties to Improve Technology Adoption: Does Heterogeneity Matter?'
date: 2023-08-28
permalink: /posts/2023/08/jmp-blog-post/
tags:
  - Targeting
  - Social Network
  - Technology Adoption
  - Agriculture
---

The adoption of modern technologies is generally low in developing countries. The literature has shown that information frictions are one of the key reasons behind such a phenomenon ([Magruder, 2018](https://www.annualreviews.org/doi/abs/10.1146/annurev-resource-100517-023202); [Mobarak and Saldanha, 2022](https://www.nature.com/articles/s41562-022-01323-9)) and that social ties can help by diffusing the information required to improve adoption. The core idea is to provide the necessary information to only a subset of the population (termed seeds) and reach most people through network connections. In doing this, it is crucial to choose the initial seeds in the right way. [Beaman et al. (2021)](https://www.aeaweb.org/articles?id=10.1257/aer.20200295) show that, given a specific, threshold-based characterization of the information diffusion process, we need to seed the most well-connected agents in a network. This result relies on the assumption that the diffusion of information depends on the number of links and position of each agent within the network. But, what if heterogeneity in other characteristics also affects the diffusion process?    
In the [working paper](https://www.aranyachakraborty.com/files/pdf/Network-Based%20Targeting%20with%20Heterogeneous%20Agents%20for%20Improving%20Technology%20Adoption.pdf) titled "Network-Based Targeting with Heterogeneous Agents for Improving Technology Adoption", I investigate the role of population heterogeneity in benefits from a technology for the diffusion of information regarding that same technology. To understand why population heterogeneity in its benefits may matter, consider for example the agricultural sector. Farmers are different from one another in education levels, skills, and abilities. Their farms also differ in land quality, size of the operation, access to irrigation, etc. I claim that this heterogeneity translates into heterogeneous benefits from any given technology. I show that such heterogeneity may affect the effectiveness of network-based interventions designed to improve technology adoption. I develop a network-based theoretical framework of information diffusion with heterogeneous agents and validate the predictions of my model using experimental data from Malawi.

Why does heterogeneity in benefits affect diffusion?
------
Learning in social networks requires spreading information from one agent to another. When the value of such information varies in a population, the knowledge of one agent may only be partially valuable to another. Consider the case of a newly developed seed that increases agricultural output. The effectiveness of the new seed variety may depend on the soil quality of the land or the education level of the farmer. As farmers differ in these characteristics, the experience of a farmer with the technology may not be equally valuable to another. Thus, if the new seed variety has a high yield only for a sub-section of the population with a specific quality of soil, providing information first to those agents without such soil quality will fail in reaching widespread diffusion. The heterogeneity in benefits from technologies and the effect of such heterogeneity on the diffusion of knowledge is widely recognized in the literature (e.g., [Munshi, 2004](https://www.sciencedirect.com/science/article/abs/pii/S0304387803001342); [Conley and Udry, 2010](https://www.aeaweb.org/articles?id=10.1257/aer.100.1.35); [Crane-Droesch, 2017](https://onlinelibrary.wiley.com/doi/abs/10.1093/ajae/aax090); [de Janvry et al.,2022](https://www.povertyactionlab.org/sites/default/files/research-paper/SeedingTheSeeds.pdf)). It is also well-documented that connected agents share similar characteristics that help them benefit similarly from any technology ([Munshi, 2007](https://www.sciencedirect.com/science/article/abs/pii/S157344710704048X)). However, little is known about the implications of such heterogeneity for network-based interventions that aim to foster technology adoption.

Social learning when benefits are heterogeneous
------

Consider a farmer trying to decide whether to adopt the new seed variety. She would require information on the effectiveness of this seed variety and seeks such information from her existing social connections. If everyone in the population is homogeneous in the information they need, the farmer would have no problem obtaining the information once some (or all) of her connections are informed. However, this would be different if people vary in the information they require. If agents that are connected share the same attributes, and the benefits from the new seed depend on those attributes, then agents can still learn from their connections in such assortative networks.  
We can see this in Figure 1A. The colors of this figure represent the benefits of some technology: red being high benefits, blue being low benefits, and yellow being average benefits. The arrows represent the network links. The links are assortative: agents are more likely to be connected to other agents with similar benefits from the technology. In such networks, informed agents can aid their uninformed connections in making the right decision as they share similar benefits. However, the extent to which this is the case depends crucially on the extent of heterogeneity in the population.

![jmp_figure1A](https://github.com/aranyac/aranyac.github.io/assets/92124904/c76ab93c-b3f4-4ea4-8e80-9a8ae068d819)



What does it mean for network-based interventions?
------

By design, network-based interventions focus on agent-level heterogeneity in social ties. For the type of diffusion process I study, the literature recommends targeting agents central to the network (in terms of existing connections) for effective diffusion. I expect this recommendation to be sensitive to population heterogeneity in the benefits of the technology. Particularly, centrality-based targeting should fail in diffusing information to those that require it for a population with highly heterogeneous benefits. In such a scenario, I argue that we can design an alternative targeting strategy based on the likelihood of adoption that would work better than centrality-based targeting if the network is highly assortative in the benefits. I call this probability-based targeting which seeds agents with the highest probability of adoption (conditional on observable characteristics) for effective diffusion.

Main results 
------

I use simulations to show that centrality-based targeting fails in the diffusion of information with high heterogeneity in benefits and that the probability-based strategy works better in such a scenario for assortative networks. For empirical verification of my results, I combine two different data sources from Malawi: the replication data of [Beaman et al. (2021)](https://www.aeaweb.org/articles?id=10.1257/aer.20200295) and the [Agricultural Extension Services and Technology Adoption Survey (AESTAS)](https://dataverse.harvard.edu/dataverse/harvard?q=Agricultural%20Extension%20Services%20and%20Technology%20Adoption%20Survey) data collected by the [International Food Policy Research Institute (IFPRI)](https://www.ifpri.org).  
[Beaman et al. (2021)](https://www.aeaweb.org/articles?id=10.1257/aer.20200295) use a randomized control trial (RCT) to improve the adoption of pit planting among maize farmers in 200 villages in Malawi. They selected two seed households per village following a two-stage randomization process. By the design of their experiment, the seed households vary in their centrality within their respective village networks. Additionally, I estimate the probability of adopting any new technology for the households in every village conditional on observable demographics, using data from AESTAS. These estimates help me calculate the adoption probability of seed households in the RCT and the coefficient of variation in these probabilities at the village level. I use the latter as a measure of village-level heterogeneity in benefits.  
I test whether the impact of the seeds’ centrality and average adoption probability on the village-level adoption of pit planting changes depending on the village-level heterogeneity in benefits. Table 5 presents the main empirical results of my paper. Controlling for village-level heterogeneity in adoption probabilities, adoption increases with the centrality of the seeds and decreases with the seeds' average adoption probability. However, as heterogeneity increases, the positive effect of seeds' centrality on adoption decrease. Similarly, the negative impact of seeds' average adoption probability also decreases with an increase in village-level heterogeneity. I find weaker (but similar) results using the experimental variations in the data.  

![jmp_table5](https://github.com/aranyac/aranyac.github.io/assets/92124904/edc3634a-bc25-422a-aacb-53177212398f)


Conclusion
------

These results support my hypotheses that centrality-based targeting performs worse as the population-level heterogeneity in benefits increases and that a probability-based strategy works better in such a scenario. The latter also suggests the assortative nature of the networks in characteristics determining the benefits. Overall, my results suggest that population heterogeneity in benefits from a new technology is crucial in the design of network-based interventions that aim to promote adoption. 


