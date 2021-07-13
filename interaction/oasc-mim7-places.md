---
description: 'OASC MIM7: Places'
---

# MIM7 - Places

## Status <a id="MIM1:ContextInformationManagement-Goal"></a>

<table>
  <thead>
    <tr>
      <th style="text-align:center">
        <p>&#x1F4A1;</p>
        <p>Work Item</p>
      </th>
      <th style="text-align:center">&gt;</th>
      <th style="text-align:center">
        <p>&#x1F9E9;</p>
        <p>Capabilities</p>
      </th>
      <th style="text-align:center">&gt;</th>
      <th style="text-align:center">
        <p>&#x1F3D7;</p>
        <p>Specification</p>
      </th>
      <th style="text-align:center">&gt;</th>
      <th style="text-align:center">
        <p>&#x1F469;&#x2696;</p>
        <p>Governance</p>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">&#x2705;</td>
      <td style="text-align:center"></td>
      <td style="text-align:center"></td>
      <td style="text-align:center"></td>
      <td style="text-align:center"></td>
      <td style="text-align:center"></td>
      <td style="text-align:center"></td>
    </tr>
  </tbody>
</table>

## Objectives <a id="MIM1:ContextInformationManagement-Goal"></a>

Specifies how to share spatial (and spatio-temporal) data, make theme interoperable with, within, and between systems and territories. This goes from static data about assets such as street lights, buildings, and streets to spatio-temporal data from sensors. The purpose of this Minimal Interoperability Mechanism (MIM) is to make this data and the way it is shared interoperable across cities, but also among stakeholders within the city. This MIM will also provide input to [MIM2 Data models](), in particular regarding data which has an explicit geospatial dimension.

## Capabilities

Geospatial information contains comprehensive bi-dimensional or tri-dimensional representation and localization about real-world entities defined in a structured way with formal definitions and provides functionalities to enable access to different data sources and analyse spatial information.

It is essential to include the geospatial data dimension into smart cities information systems for adding localization capabilities and improving its usage with spatial analysis capabilities.

Discovery and querying of geospatial information, using location and historical criteria can be achieved using Open standard formats, protocols and preferably Open API standard interfaces.

Displaying and viewing of geospatial information, can be achieved using Open standard formats, protocols and preferably Open API standard interfaces.

Retrieving and editing of geospatial information, can be achieved using Open standard formats, protocols and preferably Open API standard interfaces.

Integrating context information with geospatial information can be enabled by the context management API and geospatial management API through common data information models defined in the MIM2 Data Models.

## Specifications <a id="MIM3:EcosystemTransactionManagement-Recommendedspecifications"></a>
The specifications that are subject to adoption are focussing on (i) web interfaces for access to data, and (ii) data encoding formats. 

### Web interfaces


* **Specifications by the Open Geospatial Consortium \(OGC\)**

  **SOAP-based family of standards:**
  * Catalog Service for the Web \([CSW](https://www.ogc.org/standards/cat)\)
  * OGC Web Map Services \([WMS](https://www.ogc.org/standards/wms)\)
  * OGC Web Feature Services \([WFS](https://www.ogc.org/standards/wfs)\)
  * OGC Web Coverage Services \([WCS](https://www.ogc.org/standards/wcs)\)
  * OGC Sensor Observation Services \([SOS](https://www.ogc.org/standards/sos)\)

* **API-based family of standards:**
  * The new [OGC Web API family of standards](https://ogcapi.ogc.org/#standards), built upon the legacy of the OGC Web Service standards, to define resource-centric APIs that take advantage of modern web development practices. These standards are web-friendly and are being constructed as "building blocks" that can be used to assemble novel APIs for web access to geospatial content. \(The following OGC APIs are at a different stage of development: Features, Common, Maps, Records, Processes, Coverages, Tiles, Environmental Data Retrieval\).
  * The [OGC SensorThings API](https://www.ogc.org/standards/sensorthings), provides an open-source and uniform API to connect IoT devices, data and applications on the Web, it provides a standard way to manage and retrieve observations and metadata from IoT sensors built on the legacy of OGC SOS and SPS.

\*\*\*\*

### Data encoding

This section specifies data encodings for geospatial data that is also relevant for the provisions of [MIM2]().
* **Semantic 3D city models or digital twins standards for representing the entities of cities and landscapes.**
  * [CityGML](https://www.ogc.org/standards/citygml), an OGC open data model and XML-based format for the storage and exchange of virtual 3D city models
  * [CityJSON](https://www.cityjson.org/), a community standard, JSON-based encoding for storing 3D city models, also called digital maquettes or digital twins.
  *  [Industry Foundation Classes](https://technical.buildingsmart.org/standards/ifc) \([IFC](https://technical.buildingsmart.org/standards/ifc/ifc-formats/)\), a buildingSmart open, international standard \([ISO 16739-1:2018](https://www.iso.org/standard/70303.html)\), for a standardized, digital description of the built environment, including buildings and civil infrastructure.
  *  [ISO Observations & Measurements](https://www.ogc.org/standards/om), provides a conceptual model for representing spatio-temporal observation data. Both JSON and XML-based implementations of the conceptual model are available. This data encoding is the default for the OGC Sensor Observation Service (xml-based), and the [Sensing profile](http://docs.opengeospatial.org/is/15-078r6/15-078r6.html) of the OGC SensorThingsAPI.
  *  [Geopackage](https://www.geopackage.org/) provides an open, compact and efficient format for sharing geospatial data. It is based on an SQLite database and is very well supported by both proprietary and open source software tools.

### Standards for implementing European Union's INSPIRE Directive

For the European Union context, non-binding technical approaches are endorsed by the INSPIRE Governance bodies. Technical specifications are made available for each standard, which enable data providers to choose a particular solution based on the specific needs and concrete use cases. The following standards are available:

#### Network services
  * Discovery Services \(OGC CSW\)
  * View Services \(OGC WMS, WMTS\)
  * Download Services \(OGC WFS, WCS, SOS, ATOM Feeds, SensorThingsAPI, [OGC API-Features](https://github.com/INSPIRE-MIF/gp-ogc-api-features/blob/master/spec/oapif-inspire-download.md)\)

#### Data encoding


