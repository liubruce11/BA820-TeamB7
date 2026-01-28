# BA820-TeamB7

# Background:
Pet cats are some of the most common companion animals in the United Kingdom, yet they also represent a significant and often underappreciated ecological presence in urban and suburban neighbourhoods. Prior research estimates that pet cats in the UK kill up to 270 million animals annually, exerting predation pressure that can exceed that of native predators and is often highly concentrated near cats’ homes. This behavior proposed an important real-world challenge for urban wildlife management: while cats are individually owned and subject to household rules, their collective movement and hunting behavior can have substantial ecological impacts in the UK. Understanding how domestic cats actually use space, and how their movement behavior varies between different cats, is therefore a meaningful problem for the stakeholders of conservation researchers, policymakers, animal preservation groups, and local communities.
# Motivation:
	This project is motivated by the preliminary observation that household constraints on the cat, such as indoor time limits or hunting permission, are not useful predictors for the wide variability observed in cats’ real-world movement behavior. Even when subject to similar constraints, cats may display varied roaming patterns, space usage, and ecological impact. This difference raises our first research question: how much of observed movement behavior can be explained by household constraints alone, and what behavioral structure remains unexplained by these factors? (Appendix A)
# Potential Stakeholders: 
Ecological and conservation researchers studying wildlife predation
Animal preservation charities (SongBird Survival and Wildlife Aid Foundation)
NonProfit Organizations focused on animal welfare and behavior (Faunalytics)
Local governments and urban planners considering pet-related policies
Pet owners and local communities concerned with animal welfare
# Exploratory Data Analysis (EDA):
	We conducted preliminary EDA using the Pet Cats UK dataset, which combines high-frequency GPS tracking data with individual biological and household features. The first pattern we noticed was that the number of GPS observations per cat is highly imbalanced: most cats have moderate tracking coverage, but a small subset has extremely dense movement histories. This imbalance suggests that movement behavior should not be compared solely based on raw counts. Second, spatial visualizations revealed substantial heterogeneity in how cats use space. In the same geographic context, some cats show tightly localized movement patterns, while others roam much broader areas. This pattern shows that cats may differ in how they use space, and not just how much they move. Third, estimated prey capture per month is highly skewed: a small number of cats account for a majority of prey capture. This imbalance also suggests that ecological impact may be outlier cases rather than typical behavior.

