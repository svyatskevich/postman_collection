# URL:
https://dummyapi.io/data/v1/
# Collection:
Post Data


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
					"raw": "https://dummyapi.io/data/v1/post?page=3",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"post"
					],
					"query": [
						{
							"key": "page",
							"value": "3"
						}
					]
				}
			},
			"response": []
		}
```
# GET
Get list of tags
```json
		{
			"name": "Get list of tags",
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
					"raw": "https://dummyapi.io/data/v1/tag",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"tag"
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
					"raw": "https://dummyapi.io/data/v1/user/:id/post",
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
						"post"
					],
					"query": [
						{
							"key": "page",
							"value": "1",
							"disabled": true
						}
					],
					"variable": [
						{
							"key": "id",
							"value": "60d0fe4f5311236168a109f6"
						}
					]
				}
			},
			"response": []
		}
```
# GET
Get List By Tag
```json
		{
			"name": "Get List By Tag",
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
					"raw": "{\r\n\"data\": \"2023-09-02T17:00:40.575Z\",\r\n\"total\": 1,\r\n\"page\": 1,\r\n\"limit\": 1\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://dummyapi.io/data/v1/tag/:id/post",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"tag",
						":id",
						"post"
					],
					"query": [
						{
							"key": "tags",
							"value": "cat",
							"disabled": true
						}
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
# GET
Get Post by id
```json
		{
			"name": "Get Post by id",
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
					"raw": "{\r\n  \"firstName\": \"TestTest2\",\r\n  \"lastName\": \"TestTest2\"\r\n} ",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://dummyapi.io/data/v1/post/:id",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"post",
						":id"
					],
					"variable": [
						{
							"key": "id",
							"value": "60d21b3167d0d8992e610c47"
						}
					]
				}
			},
			"response": []
		}
```
# POST
Create Post
```json
		{
			"name": "Create Post",
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
					"raw": "{\r\n\"text\": \"smile\",\r\n\"image\": \"https://randomuser.me/api/portraits/med/women/15.jpg\",\r\n\"likes\": 10,\r\n\"tags\": \"cat\",\r\n\"owner\":\"64f34fd4a973971598b6a8bb\" \r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://dummyapi.io/data/v1/post/create",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"post",
						"create"
					]
				}
			},
			"response": []
		}
```
# PUT
Update Post
```json
		{
			"name": "Update Post",
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
					"raw": "{\r\n\"text\": \"text\",\r\n\"image\": \"https://randomuser.me/api/portraits/med/women/15.jpg\",\r\n\"likes\": 1000,\r\n\"tags\": \"qa\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://dummyapi.io/data/v1/post/:id",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"post",
						":id"
					],
					"variable": [
						{
							"key": "id",
							"value": "64f36a38ce4f016609344c4d"
						}
					]
				}
			},
			"response": []
		}
```
# DELETE
Delete Post
```json
		{
			"name": "Delete Post",
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
					"raw": "https://dummyapi.io/data/v1/post/:id",
					"protocol": "https",
					"host": [
						"dummyapi",
						"io"
					],
					"path": [
						"data",
						"v1",
						"post",
						":id"
					],
					"variable": [
						{
							"key": "id",
							"value": "64f36a38ce4f016609344c4d"
						}
					]
				}
			},
			"response": []
		}
```
