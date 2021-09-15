### Relation based

- 5 entities \>\> person, place, institution, work and event<!-- .element: class="fragment" style="font-size:0.7em"-->
- relations between them \>\> time-span, relation type<!-- .element: class="fragment" style="font-size:0.7em"-->
- 1-n texts \>\> attached to the entities<!-- .element: class="fragment" style="font-size:0.7em"-->
- offset annotations \>\> pointing to text & entity/relation<!-- .element: class="fragment" style="font-size:0.7em"-->
- provenance<!-- .element: class="fragment" style="font-size:0.7em"-->

+++

<pre><code class="JSON" data-line-numbers="4-6,10-11|18,21-23,25|57,75-76|383-384,386|388-398|400-405">
  "id": 33836,
  "url": "http://127.0.0.1:8000/apis/api2/entity/33836/",
  "name": "Sinwel",
  "start_date": "1865-04-05",
  "end_date": "1947-10-26",
  "start_date_written": "5.4.1865",
  "end_date_written": "26.10.1947",
  "status": "",
  "first_name": "Rudolf",
  "gender": "male",
  "uris": [
    {
      "id": 24130,
      "uri": "http://d-nb.info/gnd/140744088"
    }
  ],
  "labels": [
    {
      "id": 10075,
      "label": "Sinwel, Rudolf; Ps. Rolf Kurz",
      "isoCode_639_3": "deu",
      "label_type": {
        "id": 598,
        "name": "Name laut ÖBL XML"
      }
    },
    {
      "id": 10076,
      "label": "Rolf Kurz",
      "isoCode_639_3": "deu",
      "label_type": {
        "id": 430,
        "name": "Pseudonym"
      }
    }
  ],
  "revisions": [],
  "collection": [
    {
      "id": 7,
      "name": "ÖBL complete import test 30.8.16"
    },
    {
      "id": 17,
      "name": "Mittelalter 7.9.2016"
    },
    {
      "id": 52,
      "name": "Lyon export test data"
    },
    {
      "id": 77,
      "name": "Rumpolt GeWi Stichprobe"
    }
  ],
  "profession": [
    {
      "id": 128,
      "name": "Literatur, Buch- und Zeitungswesen",
      "label": "Literatur, Buch- und Zeitungswesen"
    },
    {
      "id": 149,
      "name": "Geisteswissenschaft",
      "label": "Geisteswissenschaft"
    },
    {
      "id": 188,
      "name": "Unterrichtswesen",
      "label": "Unterrichtswesen"
    },
    {
      "id": 1563,
      "name": "Heimatforscher, Schriftsteller und Lehrer",
      "label": "Geisteswissenschaft >> Heimatforscher, Schriftsteller und Lehrer"
    }
  ],
  "entity_type": "Person",
  "relations": {
    "events": [],
    "institutions": [
      {
        "id": 96481,
        "relation_type": {
          "url": "http://127.0.0.1:8000/apis/api/vocabularies/personinstitutionrelation/5642/",
          "label": "war in Ausbildung >> war Student"
        },
        "annotation": [],
        "revisions": [
          {
            "id": 17971,
            "date_created": "2016-09-27T11:19:42Z",
            "user_created": "MKaiser"
          }
        ],
        "target": {
          "id": 94158,
          "url": "undefined",
          "name": "Universität Innsbruck",
          "start_date": "1669-01-01",
          "end_date": null,
          "uris": [
            {
              "id": 63915,
              "uri": "http://d-nb.info/gnd/36165-3"
            }
          ],
          "labels": [
            {
              "id": 32218,
              "label": "Università di Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32219,
              "label": "Universitas Leopoldino-Franciscea Oenipontana",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32220,
              "label": "LFU",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32221,
              "label": "Universität Innsbruck. Senat",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32222,
              "label": "Alpen-Universität",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32223,
              "label": "Université Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32224,
              "label": "Università Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32225,
              "label": "K.K. Leopold-Franzens-Universität",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32226,
              "label": "Alpenuniversität",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32227,
              "label": "Kaiserlich-Königliche Universität Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32228,
              "label": "Akademischer Senat (Innsbruck)",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32229,
              "label": "Deutsche Alpen-Universität",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32230,
              "label": "University Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32231,
              "label": "K.K. Universität Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32232,
              "label": "Alma Mater Oenipontana",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32233,
              "label": "Université d'Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32234,
              "label": "Kaiserliche Königliche Universität Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32235,
              "label": "Leopold-Franzens-Universität Innsbruck. Akademischer Senat",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32236,
              "label": "Universität Innsbruck. Akademischer Senat",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32237,
              "label": "University of Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32238,
              "label": "Leopold-Franzens-Universität",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32239,
              "label": "Innsbruck University",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32240,
              "label": "Leopold-Franzens-Universität Innsbruck",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32241,
              "label": "Deutsche Alpenuniversität",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32242,
              "label": "Deutsche Alpen-Universität (Innsbruck)",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32243,
              "label": "Akademischer Senat (Universität Innsbruck)",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            },
            {
              "id": 32244,
              "label": "Universitas Oenipontana",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 433,
                "name": "alternative name"
              }
            }
          ],
          "revisions": [
            {
              "id": 209295,
              "date_created": "2018-04-26T09:44:42Z",
              "user_created": "ABernad"
            },
            {
              "id": 9365,
              "date_created": "2016-09-12T10:15:02Z",
              "user_created": "MKaiser"
            }
          ],
          "start_date_written": "1669",
          "end_date_written": null,
          "status": "",
          "collection": [
            {
              "id": 17,
              "name": "Mittelalter 7.9.2016"
            },
            {
              "id": 52,
              "name": "Lyon export test data"
            }
          ],
          "entity_type": "Institution"
        }
      },
      {
        "id": 96491,
        "relation_type": {
          "url": "http://127.0.0.1:8000/apis/api/vocabularies/personinstitutionrelation/5677/",
          "label": "war Mitarbeiter >> war Lehrer"
        },
        "annotation": [
          {
            "id": 1313,
            "user": "sennierer",
            "annotation": "Handelsakad. in Brünn",
            "text": "g (Ústí nad Labem) und 1895–1916 als Prof.
            an der <annotation>Handelsakad. in Brünn</annotation> (Brno); 1917
            krankheitshalber i. R. Trotz seiner ",
            "string_offset": "470-491",
            "text_url": "http://127.0.0.1:8000/apis/api/metainfo/text/15295/"
          }
        ],
        "revisions": [
          {
            "id": 17986,
            "date_created": "2016-09-27T11:25:26Z",
            "user_created": "MKaiser"
          }
        ],
        "target": {
          "id": 96488,
          "url": "undefined",
          "name": "Kaiserlich-Königliche Kaiser-Franz-Josefs-Handelsakademie (Brünn)",
          "start_date": null,
          "end_date": null,
          "uris": [
            {
              "id": 65192,
              "uri": "http://d-nb.info/gnd/401767-5"
            }
          ],
          "labels": [],
          "revisions": [
            {
              "id": 18221,
              "date_created": "2016-09-27T13:28:31Z",
              "user_created": "MKaiser"
            },
            {
              "id": 17995,
              "date_created": "2016-09-27T11:25:26Z",
              "user_created": "MKaiser"
            }
          ],
          "start_date_written": "",
          "end_date_written": "",
          "status": "",
          "collection": [
            {
              "id": 17,
              "name": "Mittelalter 7.9.2016"
            },
            {
              "id": 52,
              "name": "Lyon export test data"
            }
          ],
          "entity_type": "Institution"
        }
      },
      {
        "id": 96495,
        "relation_type": {
          "url": "http://127.0.0.1:8000/apis/api/vocabularies/personinstitutionrelation/5657/",
          "label": "war Gründer von"
        },
        "annotation": [
          {
            "id": 1315,
            "user": "sennierer",
            "annotation": "Tiroler Heimatblätter",
            "text": " Auf seine Initiative ging 1920 die Gründung der „<annotation>Tiroler Heimatblätter</annotation>“ (gem. mit Eduard Lippott) zurück, deren Schriftl",
            "string_offset": "859-880",
            "text_url": "http://127.0.0.1:8000/apis/api/metainfo/text/15295/"
          }
        ],
        "revisions": [
          {
            "id": 18015,
            "date_created": "2016-09-27T11:26:46Z",
            "user_created": "MKaiser"
          }
        ],
        "target": {
          "id": 94188,
          "url": "undefined",
          "name": "Tiroler Heimatblätter",
          "start_date": "1924-01-01",
          "end_date": "1941-01-01",
          "uris": [
            {
              "id": 63925,
              "uri": "https://apis.eos.arz.oeaw.ac.at/entity/94188"
            }
          ],
          "labels": [],
          "revisions": [
            {
              "id": 9321,
              "date_created": "2016-09-12T09:30:32Z",
              "user_created": "MKaiser"
            }
          ],
          "start_date_written": "1924",
          "end_date_written": "1941",
          "status": "",
          "collection": [
            {
              "id": 17,
              "name": "Mittelalter 7.9.2016"
            },
            {
              "id": 52,
              "name": "Lyon export test data"
            }
          ],
          "entity_type": "Institution"
        }
      }
    ],
    "persons": [
      {
        "id": 96497,
        "relation_type": {
          "url": "http://127.0.0.1:8000/apis/api/vocabularies/personpersonrelation/5421/",
          "label": "rezipierte"
        },
        "annotation": [],
        "revisions": [
          {
            "id": 18019,
            "date_created": "2016-09-27T11:34:42Z",
            "user_created": "MKaiser"
          }
        ],
        "target": {
          "id": 48138,
          "url": "undefined",
          "name": "Prem",
          "start_date": "1853-10-28",
          "end_date": "1920-04-26",
          "uris": [
            {
              "id": 33780,
              "uri": "http://d-nb.info/gnd/116282339"
            }
          ],
          "labels": [
            {
              "id": 15922,
              "label": "Prem, Simon (Marian); Ps. Christian Ewald",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 598,
                "name": "Name laut ÖBL XML"
              }
            },
            {
              "id": 15923,
              "label": "Marian",
              "isoCode_639_3": "deu",
              "label_type": {
                "id": 597,
                "name": "alternative Namensform"
              }
            },
</code></pre>
