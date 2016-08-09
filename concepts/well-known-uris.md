---
layout:    page
title:     "Well-Known URIs"
permalink: /concepts/well-known-uris
---



The following 11 Well-Known URI definitions (11 distinct values) were found in [all available `webconcepts.info` specifications](/specs). Please be advised that the table shown here is maintained and compiled from [Web Concepts](/) sources. The [official Well-Known URI registry](http://www.iana.org/assignments/well-known-uris/well-known-uris.xhtml) is maintained by the [*Internet Assigned Numbers Authority (IANA)*](http://www.iana.org/).

Well-Known URI | Specification
-------: | :-------
[`caldav`](/concepts/well-known-uri/caldav) | [**RFC 6764**: Locating Services for Calendaring Extensions to WebDAV (CalDAV) and vCard Extensions to WebDAV (CardDAV)](/specs/IETF/RFC/6764 "This specification describes how DNS SRV records, DNS TXT records, and well-known URIs can be used together or separately to locate CalDAV (Calendaring Extensions to Web Distributed Authoring and Versioning (WebDAV)) or CardDAV (vCard Extensions to WebDAV) services.")
[`carddav`](/concepts/well-known-uri/carddav) | [**RFC 6764**: Locating Services for Calendaring Extensions to WebDAV (CalDAV) and vCard Extensions to WebDAV (CardDAV)](/specs/IETF/RFC/6764 "This specification describes how DNS SRV records, DNS TXT records, and well-known URIs can be used together or separately to locate CalDAV (Calendaring Extensions to Web Distributed Authoring and Versioning (WebDAV)) or CardDAV (vCard Extensions to WebDAV) services.")
[`core`](/concepts/well-known-uri/core) | [**RFC 6690**: Constrained RESTful Environments (CoRE) Link Format](/specs/IETF/RFC/6690 "This specification defines Web Linking using a link format for use by constrained web servers to describe hosted resources, their attributes, and other relationships between links. Based on the HTTP Link Header field defined in RFC 5988, the Constrained RESTful Environments (CoRE) Link Format is carried as a payload and is assigned an Internet media type. &#34;RESTful&#34; refers to the Representational State Transfer (REST) architecture. A well-known URI is defined as a default entry point for requesting the links hosted by a server.")
[`genid`](/concepts/well-known-uri/genid) | [**W3C TR http://www.w3.org/TR/rdf11-concepts**: RDF 1.1 Concepts and Abstract Syntax](/specs/W3C/TR/rdf11-concepts "The Resource Description Framework (RDF) is a framework for representing information in the Web. This document defines an abstract syntax (a data model) which serves to link all RDF-based languages and specifications. The abstract syntax has two key data structures: RDF graphs are sets of subject-predicate-object triples, where the elements may be IRIs, blank nodes, or datatyped literals. They are used to express descriptions of resources. RDF datasets are used to organize collections of RDF graphs, and comprise a default graph and zero or more named graphs. RDF 1.1 Concepts and Abstract Syntax also introduces key concepts and terminology, and discusses datatyping and the handling of fragment identifiers in IRIs within RDF graphs.")
[`ni`](/concepts/well-known-uri/ni) | [**RFC 6920**: Naming Things with Hashes](/specs/IETF/RFC/6920 "This document defines a set of ways to identify a thing (a digital object in this case) using the output from a hash function. It specifies a new URI scheme for this purpose, a way to map these to HTTP URLs, and binary and human-speakable formats for these names. The various formats are designed to support, but not require, a strong link to the referenced object, such that the referenced object may be authenticated to the same degree as the reference to it. The reason for this work is to standardise current uses of hash outputs in URLs and to support new information-centric applications and other uses of hash outputs in protocols.")
[`posh`](/concepts/well-known-uri/posh) | [**RFC 7711**: PKIX over Secure HTTP (POSH)](/specs/IETF/RFC/7711 "Experience has shown that it is difficult to deploy proper PKIX certificates for Transport Layer Security (TLS) in multi-tenanted environments. As a result, domains hosted in such environments often deploy applications using certificates that identify the hosting service, not the hosted domain. Such deployments force end users and peer services to accept a certificate with an improper identifier, resulting in degraded security. This document defines methods that make it easier to deploy certificates for proper server identity checking in non-HTTP application protocols. Although these methods were developed for use in the Extensible Messaging and Presence Protocol (XMPP) as a Domain Name Association (DNA) prooftype, they might also be usable in other non-HTTP application protocols.")
[`reload-config`](/concepts/well-known-uri/reload-config) | [**RFC 6940**: REsource LOcation And Discovery (RELOAD) Base Protocol](/specs/IETF/RFC/6940 "This specification defines REsource LOcation And Discovery (RELOAD), a peer-to-peer (P2P) signaling protocol for use on the Internet.  A P2P signaling protocol provides its clients with an abstract storage and messaging service between a set of cooperating peers that form the overlay network.  RELOAD is designed to support a P2P Session Initiation Protocol (P2PSIP) network, but can be utilized by other applications with similar requirements by defining new usages that specify the Kinds of data that need to be stored for a particular application.  RELOAD defines a security model based on a certificate enrollment service that provides unique identities.  NAT traversal is a fundamental service of the protocol.  RELOAD also allows access from &#34;client&#34; nodes that do not need to route traffic or store data for others.")
[`stun-key`](/concepts/well-known-uri/stun-key) | [**RFC 7635**: Session Traversal Utilities for NAT (STUN) Extension](/specs/IETF/RFC/7635 "This document proposes the use of OAuth 2.0 to obtain and validate ephemeral tokens that can be used for Session Traversal Utilities for NAT (STUN) authentication. The usage of ephemeral tokens ensures that access to a STUN server can be controlled even if the tokens are compromised.")
[`timezone`](/concepts/well-known-uri/timezone) | [**RFC 7808**: Time Zone Data Distribution Service](/specs/IETF/RFC/7808 "This document defines a time zone data distribution service that allows reliable, secure, and fast delivery of time zone data and leap-second rules to client systems such as calendaring and scheduling applications or operating systems.")
[`void`](/concepts/well-known-uri/void) | [**W3C TR http://www.w3.org/TR/void**: Describing Linked Datasets with the VoID Vocabulary](/specs/W3C/TR/void "VoID is an RDF Schema vocabulary for expressing metadata about RDF datasets. It is intended as a bridge between the publishers and users of RDF data, with applications ranging from data discovery to cataloging and archiving of datasets. This document is a detailed guide to the VoID vocabulary. It describes how VoID can be used to express general metadata based on Dublin Core, access metadata, structural metadata, and links between datasets. It also provides deployment advice and discusses the discovery of VoID descriptions.")
[`webfinger`](/concepts/well-known-uri/webfinger) | [**RFC 7033**: WebFinger](/specs/IETF/RFC/7033 "This specification defines the WebFinger protocol, which can be used to discover information about people or other entities on the Internet using standard HTTP methods. WebFinger discovers information for a URI that might not be usable as a locator otherwise, such as account or email URIs.")