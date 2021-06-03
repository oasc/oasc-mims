---
description: Fair Artificial Intelligence
---

# OASC MIM5: City of Amsterdam proposal

Proposed by the City of Amsterdam and adopted as work item for 2020

## Why fair AI? <a id="MIM5:FairArtificialIntelligenceandAlgoritmes-WhyfairAI?"></a>

Governments are increasingly seeking to capture the opportunities offered by AI to improve their services. However, governments and the general public also have justified concerns over bias, privacy, accountability, transparency of artificial intelligence. New examples are becoming apparent of negative consequences from the use of \(‘black box’\) algorithms. Recently, UN Human Rights Rapporteur Alston warned the Dutch Government for the bias of fraud risk analytics system SYRI.

## Why through contracts and procurement conditions? <a id="MIM5:FairArtificialIntelligenceandAlgoritmes-Whythroughcontractsandprocurementconditions?"></a>

Without clear conditions, governments fail to install democratic oversight of algorithmic decision-making, and may inadvertently create new risks or harm to their citizens. Governments often rely on the expertise of technology providers and often lack the necessary technical or judicial skills to decide how to implement algorithmic decision making. ‘Vendor lock-ins’ are looming: The more training an algorithm gets, the more valuable and useful it usually becomes \(Assuming problems of ‘overfitting’ models that decrease in performance are adequately dealt with while training the algorithm\). This could cause market inefficiencies, as switching to another vendor involves substantial costs, and monopolization or winner take all effects are risking. The barrier to choosing an AI implementation for government officials is becoming higher, wary for not overseeing the political and material risks of AI. Technology providers understand these challenges and aim to create clarity and predictability about risks related to AI implementations in their service provisioning. While companies are generally wary of stricter guidelines for government procurement, common-sense frameworks can help governments to procure complex new technological solutions and actually open new markets for companies. Transparent guidelines will permit both established companies and new entrants to the AI space to compete on a level playing field for government contracts. \(Source: World Economic Forum \). However, guidelines and principles are not enough in practice. When contracts are negotiated decisions are being made.

Therefore, we propose to create standardised contract conditions for AI.

Summarising, current uncertainty in the market leads to higher transaction costs for governments and technology providers and a growing barrier for AI implementations. If we can harmonise the trust relationship between government and tech providers we will reduce these market inefficiencies, and use the European procurement framework to strengthen the European market for AI solutions.

1. **Background**

Internationally, we have based the draft city procurement conditions on

* the AI Ethical Guidelines of the European Commission,
* the AI Procurement Guidelines the British Government made in collaboration with World Economic Forum,
* “a governance framework for algorithmic accountability and transparency” of the European Parliament and
* the recommendations for regulation by the European Council.

At national level,

* responding to a motion in 2018, the Dutch Minister for Judicial Protection Sander Dekker developed guidelines to safeguard against the risk of data analysis by the government. These guidelines were the starting point for the
* draft procurement contract conditions we are creating for cities in the Netherlands in Amsterdam.
* Finally, a report about the oversight on algorithms by the Dutch government provided an overview of the Dutch situation, that we will use as a reference case for European AI contract conditions.

At global city level,

* New York City has installed a “ task force for Algorithmic Decision Systems”, aiming to increase accountability and transparency of algorithms. However, there has been a lotof critique of the results of this task force. As we have learned from the New York example of an algorithmic oversight commission, there is too little skills and too much risk aversion in government and the private sector to be transparent about algorithms.

In other words, the mechanisms for algorithmic transparency and fairness in government and companies are not optimal. It is our aim to define these mechanisms here.

**2. Initial scoping of \* technical \* minimal capabilities**

As a minimum interoperable definition, we have to start with defining what we mean with “algorithms”. We hereby reference the terminology used by the Dutch Ministry of Justice. Also, it allows for a technical scope ranging from complex decision tree rules till deep learning models, while excluding traditional automated decision making as referenced in GDPR.

Since we are proposing minimal technical capabilities, we are not taken into account here the processes in which AI applications are being bought, procured, and/or organisational aspects to AI control frameworks like risk assessments .

We are defining here ‘draft minimal capabilities for algorithms’ to be used in contract conditions, consisting of the following 6 minimal capabilities. For a full overview of our draft contract conditions, we refer to this document.

**Procedural Transparency**

* Full disclosure of the choices made, parties involved, risks and mitigation actions in the process of creating an algorithmic model

**Technical Transparency meaning**

* full disclosure for the buyer of the source code and model to be able to explain the model to citizens or other stakeholders
* a license to use the data to maximize multiple use cases in one government
* Access to the learnings of the model to prevent vendor lock-ins
* There should be a general understanding of the process by which an algorithmic system makes decisions in an overall system, ie. the goals and outcomes of an algorithm.

**Technical Explainability**

* Ability to explain on an individual level how a model creates certain outcomes.
* When using the algorithmic contract conditions it should always be specified to whom the information will be classified: public servants, other experts, etc.

**Fairness**

* Fairness is discussed through the lens of social justice, highlighting the potential for algorithmic systems to systematically disadvantage, or even discriminate against, different social groups and demographics. Defining fairness as a MIM: ”Fairness reflects the appreciation of a situation based on a set of social values, such as promoting equality in society”.

**Context**

* The assessment of fairness depends on facts, events, and goals, and therefore has to be understood as situation or task-specific and necessarily addressed within the scope of practice.
* Mechanisms for behavioural transparency may need to be designed into systems, and typically require the participation of the developers or operators of systems

**Accountability**

* Accountability for the supplier to create algorithms respecting human digital rights, and is compliant with federal, state, and local anti-discrimination laws.
* Agencies should not procure algorithms that are shielded from an independent validation and public review because of trade-secret or confidentiality claims

It should be noted that these capabilities should be applied differently to different systems depending on the nature, context and goals of the algorithmic system.

Technically, these capabilities can be translated into a metadata API that every vendor would provide, when supplying high impact algorithms to cities. Technically, there are also various fairness standards and frameworks to quantify the legal terms used above. For example, for fairness, there are many definitions of fairness that have been proposed in the literature. However, most of them are based on the following six, and they can be quantified.

* Unawareness
* Demographic Parity
* Equalized Odds
* Predictive Rate Parity
* Individual Fairness
* Counterfactual fairness equal probability of being labelled positively

