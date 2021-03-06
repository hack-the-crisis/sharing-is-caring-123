
# Solution Overview

SCI-CHAIN: The blockchain platform for sharing lab research and medical data to accelerate work on vaccine and improve knowledge on `COVID-19`

# What does our product solve

In the context of `COVID-19` pandemics, the time to delivery of essential data to apply countermeasures and design a vaccine is of outmost importance. However, at current pace of the spread of pandemics across the world, a reliable research and medical data is broadcasted too slow to peer reviewers whose feedback is crucial to turn the research into material product approved by the Regulator, manufactured in a factory and delivered to the general public. This is predominantly due to three reasons which are described in detail below.

## Bureaucracy

The slowness in publishing research work is caused by repetitive and redundant administrative tasks unrelated to the research effort, such as a need to secure copyright over the content, providing a uniquevocal intellectual property recognition back to the author or her/his employer, using qualified digital signatures to validate the identities of authors and publishers, and selecting information hubs of high reputation from data availability and security perspective. 

## The erosion of trusted third parties

Traditionally, authentication, timestamping and reputation are provided by central authorities or recognized bodies. However, these are now overrun by emergency tasks and are further impacted by a reduction of available staff to support the ongoing activities. A weak level of digitization also hampered the pace at which critical research data is published or distributed due to a need for a series of in-person interactions to collect the necessary administrative paperwork before a formal submission can take place. 

## Duplicate work

Proliferation of copies of the same data generates redundant activities across small community pockets unrelated or unaware of each other. Subsequent research linked to a particular copy would gather a limited recognition and cause a duplication of work based on the same piece of data. As a result, these issues are burning scarce time and resources.

<img src="https://github.com/hack-the-crisis/sharing-is-caring-123/blob/master/today.png"  width="480" />

# Our solution

Our platform is a showcase of functionalities that allow for a submission of research data and tracking of subsequent activities related to its lifecycle (peer reviews, approals for manufacturing and other activities). It does so while making sure the integrity of data and unique identification of changes is maintained. We intend to address this platform to two parties holding distinct roles:

## End users (research staff, peer reviewers, academics, general public)

From the user perspective, our application is leveraging *BCAssetManagement*, an integrated IBM-owned framework for acceleration of application development for demonstration purposes. Our application built on the basis of that framework will allow every submission and subsequent interaction of a research or medical data is supplied with a (i) digital timestamp of the data regardless of its binary and presentation form supplied with (ii) cryptographic proof of document content, (iii) a unique identifier of a content submitter and (iv) capability to register subsequent activities that can be tracked to a uniquely identifiable piece of research.

## Trust anchors (public safety bodies, general government, health and safety agencies, regulator)

From the service provider perspective, we build our solution on the backend that is based on *Hyperledger Fabric*, an open-source permissioned blockchain platform developed by Hyperledger and licensed under Apache 2.0. This choice is allowing service providers to deploy an application to avoid relying on central gateways that are prone to failure or delayed actions. Blockchain built in form of a distributed ledger network will address the need for data immutability, timestamp and tracking capabilities.

# Current state of work and next steps

So far our efforts were focused on the following activities:

(a) infrastructure deployment and use case design at a presentation layer<br>
(b) refining the business case for presentation purposes. <br>

It resulted with a mix of technical and business activities executed by all team members and a number of deliverables:

(a) technical script for our scenario leveraging BCAssetManagement framework and Hyperledger Fabric platform.<br>
(b) deployment instructions and user stories to recreate our presentation scenario.<br>
(c) demo environment for the use by the general public.<br>

We are planning to extend the functionality of the application to analytics endpoint that would provide interfaces for in-depth analytics of data already placed on the distributed ledger and generate insights out of it. We also intend to build a layer of RESTful APIs to open the application content to a wider ecosystem of contributors with their own applications and services built on top of SCI-CHAIN.

We are planning to broadcast the information about this solution to the wider public, including both central government institutions responsible for public healthcare facilities, the commercial sector responsible for manufacturing of vaccines and research community in general. Depending on their role, we want to onboard them either as network participants acting as trustless gateways to the service or network service consumers, using the functionality built on top.

<img src="https://github.com/hack-the-crisis/sharing-is-caring-123/blob/master/solution.png"  width="768" />

# The impact of our solution on the COVID-19 crisis

We believe that our showcase can be quickly transformed into a deployed network of nodes can act as trustless gateways for document and research content submissions which can then be subsequently cross-verified for timestamp, document integrity and supplied identity across the entire network. This will radically shorten the amount of time needed to :

(a) verify the origin of the document and thus, IPR ownership <br>
(b) access a tamper-proof copy of a document from anywhere in the world <br>
(c) track all activities related to a uniquely identifiable research material across its lifecycle.<br>

To make the above happen we need to be able to pitch the idea to business decision makers participating in a supply chain of information needed from preliminary research results to manufacturing of an approved vaccine. These include, among others, key public healthcare institutions, research facilities, lab testing organizations, universities and pharmaceutical companies.

<img src="https://github.com/hack-the-crisis/sharing-is-caring-123/blob/master/proposal.png"  width="480" />
