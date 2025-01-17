# Ocean Program

Repository for the [Ocean Program](https://www.openearth.org/projects/ocean-program) at the Open Earth Foundation.
![Logotype Versions_Vertical Version](https://user-images.githubusercontent.com/107511484/204840228-cc408d2a-79ae-4818-b09d-0903bb4831a6.png)

## Overview

Open Earth Foundation launched its Ocean Program to **build the digital architecture needed to conserve 30% of the global ocean** and solve the environmental problems that negatively affect it. The Ocean Program leverages the Foundation’s expertise in emerging digital technologies, including AI and blockchain, to **scale marine conservation and outcome-based conservation finance**.


## Problem Statement

There exists few financial mechanisms to protect ocean health that scale up to what we need to do to conserve the ocean. Currently, many marine conservation efforts rely on philanthropy, which is not always scalable, or are turning towards carbon markets, which were not designed for ocean solutions and which focus primarily on climate. Efforts to protect the ocean and its ecosystems are however very important for a variety of ocean health metrics, such as marine biodiversity or marine pollution. Not only do these issues affect marine life, but they also affect human health, such as through seafood, for example.

Given the specificities of ocean systems and their complexities, we need to **build adequate financial mechanisms for the protection and restoration of marine ecosystems**.

To this end, we have yet to leverage the full potential of digital technologies, such as artificial intelligence, blockchain, big data and IoT to scale ocean conservation. The rise and maturity of these emerging technologies provide opportunities for existing (e.g. Regen) and new platforms to finance and scale ocean conservation.

## Our Approach

Scaling marine conservation and results-based conservation financing by leveraging the Open Earth Foundation's expertise in emerging digital technologies, including AI and blockchain.

Specifically, we are working on **a new class of marine ecosystem credits (MEC) that center around scientific integrity, equity and scalability ([whitepaper here](https://uploads-ssl.webflow.com/62192ceb9199b3dd08431a6b/6371df5b39109b348b188447_whitepaper.pdf))**. We are building the digital infrastructure and developing protocols and methodologies to support these efforts. 

In parallel, we are also developing **free open-source tools to help lower the cost of environmental assessments in the ocean** and to enable solutions to scale across vast swathes of the ocean. 

Furthermore, we are researching and developing methodologies to apply Decentralized Identifiers (DIDs) and Verifiable Credentials (VCs) in the process of credit issuance and validation.

## Our Pilot Plan

We are building a proof-of-concept through a pilot field experiment in partnership with [Cocos Island National Park in Costa Rica (ACMC)](https://youtu.be/sHXEAwo0qCI)
![shutterstock_392070391-1200x803](https://user-images.githubusercontent.com/107511484/204839803-78caf2cc-cce5-43b7-a2fe-bf578ab8d6c0.jpeg)

To develop a scalable system of marine biodiversity credits, **we must first define what the credit unit is**. Our goal is to build a “global scale” of marine biodiversity that is scientifically sound, that is equitable and that helps support the financial efforts going into conservation, meaning it must be scalable. We strive to create a metric that would include the ecological values of the ecosystems within the acreage—or 1 $km^2$—of ocean protected.

## Content and Uses

1. This series of notebooks aims to calculate different marine biodiversity indices:
- WEGE: Weighted Endemism including Global Endangerment index
- STAR: Species Threat Abatement and Recovery
- other Marine Biodiversity Units
2. Documentation about our testing work
3. Maps and relevant documentation about our pilot plan in Coco's Marine Conservation Area in Costa Rica

## Data needed for this project

**IUCN RedList**
The data was output by `ACMC_IUCN_step1_curatedata.ipynb`. It has been gathered on our [Google Drive](https://drive.google.com/drive/folders/1yElWSaK0tWvlyDvjNUSpqnnwEJGMGdPX?usp=sharing) under a temporary folder that accompagnies the GitHub repository: 

`Ocean Program > data > to download for gh > ACMC_IUCN_data`

Source: [IUCN Red List](https://www.iucnredlist.org/resources/spatial-data-download)

**Geospatial Data to ACMC**

`Ocean Program > data > to download for gh > geospatial_input`

Source: [SNIT CR](https://www.snitcr.go.cr/)

**Bathymetry Data**

`Ocean Program > data > to download for gh > Bathymetry_Data`

Source: [GEBCO](https://www.gebco.net/)

## Installation
```bash
- Geopandas
- Numpy
- Pandas
- Glob
- Shapely.geometry
- Fiona
- Seaborn
```

```bash
OEF Funtions
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Our Team
- Margaux Filippi
- Maureen Fonseca (maureen@openearth.org)
- Ando Shah (ando@openearth.org)

## License
[OEF](https://www.openearth.org)

## Question / Comments
maureen@openearth.org

<details>
  <summary> To do</summary>
  
  ### Repository
  - [x] set up the [docs](https://github.com/Open-Earth-Foundation/oceanprogram/tree/main/docs) folder  
  - [ ] we need to add a proper .gitignore
  - [ ] we need to add a proper license
</details>
