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

By identifying **_commonly-occurring_** toponymic elements in different languages and linking them to a controlled vocabulary of **semantic classes**, we can improve place name matching and analysis across languages and historical sources. The classes we have chosen for our **Thesaurus** (below) are based on **BabelNet identifiers**, which represent concepts such as "religious building" ([bn:00045013n](https://babelnet.org/synset?id=bn:00045013n&lang=EN)), "bridge" ([bn:00013077n](https://babelnet.org/synset?id=bn:00013077n&lang=EN)), and "north" ([bn:00029051n](https://babelnet.org/synset?id=bn:00029051n&lang=EN)). **We welcome suggestions for expanding and refining our Thesaurus to better reflect linguistic diversity and historical usage.**

Historical and regional variation in the spelling of toponymic elements is accounted for, to some extent, by encoding phonetic rather than orthographic forms. For further technical details please see [here](https://github.com/WorldHistoricalGazetteer/place/issues/19).

## HELP!

To build and refine this system, we need the help of linguists. **If you have expertise in a language or historical corpus, we invite you to contribute tables of commonly-occurring toponymic elements grouped by their corresponding semantic classes.** Please make a table following this [example](https://github.com/WorldHistoricalGazetteer/epitran/blob/toponymic-linguistics/epitran/data/topos/eng.md) and send to whgazetteer(_at_)gmail(_dot_)com.

---

| BabelNet ID | Name | Description |
|---|---|---|
| _Settlements and Human-Made Structures_ |  |  |
| [bn:00070726n](https://babelnet.org/synset?id=bn:00070726n&lang=EN) | settlement | A place where people establish a community, ranging from small villages to large cities. |
| [bn:00013722n](https://babelnet.org/synset?id=bn:00013722n&lang=EN) | building | A constructed edifice with walls and a roof, designed for shelter or various activities. |
| [bn:00045013n](https://babelnet.org/synset?id=bn:00045013n&lang=EN) | religious building | A structure dedicated to religious worship or spiritual practices, such as churches, mosques, or temples. |
| [bn:00053461n](https://babelnet.org/synset?id=bn:00053461n&lang=EN) | market | A designated location where goods and services are bought and sold, often a public square or building. |
| [bn:00016570n](https://babelnet.org/synset?id=bn:00016570n&lang=EN) | castle | A large fortified residence or stronghold, historically used by nobility and military forces. |
| _Natural Landforms_ |  |  |
| [bn:00044141n](https://babelnet.org/synset?id=bn:00044141n&lang=EN) | hill | A natural elevation of land, rising above the surrounding terrain. |
| [bn:00047612n](https://babelnet.org/synset?id=bn:00047612n&lang=EN) | island | A landmass completely surrounded by water, smaller than a continent. |
| [bn:00026519n](https://babelnet.org/synset?id=bn:00026519n&lang=EN) | desert | An arid region characterized by low rainfall, sparse vegetation, and extreme temperatures. |
| _Water Bodies and Features_ |  |  |
| [bn:00009263n](https://babelnet.org/synset?id=bn:00009263n&lang=EN) | beach | A shoreline area consisting of sand, pebbles, or rocks, typically bordering a body of water. |
| [bn:00067948n](https://babelnet.org/synset?id=bn:00067948n&lang=EN) | river | A natural watercourse flowing towards an ocean, lake, or another river, often freshwater. |
| [bn:00049709n](https://babelnet.org/synset?id=bn:00049709n&lang=EN) | lake | A large body of water enclosed by land, typically freshwater or saltwater. |
| [bn:00064201n](https://babelnet.org/synset?id=bn:00064201n&lang=EN) | spring | A natural source of groundwater emerging from the Earth's surface. |
| [bn:00005204n](https://babelnet.org/synset?id=bn:00005204n&lang=EN) | spa | A location known for mineral springs or therapeutic bathing, often a health resort. |
| _Vegetation and Natural Areas_ |  |  |
| [bn:00035868n](https://babelnet.org/synset?id=bn:00035868n&lang=EN) | woodland | An area dominated by trees and undergrowth, providing habitat for various flora and fauna. |
| [bn:00043448n](https://babelnet.org/synset?id=bn:00043448n&lang=EN) | heath | A tract of wasteland; uncultivated land with sandy soil and scrubby vegetation. |
| _Infrastructure and Pathways_ |  |  |
| [bn:00067975n](https://babelnet.org/synset?id=bn:00067975n&lang=EN) | road | A route between locations. |
| [bn:00013077n](https://babelnet.org/synset?id=bn:00013077n&lang=EN) | bridge | A structure spanning a physical obstacle, facilitating passage over it. |
| _Cultural and Historical Sites_ |  |  |
| [bn:00005410n](https://babelnet.org/synset?id=bn:00005410n&lang=EN) | archaeological site | A location where evidence of past human activity is preserved. |
| _Miscellaneous_ |  |  |
| [bn:00113424a](https://babelnet.org/synset?id=bn:00113424a&lang=EN) | upper | Indicating a higher position or elevation. |
| [bn:00107238a](https://babelnet.org/synset?id=bn:00107238a&lang=EN) | lower | Indicating a lower position or elevation. |
| [bn:00098343a](https://babelnet.org/synset?id=bn:00098343a&lang=EN) | big | Indicating a large size or extent. |
| [bn:00106773a](https://babelnet.org/synset?id=bn:00106773a&lang=EN) | small | Indicating a limited size or extent. |
| [bn:00029051n](https://babelnet.org/synset?id=bn:00029051n&lang=EN) | north | The cardinal direction located at 0 degrees on a compass. |
| [bn:00029053n](https://babelnet.org/synset?id=bn:00029053n&lang=EN) | south | The cardinal direction located at 180 degrees on a compass. |
| [bn:00029050n](https://babelnet.org/synset?id=bn:00029050n&lang=EN) | east | The cardinal direction located at 90 degrees on a compass. |
| [bn:00029054n](https://babelnet.org/synset?id=bn:00029054n&lang=EN) | west | The cardinal direction located at 270 degrees on a compass. |
| [bn:00017120n](https://babelnet.org/synset?id=bn:00017120n&lang=EN) | middle | Indicating a central or intermediate position. |
