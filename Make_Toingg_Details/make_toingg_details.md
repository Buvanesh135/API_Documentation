# POST /make_toingg_details/

## Make Toingg

### Parameters

#### apiKey

- **Type:** string
- **Location:** query
- **Description:** apiKey

### Request body

- **Content Type:** application/json

#### Example Value
{
  "campaignName": "string",
  "campaignScript": "string",
  "name": "string",
  "phoneNumber": "string"
}
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


