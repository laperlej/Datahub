# Harvard Dataverse

## Table of Content

- [Harvard Dataverse](#harvard-dataverse)
  - [Table of Content](#table-of-content)
  - [Summary](#summary)
    - [info](#info)
    - [key features](#key-features)
    - [Negative points](#negative-points)
  - [Overview](#overview)
    - [general](#general)
    - [collections](#collections)
    - [Branding](#branding)
    - [other features](#other-features)
    - [citations](#citations)
    - [SSO sources](#sso-sources)
    - [permissions](#permissions)

## Summary

### info

- https://dataverse.org
- from Harvard

### key features

- free
- Institutions can have an account to publish data( department, journal, university, ... )
- API based
- focus on data publication
- can be embeded in websites
- search widget
- Options for sharing deidentified or sensitive data
- Data analysis and visualization tools 

### Negative points

- <2.5GB files
- <1TB total
- lots of overhead with handling metadata
- cannot be deleted once published

## Overview

### general

- Files are part of "[Collections](#collections)"
- uses metadata
- need title, authors, description
- "Pubish" will make accessible and generate a formal [citation](#citations)

### collections

- can be nested
- requires metadata like email affiliation, etc
- webpage with branding
- datasets also need metadata
- metadata fields are defined by collection
- metadata standards available to speed up process
- use metadata fields to create dataset templates
- choose whihc fields to use for search

### Branding

- can be embeded in webpages
- custom logo
- custom footer
- link to department
- colors (background/link/text)

### other features

- collect data about who downloads
- some formats with metadata have extra features (RData, SPSS, STATA, CSV, xlsx, FITS), this allows for search based on metadata

### citations

- author name(s)
- year (date published in the Dataverse repository)
- title
- global persistent identifier: DOI or Handle
publisher (repository that published the dataset)
- version number
- universal numerical fingerprint (UNF): for tabular data

![citation](Screen%20Shot%202022-06-19%20at%207.31.13%20PM.png)

### SSO sources

- Institutional affiliation login
- Username/email
- ORCID
- GitHub
- Google
  
### permissions

- rules
  - ViewUnpublishedDataset
  - DownloadFile
  - EditDataset
  - DeleteDatasetDraft
  - PublishDataset
- datasets requires approval depending on role
- roles are granted to institutions, users or ip address. Can be grouped.