+++?color=linear-gradient(180deg, #5289F7 18%, white 18%)
@title[Sidebar + Heading]

@snap[north h3-white]
### Relation based
@snapend

@snap[north-east]
@css[title-note text-white](APIS datamodel)
@snapend

@snap[south span-100 text-09]
@ul[list-spaced-bullets]
- 5 entities @css[fragment](\>\> person, place, institution, work and event)
- relations between them @css[fragment](\>\> time-span, relation type)
- 1-n texts @css[fragment](\>\> attached to the entities)
- offset annotations @css[fragment](\>\> pointing to text & entity/relation)
- provenance
@ulend
@snapend

---

@code[json](data/api2_json.json)

@snap[south span-100]
@[4-6,10-11,zoom-18](metadata)
@[18,21-23,25,zoom-14](Labels)
@[57,75-76,zoom-10](profession labels)
@[383-384,386,zoom-13](relations)
@[388-398](annotations)
@[400-405,zoom-13](revisions)
@snapend
