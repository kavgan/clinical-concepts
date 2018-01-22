<h2>Abstract</h2>
The ability to find highly related clinical concepts is essential for many applications such as for hypothesis generation, query expansion for medical literature search, search results filtering, ICD-10 code filtering and many other applications. While manually constructed medical terminologies such as SNOMED CT can surface certain related concepts, these terminologies are inadequate as they depend on expertise of several subject matter experts making the terminology curation process open to geographic and language bias. In addition, these terminologies also provide no quantifiable evidence on how related the concepts are. In this work, we explore an unsupervised graphical approach to mine related concepts by leveraging the volume within large amounts of clinical notes. Our evaluation shows that we are able to use a data driven approach to discovering highly related concepts for various search terms including medications, symptoms and diseases.
<h2>Mining Related Concepts</h2>
The Concept-Graph is used to mine related clinical terminology. For example if the query term is `advair`, related concepts can be `singulair`, `combivent`, `inhaler`, `nebs`, etc.  The Concept-Graph is an undirected graph with each node representing a concept and the link between the nodes indicate a presence of relationship between two concepts. The results of this work was evaluated by experts in the medical field. 

<h2>Links</h2>
<li><a href="http://kavita-ganesan.com/wp-content/uploads/2017/07/Discovering_Related_Clinical_Concepts_Using_Large_.pdf">Paper</a>
<li><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5015701/">Journal link</a>
<li><a href="/clinical-stopwords.txt">stop words used</a>


<h2>Example Related Concepts</h2>
<h3>Concepts related to `chest pain`</h3>
<img src="https://github.com/kavgan/images/raw/master/chest_pain_concepts.png" alt="concepts related to chest pain" />

<h2>Citation</h2>
<pre>@Article{Ganesan2016,
author={Ganesan, Kavita
and Lloyd, Shane
and Sarkar, Vikren},
title={Discovering Related Clinical Concepts Using Large Amounts of Clinical Notes},
journal={Biomed Eng Comput Biol},
year={2016},
month={Sep},
day={07},
publisher={Libertas Academica},
volume={7},
number={Suppl 2},
pages={27-33},
note={becb-suppl.2-2016-027[PII]},
note={27656096[pmid]},
issn={1179-5972},
doi={10.4137/BECB.S36155},
url={http://www.ncbi.nlm.nih.gov/pmc/articles/PMC5015701/}
}

</pre>
