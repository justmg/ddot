First step is to run the server by executing src/app.js
Then use /scrape endpoint on the server.
Paste this Curl request in the post request,
curl --location 'http://localhost:3000/scrape' \
--header 'Accept: application/json' \
--header 'Content-Type: application/json' \
--data '{
    "noticeNumber": "L0011592389",
    "taxPayerID": "0707"
}
'
