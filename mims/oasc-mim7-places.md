---
description: 'OASC MIM7: Places'
---

# MIM7 - Places

## Status <a href="#mim1-contextinformationmanagement-goal" id="mim1-contextinformationmanagement-goal"></a>

| <p>💡</p><p>Work Item</p> | <p>🧩</p><p>Capabilities</p> | <p>🏗</p><p>Specification</p> | <p>👩⚖</p><p>Governance</p> |
| ------------------------- | ---------------------------- | ----------------------------- | --------------------------- |
| ✅                         |                              |                               |                             |

## Objectives <a href="#mim1-contextinformationmanagement-goal" id="mim1-contextinformationmanagement-goal"></a>

Specifies how to share spatial (and spatio-temporal) data, make them interoperable with, within, and between systems and territories. This goes from static data about assets such as street lights, buildings, and streets to spatio-temporal data from sensors. The purpose of this Minimal Interoperability Mechanism (MIM) is to make this data and the way it is shared interoperable across cities, but also among stakeholders within the same city. This MIM will also provide input to [MIM2 Data models](oasc-mim-2-data-models.md), in particular regarding data which has an explicit geospatial dimension.

## Capabilities

Geospatial information contains comprehensive bi-dimensional, tri-dimensional and (when time is also involved) four-dimensional representation of real-world entities defined in a structured way. Different datasets can easily be combined based on location. In addition, powerful spatial analyses and sophisticated visualisation can be performed that provide important insights to different stakeholders in the city. It is therefore essential to include the geospatial data dimension into smart city information systems.

The discovery, querying, retrieval, visualisation, and editing of geospatial information based on location and temporal criteria can be achieved through open standard formats, protocols and preferably through the use of standardised API interfaces. Integrating context information with geospatial information can be enabled by the context management API and geospatial management API through common data information models defined in the [MIM2 Data models](oasc-mim-2-data-models.md).

## Specifications <a href="#mim3-ecosystemtransactionmanagement-recommendedspecifications" id="mim3-ecosystemtransactionmanagement-recommendedspecifications"></a>

The specifications that are subject to adoption are focussing on (i) web interfaces for discovery and access to data, and (ii) data encoding formats.

### Web Interfaces

**Specifications by the Open Geospatial Consortium (OGC)**

**OWS-based family of standards:**

