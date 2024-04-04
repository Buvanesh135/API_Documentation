# API_Documentation
                         Transforming API Documentation to Markdoc for Enhanced Developer Experience




                                               Project Explantion 

                                               

     Here i Taken Example of Make_batch_API.md ,Similar documentation is done for all other Document as Well

    1. # POST /make_batch_toingg/

     2.## Make Toingg

     3.### Parameters

     4.- `apiKey`: Your API key. (Type: string, Location: query, Required: Yes)

     5.### Request Body

     6.- Media type: application/json

     7.{
     "campaign": "string",
     "numberList": {}
     }

    8. ## Responses

    9.- **200 Successful Response**

     - Media type: application/json
     - Example Value:
     {
     "string"
     }

    10. - **422 Validation Error**
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


Line 1:Actually, The Hash symbol represent the Heading single Hash is consider Heading Tag as <h1> tag double hash means <h2> tag
           ##  POST /make_batch_toingg/    ->Basically it is Text, This text provides information about the HTTP method (POST) and the endpoint (/make_toingg/). It informs the reader that this section of the documentation pertains to making a "Toingg" via a POST request to the /make_toingg/ endpoint.

Line 2:  ## Make Toingg -> this is Heading section in mark doc used to provide more Information About the Purpoe End Point

Line 3: 3.### Parameters  -> This represent Heading level 3 tag used to specify which Parameter to be used which Parameter section basically we pass paramater to API's While calling Endpoint


Line 4.  -`apiKey`: Your API key. (Type: string, Location: query, Required: Yes) -> this section comes under Parameter section 
          '-' --> represent the unorder list Item in markdown  
          apikey-> name of parameter of list item
          Type-> represent that this parameter should be of String Type
          Location-> specifies where the parameter has be placed ,So here it shoulb be in query String
          Required-> this is like providing constraints to API that this parameter should be Provided


Line 5: ### Request Body  -> this specifies next section that is request Body where the data are passed to Endpoint


Line 6: - Media type: application/json -> this specifies the that data provided should be in json format  and content type in header Section of endpoint  should be set to  application/json 


Line 7:
     {
     "campaign": "string",
     "numberList": {}
     }
     this is the Example i Provide here the data is in form of json  numberList {}-> this represent the numberlist should be of type Object and Campaign property of type String


line 8: ## Responses -> this is another Section response Section ##-> represent Heading level 2  that is <h2> tag


line 9. - **200 Successful Response**
     - Media type: application/json
     - Example Value:
     {
     "string"
     }   
     This represent sample that how the  succesful response of API have to Come
     Media type:application/json -> represent that 
     String ->representing Succesful message of endpoint
     200-> http status code for successful message
     **-> makes it bold 
     here it is represented  as {} for json format of Response


line 10.- **422 Validation Error**
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
     }   This represent how the response of endpoint have to be  if it fails
         422-> Status code for Any Internal Server error or Bad Request Came
         loc -> this represent the location of  where the exact error happened in Code
         msg-> represents string related Error Message  and type is also set to string
         here
         loc-> list contains multiple values 
 
     




                                                       Setup

step1: At First,Basically to transform given API to MarkDoc we can  use any text editor you prefer. Here in My Case I Used VS Code 

step2: After that, Create one file and Write MarkDown Tags and Content to be Added and Save the File with .md extension

step3: To Preview the MarkDocument in Better feel Install the extension "Markdown Preview Enhanced" and to preview markdoc Use 
          1->use Command :ctrl+shift+p 
         `2-> Click on Markdown Preview Enhanced to Preview
          3 ->Now you can view the file in Well Strutured and in Much Defined Format
          4 ->right click to Export to HTML Format

step4 :In my Case I Used to Transform the MarkDown to HTML So that i Can we Displayed while Deployment


                                        





                                        How To View the Document 


               1.Here I Hosted   the  API Documentation  as  WebSite and its Simple to View 

               Here are steps:
               step 1: Click on this Link https://buvanesh135.github.io/API_Documentation/
               step 2: Now you can view Each and every Documentation Made for Every API
               step 3: Click ON "open" Button to View it


               


