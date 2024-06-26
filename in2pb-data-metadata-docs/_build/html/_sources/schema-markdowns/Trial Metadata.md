# Trial metadata element schema

**Description:** Trial metadata element schema generated by the CEDAR Template Editor 2.6.56

## Session Identifier

**Label:** sessionID

**Description:** Session identifier in which the trial being described occurs.

**Required:** No

**Input Type:** textfield

**Value Relation Links:** [Link](https://schema.metadatacenter.org/properties/f630ff04-b56e-4122-80f7-60e87c9b8e2e) <details>
<summary>Field Schema JSON</summary>

```json
{
  "@type": "https://schema.metadatacenter.org/core/TemplateField",
  "@context": {
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "pav": "http://purl.org/pav/",
    "bibo": "http://purl.org/ontology/bibo/",
    "oslc": "http://open-services.net/ns/core#",
    "schema": "http://schema.org/",
    "skos": "http://www.w3.org/2004/02/skos/core#",
    "schema:name": {
      "@type": "xsd:string"
    },
    "schema:description": {
      "@type": "xsd:string"
    },
    "skos:prefLabel": {
      "@type": "xsd:string"
    },
    "skos:altLabel": {
      "@type": "xsd:string"
    },
    "pav:createdOn": {
      "@type": "xsd:dateTime"
    },
    "pav:createdBy": {
      "@type": "@id"
    },
    "pav:lastUpdatedOn": {
      "@type": "xsd:dateTime"
    },
    "oslc:modifiedBy": {
      "@type": "@id"
    }
  },
  "type": "object",
  "title": "sessionID field schema",
  "description": "sessionID field schema generated by the CEDAR Template Editor 2.6.54",
  "_ui": {
    "inputType": "textfield"
  },
  "_valueConstraints": {
    "requiredValue": false
  },
  "properties": {
    "@type": {
      "oneOf": [
        {
          "type": "string",
          "format": "uri"
        },
        {
          "type": "array",
          "minItems": 1,
          "items": {
            "type": "string",
            "format": "uri"
          },
          "uniqueItems": true
        }
      ]
    },
    "@value": {
      "type": [
        "string",
        "null"
      ]
    },
    "rdfs:label": {
      "type": [
        "string",
        "null"
      ]
    }
  },
  "required": [
    "@value"
  ],
  "schema:name": "sessionID",
  "schema:description": "Session identifier in which the trial being described occurs.",
  "pav:createdOn": "2024-05-14T01:41:53-07:00",
  "pav:createdBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "pav:lastUpdatedOn": "2024-05-14T01:41:53-07:00",
  "oslc:modifiedBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "schema:schemaVersion": "1.6.0",
  "additionalProperties": false,
  "skos:prefLabel": "Session Identifier",
  "@id": "https://repo.metadatacenter.org/template-fields/07f28d02-735f-4a69-9f50-29221fc5efe4",
  "$schema": "http://json-schema.org/draft-04/schema#"
}
```
</details>

## Trial ID

**Label:** trialID

**Description:** Unique identifier associated with each trial.

**Required:** No

**Input Type:** textfield

**Value Relation Links:** [Link](http://www.geneontology.org/formats/oboInOwl#id) <details>
<summary>Field Schema JSON</summary>

```json
{
  "@type": "https://schema.metadatacenter.org/core/TemplateField",
  "@context": {
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "pav": "http://purl.org/pav/",
    "bibo": "http://purl.org/ontology/bibo/",
    "oslc": "http://open-services.net/ns/core#",
    "schema": "http://schema.org/",
    "skos": "http://www.w3.org/2004/02/skos/core#",
    "schema:name": {
      "@type": "xsd:string"
    },
    "schema:description": {
      "@type": "xsd:string"
    },
    "skos:prefLabel": {
      "@type": "xsd:string"
    },
    "skos:altLabel": {
      "@type": "xsd:string"
    },
    "pav:createdOn": {
      "@type": "xsd:dateTime"
    },
    "pav:createdBy": {
      "@type": "@id"
    },
    "pav:lastUpdatedOn": {
      "@type": "xsd:dateTime"
    },
    "oslc:modifiedBy": {
      "@type": "@id"
    }
  },
  "type": "object",
  "title": "trialID field schema",
  "description": "trialID field schema generated by the CEDAR Template Editor 2.6.54",
  "_ui": {
    "inputType": "textfield"
  },
  "_valueConstraints": {
    "requiredValue": false
  },
  "properties": {
    "@type": {
      "oneOf": [
        {
          "type": "string",
          "format": "uri"
        },
        {
          "type": "array",
          "minItems": 1,
          "items": {
            "type": "string",
            "format": "uri"
          },
          "uniqueItems": true
        }
      ]
    },
    "@value": {
      "type": [
        "string",
        "null"
      ]
    },
    "rdfs:label": {
      "type": [
        "string",
        "null"
      ]
    }
  },
  "required": [
    "@value"
  ],
  "schema:name": "trialID",
  "schema:description": "Unique identifier associated with each trial.",
  "pav:createdOn": "2024-05-14T01:41:53-07:00",
  "pav:createdBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "pav:lastUpdatedOn": "2024-05-14T01:41:53-07:00",
  "oslc:modifiedBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "schema:schemaVersion": "1.6.0",
  "additionalProperties": false,
  "@id": "https://repo.metadatacenter.org/template-fields/1298a95c-77f6-4968-ab07-7b5b8b037191",
  "skos:prefLabel": "Trial ID",
  "$schema": "http://json-schema.org/draft-04/schema#"
}
```
</details>

## Trial Start Timestamp

**Label:** trialTimeStamp

**Description:** Timestamp associated with the start of the trial.

**Required:** No

**Input Type:** temporal

**Value Relation Links:** [Link](http://purl.obolibrary.org/obo/RO_0002537) <details>
<summary>Field Schema JSON</summary>

```json
{
  "@type": "https://schema.metadatacenter.org/core/TemplateField",
  "@context": {
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "pav": "http://purl.org/pav/",
    "bibo": "http://purl.org/ontology/bibo/",
    "oslc": "http://open-services.net/ns/core#",
    "schema": "http://schema.org/",
    "skos": "http://www.w3.org/2004/02/skos/core#",
    "schema:name": {
      "@type": "xsd:string"
    },
    "schema:description": {
      "@type": "xsd:string"
    },
    "skos:prefLabel": {
      "@type": "xsd:string"
    },
    "skos:altLabel": {
      "@type": "xsd:string"
    },
    "pav:createdOn": {
      "@type": "xsd:dateTime"
    },
    "pav:createdBy": {
      "@type": "@id"
    },
    "pav:lastUpdatedOn": {
      "@type": "xsd:dateTime"
    },
    "oslc:modifiedBy": {
      "@type": "@id"
    }
  },
  "type": "object",
  "title": "trialTimeStamp field schema",
  "description": "trialTimeStamp field schema generated by the CEDAR Template Editor 2.6.54",
  "_ui": {
    "inputType": "temporal",
    "timezoneEnabled": true,
    "inputTimeFormat": "12h",
    "temporalGranularity": "second"
  },
  "_valueConstraints": {
    "requiredValue": false,
    "temporalType": "xsd:time"
  },
  "properties": {
    "@type": {
      "oneOf": [
        {
          "type": "string",
          "format": "uri"
        },
        {
          "type": "array",
          "minItems": 1,
          "items": {
            "type": "string",
            "format": "uri"
          },
          "uniqueItems": true
        }
      ]
    },
    "@value": {
      "type": [
        "string",
        "null"
      ]
    },
    "rdfs:label": {
      "type": [
        "string",
        "null"
      ]
    }
  },
  "required": [
    "@value"
  ],
  "schema:name": "trialTimeStamp",
  "schema:description": "Timestamp associated with the start of the trial.",
  "pav:createdOn": "2024-05-14T01:41:53-07:00",
  "pav:createdBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "pav:lastUpdatedOn": "2024-05-14T01:41:53-07:00",
  "oslc:modifiedBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "schema:schemaVersion": "1.6.0",
  "additionalProperties": false,
  "skos:prefLabel": "Trial Start Timestamp",
  "@id": "https://repo.metadatacenter.org/template-fields/13d276c2-6503-468e-a15f-dc84f5910824",
  "$schema": "http://json-schema.org/draft-04/schema#"
}
```
</details>

## Trial End Timestamp

**Label:** trialEndStamp

**Description:** Timestamp associated with the end of the trial.

**Required:** No

**Input Type:** temporal

**Value Relation Links:** [Link](http://purl.obolibrary.org/obo/RO_0002538) <details>
<summary>Field Schema JSON</summary>

```json
{
  "@type": "https://schema.metadatacenter.org/core/TemplateField",
  "@context": {
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "pav": "http://purl.org/pav/",
    "bibo": "http://purl.org/ontology/bibo/",
    "oslc": "http://open-services.net/ns/core#",
    "schema": "http://schema.org/",
    "skos": "http://www.w3.org/2004/02/skos/core#",
    "schema:name": {
      "@type": "xsd:string"
    },
    "schema:description": {
      "@type": "xsd:string"
    },
    "skos:prefLabel": {
      "@type": "xsd:string"
    },
    "skos:altLabel": {
      "@type": "xsd:string"
    },
    "pav:createdOn": {
      "@type": "xsd:dateTime"
    },
    "pav:createdBy": {
      "@type": "@id"
    },
    "pav:lastUpdatedOn": {
      "@type": "xsd:dateTime"
    },
    "oslc:modifiedBy": {
      "@type": "@id"
    }
  },
  "type": "object",
  "title": "trialEndStamp field schema",
  "description": "trialEndStamp field schema generated by the CEDAR Template Editor 2.6.54",
  "_ui": {
    "inputType": "temporal",
    "timezoneEnabled": true,
    "inputTimeFormat": "12h",
    "temporalGranularity": "second"
  },
  "_valueConstraints": {
    "requiredValue": false,
    "temporalType": "xsd:time"
  },
  "properties": {
    "@type": {
      "oneOf": [
        {
          "type": "string",
          "format": "uri"
        },
        {
          "type": "array",
          "minItems": 1,
          "items": {
            "type": "string",
            "format": "uri"
          },
          "uniqueItems": true
        }
      ]
    },
    "@value": {
      "type": [
        "string",
        "null"
      ]
    },
    "rdfs:label": {
      "type": [
        "string",
        "null"
      ]
    }
  },
  "required": [
    "@value"
  ],
  "schema:name": "trialEndStamp",
  "schema:description": "Timestamp associated with the end of the trial.",
  "pav:createdOn": "2024-05-14T01:41:53-07:00",
  "pav:createdBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "pav:lastUpdatedOn": "2024-05-14T01:41:53-07:00",
  "oslc:modifiedBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "schema:schemaVersion": "1.6.0",
  "additionalProperties": false,
  "skos:prefLabel": "Trial End Timestamp",
  "@id": "https://repo.metadatacenter.org/template-fields/d4afd006-e1f4-4d2a-a424-22ad0a0ea849",
  "$schema": "http://json-schema.org/draft-04/schema#"
}
```
</details>

## Trial Type

**Label:** trialType

**Description:** Referemce to the trial type to be used.

**Required:** No

**Input Type:** textfield

**Value Relation Links:** [Link](http://purl.org/dc/elements/1.1/type) <details>
<summary>Field Schema JSON</summary>

```json
{
  "@type": "https://schema.metadatacenter.org/core/TemplateField",
  "@context": {
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "pav": "http://purl.org/pav/",
    "bibo": "http://purl.org/ontology/bibo/",
    "oslc": "http://open-services.net/ns/core#",
    "schema": "http://schema.org/",
    "skos": "http://www.w3.org/2004/02/skos/core#",
    "schema:name": {
      "@type": "xsd:string"
    },
    "schema:description": {
      "@type": "xsd:string"
    },
    "skos:prefLabel": {
      "@type": "xsd:string"
    },
    "skos:altLabel": {
      "@type": "xsd:string"
    },
    "pav:createdOn": {
      "@type": "xsd:dateTime"
    },
    "pav:createdBy": {
      "@type": "@id"
    },
    "pav:lastUpdatedOn": {
      "@type": "xsd:dateTime"
    },
    "oslc:modifiedBy": {
      "@type": "@id"
    }
  },
  "type": "object",
  "title": "trialType field schema",
  "description": "trialType field schema generated by the CEDAR Template Editor 2.6.54",
  "_ui": {
    "inputType": "textfield"
  },
  "_valueConstraints": {
    "requiredValue": false
  },
  "properties": {
    "@type": {
      "oneOf": [
        {
          "type": "string",
          "format": "uri"
        },
        {
          "type": "array",
          "minItems": 1,
          "items": {
            "type": "string",
            "format": "uri"
          },
          "uniqueItems": true
        }
      ]
    },
    "@value": {
      "type": [
        "string",
        "null"
      ]
    },
    "rdfs:label": {
      "type": [
        "string",
        "null"
      ]
    }
  },
  "required": [
    "@value"
  ],
  "schema:name": "trialType",
  "schema:description": "Referemce to the trial type to be used.",
  "pav:createdOn": "2024-05-14T01:41:53-07:00",
  "pav:createdBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "pav:lastUpdatedOn": "2024-05-14T01:41:53-07:00",
  "oslc:modifiedBy": "https://metadatacenter.org/users/f3d8067f-c204-45c0-8fb1-8393e486593c",
  "schema:schemaVersion": "1.6.0",
  "additionalProperties": false,
  "skos:prefLabel": "Trial Type",
  "@id": "https://repo.metadatacenter.org/template-fields/74e6f895-779d-4a2b-8c09-00154d9799ec",
  "$schema": "http://json-schema.org/draft-04/schema#"
}
```
</details>

