# Russian Arms Exporters
By Andrea Christelle, Ian Forrest, David Hang, Curtis McKendrick, & Andre Savkin


## Introduction 
The Center for Advanced Defensive Studies aims to identify non-state arms exporters and front companies for state-sponsored arms exports using profiles created from known exporters and manufacturers. This training set of tagged data consists of exports from Ukrainian and Russian state-owned arms exporters, with the aim of training a model for the identification of smaller companies exporting similar products or trading with similar parties. This information may be shared with export control authorities (C4ADS has a direct partnership with the IAEA Department of Safeguards).

Our project aimed to build these 'profiles' for known Russian arms exporters analyzing text through natural language processing (NLP). The dataset we analyzed, provided by C4ADS, contained over 170 GB of Russian trade information. Using NLP, we analyzed the text in the 'description' of every trade, and subsequently grouped bodies of similar text together using machine learning and KMeans clustering.

Once grouped, our customized product analyzes the patterns in the text of those trades and compares it with trading patterns of known arms exporters. This is accomplished by looking at the inverse euclidian distances and pairwise distances between the observations in n-dimensional space. In other words, it checks how similar the cluster ratios of each company are to known arms exporters.

The notebooks in this repository will explore our process.

