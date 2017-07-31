.. container:: wy-alert wy-alert-warning

   **This document was translated by a machine.**

   We want to make our country more efficient. We believe humans and machines should complement each other. Artificial Intelligence is the technology that will enable such symbiosis.
   This document has been translated using a mix of state-of-the-art machine translation and human-driven AI. The raw machine translation output has been edited by an automated system trained on millions of professionally corrected sentences. Finally, a human went through the document to make sure that no information had been lost.

   This means leaving behind some stylistic improvements and potential errors. However, this AI-augmented approach to translation allowed us to prepare this English version at a fraction of the cost and time of the legacy translation process.
   
   Visit the `Github repository <https://github.com/italia/pianotriennale-ict-doc-en>`_ dedicated to contribute with feedback and changes to the Three Year Plan for the Digital Transformation of the Public Administration.

Interoperability Model 
=======================

The Interoperability Model is a supporting axis necessary for the
functioning of the entire Public Information System.

This Model makes it possible to collaborate between Public
Administrations and between these and third parties through
technological solutions that ensure interaction and exchange of
information without constraints on implementations, avoiding ad hoc
integrations.

The Interoperability Model:

-  Enables the development of new applications for PA users consistent
   with the activities described in Chapter 7 "Tools for Generating and
   Delivering Digital Services" and with the objectives of the Plan;

-  Ensures dialogue within individual ecosystems and between ecosystems;

-  Regulates the use of Intangible Infrastructure components by
   regulating their sharing and publication;

-  Regulates the ways in which data streams are sent to the Data &
   Analytics Framework;

-  Ensures, in the respect of the right to privacy, access to public
   administration data also by third parties;

-  Is designed in accordance with the principles still valid in the
   `European Interoperability
   Framework <https://joinup.ec.europa.eu/sites/default/files/5e/db/a3/isa_annex_ii_eif_en.pdf>`__
   (EIF) version 2.0 [66]_, published in 2010 under the program
   `Interoperability Solutions for Public Administration, Businesses
   and <https://ec.europa.eu/isa2/isa2_en>`__\  [67]_ Citizens (ISA,
   2016 ISA²).

Current scenario
----------------

In October 2005, CNIPA (today AgID) published a set of documents that
constitute the technical reference for interoperability between public
administrations. These documents outline the technical and implementing
framework of the Public Co-operation System (SPC Coop). AgID is in the
process of consolidating the definition of the new Interoperability
Model which goes beyond the previous model and will be defined with
appropriate guidelines.

The new Model, as anticipated by the recent changes to the CAD with the
repeal of Article 58, allows to overcome the need for agreements for the
exchange of point-to-point information.

Strategic objectives
--------------------

-  Harmonise the architectural choices of the Public Administration,
   specifying the conditions required for joining the PA Information
   System.

-  Create the technological conditions that encourage the development of
   innovative, citizen-oriented, business and government-based
   application solutions by administrations and businesses and enabling
   the use of the services described in Chapter 4 "Intangible
   Infrastructures".

-  Promote the adoption of the API first approach to foster the
   separation of back end and front-end levels with open logic and
   public standards that guarantee other players, public and private,
   accessibility and maximum interoperability of data and services.

-  Prioritise technology standards that meet the need to ensure
   interaction between public administrations and those with citizens
   and businesses.

-  Enable data flow useful to the population of the Data & Analytics
   Framework.

-  Simplify the procedures for the exchange of services between Public
   Administrations and, where possible, between Public Administration
   and private individuals, through publication of participation rules
   in the guidelines.

-  Ensure compliance with the guidelines and promote the quality of the
   PA's services.

Lines of action
---------------

The Interoperability Model defines the guidelines that all Public
Administrations will have to take to ensure interoperability of their
systems with those of other subjects and the overall implementation of
the PA Information System.

Technological standards will reflect the *best practice* in the
interoperability of information systems and / or will adhere to
established standards, including within the EU.

All administrations must adhere to the new interoperability model's
technological standards and interoperability profiles to define and
present compliant *Application Programming Interface* (API).

APIs will have to resort to best management practices (API management),
including in particular:

-  Traceability of different versions of APIs in order to allow
   non-destructive evolution (*versioning*);

-  Coordinated documentation with the API version (*documentation*);

-  User management, in particular authentication and authorisation;

-  Usage restrictions related to the characteristics of the API itself
   and the user class (*throttling*);

-  Traceability of requests received and their outcome (logging *and
   accounting*), also for the purpose of non-repudiation of
   communication;

-  Testing environment

-  Software interfaces for third-party strategic services (SDKs);

-  An adequate level of service according to the type of service
   provided (SLA);

