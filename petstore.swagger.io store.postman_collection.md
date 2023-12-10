# URL:
https://petstore.swagger.io/v2/store

# Collection:
petstore.swagger.io store

# POST
Place an order
```json
		{
			"name": "Place an order",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"id\": 5,\r\n  \"petId\": 9223372036854692204,\r\n  \"quantity\": 5,\r\n  \"shipDate\": \"2023-09-02T17:42:47.534Z\",\r\n  \"status\": \"placed\",\r\n  \"complete\": true\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://petstore3.swagger.io/api/v3/store/order",
					"protocol": "https",
					"host": [
						"petstore3",
						"swagger",
						"io"
					],
					"path": [
						"api",
						"v3",
						"store",
						"order"
					]
				}
			},
			"response": []
		}
```
# GET
Find purchase order by ID
```json
		{
			"name": "Find purchase order by ID",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "accept",
						"value": "application/json"
					},
					{
						"key": "Content-Type",
						"value": "application/json"
					}
				],
				"body": {
					"mode": "raw",
					"raw": ""
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/store/order/5",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"store",
						"order",
						"5"
					]
				}
			},
			"response": []
		}
```
# DELETE
Delete purchase order by ID
```json
		{
			"name": "Delete purchase order by ID",
			"request": {
				"method": "DELETE",
				"header": [
					{
						"key": "accept",
						"value": "application/json"
					},
					{
						"key": "Content-Type",
						"value": "application/json"
					}
				],
				"body": {
					"mode": "raw",
					"raw": ""
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/store/order/5",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"store",
						"order",
						"5"
					]
				}
			},
			"response": []
		}
```
# GET
Inventory
```json
		{
			"name": "Inventory",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "accept",
						"value": "application/json"
					},
					{
						"key": "Content-Type",
						"value": "application/json"
					}
				],
				"body": {
					"mode": "raw",
					"raw": ""
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/store/inventory",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"store",
						"inventory"
					]
				}
			},
			"response": []
		}
```
