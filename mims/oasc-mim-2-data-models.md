---
description: 'OASC MIM2: Shared Data models'
---

# MIM2 - Data Models

## Status <a href="#mim1-contextinformationmanagement-goal" id="mim1-contextinformationmanagement-goal"></a>

| <p><span data-gb-custom-inline data-tag="emoji" data-code="1f4a1">💡</span></p><p>Work Item</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f9e9">🧩</span></p><p>Capabilities</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f3d7">🏗</span></p><p>Specification</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f469-2696">👩⚖</span></p><p>Governance</p> |
| :---------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------: |
|                                       :white\_check\_mark:                                      |                                        :white\_check\_mark:                                        |                                         :white\_check\_mark:                                        |                                                                                                        |

## Objectives

Guidelines and catalog of minimum common data models in different verticals to enable interoperability for applications and systems among different cities.

Harmonized representation formats and semantics that will be used by applications both to consume and to publish data.

Smart Data Models for interoperable and replicable smart solutions in multiple sectors, starting with smart cities but also for smart agrifood, smart utilities, smart industry, etc.

## Capabilities

Data models serve as a language in which systems can talk to each other. Clear defined data models help cities in choosing and opening up data across solutions.

Data models should capture as much the complete context they are representing. This enables other applications to define what they need for their context and request the specific attributes they are interested in.

Harmonization across data models help in supporting different data models again to support the different applications out there. Clear definitions of the data models help in transforming this data models between the different standards

## Specifications

**Recommended specifications:**

* NGSI-LD compliant data models for aspects of the smart city have been defined by organisations and projects, including OASC, FIWARE, GSMA and the SynchroniCity project and there is an ongoing joint activity of TM Forum and FIWARE to specify more.
* Existing data models and ontologies, e.g. the SAREF (Smart Applications REFerence ontology) standard by ETSI/oneM2M, can be mapped for use with NGSI-LD by identifying what are entities, properties and relationships, which can be managed and requested by the NGSI-LD API.
* oneM2M base ontology (that is compatible with SAREF). Additionally, oneM2M provides the means to instantiate ontologies as a means to provide semantic descriptions of the data exchanged (through the use of metadata)
* SAREF: Smart Appliances REFerence (SAREF) ontology specified by ETSI OneM2M committee with the extension of SAREF4Cities provides an ontology focused on smart cities
* Core vocabularies of ISA like Core Public Service Vocabulary Application Profile used as the basis for the Single Digital Gateway Regulation that touches local governments, Core Person, Core Organization etc
* DTDL is the Digital twin Definition Language developed by Microsoft. This language is based on top op json-ld and the existing Fiware data models are converted in this format.
* For spatial (and spatio-tempopral) observation data the provisions of [MIM-7 (Places)](oasc-mim7-places.md) about data encoding have to be taken into consideration.

{% hint style="info" %}
Unfinished page
{% endhint %}
