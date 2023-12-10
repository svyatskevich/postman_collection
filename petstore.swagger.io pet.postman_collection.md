# URL:
https://petstore.swagger.io/v2/pet

# Collection:
petstore.swagger.io pet

# POST
Add a new pet
```json
		{
			"name": "Add a new pet",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"id\": 0,\r\n  \"category\": {\r\n    \"id\": 5,\r\n    \"name\": \"Loki\"\r\n  },\r\n  \"name\": \"Loki\",\r\n  \"photoUrls\": [\r\n    \"string\"\r\n  ],\r\n  \"tags\": [\r\n    {\r\n      \"id\": 5,\r\n      \"name\": \"Loki\"\r\n    }\r\n  ],\r\n  \"status\": \"available\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/pet",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"pet"
					]
				}
			},

			"response": []
		}
```
# POST
Upload image
```json
		{
			"name": "Upload image",
			"request": {
				"method": "POST",
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
					"raw": "{\n  \"id\": 17,\n  \"name\": \"doggie\",\n  \"category\": {\n    \"id\": 1,\n    \"name\": \"Dogs\"\n  },\n  \"photoUrls\": [\n    \"string\"\n  ],\n  \"tags\": [\n    {\n      \"id\": 0,\n      \"name\": \"string\"\n    }\n  ],\n  \"status\": \"available\"\n}"
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/pet/9223372036854691911/uploadImage",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"pet",
						"9223372036854691911",
						"uploadImage"
					],
					"query": [
						{
							"key": "additionalMetadata",
							"value": "",
							"disabled": true
						},
						{
							"key": "file",
							"value": "",
							"disabled": true
						},
						{
							"key": "petId",
							"value": "9223372036854691911",
							"disabled": true
						}
					]
				}
			},
			"response": []
		}
```
# GET
Find pet by ID
```json
		{
			"name": "Find pet by ID",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/pet/9223372036854692204",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"pet",
						"9223372036854692204"
					]
				}
			},
			"response": []
		}
```
# GET
Find pet by status
```json
		{
			"name": "Find pet by status",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/pet/findByStatus?status=available",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"pet",
						"findByStatus"
					],
					"query": [
						{
							"key": "status",
							"value": "available"
						}
					]
				}
			},
			"response": []
		}
```
# PUT
Update an existing pet
```json
		{
			"name": "Update an existing pet",
			"request": {
				"method": "PUT",
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
					"raw": "{\n    \"id\": 9223372036854691911,\n    \"category\": {\n        \"id\": 5,\n        \"name\": \"Loki\"\n    },\n    \"name\": \"Loki\",\n    \"photoUrls\": [\n        \"string\"\n    ],\n    \"tags\": [\n        {\n            \"id\": 5,\n            \"name\": \"Loki\"\n        }\n    ],\n    \"status\": \"available\"\n}"
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/pet",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"pet"
					]
				}
			},
			"response": []
		}
```
# POST
Update a pet in the store
```json
		{
			"name": "Update a pet in the store",
			"request": {
				"method": "POST",
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
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "https://petstore.swagger.io/v2/pet/9223372036854692204?name=Love&status=sold",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"pet",
						"9223372036854692204"
					],
					"query": [
						{
							"key": "name",
							"value": "Love"
						},
						{
							"key": "status",
							"value": "sold"
						}
					]
				}
			},
			"response": []
		}
```
# DELETE
Delete a pet
```json
		{
			"name": "Delete a pet",
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
					"raw": "https://petstore.swagger.io/v2/pet/9223372036854692204",
					"protocol": "https",
					"host": [
						"petstore",
						"swagger",
						"io"
					],
					"path": [
						"v2",
						"pet",
						"9223372036854692204"
					]
				}
			},
			"response": []
		}
```
