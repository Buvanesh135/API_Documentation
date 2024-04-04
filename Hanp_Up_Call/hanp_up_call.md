# POST /hang_up_call/

## Hang Up Call

### Parameters

- `callSid`: The call session ID. (Type: string, Location: query, Required: Yes)
- `apiKey`: Your API key. (Type: string, Location: query, Required: Yes)

### Responses

- **200 Successful Response**

  - Media type: application/json
  - Example Value:
    "string"

- **422 Validation Error**
  - Media type: application/json
  - Example Value:
    {
    "detail": [
    {
    "loc": ["string", 0],
    "msg": "string",
    "type": "string"
    }
    ]
    }
