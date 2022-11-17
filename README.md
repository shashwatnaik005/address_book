Kindly change the the mongodb server url in main.py

use postman to send api request

--for VIEWING all address in Address Book
request method: "GET"
url: http://127.0.0.1:5000/
body(in json format): none

--to SEARCH address
request method: "GET"
url: http://127.0.0.1:5000/address
body(in json format): Search criteria

--to add address to Address Book
request method: "POST"
url: http://127.0.0.1:5000/address
body(in json format): Address details

--to update address
request method: "PUT"
url: http://127.0.0.1:5000/update/<id>
body(in json format): value to be updated

--to delete a address
request method: "DELETE"
url: http://127.0.0.1:5000/address/<id>
body(in json format): none
