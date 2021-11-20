# status

## Description

Indication of the progress status of the resource. Value comes from ECL controlled vocabulary.

## Table — Metadata for the status property

| Attribute | Value |
| --------- | ----- |
| Required | Yes |
| Cardinality | 1..1 |
| Type | string |
| Allowed values | ECL Controlled vocabulary |

## Table — Vocabulary of status

| Term | Description |
| --------- | ----- |
| incomplete | Started and saved by user, not yet submitted for review. |
| submitted | Submitted by user for review, not yet published. |
| published | Approved by ECL staff, DOI assigned (unless user opted out), metadata viewable on the ECL interface. If after Release Date, file(s) available for download. |
| rejected | Submitted by user but rejected by ECL (e.g., inappropriate content). |
| archived | A previously public submission that has since been archived and is no longer available for metadata view or file download. |

## Usage

* The **status** should be set to **incomplete** by user when user create a new record.
* The **status** should stay at **incomplete** when user modify and save the record, but not ready to be reviewed.
* The **status** should be changed from **incomplete** to **submitted** by user when user wants the record to be reviewed by ECL after fill in all required metadata and attach relevant files to the record.
* User can not change the **status** from **submitted** back to **incomplete**
* THe **status** will be changed from **submitted** to **incomplete** by reviewer if furthur modification required after the review.
* User can not modify or delete the record when the **status** is one of **submitted**, **published**, and **archived**.
* User can modify or delete the record when the **status** is **incomplete**.