-  Scalable resource configuration;

-  Publishing usage metrics (*analytics*).

In this perspective, there is no single centralised element
*(*\ middleware) which mediates access to PA services and instead it is
expected that AgID, directly or indirectly:

-  Furnishes a distributed catalogue of APIs and services available with
   a unique access interface;

-  Verifies compliance with the rules of the Interoperability Model as a
   condition of access to the catalogue;

-  Continuously checks compliance with the requirements for registration
   to the catalogue;

-  Assists in resolving issues with appropriate cooperation tools (e.g.
   Help desk, forums, mailing lists and newsletters);

-  Establishes, publishes, and monitors usage metrics;

-  Provides libraries and SDKs to provide many of the features defined
   in the guidelines.

Consistent with the repeal of Article 58 of the CAD, there will no
longer be agreements between administrations; AgID will establish API
membership guidelines.

Public Administrations will be responsible for defining the terms of use
of the APIs they are exposed to.

The rules for the adherence of private individuals will then be defined.

In order to promote and coordinate all activities, AgID:

-  Will support the activities described in Chapter 6 "Ecosystems" and,
   more generally, the administrations involved in adapting their
   systems to the new interoperability Model;

-  Will ensure that the Interoperability Model is constantly updated
   from a technological point of view.

+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Subject       | New Interoperability Model Guidelines                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Time Frames   | By December 2017                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Players       | AgID                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Description   | Issue of useful guidelines for Public Administrations and other players in the PA's Information System to adhere to the Interoperability Model. More precisely, the indications that will need to be adopted (in terms of technology standards, interoperability profiles and communication protocols) will be provided for the implementation of the APIs needed to adapt the components described in Chapter 4 "Intangible Infrastructure" and in Chapter 6 "Ecosystems". Indications will also be provided for the implementation of new end-user applications, described in Chapter 7 "Tools for Generating and Delivering Digital Services" and for populating the *Data & Analytics Framework.*   |
|               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|               | The publication of the guidelines will be preceded by the issuance of a document showing the evolutionary roadmap from the old to the new model and a phase-out plan for the old-model infrastructural elements that are being decommissioned.                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Result        | | Guidelines for Transit to the New Interoperability Model                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|               | | *(Release date: May 2017)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|               | | New Interoperability Model Guidelines                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|               | | *(Release date version 1.0: December 2017)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Subject       | Adoption of the Model by PAs                                                                                                                                                                                                                                                                                                                                                                                                 |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Time Frames   | From May 2017                                                                                                                                                                                                                                                                                                                                                                                                                |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Players       | AgID, PA                                                                                                                                                                                                                                                                                                                                                                                                                     |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Description   | For existing platforms and ongoing design activities, PAs adopt transition guidelines, while new designs are adapted to the new Model.                                                                                                                                                                                                                                                                                       |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Result        | ---                                                                                                                                                                                                                                                                                                                                                                                                                          |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Subject       | API catalogue                                                                                                                                                                                                                                                                                                                                                                                                                |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Time Frames   | From June 2017                                                                                                                                                                                                                                                                                                                                                                                                               |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Players       | AgID                                                                                                                                                                                                                                                                                                                                                                                                                         |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Description   | AgID will create a special API catalogue, which will allow the PA to share APIs. Through the information recorded in the catalogue, a display point is created in which user-shared APIs will be censored and documented, and useful to developers and other stakeholders involved in ecosystems. However, in respect of the privacy rights regarding the data processed, APIs may also be used by parties outside the PA.   |
|               |                                                                                                                                                                                                                                                                                                                                                                                                                              |
|               | AgID will define a set of usage rules and a governance model for management.                                                                                                                                                                                                                                                                                                                                                 |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Result        | First release of the catalogue (release date: December 2017)                                                                                                                                                                                                                                                                                                                                                                 |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Subject       | API population catalogue                                                                                                                                                                              |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Time Frames   | From January 2018                                                                                                                                                                                     |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Players       | PA                                                                                                                                                                                                    |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Description   | PAs, in implementing the rules of the Interoperability Model, will follow the implementation of APIs and the subsequent population of the catalogue in order to facilitate their use by developers.   |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Result        | ---                                                                                                                                                                                                   |
+---------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

.. rubric:: Notes

.. [66]
   `*https://joinup.ec.europa.eu/sites/default/files/5e/db/a3/isa\_annex\_ii\_eif\_en.pdf* <https://joinup.ec.europa.eu/sites/default/files/5e/db/a3/isa_annex_ii_eif_en.pdf>`__

.. [67]
   `*https://ec.europa.eu/isa2/isa2\_en* <https://ec.europa.eu/isa2/isa2_en>`__
