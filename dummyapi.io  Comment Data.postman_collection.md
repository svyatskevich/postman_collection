# URL:
https://dummyapi.io/data/v1/comment
# Collection:
Comment Data


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
					"raw": "https://dummyapi.io/data/v1/comment",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"comment"
					]
				}
			},
			"response": []
		}
```
# GET
Get List By Post
```json
		{
			"name": "Get List By Post",
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
					"raw": "https://dummyapi.io/data/v1/post/:id/comment",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"post",
						":id",
						"comment"
					],
					"variable": [
						{
							"key": "id",
							"value": "60d21bad67d0d8992e610daf"
						}
					]
				}
			},
			"response": []
		}
```
# GET
Get List By User
```json
		{
			"name": "Get List By User",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
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
					"raw": "https://dummyapi.io/data/v1/user/:id/comment",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"user",
						":id",
						"comment"
					],
					"variable": [
						{
							"key": "id",
							"value": "60d0fe4f5311236168a10a29"
						}
					]
				}
			},
			"response": []
		}
```
# POST
Create Comment
```json
		{
			"name": "Create Comment",
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
					"raw": "{\r\n\"message\": \"Axaxax\",\r\n\"owner\": \"64f34fd4a973971598b6a8bb\",\r\n\"post\": \"64f36a38ce4f016609344c4d\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://dummyapi.io/data/v1/comment/create",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"comment",
						"create"
					]
				}
			},
			"response": []
		}
```
# DELETE
Delete Comment
```json
		{
			"name": "Delete Comment",
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
					"raw": "https://dummyapi.io/data/v1/comment/:id",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"comment",
						":id"
					],
					"variable": [
						{
							"key": "id",
							"value": "64f37210fa7928a0f01d063c"
						}
					]
				}
			},
			"response": []
		}
	
```
