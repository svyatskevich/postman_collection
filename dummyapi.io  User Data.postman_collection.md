# URL:
https://dummyapi.io/data/v1/user
# Collection:
User Data


# GET
Get List
```json
		{
			"name": "Get List",
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "app-id",
						"value": "64f34af2915e08b06baea15c",
						"type": "text"
					}
				],
				"url": {
					"raw": "https://dummyapi.io/data/v1/user",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"user"
					]
				}
			},
			"response": []
		}
```
# GET
Get User by id
```json
		{
			"name": "Get User by id",
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "app-id",
						"value": "64f34af2915e08b06baea15c",
						"type": "text"
					}
				],
				"url": {
					"raw": "https://dummyapi.io/data/v1/user/:id",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"user",
						":id"
					],
					"variable": [
						{
							"key": "id",
							"value": "64f34fd4a973971598b6a8bb"
						}
					]
				}
			},
			"response": []
		}
```
# POST
Create User
```json
		{
			"name": "Create User",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "app-id",
						"value": "64f34af2915e08b06baea15c",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"firstName\": \"TestTest\",\r\n  \"lastName\": \"TestTest\",\r\n  \"email\": \"test123123@gmail.com\"\r\n} ",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://dummyapi.io/data/v1/user/create",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"user",
						"create"
					]
				}
			},
			"response": []
		}
```
# PUT
Update User
```json
		{
			"name": "Update User",
			"request": {
				"method": "PUT",
				"header": [
					{
						"key": "app-id",
						"value": "64f34af2915e08b06baea15c",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n  \"firstName\": \"TestTest2\",\r\n  \"lastName\": \"TestTest2\"\r\n} ",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://dummyapi.io/data/v1/user/:id",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"user",
						":id"
					],
					"variable": [
						{
							"key": "id",
							"value": "64f34fd4a973971598b6a8bb"
						}
					]
				}
			},
			"response": []
		}
```
# DELETE
Delete User
```json
		{
			"name": "Delete User",
			"request": {
				"method": "DELETE",
				"header": [
					{
						"key": "app-id",
						"value": "64f34af2915e08b06baea15c",
						"type": "text"
					}
				],
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
					"raw": "https://dummyapi.io/data/v1/user/:id",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"user",
						":id"
					],
					"variable": [
						{
							"key": "id",
							"value": "64f34fd4a973971598b6a8bb"
						}
					]
				}
			},
			"response": []
		}
```
