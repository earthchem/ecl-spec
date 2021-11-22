# type | string

## Description

The nature or genre of the resource.Values come from DCMI Type Vocabulary.

### Table — Metadata for the type property

| Attribute | Value |
| --------- | ----- |
| Required | Yes |
| Cardinality | 1..1 |
| Allowed values | Terms of type vocabulary |

### Table — Vocabulary of type

| Term | Description |
| --------- | ----- |
| Collection | An aggregation of resources. |
| Dataset | Data encoded in a defined structure. |
| Event | A non-persistent, time-based occurrence. |
| Image | A visual representation other than text. |
| InteractiveResource | A resource requiring interaction from the user to be understood, executed, or experienced. |
| MovingImage | A series of visual representations imparting an impression of motion when shown in succession. |
| PhysicalObject | An inanimate, three-dimensional object or substance. |
| Service | A system that provides one or more functions. |
| Software | A computer program in source or compiled form. |
| Sound | A resource primarily intended to be heard. |
| StillImage | A static visual representation. |
| Text | A resource consisting primarily of words for reading. |

## Credit

[DCMI-TYPE] DCMI Type Vocabulary. URL: https://dublincore.org/documents/dcmi-type-vocabulary/

## Mappings

| ECL | DataCite (V4.3) | Zenodo (record-v1.0.0) |
| --------- | ----- | ----- |
| type | resourceTypeGeneral | resource_type |