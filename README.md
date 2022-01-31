# Party identifier additions - OCDS extension

OCDS extension that allows manually entered organisation identifier scheme names or the rationale for not providing an identifier.

Used by Find a Tender.

## Examples

### Manually entered scheme

```json
{
  "parties": [
    {
      "id": "GB-FTS-123",
      "name": "Company Ltd",
      "identifier": {
        "schemeEntered": "New Register",
        "id": "12345678"
      }
    }
  ]
}
```

### Rationale for no identifier

```json
{
  "parties": [
    {
      "id": "GB-FTS-456",
      "name": "Crown Commercial Service",
      "identifier": {
        "noIdentifierRationale": "notOnAnyRegister"
      }
    }
  ]
}
```
