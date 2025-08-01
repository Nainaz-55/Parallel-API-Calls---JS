# Parallel-API-Calls---JS
Calling Services in Parallel Using JavaScript

performed the following tasks:
- Call APIs from JavaScript.
- Separate requests from responses in order to call APIs in parallel.

### Tasks
- **Created New No Target Proxy**
- **Added a JavaScript policy to call the Google Book API.**
- **Added a JavaScript policy to the responses to retrieve the responses and combine them into a single response.**
- **Add an AssignMessage policy to build the response**

## Curl to test the API
`curl -k -X GET "https://eval.example.com/lab8a/v1?search=java,sql,python" | jq ` <br>
**Response:**<br>
```
[
    {
        "query" : "java",
        "result" : {
            "items" : [
                {
                "accessInfo" : {
                    "accessViewStatus" : "SAMPLE",
                    "country" : "US",
                    "embeddable" : true,
                    "epub" : {
                        "isAvailable" : false
                    },
                    "pdf" : {
                        "isAvailable" : true
                    },
                    "publicDomain" : false,
                    "quoteSharingAllowed" : false,
                    "textToSpeechPermission" : "ALLOWED",
                    "viewability" : "PARTIAL",
                    "webReaderLink" : "http://play.google.com/books/reader?id=nzhxR1spWEYC&hl=&source=gbs_api"
                },
                "etag" : "I/aKsW0+3W4",
                "id" : "nzhxR1spWEYC",
                "kind" : "books#volume",
                "saleInfo" : {
                    "country" : "US",
                    "isEbook" : false,
                    "saleability" : "NOT_FOR_SALE"
                },
                "selfLink" : "https://www.googleapis.com/books/v1/volumes/nzhxR1spWEYC",
...................
```
