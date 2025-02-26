## TOPOS Thesaurus

### Purpose:

TOPOS is designed to add semantic information to the representation of place names. This means it helps to capture the meaning or concept associated with a place, rather than just its phonetic sounds.
This semantic information is encoded as "one-hot semantic vector embeddings." These are essentially vectors where each element corresponds to a specific concept from the thesaurus, and the value of the element (1 or 0) indicates whether that concept is present or absent in the place name.

This semantic embedding can then be used in a vector index along with other phonetic embeddings to improve the accuracy and depth of place name matching and analysis.

### Structure:

The thesaurus consists of a controlled vocabulary of Wikidata QIDs (identifiers for Wikidata items). These QIDs represent various geographic concepts, such as "human settlement," "mountain," "market," etc.
Each QID is associated with a language-specific Markdown file (*.md). These files contain lists of common toponymic elements (parts of place names) that are related to the concept represented by the QID.
The phonetic information (IPA transcriptions) of these toponymic elements is extracted from the Markdown files and stored in a JSON file (TOPOS.json).
This information is then used to generate the one-hot semantic embeddings for toponyms.

*QIDs may be added to the **end** of the table. Reordering of the table would invalidate any embeddings generated previously.*

---

| Wikidata ID | Name                  | Description |
|------------|----------------------|-------------|
| Q486972    | Human settlement      | A place where people live |
| Q8502      | Mountain              | A large natural elevation of the earth's surface rising abruptly from the surrounding level |
| Q1549591   | Market                | Location of a market or trading place |
| Q54113     | Color                 | A colour used to describe a geographical feature |
| Q43229     | River                 | A natural flowing watercourse, usually freshwater, flowing towards an ocean, sea, lake or another river |
| Q168555    | Forest                | A large area covered chiefly with trees and undergrowth |
| Q23442     | Lake                  | A large body of water surrounded by land |
| Q571       | Island                | Any piece of land surrounded by water |
| Q28637634  | Archaeological site   | A place (or group of physical sites) in which evidence of past activity is preserved (either prehistoric or historic or contemporary) |
| Q1209537   | Building              | A structure with a roof and walls, such as a house, school, store, or factory |
| Q33857     | Park                  | An area of natural, semi-natural or planted space set aside for human enjoyment and recreation |
| Q11442     | Road                  | An identifiable route, way or path between two or more places |
| Q133506    | Beach                 | A pebbly or sandy shore, especially by the ocean between high- and low-water marks |
| Q170925    | Desert                | A barren area of land with little precipitation |