Those [OGC Web Services](https://www.ogc.org/standards/owc) standards follow the same conceptual model. They are mature, well-known by the geospatial community and supported by a wide number of client and server implementations.

* Catalogue Service for the Web ([CSW](https://www.ogc.org/standards/cat))
* Web Map Service ([WMS](https://www.ogc.org/standards/wms))
* Web Map Tile Service ([WMTS](https://www.ogc.org/standards/wmts))
* Web Feature Service ([WFS](https://www.ogc.org/standards/wfs))
* Web Coverage Service ([WCS](https://www.ogc.org/standards/wcs))
* Sensor Observation Service ([SOS](https://www.ogc.org/standards/sos))

**API-based family of standards:**

The new [OGC Web API family of standards](https://ogcapi.ogc.org/#standards) are built upon the legacy of the OGC Web Service standards to define resource-centric APIs that take advantage of modern web development practices. These new standards are web-friendly and are being constructed as "building blocks" that can be used to assemble novel APIs for web access to geospatial content. (The following OGC APIs are at a different stage of development: Features, Common, Maps, Records, Processes, Coverages, Tiles, Environmental Data Retrieval).

* The [OGC SensorThings API](https://www.ogc.org/standards/sensorthings) standard provides an open source and uniform API to connect IoT devices, data and applications on the Web; it provides a standard way to manage and retrieve observations and metadata from IoT sensors built on the legacy of the OGC SOS and SPS. The SensorThings API standard supports both request-response and asynchronous transactions.
* The [OGC API - Features](https://www.ogc.org/standards/ogcapi-features) standard provides a modular, encoding-agnostic and web-friendly means for the exposure of geospatial features on the web. &#x20;

\*\*\*\*

### Data encoding

This section specifies data encodings for geospatial data that is also relevant for the provisions of [MIM2 Data models](oasc-mim-2-data-models.md).

* Semantic 3D city models or digital twins standards for representing the entities of cities and landscapes.
  * [CityGML](https://www.ogc.org/standards/citygml), an OGC open data model and XML-based format for the storage and exchange of virtual 3D city models
  * [CityJSON](https://www.cityjson.org), a community standard, JSON-based encoding for storing 3D city models, also called digital maquettes or digital twins.
* [Industry Foundation Classes](https://technical.buildingsmart.org/standards/ifc) ([IFC](https://technical.buildingsmart.org/standards/ifc/ifc-formats/)), a buildingSmart open, international standard ([ISO 16739-1:2018](https://www.iso.org/standard/70303.html)), for a standardised, digital description of the built environment, including buildings and civil infrastructure.
* [ISO Observations & Measurements](https://www.ogc.org/standards/om), providing a conceptual model for representing spatio-temporal observation data. Both JSON and XML-based implementations of the conceptual model are available. This data encoding is the default for the OGC Sensor Observation Service (xml-based), and the [Sensing profile](http://docs.opengeospatial.org/is/15-078r6/15-078r6.html) of the OGC SensorThings API.
* [GeoPackage](https://www.geopackage.org) provides an open, compact and efficient format for sharing geospatial data. It is based on an SQLite database and is very well supported by both proprietary and open source software tools.

### Standards for implementing European Union's INSPIRE Directive

For the European Union context, non-binding [technical guidelines](https://inspire.ec.europa.eu/Technical-Guidelines) and [good practices](https://inspire.ec.europa.eu/portfolio/good-practice-library) are available for implementing the legal provisions of the [INSPIRE Directive](https://inspire.ec.europa.eu). Technical specifications are made available for each standard, which enable data providers to choose a particular solution based on the specific needs and concrete use cases. The governance of the technical specifications is ensured by the INSPIRE Maintenance and Implementation group (MIG), and its permanent technical sub-group (MIG-T). The following standards are available:

#### Network services

NSPIRE Network Services specify common interfaces for web services. Dedicated technical guidelines are made available for:

* Discovery Services ([OGC CSW](https://inspire.ec.europa.eu/documents/technical-guidance-implementation-inspire-discovery-services-0))
* View Services ([OGC WMS, WMTS](https://inspire.ec.europa.eu/documents/technical-guidance-implementation-inspire-view-services-1))
* Download Services ([OGC WFS](https://inspire.ec.europa.eu/documents/technical-guidance-implementation-inspire-download-services), [WCS](https://inspire.ec.europa.eu/id/document/tg/download-wcs), [SOS](https://inspire.ec.europa.eu/id/document/tg/download-sos), [ATOM Feeds](https://inspire.ec.europa.eu/documents/technical-guidance-implementation-inspire-download-services), [SensorThings API](https://github.com/INSPIRE-MIF/gp-ogc-sensorthings-api), [OGC API - Features](https://github.com/INSPIRE-MIF/gp-ogc-api-features/blob/master/spec/oapif-inspire-download.md))

#### Data encoding

The [INSPIRE data specifications](https://inspire.ec.europa.eu/Technical-Guidelines) define common data models, code lists, map layers and additional metadata on the interoperability to be used when exchanging spatial datasets. In addition, a dedicated [Location Core Vocabulary](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/core-location-vocabulary/release/100) provides a minimum set of classes and properties for describing a location represented as an address, a geographic name, or a geometry.

* [GML](https://github.com/INSPIRE-MIF/application-schemas)
* [GeoJSON](https://github.com/INSPIRE-MIF/2017.2/blob/master/GeoJSON/geojson-encoding-rule.md)
* [GeoPackage](https://github.com/INSPIRE-MIF/gp-geopackage-encodings)

#### Validation

An advantage of INSPIRE is the ability to validate metadata, services and data against the technical provisions listed above. To this end, the [INSPIRE reference validator](https://inspire.ec.europa.eu/validator/), fully based on open source components, is being used. Local instances of the tool can be deployed within the cities own infrastructures in addition to the centrally available solution.



## MIM7 Working Group  <a href="#mim3-ecosystemtransactionmanagement-recommendedspecifications" id="mim3-ecosystemtransactionmanagement-recommendedspecifications"></a>

Representatives of the following organisations:&#x20;

* INSPIRE, Open Geospatial Consortium (OGC)
* Cities of Athens, Gothenburg, Swedish Association of Local Authorities and Regions (SALAR), Vienna
* European Commission: DG Connect and DG Digit
* Companies: ATOS, Engineering, NEC
