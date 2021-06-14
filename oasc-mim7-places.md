---
description: 'OASC MIM7: Geospatial Information Management'
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
        <p>Capability</p>
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
      <td style="text-align:center"></td>
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

Specifies how to handle geospatial data, make it interoperable with, within, and between systems and territories. This goes from streetlights, buildings, streets to complete cities and regions. The purpose of this MIM is to make this data interoperable across cities, but also to make this data interoperable with the other data captured by a city, like IoT data. 

This MIM will also provide input the MIM2 Data models, in the body of Geospatial Data Models.

## Capabilities

Geospatial information contains comprehensive bi-dimensional or tri-dimensional representation and localization about real-world entities defined in a structured way with formal definitions and provides functionalities to enable access to different data sources and analyse spatial information.

It’s crucial to include the geospatial data dimension into smart cities information systems for adding localization capabilities and improving its usage with spatial analysis capabilities.

Discovery and querying of geospatial information, using location and historical criteria can be achieved using Open standard formats, protocols and preferably Open API standard interfaces..

Displaying and viewing of geospatial information, can be achieved using Open standard formats, protocols and preferably Open API standard interfaces.

Retrieving and editing of geospatial information, can be achieved using Open standard formats, protocols and preferably Open API standard interfaces.

Integrating context information with geospatial information can be enabled by the context management API and geospatial management API through common data information models defined in the MIM2 Data Models.

## Specifications <a id="MIM3:EcosystemTransactionManagement-Recommendedspecifications"></a>

**Baseline specifications proposed for adoption:**

* **International geospatial specifications defined and adopted on a global level by Open Geospatial Consortium \(OGC\):**
  * Catalog Service for the Web \([CSW](https://www.ogc.org/standards/cat)\)
  * OGC Web Map Services \([WMS](https://www.ogc.org/standards/wms)\)
  * OGC Web Feature Services \([WFS](https://www.ogc.org/standards/wfs)\)
  * OGC Web Coverage Services \([WCS](https://www.ogc.org/standards/wcs)\)
  * OGC Sensor Observation Services \([SOS](https://www.ogc.org/standards/sos)\)



* **European INSPIRE Directive adopted OGC and ISO \(19115/19119/19139\) specifications:**
  * Discovery Services \(OGC CSW\)
  * View Services \(OGC WMS\)
  * Download Services \(OGC WFS, WCS, SOS, ATOM Feeds\)



* **Endorse the new API based family of OGC standards:**
  * The [OGC SensorThings API](https://www.ogc.org/standards/sensorthings), provides an open-source and uniform API to connect IoT devices, data and applications on the Web, it provides a standard way to manage and retrieve observations and metadata from IoT sensors built on the legacy of OGC SOS and SPS.
  * The new [OGC Web API family of standards](https://ogcapi.ogc.org/#standards), built upon the legacy of OGC Web Service standards, to define resource-centric APIs that take advantage of modern web development practices. These standards are being constructed as "building blocks" that can be used to assemble novel APIs for web access to geospatial content. \(OGC APIs: Features, Common, Maps, Records, Processes, Coverages, Tiles, Styles EDR\)

\*\*\*\*

* **Semantic 3D city models or digital twins standards for representing the entities of cities and landscapes.**
  * [CityGML](https://www.ogc.org/standards/citygml), an OGC open data model and XML-based format for the storage and exchange of virtual 3D city models
  * [CityJSON](https://www.cityjson.org/), a community standard, JSON-based encoding for storing 3D city models, also called digital maquettes or digital twins.
  *  [Industry Foundation Classes](https://technical.buildingsmart.org/standards/ifc) \([IFC](https://technical.buildingsmart.org/standards/ifc/ifc-formats/)\), a buildingSmart open, international standard \([ISO 16739-1:2018](https://www.iso.org/standard/70303.html)\), for a standardized, digital description of the built environment, including buildings and civil infrastructure.



