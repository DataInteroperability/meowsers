The Experience API (xAPI)
Conformance Requirements for Learning Record Stores

Version 1.0.3

**
**

**Megan Bowe, 
Technical Editor**

![image alt text](image_0.png)

Under contract #W911QY-16-C-0109 by

![image alt text](image_1.png)

The Experience API (xAPI) Conformance Requirements for Learning Record Stores Version 1.0.3

Copyright 2016, Data Interoperability Standards Consortium

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, this is distributed under the License and is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

Table of Contents

[[TOC]]

# Introduction

The Experience API (xAPI) specification contains technical information for a variety of audiences. Vendors, product managers and developers need to know which specific information is critical to making their Learning Record Stores (LRSs) conformant to the xAPI specification.

The Data Interoperability Standards Consortium, contracted by the Advanced Distributed Learning Initiative to support LRS Conformance Testing, collected and structured this information in a format that follows the document structure of Version 1.0.3 of the xAPI specification.

This document provides a detailed accounting of the xAPI conformance requirements as defined in the specification. LRS products must adhere to these requirements to be recognized as xAPI-conformant. To achieve a conformance label, all conformance requirements for the associated product must be met.

## Purpose

In 1997, the US Department of Defense (DoD) established the Advanced Distributed Learning (ADL) Initiative to develop a DoD-wide strategy for using learning and information technologies to modernize education and training. The ADL Initiative defined requirements for to responsibly share essential learning data between applications using common API specifications and data models and provide a sound economic basis for investment. xAPI is the first of these services focused on sharing data about learning experiences.

It is highly recommended that the reader is familiar with the documentation for xAPI, Version 1.0.3, before reading this document.

## Scope

**This document documents the conformance requirements put forth by Version 1.0.3 of the xAPI specification that must be implemented by Learning Record Stores (LRSs).** In the case of a conflict between conformance requirements described herein and the specification, the specification is the authoritative document.

Passing conformance testing based on the conformance requirements documented herein does not mean *all* the requirements described in the xAPI-specification have been met. Some requirements are difficult, if not impossible to test in an automated way. In the xAPI-specification are described best practices (SHOULDs) as well as permissible and encouraged practices (MAYs) which are not accounted for in this conformance requirements document. 

Future versions of this document, in lieu of other conformance requirements documents, *may* address xAPI’s conformance requirements for other product categories, such as:

1. Learning Management Systems supporting the following xAPI profiles:

    1. cmi5

    2. SCORM

2. Learning Record Providers, vis a vis **content** launched by systems supporting the following xAPI profiles:

    3. cmi5

    4. SCORM

3. Learning Record Consumers, such as dashboards and/or data analysis software.

# Community Contributors

Aaron Silvers, Data Interoperability Standards Consortium

Alex Horan, Riptide Learning

Amanda Bond

Andrew Downes, Watershed LRS

Andy Creighton, ADL

Andy Johnson, ADL

Anthony Altieri, Omnes Solutions

Avron Barr, IEEE-LTSC

Ben Betts, HT2 Labs

Charles Touron, Department of Army

Chris Raasch, Data Interoperability Standards Consortium

David Pate, Riptide Learning

Freddie O’Connell, Rustici Software

James Mullaney, HT2 Labs

Jason Haag, ADL

Jeffery Palazzo

Jessie Chuang, Classroom Aid

John Blackmon, Trivantis

J. Pablo Caballero, Acutilis

Henry Ryng

Kyle Moran, ADL

Liliana Behny, Department of Army

Lou Wolford, ADL

Mark Grant

Megan Bowe, Data Interoperability Standards Consortium

Michael Thompson, Department of National Defence

Michael Yudelson, Carnegie Learning/Carnegie Mellon University

Nick Washburn, Riptide Learning

Pankaj Agrawal, Next Software Solutions

Russell Duhon, SaltBox

Ryan Smith, HT2 Labs

Shelly Blake-Plock, Yet Analytics

Steven Vergenz, ADL

Tamara Krepps, Department of Army

Tom Creighton, ADL

Tyler Dixon, Riptide Learning

Wendy Wickham, Data Interoperability Standards Consortium

# Conventions

## Definitions

**Conformant**

A Learning Record Store (LRS) shall be considered conformant if it, when tested properly, follows the entirety of the conformance requirements identified herein. These requirements are applicable to versions 1.0.0, 1.0.1, 1.0.2, and 1.0.3 of the Experience API specification. 

## Keywords

