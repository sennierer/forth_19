
---
@code[python code-scrollable](data/cidoc_mapping.py)
@snap[south span-100 text-09]
@[51-76](Place serialization)
@[52-54](return the URI, if place already exists)
@[52-54](return the URI, if place already exists)
@[56-67](place appellation)
@[68-69](spatial data)
@[70](sameAs)
@[10-14](function sameAs)
@snapend

+++?color=linear-gradient(180deg, #5289F7 18%, white 18%)
@title[Sidebar + Heading]

@snap[north h3-white]
### Omnipot
@snapend

@snap[north-east]
@css[title-note text-white](all together?)
@snapend

@snap[center span-100]
@ol[list-spaced-bullets list-boxed-bullets text-07]
- The Austrian Academy of Sciences was founded in 1847 @css[fragment](\>\> a LOT of legacy data in wild formats, using even wilder vocabularies and ontologies)
- interlink as much data as possible
- Idea of the omnipot:
	+ Start with (partial) mapping of data to CIDOC CRM
	+ Serialize the rest creating an ad hoc Ontology based on e.g. column- and table-names
	+ Use metaphacts/researchspace to find overlaps using temaples and fields
	+ and take the interlinking from there
@olend
@snapend

+++

@snap[midpoint span-100]
![Omnipot example](images/screen_Omnipot_localGraph.PNG)
@snapend
