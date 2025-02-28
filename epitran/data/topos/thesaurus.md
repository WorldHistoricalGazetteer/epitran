# TOPOS

**T**oponymic **O**perations and **P**rocessing for **O**ntological **S**emantics

An initiative by the [World Historical Gazetteer](https://whgazetteer.org/) to enhance place name indexing across languages, scripts, and time, by extracting semantic meaning.

---

Many place names contain elements that indicate or describe geographic features, settlement types, or directional cues, for example:

- **Chipping Norton** = *cēping* (market) + *norð* (north) + *tūn* (enclosure) *(Old English)*
- **Innsbruck** = *Inn* (river name) + *Bruck* (bridge) *(German)*
- **Beograd** = *Beli* (white) + *Grad* (fortress) *(Serbian)*
- **Kirkjubøur** = *Kirkja* (church) + *Bøur* (farm) *(Faroese)*
- **松山** = *松* (pine tree) + *山* (mountain) *(Japanese)*
- **Llanfairpwllgwyngyll** = *Llan* (parish/church) + *Fair* (St. Mary) + *Pwll* (pool) + *Gwyn* (white) + *Gyll* (hazel) *(Welsh)*
- **Новгород** = *Нов* (new) + *город* (city) *(Russian)*

By identifying **_commonly-occurring_** toponymic elements in different languages and linking them to a controlled vocabulary of **semantic classes**, we can improve place name matching and analysis across languages and historical sources. The classes we have chosen for our **Thesaurus** (below) are based on **Wikidata IDs**, which represent concepts such as "religious building" (Q24398318), "bridge" (Q12280), and "direction" (Q2151613). **We welcome suggestions for expanding and refining our Thesaurus to better reflect linguistic diversity and historical usage.**

Historical and regional variation in the spelling of toponymic elements is accounted for, to some extent, by encoding phonetic rather than orthographic forms. For further technical details please see [here](https://github.com/WorldHistoricalGazetteer/place/issues/19).

## HELP!

To build and refine this system, we need the help of linguists. **If you have expertise in a language or historical corpus, we invite you to contribute tables of commonly-occurring toponymic elements grouped by their corresponding semantic classes.** Please follow this [Example](https://github.com/WorldHistoricalGazetteer/epitran/edit/toponymic-linguistics/epitran/data/topos/eng.md) and send to whgazetteer@gmail.com.

---

*Changes made to the tables in this file will invalidate any embeddings generated previously.*

### Settlements and Human-Made Structures
| Wikidata ID  | Name                 | Description |
|-------------|----------------------|-------------|
| Q486972     | Human settlement      | A place where people live |
| Q1209537    | Building              | A structure with a roof and walls, such as a house, school, store, or factory |
| Q24398318   | Religious building    | A building used for religious activities, such as a church, mosque, temple, or synagogue |
| Q1549591    | Market                | Location of a market or trading place |

### Natural Landforms
| Wikidata ID  | Name                 | Description |
|-------------|----------------------|-------------|
| Q8502       | Mountain              | A large natural elevation of the earth's surface rising abruptly from the surrounding level |
| Q571        | Island                | Any piece of land surrounded by water |
| Q170925     | Desert                | A barren area of land with little precipitation |

### Water Bodies and Features
| Wikidata ID  | Name                 | Description |
|-------------|----------------------|-------------|
| Q43229      | River                 | A natural flowing watercourse, usually freshwater, flowing towards an ocean, sea, lake, or another river |
| Q23442      | Lake                  | A large body of water surrounded by land |
| Q133506     | Beach                 | A pebbly or sandy shore, especially by the ocean between high- and low-water marks |

### Vegetation and Natural Areas
| Wikidata ID  | Name                 | Description |
|-------------|----------------------|-------------|
| Q168555     | Forest                | A large area covered chiefly with trees and undergrowth, or a historical hunting ground |
| Q33857      | Park                  | An area of natural, semi-natural or planted space set aside for human enjoyment and recreation |

### Infrastructure and Pathways
| Wikidata ID  | Name                 | Description |
|-------------|----------------------|-------------|
| Q11442      | Road                  | An identifiable route, way or path between two or more places |
| Q12280      | Bridge                | Structure that spans and provides a passage over a road, railway, river, or some other obstacle |

### Cultural and Historical Sites
| Wikidata ID  | Name                 | Description |
|-------------|----------------------|-------------|
| Q28637634   | Archaeological site   | A place (or group of physical sites) in which evidence of past activity is preserved (either prehistoric, historic, or contemporary) |

### Miscellaneous
| Wikidata ID  | Name                 | Description |
|-------------|----------------------|-------------|
| Q54113      | Color                 | A colour used to describe a geographical feature |
| Q2151613	  | Relative direction    | A directional component, such as `north`, `south`, `east`, or `west`, used in place names |
| Q2633778    | Elevation             | Commonly used in toponyms as a relative measure, for example `upper` or `lower` |
| Q322481     | Size                  | Commonly used in toponyms as a relative measure, for example `great` or `little` |

