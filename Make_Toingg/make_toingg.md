

## POST /make_toingg/

### Make Toingg

#### Parameters

- `apiKey`: Your API key. (Type: string, Location: query, Required: Yes)

#### Request Body

{
"campaign": "string",
"name": "string",
"phoneNumber": "string"
}

### Responses

- **200 Successful Response**

  - Media type: application/json
  - Example Value:
    ```json
    "success"
    ```

- **422 Validation Error**
  - Media type: application/json
  - Example Value:
    {
    "detail": [
    {
    "loc": ["string", 0],
    "msg": "Invalid phone number",
    "type": "validation_error"
    }
    ]
    }
