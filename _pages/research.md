---
title: "Research"
permalink: /research/
author_profile: true
---


## Factual Generalization Capabilities of GPT-3 Across Domains [[paper]](/files/MLLU_final.pdf)

GPT-3 has achieved impressive results in general purpose question answering tasks, exceeding human performance in some instances, but still has its weaknesses. TruthfulQA looks at imitative falsehoods stemming from defections in the training dataset, and provides a benchmark of questions where the most common answer online will likely be false. Building on this, we present a further study on generalizing factuality across domains where such falsehoods are prone. We evaluate the effectiveness of different domain combinations and prompting techniques after cross-prompting among six domains. Further exploration of the general-ization capacities beyond questions present in TruthfulQA is then provided.

![](/images/SampleQA.jpg)

*Figure 1. Sample Question-Answer pairs from experiments using different prompting methods*

![](/images/promtmethods.jpg)

*Figure 2. Our main result -- accuracy of prompt methods goes up as number of prompts increases*

## NBA Winning Rate and Season Record Prediction [[paper]](/files/ML_Final_paper.pdf)

Statistics driven performance analysis has been gaining ground in all major sports leagues. Particularly, the National Basketball Association (NBA) is at the frontlines of transitioning to data-driven approaches. While various statistical models for predicting the MVP candidate and the championship possibilities have been developed, the field of single-game winning rate prediction has gone rather under-explored. Here we report our efforts in achieving accuracies of predicting single-game outcomes comparable to preexisting machine learning models. After formatting the raw dataset with aggregate functions that yield recent performance, we evaluated across five different models to generate our best guess at the W/L result. Since our model takes into account the lineups of each team, it also offers quantitative insights into NBA team’s roster management.

![](/images/Coef_Mat.png)

*Figure 3. EDA: Correlation coefficient of all features including box scores.*


![](/images/ML_methods.png)

*Figure 4. The ROC curves of all models we employed.*



## RL for CAD Flows and Secure Chip Design [[slides]](https://github.com/Dennis-who/Dennis-who.github.io/blob/5bac951fe0f85313c0db70cb64483fb85a2689ce/files/ML%20for%20CAD%20Flows%20and%20Secure%20Chip%20Design.pdf)

Due to the increasing size of integrated circuits, their design and optimization phases (i.e., computer-aided design, CAD) grow increasingly complex. At design time, a large design space needs to be explored to find an implementation that fulfills all specifications and then optimizes metrics like energy, area, delay, reliability, etc. At run time, a large configuration space needs to be searched to find the best set of parameters (e.g., voltage/frequency) to further optimize the system. Both spaces are infeasible for exhaustive search typically leading to heuristic optimization algorithms that find some trade-off between design quality and computational overhead. Machine learning can build powerful models that have successfully been employed in related domains. In this project, we categorize how ML may be used and is used for design-time and run-time optimization and exploration strategies of ICs. A meta-study of published techniques unveils areas in CAD that are well-explored and underexplored with ML, as well as trends in the employed ML algorithms. We present a comprehensive categorization and summary of the state of the art on ML for CAD. Finally, we summarize remaining challenges and promising open research directions.

![](/images/CAD.png)

*Figure 5. The basic structure of incorporating ML into hardware design.*



## [On-going] Diversity and Fairness in Music Recommendations

Recommendation systems are algorithms used to match users to content based on the individual's history of interactions. With the abundance of commodities increasing and thus becoming impossible for a user to fully experience, the role of the recommender system is becoming more prominent in affecting people’s information feeds and decision making in terms of what music to listen to, what content to watch, or what products to purchase.

Modern recommender systems have evolved rapidly, as have deep learning models that are well-optimized for overall performance. A recommendation algorithm that focuses solely on average performance, on the other hand, may reinforce the exposure bias in the training data and exacerbate the "rich-get-richer" effect, trapping users in a experience among certain subgroups. This is a common problem that many recommender systems suffer from popularity bias. This phenomenon is especially pronounced in music streaming platforms: more and more viral hits are produced by short video content such as those in TikTok, and users often have no choice but to hear those songs in every playlist.  However, recommending the ignored products in the "long tail" is critical for businesses as they are less likely to be discovered. With this in mind, a more fair and niche-sensitive recommender is needed.

