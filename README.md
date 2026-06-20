# ConCafe-Concept-Cooccurrence-Dataset
&nbsp;&nbsp;&nbsp;This repository contains concept cafe data for analyzing concept co-occurrence networks, community structures, regional patterns, and popularity distributions.
<br>
<br>
【concept_cafe_dataset.txt】
<br>
&nbsp;&nbsp;&nbsp;This dataset contains original concept cafe data collected from Japanese concept cafes listed on the concept cafe information website (https://con-cafe.jp/). The data were collected in February 2026. Each row represents an individual concept cafe, including basic information about the cafe, its concept description, popularity indicators, location information, and a processed list of concepts used for concept co-occurrence analysis.
<br>
&nbsp;&nbsp;&nbsp;・cafeName：Name of the concept cafe
<br>
&nbsp;&nbsp;&nbsp;・orderByNew：Listing order on the data collection platform
<br>
&nbsp;&nbsp;&nbsp;・concept：Original concept description provided by the cafe
<br>
&nbsp;&nbsp;&nbsp;・nofConKatsu：Number of user comments/reviews on the platform
<br>
&nbsp;&nbsp;&nbsp;・WantToGo：Number of user "want to visit" reactions (popularity indicator)
<br>
&nbsp;&nbsp;&nbsp;・OperatingHours：Operating hours of the cafe
<br>
&nbsp;&nbsp;&nbsp;・Fee：Pricing information
<br>
&nbsp;&nbsp;&nbsp;・NearestStation：Nearest railway station
<br>
&nbsp;&nbsp;&nbsp;・Area：Geographic area of the cafe
<br>
&nbsp;&nbsp;&nbsp;・concept_list：Tokenized list of individual concepts extracted from the original concept description
<br>
<br>
【concept_frequency_with_english_labels.txt】
<br>
&nbsp;&nbsp;&nbsp;This dataset contains concept-level statistics derived from Japanese concept cafe data. Each row represents an individual concept used by concept cafes. The dataset includes the original Japanese concept label, the number of concept cafes adopting each concept, and the corresponding English label used in the manuscript.
<br>
&nbsp;&nbsp;&nbsp;・concept：Original Japanese concept label extracted from concept cafe descriptions
<br>
&nbsp;&nbsp;&nbsp;・count：Number of concept cafes adopting the corresponding concept
<br>
&nbsp;&nbsp;&nbsp;・concept_Eng：English label of the concept used for analysis and visualization (translated by the author)
<br>

・The whole network devided by the community detection: https://yutarookn2025.github.io/ConCafe-Concept-Cooccurrence-Dataset/network_dividevByCommunities.html <p>
・・The Anime-Cosplay community: https://yutarookn2025.github.io/ConCafe-Concept-Cooccurrence-Dataset/Anime-Cosplay community.html <p>
・・The Gothic-Dark community: https://yutarookn2025.github.io/ConCafe-Concept-Cooccurrence-Dataset/Gothic-Dark community.html <p>
・・The Idol-Kawaii community: https://yutarookn2025.github.io/ConCafe-Concept-Cooccurrence-Dataset/Gothic-Dark community.html <p>
・・The Maid community: https://yutarookn2025.github.io/ConCafe-Concept-Cooccurrence-Dataset/Maid community.html <p>
・・The Music-Fashion community: https://yutarookn2025.github.io/ConCafe-Concept-Cooccurrence-Dataset/Music-Fashion community.html <p>
・・The Prince community: https://yutarookn2025.github.io/ConCafe-Concept-Cooccurrence-Dataset/Prince community.html <p>
・・The School-Student community: https://yutarookn2025.github.io/ConCafe-Concept-Cooccurrence-Dataset/School-Student community.html <p>
