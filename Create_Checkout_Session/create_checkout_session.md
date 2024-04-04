# POST /create-checkout-session

## Create Checkout Session

### Request Body

- Media type: application/json

{
"apikey": "string" 
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
