### On top of base serialization, renderers to various formats/ontologies

+++

### Basic CIDOC CRM Serialization

- Name
- LOD Links
- Place of Birth
- Date of Birth
- \>\> more planned
- \>\> ACDHs omnipot

+++

<pre><code class="XML" data-line-numbers="24-29|47-53|9-16|4-8">
<?xml version="1.0" encoding="UTF-8"?>
<rdf:RDF
   xmlns:cidoc="http://www.cidoc-crm.org/cidoc-crm/"
   xmlns:owl="http://www.w3.org/2002/07/owl#"
   xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
   xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
>
  <rdf:Description rdf:nodeID="N388433cf2353495cbbcb598c2f2e488b">
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E52_Time-Span"/>
    <cidoc:P82b_end_of_the_end rdf:datatype="http://www.w3.org/2001/XMLSchema#date">1947-10-26</cidoc:P82b_end_of_the_end>
    <cidoc:P82a_begin_of_the_begin rdf:datatype="http://www.w3.org/2001/XMLSchema#date">1947-10-26</cidoc:P82a_begin_of_the_begin>
  </rdf:Description>
  <rdf:Description rdf:about="https://apis.acdh-dev.oeaw.ac.at/apis/api2/entity/6700">
    <cidoc:P1_is_identified_by rdf:resource="https://apis.acdh-dev.oeaw.ac.at/appellation/place/6700"/>
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E53_Place"/>
    <rdfs:label xml:lang="en">Innsbruck</rdfs:label>
    <owl:sameAs rdf:resource="http://d-nb.info/gnd/4027096-8"/>
    <owl:sameAs rdf:resource="http://sws.geonames.org/2775220/"/>
    <cidoc:P168_place_is_defined_by rdf:datatype="geo:wktLiteral">Point( 11.39454 47.26266 )</cidoc:P168_place_is_defined_by>
  </rdf:Description>
  <rdf:Description rdf:about="https://apis.acdh-dev.oeaw.ac.at/appellation/birth/33836">
    <cidoc:P7_took_place_at rdf:resource="https://apis.acdh-dev.oeaw.ac.at/apis/api2/entity/21548"/>
    <rdfs:label xml:lang="de">Geburt von Rudolf Sinwel</rdfs:label>
    <cidoc:P4_has_time-span rdf:nodeID="N2cbfa1f73e7f40bd99d09c2c0635ea83"/>
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E67_Birth"/>
    <cidoc:P98_brought_into_life rdf:resource="https://apis.acdh-dev.oeaw.ac.at/apis/api2/entity/33836/"/>
  </rdf:Description>
  <rdf:Description rdf:about="https://apis.acdh-dev.oeaw.ac.at/apis/api2/entity/33836/">
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E21_Person"/>
    <owl:sameAs rdf:resource="http://d-nb.info/gnd/140744088"/>
    <cidoc:P1_is_identified_by rdf:nodeID="Nf5b68bb7d5bd494ab8b6172f375b44c2"/>
    <rdfs:label xml:lang="en">Rudolf Sinwel</rdfs:label>
  </rdf:Description>
  <rdf:Description rdf:nodeID="N2cbfa1f73e7f40bd99d09c2c0635ea83">
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E52_Time-Span"/>
    <cidoc:P82a_begin_of_the_begin rdf:datatype="http://www.w3.org/2001/XMLSchema#date">1865-04-05</cidoc:P82a_begin_of_the_begin>
    <cidoc:P82b_end_of_the_end rdf:datatype="http://www.w3.org/2001/XMLSchema#date">1865-04-05</cidoc:P82b_end_of_the_end>
    <rdfs:label>data['start_date']</rdfs:label>
  </rdf:Description>
  <rdf:Description rdf:about="https://apis.acdh-dev.oeaw.ac.at/apis/api2/entity/21548">
    <owl:sameAs rdf:resource="http://sws.geonames.org/2760634/"/>
    <rdfs:label xml:lang="en">Zell am See</rdfs:label>
    <cidoc:P168_place_is_defined_by rdf:datatype="geo:wktLiteral">Point( 12.79444 47.32556 )</cidoc:P168_place_is_defined_by>
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E53_Place"/>
    <cidoc:P1_is_identified_by rdf:resource="https://apis.acdh-dev.oeaw.ac.at/appellation/place/21548"/>
  </rdf:Description>
  <rdf:Description rdf:nodeID="Nf5b68bb7d5bd494ab8b6172f375b44c2">
    <rdfs:label xml:lang="en">Rudolf Sinwel</rdfs:label>
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E41_Appellation"/>
  </rdf:Description>
  <rdf:Description rdf:about="https://apis.acdh-dev.oeaw.ac.at/appellation/death/33836">
    <rdfs:label xml:lang="de">Tod von Rudolf Sinwel</rdfs:label>
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E69_Death"/>
    <cidoc:P7_took_place_at rdf:resource="https://apis.acdh-dev.oeaw.ac.at/apis/api2/entity/6700"/>
    <cidoc:P4_has_time-span rdf:nodeID="N388433cf2353495cbbcb598c2f2e488b"/>
    <cidoc:P100_was_death_of rdf:resource="https://apis.acdh-dev.oeaw.ac.at/apis/api2/entity/33836/"/>
  </rdf:Description>
  <rdf:Description rdf:about="https://apis.acdh-dev.oeaw.ac.at/appellation/place/21548">
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E41_Appellation"/>
    <rdfs:label xml:lang="en">Zell am See</rdfs:label>
  </rdf:Description>
  <rdf:Description rdf:about="https://apis.acdh-dev.oeaw.ac.at/appellation/place/6700">
    <rdfs:label xml:lang="en">Innsbruck</rdfs:label>
    <rdf:type rdf:resource="http://www.cidoc-crm.org/cidoc-crm/E41_Appellation"/>
  </rdf:Description>
