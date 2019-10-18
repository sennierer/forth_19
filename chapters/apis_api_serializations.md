---
@snap[midpoint span-100 text-black]
### On top of base serialization, renderers to various formats/ontologies
@snapend

+++?color=linear-gradient(180deg, #5289F7 18%, white 18%)
@snap[north span-100 h3-white]
### Basic CIDOC CRM Serialization
@snapend

@snap[south span-100]
@ul[list-spaced-bullets text-09]
- Name
- LOD Links
- Place of Birth
- Date of Birth
- \>\> more planned
- \>\> ACDHs omnipod
@ulend
@snapend

+++
@code[XML code-scrollable](data/cidoc_serialization_v2.xml)
@snap[south span-100 text-09]
@[28-33](Basic metadata)
@[51-57](Death event)
@[13-20](related place)
@[8-12](time span)
@snapend

+++
@code[xml code-scrollable](data/tei_serialization.xml)
@snap[south span-100 text-09]
@[19-27](Metadata)
@[32-36](Relations to other entities)
@[51](LOD links)
@snapend

+++?color=linear-gradient(180deg, #5289F7 18%, white 18%)

@snap[north h3-white]
### More To Come
@snapend

@snap[midpoint span-100]
@ul[list-spaced-bullets]
- Links to vocabularie entries
- Annotation of texts
- ...
@ulend
@snapend

+++?color=linear-gradient(180deg, #5289F7 18%, white 18%)

@snap[north span-100 h3-white]
### ProsopogrAPhI Serialization
@snapend

@snap[south span-100]
@ul[list-spaced-bullets text-09]
- [ProsopogrAPhi](https://github.com/GVogeler/prosopogrAPhI)
- Created by Georg Vogeler & colleagues
- Based on the idea of factoids
- easy to implement while allowing for some matching
- Definition in swagger
- contributions & ideas welcome on GitHub
@ulend
@snapend

+++
@code[json code-scrollable](data/prosop_serialization.json)
@snap[south span-100 text-09]
@[4-16](Metadata on person and source)
@[17,22-30](list of statenments about person, e.g. birth)
@[54-77](several statmentContents in one statement)
@[106-119](new factoid for staments created by user, including revisions)
@[134-153](statement including annotations of biographical text)
@snapend
