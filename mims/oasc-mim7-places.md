---
description: 'OASC MIM7: Places'
---

# MIM7 - Places\*

## Status <a href="#mim1-contextinformationmanagement-goal" id="mim1-contextinformationmanagement-goal"></a>

| <p><span data-gb-custom-inline data-tag="emoji" data-code="1f4a1">💡</span></p><p>Work Item</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f9e9">🧩</span></p><p>Capabilities</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f3d7">🏗</span></p><p>Specification</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f469-2696">👩⚖</span></p><p>Governance</p> |
| :---------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------: |
|                                       :white\_check\_mark:                                      |                                        :white\_check\_mark:                                        |                                                                                                     |                                                                                                        |

## Background <a href="#mim1-contextinformationmanagement-goal" id="mim1-contextinformationmanagement-goal"></a>

MIM7 aims to provide Minimal Interoperability Mechanisms related to geo-temporal data. However, there are many existing geo-temporal data standards that are of relevance to cities and to propose the full list would not be compatible with the concept of MIMs. MIM7 is therefore being developed as a number of parts.

During the work on MIM7 it has become clear that there are considerable inconsistencies between MIM7 on one hand and MIM1 and MIM2 on the other. Those inconsistencies are related both to the scope of the respective MIMs, and also due to the fact that they are based on two different ecosystems of standards that do not seem to align at the moment. The geospatial world is strongly based on the OGC ecosystem of standards, whereas MIM1 & MIM2 are based on the ETSI ecosystem of standards. In order for the three MIMs to work together for a municipality this needs to align.

MIM7 Part 1 has been developed to address this issue.

## Requirements and Recommendations <a href="#mim1-contextinformationmanagement-goal" id="mim1-contextinformationmanagement-goal"></a>

**MIM7 Part 1** comprises two minimal requirements and two recommendations. Aligned with the Rules for the structure and drafting of International Standards endorsed by the ISO and OGC OGC (see sub-clause 5.3 of \[OGC 06-121r9]). The verb form “shall” indicates a requirement to be strictly followed to conform to this MIM. Recommendations, in turn, are based on good practices and ‘should’ not be strictly followed.

### Requirements:

1. Expose data through a service interface either through OGC WFS or OGC API features.
2. Ensure that all published features have unique identifiers that follow the requirements of the Inspire directive data specifications, chapter 14 Identifier management: [https://inspire.ec.europa.eu/documents/Data\_Specifications/D2.5\_v3.4rc3.pdf](https://inspire.ec.europa.eu/documents/Data\_Specifications/D2.5\_v3.4rc3.pdf) or the work of W3C in the data on the web best practice: [https://www.w3.org/TR/dwbp/#DataIdentifiers](https://www.w3.org/TR/dwbp/#DataIdentifiers)

### Recomendations:

1. If data is shared through WFS, a proxy OGC API could be considered on top of that.
2. The use of standard-based encoding such as GeoJSON, GML, GeoPackage and CityGML.

## Rationale

* MIMs are Minimal Interoperability Mechanism that should be relatively easy for cities and communities to achieve.
* The Inspire Directive, leveraging data sharing, description principles and standards like WMS and WFS, has transformed the European geospatial landscape in the last decade, and is making geodata interoperable throughout Europe.
* A main recognised challenge for European municipalities is to integrate and transfer data between internal and external IT systems.
* That most municipalities with minimal effort can establish OGC services like WFS, WMS and OGC APIs with minor investments.
* Geodata-based features need to be accessed as linked data by many IT- and IoT-systems, and over a long period of time, thus persistent identifiers are vital for the integrity of IT- and IoT-systems over time.
* For municipalities with more technical and financial strength the OGC ecosystem of standards for both geodata and sensor data are a good basis for more complex services.

Understanding that:

* The Feature and Thing (in OGC and entity in NGSI-LD) is the essential item for integrating between the two ecosystems of standards.
* That context will be created from data from various sources, for example geodata and building information models.
* A main challenge for municipalities will be to both establish and maintain the number of connections between NGSI-LD entities and their representations in the SDI (identifiers, existence, location) over time and that this process will need to be automated, most probably based on geospatial techniques like geodata or in the more complex case a digital twin.

Specifies how to share spatial (and spatio-temporal) data, make them interoperable with, within, and between systems and territories. This goes from static data about assets such as street lights, buildings, and streets to spatio-temporal data from sensors. The purpose of this Minimal Interoperability Mechanism (MIM) is to make this data and the way it is shared interoperable across cities, but also among stakeholders within the same city. This MIM will also provide input to [MIM2 Data models](oasc-mim-2-data-models.md), in particular regarding data which has an explicit geospatial dimension.

## MIM7 Working Group members

Representatives of the following organisations and initiatives:

* INSPIRE, Open Geospatial Consortium (OGC).
* Cities of Athens, Gothenburg, Swedish Association of Local Authorities and Regions (SALAR), Vienna.
* European Commission: DG Connect, DG Digit and DG JRC.

## Recommendations approved at the OASC Annual Summit on June 7th 2022:

* To agree that MIM7 be developed as a series of Parts, each focusing on a particular aspect of geo-temporal data.
* To agree the proposed updated technical specifications for MIM7 Part 1 and for a programme of testing and review to be carried out in the new work year.
