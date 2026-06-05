# Country.io (country-io)

Country.io is a small open data project that publishes a set of static JSON files mapping ISO 3166-1 alpha-2 country codes to common reference data: country names, capital cities, ISO 3166-1 alpha-3 codes, continent codes, international telephone dialing prefixes, and ISO 4217 currency codes. The files are commonly consumed as a lightweight country-data dataset for forms, country pickers, and analytics enrichment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/country-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/country-io/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- Capitals
- Continents
- Countries
- Currencies
- Currency Codes
- Dialing Codes
- Geography
- ISO 3166
- JSON
- Open Data
- Phone Codes
- Reference Data

## Timestamps

- **Created:** 2025-02-21
- **Modified:** 2026-05-19

## APIs

### Country.io Data API

Country.io exposes six static JSON files under https://country.io. Each file is a flat object keyed by ISO 3166-1 alpha-2 country code and maps to a single reference value: country name, capital city, continent code, ISO3 code, dialing prefix, or currency code. The endpoints are open and unauthenticated.

- **Human URL:** [https://country.io/data/](https://country.io/data/)
- **Base URL:** `https://country.io`

#### Tags

- Capitals
- Countries
- Currencies
- ISO 3166
- Open Data
- Phone Codes
- Reference Data

#### Properties

- [Documentation](https://country.io/data/)
- [OpenAPI](openapi/country-io-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/country-io-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/country-io-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/country-io-data-rules.yml)
- [Capabilities](capabilities/country-io-data-capabilities.yml)

## Common Properties

- [Website](https://country.io/)
- [Data](https://country.io/data/)
- [Countries](https://country.io/countries/)
- [Rankings](https://country.io/rankings/)
- [Contact](https://country.io/contact/)
- [Vocabulary](vocabulary/country-io-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
