# community | string

## Description

A network of interacting scientists defined by ECL/AstroRepo. Values come from ECL/AstroRepo controlled vocabulary.

### Table — Metadata for the status property

| Attribute | Value |
| --------- | ----- |
| Required | Yes |
| Cardinality | 1..1 |
| Allowed values | Terms of communities vocabulary |

### Table — Vocabulary of communities

| Term | Description |
| --------- | ----- |
| Geochemistry & Petrology |  |
| Cosmochemistry |  |
| Geochronology |  |
| Experimental Petrology |  |
| Tephra Data |  |
| Clumped Isotopes |  |
| CZNet |  |

## Intent

Community is used to categorize ECL/AstroRepo records at the community level.

## Mappings

| ECL | Zenodo (record-v1.0.0) |
| --------- | ----- |
| community (string) | communities (array of string) |
