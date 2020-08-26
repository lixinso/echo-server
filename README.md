# echo-server

Print/Log the request for debugging purpose

Modified based on https://gist.github.com/huyng/814831

$ python2 echo.py


Test:


curl --location --request POST 'http://localhost:8080/' \
--header 'headerkey1: headervalue1' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonbodykey1": "value1"
}'
