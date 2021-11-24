# identifiers | array of objects [{}]

## Description

A standard data structure appered in different level of the JSON data of the record, which hold unique identifiers to identifier different resource (e.g. person, publication, etc.).

### Table — Members of object

| Member (type) | Cardinality | Description | Allowed values |
| --------- | ----- | ----- | ----- |
| scheme (string) | 1..1 | The name of the persistent identifier scheme. | Terms of scheme vocabulary |
| schemeURI (string) | 0..1 | The URI of the persistent identifier scheme. | Allowed values |
| identifier (string) | 1..1 | Unique identifier for an individual or legal entity, based on scheme applied. |  |
| url (string) | 0..1 | The url of the identifier. |  |

### Table — Vocabulary of scheme

| shortID | Name | URI | Usage | Description |
| --------- | ----- | --------- | ----- | ----- |
| DOI | Digital Object Identifier | https://doi.org/ | {identifiers, relatedResources} | Digital Object Identifier; a character string used to uniquely identify an object. A DOI name is divided into two parts, a prefix and a suffix, separated by a slash. |
| Bibcode | Bibliographic code | https://ui.adsabs.harvard.edu/abs/ | {identifiers, relatedResources} | Astrophysics Data System bibliographic codes; a standardized 19 character identifier according to the syntax yyyyjjjjjvvvvmppppa. |
| CFID | Crossref Funder ID | https://doi.org/ | {funder} | ----- |
| R2R | R2R Cruise ID | https://doi.org/ | {relatedResources} | ----- |
| ORCID | Open Researcher and Contributor ID | https://orcid.org/ | {creators, contributors} | ----- |
| ROR | Research Organization Registry | https://ror.org/ | {affiliation, funder} | ----- |
| IGSN | International Global Sample Number | https://app.geosamples.org/sample/igsn/ | {relatedResources} | ----- |
| SVN | Smithsonian Volcano Number | https://volcano.si.edu/volcano.cfm?vn= | {relatedResources} | ----- |

## Usage

* If **identifiers** is used, and there is at least one object, in which **scheme** and **identifier** are mandatory for submission.
  