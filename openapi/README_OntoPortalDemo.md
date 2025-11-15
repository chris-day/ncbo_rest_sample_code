# OntoPortal Demo API – Developer Overview

This repository contains an unofficial OpenAPI 3.0 description and companion Postman collections for the OntoPortal Demo instance at https://demodata.ontoportal.org.

## 1. Multi-file OpenAPI layout

The OpenAPI spec is conceptually split into multiple files to keep things maintainable and aligned with functional domains.

### Structure

- openapi.yaml
- components/
  - security.yaml
  - parameters.yaml
  - schemas.yaml
- paths/
  - common.yaml
  - ontologies.yaml
  - categories.yaml
  - analytics.yaml
  - metrics.yaml
  - mappings.yaml
  - notes_replies.yaml
  - projects.yaml
  - users.yaml
  - provisionals.yaml

## 2. Tags

Tags group endpoints logically for Swagger UI/ReDoc and generated SDKs.

- Search
- Annotator
- Recommender
- Batch
- Ontologies
- Classes
- Categories
- Provisionals
- Metrics
- Analytics
- Mappings
- Notes
- Projects
- Users

## 3. Postman Collections

Example collections:

- ontoportal-search.postman_collection.json
- ontoportal-ontologies.postman_collection.json

A combined “kitchen sink” collection may also be provided.

## Usage

1. Import Postman collections.
2. Set environment variables such as API_KEY.
3. Explore grouped endpoints in Swagger UI or ReDoc.