</rdf:RDF>
</code></pre>

+++

### More To Come?

- Annotation of texts
- Provenance of data
- Affiliation with institutions
- ...

+++

### Factoid

- Statement X about person Y expressed by researcher Z backed by source S
- [ProsopogrAPhi](https://github.com/GVogeler/prosopogrAPhI) - JSON API
- easy to implement while allowing for some matching
- Definition in swagger
- contributions & ideas welcome on GitHub

+++


<pre><code class="JSON" data-line-numbers="4-16|17,22-30|54-77|106-119|134-153">
 "factoids": [
  {
   "createdBy": "TITLE export",
   "createdWhen": "2019-05-15T10:26:09.770Z",
   "id": "apis_person_33836",
   "person": {
    "id": "33836",
    "uris": [
     "http://d-nb.info/gnd/140744088"
    ]
   },
   "source": {
    "id": "TITLE",
    "metadata": "TITLE export"
   },
   "statements": [
    {
     "id": "Stmt33836_1",
     "name": "Sinwel, Rudolf"
    },
    {
     "date": {
      "label": "26.10.1947",
      "sortdate": "1947-10-26"
     },
     "id": "Stmt33836_2",
     "role": {
      "label": "stirbt"
     }
    },
    {
     "date": {
      "label": "5.4.1865",
      "sortdate": "1865-04-05"
     },
     "id": "Stmt33836_3",
     "role": {
      "label": "geboren"
     }
    },
    {
     "id": "Stmt33836_4",
     "role": {
      "label": "gender",
      "uri": "bio-crm:gender"
     },
     "statmentContent": [
      {
       "label": "male"
      }
     ]
    },
    {
     "id": "Stmt33836_5",
     "role": {
      "label": "profession"
     },
     "statementContent": [
      {
       "label": "Literatur, Buch- und Zeitungswesen",
       "uri": "apis_profession_type:128"
      },
      {
       "label": "Geisteswissenschaft",
       "uri": "apis_profession_type:149"
      },
      {
       "label": "Unterrichtswesen",
       "uri": "apis_profession_type:188"
      },
      {
       "label": "Geisteswissenschaft >> Heimatforscher, Schriftsteller und Lehrer",
       "uri": "apis_profession_type:1563"
      }
     ]
    },
    {
     "id": "Stmt33836_rel_33837",
     "role": {
      "label": "place of birth",
      "url": "http://127.0.0.1:8000/apis/api/vocabularies/personplacerelation/595/"
     },
     "statementContent": [
      {
       "label": "Zell am See",
       "uri": "https://apis.acdh.oeaw.ac.at/api2/entity/21548"
      }
     ]
    },
    {
     "id": "Stmt33836_rel_33838",
     "role": {
      "label": "place of death",
      "url": "http://127.0.0.1:8000/apis/api/vocabularies/personplacerelation/596/"
     },
     "statementContent": [
      {
       "label": "Innsbruck",
       "uri": "https://apis.acdh.oeaw.ac.at/api2/entity/6700"
      }
     ]
    }
   ]
  },
  {
   "createdBy": "MKaiser",
   "createdWhen": "2016-09-27",
   "id": "apis_person_33836_5",
   "person": {
    "id": "33836",
    "uris": [
     "http://d-nb.info/gnd/140744088"
    ]
   },
   "source": {
    "id": "APIS",
    "metadata": "APIS highlighter annotations rev. 17971 / 17986 / 18015 / 18019 / 17968 / 17974 / 17976 / 17980 / 17983 / 18011"
   },
   "statements": [
    {
     "id": "Stmt33836_rel_96481",
     "role": {
      "label": "war in Ausbildung >> war Student",
      "url": "http://127.0.0.1:8000/apis/api/vocabularies/personinstitutionrelation/5642/"
     },
     "statementContent": [
      {
       "label": "Universit\u00e4t Innsbruck",
       "uri": "https://apis.acdh.oeaw.ac.at/api2/entity/94158"
      }
     ]
    },
    {
     "id": "Stmt33836_rel_96491",
     "role": {
      "label": "war Mitarbeiter >> war Lehrer",
      "url": "http://127.0.0.1:8000/apis/api/vocabularies/personinstitutionrelation/5677/"
     },
     "statementContent": [
      {
       "label": "Kaiserlich-K\u00f6nigliche Kaiser-Franz-Josefs-Handelsakademie (Br\u00fcnn)",
       "uri": "https://apis.acdh.oeaw.ac.at/api2/entity/96488"
      },
      {
       "id": "Annotation_1313",
       "label": "g (\u00dast\u00ed nad Labem) und 1895\u20131916 als 
       Prof. an der <annotation>Handelsakad. in Br\u00fcnn</annotation> (Brno); 
       1917 krankheitshalber i. R. Trotz seiner "
      }
     ]
    },
    {
     "id": "Stmt33836_rel_96495",
     "role": {
      "label": "war Gr\u00fcnder von",
      "url": "http://127.0.0.1:8000/apis/api/vocabularies/personinstitutionrelation/5657/"
     },
     "statementContent": [
      {
       "label": "Tiroler Heimatbl\u00e4tter",
       "uri": "https://apis.acdh.oeaw.ac.at/api2/entity/94188"
</code></pre>
