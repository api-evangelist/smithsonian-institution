# Smithsonian Institution

The Smithsonian Institution provides open access APIs to its collections of over 22 million objects, artworks, and natural history specimens from 19 museums, 21 libraries, and 9 research centers. The Open Access API enables developers to search and retrieve collection data, images, and metadata.

## APIs

| API | Description |
|-----|-------------|
| [Open Access API](openapi/smithsonian-open-access-openapi.yml) | Search and retrieve museum collection data, media, and metadata |

## Artifacts

### OpenAPI Specifications
- [smithsonian-open-access-openapi.yml](openapi/smithsonian-open-access-openapi.yml) — Open Access API (search, content retrieval, metrics)

### Capabilities
- [collection-discovery.yaml](capabilities/collection-discovery.yaml) — Collection discovery and exploration workflow

#### Shared Definitions
- [capabilities/shared/open-access-api.yaml](capabilities/shared/open-access-api.yaml) — Open Access API capability definition

### Rules
- [smithsonian-rules.yml](rules/smithsonian-rules.yml) — Spectral ruleset for Smithsonian API conventions

### JSON Schema
- [smithsonian-collection-item-schema.json](json-schema/smithsonian-collection-item-schema.json) — Collection item entity schema

### JSON Structure
- [smithsonian-collection-item-structure.json](json-structure/smithsonian-collection-item-structure.json) — Collection item object structure

### JSON-LD
- [smithsonian-institution-context.jsonld](json-ld/smithsonian-institution-context.jsonld) — Linked data context mapping to schema.org

### Examples
- [smithsonian-search-collections-example.json](examples/smithsonian-search-collections-example.json) — Collection search request/response

### Vocabulary
- [smithsonian-institution-vocabulary.yml](vocabulary/smithsonian-institution-vocabulary.yml) — Museum and collection domain vocabulary

## Authentication

API key required — register for free at [api.data.gov](https://api.data.gov/signup)

## Developer Resources

- [Developer Tools](https://www.si.edu/openaccess/devtools)
- [Open Access Portal](https://www.si.edu/openaccess)
- [Metadata Documentation](https://edan.si.edu/openaccess/docs/)
- [GitHub Organization](https://github.com/Smithsonian)
- [Data Repository](https://github.com/Smithsonian/OpenAccess)
- [Python Client](https://github.com/Smithsonian/smithsonian-openaccess)
