---
description: 'OASC MIM1: Context Information Management'
---

# MIM1 - Context

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
      <td style="text-align:center">&#x2705;</td>
      <td style="text-align:center"></td>
      <td style="text-align:center">&#x2705;</td>
      <td style="text-align:center"></td>
      <td style="text-align:center">&#x2705;</td>
      <td style="text-align:center"></td>
      <td style="text-align:center">&#x2705;</td>
    </tr>
  </tbody>
</table>

## Objectives <a id="MIM1:ContextInformationManagement-Goal"></a>

Context information management ensures comprehensive and integrated access, use, sharing, and management of data across different solutions and purposes. It manages the context information coming from Internet of Things \(IoT\) devices and other public and private data sources providing cross cutting context data and access through a uniform interface.

## Capabilities <a id="MIM1:ContextInformationManagement-Capabilities"></a>

Context information contains comprehensive status information about real-world entities defined in a structured way with formal definitions and provides functionalities to enable access to different data sources and analyse context information, e.g. for detecting events.

The information that cities, regions and communities possess or gather is available and easily accessible to applications across different domains. To make the information usable the context information is key.

Applications are able to discover the information relevant to their context. For example by specifying what is needed and retrieve or subscribe to this requested information. To share and re-use this information an agreement is in place on the concepts, this can be provided by data information models.

Discovery and querying of information, both current and historical, is possible, also in a geospatial way.

Applications can subscribe to changes of information so that they are always aware of the current and latest status.

The implementation across \(and even within\) the city, or any application ecosystem, can be very diverse and heterogeneous. An agreement on the interfaces is necessary to be able to access the information. This is enabled by the context management API and the data information models.

## Specifications <a id="MIM1:ContextInformationManagement-Recommendation"></a>

All documents and deliverables can be found 

| **Standard** | Aspect | **Reference** |
| :--- | :--- | :--- |
| **ETSI NGSI-LD** | **Group Specification** | [**https://www.etsi.org/comittee/cim**](https://www.etsi.org/committee/cim/) |

## ETSI NGSI-LD Reference Implementations <a id="MIM1:ContextInformationManagement-ETSINGSI-LDReferenceImplementations"></a>

The below table lists reference implementations of the NGSI standard known to OASC. If you are aware of other reference implementations please share them in the comments section.

_Please note that this list purely serves an informational purpose. OASC does not guarantee that the listed reference implementations are operational with local technical environments and OASC cannot be held responsible for the listed implementations._

| **Provider** | **Name** | **Link** |
| :--- | :--- | :--- |
| FIWARE | Orion Context Broker | [https://github.com/telefonicaid/fiware-orion](https://github.com/FIWARE/context.Orion-LD) |
| NEC | Scorpio Broker | [https://github.com/ScorpioBroker/ScorpioBroker](https://github.com/ScorpioBroker/ScorpioBroker) |
| Sensinov | Djane.io | [https://github.com/sensinov/djane](https://github.com/sensinov/djane) |
| EGM | Stellio Broker | [https://github.com/stellio-hub/stellio-context-broker](https://github.com/stellio-hub/stellio-context-broker) |

{% hint style="info" %}
We are updating this list
{% endhint %}

## Verification

ETSI organized a Testing Task Force \(TTF\) to create a Testing toolkit to validate context brokers towards the NGSI-LD specification. EGM, Ubiwhere and OASC collaborated on this task force to create this toolkit. The result was a set of clear defined test descriptions, test purposes and executable robot scripts. All this information can be found on the ETSI CIM Website [**https://www.etsi.org/comittee/cim**](https://www.etsi.org/committee/cim/)**.**

