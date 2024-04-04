

# POST /make_batch_toingg/

## Make Toingg

### Parameters

- `apiKey`: Your API key. (Type: string, Location: query, Required: Yes)

### Request Body

- Media type: application/json

{
"campaign": "string",
"numberList": {}
}

## Responses

- **200 Successful Response**

  - Media type: application/json
  - Example Value:
    {
    "string"
    }

- **422 Validation Error**
  - Media type: application/json
  - Example Value:
    {
    "detail": [
    {
    "loc": [
    "string",
    0
    ],
    "msg": "string",
    "type": "string"
    }
    ]
    }

