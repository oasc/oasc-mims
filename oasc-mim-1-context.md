---
description: >-
  Enabling homogeneous access to real-time context information from hundreds of
  cities.
---

# OASC MIM1: Context

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
        <p>Reference</p>
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

Context information management ensures comprehensive and integrated access, use, sharing, and management of data. It manages the context information coming from Internet of Things \(IoT\) devices and other public and private data sources providing context data access through a uniform interface.

## Capabilities <a id="MIM1:ContextInformationManagement-Capabilities"></a>

Context information contains status information about real-world entities defined in a structured way and provides functionalities to enable access to different data sources and analyse context information, e.g. for detecting events.

The information that cities, regions and communities possess or gather is available and easily accessible to applications across different domains. To make the information usable the context information is key.

Applications are able to discover the information relevant to them. For example by specifying what is needed and retrieve or subscribe to this requested information. To share and re-use this information an agreement is in place on the concepts, this can be provided by data information models.

Discovery and querying of information, both current and historical, is possible, also in a geospatial way.

Applications can subscribe to changes of information so that they are always aware of the current status.

The implementation across \(and even within\) the city, or any application ecosystem, can be very diverse and heterogeneous. An agreement on the interfaces is necessary to be able to access the information. This is enabled by the context management API and the data information models.

## Specifications <a id="MIM1:ContextInformationManagement-Recommendation"></a>

| **Standard** | Aspect | **Reference** |
| :--- | :--- | :--- |
| **ETSI NGSI-LD** | **Group Specification** | \*\*\*\*[**https://www.etsi.org/deliver/etsi\_gs/CIM/001\_099/009/**](https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/)\*\*\*\* |
| ETSI NGSI-LD | API | [https://www.etsi.org/deliver/etsi\_gs/CIM/001\_099/004/](https://www.etsi.org/deliver/etsi_gs/CIM/001_099/004/) |
| ETSI NGSI-LD | Information model | [https://www.etsi.org/deliver/etsi\_gs/CIM/001\_099/006/](https://www.etsi.org/deliver/etsi_gs/CIM/001_099/006/) |

## ETSI NGSI-LD Reference Implementations <a id="MIM1:ContextInformationManagement-ETSINGSI-LDReferenceImplementations"></a>

The below table lists reference implementations of the NGSI standard known to OASC. If you are aware of other reference implementations please share them in the comments section.

_Please note that this list purely serves an informational purpose. OASC does not guarantee that the listed reference implementations are operational with local technical environments and OASC cannot be held responsible for the listed implementations._

| **Provider** | **Name** | **Link** |
| :--- | :--- | :--- |
| FIWARE | Orion Context Broker | [https://github.com/telefonicaid/fiware-orion](https://github.com/telefonicaid/fiware-orion) |
| NEC | Scorpio Broker | [https://github.com/ScorpioBroker/ScorpioBroker](https://github.com/ScorpioBroker/ScorpioBroker) |
| Sensinov | Djane.io | [https://github.com/sensinov/djane](https://github.com/sensinov/djane) |
| EGM | Stellio Broker | [https://github.com/stellio-hub/stellio-context-broker](https://github.com/stellio-hub/stellio-context-broker) |

{% hint style="info" %}
We are updating this list 
{% endhint %}
