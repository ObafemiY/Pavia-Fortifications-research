# Lombardy Cities Linked Open Data (LOD)

This repository contains Linked Open Data (LOD) about cities in the Lombardy region of Italy and their famous cultural traditions. This data is structured in JSON-LD format, adhering to Linked Data standards, making it accessible and interoperable with other LOD datasets worldwide.

## Project Description

The Lombardy region is known for its rich cultural heritage and vibrant local traditions. This dataset provides information on 12 cities in Lombardy, detailing each city’s unique cultural events or traditions, along with the provincial location of each city.

This Linked Open Data project aims to support:
- **Cultural and tourism research**
- **Educational purposes**
- **Data linking and integration** with other LOD projects

## Data Overview

The data is structured in [JSON-LD](https://json-ld.org/) format. Each entry contains the following attributes:
- **City Name**: The name of the city.
- **Location**: The city’s provincial location within Lombardy.
- **Tradition**: The unique cultural tradition associated with the city.

### Example Data Entry

```json
{
  "@id": "https://example.org/data/Milan",
  "name": "Milan (Milano)",
  "location": "Metropolitan City of Milan",
  "tradition": "Milan Fashion Week — Held twice a year, this is one of the most prestigious fashion events worldwide, showcasing Italian and international fashion designers."
   "sameAs": [
        "https://dbpedia.org/resource/Milan",
        "https://www.wikidata.org/wiki/Q490"
      ]
}
