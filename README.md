# RAML-online-shopping-website

RAML SPECIFICATION FOR ONLINE SHOPPING WEBSITE

APIs:
1. /orders/submitOrder: Submitting an order (POST)
2. /orders/{cartID}: Updating and Deleting an order (PUT/ DELETE)
2. /orders/priceDetails/{custID}: To get prices details and total cost of cart of a customer (GET)

APIs protected using Client_ID Client_Secret to allow only authorized users to make requests.


Cloudhub Endpoints:
1. GET mule-worker-internal-<<cloudHubUrl>>:8091/api/reports
2. GET mule-worker-internal-<<cloudHubUrl>>:8091/api/reports/{reportId}
3. GET mule-worker-internal-< cloudHubUrl >:8091/api/reports/{reportId}/fields
4. POST mule-worker-internal-<< cloudHubUrl >>:8091/api/query
