curl -X 'POST' \
  'http://localhost:8080/greet' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "Walter",
  "language": "Spanish"
}'