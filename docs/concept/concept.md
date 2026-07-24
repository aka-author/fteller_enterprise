# Business Concept

The business provides a **research-based fortune-telling service through professional fortune tellers**.

The service interprets minor events, signs, coincidences, dreams, and similar experiences using documented legends, beliefs, myths, and traditional interpretations collected from different cultures.

Professional fortune tellers use the service with their own clients. They remain the customer-facing service providers, while the digital service supplies the underlying interpretations and conversational support.

The business therefore combines three things:

**scientific data > digital interpretation service > existing fortune-telling market**

The objective is to turn a scientifically maintained collection of cultural knowledge into a profitable online service.

# Customer Need

People regularly experience minor events that they may perceive as meaningful: an unusual dream, an accidental encounter, an object breaking, an animal appearing unexpectedly, or some other coincidence.

Such events can create uncertainty or anxiety. The architecture assumes that giving an event an interpretation can provide a person with a greater sense of control.

Fortune tellers already serve an audience interested in such interpretations. This makes them a natural distribution channel for the service.

# Value Proposition

The service does not claim to possess supernatural knowledge.

Instead, it answers questions such as:

> How has this kind of event been interpreted in different cultures and traditions?

The client receives an interpretation presented in the familiar form of a conversation with a fortune teller, while the underlying content comes from documented cultural sources.

This combination is intended to provide two kinds of value:

**for the client:** an understandable interpretation of an otherwise ambiguous event;

**for the fortune teller:** access to a much larger and better structured body of traditional interpretations than an individual practitioner could maintain personally.

The service is therefore designed to resemble fortune telling without pretending that the system itself has supernatural abilities.

# Participants and Roles

The architecture involves four main participants.

**Client**

The end customer who wants an event, sign, or experience interpreted.

**Delivery Partner**

A professional fortune teller who provides the service to the Client and uses the digital system as part of the consultation.

**Provider**

The organization that operates the digital service, maintains the commercial relationship with Delivery Partners, and receives B2B revenue.

**Associate Researcher**

A humanities scholar who contributes material to the scientific database and can also use its search facilities for research.

The Provider and the Delivery Partner interact through the **Fortuneteller Partnership Program**.

# Service Delivery

The Delivery Partner receives a question or description of an event from the Client.

The digital service then searches the scientific database for relevant beliefs, legends, signs, myths, and traditional interpretations.

FT AI uses this material to support a conversation resembling an interaction with a fortune teller.

The result is returned through the Delivery Partner to the Client.

The operational chain is therefore:

**Client > Fortune Teller > Fortune-Telling Service > LISM**

and the interpretation flows back:

**LISM > Fortune-Telling Service > Fortune Teller > Client**

The fortune teller remains responsible for the relationship with the Client. The digital system supplies the knowledge and interpretation capability behind that relationship.

# Revenue Model

The architecture separates the retail relationship from the Provider's revenue.

The **Client buys the service from the fortune teller**.

The fortune teller acts as the Delivery Partner and retains a **retail margin**.

The Provider supplies the underlying digital service and receives **B2B revenue** from the Delivery Partner.

The commercial flow can therefore be summarized as:

**Client payment > Delivery Partner retail margin + Provider B2B revenue**

This allows the Provider to reach the consumer market without building its entire customer-acquisition model around direct B2C sales.

The architecture defines the general model but does not yet specify whether the Provider charges per consultation, by subscription, by prepaid credits, or through another pricing mechanism.

# Knowledge Base and Research

The central knowledge asset is **LISM**.

LISM contains scientific data about legends, signs, interpretations, myths, beliefs, and related cultural material.

Humanities scholars contribute information to the database. A Maintainer manages the collection, while the search service makes the accumulated material available both to researchers and to the commercial fortune-telling service.

This creates a second value chain alongside the commercial one:

**research contributions > structured scientific data > searchable knowledge**

The commercial service then uses the same knowledge:

**searchable knowledge > interpretation > consultation > revenue**

Research and commercial activity therefore share the same underlying information asset rather than operating as separate systems.

# Constraints and Boundaries

Several principles limit what the service may do.

The service must be based on scientific collections of legends, interpretations, signs, and myths.

The interaction should resemble a conversation with a fortune teller.

The service must not frighten clients or encourage dangerous decisions.

The service and its terms must comply with applicable local regulations.

These constraints are important because the service occupies an unusual position: it uses the form and language of fortune telling while grounding its content in documented traditions rather than presenting invented predictions as facts.

# Architecture in One View

The complete business can be reduced to two connected flows.

**Knowledge flow**

**Researchers > LISM > Search > FT AI > Fortune-Telling Service**

**Commercial flow**

**Provider > Delivery Partner > Client**

The two flows meet in the Fortune-Telling Service.

LISM supplies the knowledge.

FT AI turns that knowledge into a conversational interpretation.

The Provider operates the service.

The fortune teller sells and delivers it.

The Client pays for the resulting consultation.

This is the central idea of the architecture.
