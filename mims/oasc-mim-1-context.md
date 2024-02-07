---
description: 'OASC MIM1: Context Information Management'
---

# MIM1 - Context

## Status

| <p><span data-gb-custom-inline data-tag="emoji" data-code="1f4a1">💡</span></p><p>Work Item</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f9e9">🧩</span></p><p>Capabilities</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f3d7">🏗</span></p><p>Specification</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f469-2696">👩⚖</span></p><p>Governance</p> |
| :---------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------: |
|                                       :white\_check\_mark:                                      |                                        :white\_check\_mark:                                        |                                         :white\_check\_mark:                                        |                                          :white\_check\_mark:                                          |

## Objectives

Context information management ensures comprehensive and integrated access, use, sharing, and management of data across different solutions and purposes. It manages the context information coming from Internet of Things (IoT) devices and other public and private data sources providing cross cutting context data and access through a uniform interface.

This objective is currently being reviewed

## Capabilities

Context information contains comprehensive status information about real-world entities defined in a structured way with formal definitions and provides functionalities to enable access to different data sources and analyse context information, e.g. for detecting events.

The information that cities, regions and communities possess or gather is available and easily accessible to applications across different domains. To make the information usable the context information is key.

Applications are able to discover the information relevant to their context. For example by specifying what is needed and retrieve or subscribe to this requested information. To share and re-use this information an agreement is in place on the concepts, this can be provided by data information models.

Discovery and querying of information, both current and historical, is possible, also in a geospatial way.

Applications can subscribe to changes of information so that they are always aware of the current and latest status.

The implementation across (and even within) the city, or any application ecosystem, can be very diverse and heterogeneous. An agreement on the interfaces is necessary to be able to access the information. This is enabled by the context management API and the data information models.

## Specifications

All documents and deliverables can be found

| **Standard** | **Aspect**          | **Reference**                                                            |
| ------------ | ------------------- | ------------------------------------------------------------------------ |
| ETSI NGSI-LD | Group Specification | [https://www.etsi.org/comittee/cim](https://www.etsi.org/committee/cim/) |

## ETSI NGSI-LD Reference Implementations

The below table lists reference implementations of the NGSI standard known to OASC. If you are aware of other reference implementations please share them in the comments section.

_Please note that this list purely serves an informational purpose. OASC does not guarantee that the listed reference implementations are operational with local technical environments and OASC cannot be held responsible for the listed implementations._

| **Provider** | **Name**             | **Link**                                                                                                       |
| ------------ | -------------------- | -------------------------------------------------------------------------------------------------------------- |
| FIWARE       | Orion Context Broker | [https://github.com/FIWARE/context.Orion-LD](https://github.com/FIWARE/context.Orion-LD)                       |
| NEC          | Scorpio Broker       | [https://github.com/ScorpioBroker/ScorpioBroker](https://github.com/ScorpioBroker/ScorpioBroker)               |
| Sensinov     | Djane.io             | [https://github.com/sensinov/djane](https://github.com/sensinov/djane)                                         |
| EGM          | Stellio Broker       | [https://github.com/stellio-hub/stellio-context-broker](https://github.com/stellio-hub/stellio-context-broker) |

{% hint style="info" %}
We are updating this list
{% endhint %}

## Verification

ETSI organized a Testing Task Force (TTF) to create a Testing toolkit to validate context brokers towards the NGSI-LD specification. EGM, Ubiwhere and OASC collaborated on this task force to create this toolkit. The result was a set of clear defined test descriptions, test purposes and executable robot scripts. All this information can be found on the ETSI CIM Website [**https://www.etsi.org/comittee/cim**](https://www.etsi.org/committee/cim/)**.**
