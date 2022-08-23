---
description: 'OASC MIM5: Fair and Transparent Artificial Intelligence'
---

# MIM5 - Transparency\*

## Status <a href="#mim1-contextinformationmanagement-goal" id="mim1-contextinformationmanagement-goal"></a>

| <p><span data-gb-custom-inline data-tag="emoji" data-code="1f4a1">💡</span></p><p>Work Item</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f9e9">🧩</span></p><p>Capabilities</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f3d7">🏗</span></p><p>Specification</p> | <p><span data-gb-custom-inline data-tag="emoji" data-code="1f469-2696">👩⚖</span></p><p>Governance</p> |
| :---------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------: |
|                                       :white\_check\_mark:                                      |                                        :white\_check\_mark:                                        |                                                                                                     |                                                                                                        |

{% hint style="info" %}
Supporting automated decision-making using algorithmic systems that are trusted, fair and transparent.
{% endhint %}

## Background

Governments are increasingly seeking to capture the opportunities offered by automated decision-making algorithmic systems, to improve their services. However, government agencies and the general public have justified concerns over bias, privacy, accountability, and transparency of such automated decision-making processes. New examples continue to emerge of potential negative consequences from the inappropriate use of ('black box') algorithms.

Here we define "Algorithmic System" as: "software that automatically makes predictions, makes decisions and/or gives advice by using data analysis, statistics and/or self-learning logic."

‌An automated decision-making algorithmic system does not necessarily require any form of self-learning logic (such as machine learning). In actual practice, software is often used that does not contain any self-learning logic, but the application of which may have great and sometimes unknown or unintended impact on citizens.

This is an increasingly important issue as cities and communities are increasingly using complex modelling to support their decision making and moving towards the implementation of local digital twins.

To provide citizens and governments with a proper process to mitigate risk, Amsterdam city council, the original champion of MIM5, is working with other cities to develop a European standard for procurement rules for government agencies to use when procuring algorithmic systems to support automated decision-making. Alongside this, guidance is being developed regarding the actions that government agencies themselves need to take to make sure that automated decision-making is trusted, fair and transparent. This will include providing channels for citizens to query the decision-making process and involving citizens in co-designing the algorithmic systems. Most importantly there is the need to ensure that the data used by those systems is accurate and appropriate.

In addition, there are some useful checklists that have been developed elsewhere, and the UK has developed a Framework on Fair AI for the Public Sector and an Algorithmic Transparency standard (links available in [References](references.md)).

## Objectives

MIM 5 will provide the technical capabilities required to check that the algorithmic systems offered by suppliers comply with the requirements for fairness, trustworthiness and transparency identified by Amsterdam and by other checklists and standards.

## Capabilities

\
In order to match the procurement norm being developed, the following are the set of six minimal requirements from Amsterdam for suppliers of algorithmic systems to ensure that these are fair, trustworthy and transparent.

### **Procedural Transparency**

* Full disclosure of the type of choices made, parties involved, risks and mitigation actions in the process of creating an algorithmic model.

### **Technical Transparency**

* Full disclosure to allow the buyer of the source code and model to explain the model to citizens or other stakeholders.
* Access to the learnings of the model, ideally structured using MIM2, to prevent vendor lock-ins.
* Clarity about the process by which an algorithmic system makes decisions in an overall system, i.e. the optimisation goals and outcomes of an algorithm.

### **Technical Explainability**&#x20;

* Ability to explain on an individual level how a model creates certain outcomes.
* Ability to address any restrictions as to whom the information will be classified: public servants, other experts, etc.

### **Fairness**

* Ensuring that the algorithmic systems does not systematically disadvantage, show bias against, or even discriminate against, different social groups and demographics.

### **Context**

* The assessment of fairness depends on facts, events, and goals, and therefore has to be understood as situation or task-specific and necessarily addressed within the scope of practice. For instance, there may be an explicit goal to address an historic imbalance, where positive discrimination is considered appropriate. Here the aspect of “fairness” needs to be seen in the wider context.

### **Accountability**

* Accountability for the supplier to create algorithms that respect human digital rights, and that are compliant with national and local anti-discrimination laws and regulations.
* Agencies should not procure algorithms that are shielded from an independent validation and public review because of trade-secret or confidentiality claims.

It should be noted that these capabilities should be applied differently to different systems depending on the nature, context and goals of the algorithmic system.

Technically, these capabilities can be translated into a metadata API that every vendor would provide, when supplying high impact algorithms to cities, and the buyers could put in their requirements when procuring.

## Work to be done

The work is to identify/develop a set of APIs that enable any potential algorithmic decision-making system to be queried as to:

1.Does the system use AI/ automated decision making?

&#x20;   a. Yes/No

&#x20;   b. Which level?

&#x20;   c. What schema is being used?

2\. What does the algorithms do?

&#x20;   a. List of algorithms.

&#x20;   b.  What schema is being used?

3\. Who certified this claim?

&#x20;   a. Link to the certification

&#x20;   b. A Registry of certified algorithms

&#x20;   c. Schema used

And to enable the claim to be checked by comparing the results from the use of the system with the results from a known system (for instance with human decision making) to ensure the results are accurate. Here the APIs need to check both the data sets being used and the algorithms.

Alongside this, to develop relevant guidance as to how these APIs can be used.

### Carrying out the work

The work would consist of:

1. Agreeing a set of definitions of key terms to ensure clarity in the work we do and as a resource to be included in MIM5.
2. Developing technical tools and guidance to support cities in procuring and using fair and transparent AI. This will build on the Standard Clauses for Procurement of Trustworthy Algorithmic Systems developed by the City of Amsterdam, as well as some checklists and standards that are being gathered from around the world and that focus on the process of deciding when and how to use AI for citizen centred services. The work will involve guidance as to how cities:
   * can test whether products and services they are procuring, planning to use, or are actually using, are fair, trustworthy and transparent.
   * can ensure the appropriateness and accuracy of data used both in training the algorithmic systems as well as used by those systems in decision making.

The work could be carried out in a two-stage process:

a. First scope out the key issues to be covered using the Amsterdam procurement guidance and other relevant checklists to scope out the technical requirements needed to support such guidance.

b. Then identify/develop a set of APIs that can automatically check whether a decision-making algorithmic system complies with the guidance document

3\. Working with the agencies developing algorithmic registers, aim to align the format and process they are developing to help communities audit and keep track of their use of decision-making algorithms with the guidance and technical solutions provided in MIM5.

In addition, it would be important to link with European implementation timetable. In about one and half years there will be many cities needing support in Europe. Funding will be available for toolboxes in the coming few months. Knowing this, some preparation work could be done to help use these opportunities in the best way to build on the work being done on MIM5. One possible option would be to put together a paper on what is needed to complement the toolbox.

## MIM5 Working Group members <a href="#mim3-ecosystemtransactionmanagement-recommendedspecifications" id="mim3-ecosystemtransactionmanagement-recommendedspecifications"></a>

Representatives of the following organisations:

* Cities of Amsterdam, Athens, Barcelona.
* European Commission: DG Connect and DG Digit.
* Companies: ATOS, Engineering, NEC.

## Recommendations approved at the OASC Annual Summit on June 7th 2022:

* To agree the proposed scope of the APIs.
* To agree that the technical specifications should be developed in the new work year to bring to the Annual Summit in 2023 for agreement.