The keywords "MUST", “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” in this document should be interpreted as described in IETF [RFC 2119](https://tools.ietf.org/html/rfc2119).

## Identifiers

To identify a particular conformance requirement, the following convention applies:

xAPI-xxxxx

*Example*: **xAPI-00001** refers to the first conformance requirement identified in the xAPI specification.

# Reference Specifications

"AICC/CMI-5_Spec_Current." GitHub. August 26, 2016. Accessed September 27, 2016. [https://github.com/AICC/CMI-5_Spec_Current](https://github.com/AICC/CMI-5_Spec_Current).

Bradner, S. "RFC 2119 - Key Words for Use in RFCs to Indicate Requirement Levels." RFC 2119 - Key Words for Use in RFCs to Indicate Requirement Levels. March 1997. Accessed September 27, 2016. [https://tools.ietf.org/html/rfc2119](https://tools.ietf.org/html/rfc2119).

"Data Elements and Interchange Formats — Information Interchange — Representation of Dates and times." ISO. 2004. Accessed September 27, 2016. [https://www.iso.org/obp/ui/#iso:std:iso:8601:ed-3:v1:en](https://www.iso.org/obp/ui/#iso:std:iso:8601:ed-3:v1:en).

"IEEE Standard for Floating-Point Arithmetic." IEEE Xplore Document - IEEE Standard for Floating-Point Arithmetic. August 29, 2008. Accessed September 27, 2016. doi:10.1109/IEEESTD.2008.4610935.

Jones, M., J. Bradley, and N. Sakimura. "RFC 7515 - JSON Web Signature (JWS)." RFC 7515 - JSON Web Signature (JWS). May 2015. Accessed September 27, 2016. [http://tools.ietf.org/html/rfc7515](http://tools.ietf.org/html/rfc7515).

"The Experience API (xAPI) Specification Version 1.0.3." GitHub. September 21, 2016. Accessed September 27, 2016. [https://github.com/adlnet/xAPI-Spec/](https://github.com/adlnet/xAPI-Spec/).

"xAPI-SCORM-Profile." GitHub. June 17, 2016. Accessed September 27, 2016. [https://github.com/adlnet/xAPI-SCORM-Profile](https://github.com/adlnet/xAPI-SCORM-Profile).

# Part Two:[ Experience API Data](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#parttwo)

# 1.0.[ Documents](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#documents)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

# 2.0.[ Statements](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#statements)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 2.1.[ Purpose](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#statement-purpose)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 2.2.[ Formatting Requirements](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#dataconstraints)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00001</td>
    <td>An LRS rejects with error code 400 Bad Request any Statement having a property whose value is set to "null", an empty object, or has no value, except in an "extensions" property</td>
  </tr>
  <tr>
    <td>XAPI-00002</td>
    <td>An LRS stores 32-bit floating point numbers with at least the precision of IEEE 754 </td>
  </tr>
  <tr>
    <td>XAPI-00003</td>
    <td>An LRS rejects with error code 400 Bad Request a Statement which does not contain an "actor" property </td>
  </tr>
  <tr>
    <td>XAPI-00004</td>
    <td>An LRS rejects with error code 400 Bad Request a Statement which does not contain a "verb" property </td>
  </tr>
  <tr>
    <td>XAPI-00005</td>
    <td>An LRS rejects with error code 400 Bad Request a Statement which does not contain an "object" property</td>
  </tr>
  <tr>
    <td>
XAPI-00006</td>
    <td>An LRS rejects with error code 400 Bad Request a Statement which uses the wrong data type</td>
  </tr>
  <tr>
    <td>XAPI-00007</td>
    <td>An LRS rejects with error code 400 Bad Request a Statement which uses any non-format-following key or value, including the empty string, where a string with a particular format (such as mailto IRI, UUID, or IRI) is required.</td>
  </tr>
  <tr>
    <td>XAPI-00008</td>
    <td>An LRS rejects with error code 400 Bad Request a Statement where the case of a key does not match the case specified in this specification.</td>
  </tr>
  <tr>
    <td>XAPI-00009</td>
    <td>An LRS rejects with error code 400 Bad Request a Statement where the case of a value restricted to enumerated values does not match an enumerated value given in this specification exactly.</td>
  </tr>
  <tr>
    <td>
XAPI-00010</td>
    <td>An LRS rejects with error code 400 Bad Request a Statement where a key or value is not allowed by this specification.</td>
  </tr>
  <tr>
    <td>XAPI-00011</td>
    <td>An LRS rejects with error code 400 Bad Request a Statement containing IRL or IRI values without a scheme.</td>
  </tr>
  <tr>
    <td>XAPI-00012</td>
    <td>The LRS rejects with error code 400 Bad Request parameter values which do not validate to the same standards required for values of the same types in Statements.</td>
  </tr>
  <tr>
    <td>XAPI-00013</td>
    <td>The LRS rejects with error code 400 Bad Request a token with does not validate as matching the RFC 5646 standard in the sequence of token lengths for language map keys.</td>
  </tr>
  <tr>
    <td>XAPI-00014</td>
    <td>All Objects are well-created JSON Objects (Nature of Binding) </td>
  </tr>
  <tr>
    <td>XAPI-00015</td>
    <td>All Strings are encoded and interpreted as UTF-8 </td>
  </tr>
</table>


## 2.3.[ Statement Lifecycle](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#lifecycle)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

#### 2.3.1.[ Statement Immutability](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#statement-immutability-and-exceptions)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

#### 2.3.2.[ Voiding](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#voided)

**Definitions**

1. A Voided Statement is defined as a Statement that is not a Voiding Statement and is the Target of a Voiding Statement within the LRS 

2. A Voiding Statement is defined as a Statement whose "verb" property's "id" property's IRI ending with "voided" 

3. A Voiding Statement's Target is defined as the Statement corresponding to the "object" properties "id" property's UUID 

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00016</td>
    <td>A Voiding Statement cannot Target another Voiding Statement. LRS behavior this new VOIDING statement MAY be rejected. If the LRS accepts that statement, the violating VOIDING statement SHOULD be ignored.</td>
  </tr>
  <tr>
    <td>XAPI-00017</td>
    <td>An LRS rejects a Voiding Statement with 400 Bad Request if the "objectType" field does not have a value of "StatementRef" </td>
  </tr>
  <tr>
    <td>XAPI-00018</td>
    <td>An LRS MUST consider a Statement it contains voided if the Statement is not itself a voiding Statement and the LRS also contains a voiding Statement referring to the first Statement. 

Test: Void a statement and then send a GET for that statement which uses "statementId" instead of “voidedStatementId.” The statement should then not be returned in the GET request, which should return a 404. </td>
  </tr>
  <tr>
    <td>XAPI-00019</td>
    <td>A Voiding Statement is defined as a Statement whose "verb" property's "id" property's IRI ending with "voided"</td>
  </tr>
  <tr>
    <td>XAPI-00020</td>
    <td>A Voiding Statement's "objectType" field has a value of "StatementRef" </td>
  </tr>
</table>


## 2.4.[ Statement Properties](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#statement-properties)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00021</td>
    <td>All Statement properties must be used at most one time. An LRS rejects with 400 Bad Request a statement that contains a JSON object with a duplicate key. </td>
  </tr>
  <tr>
    <td>XAPI-00022</td>
    <td>A "timestamp" property is a TimeStamp, per section 4.5. An LRS rejects with 400 Bad Request a statement if it has a TimeStamp and that TimeStamp is invalid.</td>
  </tr>
  <tr>
    <td>XAPI-00023</td>
    <td>A "stored" property is a TimeStamp, per section 4.5. An LRS assigns the "stored" property upon receipt with a valid TimeStamp. </td>
  </tr>
  <tr>
    <td>XAPI-00024</td>
    <td>An "authority" property is an Agent or Group. An LRS rejects with 400 Bad Request a statement which has an “authority” property which is not Agent or Group. </td>
  </tr>
  <tr>
    <td>XAPI-00025</td>
    <td>A Statement's "attachments" property is an array of Attachments. An LRS rejects with 400 Bad Request a statement which has an “attachments” property which is not an array of attachments.</td>
  </tr>
</table>


### 2.4.1.[ ID](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#stmtid)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00026</td>
    <td>An LRS generates the "id" property of a Statement if none is provided (Modify, 4.1.1.a)</td>
  </tr>
  <tr>
    <td>XAPI-00027</td>
    <td>A Statement's "id" property is a UUID following RFC 4122. An LRS rejects with 400 Bad Request a statement which has an "id" and that “id” is invalid. </td>
  </tr>
  <tr>
    <td>XAPI-00028</td>
    <td>A Statement's "id" property is a String. An LRS rejects with 400 Bad Request a statement which has an “id” and that property is not a string</td>
  </tr>
  <tr>
    <td>XAPI-00029</td>
    <td>All UUID types are in standard String form. An LRS rejects with 400 Bad Request a statement which has an property which is required to be a UUID and that property is not in standard string form</td>
  </tr>
  <tr>
    <td>XAPI-00030</td>
    <td>All UUID types follow requirements of RFC4122.  An LRS rejects with 400 Bad Request a statement which has a property which is required to be a UUID and does not follow RFC4122. </td>
  </tr>
</table>


### 2.4.2.[ Actor](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#actor)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00031</td>
    <td>An "actor" property's "objectType" property is either "Agent" or "Group" An LRS rejects with 400 Bad Request an actor with an "objectType" which is not “Agent” or “Group”</td>
  </tr>
</table>


#### 2.4.2.1 [When the Actor objectType is Agent](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#2421-when-the-actor-objecttype-is-agent)

**Definition**

1. An Agent is defined as an Actor with "objectType" of an "Agent", an instructor with "objectType" of an "Agent", or "object" property with value "Agent"

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00032</td>
    <td>An "objectType" property is a String. If present, the LRS must validate and reject with 400 Bad Request if invalid</td>
  </tr>
  <tr>
    <td>XAPI-00033</td>
    <td>A "name" property is a String. If present, the LRS must validate and reject with 400 Bad Request if invalid. </td>
  </tr>
  <tr>
    <td>XAPI-00034</td>
    <td>An "actor" property with "objectType" as "Agent" uses exactly one of the following Inverse Functional Identifier properties: "mbox", "mbox_sha1sum", "openid", "account". An LRS rejects with 400 Bad Request any agent object:
Where the IFI property is absent 
Where the IFI value is invalid
With more than one IFI</td>
  </tr>
</table>


#### 2.4.2.2[ When the Actor ObjectType is Group](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#2422-when-the-actor-objecttype-is-group)

**Definition**

1. An anonymous Group is defined when at least one of the following is true:

    * An "actor" property with “objectType” of “group” with the “member” property present, but without an IFI

    * A "context" object with a “team” property of “group” with the “member” property present

    * An "object" with the value “Group” with the “member” property present.

2. An identified Group is defined when at least one of the following is true:

    * An "actor" property with “objectType” of “group” and an IFI present

    * A "context" object with a “team” property of “group” and an IFI is present

    * An "object" with the value “Group” and an IFI present

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00035</td>
    <td>A Group uses the "member" property. An LRS rejects with 400 Bad Request if the "member" property is present anywhere but in a group object (Actor or team).  </td>
  </tr>
  <tr>
    <td>XAPI-00036</td>
    <td>The "member" property is an array of Objects following Agent requirements. An LRS rejects with 400 Bad Request any group object which has a member property with anything other than a valid array of Agents as a value</td>
  </tr>
  <tr>
    <td>XAPI-00037</td>
    <td>An "actor" property with "objectType" as "Group" uses exactly one of the following Inverse Functional Identifier properties: "mbox", "mbox_sha1sum", "openid", "account" or a member property with at least one Agent. An LRS rejects with 400 Bad Request any group object with:
no IFI and no member property
more than one IFI 
an invalid IFI value</td>
  </tr>
</table>


#### 2.4.2.3 [Inverse Functional Identifier](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#2423-inverse-functional-identifier)

**Definition**

An Inverse Functional Identifier (IFI) is a value of an Agent or Identified Group that is guaranteed to only ever refer to that Agent or Identified Group.

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00038</td>
    <td>An "mbox" property has the form "mailto:email address" and is an IRI. An LRS rejects with 400 Bad Request if a statement that uses the "mbox" IFI is an invalid form. </td>
  </tr>
  <tr>
    <td>
XAPI-00039</td>
    <td>An "mbox_sha1sum" property is a String An LRS rejects with 400 Bad Request if a statement uses the “mbox_sha1sum” IFI and it is not a valid string.</td>
  </tr>
  <tr>
    <td>
XAPI-00040</td>
    <td>An "openid" property is a URI. An LRS rejects with 400 Bad Request if a statement uses the “openID” IFI and the URI is invalid. </td>
  </tr>
  <tr>
    <td>XAPI-00041</td>
    <td>An “account” property is an object. An LRS rejects with 400 Bad Request if a statement uses an invalid Account Object. A valid account is defined by the requirements listed in XAPI-I-63 and XAPI-I-66</td>
  </tr>
</table>


#### 2.4.2.4[ Account Object](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#2424-account-object)

**Definition**

1. An Account Object is the "account" property of a Group or Agent 

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00042</td>
    <td>An Account Object's homePage" property is an IRL. An LRS rejects with 400 Bad Request if a statement uses the "account" IFI and the “homePage” property is absent or has an invalid IRL.</td>
  </tr>
  <tr>
    <td>XAPI-00043</td>
    <td>An Account Object "name" property is a String. An LRS rejects with 400 Bad Request if a statement uses the “account” IFI and the “name” property is absent or has an invalid string.</td>
  </tr>
</table>


### 2.4.3.[ Verb](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#verb)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00044</td>
    <td>A "verb" object contains an "id" property which is required to be an IRI. An LRS rejects with 400 Bad Request if a statement uses the Verb Object and "id" is absent or “id” is present, but the value is an invalid IRI. </td>
  </tr>
  <tr>
    <td>XAPI-00045</td>
    <td>A "verb" property's "display" property is a Language Map. An LRS rejects with 400 Bad Request if a statement uses the Verb Object’s “display” property and it is not a valid Language Map.</td>
  </tr>
</table>


### 2.4.4.[ Object](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#object)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00046</td>
    <td>An "object" property's "objectType" property is either "Activity", "Agent", "Group", "SubStatement", or "StatementRef". An LRS rejects with 400 Bad Request an "object" property with an objectType which is not "Activity", "Agent", "Group", "SubStatement", or "StatementRef".</td>
  </tr>
</table>


#### 2.4.4.1 [When the ObjectType is Activity](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#2441-when-the-objecttype-is-activity)

**Definition**

1. An Activity is defined by an "object" without "objectType" or with "objectType" having the value "Activity" 

2. An Activity Definition is defined as the contents of a "definition" property object of an Activity 

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00047</td>
    <td>An "object" property uses the "id" property exactly one time. The LRS must reject with 404 Bad Request an otherwise legal statement if the object's objectType is Activity and the object's "id" is not an IRI or the object’s “id” is absent</td>
  </tr>
  <tr>
    <td>XAPI-00048</td>
    <td>An "object" property uses the "definition" property at most one time. The LRS rejects with 400 Bad Request an otherwise legal statement if the object's “definition” property is an invalid object.</td>
  </tr>
  <tr>
    <td>XAPI-00049</td>
    <td>An Activity Definition's "interactionType" property is a String with a value of either true-false, choice, fill-in, long-fill-in, matching, performance, sequencing, likert, numeric or other. An LRS rejects with 400 Bad Request an Activity Definition's "interactionType" property if it is not a string value of true-false, choice, fill-in, long-fill-in, matching, performance, sequencing, likert, numeric or other.</td>
  </tr>
  <tr>
    <td>XAPI-00050</td>
    <td>An Activity Definition's "correctResponsesPattern" property is an array of Strings. An LRS rejects with 400 Bad Request an Activity Definition's "correctResponsesPattern" property if present, and if it is not a valid array of strings.  </td>
  </tr>
  <tr>
    <td>XAPI-00051</td>
    <td>An Activity Definition's "steps" property is an array of Interaction Components. An LRS rejects with 400 Bad Request if an Activity Definition's "steps" property if present, and is not a valid array of Interaction Components. </td>
  </tr>
  <tr>
    <td>XAPI-00052</td>
    <td>An Activity Definition's "target" property is an array of Interaction Components. An LRS rejects with 400 Bad Request if an Activity Definition's "target" property if present, and is not a valid array of Interaction Components. </td>
  </tr>
  <tr>
    <td>XAPI-00053</td>
    <td>An Activity Definition's "source" property is an array of Interaction Components. An LRS rejects with 400 Bad Request if an Activity Definition's "source" property if present, and is not a valid array of Interaction Components. </td>
  </tr>
  <tr>
    <td>XAPI-00054</td>
    <td>An Activity Definition's "scale" property is an array of Interaction Components, An LRS rejects with 400 Bad Request if an Activity Definition's "scale" property if present, and is not a valid array of Interaction Components. </td>
  </tr>
  <tr>
    <td>XAPI-00055</td>
    <td>An Activity Definition's "choices" property is an array of Interaction Components. An LRS rejects with 400 Bad Request if an Activity Definition's "choices" property if present, and is not a valid array of Interaction Components. </td>
  </tr>
  <tr>
    <td>XAPI-00056</td>
    <td>An Activity Definition's "name" property is a Language Map. The LRS rejects with 400 Bad Request an otherwise legal statement if the Activity Definition's "name" property is present and is an invalid Language Map.</td>
  </tr>
  <tr>
    <td>XAPI-00057</td>
    <td>An Activity Definition's "extension" property is an Object. The LRS rejects with 400 Bad Request an otherwise legal statement if the Activity Definition's "extension" property is present and is an invalid Extension Object. </td>
  </tr>
  <tr>
    <td>XAPI-00058</td>
    <td>Within an array of Interaction Components, the "id" property is a string which is required and unique (within the specific interaction array). The LRS rejects with 400 Bad Request an interaction activity with an array of interaction components in which the “id” property is absent, duplicative, or an invalid string. </td>
  </tr>
  <tr>
    <td>XAPI-00059</td>
    <td>An Activity Definition's "description" property is a Language Map. The LRS rejects with 400 Bad Request an otherwise legal statement if the Activity Definition's "description" property is present and is an invalid Language Map. </td>
  </tr>
  <tr>
    <td>XAPI-00060</td>
    <td>An Activity Definition's "type" property is an IRI. The LRS rejects with 400 Bad Request an otherwise legal statement if the Activity Definition's "type" property is present and is an invalid IRI. </td>
  </tr>
  <tr>
    <td>
XAPI-00061</td>
    <td>An Activity Definition's "moreinfo" property is an IRL. The LRS rejects with 400 Bad Request an otherwise legal statement if the Activity Definition's "moreinfo" property is present and is an invalid IRL. </td>
  </tr>
  <tr>
    <td>
XAPI-00062</td>
    <td>An Interaction Component’s "description" property is a Language Map. The LRS rejects with 400 Bad Request an otherwise legal statement if the Interaction Component's "description" property is present and is an invalid Language Map. </td>
  </tr>
  <tr>
    <td>
XAPI-00063</td>
    <td>An individual Interaction Component, within the array of Interaction Components, is an Object. The LRS rejects with 400 Bad Request an otherwise legal statement if the Interaction Component is present and is an invalid Object. </td>
  </tr>
  <tr>
    <td>
XAPI-00064</td>
    <td>An Activity Definition uses the "interactionType" property if correctResponsesPattern is present. An LRS rejects a statement with 400 Bad Request if a correctResponsePattern is present and interactionType is not. </td>
  </tr>
</table>


#### 2.4.4.2 [When the "Object" is an Agent or a Group](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#2442-when-the-object-is-an-agent-or-a-group)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00065</td>
    <td>Statements that use an Agent or Group as an Object MUST specify an "objectType" property. The LRS rejects with 400 Bad Request if the "objectType" property is absent and the Object is an Agent Object or Group Object. </td>
  </tr>
</table>


#### 2.4.4.3 [When the "Object" is a Statement](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#2443-when-the-object-is-a-statement)

**Definition**

1. A Statement Reference is defined by the "objectType" of an "object" with value "StatementRef"

2. A Sub-Statement is defined by the "objectType" of an "object" with value "SubStatement"

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00066</td>
    <td>A Sub-Statement follows the requirements of all Statements. The LRS rejects with 400 Bad Request a Statement with a Sub-Statement with any invalid statement properties in an otherwise valid sub-statement. </td>
  </tr>
  <tr>
    <td>
XAPI-00067</td>
    <td>A Sub-Statement cannot use the "authority" property. The LRS rejects with 400 Bad Request a Statement with a Sub-Statement where the "authority" property is present. </td>
  </tr>
  <tr>
    <td>
XAPI-00068</td>
    <td>A Sub-Statement cannot use the "version" property. The LRS rejects with 400 Bad Request a Statement with a Sub-Statement where the “version” property is present.</td>
  </tr>
  <tr>
    <td>
XAPI-00069</td>
    <td>A Sub-Statement cannot use the "stored" property.  The LRS rejects with 400 Bad Request a Statement with a Sub-Statement where the “stored” property is present.</td>
  </tr>
  <tr>
    <td>
XAPI-00070</td>
    <td>A Sub-Statement cannot use the "id" property at the Statement level  The LRS rejects with 400 Bad Request a Statement with a Sub-Statement where the “id” property is present.</td>
  </tr>
  <tr>
    <td>
XAPI-00071</td>
    <td>A Sub-Statement cannot have a Sub-Statement.  The LRS rejects with 400 Bad Request a Statement with a Sub-Statement which contains a Sub-Statement.</td>
  </tr>
  <tr>
    <td>
XAPI-00072</td>
    <td>A Statement Reference's "id" property is a UUID. The LRS rejects with 400 Bad Request a Statement Reference Object with an “id” property which is absent or an invalid UUID.</td>
  </tr>
  <tr>
    <td>XAPI-00073</td>
    <td>Statements that have a StatementRef or Sub-Statement as an Object MUST specify an "objectType" property. The LRS rejects with 400 Bad Request if the “objectType” property is absent and the Object is a StatementRef or Sub-Statement. </td>
  </tr>
</table>


### 2.4.5.[ Result](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#result)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00074</td>
    <td>A "success" property is a Boolean. The LRS rejects with 400 Bad Request a Statement which has a Result Object with a "success" property which does not have a valid Boolean value, if present. </td>
  </tr>
  <tr>
    <td>
XAPI-00075</td>
    <td>A "completion" property is a Boolean. The LRS rejects with 400 Bad Request a Statement which has a Result Object with a “completion” property which does not have a valid Boolean value, if present. </td>
  </tr>
  <tr>
    <td>
XAPI-00076</td>
    <td>A "response" property is a String. The LRS rejects with 400 Bad Request a Statement which has a Result Object with a “response” property which does not have a valid String value, if present. </td>
  </tr>
  <tr>
    <td>
XAPI-00077</td>
    <td>A "duration" property is a formatted to ISO 8601 durations (see part 3, section 4.6). The LRS rejects with 400 Bad Request a Statement which has a Result Object with a “duration” property which does not have a valid ISO 8601 value, if present. </td>
  </tr>
  <tr>
    <td>
XAPI-00078</td>
    <td>An "extensions" property is an Object. The LRS rejects with 400 Bad Request a Statement which has a Result Object with aa “extensions” property which does not have a valid Extensions Object, if present. </td>
  </tr>
</table>


#### 2.4.5.1 [Score](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#2451-score)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00079</td>
    <td>A "score" property is an Object. The LRS rejects with 400 Bad Request a "score" property which is not a valid object. </td>
  </tr>
  <tr>
    <td>XAPI-00080</td>
    <td>If the "score" Object uses the "max" property, the value must be a decimal number more than the "min" property, if it is present. If "min" is not present "max" can be any number. The LRS rejects with 400 Bad Request a statement with a Result Object using the “max” property  (if it is present) which is not a decimal number or is lesser than the value of the “min” property, if it is present. </td>
  </tr>
  <tr>
    <td>XAPI-00081</td>
    <td>If the "score" Object uses the "min" property, the value must be a decimal number less than the "max" property, if it is present. If "max" is not present "min" can be any number. The LRS rejects with 400 Bad Request a statement with a Result Object using the “min” property  (if it is present) which is not a decimal number or is greater than the value of the “max” property, if it is present. </td>
  </tr>
  <tr>
    <td>XAPI-00082</td>
    <td>If the "score" Object uses the "raw" property, the value must be a decimal number between the "min" and "max", if they are present. If they are not present "raw" can be any number. The LRS rejects with 400 Bad Request a statement with a Result Object using the “raw” property (if it is present) which is not a decimal number or is greater than the value of the “max” property, if it is present, or lesser than the value of the “min” property, if it is present. </td>
  </tr>
  <tr>
    <td>XAPI-00083</td>
    <td>If the "score" Object uses the "scaled" property, the value must be a decimal number between -1 and 1. The LRS rejects with 400 Bad Request a statement with a Result Object using the “scaled” property (if it is present) which is not a decimal number or is greater than 1 or less than -1. </td>
  </tr>
</table>


### 2.4.6.[ Context](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#context)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00084</td>
    <td>A Statement cannot contain both a "revision" property in its "context" property and have the value of the "object" property's "objectType" be anything but "Activity". The LRS rejects a statement with 400 Bad Request if contains a "revision" property in its "context" property and does not have an Object with an "objectType" value of “activity” or an Object where the “objectType” property is absent.</td>
  </tr>
  <tr>
    <td>
XAPI-00085</td>
    <td>A Statement cannot contain a "platform" property in its "context" property and have the value of the "object" property's "objectType" be anything but "Activity". The LRS rejects a statement with 400 Bad Request if contains a "platform" property in its "context" property and does not have an Object with an “objectType” value of “activity” or an Object where the “objectType” property is absent.</td>
  </tr>
  <tr>
    <td>
XAPI-00086</td>
    <td>A "contextActivities" property is an Object. The LRS rejects with 400 Bad Request a statement with a “contextActivities” property which is not a valid object. </td>
  </tr>
  <tr>
    <td>
XAPI-00087</td>
    <td>A "registration" property is a UUID. The LRS rejects with 400 Bad Request a statement with a “registration” property which is not a valid UUID.</td>
  </tr>
  <tr>
    <td>
XAPI-00087</td>
    <td>An "instructor" property is an Agent. The LRS rejects with 400 Bad Request a statement with an “instructor” property which is not a valid Agent.</td>
  </tr>
  <tr>
    <td>
XAPI-00088</td>
    <td>An "team" property is a Group. The LRS rejects with 400 Bad Request a statement with a “team” property which is not a valid Group.</td>
  </tr>
  <tr>
    <td>
XAPI-00089</td>
    <td>A "revision" property is a String. The LRS rejects with 400 Bad Request a statement with a “revision” property which is not a valid string.</td>
  </tr>
  <tr>
    <td>
XAPI-00090</td>
    <td>A "platform" property is a String. The LRS rejects with 400 Bad Request a statement with a “platform” property which is not a valid string.</td>
  </tr>
  <tr>
    <td>
XAPI-00091</td>
    <td>A "language" property is a String which follows RFC 5646. The LRS rejects with 400 Bad Request a statement with a “language” property which is not a valid RFC 5646 string.</td>
  </tr>
  <tr>
    <td>
XAPI-00092</td>
    <td>A "statement" property is a Statement Reference. The LRS rejects with 400 Bad Request a statement with a “statement” property which is not a valid StatementRef.</td>
  </tr>
</table>


#### 2.4.6.2 [ContextActivities Property](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#2462-contextactivities-property)

**Definition**

1. A ContextActivity is defined as a single Activity of the "value" of the "contextActivities" property

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00093</td>
    <td>A "contextActivities" property's "key" has a value of "parent", "grouping", "category", or "other". The LRS rejects with 400 Bad Request a statement which has a key other than "parent", "grouping", "category", or "other" for the "contextActivities" property</td>
  </tr>
  <tr>
    <td>
XAPI-00094</td>
    <td>A "contextActivities" property's "value" is an Activity. The LRS rejects with 400 Bad Request a statement which has a value which is not an Activity for the “contextActivities” property. </td>
  </tr>
  <tr>
    <td>
XAPI-00095</td>
    <td>A "contextActivities" property contains one or more key/value pairs. The LRS rejects with 400 Bad Request a statement which has an empty “contextActivities” property. </td>
  </tr>
  <tr>
    <td>
XAPI-00096</td>
    <td>An LRS's Statement Resource returns a ContextActivity in an array, even if only a single ContextActivity is returned. </td>
  </tr>
</table>


### 2.4.8. [Stored](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#stored)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00097</td>
    <td>An LRS MUST assign the "stored" property timestamp upon receiving a statement. </td>
  </tr>
</table>


### 2.4.9.[ Authority](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#authority)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00098</td>
    <td>An "authority" property which is also a Group contains exactly two Agents. The LRS rejects with 400 Bad Request a statement which has an "authority" property with a “objectType” of “Group” with more or less than two Oauth Agents as values of the “member” property.</td>
  </tr>
  <tr>
    <td>
XAPI-00099</td>
    <td>An LRS populates the "authority" property if it is not provided in the Statement </td>
  </tr>
  <tr>
    <td>
XAPI-00100</td>
    <td>An LRS rejects with error code 400 Bad Request, a Request whose "authority" is a Group having more than two Agents</td>
  </tr>
</table>


### 2.4.10.[ Version](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#version)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00101</td>
    <td>An LRS rejects with error code 400 Bad Request, a Request which uses "version" and has the value set to anything but "1.0" or "1.0.x", where x is the semantic versioning number </td>
  </tr>
</table>


### 2.4.11.[ Attachments](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#attachments)

**Definition**

1. An Attachment is an Object 

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00102</td>
    <td>A "length" property is an Integer. The LRS rejects with 400 Bad Request a statement which does not have a "length" property or the “length” property is not a valid integer in octets in the Attachment Object. </td>
  </tr>
  <tr>
    <td>
XAPI-00103</td>
    <td>A "sha2" property is a String. The LRS rejects with 400 Bad Request a statement which does not have a “sha2” property or the ”sha2” property is not a valid hash in the Attachment Object. </td>
  </tr>
  <tr>
    <td>
XAPI-00104</td>
    <td>A "fileUrl" property is an IRL. The LRS rejects with 400 Bad Request a statement the “fileURL” property if it is present and it is not a valid IRL in the Attachment Object. </td>
  </tr>
  <tr>
    <td>
XAPI-00105</td>
    <td>A "contentType" property is an Internet Media/MIME type. The LRS rejects with 400 Bad Request a statement which does not have a “contentType” property or the  “contentType” property value is not Internet Media/MIME in the Attachment Object. </td>
  </tr>
  <tr>
    <td>
XAPI-00106</td>
    <td>A "display" property is a Language Map. The LRS rejects with 400 Bad Request a statement which does not have a “display” property or the  “display” property value is not a valid Language Map in the Attachment Object. </td>
  </tr>
  <tr>
    <td>
XAPI-00107</td>
    <td>A "usageType" property is an IRI. The LRS rejects with 400 Bad Request a statement which does not have a "usageType" property or the "usageType" property value is not a valid IRI in the Attachment Object. </td>
  </tr>
</table>


## 2.5.[ Retrieval of Statements](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#retrieval)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00108</td>
    <td>If not empty, the "more" property's IRL refers to a specific container object corresponding to the next page of results from the original GET request. To test make a GET request which will return a known number of statements and confirm the LRS returns a "more" property which has an IRL with a container of the remaining statements and that the IRL is valid.</td>
  </tr>
  <tr>
    <td>
XAPI-00109</td>
    <td>The "more" property is absent or an empty string (no whitespace) if the entire results of the original GET request have been returned. To test make a GET request which will return a known number of statements and check to make sure the LRS either returns an empty string or the more property is absent.</td>
  </tr>
  <tr>
    <td>
XAPI-00110</td>
    <td>A "statements" property is an Array of Statements. Make a GET request which will return at least one statement and confirm the “statements” property is a valid Array of Statements. </td>
  </tr>
  <tr>
    <td>
XAPI-00111</td>
    <td> A "more" property's referenced container object follows the same rules as the original GET request, originating with a single "statements" property and a single "more" property. </td>
  </tr>
  <tr>
    <td>
XAPI-00112</td>
    <td>The LRS will NOT reject a GET request which returns an empty "statements" property. Send a GET request which will not return any results and check that a 200 Ok and an empty StatementResult Object is returned. </td>
  </tr>
  <tr>
    <td>
XAPI-00113</td>
    <td>An LRS's Statement API, upon processing a successful GET request, will return a single "statements" property and a single "more" property. A single "more" property must be present if there are additional results available. </td>
  </tr>
  <tr>
    <td>
XAPI-00114</td>
    <td>A "statements" property result which is paginated will create a container for each additional page.</td>
  </tr>
</table>


## 2.6.[ Signed Statements](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#signature)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00115</td>
    <td>A Signed Statement MUST include a JSON web signature (JWS) as defined here: http://tools.ietf.org/html/rfc7515, as an Attachment with a usageType of http://adlnet.gov/expapi/attachments/signature and a contentType of application/octet-stream. The LRS must reject with 400 a statement which has usageType of http://adlnet.gov/expapi/attachments/signature and a contentType of application/octet-stream but does not have a signature attached.  </td>
  </tr>
  <tr>
    <td>
XAPI-00116</td>
    <td>The JWS signature MUST have a payload of a valid JSON serialization of the complete Statement before the signature was added.The LRS must reject with 400 a statement which does not have a valid JSON serialization.</td>
  </tr>
  <tr>
    <td>
XAPI-00117</td>
    <td>The JWS signature MUST use an algorithm of "RS256", "RS384", or "RS512". The LRS must reject with 400 a statement which does not use one of these algorithms or does not use one of these algorithms correctly.</td>
  </tr>
</table>


# 3.0.[ Metadata](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#metadata)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 3.1.[ IRI Requirements](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#iri-requirements)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 3.2.[ Hosted Metadata](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#miscmeta)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

# 4.0.[ Special Data Types and Rules](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#special-data)

## 4.1.[ Extensions](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#miscext)

**Definitions**

1. An Extension is defined as an Object of any "extensions" property

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00118</td>
    <td>An Extension "key" is an IRI. The LRS rejects with 400 a statement which has an extension key which is not a valid IRI, if an extension object is present. </td>
  </tr>
  <tr>
    <td>
XAPI-00119</td>
    <td>An Extension can be null, an empty string, objects with nothing in them. The LRS accepts with 200 if a PUT or 204 if a POST an otherwise valid statement which has any extension value including  null, an empty string, or an empty object.</td>
  </tr>
  <tr>
    <td>
XAPI-00120</td>
    <td>An Extension's structure is that of "key"/"value" pairs. The LRS rejects with 400 a statement which does not use valid "key"/”value” pairs in the Extension property</td>
  </tr>
</table>


## 4.2.[ Language Maps](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#lang-maps)

**Definition**

1. A Language Map is defined as an array of language tag/String pairs has at least 1 entry Implicit

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00121</td>
    <td>A Language Map follows RFC 5646. The LRS rejects with 400 a statement using a Language Map which doesn’t not validate to RFC 5646. </td>
  </tr>
</table>


## 4.3.[ IRIs](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#iris)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 4.4.[ UUIDs](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#uuids)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 4.5.[ ISO 8601 Timestamps](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#timestamps)

**Definitions**

1. A Timestamp is defined as a Date/Time formatted according to ISO 8601 

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00122</td>
    <td>A Timestamp MUST preserve precision to at least milliseconds (3 decimal points beyond seconds). The LRS accepts a statement with a valid timestamp which has more than 3 decimal points beyond seconds and when recalled it returns at least 3 decimals points beyond seconds. </td>
  </tr>
  <tr>
    <td>XAPI-00123</td>
    <td>A Timestamp must conform to ISO 8601 Date format. An LRS rejects a statement with a Timestamp which doesn’t validate to ISO 8601 Extended or ISO 8601 Basic. </td>
  </tr>
</table>


## 4.6.[ ISO 8601 Durations](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Data.md#durations)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00124</td>
    <td>A Duration MUST be expressed using the format for Duration in ISO 8601:2004(E) section 4.4.3.2. The alternative format (in conformity with the format used for time points and described in ISO 8601:2004(E) section 4.4.3.3) MUST NOT be used. The LRS rejects with 400 a statement which includes the "duration" property and the value does not validate to ISO 8601:2004(E) section 4.4.3.2.</td>
  </tr>
</table>


# Part Three:[ Data Processing, Validation, and Security](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#partthree)

# 1.0.[ Requests](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#requests)

## 1.1.[ HEAD Request Implementation](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#httphead)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00125</td>
    <td>An LRS responds to a HEAD request in the same way as a GET request, but without the message-body. This means run ALL GET tests with HEAD</td>
  </tr>
  <tr>
    <td>XAPI-00126</td>
    <td>An LRS accepts HEAD requests. </td>
  </tr>
</table>


## 1.2.[ Headers](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#headers)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 1.3.[ Alternate Request Syntax](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#alt-request-syntax)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 1.4.[ Encoding](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#encoding)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 1.5.[ Content Types](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#content-types)

**Definition**

1. A Boundary is defined as the value of the body header named "boundary"

### 1.5.1.[ Application/JSON](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#applicationjson)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00127</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which does not have a "Content-Type" header with value "application/json" or "multipart/mixed" </td>
  </tr>
  <tr>
    <td>
XAPI-00128</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which has excess multi-part sections that are not attachments.</td>
  </tr>
  <tr>
    <td>XAPI-00129</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which is missing multi-part sections for non-fileURL attachments must be rejected.</td>
  </tr>
</table>


 

### 1.5.2.[ Multipart/Mixed](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#multipartmixed)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00130</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which uses Attachments, has a "Content Type" header with value "multipart/mixed", and does not have a Boundary before each "Content-Type" header</td>
  </tr>
  <tr>
    <td>

XAPI-00131</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which uses Attachments, has a "Content Type" header with value "multipart/mixed", and does not have a body header named "boundary" </td>
  </tr>
  <tr>
    <td>
XAPI-00132</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which uses Attachments, has a "Content Type" header with value "multipart/mixed", and for any part except the first does not have a Header named "X-Experience-API-Hash" with a value of one of those found in a "sha2" property of a Statement in the first part of this document </td>
  </tr>
  <tr>
    <td>
XAPI-00133</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which uses Attachments, has a "Content Type" header with value "multipart/mixed", and does not have all of the Statements in the first document part </td>
  </tr>
  <tr>
    <td>
XAPI-00134</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which uses Attachments, has a "Content Type" header with value "multipart/mixed", and does not the first document part with a "Content-Type" header with a value of "application/json"</td>
  </tr>
  <tr>
    <td>
XAPI-00135</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which uses Attachments, has a "Content Type" header with value "multipart/mixed", and for any part except the first does not have a Header named "Content-Transfer-Encoding" with a value of "binary" </td>
  </tr>
  <tr>
    <td>
XAPI-00137</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which uses Attachments, has a "Content Type" header with value "multipart/mixed", and does not have a body header named "MIME-Version" with a value of "1.0" or greater</td>
  </tr>
  <tr>
    <td>
XAPI-00138</td>
    <td>An LRS rejects with error code 400 Bad Request, a PUT or POST Request which uses Attachments, has a "Content Type" header with value "multipart/mixed", and does not have a body header named "Content-Type" with value "multipart/mixed" </td>
  </tr>
</table>


# 2.0.[ Resources](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#datatransfer)

**Definition**

1. A POST request is defined as a "pure" POST, as opposed to a GET taking on the form of a POST

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00139</td>
    <td>An LRS has a Statement API with endpoint "base IRI"+"/statements" </td>
  </tr>
  <tr>
    <td>XAPI-00140</td>
    <td>An LRS implements all of the Statement, State, Agent, and Activity Profile sub-APIs </td>
  </tr>
  <tr>
    <td>
XAPI-00141</td>
    <td>An LRS's returned array of ids from a successful GET request all refer to documents stored after the TimeStamp in the "since" parameter of the GET request if such a parameter was present (7.5.table3.row2)</td>
  </tr>
</table>


## 2.1.[ Statement Resource](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#stmtres)

### [2.1.1 PUT Statements](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#211-put-statements)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00142</td>
    <td>An LRS cannot modify a Statement in the event it receives a Statement with statementID equal to a Statement in the LRS already. 

To test: Send one statement with a particular statement ID. Send a second statement with the same statement ID but everything else different. Retrieve the statement before the second statement and after and both retrieved statements MUST match.</td>
  </tr>
  <tr>
    <td>
XAPI-00143</td>
    <td>An LRS's Statement API upon processing a valid PUT request successfully returns code 204 No Content</td>
  </tr>
  <tr>
    <td>
XAPI-00144</td>
    <td>An LRS's Statement API accepts PUT requests only if it contains a "statementId" parameter, returning 204 No Content </td>
  </tr>
  <tr>
    <td>XAPI-00145</td>
    <td>An LRS's Statement API rejects a PUT request which does not have a "statementId" parameter, returning 400 Bad Request</td>
  </tr>
</table>


### [2.1.2 POST Statements](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#212-post-statements)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00146</td>
    <td>An LRS's Statement API upon processing a successful POST request returns code 200 OK and all Statement UUIDs within the POST</td>
  </tr>
  <tr>
    <td>
XAPI-00147</td>
    <td>An LRS's Statement API accepts POST requests </td>
  </tr>
  <tr>
    <td>
XAPI-00148</td>
    <td>An LRS accepts a valid POST request containing a GET request returning 200 OK and the StatementResult Object.</td>
  </tr>
</table>


### [2.1.3 GET Statements](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#213-get-statements)

**Definition**

1. A GET request is defined as either a GET request or a POST request containing a GET request 

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00149</td>
    <td>The LRS will NOT reject a GET request which returns an empty "statements" property. Send a GET request which will not return any results and check that a 200 Ok and an empty StatementResult Object is returned. </td>
  </tr>
  <tr>
    <td>
XAPI-00150</td>
    <td>An LRS's Statement API rejects a GET request with both "voidedStatementId" and anything other than "attachments" or "format" as parameters with error code 400 Bad Request.</td>
  </tr>
  <tr>
    <td>
XAPI-00151</td>
    <td>An LRS's Statement API rejects a GET request with both "statementId" and anything other than "attachments" or "format" as parameters with error code 400 Bad Request.</td>
  </tr>
  <tr>
    <td>
XAPI-00152</td>
    <td>An LRS's "X-Experience-API-Consistent-Through" header's value is not before (temporal) any of the "stored" values of any of the returned Statements.</td>
  </tr>
  <tr>
    <td>
XAPI-00153</td>
    <td>An LRS's Statement API upon processing a GET request, returns a header with name "X-Experience-API-Consistent-Through" regardless of the code returned. </td>
  </tr>
  <tr>
    <td>
XAPI-00154</td>
    <td>An LRS's Statement API upon processing a successful GET request with neither a "statementId" nor a "voidedStatementId" parameter, returns code 200 OK and a StatementResult Object.</td>
  </tr>
  <tr>
    <td>
XAPI-00155</td>
    <td>An LRS's Statement API upon processing a successful GET request with a "voidedStatementId" parameter, returns code 200 OK and a single Statement with the corresponding "id". </td>
  </tr>
  <tr>
    <td>
XAPI-00156</td>
    <td>An LRS's Statement API upon processing a successful GET request with a "statementId" parameter, returns code 200 OK and a single Statement with the corresponding "id". </td>
  </tr>
  <tr>
    <td>
XAPI-00157</td>
    <td>An LRS's Statement API can process a GET request with "voidedStatementId" as a parameter </td>
  </tr>
  <tr>
    <td>XAPI-00158</td>
    <td>An LRS's Statement API can process a GET request with "statementId" as a parameter </td>
  </tr>
  <tr>
    <td>XAPI-00159</td>
    <td>An LRS's Statement API accepts GET requests </td>
  </tr>
  <tr>
    <td>XAPI-00160</td>
    <td>An LRS's "X-Experience-API-Consistent-Through" header is an ISO 8601 combined date and time </td>
  </tr>
  <tr>
    <td>
XAPI-00161</td>
    <td>An LRS's Statement API not return attachment data and only return application/json if the "attachment" parameter set to "false"</td>
  </tr>
  <tr>
    <td>
XAPI-00162</td>
    <td>An LRS's Statement API processes a successful GET request using a parameter (such as stored time) which includes a voided statement and unvoided statements targeting the voided statement. The API must return 200 Ok and the statement result object, containing statements which target a voided statement, but not the voided statement itself. </td>
  </tr>
  <tr>
    <td>
XAPI-00163</td>
    <td>An LRS's Statement API, upon processing a successful GET request, can only return a Voided Statement if that Statement is specified in the voidedStatementId parameter of that request </td>
  </tr>
  <tr>
    <td>
XAPI-00164</td>
    <td>The Statements within the "statements" property will correspond to the filtering criterion sent in with the GET request </td>
  </tr>
  <tr>
    <td>
XAPI-00165</td>
    <td>An LRS's Statement API, upon receiving a GET request, MUST have a "Content-Type" header. </td>
  </tr>
  <tr>
    <td>
XAPI-00166</td>
    <td>An LRS's Statement API can process a GET request with "ascending" as a parameter The Statement API MUST return 200 OK, StatementResult Object with results in ascending order of stored time if the ascending parameter is set to true.</td>
  </tr>
  <tr>
    <td>
XAPI-00167</td>
    <td>An LRS's Statement API can process a GET request with "attachments" as a parameter. The Statement API MUST return 200 OK, StatementResult Object and use the multipart response format and include all attachments if the attachment parameter is set to true</td>
  </tr>
  <tr>
    <td>
XAPI-00168</td>
    <td>An LRS's Statement API can process a GET request with "format" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with results in the requested format or in "exact" if the “format” parameter is absent. </td>
  </tr>
  <tr>
    <td>XAPI-00169</td>
    <td>An LRS's Statement API can process a GET request with "format" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with results in the requested format. If “canonical”, return Activity Objects and Verbs populated with the canonical definition of the Activity Objects and Display of the Verbs as determined by the LRS, returning only one language.</td>
  </tr>
  <tr>
    <td>XAPI-00170</td>
    <td>An LRS's Statement API can process a GET request with "format" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with results in the requested format. If “exact”, return Agent, Activity, Verb and Group Objects populated exactly as they were when the Statement was received. </td>
  </tr>
  <tr>
    <td>XAPI-00171</td>
    <td>An LRS's Statement API can process a GET request with "format" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with results in the requested format. If “ids”, only include identifiers for Agent, Activity, Verb, Group Objects, and members of Anonymous groups.</td>
  </tr>
  <tr>
    <td>XAPI-00172</td>
    <td>If the "Accept-Language" header is present as part of the GET request to the Statement API and the "format" parameter is set to "canonical", the LRS MUST apply this data to choose the matching language in the response.</td>
  </tr>
  <tr>
    <td>
XAPI-00173</td>
    <td>An LRS's Statement API can process a GET request with "limit" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with only the number of results set by the integer in the limit parameter. If the limit parameter is not present, the limit is defaulted to 0 which returns all results up to the server limit.</td>
  </tr>
  <tr>
    <td>
XAPI-00174</td>
    <td>An LRS's Statement API can process a GET request with "until" as a parameter. The Statement API MUST return 200 OK, StatementResult Object containing all statements which have a stored timestamp at or before the specified until parameter timestamp.</td>
  </tr>
  <tr>
    <td>

XAPI-00175</td>
    <td>An LRS's Statement API can process a GET request with "since" as a parameter. The Statement API MUST return 200 OK, StatementResult Object containing all statements which have a stored timestamp after the since parameter timestamp in the query.</td>
  </tr>
  <tr>
    <td>
XAPI-00176</td>
    <td>An LRS's Statement API can process a GET request with "related_agents" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with exact match agent results if the agent parameter is set with a valid Agent or Identified Group JSON Object unless the related_agents parameter is set to true. If set to true it MUST return 200 OK, StatementResult Object with agent matches in the Actor, Object, authority, instructor, team, or any of these properties in a contained SubStatement</td>
  </tr>
  <tr>
    <td>
XAPI-00177</td>
    <td>An LRS's Statement API can process a GET request with "related_activities" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with exact match activity results if the activity parameter is set with a valid Verb IRI unless the related_activities parameter is set to true. If set to true it MUST return 200 OK, StatementResult Object with activity ID matches in the Statement Object, and Context Objects and SubStatement Objects.</td>
  </tr>
  <tr>
    <td>
XAPI-00178</td>
    <td>An LRS's Statement API can process a GET request with "registration" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with exact match registration results if the registration parameter is set with a valid registration UUID</td>
  </tr>
  <tr>
    <td>
XAPI-00179</td>
    <td>An LRS's Statement API can process a GET request with "activity" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with exact match activity results if the activity parameter is set with a valid activity IRI</td>
  </tr>
  <tr>
    <td>
XAPI-00180</td>
    <td>An LRS's Statement API can process a GET request with "verb" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with exact match verb results if the verb parameter is set with a valid Verb IRI</td>
  </tr>
  <tr>
    <td>
XAPI-00181</td>
    <td>An LRS's Statement API can process a GET request with "agent" as a parameter. The Statement API MUST return 200 OK, StatementResult Object with exact match agent result if the agent parameter is set with a valid Agent IFI</td>
  </tr>
</table>


## 2.2.[ Documents Resources](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#doctransfer)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00182</td>
    <td>An LRS makes no modifications to stored data for any rejected request.</td>
  </tr>
  <tr>
    <td>
XAPI-00183</td>
    <td>A Document Merge only performs overwrites at one level deep, although the entire object is replaced. </td>
  </tr>
  <tr>
    <td>
XAPI-00184</td>
    <td>A Document Merge overwrites any duplicate values from the previous document with the new document. </td>
  </tr>
  <tr>
    <td>XAPI-00185</td>
    <td>A Document Merge re-serializes all Objects to finalize a single document</td>
  </tr>
  <tr>
    <td>
XAPI-00186</td>
    <td>A Document Merge de-serializes all Objects represented by each document before making other changes.</td>
  </tr>
</table>


## 2.3.[ State Resource](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#stateres)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00187</td>
    <td>An LRS's State API upon processing a successful DELETE request returns code 204 No Content </td>
  </tr>
  <tr>
    <td>
XAPI-00188</td>
    <td>An LRS's State API upon processing a successful GET request returns 200 Ok, State Document</td>
  </tr>
  <tr>
    <td>
XAPI-00189</td>
    <td>An LRS's State API upon processing a successful POST request returns code 204 No Content </td>
  </tr>
  <tr>
    <td>
XAPI-00190</td>
    <td>An LRS's State API upon processing a successful PUT request returns code 204 No Content </td>
  </tr>
  <tr>
    <td>
XAPI-00191</td>
    <td>An LRS's State API upon processing a successful DELETE request with a valid "stateId" as a parameter deletes the document satisfying the requirements of the DELETE and returns code 204 No Content NOTE: There is no requirement here that the LRS reacts to the "since" parameter in the case of a DELETE request with valid "stateId" - this is intentional</td>
  </tr>
  <tr>
    <td>
XAPI-00192</td>
    <td>An LRS's State API upon processing a successful GET request with a valid "stateId" as a parameter returns the document satisfying the requirements of the GET and code 200 OK NOTE: There is no requirement here that the LRS reacts to the "since" parameter in the case of a GET request with valid "stateId" - this is intentional</td>
  </tr>
  <tr>
    <td>
XAPI-00193</td>
    <td>An LRS's State API upon processing a successful GET request without "stateId" as a parameter returns an array of ids of state data documents satisfying the requirements of the GET and code 200 OK</td>
  </tr>
  <tr>
    <td>
XAPI-00194</td>
    <td>An LRS's State API upon processing a successful DELETE request without "stateId" as a parameter deletes documents satisfying the requirements of the DELETE and code 204 No Content</td>
  </tr>
  <tr>
    <td>
XAPI-00195</td>
    <td>An LRS's returned array of ids from a successful GET request all refer to documents stored after the TimeStamp in the "since" parameter of the GET request </td>
  </tr>
  <tr>
    <td>
XAPI-00196</td>
    <td>An LRS's State API rejects a DELETE request with "agent" as a parameter if it is not in JSON format with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00197</td>
    <td>An LRS's State API rejects a GET request with "agent" as a parameter if it is not in JSON format with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00198</td>
    <td>An LRS's State API rejects a POST request with "agent" as a parameter if it is not in JSON format with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00199</td>
    <td>An LRS's State API rejects a PUT request with "agent" as a parameter if it is not in JSON format with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00200</td>
    <td>An LRS's State API rejects a DELETE request with "registration" as a parameter if it is not a UUID with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00201</td>
    <td>An LRS's State API rejects a GET request with "registration" as a parameter if it is not a UUID with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00202</td>
    <td>An LRS's State API rejects a POST request with "registration" as a parameter if it is not a UUID with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00203</td>
    <td>An LRS's State API rejects a PUT request with "registration" as a parameter if it is not a UUID with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00204</td>
    <td>An LRS's State API rejects a GET request with "since" as a parameter if it is not a "TimeStamp", with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00205</td>
    <td>An LRS's State API rejects a DELETE request with "since" as a parameter if it is not a "TimeStamp", with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00206</td>
    <td>An LRS's State API rejects a PUT request without "stateId" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00207</td>
    <td>An LRS's State API rejects a DELETE request without "activityId" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00208</td>
    <td>An LRS's State API rejects a GET request without "activityId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00209</td>
    <td>An LRS's State API rejects a POST request without "activityId" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00210</td>
    <td>An LRS's State API rejects a PUT request without "activityId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00211</td>
    <td>An LRS's State API rejects a POST request without "stateId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00212</td>
    <td>An LRS's State API rejects a DELETE request without "agent" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00213</td>
    <td>An LRS's State API rejects a GET request without "agent" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00214</td>
    <td>An LRS's State API rejects a POST request without "agent" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00215</td>
    <td>An LRS's State API rejects a PUT request without "agent" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00216</td>
    <td>An LRS's State API can process a DELETE request with "stateId" as a parameter</td>
  </tr>
  <tr>
    <td>
XAPI-00217</td>
    <td>An LRS's State API can process a GET request with "stateId" as a parameter</td>
  </tr>
  <tr>
    <td>
XAPI-00218</td>
    <td>An LRS's State API can process a PUT request with "registration" as a parameter </td>
  </tr>
  <tr>
    <td>
XAPI-00219</td>
    <td>An LRS's State API can process a DELETE request with "registration" as a parameter</td>
  </tr>
  <tr>
    <td>XAPI-00220</td>
    <td>An LRS's State API can process a GET request with "registration" as a parameter </td>
  </tr>
  <tr>
    <td>
XAPI-00221</td>
    <td>An LRS's State API can process a GET request with "since" as a parameter. Returning 200 OK and  all matching profiles after the date/time of the "since" parameter. </td>
  </tr>
  <tr>
    <td>XAPI-00222</td>
    <td>The State API's returned array of ids from a successful GET request all refer to documents stored after the TimeStamp in the "since" parameter of the GET request if such a parameter was present </td>
  </tr>
  <tr>
    <td>XAPI-00223</td>
    <td>An LRS's State API can process a DELETE request with "since" as a parameter </td>
  </tr>
  <tr>
    <td>
XAPI-00224</td>
    <td>An LRS's State API rejects a DELETE request with "stateId" as a parameter if it is not type "String" with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00225</td>
    <td>An LRS's State API rejects a GET request with "stateId" as a parameter if it is not type "String" with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00226</td>
    <td>An LRS's State API rejects a POST request with "stateId" as a parameter if it is not type "String" with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>XAPI-00227</td>
    <td>An LRS's State API can process a POST request with "registration" as a parameter </td>
  </tr>
  <tr>
    <td>
XAPI-00228</td>
    <td>An LRS's State API rejects a PUT request with "stateId" as a parameter if it is not type "String" with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>XAPI-00229</td>
    <td>An LRS's State API, rejects a POST request if the document is found and either document is not a valid JSON Object </td>
  </tr>
  <tr>
    <td>XAPI-00230</td>
    <td>An LRS has a State API with endpoint "base IRI"+"/activities/state" </td>
  </tr>
  <tr>
    <td>XAPI-00231</td>
    <td>An LRS will accept a POST request to the State API </td>
  </tr>
  <tr>
    <td>
XAPI-00232</td>
    <td>An LRS's State API, rejects a POST request if the document is found and either document's type is not "application/json" with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00233</td>
    <td>An LRS's State API, upon receiving a POST request for a document not currently in the LRS, treats it as a PUT request and store a new document. Returning 204 No Content </td>
  </tr>
  <tr>
    <td>
XAPI-00234</td>
    <td>An LRS's State API performs a Document Merge if a profileId is found and both it and the document in the POST request have type "application/json". If the merge is successful, the LRS MUST respond with HTTP status code 204 No Content. </td>
  </tr>
  <tr>
    <td>
XAPI-00235</td>
    <td>An LRS must reject with 400 Bad Request a POST request to the State API which contains name/value pairs with invalid JSON and the Content-Type header is "application/json</td>
  </tr>
</table>


## 2.4.[ Agents Resource](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#agentsres)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00236</td>
    <td>An LRS's Agents API accepts GET requests with response 200 OK, Person Object</td>
  </tr>
  <tr>
    <td>
XAPI-00237</td>
    <td>A Person Object's "objectType" property is a String and is "Person" The LRS must return a valid "objectType" string. </td>
  </tr>
  <tr>
    <td>
XAPI-00238</td>
    <td>A Person Object's "name" property is an Array of Strings. The LRS must return a “name” property with a valid Array of Strings, if present.  </td>
  </tr>
  <tr>
    <td>
XAPI-00239</td>
    <td>A Person Object's "mbox" property is an Array of IRIs. The LRS must return an “mbox” property with a valid array of IRIs, if present.  </td>
  </tr>
  <tr>
    <td>
XAPI-00240</td>
    <td>A Person Object's "mbox_sha1sum" property is an Array of Strings. The LRS must return a  Person Object which has a “mbox_sha1sum” and is valid array of strings, if present.  </td>
  </tr>
  <tr>
    <td>
XAPI-00241</td>
    <td>A Person Object's "openid" property is an Array of Strings The LRS must return a “openid” value which is valid array of strings, if present.  </td>
  </tr>
  <tr>
    <td>
XAPI-00242</td>
    <td>A Person Object's "account" property is an Array of Account Objects The LRS must return a Person Object with a “name” value which is a valid array of account objects, if present.  </td>
  </tr>
  <tr>
    <td>
XAPI-00243</td>
    <td>An LRS's Agents API rejects a GET request without "agent" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00244</td>
    <td>A Person Object's "mbox" entries have the form "mailto:emailaddress". The LRS must return a Person Object which has a “mbox” value with the form "mailto:emailaddress"</td>
  </tr>
  <tr>
    <td>XAPI-00245</td>
    <td>An LRS has an Agents API with endpoint "base IRI" + /agents"</td>
  </tr>
  <tr>
    <td>XAPI-00246</td>
    <td>The Agents Resource MUST have an endpoint which accepts GET requests and returns a special, Person Object where each attribute has an array value and it is legal to include multiple identifying properties.</td>
  </tr>
  <tr>
    <td>XAPI-00247</td>
    <td>If an LRS does not have any additional information about an Agent to return from the Agents Resource, the LRS MUST still return a Person when queried, but that Person Object will only include the information associated with the requested Agent.</td>
  </tr>
  <tr>
    <td>
XAPI-00248</td>
    <td>An LRS's Agents API upon processing a successful GET request returns a Person Object based on matched data from the "agent" parameter and code 200 OK </td>
  </tr>
  <tr>
    <td>
XAPI-00249</td>
    <td>An LRS's Agents API rejects a GET request with "agent" as a parameter if it is not a valid (in structure) Agent with error code 400 Bad Request </td>
  </tr>
</table>


## 2.5.[ Activities Resource](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#activitiesres)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00250</td>
    <td>An LRS's Activities API rejects a GET request without "activityId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00251</td>
    <td>An LRS's Activities API upon processing a successful GET request returns 200 OK and the complete Activity Object</td>
  </tr>
  <tr>
    <td>
XAPI-00252</td>
    <td>An LRS has an Activities API with endpoint "base IRI" + /activities" (7.5) Implicit (in that it is not named this by the spec)</td>
  </tr>
  <tr>
    <td>XAPI-00253</td>
    <td>An LRS's Activities API accepts GET requests</td>
  </tr>
  <tr>
    <td>XAPI-00254</td>
    <td>The Activity Object must contain all available information about an activity from any statements who target the same "activityId". For example, LRS accepts two statements each with a different language description of an activity using the exact same “activityId”. The LRS must return both language descriptions when a GET request is made to the Activities endpoint for that “activityId”.</td>
  </tr>
</table>


## 2.6.[ Agent Profile Resource](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#agentprofres)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00255</td>
    <td>An LRS's Agent Profile API rejects a DELETE request with "agent" as a parameter if it is not an Agent Object with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00256</td>
    <td>An LRS's Agent Profile API rejects a POST request with "agent" as a parameter if it is not an Agent Object with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00257</td>
    <td>An LRS's Agent Profile API rejects a PUT request with "agent" as a parameter if it is not an Agent Object with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00258</td>
    <td>An LRS's Agent Profile API rejects a GET request with "agent" as a parameter if it is not an Agent Object with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>XAPI-00259</td>
    <td>The Agent Profile API MUST return 200 OK - Profile Content when a GET request is received with a valid agent JSON Object.</td>
  </tr>
  <tr>
    <td>
XAPI-00260</td>
    <td>An LRS's Agent Profile API rejects a GET request with "since" as a parameter if it is not a "TimeStamp", with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00261</td>
    <td>An LRS's Agent Profile API rejects a GET request without "agent" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00262</td>
    <td>An LRS's Agent Profile API rejects a DELETE request without "agent" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00263</td>
    <td>An LRS's Agent Profile API rejects a POST request without "agent" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00264</td>
    <td>An LRS's Agent Profile API rejects a PUT request without "agent" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00265</td>
    <td>An LRS's Agent Profile API rejects a DELETE request without "profileId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00266</td>
    <td>An LRS's Agent Profile API rejects a POST request without "profileId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00267</td>
    <td>An LRS's Agent Profile API rejects a PUT request without "profileId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00268</td>
    <td>An LRS's Agent Profile API can process a GET request with "since" as a parameter. Returning 200 OK and  all matching profiles after the date/time of the "since" parameter. </td>
  </tr>
  <tr>
    <td>
XAPI-00269</td>
    <td>An LRS's Agent Profile API upon processing a successful GET request with a valid Agent Object and valid "profileId" as a parameter returns the document satisfying the requirements of the GET and code 200 OK </td>
  </tr>
  <tr>
    <td>
XAPI-00270</td>
    <td>An LRS's Agent Profile API upon processing a successful GET request with a valid Agent Object and without "profileId" as a parameter returns an array of ids of agent profile documents satisfying the requirements of the GET and code 200 OK</td>
  </tr>
  <tr>
    <td>
XAPI-00271</td>
    <td>An LRS's Agent Profile API upon processing a successful DELETE request deletes the associated profile and returns code 204 No Content </td>
  </tr>
  <tr>
    <td>
XAPI-00272</td>
    <td>An LRS's Agent Profile API upon processing a successful POST request returns code 204 No Content </td>
  </tr>
  <tr>
    <td>
XAPI-00273</td>
    <td>An LRS's Agent Profile API upon processing a successful PUT request returns code 204 No Content </td>
  </tr>
  <tr>
    <td>
XAPI-00274</td>
    <td>An LRS's Agent Profile API accepts valid GET requests with code 200 OK, Profile document</td>
  </tr>
  <tr>
    <td>XAPI-00275</td>
    <td>The Agent Profile API's returned array of ids from a successful GET request all refer to documents stored after the TimeStamp in the "since" parameter of the GET request if such a parameter was present </td>
  </tr>
  <tr>
    <td>
XAPI-00276</td>
    <td>An LRS's Agent Profile API rejects a POST request with "profileId" as a parameter if it is not type "String" with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00277</td>
    <td>An LRS's Agent Profile API rejects a PUT request with "profileId" as a parameter if it is not type "String" with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00278</td>
    <td>An LRS's Agent Profile API, rejects a POST request if the document is found and either document's type is not "application/json" with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00279</td>
    <td>An LRS's Agent Profile API performs a Document Merge if a profileId is found and both it and the document in the POST request have type "application/json" If the merge is successful, the LRS MUST respond with HTTP status code 204 No Content. </td>
  </tr>
  <tr>
    <td>
XAPI-00280</td>
    <td>An LRS's Agent Profile API, upon receiving a POST request for a document not currently in the LRS, treats it as a PUT request and store a new document.Returning 204 No Content </td>
  </tr>
  <tr>
    <td>XAPI-00281</td>
    <td>An LRS's Agent Profile API, rejects a POST request if the document is found and either document is not a valid JSON Object </td>
  </tr>
  <tr>
    <td>
XAPI-00282</td>
    <td>An LRS has an Agent Profile API with endpoint "base IRI"+"/agents/profile"</td>
  </tr>
  <tr>
    <td>
XAPI-00283</td>
    <td>An LRS will accept a POST request to the Agent Profile API </td>
  </tr>
  <tr>
    <td>
XAPI-00284</td>
    <td>An LRS must reject, with 400 Bad Request, a POST request to the Agent Profile API  which contains name/value pairs with invalid JSON and the Content-Type header is "application/json</td>
  </tr>
</table>


## 2.7.[ Activity Profile Resource](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#actprofres)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00285</td>
    <td>An LRS's Activity Profile API upon processing a successful DELETE request deletes the associated profile and returns code 204 No Content</td>
  </tr>
  <tr>
    <td>
XAPI-00286</td>
    <td>An LRS's Activity Profile API upon processing a successful POST request returns code 204 No Content </td>
  </tr>
  <tr>
    <td>
XAPI-00287</td>
    <td>An LRS's Activity Profile API upon processing a successful PUT request returns code 204 No Content </td>
  </tr>
  <tr>
    <td>
XAPI-00288</td>
    <td>An LRS's Activity Profile API upon processing a successful GET request with a valid "profileId" as a parameter returns the document satisfying the requirements of the GET and code 200 OK </td>
  </tr>
  <tr>
    <td>
XAPI-00289</td>
    <td>An LRS's Activity Profile API upon processing a successful GET request without "profileId" as a parameter returns an array of ids of activity profile documents satisfying the requirements of the GET and code 200 OK </td>
  </tr>
  <tr>
    <td>
XAPI-00290</td>
    <td>An LRS's Activity Profile API accepts GET requests </td>
  </tr>
  <tr>
    <td>
XAPI-00291</td>
    <td>An LRS's Activity Profile API accepts DELETE requests </td>
  </tr>
  <tr>
    <td>
XAPI-00292</td>
    <td>An LRS's Activity Profile API accepts POST requests </td>
  </tr>
  <tr>
    <td>
XAPI-00293</td>
    <td>An LRS's Activity Profile API accepts PUT requests </td>
  </tr>
  <tr>
    <td>
XAPI-00294</td>
    <td>The Activity Profile API's returned array of ids from a successful GET request all refer to documents stored after the TimeStamp in the "since" parameter of the GET request if such a parameter was present </td>
  </tr>
  <tr>
    <td>
XAPI-00295</td>
    <td>An LRS's Activity Profile API rejects a GET request with "since" as a parameter if it is not a "TimeStamp", with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00296</td>
    <td>An LRS's Activity Profile API rejects a GET request without "activityId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00297</td>
    <td>An LRS's Activity Profile API rejects a DELETE request without "activityId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00298</td>
    <td>An LRS's Activity Profile API rejects a POST request without "activityId" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00299</td>
    <td>An LRS's Activity Profile API rejects a PUT request without "activityId" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00300</td>
    <td>An LRS's Activity Profile API rejects a DELETE request without "profileId" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00301</td>
    <td>An LRS's Activity Profile API rejects a POST request without "profileId" as a parameter with error code 400 Bad Request</td>
  </tr>
  <tr>
    <td>
XAPI-00302</td>
    <td>An LRS's Activity Profile API rejects a PUT request without "profileId" as a parameter with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00303</td>
    <td>An LRS's Activity Profile API can process a GET request with "since" as a parameter. Returning 200 OK and  all matching profiles after the date/time of the "since" parameter. </td>
  </tr>
  <tr>
    <td>
XAPI-00304</td>
    <td>An LRS's Activity Profile API rejects a GET request with "agent" as a parameter if it is not in JSON format with error code 400 Bad Request (format, 7.4.table2.row2.a)</td>
  </tr>
  <tr>
    <td>
XAPI-00305</td>
    <td>An LRS's Activity Profile API rejects a DELETE request with "profileId" as a parameter if it is not type "String" with error code 400 Bad Request (format, 7.5.table2.row2.a)</td>
  </tr>
  <tr>
    <td>
XAPI-00306</td>
    <td>An LRS's Activity Profile API API rejects a POST request with "profileId" as a parameter if it is not type "String" with error code 400 Bad Request (format, 7.5.table2.row2.a)</td>
  </tr>
  <tr>
    <td>
XAPI-00307</td>
    <td>An LRS's Activity Profile API rejects a PUT request with "profileId" as a parameter if it is not type "String" with error code 400 Bad Request (format, 7.5.table2.row2.a)</td>
  </tr>
  <tr>
    <td>
XAPI-00308</td>
    <td>An LRS's Activity Profile API performs a Document Merge if a activityId is found and both it and the document in the POST request have type "application/json" If the merge is successful, the LRS MUST respond with HTTP status code 204 No Content. </td>
  </tr>
  <tr>
    <td>
XAPI-00309</td>
    <td>An LRS's Activity Profile API, rejects a POST request if the document is found and either document's type is not "application/json" with error code 400 Bad Request </td>
  </tr>
  <tr>
    <td>
XAPI-00310</td>
    <td>An LRS's Activity Profile API, upon receiving a POST request for a document not currently in the LRS, treats it as a PUT request and store a new document. Returning 204 No Content </td>
  </tr>
  <tr>
    <td>XAPI-00311</td>
    <td>An LRS has an Activity Profile API with endpoint "base IRI"+"/activities/profile" </td>
  </tr>
  <tr>
    <td>
XAPI-00312</td>
    <td>An LRS will accept a POST request to the Activity Profile API</td>
  </tr>
  <tr>
    <td>
XAPI-00313</td>
    <td>An LRS's Activity Profile API, rejects a POST request if the document is found and either document is not a valid JSON Object </td>
  </tr>
  <tr>
    <td>
XAPI-00314</td>
    <td>An LRS must reject, with 400 Bad Request, a POST request to the Activity Profile API  which contains name/value pairs with invalid JSON and the Content-Type header is "application/json</td>
  </tr>
</table>


## 2.8.[ About Resource](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#aboutresource)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00315</td>
    <td>An LRS has an About API with endpoint "base IRI"+"/about"</td>
  </tr>
  <tr>
    <td>
XAPI-00316</td>
    <td>An LRS's About API's version property can only have values of "0.9", "0.95", "1.0.0", or "1.0.x" with </td>
  </tr>
  <tr>
    <td>XAPI-00317</td>
    <td>An LRS's About API's version property contains at least one string of "1.0.x" </td>
  </tr>
  <tr>
    <td>XAPI-00318</td>
    <td>An LRS's About API's version property is an array of strings</td>
  </tr>
  <tr>
    <td>
XAPI-00319</td>
    <td>An LRS's About Resource accepts GET requests. Upon processing a successful GET request returns a version property and code 200 OK </td>
  </tr>
  <tr>
    <td>
XAPI-00320</td>
    <td>An LRS's About API upon processing a successful GET request can return an Extension Object with code 200 OK </td>
  </tr>
  <tr>
    <td>
XAPI-00321</td>
    <td>An LRS rejects with error code 400 Bad Request, a Request which does not use a "X-Experience-API-Version" header name to any API except the About API </td>
  </tr>
</table>


# 3.0.[ Data Validation](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#validation)

## 3.1.[ Concurrency](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#concurrency)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>XAPI-00322</td>
    <td>An LRS must support HTTP/1.1 entity tags (ETags) to implement optimistic concurrency control when handling APIs where PUT may overwrite existing data (State, Agent Profile, and Activity Profile)</td>
  </tr>
</table>


## 3.2.[ Error Codes](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#errorcodes)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00323</td>
    <td>An LRS can only reject Statements using the error codes in this specification </td>
  </tr>
  <tr>
    <td>
XAPI-00324</td>
    <td>An LRS rejects with error code 400 Bad Request any request to an API which uses a parameter not recognized by the LRS </td>
  </tr>
  <tr>
    <td>
XAPI-00325</td>
    <td>An LRS rejects with error code 400 Bad Request any request to an API which uses a parameter with differing case </td>
  </tr>
  <tr>
    <td>
XAPI-00326</td>
    <td>An LRS rejects with a 400 Bad Request any batch of Statements in which one or more Statements is rejected and if necessary, restores the LRS to the state in which it was before the batch began processing. The response may identify the first statementId which failed. </td>
  </tr>
  <tr>
    <td>
XAPI-00327</td>
    <td>An LRS rejects a Statement of insufficient permissions (credentials are valid, but not adequate) with error code 403 Forbidden</td>
  </tr>
  <tr>
    <td>
XAPI-00328</td>
    <td>An LRS rejects a Statement due to size if the Statement exceeds the size limit the LRS is configured to with error code 413 Request Entity Too Large. Suggestion: test increasingly larger statements to identify capacity of the upper limit - 1MB, 5MB, 10MB, 20MB until a 413 is returned.</td>
  </tr>
  <tr>
    <td>
XAPI-00329</td>
    <td>An LRS rejects a Statement due to network/server issues with an error code of 500 Internal Server Error</td>
  </tr>
</table>


## 3.3[ Versioning](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#versioning)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00330</td>
    <td>An LRS will not modify Statements based on a "version" before "1.0.1" </td>
  </tr>
  <tr>
    <td>
XAPI-00331</td>
    <td>An LRS rejects with error code 400 Bad Request, a Request which the "X-Experience-API-Version" header's value is anything but "1.0" or "1.0.x", where x is the semantic versioning number to any API except the About API </td>
  </tr>
  <tr>
    <td>XAPI-00332</td>
    <td>Statements returned by an LRS MUST retain the version property they are accepted with.</td>
  </tr>
  <tr>
    <td>
XAPI-00333</td>
    <td>An LRS sends a header response with "X-Experience-API-Version" as the name and latest patch version after 1.0.0 as the value</td>
  </tr>
</table>


# 4.0.[ Authentication](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#authentication)

**Requirements**

<table>
  <tr>
    <td>ID</td>
    <td>Requirement</td>
  </tr>
  <tr>
    <td>
XAPI-00334</td>
    <td>An LRS rejects a Statement of bad authorization (either authentication needed or failed credentials) with error code 401 Unauthorized  </td>
  </tr>
  <tr>
    <td>XAPI-00335</td>
    <td>An LRS must support HTTP Basic Authentication</td>
  </tr>
</table>


## 4.1.[ OAuth 1.0 Authentication Scenarios and Methods](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#authdefs)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

## 4.2.[ OAuth 1.0 Authorization Scope](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#oauthscope)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

# 5.0[ Security](https://github.com/adlnet/xAPI-Spec/blob/1.0.3/xAPI-Communication.md#security)

With no applicable conformance requirements in this section of the xAPI Specification, this section is intentionally blank.

